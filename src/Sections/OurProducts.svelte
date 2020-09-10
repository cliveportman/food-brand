<section>

  <div class="intro">
    <h1>Our Products</h1>
    <h2>
      <span class="left">Packed with <strong>flavour</strong></span>
      <img src="/img/divider.svg" alt="">
      <span class="right">Good for <strong>the gym</strong></span>
    </h2>
  </div>

  <div class="products">
    
    <a href="#" class="product">
      <img class="product-thumb" src="/img/cheeky-ps-barbque.jpg" alt="Cheeky P's bar-b-que">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>
    
    <a href="#" class="product">
      <img class="product-thumb" src="/img/cheeky-ps-cheese.jpg" alt="Cheeky P's cheese">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>
    
    <a href="#" class="product">
      <img class="product-thumb" src="/img/cheeky-ps-curry.jpg" alt="Cheeky P's curry">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>
    
    <a href="#" class="product">
      <img class="product-thumb" src="/img/cheeky-ps-chilli-lime.jpg" alt="Cheeky P's chilli & lime">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>

  </div>

  <div class="copy">

    <article>
      <h2 class="one"><strong>Here at Cheeky'Ps,</strong>We do not do things in half measures!</h2>
      <p>Our peas are guaranteed to provide you with that burst of flavour and oh-so-satisfying crunch that you'll love.</p>
    </article>

    <article>
      <h2 class="two"><strong>Guess what, that's not all!</strong></h2>
      <p>we made sure that our peas are not only scrumptious but packed with nutrients. With each serving offering more than 10g of muscle-building protein and 7g of fibre that your tummy will absolutely thank you for, we make healthy snacking an easy peasy thing for you!</p>
    </article>


  </div>
</section>


<style>





  section {
    position: relative;
    padding: 0 2.4vw 0;
  }

  h1 {
    position: absolute; z-index: 0; right: 6vw; top: -28vw;
    width: 33vw;  
    font-family: "Jomhuria"; font-size: 13vw; text-transform: uppercase; line-height: 0.5em; text-align: center;
    font-weight: 700; letter-spacing: 0.02em;
  }
  h1:before {
    position: absolute; right: -13vw; top: -25vw; z-index: -1;
    content: '';
    width: 65vw;
    height: 60vw;
    background: #F0EEE8;
    border-radius: 66vw 0 0 0;
    -moz-border-radius: 66vw 0 0 0;
    -webkit-border-radius: 66vw 0 0 0;
  }

  .intro h2 {
    position: relative; z-index: 1;  width: 70vw;
    margin: 6.2vw auto 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-family: "Jomhuria"; font-size: 10vw; text-transform: uppercase; line-height: 0.6em; text-align: center;
  }
@media (min-width: 768px) {
  .intro h2 {
    width: 44vw;
    font-size: 6vw;
  }
}
  .intro h2 span {
    display: block;
  }

  .intro h2 span strong {
    display: block; font-weight: 700; }

  .intro h2 span.left {
    padding-top: 0.6vw;
    letter-spacing: -0.01em;
  }
  .intro h2 span.left strong {
    font-size: 13vw; letter-spacing: 0.03em;
  }
  @media (min-width: 768px) {
    .intro h2 span.left strong {
      font-size: 8vw;
    }
  }

  .intro h2 span.right {
    padding-top: 0.7vw;
    font-size: 11vw;
  }
  @media (min-width: 768px) {
    .intro h2 span.right {
      font-size: 7vw;
    }
  }

  .intro h2 span.right strong {
    font-size: 11vw; letter-spacing: 0.03em;
  }
  @media (min-width: 768px) {
    .intro h2 span.right strong {
      font-size: 8vw;
    }
  }

  .intro h2 img {
    width: 0.84vw;
  }

.products {
  position: relative; z-index: 1;
  display: flex; justify-content: space-between;
  flex-wrap: wrap;
  margin: 0 0 11.7vw;
}

.product {
  display: block;
  width: 48%;
  padding: 0 0.5vw;
  text-decoration: none;
}
@media (min-width: 768px) {
.product {
  width: 24%;
}
}

  .product img.product-thumb {
    position: relative; bottom: -4vw;
    width: 100%;
    margin-bottom: 1vw;
    transition: bottom 0.3s;
    transition-delay: 0.3s;
  }

  .product:hover img.product-thumb {
    bottom: 0;
    transition-delay: 0s;
  }

  .product button {
    display: block; margin: 0 auto 1.6vw;
    padding: 0.75vw 1vw 0.25vw; border-radius: 0.5vw;
    background: #1D1E1B;
    border: none;
    font-family: "Jomhuria"; font-size: 3vw; text-transform: uppercase; line-height: 0.6em; text-align: center;color: #F0EEE8;
    letter-spacing: 0.025em;
    opacity: 0;
    transition: opacity 0.3s; transition-delay: 0s;
    cursor: pointer;
  }

  .product:hover button {
    opacity: 1;
    transition: opacity 0.3s; transition-delay: 0.3s;
  }

  .product img.shadow {
    display: block;
    width: 100%;
    padding: 0 1vw;
  }

  .copy {
    display: block;
  }


  article {
    margin: 0 0 5.9vw;
  }

  .copy h2 {
    font-family: "Jomhuria"; font-size: 8vw; text-transform: uppercase; line-height: 0.75em; text-align: center;
    letter-spacing: -0.01em; font-weight: 400;
    margin-bottom: 0.5vw;
  }
  @media (min-width: 768px) {
    .copy h2 {
      font-size: 6vw;
    }
  }

  .copy h2.one {
    
  }
  .copy h2.one strong {
    display: block;
    font-weight: 700;
    font-size: 12vw; letter-spacing: 0.03em;
  }
  @media (min-width: 768px) {
    .copy h2.one strong {
      font-size: 8vw;
    }
  }


  .copy h2.two {}
  .copy h2.two strong {
    font-size: 10vw;
  }
  @media (min-width: 768px) {
  .copy h2.two strong {
    font-size: 7vw;
  }
  }

  .copy p {
    margin: 0 auto;
    font-family: Abel; font-size: 4.2vw; font-weight: 400; line-height: 1.2em; text-align: center;
  }  
  @media (min-width: 768px) {
    .copy p {
      max-width: 55.9vw;
      font-size: 2.6vw;
    }
  }

</style>