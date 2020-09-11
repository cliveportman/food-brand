<script>



  import Header from './Header/Header.svelte';
  import Splash from './Sections/Splash.svelte';
  import OurProducts from './Sections/OurProducts.svelte';
  import Sustainability from './Sections/Sustainability.svelte';
  import Stockists from './Sections/Stockists.svelte';
  import Contacts from './Sections/Contacts.svelte';
  import Footer from './Footer/Footer.svelte';
</script>

<div class="container">
  <div class="spacer left"></div>
  <main>
    <Header />
    <Splash />
    <OurProducts />
    <Sustainability />
    <Stockists />
    <Contacts />
  </main>
  <div class="spacer right"></div>
</div>
<Footer />

<style>

  main {
    flex: 1;
    background: #F0EEE8;
  }
  
	@media (min-width: 768px) {
    main {
      position: relative;
      padding: 0;
    }
  }

  .container {
    display: flex;
    width: 100%; overflow: hidden;
  }
  .spacer {
    width: 7vw;
  }
  @media (min-width: 768px) {
    .spacer {
      width: 7vw;
    }
  }
  .spacer.left {
    background: #F0EEE8;
  }
  .spacer.right {
    background: #F0EEE8;
    
  }

</style>