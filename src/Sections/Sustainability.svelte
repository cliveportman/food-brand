<style>

:global(#raisedsofar-fill.aos-animate) {

  /* THIS IS THE ALL IMPORTANT LINE. UPDATE THE PERCENTAGE ONLY */
  height: calc(50% * 0.9);

}
  
  
:global(#raisedsofar-fill) {
  position: absolute; bottom: 1px; left: 1px; right: 1px; z-index: 4;
  height: 0;
  background: #FFD700;
}






  section {
    padding: 10vw 5vw 8.8vw; margin-bottom: 1.8vw;
    background: #FC5412;
  }
  @media (min-width: 768px) {
    section {
    padding: 6vw 15vw 8.8vw;
    }
  }
  
  @media (min-width: 768px) {
  .articles {
    display: flex;
    justify-content: space-between;
    align-items: stretch;
  }
  }
  
  .divider {
    display: none;
  }
  @media (min-width: 768px) {
  .divider {
    display: block;
    flex: 0 0 0.75vw;
  }
  }
  
  article {
    flex: 0 0 23.5vw;
  }
  
  article img {
    width: 100%; display: block;
    max-width: 40vw; margin: 2vw auto 10vw;
  }
  @media (min-width: 768px) {
    article img {
    max-width: auto;
    margin: 0;
  }
  }
  
  article.left h2 {
    font-family: "Hamilton"; text-transform: uppercase; letter-spacing: -0.03em;
    line-height: 0.8em; text-align: center; font-size: 10vw;
    margin-bottom: 3vw;
  }
  
  article.left h2 .one {
    font-size: 13vw;
    font-weight: 300;
  }
  article.left h2 .one strong {
    font-weight: 500; letter-spacing: -0.03em;
  }
  article.left h2 .two {
    display: block;
    font-weight: 400;
  }
  article.left h2 .two strong {
    font-size: 11vw;
    font-weight: 500;
  }
  article.left h2 .three {
    font-weight: 300; 
    font-size: 10vw;
  }
  
  article.left p, article.right p {
    margin: 0 auto 6vw;  width: 43vw;
    font-family: "Hamilton"; text-transform: none; text-align: left;
    letter-spacing: -0.03em; line-height: 1em; font-size: 5vw; font-weight: 300;
    
  }
  article.left p a, article.right p a {
    text-transform: none; color: inherit; text-decoration: none; font-weight: 500;     letter-spacing: -0.06em;
  }
  
  @media (min-width: 768px) {
  article.left {
    padding-right: 4vw; position: relative; right: -2vw;
    background: url("/img/sustainability-divider.svg") repeat-y;
    background-position: right top;
    background-size: 1vw;
  }
  article.left h2 {
    line-height: 4.5vw; font-size: 6.2vw;
  }
  article.left h2 .one {
    font-size: 6.6vw; 
    font-weight: 300; 
  }
  article.left h2 .one strong {
  }
  article.left h2 .two {
    padding-top: 0.75vw;
  }
  article.left h2 .two strong {
    font-size: 5.6vw; 
  }
  article.left h2 .three {
    font-size: 4.9vw; letter-spacing: -0.03em; 
  }
  
  
  
  article.left p, article.right p {
    margin-bottom: 2vw; width: auto;
    font-family: "Hamilton"; text-transform: none; text-align: left;
    letter-spacing: -0.03em; line-height: 1em; font-size: 2.5vw; font-weight: 300;
    
  }
  article.left p a, article.right p a {
    text-transform: none; color: inherit; text-decoration: none; font-weight: 500;     letter-spacing: -0.06em;
  }
  
  article.left a {
    display: block; margin-top: 2vw;
  }
  }
  
  
  article.right {}
  article.right h2 {
    font-family: "Hamilton"; text-transform: uppercase; text-align: center;
    letter-spacing: -0.03em; line-height: 0.65; font-size: 10vw;
    margin-bottom: 3vw;
  }
  article.right h2 .one {
    font-weight: 300; 
  }
  article.right h2 .one strong {
    display: block;
    font-weight: 500; letter-spacing: -0.03em; font-size: 12vw;
  }
  article.right h2 .two {
    font-weight: 300; letter-spacing: -0.03em; line-height: 1em;
  }
  article.right h2 .three strong {
    display: block;
    font-size: 11vw;
    font-weight: 500; letter-spacing: -0.03em; 
  }
  
  
  #raisedsofar {
    padding: 1vw 0; margin-bottom: 4vw;
    display: flex; justify-content: center; align-items: center
  }
  #raisedsofar p {
    padding-right: 0; margin-left: 0; margin-right: 0; width: 38vw;
    margin-bottom: 0; text-transform: uppercase; font-size: 7.2vw;
  }
  #raisedsofar p span {
    letter-spacing: -0.06em; font-weight: 300;
  }
  #raisedsofar p strong {
    display: block; font-size: 16vw; line-height: 0.9em;
  }
  #raisedsofar-filler {
    position: relative; width: 22vw; align-items: flex-start
  }
  #raisedsofar-filler img {
    position: relative; z-index: 5; margin-bottom: 0; width: 22vw;
  }

  @media (min-width: 768px) {
    #raisedsofar { justify-content: space-between;   }
    #raisedsofar-filler img { width: 10vw; }
  }
  
  
  @media (min-width: 768px) {
  article.right h2 {
    line-height: 4.75vw; font-size: 6vw;
  }
  article.right h2 .one strong {
    font-size: 6.5vw;
    font-weight: 500;
  }
  article.right h2 .two {
    font-size: 5.4vw; line-height: 1em;
  }
  article.right h2 .three strong {
    font-size: 5.8vw;
    font-weight: 500;
  }
  
  #raisedsofar {
    margin-bottom: 2vw;
  }
  #raisedsofar p {
    width: auto; margin: 0;
    font-size: 2.5vw; padding-right: 2vw;
  }
  #raisedsofar p strong {
    display: block; font-size: 5.6vw; line-height: 0.9em;
  }
  #raisedsofar-filler {
    position: relative; width: auto; align-items: flex-start
  }
  
  }
  
  </style>



