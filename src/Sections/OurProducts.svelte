<section>

  <div class="intro">
    <h1 id="our-products">Our Products</h1>
    <h2 data-aos="fade-up">
      <span class="left">Packed with <strong>flavour</strong></span>
      <img src="/img/divider.svg" alt="">
      <span class="right">Good for <strong>the gym</strong></span>
    </h2>
  </div>

  <div class="products">
    
    <a href="https://shop.cheekyps.co.uk/collections/home-page/products/bar-b-que-12x50g" class="product" data-aos="fade-up">
      <img class="product-thumb" src="/img/cheeky-ps-barbque.jpg" alt="Cheeky P's bar-b-que">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>
    
    <a href="https://shop.cheekyps.co.uk/collections/home-page/products/cheese-12x50g" class="product" data-aos="fade-up" data-aos-delay="50">
      <img class="product-thumb" src="/img/cheeky-ps-cheese.jpg" alt="Cheeky P's cheese">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>
    
    <a href="https://shop.cheekyps.co.uk/collections/home-page/products/curry-12x50g" class="product" data-aos="fade-up" data-aos-delay="100">
      <img class="product-thumb" src="/img/cheeky-ps-curry.jpg" alt="Cheeky P's curry">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>
    
    <a href="https://shop.cheekyps.co.uk/collections/home-page/products/chilli-lime-12x50g" class="product" data-aos="fade-up" data-aos-delay="150">
      <img class="product-thumb" src="/img/cheeky-ps-chilli-lime.jpg" alt="Cheeky P's chilli & lime">
      <button>Buy now</button>
      <img class="shadow" src="/img/packet-shadow.svg" alt="">
    </a>

  </div>

  <div class="copy" id="our-story" data-aos="fade-up">

    <article>
      <h2 class="one" data-aos="fade-up"><strong>We are the Cheeky P's,</strong>We're rebels against monotony.<br>We riot against boring.</h2>
      <p data-aos="fade-up">Our aim is to bring mischief into the everyday life of snack lovers everywhere, with a little help from the not-so humble chickpea.</p>
      <p data-aos="fade-up">We're a spark of life, a full-bellied laugh, a good-natured dig in the ribs. And we can be a right pain in the a**e when we want to be.</p>
      <p data-aos="fade-up">Our chickpea snacks play mayhem with the mundane. Bold? Yes. Brazen? Undoubtedly. We're full of ourselves, impressively packed with protein and fibre, and shamelessly tasty to boot.</p>
      <p data-aos="fade-up">We're immodestly adaptable. Good for the gym, delicious with dinner and perfect with a pint, we make any occasion a little bit more cheeky than you'd bargained for.</p>
      <p data-aos="fade-up"><strong>Not convinced? The cheek of it.</strong></p>
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
    font-size: 9.2vw; text-transform: uppercase; line-height: 0.8em; text-align: center;
    font-weight: 700; 
    font-family: "Hamilton"; letter-spacing: -0.03em;
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
  font-family: "Hamilton"; letter-spacing: -0.03em; font-size: 10vw; 
  text-transform: uppercase; line-height: 0.8em; text-align: center;
}
.intro h2 span {
  display: block;
  font-weight: 300;
}
.intro h2 span strong {
  display: block; font-weight: 700; 
}
.intro h2 span.left {
  padding-top: 0.6vw;
}
.intro h2 span.left strong {
  font-size: 9vw;
}

@media (min-width: 768px) {
  .intro h2 {
    width: 44vw;
    font-size: 6.5vw;
  }
  .intro h2 span {
    display: block;
  }
    .intro h2 span.left strong {
      font-size: 5.8vw;
    }
}




.intro h2 span.right {
  padding-top: 0.7vw;
  font-size: 11vw;
}

.intro h2 span.right strong {
  font-size: 8vw;
}
  @media (min-width: 768px) {
    .intro h2 span.right {
      font-size: 7.1vw;
    }
    .intro h2 span.right strong {
      font-size: 5.4vw;
    }
  }

  .intro h2 img {
    width: 1.2vw;
  }
  @media (min-width: 768px) {
  .intro h2 img {
    width: 0.84vw;
  }
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
    padding: 3vw 3vw 1.5vw; border-radius: 0.5vw;
    background: #1D1E1B;
    border: none;
    font-family: "Hamilton"; font-size: 8vw; text-transform: uppercase; line-height: 0.8em; text-align: center;color: #F0EEE8;
    letter-spacing: -0.03em;
    opacity: 0;
    transition: opacity 0.3s; transition-delay: 0s;
    cursor: pointer;
  }

  @media (min-width: 768px) {
    .product button {
      padding: 1vw 2vw 1vw;
      font-size: 3vw;
    }
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
    font-family: "Hamilton"; font-size: 7.6vw; text-transform: uppercase; line-height: 1.2em; text-align: center;
    letter-spacing: -0.03em; font-weight: 300;
    margin-bottom: 2vw;
  }
  @media (min-width: 768px) {
    .copy h2 {
      font-size: 4.9vw;
    }
  }

  .copy h2.one {
    
  }
  .copy h2.one strong {
    display: block;
    font-weight: 700;
    font-size: 10vw; 
  }
  @media (min-width: 768px) {
    .copy h2.one strong {
      font-size: 6.1vw;
    }
  }


  .copy h2.two {}
  .copy h2.two strong {
    font-size: 8vw; font-weight: 500;
  }
  @media (min-width: 768px) {
  .copy h2.two strong {
    font-size: 5.2vw;
  }
  }

  .copy p {
    margin: 0 auto 2vw;
    font-family: Abel; font-size: 4.2vw; font-weight: 400; line-height: 1.2em; text-align: center;
  } 
  .copy p strong {
    font-family: "Hamilton"; font-size: 7.6vw; text-transform: uppercase; line-height: 1.2em; text-align: center;
    letter-spacing: -0.03em; font-weight: 300;
  }
  @media (min-width: 768px) {
    .copy p {
      max-width: 72vw;
      font-size: 2.6vw;
    }
    .copy p strong { 
      font-size: 4.9vw;
    }
  }

</style>
