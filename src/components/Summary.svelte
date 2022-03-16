<script>
    import Card from './Card.svelte'
</script>

<main>
    <Card
     title= "Entradas"
     amount= "17.400"
     isTotal= {false}
     />
     <Card
     title= "Saídas"
     amount= "1.259"
     isTotal= {false}
     />
     <Card
     title= "Total"
     amount= "16.141"
     isTotal={true}
     />
</main>

<style>
    main{
        position:absolute;
        display: flex;
        width: 80%;
        height: fit-content;
        align-items: center;
        justify-content: space-between;
    }
</style>