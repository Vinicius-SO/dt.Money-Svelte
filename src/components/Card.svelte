<script>
    export let title
    export let amount
    export let isTotal

    const classe = isTotal ? 'total': 'normal'

</script>

<main class= {classe}>
    <div class="title">
        {title} 
    {#if title === 'Entradas'}
        <img src="\assets\income.svg" alt="">
    {:else if title === 'Saídas'}
        <img src="\assets\outcome.svg" alt="">
    {:else}
        <img src="\assets\Total.svg" alt="">
    {/if}

    </div>
    <div class="amount"> R$ <span>{amount}</span>,00</div>
</main>

<style>
    main{
        width: 25rem;
        height: 10rem;
        background: var(--shape);
        border-radius: 5px ;
        font-family: 'Poppins', sans-serif;
        padding: 1.5rem;
    }
    main.total{
        background: var( --green);
        color: var(--shape);

    }
    .title{
        display:flex;
        justify-content: space-between;
        margin-bottom: 1rem;
        font-weight: 400;
        color: var(--text-title);
    }
    .amount{
        font-size: 2.5rem;
        font-weight: 400;
    }
    span{
        font-weight: 600;
    }
</style>
