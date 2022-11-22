# code-from-courses
CSS
setup and syntax

<!DOCTYPE html>
<html>

<head>
  <title>Vacation World</title>
  <link href='style.css' rel='stylesheet'>
</head>

<body>
  <img src='https://content.codecademy.com/courses/freelance-1/unit-2/explorer.jpeg' />
  <h1 class='title'>Top Vacation Spots</h1>
  <h5>By: Stacy Gray</h5>
  <h6>Published: 2 Days Ago</h6>

  <p>The world is full of fascinating places. Planning the perfect vacation involves packing up, leaving home, and experiencing something new.</p>

  <h2 class='destination'>1. Florence, Italy</h2>
  <div class='description'>A city-size shrine to the Renaissance, Florence offers frescoes, sculptures, churches, palaces, and other monuments from the richest cultural flowering the world has known. Names from its dazzling historical past; Dante, Michelangelo, Galileo, Machiavelliare are some of the most resonant of the medieval age. <a href='https://www.nationalgeographic.com/travel/destination/florence' target='_blank'>Learn More</a>.
    <h5>Top Attractions</h5>
    <ul>
      <li>Museums</li>
      <li>Bike Tours</li>
      <li>Historical Monuments</li>
    </ul>
  </div>

  <h2 class='destination'>2. Beijing, China</h2>
  <div class='description'>A city in the midst of reinventing itself and continuing to build on the success of the 2008 Summer Olympics, Beijing is a place of frenzied construction. New housing, new roads, and new sports venues seem to spring up overnight. At the same time, the capital of the Peoples Republic of China remains an epicenter of tradition, with the treasures of nearly 2,000 years as the imperial capital still on view in the famed Forbidden City and in the luxuriant pavilions and gardens of the Summer Palace.
    <a href='https://www.nationalgeographic.com/travel/destination/beijing' target='_blank'>Learn More</a>.
    <h5>Top Attractions</h5>
    <ul>
      <li>Biking</li>
      <li>Historical Sites</li>
      <li>Restaurants and Dining</li>
    </ul>
  </div>

  <h2 class='destination'>3. Seoul, South Korea</h2>
  <div class='description'>The Korean capital is a city of contrasts. Fourteenth-century city gates squat in the shadow of 21st-century skyscrapers, while the broad Han River is back-dropped by granite mountains rising in the city center complete with alpine highways speeding around their contours and temples nestling among their crags. Fashionable, gadget-laden youths battle for sidewalk space with fortune-tellers and peddlers, while tiny neighborhoods of traditional cottages contrast with endless ranks of identical apartments.
    <a href='https://www.nationalgeographic.com/travel/destination/seoul' target='_blank'>Learn More</a>.
    <h5>Top Attractions</h5>
    <ul>
      <li>Parasailing</li>
      <li>Segway Tours</li>
      <li>Spas and Resorts</li>
    </ul>
  </div>

  <h2> More Destinations </h2>
  <ul>
<li><h4 class='destination'>Jackson Hole, Wyoming</h4></li>
    <li><h4 class='destination'>Cape Town, South Africa</h4></li>
    <li><h4 class='destination'>La Paz, Bolivia</h4></li>
  </ul>

  <p>&mdash;Best of luck with your travels, and be sure to send pictures and stories. We'd love to hear them!</p>


</body>

</html>

p {
  color: green;
}



SELECTORS
* {
  border: 1px solid red;
}

p {
  color: green;
}

h1 {
  color: maroon;
}

.title {
  color: teal;
}

.uppercase {
  text-transform: uppercase;
}

#article-title {
  font-family: cursive;
}

a[href*='florence'] {
  color: lightgreen;
}

a[href*='beijing'] {
  color: lightblue;
}

a[href*='seoul'] {
  color: lightpink;
}

a:hover {
  color:darkorange;
}

.heading-background {
  background-color: aqua;
}

#publish-time {
  color: lightgray;
}

h5 {
  color: yellow;
}

.author-class {
  color: pink;
}

#author-id {
  color: cornflowerblue;
}

h2.destination {
  font-family: Tahoma;
}

.description h5 {
  color: blueviolet;
}

li h4 {
  color: gold;
}

h4 {
  color: dodgerblue;
}

li,
h5 {
  font-family: monospace;
}


