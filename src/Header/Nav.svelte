<script>

  
import * as animateScroll from "svelte-scrollto";



function scrollTo(id) {
    animateScroll.scrollTo({element: id, offset: -20})
  }
</script>

<nav>
  <a href="#our-products" class="medium"on:click|preventDefault="{() => scrollTo('#our-products')}">Products</a>
  <a href="#our-story" class="light"on:click|preventDefault="{() => scrollTo('#our-story')}">Our Story</a>
  <a href="#sustainability" class="medium"on:click|preventDefault="{() => scrollTo('#sustainability')}">Sustainability</a>
  <a href="#our-stockists" class="light"on:click|preventDefault="{() => scrollTo('#our-stockists')}">Stockists</a>
  <a href="https://cheeky-ps.myshopify.com/" class="bold">Shop</a>
</nav>

  


<style>

  nav {
    width: 47vw;
    display: flex; justify-content: space-between;
  }

  a {
    position: relative;
    display: inline;
    font-family: "Hamilton"; letter-spacing: -0.03em; font-size: 2.8vw; line-height: 1em; color: #1D1E1B;
    text-decoration: none; text-transform: uppercase; font-weight: 500;
    transition: top 0.3s; 
  }
  a.light {
    font-weight: 300;
  }
  a.medium {
    font-weight: 500;
  }
  a.bold {
    font-weight: 700;
  }

  a:focus, a:hover, a:active {
    top: -5px;
  }


  </style>