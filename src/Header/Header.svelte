<script>
  import { fade, fly } from 'svelte/transition';
  import SocialLinks from './SocialLinks.svelte';
  import Nav from './Nav.svelte';

  let displayMobileNav = true;
</script>


<header>
  <h1><img src="/img/cheeky-ps.svg" alt="Cheeky P's"></h1>

  <input id="burger" type="image" src="/img/burger.svg" on:click={() => displayMobileNav = !displayMobileNav}>

  <div class="links">  
    <SocialLinks />  
    <Nav />    
  </div>

  {#if displayMobileNav}
  <div id="smallnav" in:fly="{{ delay: 0, duration: 300, x: 0, y: -1000, opacity: 1 }}" out:fly="{{ delay: 0, duration: 300, x: 0, y: -1000, opacity: 1 }}">
    <input id="smallnav-close" type="image" src="/img/burger-close.svg" on:click={() => displayMobileNav = !displayMobileNav}>
    <a href="#products" class="medium">Products</a>
    <a href="#our-story" class="light">Our Story</a>
    <a href="#sustainability" class="medium">Sustainability</a>
    <a href="#stockists" class="bold">Stockists</a>
    <a href="#" class="basket"><img src="/img/basket.svg" alt="Basket"></a>
    <div class="sociallinks">
      <a href=""><img src="img/instagram.svg" alt="Instagram"></a>
      <a href=""><img src="img/twitter.svg" alt="Twitter"></a>
      <a href=""><img src="img/facebook.svg" alt="Facebook"></a>
    </div>
  </div>
  {/if}

</header>


<style>

  header {
    position: relative;
    padding: 5vw;
    background: #00BCB5;
  }

  h1 {
    width: 57vw;
    margin: 0 auto;
  }

  #burger {
    position: absolute; top: 4vw; right: 4vw;
    width: 8.9vw;
  }

  #smallnav {
    position: fixed; left: 0; top: 0; right: 0; bottom: 0; z-index: 9999;
    padding-top: 20vw;
    background: #00BCB5;
    border-left: 7.1vw solid #F0EEE8; border-right: 7.1vw solid #F0EEE8;
  }

  #smallnav a {
    position: relative; top: 0;
    display: block;
    padding: 2vw;
    font-family: "Hamilton"; letter-spacing: -0.03em; font-size: 12vw; line-height: 1em; color: #1D1E1B;
    text-decoration: none; text-transform: uppercase; font-weight: 500; text-align: center;
    transition: all 0.3s linear;
  }
  #smallnav a.light {
    font-weight: 300;
  }
  #smallnav a.medium {
    font-weight: 500;
  }
  #smallnav a.bold {
    font-weight: 700;
  }

  .basket img {
    width: 20vw;
  }

  .sociallinks {
    display: flex; justify-content: center;
  }
  .sociallinks a {
    display: block;
  }
  .sociallinks a img {
    width: 8vw;
  }

  a:focus, #smallnav a:hover, a:active {
    top: -2px;
    animation: shake 0.3s;
  }

  #smallnav-close {
    position: absolute; top: 4vw; right: 4vw;
    width: 8.9vw;
  }



  @media (min-width: 768px) {
  }

  .links { display: none; }



  @media (min-width: 768px) {
    header {
      padding: 2.4vw;
      display: flex;
      justify-content: space-between;
    }
    h1 {
      width: 24.1vw;
    }
    #burger, #smallnav { display: none; }
    .links { display: block; }
  }





  @keyframes shake {
  0% { transform: translate(1px, 1px) rotate(0deg); }
  10% { transform: translate(-1px, -1px) rotate(-1deg); }
  20% { transform: translate(-1px, 0px) rotate(1deg); }
  30% { transform: translate(1px, 1px) rotate(0deg); }
  40% { transform: translate(1px, -1px) rotate(1deg); }
  50% { transform: translate(-1px, 2px) rotate(-1deg); }
  60% { transform: translate(-1px, 1px) rotate(0deg); }
  70% { transform: translate(1px, 1px) rotate(-1deg); }
  80% { transform: translate(-1px, -1px) rotate(1deg); }
  90% { transform: translate(1px, 1px) rotate(0deg); }
  100% { transform: translate(1px, -1px) rotate(-1deg); }
}
</style>