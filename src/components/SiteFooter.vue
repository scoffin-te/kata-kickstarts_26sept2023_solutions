<template>
    <footer>
        <p>&copy; Web Dev, {{ new Date().getFullYear() }}</p>
        <a href="https://linkedin.com" target="_blank">
            <img src="../../public/linkedin-logo.png" alt="linkedin-logo">
        </a>
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

    @import '../../public/styles.css';

    footer {
        align-items: center;
        background-color: var(--candy-apple);
        bottom: 0;
        color: var(--ghost);
        display: flex;
        height: 2.5rem;
        padding: 0 2rem;
    }

    footer p, footer a {
        height: 1rem;
        margin: 0;
        flex-basis: 50%;
    }

    footer a img {
        height: 1rem;
    }

    footer a {
        text-align: right;
    }
</style>