# task-2
About your portfolio

Rportfolio.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!--CSS Styles -->
    <link rel="stylesheet" href="stylesheet.css" />

    <!-- Favicons -->
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="assets/icons/apple-touch-icon.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="assets/icons/favicon-32x32.png"
    />

    <!-- Animate CSS CDN -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
    <title>Ratna Priya | Web Developer</title>
  </head>

  <body>
    <!-- Navbar -->

    <!-- Hero Section -->

    <!-- More about -->

    <!-- Skills section -->

    <!-- Contact section -->

    <!-- Social accounts - Fixed to the right -->

    <!-- Scroll to top -->

    <!-- Footer section -->

    <!-- Website scripts -->

    <nav>
        <h1>RATNA PRIYA</h1>
        <ul class="navigation">
          <li><a href="#about" class="nav-link">About</a></li>
          <li><a href="#skills" class="nav-link">Skills</a></li>
          <li><a href="#contact" class="nav-link">Contact</a></li>
        </ul>
        <button class="burger-menu" id="burger-menu">
          <ion-icon class="bars" name="menu-outline"></ion-icon>
        </button>
  </nav>

  <section class="hero" id="about">
    <img
      src="C:\Users\Ratna Priya\Downloads\level2img.png"
      alt="Ratna Priya"
      loading="lazy"
      class="hero-img"
    />
    <div class="bio animate__animated animate__shakeX">
      <h2 class="bio-title">About Me</h2>
      <p class="bio-text">
        I'm currently pursing bachelors degree in field of computer science, 
        which teaches computer applications and prpogramming.
        By completing this course, the students will be able to build their careers 
        in the field of Information Technology sector.
      </p>
    </div>
</section>
<section class="more-about">
  <h2>More About Me</h2>
  <p>
    I, Ratna Priya a degree student pursing BCA(Bachelor of Computer Apllications) 
    in GITAM University, Visakhapatnam. Pursuing a BCA course helps you build a 
    strong foundation in computer science. We will gain in-depth knowledge of programming 
    languages, data structures, algorithms, computer networks, and other essential concepts. 
    This foundation will be valuable in your future endeavors.
  </p>
  <p>
    A significant portion of your computer science studies will involve programming. 
    We start out by learning high-level, basic languages such as Java and C++. As you go on, 
    we'll be introduced to more complex coding methods, including Prolog, Scheme, and machine code, 
    also known as assembly language programming.
  </p>
  <p>
    As they continue to evolve, they will undoubtedly unlock new potentials and challenges. 
    As responsible users, it is incumbent upon us to harness their power for good 
    while mitigating potential risks.
  </p>
</section>
<section class="skills" id="skills">
  <h2 class="skill-header">My Top Skills</h2>

  <div class="skills-wrapper">
    <div class="first-set animate__animated animate__pulse">
      <img
        src="C:\Users\Ratna Priya\Downloads\html.png"
        alt=""
        loading="lazy"
        class="icon icon-card"
      />
      <img
        src="C:\Users\Ratna Priya\Downloads\css.png"
        alt=""
        loading="lazy"
        class="icon icon-card"
      />
      <img
        src="C:\Users\Ratna Priya\Downloads\javascript.png"
        alt=""
        loading="lazy"
        class="icon icon-card"
      />
    </div>

    <div class="second-set animate__animated animate__pulse">
      <img
        src="C:\Users\Ratna Priya\Downloads\java'.png"
        alt=""
        loading="lazy"
        class="icon icon-card"
      />
      <img
        src="C:\Users\Ratna Priya\Downloads\c++.png"
        alt=""
        loading="lazy"
        class="icon icon-card"
      />
      <img
        src="C:\Users\Ratna Priya\Downloads\pythin.jpeg"
        alt=""
        loading="lazy"
        class="icon icon-card"
      />
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <h2>Get In Touch With Me</h2>
  <div class="contact-form-container">
    <div class="contact-form">
      <form action="https://formspree.io/f/xgejyggv" method="POST">
        <div class="form-control">
          <label for="name">Name</label>
          <input
            type="text"
            id="name"
            name="sender-name"
            placeholder="Enter Your Name"
            class="input-field"
            required
          />
        </div>
        <div class="form-control">
          <label for="email">Email</label>
          <input
            type="email"
            id="email"
            name="sender-email"
            placeholder="Enter Your Email"
            class="input-field"
            required
          />
        </div>
        <div class="form-control">
          <label for="message">Message</label>
          <textarea
            id="message"
            cols="60"
            rows="10"
            placeholder="Enter Your Message"
            name="message"
            class="input-field"
            required
          ></textarea>
        </div>
        <input
          type="submit"
          value="Submit"
          id="submit-btn"
          class="submit-btn"
        />
      </form>
    </div>
  </div>
</section>
<div class="socials">
  <a href="#" target="_blank"
    ><img
      src="https://techcrunch.com/wp-content/uploads/2014/06/twitter-rise.gif"
      alt="Twitter"
      loading="lazy"
      class="socicon"
  /></a>
  <a href="#" target="_blank"
    ><img
      src="https://media2.giphy.com/media/uo6rcjwHSAFsQ/giphy.gif"
      alt="Instagram"
      loading="lazy"
      class="socicon"
  /></a>
  <a href="#" target="_blank"
    ><img
      src="https://cliply.co/wp-content/uploads/2021/02/372102050_LINKEDIN_ICON_TRANSPARENT_1080.gif"
      alt="Linkedin"
      loading="lazy"
      class="socicon"
  /></a>
  <a href="#" target="_blank"
    ><img src="https://raw.githubusercontent.com/gist/ManulMax/2d20af60d709805c55fd784ca7cba4b9/raw/bcfeac7604f674ace63623106eb8bb8471d844a6/github.gif" alt="Github" class="socicon"
  /></a>
  </div>

    <footer>
      <p class="copy">&copy; Copyright 2021</p>
      <p class="copy">
        Built with &#x2661; by
        <a href="https://x.com/Ratna_4127?t=lWDqed6jOx96i_crixKAjA&s=08" target="_blank"
          >Ratna Priya</a>
      </p>
    </footer>

    <script src="index.js"></script>
    <!-- Ion icons scripts -->
    <script
      type="module"
      src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"
    ></script>
    <script
      nomodule
      src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"
    ></script>
  </body>
