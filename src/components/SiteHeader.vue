<template>
    <header>
        <div id="site-logo">
            <img src="../../public/site-logo.png" />
        </div>
        <nav id="header-nav">
            <a href="#">Home</a>
            <a href="#">About Us</a>
        </nav>
    </header>
</template>

<script>
export default {

}
</script>

<style scoped>
  @import '../../public/styles.css';
    header {
        align-items: center;
        color: var(--ghost);
        display: flex;
        background-color: var(--candy-apple);
        height: 4rem;
        padding: 0 2rem;
    }
    #site-logo, #header-nav {
        flex-basis: 50%;
        height: 3rem;
    }

    #site-logo img {
        height: 3rem;
    }

    #header-nav {
        align-items: center;
        display: flex;
        justify-content: flex-end;
    }

    #header-nav a {
        color: var(--ghost);
        display: inline-block;
        padding: 0 1rem;
        text-decoration: none;
    }

    #header-nav a:hover {
        text-decoration: underline;
    }
</style>