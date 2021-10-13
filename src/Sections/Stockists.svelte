<script>
  import SainsburysModal from '../Components/_sainsburysModal.svelte'
  let showSainsburysModal = false
</script>

<section id="our-stockists">

  <h1>Find the horde</h1>
  <div class="stockists col3">
    <a target="_blank" href="https://www.ocado.com/search?entry=Cheeky%20P%27s"><img src="/img/ocado.png" alt=""></a>
    <img src="/img/amazon.png" alt="">
    <img src="/img/nisa.png" alt="">
    <a target="_blank" href="https://www.hollandandbarrett.com/search/?isSearch=true&query=Cheeky%20P%27s"><img src="/img/holland-barrett.png" alt="Holland & Barratt" class="hollandbarrett"></a>
    <img src="/img/booths.png" alt="Booths" class="booths">
    <a target="_blank" href="https://proteinpackage.co.uk/search?q=Cheeky+P%27s"><img src="/img/protein-package.png" class="protein" alt="Protein Package"></a>
    <a target="_blank" href="https://thevegankind.com/search?query=Cheeky%20P%27s"><img src="/img/the-vegan-kind.svg" class="vegankind" alt="The Vegan Kind"></a>
    
    <a target="_blank" href="https://www.sainsburys.co.uk/gol-ui/SearchDisplayView?filters[keyword]=Cheeky%20P%27s&&langId=44&storeId=10151&searchType=2&searchTerm=Cheeky%20P%27s"><img src="/img/sainsburys.svg" class="sainsburys" alt=""></a>
  </div>
  <a on:click|preventDefault="{ () => { showSainsburysModal = true }}" href="#" class="sainsburyslist">View list of Sainsbury's stores</a>

</section>

<SainsburysModal bind:display="{showSainsburysModal}"/>


<style>

section {
  padding: 8vw 2vw 8.8vw; margin-bottom: 0;
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
  justify-content: center; align-items: center;
}

.stockists img {
  display: block;
  height: 12vw; width: auto;
  margin: 0 0.5rem 2rem;
  
}
img.sainsburys {
  margin-top: 2vw; margin-bottom: 0;
  height: 10vw;
}
img.hollandbarrett {
  height: 10vw;
}
img.booths {
  margin: 0 1rem 2rem 0;
}
img.protein {
  height: 16vw;
  margin: 0 1rem 2rem 0;
}
img.vegankind {
  height: 12vw;
}

@media (min-width: 768px) {
section {
  padding: 8vw 12vw 8.8vw; margin-bottom: 0;
  background: #FA364A;
}
  .stockists.col3 img {
    height: 11vw;
  }
  .stockists.col3 img.sainsburys {
    height: 7vw;
  }
  .stockists.col3 img.hollandbarrett {
    height: 6vw;
    margin: 4rem 4rem 2rem 0;
  }
  .stockists.col3 img.booths {
    height: 7vw;
    margin: 4rem 4rem 2rem 0;
  }
  .stockists.col3 img.protein {
    height: 9vw;
    margin: 0 4rem 0 0;
  }
  .stockists.col3 img.vegankind {
    height: 8vw;
    margin: 0;
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