</html>

stylesheet.css

:root {
    --variable-name: value;
  }
  selector {
    property: var(--variable-name);
  }
  @import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,900;1,700&display=swap");

  /* Variables */
  :root {
    --font-family: "Roboto", sans-serf;
    --normal-font: 400;
    --bold-font: 700;
    --bolder-font: 900;
    --bg-color: #fcfcfc;
    --primary-color: #4756df;
    --secondary-color: #ff7235;
    --primary-shadow: #8b8eaf;
    --secondary-shadow: #a17a69;
    --bottom-margin: 0.5rem;
    --bottom-margin-2: 1rem;
    --line-height: 1.7rem;
    --transition: 0.3s;
  }
  /* Variables end */
  
  html {
    scroll-behavior: smooth;
  }
  
  /* CSS Resets */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  ul {
    list-style-type: none;
  }
  
  a {
    text-decoration: none;
    color: var(--primary-color);
  }
  
  a:hover {
    color: var(--secondary-color);
  }
  
  body {
    font-family: var(--font-family);
  }
   
  nav {
    position: sticky;
    top: 0;
    left: 0;
    z-index: 1;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1.5rem 3.5rem;
    background-color: var(--bg-color);
    box-shadow: 0 3px 5px rgba(0, 0, 0, 0.1);
  }
  
  nav h1 {
    color: var(--primary-color);
  }
  
  nav a {
    color: var(--primary-color);
    transition: var(--transition);
  }
  nav a:hover {
    color: var(--secondary-color);
    border-bottom: 2px solid var(--secondary-color);
  }
  
  nav ul {
    display: flex;
    gap: 1.9rem;
  }
  
  nav ul li {
    font-weight: var(--bold-font);
  }
  .burger-menu {
    color: var(--primary-color);
    font-size: 2rem;
    border: 0;
    background-color: transparent;
    cursor: pointer;
    display: none;
  }
  .hero {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 2.5rem;
    max-width: 68.75rem;
    margin: auto;
  }
  .hero img {
    height: 37.5rem;
    width: 37.5rem;
  }
  
  .bio {
    width: 25rem;
    padding: 0.625rem;
    border-radius: 6px;
    box-shadow: 0px 2px 15px 2px var(--primary-shadow);
  }
  
  .bio h1 {
    margin-bottom: var(--bottom-margin);
  }
  
  .bio p {
    line-height: var(--line-height);
    padding: 0.3rem 0;
  }
  .more-about {
    background-color: var(--bg-color);
    padding: 1rem 6rem;
  }
  
  .more-about h2 {
    margin-bottom: var(--bottom-margin);
    text-align: center;
  }
  
  .more-about p {
    line-height: var(--line-height);
    padding: 0.4rem;
  }

  .skills {
    max-width: 68.75rem;
    margin: auto;
    text-align: center;
    margin-top: 2.5rem;
  }
  
  .skill-header {
    margin-bottom: 1rem;
  }
  
  .skills-wrapper img {
    padding: 1.25rem;
  }
  
  .icon {
    width: 11.875rem;
    height: 11.25rem;
  }

  .icon-card {
    background-color: #fff;
    border-radius: 11px;
    box-shadow: 0 3px 10px var(--secondary-shadow);
    padding: 20px;
    margin: 10px;
  }

  .contact {
    margin-top: 2rem;
  }
  
  .contact h2 {
    text-align: center;
    margin-bottom: var(--bottom-margin-2);
  }
  
  .contact-form-container {
    max-width: 40.75rem;
    margin: 0 auto;
    padding: 0.938rem;
    border-radius: 5px;
    box-shadow: 0 3px 10px var(--secondary-shadow);
  }

  .contact-form-container label {
    line-height: 2.7em;
    font-weight: var(--bold-font);
    color: var(--primary-color);
  }
  
  .contact-form-container textarea {
    min-height: 6.25rem;
    font-size: 14px;
  }
  
  .contact-form-container .input-field {
    width: 100%;
    padding-top: 10px;
    padding-bottom: 10px;
    border-radius: 5px;
    border: none;
    border: 2px outset var(--primary-color);
    font-size: 0.875rem;
    outline: none;
  }

  .submit-btn {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    background-color: #fff;
    border: 2px solid var(--primary-color);
    border-radius: 5px;
    font-size: 1rem;
    font-weight: var(--bold-font);
    transition: var(--transition);
  }
  .submit-btn:hover {
    background-color: var(--primary-color);
    border: 2px solid var(--primary-color);
    cursor: pointer;
  }
  
  .socials {
    display: flex;
    flex-direction: column;
    position: fixed;
    right: 1%;
    bottom: 50%;
  }
  
  .socicon {
    width: 2rem;
    height: 2rem;
  }

  footer {
    background-color: var(--bg-color);
    padding: 1.25rem;
    text-align:center;
    margin: 2rem 0 0;
  }

