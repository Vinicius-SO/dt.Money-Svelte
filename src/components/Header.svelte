<script>
</script>

<main>
    <a href="/">
        <img src="\assets\Logo.svg" alt="">
    </a>
    <button>Nova transação</button>

</main>

<style>
    main{
        width: 80%;
        height: 5rem;
        margin: 2rem 0;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    img{
        max-width: 200px;
        max-height: 200px;
        cursor: pointer;
    }
    button{
        background: var(--blue-light);
        color: white;
        width: 12.188rem;
        height: 3rem;
        border-radius: 5px;
        font-size: 1rem;
        line-height: 1.5rem;
        font-weight: 600;
        font-family: 'Poppins', sans-serif;
        transition: .5s;
        cursor: pointer;
    }

    button:hover{
        transform: scale(1.1);
        filter: brightness(1.2);
    }
</style>