VISUALS
body {
  /* Old browsers */
  background: #141E30;
  /* Chrome 10-25, Safari 5.1-6 */
  background: -webkit-linear-gradient(-45deg, #35577D, #141E30);
  /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  background: linear-gradient(-45deg, #35577D, #141E30);
  margin: 0;
  padding: 0;
}

h1 {
  color: #FFF !important;
  font-size: 2em;
  padding-top: 100px;
  width: 100%;
  font-family: Georgia;
  text-align: center;
}

h2 {
  border-bottom: 1px solid rgba(255, 255, 255, 0.5);
  color: rgba(255, 255, 255, 0.5);
  font-weight: 100;
  font-size: 22px;
  line-height: 24px;
  padding-bottom: 30px;
  text-align: left;
  width: 70%;
  font-family: Georgia;
}

p {
  color: aliceblue;
  line-height: 1.3em;
  text-align: left;
  width: 100%;
  font-family: Helvetica;
  font-size: 18px;
  font-weight: bold;
}

.byline {
  font-family: Helvetica;
  color: rgba(255, 255, 255, 0.5);
  float: left;
  font-size: 14px;
  padding-left: 10px;
  text-transform: uppercase;
}

.caption {
  display: block;
  font-family: 'Playfair Display', serif;
  font-size: 14px;
  font-style: italic;
  line-height: 14px;
  margin-left: 20px;
  padding: 10px;
  position: relative;
  top: 80%;
  width: 60%;
  background-color: white;
  color: black;
}

.content {
  padding: 40px;
}

.image {
  background-image: url('https://content.codecademy.com/courses/freelance-1/unit-2/soccer.jpeg');
  background-size: cover;
  background-position: center;
  height: 300px;
}

.writer-img {
  -webkit-box-shadow: 5px 0px 5px 0px rgba(0, 0, 50, 0.97);
  -moz-box-shadow: 5px 0px 5px 0px rgba(0, 0, 50, 0.97);
  box-shadow: 5px 0px 5px 0px rgba(0, 0, 50, 0.97);
  float: left;
  width: 50px;
}


THE BOX MODEL
body {
  background-color: white;
  font-family: 'Raleway', sans-serif;
  margin: 0;
  padding: 0;
}

.navigation ul {
  margin: 0;
  padding: 0;
  text-align: center;
}

.navigation li {
  font-weight: 100;
  letter-spacing: 2px;
  padding: 20px;
}

.navigation  li.logo {
  color: black;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 4px;
}

.donate{
  visibility: hidden;
}

#banner {
  background-image: url("https://content.codecademy.com/courses/web-101/unit-6/htmlcss1-img_tahoe.jpeg");
  background-size: cover;
  background-position: bottom center;
  height: 700px;
  width: 100%;
}

#banner .content h1 {
  border: 3px solid white;
  position: relative;
  top: 50px;
  width: 400px;
  margin: 0 auto;
}

#main {
  margin: 0 auto;
  padding: 40px;
  text-align: center;
  width: 400px;
  height: 1000px;
  overflow: scroll;
}

h1 {
  color: white;
  font-size: 42px;
  font-weight: 600;
  text-align: center;
}

h2 {
  border: 1px dotted red;
  color: red;
  font-size: 14px;
  line-height: 48px;
  padding: 20px 30px;
  margin: 30px 20px;
  text-align: center;
}

h3 {
  color: red;
  font-size: 26px;
  font-weight: 700;
  padding: 20px 10px;
}

p {
  color: grey;
  font-size: 16px;
  line-height: 48px;
  margin-top: 60px;
  padding: 10px 20px;
}

.pull-quote {
  margin: 0 auto;
  width: 400px;
}

.byline {
  border-bottom: 1px solid LightGrey;
  border-top: 1px solid LightGrey;
  color: DarkGrey;
  font-size: 14px;
  font-weight: 200;
}

.share {
  border: 1px solid LightGrey;
  padding: 40px 0px;
  position: relative;
  text-align: center;
  width: 100%;
}

.share a {
  background: red;
  border: 1px solid red;
  border-radius: 3px;
  color: white;
  display: inline-block;
  margin: 10px;
  padding: 14px;
  text-decoration: none;
}

.share a:hover {
  background: white;
  border: 1px solid red;
  color: red; }


DISPLAY AND POSITIONING
body {
  background-color: #FFF;
  margin: 0 auto;
}

header {
  background-color: #466995;
  border-bottom: 1px solid #466995;
  position: fixed;
  width: 100%;
  z-index: 10;
}

ul {
  margin: 30px auto;
  padding: 0 20px;
  text-align: center;
}

li {
  color: #FFF;
  font-family: 'Oswald', sans-serif;
  font-size: 16px;
  font-weight: 300;
  text-transform: uppercase;
  display: inline-block;
  width: 80px;  
}

li:hover {
  color: #DBE9EE;
}

h1 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 32px;
  font-weight: 300;
  text-transform: uppercase;
}

h2 {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 26px;
  font-weight: 100;
  margin: 0 auto 20px auto;
}

h3 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  text-align: center;
  font-weight: 700;
  text-transform: uppercase;
  padding: 30px;
}

h4 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  font-weight: 300;
  letter-spacing: 2px;
  text-align: center;
  text-transform: uppercase
}

p {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 18px;
}

footer {
  background-color: #DBE9EE;
  text-align: center;
  height: 100px;
}

.welcome {
  background-color: #DBE9EE;
  box-sizing: border-box;
  padding: 40px;
  text-align: center;
  width: 100%;
  position: relative;
  top: 50px;
}

