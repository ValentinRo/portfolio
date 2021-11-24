<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--CSS styles-->
    <link rel="stylesheet" href="assets/css/style.css">
    <!--Favicons-->
    <link rel="apple-touch-icon" sizes="180x180" href="assets/icons/apple-touch-icon.png"/>
    <link rel="icon" type ="image/png" href="assets/icons/apple-touch-icon.png"/>
    <!--Animate CSS CDN-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
   <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet""> 
</head>
<body>
  <!-- Menu--> 
    <h1>BasiCode</h1>
      <ul class="menu">
        <li><a href ="#about" class="menuItem">About</a></li>
        <li><a href ="#skills" class="menuItem">Skills</a></li>
        <li><a href ="#projects" class="menuItem">Projects</a></li>
        <li><a href ="#contact" class="menuItem">Contact</a></li>
      </ul>
      <button class="hamburger">
        <i class="menuIcon material-icons">menu</i>
        <i class="closeIcon material-icons">close</i>
      </button> 
  <!--Hero Section-->
  <section class="hero" id="about">
    <img
        src="assets/images/wfh_1.svg"
        alt ="basicode"
        loading="lazy"
        class="hero-img" />
    <div class "bio animate__animated animate__shakeX">
      <h2 class ="bio-title">About Me</h2>
      <p class= "bio-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
        Rem aliquid voluptatem exercitationem nisi cum adipisci quod. 
        Odio magni non asperiores rem reiciendis illum quibusdam ipsum ad culpa! Labore, nobis sit.
      </p>
    </div>
  </section>
  <!-- More About-->
  <section class="more-about">
    <h2>More About Me </h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
      Mollitia ipsa aliquid laudantium quaerat eum doloribus laboriosam, debitis id cumque magnam, 
      provident eveniet nisi impedit quia alias corporis iusto dolores soluta.</p>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
       Perspiciatis ea illum, vel cum doloribus omnis, minima hic aspernatur necessitatibus 
       atque quisquam aliquam magnam quas facere, sit dicta reiciendis officia sapiente?</p>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Porro quos obcaecati itaque velit. 
      Quibusdam nihil vel ipsam, voluptatum nemo, eligendi veritatis atque illum, necessitatibus odit hic a dolores asperiores ullam!</p>
  </section>
  <!--Skills Section-->
  <section class="skills" id="skills">
    <h2 class="skill-header">My Top Skills</h2>
    <div class="skills-wrapper">
      <div class="first-set animate__animated animate__pulse ">
        <img src="assets/icons/logo-html5.svg" 
        alt=""
        loading="lazy"
        class= "icon icon-card"
        />
        <img src="assets/icons/logo-css3.svg" 
        alt=""
        loading="lazy"
        class= "icon icon-card"
        />
        <img src="assets/icons/logo-javascript.svg" 
        alt=""
        loading="lazy"
        class= "icon icon-card"
        />
      </div>
      <div class="second-set animate__animated animate__pulse ">
        <img src="assets/icons/logo-github.svg" 
        alt=""
        loading="lazy"
        class= "icon icon-card"
        />
        <img src="assets/icons/logo-python.svg" 
        alt=""
        loading="lazy"
        class= "icon icon-card"
        />
        <img src="assets/icons/logo-react.svg" 
        alt=""
        loading="lazy"
        class= "icon icon-card"
        />
      </div>
    </div>
  </section>
  <section class="projects" id="projects">
    <h2 class="projects-title">Some of my Recents Projects</h2>
    <div class="projects-container">
      <div class="project-container project-card">
        <img
          src="assets/images/expertTracker.png"
          alt=""
          loading="lazy"
          class="project-pic"
        />
        <h3 class="projects-title">Expense Tracker</h3>
        <p class="project-details">Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
          Nisi, possimus repellat exercitationem totam quam provident, atque minus voluptatem accusantium ab nemo magni omnis! 
          Asperiores architecto excepturi fuga laborum placeat eligendi?
        </p>
        <a href="#" target="_blank" class="project-link">Check it Out</a>
      </div>
      <div class="project-container project-card">
        <img
          src="assets/images/netflixClone.png"
          alt=""
          loading="lazy"
          class="project-pic"
        />
        <h3 class="projects-title">Netflix Clone</h3>
        <p class="project-details">Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
          Nisi, possimus repellat exercitationem totam quam provident, atque minus voluptatem accusantium ab nemo magni omnis! 
          Asperiores architecto excepturi fuga laborum placeat eligendi?
        </p>
        <a href="#" target="_blank" class="project-link">Check it Out</a>
      </div>
      <div class="project-container project-card">
        <img
          src="assets/images/greenyEarth.png"
          alt=""
          loading="lazy"
          class="project-pic"
        />
        <h3 class="projects-title">Greeny Earth</h3>
        <p class="project-details">Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
          Nisi, possimus repellat exercitationem totam quam provident, atque minus voluptatem accusantium ab nemo magni omnis! 
          Asperiores architecto excepturi fuga laborum placeat eligendi?
        </p>
        <a href="#" target="_blank" class="project-link">Check it Out</a>
      </div>
    </div>
  </section>
  <!--Contact Section-->
  <section class="contact" id="contact">
    <h2>Get In Touch With Me</h2>
    <div class="contact-form-container ">
      <div class="contact-form">
        <form action="https://formspree.io/f/xyylngw" method="POST"
          <div class="form-control">
            <label for="name">Name</label>
            <input
              type="text"
              id="name"
              name="sender-name"
              placeholder="Enter Your Name"
              class="input-field"
              required/>
          </div>
          <div class="form-control">
            <label for="name">Email</label>
            <input
              type="email"
              id="email"
              name="sender-email"
              placeholder="Enter Your Email"
              class="input-field"
              required/>
          </div>
          <div class="form-control">
            <label for="name">Message</label>
            <textarea
              id="message"
              cols="60"
              rows="10"
              placeholder="Enter Your Message"
              name="message"
              class="input-field"
              required></textarea>
          </div>
          <input 
            type="submit"
            value="Submit" 
            id="submit-btn"
            class="submit-btn"/>
        </form>
      </div>
    </div>
  </section>
  <!--Social Accounts- Fixed to the right-->
  <div class="socials">
    <a href="#" target="_blank"><img
      src="assets/icons/icons8-facebook.gif"
      alt="facebook"
      loading="lazy"
      class="socicon"/>
    </a>
    <a href="#" target="_blank"><img
      src="assets/icons/icons8-twitter.gif"
      alt="twitter"
      loading="lazy"
      class="socicon"/>
    </a>
    <a href="#" target="_blank"><img
      src="assets/icons/icons8-instagram.gif"
      alt="instagram"
      loading="lazy"
      class="socicon"/>
    </a>
    <a href="#" target="_blank"><img
      src="assets/icons/icons8-linkedin.gif"
      alt="twitter"
      loading="lazy"
      class="socicon"/>
    </a>
  </div>
  <!--Scroll to top-->
  <i class="scroll-up" id="scroll-up"
    ><img src="assets/icons/icons8-scroll-up.gif"
      class="socicon up-arrow"
      alt="scroll-up"
      /></i>
  <!--Footer Section-->
  <footer>
          <p class="copy">&copy; Copyright 2021</p>
          <p class="copy">
            Built with &#x2661; by 
            <a href ="https://www.basicode.eu" target="_blank">Basicode</a>
          </p>
  </footer>
  <!-- Website Scripts-->
<script>
  // scroll to top functionality
const scrollUp = document.querySelector("#scroll-up");

scrollUp.addEventListener("click", () => {
  window.scrollTo({
    top: 0,
    left: 0,
    behavior:"smooth",
  });
});
</script>
<script>
const menu = document.querySelector(".menu");
const menuItems = document.querySelectorAll(".menuItem");
const hamburger= document.querySelector(".hamburger");
const closeIcon= document.querySelector(".closeIcon");
const menuIcon = document.querySelector(".menuIcon");

function toggleMenu() {
  if (menu.classList.contains("showMenu")) {
    menu.classList.remove("showMenu");
    closeIcon.style.display = "none";
    menuIcon.style.display = "block";
  } else {
    menu.classList.add("showMenu");
    closeIcon.style.display = "block";
    menuIcon.style.display = "none";
  }
}

hamburger.addEventListener("click", toggleMenu);
menuItems.forEach( 
  function(menuItem) { 
    menuItem.addEventListener("click", toggleMenu);
  }
)
</script>
  <script src="assets/js/app.js"></script>
  <!--Ion icons scripts-->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>
</html>
