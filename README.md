# starter-pete-thinkful-portfolio
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Pete Thinkful</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
    />
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <!-- Header section -->
    <header>
      <h1>Pete Thinkful | Artist</h1>
      <nav>
        <a href="#about">About</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <div>
        <!-- About section -->
        <article id="about">
          <h2>About</h2>
          <section>
            <h3 class="center">Hi! I'm Pete Thinkful</h3>
           
              <img
                class="image-circle"
                src="images/pete-thinkful.png"
                alt="Pete Thinkful"
              />
         
            <p class="about">I'm an artist living in Denver, Colorado.</p>
            <p class="about">As an artist, I'm interested in:</p>
            <ul class="center">
              <li>Producing abstract art</li>
              <li>Creating street graffiti art</li>
              <li>Connecting with like-minded artists</li>
            </ul>
            <p class="about">
              Please feel free to take a look at my website and feel free to
              <a href="#contact">contact me</a>.
            </p>
          </section>
          </article>
      

          <section>
            <h3 class="background">Pete's Background</h3>
            <p>
              After graduating college, I became an art teacher and worked with
              beginners and professionals. I love art and my works have been
              featured in major art galleries across the globe.
            </p>
            <p>
              If you're looking to hire an artist or if you're an artist looking
              for a collaborator for your next project, please reach out! I'm so
              excited to work with other artists to create new art.
            </p>
          </section>
        </article>

        <hr />

        <!-- Portfolio section -->
        <article id="portfolio">
          <h2>Portfolio</h2>

          <div class="container space-around container-space-between container center">
            <div class="container space-evenly">
              <h3 class="abstract">Abstract Red</h3>
              <h3 class="spiral">Spiral Zany</h3>
              <h3 class="rainbow">Melted Rainbow</h3>
            </div>
          </div>
         
          <section class="container space-around container-space-between container center">
            <div>
              <img src="images/abstract-red.png" alt="Abstract Red" />
              <img src="images/spiral-zany.png" alt="Spiral Zany" />
              <img src="images/melted-rainbow.png" alt="Melted Rainbow" />
            </div>
          </section>

          <section class="container space-around container-space-between container center">
            <p class="item-text">
              Vaporware wayfarers heirloom neutra disrupt. Activated charcoal
              waistcoat scenester hell of.
            </p>
            <p class="item-text">
              Sriracha portland taxidermy cronut messenger bag, vegan
              distillery. Vaporware kickstarter air plant mumblecore food truck.
            </p>
            <p class="item-text">
              Edison bulb single-origin coffee snackwave, actually ennui
              locavore shabby chic forage.
            </p>
          </section>
        </article>

        <hr />

        <!-- Contact section -->
        <article id="contact">
          <h2>Contact</h2>
          <p>
            I'd love to hear from you! Please feel free to contact or follow me:
          </p>
          <ol>
            <li>
              <a href="">LinkedIn</a>
            </li>
            <li>
              <a href="">Instagram</a>
            </li>
            <li>
              <a href="">Pinterest</a>
            </li>
          </ol>
        </article>
      </div>
    </main>

    <!-- Footer section -->
    <footer>
      <p>© Pete Thinkful. All rights reserved.</p>
    </footer>
  </body>
</html>


STYLE CSS

* The @import rule below imports the Playfair Display and Source Sans Pro fonts into the stylesheet*/
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display&family=Source+Sans+Pro:wght@400&display=swap");

body {
  background-color: #eae2b7;
  color: #003049;
  font-family: "Source Sans Pro", Tahoma, Geneva, Verdana, sans-serif;
  padding: 40px;
}

/* Headings */
h1,
h2 {
  text-align: center;
}

h3 {
  display: flex;
  font-family: "Playfair Display", Times, serif;
  text-align: center;

}

h3.center {
  margin-left: 300px;
}

h3.rainbow {
  display: inline-block;
  margin-left: 0px
}

h3.background {
  margin-left: 200px;
}

h3.abstract {
    display: inline-block;
    margin-left: -25px;
    width: 150px;
}

h3.spiral {
  display: inline-block;
}

p.item-text {
  text-align: center;
  width: 200px;
}

/* Header */
header {
  display: flex;
  text-align: center;
  margin-left: 400px;
}


/* Containers */
div {
  background-color: #eae2b7;
  margin: auto;
  width: 600px;
}

article {
  padding: 50px 0;
}

article div {
  text-align: center;
  width: 100%;
}

/* Paragraphs */
p {
  line-height: 1.5;
}

p.padding {
  font-align: center;
}

p.about {
  margin-left: 300px;
}

ul.center {
  margin-left: 300px;
}

/* Links */
a:link {
  color: #d62828;
}

a:hover {
  color: #f77f00;
}

nav a {
  padding-left: 20px;
} 

nav {
  margin-top: 30px;
    text-align: center;
    vertical-align: middle;
}

/* Images */
img {
  margin-right: 300px;
  width: 100%;
  max-width: 180px;
  height: auto;
  float: center; margin: 0px 15px 15px 0px
}

.container.space-evenly {
  justify-content: space-around;
  text-align: center;
}


.container {
  display: flex;
}
.container.space-around {
  justify-content: space-around;
}
.container.space-between {  
  justify-content: space-between;
}

.image-circle {
  border: 2px solid #003049;
  border-radius: 50%;
  float: left; margin: 0px 15px 15px 0px; 
}

/* Footer */
footer {
  text-align: center;
}

/* Other page elements */
hr {
  border: 1px solid black;
}
