<section id="our-stockists">

  <h1 data-aos="fade-up">Find the horde</h1>
  <div class="stockists col3">
    <img src="/img/ocado.png" alt="" data-aos="fade-up">
    <img src="/img/amazon.png" alt="" data-aos="fade-up" data-aos-delay="50">
    <img src="/img/nisa.png" alt="" data-aos="fade-up" data-aos-delay="100">
  </div>
  <p>& many more independents!</p>

</section>

<style>

section {
  padding: 8vw 12vw 8.8vw; margin-bottom: 0;
  background: #FA364A;
}

h1 {
  position: relative;
  margin-bottom: 4vw;
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
  justify-content: center;
}

.stockists img {
  display: block;
  height: 10vw; width: auto;
}


@media (min-width: 768px) {
  .stockists.col3 img {
    height: 11vw;
  }
}


p {
  position: relative;
  margin-top: 4vw;
  font-family: "Hamilton"; font-size: 6.4vw; text-transform: uppercase; line-height: 1em; text-align: center;
  font-weight: 300; letter-spacing: -0.03em;
}

</style>