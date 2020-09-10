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
        <p>Find out more<br>about our<br>tree planting</p>
      </a>
  </div>

</section>

<style>


section {
  padding: 8.8vw 12vw 8.8vw; margin-bottom: 1.8vw;
  background: #FA364A;
}
@media (min-width: 768px) {
  section {
    padding: 6vw 15vw 8.8vw;
  }
}

h1 {
  margin-bottom: 10vw;
  font-family: "Jomhuria"; font-size: 14vw; text-transform: uppercase; line-height: 0.5em; text-align: center;
  font-weight: 700; letter-spacing: 0.03em;
}
@media (min-width: 768px) {
h1 {
  font-size: 10vw;
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
  flex: 0 0 5px;
}
}

article {
  display: flex;
  flex: 0 0 23.5vw;
  justify-content: space-between; flex-direction: column;
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

article.left {}
article.left h2 {
  font-family: "Jomhuria"; text-transform: uppercase;
  line-height: 0.5em; text-align: center;
}

article.left h2 .one {
  font-size: 10vw; line-height: 0.55em;
  font-weight: 400; letter-spacing: 0.01em;
}
article.left h2 .one strong {
  font-size: 9.8vw;
  font-weight: 700; letter-spacing: 0.05em;
}
article.left h2 .two {
  font-weight: 400; line-height: 0.55em;
}
article.left h2 .two strong {
  font-size: 12vw; line-height: 0.55em;
  font-weight: 700; letter-spacing: 0.04em;
}
article.left h2 .three {
  font-weight: 400; line-height: 0.55em;
  font-size: 10vw;
}

@media (min-width: 768px) {
article.left h2 .one {
  font-size: 7vw; line-height: 0.55em;
  font-weight: 400; letter-spacing: 0.01em;
}
article.left h2 .one strong {
  font-size: 6.8vw;
  font-weight: 700; letter-spacing: 0.05em;
}
article.left h2 .two {
  font-weight: 400; line-height: 0.55em;
}
article.left h2 .two strong {
  font-size: 6.4vw; line-height: 0.55em;
  font-weight: 700; letter-spacing: 0.04em;
}
article.left h2 .three {
  font-weight: 400; line-height: 0.55em;
  font-size: 5.2vw;
}
}

article.right {}
article.right h2 {
  font-family: "Jomhuria"; text-transform: uppercase; text-align: center;
}
article.right h2 .one {
  font-size: 10vw; line-height: 0.5em;
  font-weight: 400; letter-spacing: 0.02em;
}
article.right h2 .one strong {
  display: block;
  font-size: 13vw;
  font-weight: 700; letter-spacing: 0.05em;
}
article.right h2 .two {
  font-weight: 400; line-height: 0.55em;
  font-size: 9.8vw;
}
article.right h2 .three {
  font-size: 7vw; line-height: 0.75em;
  font-weight: 400; letter-spacing: 0.02em;
}
article.right h2 .three strong {
  display: block;
  font-size: 12vw;
  font-weight: 700; letter-spacing: 0.05em;
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
  padding-left: 0.9vw; padding-top: 0.9vw;
  font-family: "Jomhuria"; text-transform: uppercase;
  font-weight: 400; line-height: 0.55em;
  font-size: 8vw; color: inherit;
}


@media (min-width: 768px) {
  article.right {}
article.right h2 {
  font-family: "Jomhuria"; text-transform: uppercase;
}
article.right h2 .one {
  font-size: 7vw; line-height: 0.55em;
  font-weight: 400; letter-spacing: 0.02em;
}
article.right h2 .one strong {
  display: inline;
  font-size: 6.8vw;
  font-weight: 700; letter-spacing: 0.05em;
}
article.right h2 .two {
  font-weight: 400; line-height: 0.55em;
  font-size: 5.1vw;
}
article.right h2 .three {
  font-size: 7vw; line-height: 0.55em;
  font-weight: 400; letter-spacing: 0.02em;
}
article.right h2 .three strong {
  font-size: 6.2vw;
  font-weight: 700; letter-spacing: 0.05em;
}

article.right a {
  display: flex; justify-content: space-between; flex-direction: row;
  text-decoration: none; color: inherit;
}

article.right a img {
  display: block; width: 7.5vw;
  padding-bottom: 0.45vw;
}
article.right a p {
  padding-left: 0.9vw; padding-top: 0.9vw;
  font-family: "Jomhuria"; text-transform: uppercase;
  font-weight: 400; line-height: 0.55em;
  font-size: 4vw; color: inherit;
}
}

</style>