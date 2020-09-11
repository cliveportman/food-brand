<section>

  <h1>Sustainability story</h1>

  <div class="articles">

    <article class="left">
      <h2>
        <span class="one">We <strong>Only</strong> use</span>
        <span class="two"><strong>sustainably</strong></span>
        <span class="three">sourced palm oil</span>
      </h2>
      <a href="#">
        <img src="/img/palm-oil-logo.png" alt="">
      </a>
    </article>

    <img class="divider" src="/img/sustainability-divider.svg" alt="">

    <article class="right">
      <h2>
        <span class="one"><strong>Every pack</strong></span>
        <span class="two">purchased helps</span>
        <span class="three"><strong>plant trees</strong></span>
      </h2>
      <a href="#">
        <img src="/img/plant-trees-logo.png" alt="">
        <p>To find out more<br>please go to:<br>www.cheekyps.co.uk</p>
      </a>
      </article>
  </div>

</section>

<style>

section {
  padding: 10vw 5vw 8.8vw; margin-bottom: 1.8vw;
  background: #FA364A;
}
@media (min-width: 768px) {
  section {
  padding: 6vw 15vw 8.8vw;
  }
}

h1 {
  margin-bottom: 10vw;
  font-family: "Hamilton"; font-size: 11vw; text-transform: uppercase; line-height: 0.8em; text-align: center;
  font-weight: 700; letter-spacing: -0.03em;
}
@media (min-width: 768px) {
h1 {
  font-size: 7.3vw; margin-bottom: 5vw;
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

@media (min-width: 768px) {
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
  font-size: 5vw; letter-spacing: -0.03em; 
}

article.left a {
  display: block; margin-top: 2vw;
}
}


article.right {}
article.right h2 {
  font-family: "Hamilton"; text-transform: uppercase; text-align: center;
  letter-spacing: -0.03em; line-height: 0.65; font-size: 10vw;
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

article.right a {
  display: flex; justify-content: space-between; flex-direction: row;
  text-decoration: none; color: inherit;
  width: 46vw; margin: 2vw auto 0;
}

article.right a img {
  margin: 0;
  display: block; width: 15vw;
  padding-bottom: 0.45vw;
}
article.right a p {
  padding-left: 0.9vw; padding-top: 1.5vw; padding-right: 1vw;
  font-family: "Hamilton"; text-transform: uppercase;
  font-weight: 300; line-height: 0.8em; letter-spacing: -0.03em;
  font-size: 5vw; color: inherit;
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

article.right a {
  display: flex; justify-content: space-between; flex-direction: row;
  text-decoration: none; color: inherit;
  width: auto;
}

article.right a img {
  display: block; width: 7.5vw;
  padding-bottom: 0.45vw;
}
article.right a p {
  padding-left: 1vw; padding-top: 0.5vw; padding-right: 1vw;
  font-size: 2.8vw;
}

}

</style>