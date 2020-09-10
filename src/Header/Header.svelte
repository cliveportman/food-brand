<script>
  import SocialLinks from './SocialLinks.svelte';
  import Nav from './Nav.svelte';
</script>


<header>
  <h1><img src="/img/cheeky-ps.svg" alt="Cheeky P's"></h1>

  <div class="links">  
    <SocialLinks />  
    <Nav />    
  </div>

</header>


<style>

  header {
    padding: 2.4vw;
    background: #00BCB5;
    display: flex;
    justify-content: space-between;
  }

  h1 {
    width: 24.1vw;
  }
</style>