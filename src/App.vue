<template>
  <div id="app">
    <site-header />
    <router-view />
    <site-footer />
  </div>
</template>

<script>
  import SiteHeader from './components/SiteHeader';
  import SiteFooter from './components/SiteFooter';
  export default {
    components: {
      SiteHeader,
      SiteFooter
    }
  }
</script>

<style>
  @import '../public/styles.css';

  body {
    background-color: var(--jack-o-lantern);
    height: 100vh;
    margin: 0;
  }

  #app {
    color: var(--black-cat);
    display: flex;
    flex-direction: column;
    width: 100%;
  }

  @media screen and (min-width: 750px) {
    #app {
      height: 100vh;
    }
  }
</style>