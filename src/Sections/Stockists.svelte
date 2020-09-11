<section id="our-stockists">

  <h1>Stockists</h1>

  <div class="stockists col4">
    <img src="/img/stockists/slice1.png" alt="">
    <img src="/img/stockists/slice2.png" alt="">
    <img src="/img/stockists/slice3.png" alt="">
    <img src="/img/stockists/slice4.png" alt="">
    <img src="/img/stockists/slice5.png" alt="">
    <img src="/img/stockists/slice6.png" alt="">
    <img src="/img/stockists/slice7.png" alt="">
    <img src="/img/stockists/slice8.png" alt="">
    <img src="/img/stockists/slice9.png" alt="">
    <img src="/img/stockists/slice10.png" alt="">
    <img src="/img/stockists/slice11.png" alt="">
    <img src="/img/stockists/slice12.png" alt="">
    <img src="/img/stockists/slice13.png" alt="">
    <img src="/img/stockists/slice14.png" alt="">
    <img src="/img/stockists/slice15.png" alt="">
  </div>
  <div class="stockists col3">
    <img src="/img/stockists/slice16.png" alt="">
    <img src="/img/stockists/slice17.png" alt="">
    <img src="/img/stockists/slice18.png" alt="">
    <img src="/img/stockists/slice19.png" alt="">
    <img src="/img/stockists/slice20.png" alt="">
    <img src="/img/stockists/slice21.png" alt="">
  </div>
  <div class="stockists col2">
    <img src="/img/stockists/slice22.png" alt="">
    <img src="/img/stockists/slice23.png" alt="">
  </div>

</section>

<style>

section {
  padding: 8vw 12vw 8.8vw; margin-bottom: 0;
  background: #FFD700;
}

h1 {
  position: relative;
  margin-bottom: 9vw;
  font-family: "Hamilton"; font-size: 8.5vw; text-transform: uppercase; line-height: 1em; text-align: center;
  font-weight: 700; letter-spacing: -0.03em;
}

h1:after {
  content: '';
  position: absolute; top: -3vw; left: 27.75vw;
  width: 5.7vw; height: 5.7vw;
  background: url('/img/stockist-h1-pea.svg') no-repeat;
}

h1:before {
  content: '';
  position: absolute; top: 8.25vw; left: 27.75vw;
  width: 6.1vw; height: 0.3vw;
  background: url('/img/stockist-h1-shadow.svg') no-repeat;
}

.stockists {
  display: flex;
  flex-wrap: wrap;
}

.stockists img {
  display: block;
  height: 10vw; flex-grow: 1; width: auto;
}


@media (min-width: 768px) {

  .stockists img {
    height: 11vw;

  }
  .stockists.col3 img, .stockists.col2 img {
    height: 10vw;
  }
}

</style>