<section id="sustainability">

  <div class="articles">

    <article class="left">
      <h2 data-aos="fade-up">
        <span class="one">We <strong>Only</strong> use</span>
        <span class="two"><strong>sustainably</strong></span>
        <span class="three">sourced palm oil</span>
      </h2>
      <p data-aos="fade-up">Although palm oil has received its
        fair share of bad press, we strongly
        believe that sustainably sourced
        palm oil is currently still the way to
        go as it provides the highest yield
        compared to its substitutes. Rival
        crops like rapeseed need as much
        as 6 times of land to produce the
        same volume of oil! This is why we
        chose to use only deforestation
        free palm oil certified by RSPO. </p>
    </article>


    <article class="right">
      <h2 data-aos="fade-up" data-aos-delay="50">
        <span class="one"><strong>Every pack</strong></span>
        <span class="two">purchased helps</span>
        <span class="three"><strong>plant trees</strong></span>
      </h2>
      <p data-aos="fade-up" data-aos-delay="50">Purchase a case of Cheeky P's and we'll
        donate £1 to WLT's Plant A Tree project
        to help restore forests for wildlife</p>
      <div id="raisedsofar" data-aos="fade-up" data-aos-delay="50">
        <p>So far, we've raised <strong>£4,900</strong> <span>of our £10,000 target</span></p>
        <div id="raisedsofar-filler">
          <div id="raisedsofar-fill" data-aos="fill-up" data-aos-delay="300" data-aos-duration="1000"></div>
          <img src="/img/empty-chickpea.svg" alt="">
        </div>
      </div>
      <p data-aos="fade-up" data-aos-delay="50">To find out more or make a direct contribution, <a href="#" target="_blank">please click here.</a></p>
      </article>
  </div>

</section>
