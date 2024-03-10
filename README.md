# Homework-19-updated
Update

body {
    background-color: #082B59;
    margin: 0;
    padding: 0;
    font-family: 'Lato', sans-serif;
    line-height: 2;
  }
  h1, h2, h3 {
    font-family: 'Poppins', sans-serif;
  }
  h1 {
    font-size: 2rem;
    margin-bottom: 0;
  }
  /* make images flexible */
  img {
    max-width: 100%;
  }
  a {
    color: #59331d;
  }
  a:hover {
    text-decoration: none;
  }
  header {
    border-bottom: 10px solid #d98555;
  }
  /* navbar styling */
  nav ul {
    padding: 0;
    margin: 0;
    list-style-type: none;
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
  }
  nav li {
    margin: 0 1rem 1rem 1rem;
    font-size: 1.3rem;
  }
  /* max width on the image in pixels */
  nav .logo img {
    max-width: 150px;
  }
  /* flex basis on the image container, li */
  nav .logo {
    flex-basis: 100%;
    text-align: center;
  }
  nav a {
    color: white;
    text-decoration: none;
    display: block;
  }
  nav a:hover {
    color: #d98555;
  }
  /* establishes a white background */
  .main-bkgd {
    background: #ffffff url(https://assets.codepen.io/6306176/gulp-bean-bkgd.jpg) repeat-x bottom;
    padding-bottom: 300px;
  }
  /* sits inside of the white background, centered */
  .main {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
  }
  article {
    flex-basis: 73%;
  }
  figure {
    margin: 3rem 0 0 0;
    flex-basis: 25%;
    background-color: #59331d;
    border-radius: 10px;
  }
  figure img {
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
  }
  figcaption {
    color: #f2f2f2;
    padding: 0.5rem;
  }
  .button {
    display: inline-block;
    background-color: #59331D;
    border-radius: 10px;
    padding: 0.5rem 1rem;
    margin: 0;
    color: #f2f2f2;
    text-decoration: none;
    border: 3px solid #59331d;
  }
  .button:hover {
    background-color: #f2f2f2;
    color: #59331d;
  }
  footer {
    color: #f2f2f2;
    text-align: center;
    border-top: 10px solid #d98555;
  }
  footer ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
  }
  footer a {
    color: #f2f2f2;
    font-size: 2rem;
    display: block;
    margin: 0 1rem 3rem 1rem;
  }
<!-- includes a few changes to the design since M17 -->
<!DOCTYPE html>
<html>
<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato&family=Poppins:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href ="Homework 19 copy.css">
</head>
<header>
  <nav>
    <ul>
      <li class="logo"><a href="https://uxuicurriculum.wixsite.com/gulproast"><img src="https://assets.codepen.io/6306176/gulp-logo-light.png" alt="Gulp Roast. Click for home." /></a></li>
      <li><a href="https://uxuicurriculum.wixsite.com/gulproast"><span aria-hidden="true" class="fa-solid fa-mug-saucer"></span> About</a></li>
      <li><a href="https://uxuicurriculum.wixsite.com/gulproast"><span aria-hidden="true" class="fa-solid fa-fire-flame-curved"></span> Products</a></li>
      <li><a href="https://uxuicurriculum.wixsite.com/gulproast"><span aria-hidden="true" class="fa-solid fa-phone"></span> Contact</a></li>
    </ul>
  </nav>
</header>
<div class="main-bkgd">
  <section class="main">
    <article>
      <h1>About Us</h1>
      <p>Life without coffee is a gloomy place. That’s why Gulp Roast has been proudly serving up fresh coffee to the <a href="https://goo.gl/maps/3rAyszfwSDx8Si2Y9" target="_blank">San Francisco area</a> since 2000. Our coffee is locally sourced with the most delicious blends coming directly to your home, right from coffee farmers near you. Our coffee makes even the most difficult days just a tad easier to get through.</p>

      <p>For us, this isn’t just brewing coffee. This is an active life mission to bring our customers the most flavorful, full-bodied beverages we can get our hands on. Browse our site to learn more about our locations and sourcing techniques.</p>

      <a class="button" href="https://uxuicurriculum.wixsite.com/gulproast">Contact Us</a>
    </article>
    <figure>
      <img src="https://assets.codepen.io/6306176/gulp-pouring-coffee-vertical.jpg" alt="Making pour-over coffee at our shop." />
      <figcaption>Our pour-over coffee is known for its freshness and amazing taste.</figcaption>
    </figure>
  </section>
</div>
<footer>
  <p>&copy; 2022 Gulp Roast Coffee. All rights reserved.</p>
  <ul>
    <li>
      <a href="https://facebook.com" target="_blank">
        <span aria-hidden="true" class="fa-brands fa-facebook-square"></span>
        <span class="sr-only">Facebook</span>
      </a>
    </li>
    <li>
      <a href="https://twitter.com" target="_blank">
        <span aria-hidden="true" class="fa-brands fa-twitter-square"></span>
        <span class="sr-only">Twitter</span>
      </a>
    </li>
    <li>
      <a href="https://instagram.com" target="_blank">
        <span aria-hidden="true" class="fa-brands fa-instagram-square"></span>
        <span class="sr-only">Instagram</span>
      </a>
    </li>
  </ul>
</footer>
</html>
