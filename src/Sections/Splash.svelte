<script>
  import { fade, fly } from 'svelte/transition';
	import { expoInOut } from 'svelte/easing';

  let visible = false;
  setTimeout(function(){ 
    visible = true; 
  }, 0);

</script>


<section>
  {#if visible}
    <h1 in:fade="{{ delay: 900, duration: 900, easing: expoInOut }}">The Not So<br> Humble Chickpea</h1>
    <img in:fade="{{ delay: 1800, duration: 600, easing: expoInOut }}" id="splash-fibre" src="/img/high-in-protein-and-fibre.svg" alt="High in protein and fibre">
    <img in:fade="{{ delay: 1900, duration: 600, easing: expoInOut }}" id="splash-vegans" src="/img/vegans-love-us.svg" alt="Vegans love us!">
    <!--
    <img in:fly="{{ delay: 350, duration:400, x: 1200, y: -200, opacity: 1 }}" id="splash-p2" src="/img/splash-p2.svg" alt="">
    <img in:fly="{{ delay: 400, duration:300, x: 800, opacity: 1 }}" id="splash-p5" src="/img/splash-p5.svg" alt="">
    <img in:fly="{{ delay: 500, duration:500, x: 1000, opacity: 1 }}" id="splash-p4" src="/img/splash-p4.svg" alt="">
    <img in:fly="{{ delay: 300, duration:300, x: -1700, y: -400, opacity: 1 }}" id="splash-p3" src="/img/splash-p3.svg" alt="">
    <img in:fly="{{ delay: 250, duration:300, x: 800, opacity: 1 }}" id="splash-p6" src="/img/splash-p6.svg" alt="">
    <img in:fly="{{ delay: 600, duration:600, x: 1300, y: 300, opacity: 1 }}" id="splash-p1" src="/img/splash-p1.svg" alt="">
    -->
    <img in:fly="{{ delay: 350, duration:400, x: 0, y: -1800, opacity: 1 }}" id="splash-p2" src="/img/splash-p2.svg" alt="">
    <img in:fly="{{ delay: 400, duration:300, x: 0, y: -1800, opacity: 1 }}" id="splash-p5" src="/img/splash-p5.svg" alt="">
    <img in:fly="{{ delay: 500, duration:500, x: 0, y: -1800, opacity: 1 }}" id="splash-p4" src="/img/splash-p4.svg" alt="">
    <img in:fly="{{ delay: 300, duration:300, x: 0, y: -1800, opacity: 1 }}" id="splash-p3" src="/img/splash-p3.svg" alt="">
    <img in:fly="{{ delay: 250, duration:300, x: 0, y: -1800, opacity: 1 }}" id="splash-p6" src="/img/splash-p6.svg" alt="">
    <img in:fly="{{ delay: 600, duration:600, x: 0, y: -1800, opacity: 1 }}" id="splash-p1" src="/img/splash-p1.svg" alt="">
  {/if}
</section>


<style>





  section {
    padding: 0 2.4vw 68.8vw;
    background: #00BCB5;
  }

    h1 {
      margin: 0 auto;
      font-size: 6.7vw; text-transform: uppercase; line-height: 0.8em; text-align: center;
      font-weight: 700;
      font-family: "Hamilton"; letter-spacing: -0.03em;
    }

    #splash-p1 {
      position: absolute; left: 21.5vw; margin-top: 1.6vw; z-index: 1;
      width: 29.3vw;    
    }
    #splash-p2 {
      position: absolute; left: 42vw; margin-top: 3.1vw; z-index: 1;
      width: 14.5vw;    
    }
    #splash-p3 {
      position: absolute; left: 46.5vw; margin-top: 21.6vw; z-index: 1;
      width: 18.35vw;    
    }
    #splash-p4 {
      position: absolute; left: 50.8vw; margin-top: 4.8vw; z-index: 1;
      width: 27.4vw;    
    }
    #splash-p5 {
      position: absolute; left: 73vw; margin-top: 12.3vw; z-index: 1;
      width: 19.6vw;    
    }
    #splash-p6 {
      position: absolute; left: 76.2vw; margin-top: -4vw; z-index: 1;
      width: 18vw;    
    }

    #splash-fibre {
      position: absolute; left: -1vw; margin-top: 7vw;
      width: 16.9vw;
    }

    #splash-vegans {
      position: absolute; left: 9.1vw; margin-top: 22.7vw;
      width: 15.6vw;
    }




</style>