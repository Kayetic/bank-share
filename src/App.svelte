<script>
    import "./app.css";
    import Detail from "./Detail.svelte";
</script>

<main>
    <Detail name="John Doe" sortCode="12-34-56" accountNumber="78008093"
    ></Detail>
    <Detail name="Bartosz Bak" sortCode="98-19-77" accountNumber="98562028"
    ></Detail>
</main>

<style>
    main {
        padding: 3rem;

        display: flex;
        flex-direction: column;
        gap: 1.5rem;
    }
</style>
