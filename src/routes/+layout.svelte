<header>

</header>

<main>
    <slot/>
</main>

<footer>

</footer>

<style>
    header{
        height: 10vh;
        background-color: #444;
    }
    main{
        display: flex;
        flex-direction: column;
        min-height: 85vh;
        background-color: #a0a0a0;
        padding: 5em;
        gap: 5em;
        max-width: 100vw;
    }
    footer{
        height: 5vh;
        background-color: #444;
    }
</style>