

<svelte:head>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js" on:load={aosLoaded}></script>
</svelte:head>

<script>
  import { onMount } from 'svelte';
  let aosReady = false;
  let mounted = false;
   
  onMount(() => {
      mounted = true;
      if (aosReady) {
        setTimeout(initAos(), 2000);
      }
  });

  function aosLoaded() {
      aosReady = true;
      if (mounted) {
        setTimeout(initAos(), 2000);
      }
  }

  function initAos() {
    AOS.init({
      useClassNames: true
    });
  }




  import Header from './Header/Header.svelte';
  import Splash from './Sections/Splash.svelte';
  import OurProducts from './Sections/OurProducts.svelte';
  import Sustainability from './Sections/Sustainability.svelte';
  import Stockists from './Sections/Stockists.svelte';
  import Contacts from './Sections/Contacts.svelte';
  import Footer from './Footer/Footer.svelte';
</script>

<div class="container">
  <main>
    <Header />
    <Splash />
    <OurProducts />
    <Sustainability />
    <Stockists />
    <Contacts />
  </main>
</div>
<Footer />

<style>

  main {
    flex: 1;
    margin: 0 7vw;
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