.question {
  text-align: center;
  position: relative;
  top: 40px;
}

.answer {
  border: 1px solid #466995;
  margin: 20px;
  display: inline-block;
}

.answer:hover {
  background: #C0D6DF;
  color: #FFF;
}



COLOR
html,
body {
  margin: 0;
  height: 100%;
}

.wrapper {
  position: relative;
  margin: auto;
  padding: 0;
  max-width: 75vw;
}

.midground, .foreground {
  position: absolute;
  top: 0;
  left: 0;
  display: inline-block;
  margin: 15vh 0 0 15vw;
  padding: 0;
  width: 35vw;
  height: 59vh;
}

body {
  background-color: rgba(0, 255, 0, 0.1);
}

.midground {
  background-color: hsla(225, 100%, 25%, 0.4);
}

.foreground {
  background-color: hsla(325, 50%, 50%, 0.6);
}



TYPOGRAPHY
@font-face {
  font-family: 'GlegooBanner';
  src: url('../fonts/Glegoo-Regular.woff2') format('woff2'),
       url('../fonts/Glegoo-Regular.woff') format('woff'),
       url('../fonts/Glegoo-Regular.ttf') format('truetype')
}

/* Universal Styles */
html {
  font-size: 16px;
  font-family: 'Arial', sans-serif;
}

body {
  background-color: #F2F2F2;  
  text-align: center;  
}

h1 {
  padding: 20px;
  color: white;
  font-size: 28px;
  text-align: center;
  font-family: Georgia;
  text-transform: uppercase;
  letter-spacing: 0.3em;
}

h2 {
  padding: 40px 20px 0 20px;
  font-size: 24px;
  text-align: center;
}

a {
  text-decoration: none;
}

p {
  max-width: 900px;
  margin: 0 auto;
  padding: 20px;
  text-align: justify;
}


/* Header */
.header {
  position: fixed;
  top: 0;
  width: 100%;
  padding: 20px 0;
  background-color: #fff;
  font-size: 14px;
  font-weight: 900;
}

.header li {
  display: inline-block;
  padding: 10px;
}

.header a {
  color: #4A4A4A;
}

a.home {
  color: #4D00FF;
}


/* Banner Section */
.banner {
  margin-top: 74px;
  padding: 40px 0 100px 0;
  background-color: #4D00FF;
}

.banner p {
  border-top: 1px solid #fff;
  border-bottom: 1px solid #fff;
  color: #ffffff;
  font-weight: lighter;
  word-spacing: 0.25em;
  line-height: 1.4;
  font-family: 'GlegooBanner';
  font-size: 20px;
}


/* Editorial Sections */
.editorial {
  padding-bottom: 40px;
  color: #717171;
  font-family: 'Trebuchet MS', 'Times New Roman', serif;
}

/* Font Card Sections */
.font-card {
  padding: 10px 0 40px 0;
  background-color: #ffffff;
  text-align: center;
}

.font-card .creator {
  padding: 10px 20px;
  font-size: 16px;
  font-style: italic;
}

.sample {
  display: inline-block;  
  padding: 5px 40px;
}

.sample .text {
  color: #4D00FF;
  font-size: 100px;
}

.garamond {
  font-family: Garamond;
}

.helvetica {
  font-family: Helvetica;
}

.space {
  font-family: 'Space Mono', monospace;
}

.bold {
  font-weight: 900;
}

.regular {
  font-weight: normal;
}

.italic {
  font-weight: normal;
  font-style: italic;
}



MAKE A WEBSITE
html, body {
  min-height: 100%;
  display: flex;
  flex-direction: column;
  font-weight: 300;
  line-height: 1.5;
}

body {
  font-family: 'Lato', sans-serif;
  background-image: url('https://content.codecademy.com/projects/make-a-website/lesson-3/background.jpg');
  background-position: center top;
  background-size: cover;
  margin: 0;
}

a {
  color: #204156;
  text-decoration: none;
}

.page-title {
  text-align: center;
  font-weight: 100;
}

.page-description {
  border: 1px solid #000;
  margin: 2px;
  text-align: center;
  padding: 30px;
}

.gallery {
  margin-top: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center
}

.gallery-item {
  margin: 20px;
}

.gallery-item .thumbnail {
  border: 5px solid #fff;
}

/* FOOTER NAVIGATION */

nav {
  background-color: #FFF;
}

nav li {
  display: inline;
  margin: 0;
  padding: 0 10px;
}

nav ul {
  display: inline;
}

.contact-btn {
  float: right;
}

.contact-btn a {
  cursor: pointer;
  margin-right: 30px;
  padding: 8px 18px;
  border: 1px solid #204156;
position: relative;
}

.contact-btn a:active {
  top: 2px; 
}

nav a {
  height: 60px;
  line-height: 60px;
  color: #204156;
  text-decoration: none;
}
