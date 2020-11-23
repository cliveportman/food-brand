<script>
  import SainsburysModal from '../Components/_sainsburysModal.svelte'
  let showSainsburysModal = false
</script>

<section id="our-stockists">

  <h1>Find the horde</h1>
  <div class="stockists col3">
    <img src="/img/ocado.png" alt="">
    <img src="/img/amazon.png" alt="">
    <img src="/img/nisa.png" alt="">
    <a href="https://www.sainsburys.co.uk/gol-ui/SearchDisplayView?filters[keyword]=Cheeky%20P%27s&&langId=44&storeId=10151&searchType=2&searchTerm=Cheeky%20P%27s"><img src="/img/sainsburys.svg" class="sainsburys" alt=""></a>
  </div>
  <a on:click|preventDefault="{ () => { showSainsburysModal = true }}" href="#" class="sainsburyslist">View list of Sainsbury's stores</a>

</section>

<SainsburysModal bind:display="{showSainsburysModal}"/>


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
img.sainsburys {
  margin-top: 4vw;
  height: 7vw;
}

@media (min-width: 768px) {
  .stockists.col3 img {
    height: 11vw;
  }
  .stockists.col3 img.sainsburys {
    height: 7vw;
  }
}


a.sainsburyslist {
  position: relative;
  display: block; color: #1D1E1B;
  margin-top: 4vw;
  font-family: "Hamilton"; font-size: 6.4vw; text-transform: uppercase; line-height: 1em; text-align: center;
  font-weight: 300; letter-spacing: -0.03em; text-decoration: underline;
}
a.sainsburyslist:hover {
  color: #f47320; cursor: pointer;
}

</style>