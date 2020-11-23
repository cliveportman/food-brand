<script>

  export let display = false

</script>

{#if display}
  <div class="overlay" on:click="{ () => { display = !display } }">
    <div class="content">
      
      <h1>Find us in Sainsbury's</h1>
      <div class="closebutton" on:click="{ () => { display = !display } }">✖</div>
      <ul>
        <li>Alphington Rd</li>
        <li>Alton</li>
        <li>Apsley Mills</li>
        <li>Badger Farm</li>
        <li>Bagshot Rd</li>
        <li>Bath</li>
        <li>Bramingham Park</li>
        <li>Brentwood</li>
        <li>Broadcut</li>
        <li>Brookwood</li>
        <li>Burpham</li>
        <li>Bury St Edmunds</li>
        <li>Bybrook</li>
        <li>Calcot</li>
        <li>Camden</li>
        <li>Chichester</li>
        <li>Chippenham</li>
        <li>Chiswick</li>
        <li>Christchurch</li>
        <li>Crayford</li>
        <li>Dulwich</li>
        <li>East Grinstead</li>
        <li>Emersons Grn</li>
        <li>Godalming</li>
        <li>Hampden Park</li>
        <li>Hankridge Farm</li>
        <li>Harringay</li>
        <li>Haywards Heath</li>
        <li>Hedge End</li>
        <li>Hempstead Valley</li>
        <li>Heyford Hill</li>
        <li>Islington</li>
        <li>Kempshott</li>
        <li>Kidderminster</li>
        <li>Kidlington</li>
        <li>Kiln Lane</li>
        <li>Ladbroke Grove</li>
        <li>Marsh Mills</li>
        <li>Marshall Lake</li>
        <li>Mere Grn</li>
        <li>Merton</li>
        <li>Moortown</li>
        <li>North Cheam</li>
        <li>Pepper Hill</li>
        <li>Purley Way</li>
        <li>Rayleigh Weir</li>
        <li>Richmond</li>
        <li>Rustington</li>
        <li>Sedlescombe Rd</li>
        <li>Sevenoaks</li>
        <li>Shorehead</li>
        <li>Shrewsbury</li>
        <li>Springfield</li>
        <li>St Albans</li>
        <li>St Clares</li>
        <li>Staines</li>
        <li>Stanway</li>
        <li>Sydenham</li>
        <li>Tonbridge</li>
        <li>Torquay</li>
        <li>Tunbridge Wells</li>
        <li>Wallington</li>
        <li>Warlingham</li>
        <li>Warren Heath</li>
        <li>Water Lane</li>
        <li>Weedon Rd</li>
        <li>West Hove</li>
        <li>Winchmore Hill</li>
        <li>Winnersh</li>
        <li>Witney</li>
      </ul>

    </div>
  </div>
{/if}

<style>
  .overlay {
    position: fixed; top: 0; right: 0; bottom: 0; left: 0; z-index: 9999;
    background: rgba(0,0,0,0.7);
    display: flex; justify-content: center; align-items: center;
  }
    .content {
      width: 100%; max-width: 90vw;
        max-height: 90vh;
      position: relative;
      padding: 4vw 4vw 0;
      background: #F0EEE8;
        overflow: auto;
    }
    .closebutton{
      position: absolute; right: 4vw; top: 6vw;
      font-size: 10vw; cursor: pointer;
    }
    @media (min-width: 768px) {
      .content {
        max-height: 90vh;
      width: 100%; max-width: 80vw;
      padding: 3vw 2vw 2vw;
      }
      .closebutton{
        position: absolute; right: 1.5vw; top: 3vw;
        font-size: 5vw;
      }
    }

    h1 {
    font-size: 8vw; text-transform: uppercase; line-height: 0.8em; text-align: left;
    font-weight: 700; 
    font-family: "Hamilton"; letter-spacing: -0.03em;
    }
      ul {
        padding: 3vw 0 2vw;
        column-count: 2;
        list-style-type: none;
      }

    li {
      margin: 0 auto 0.25em;
      font-family: Abel; font-size: 4vw; font-weight: 700; line-height: 1.2em; text-align: center;
      text-align: left;
    } 
    
    @media (min-width: 768px) {
      h1 {
        margin-bottom: 2vw;
        font-size: 4vw; text-align: center;
      }

      ul {
        padding: 1vw;
        column-count: 3;
        list-style-type: none;
      }
      li {
        font-size: 1.5vw;
      }
    }
    
    @media (min-width: 1024px) {
      h1 {
        margin-bottom: 2vw;
        font-size: 5vw; text-align: center;
      }

      ul {
        padding: 1vw 2vw 2vw;
        column-count: 4;
        list-style-type: none;
      }
      li {
        font-size: 1.3vw;
      }
    }


</style>