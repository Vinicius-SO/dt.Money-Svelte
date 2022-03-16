<script>
  import Dashboard from './components/Dashboard.svelte';
  import HeaderContainer from './components/HeaderContainer.svelte';
</script>

<main>
  <HeaderContainer/>
  <Dashboard/>
</main>


<style>

  :global(html){
        --background: #f0f2f5;
        --red: #e52e4d;
        --blue: #5429CC;
        --green: #33cc95;

        --blue-light: #6933ff;

        --text-title: #363F5F;
        --text-body: #969CB3;

        --shape: #FFFFFF;

  }
    
  :global(*){
      margin:0;
      padding:0;
      box-sizing:border-box;
      border: none;
  }

  main{
      margin: 0 auto;
      background: var(--background);
      width: 100vw;
      height: 100vh;
      
  }
</style>
