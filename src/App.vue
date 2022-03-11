<template>
  <header>
    <navbar class="navbar">
      <div class="nav_links">
        <div class="logo">
          <a href="#">
            <h2 class="logo_text">
              Developer<span class="logo_text1">_o7</span>
            </h2>
          </a>
        </div>
        <div class="links">
          <a href="#" class="link">About</a>
          <a href="#passions" class="link">Passions</a>
          <a href="#portfolio" class="link">Portfolio</a>

          <a href="#contact" class="btn">Contact</a>
        </div>
      </div>
    </navbar>

    <div class="container col-12 flex">
      <img class="back1" src="./assets/img/back1.png" alt="404" />
      <div class="header_text col-7 text-2xl">
        <h3 class="header_n1">Hi !</h3>
        <h1 class="header_title">I’m Muzaffar. a Front-End Developer</h1>
        <p class="header_subtitle">
          Front-End developer based in Jizzakh, Uzbekistan I’am coding with a
          clean and beautiful problem solving in mind.
        </p>
        <img class="back3" src="./assets/img/back1.png" alt="404" />
      </div>

      <div class="header_img col-5">
        <img class="back2" src="./assets/img/back2.png" alt="404" />
        <img src="./assets/img/heroImg 1.png" alt="404" />
      </div>
    </div>
  </header>

  <!-- Additional Page -->

  <div id="passions">
    <h2 class="v-25">Additional <span class="pas">passions</span></h2>
  </div>

  <div class="container flex">
    <!-- card-1 -->
    <div class="card">
      <img class="back4" src="./assets/img/back2.png" alt="404" />
      <div class="card_img">
        <img src="./assets/img/img1.png" alt="404" />
      </div>
      <div class="card_title"><span>Front-End</span> Developer</div>
      <div class="card_subtitle">(Sass, Bootstrap, Tailwind)</div>
    </div>

    <!-- card-2 -->
    <div class="card">
      <div class="card_img">
        <img src="./assets/img/img2.png" alt="404" />
      </div>
      <div class="card_title"><span>Back-End</span> Developer</div>
      <div class="card_subtitle">(NodeJS, Laravel, Codeigniter)</div>
      <img class="back5" src="./assets/img/back2.png" alt="404" />
    </div>

    <!-- card-3 -->
    <div class="card">
      <div class="card_img">
        <img src="./assets/img/img3.png" alt="404" />
      </div>
      <div class="card_title"><span>UI/UX</span> Designer</div>
      <div class="card_subtitle">(Figma, Zeplin, Adobe XD)</div>
    </div>
  </div>

  <!--  Portfolio page -->

  <div id="portfolio">
    <h2 class="v-30">My <span class="pas1"> portfolio</span></h2>

    <div class="container flex">
      <!-- card-1 -->
      <div class="card">
        <img class="back6" src="./assets/img/back2.png" alt="404" />
        <div class="card_email flex">
          <img src="./assets/img/e-mail.png" alt="404" />
          <p class="email_text">Sendpay</p>
        </div>
        <img class="card2" src="./assets/img/Ellipse 1.png" />
        <img class="card3" src="./assets/img/card1.png" />
      </div>

      <!-- card-2 -->
      <div class="card">
        <div class="card_text flex">
          <p>E- Commerce</p>
          <small>Website</small>
        </div>
        <img class="card2" src="./assets/img/Ellipse 2.png" />
        <img class="card3" src="./assets/img/card2.png" />
      </div>

      <!-- card-3 -->
      <div class="card">
        <div class="card_beats flex">
          <img src="./assets/img/beats.png" alt="404" />
        </div>
        <img class="card2" src="./assets/img/Ellipse 3.png" />
        <img class="card3" src="./assets/img/card3.png" />
        <img class="back7" src="./assets/img/back2.png" alt="404" />
      </div>
    </div>
  </div>

  <!-- Contact page -->

  <div id="contact">
    <h2 class="v-30">Contact <span class="pas1">Me</span></h2>

    <div class="container col-12 flex">
      <div class="contact_card col-3">
        <svg
          class="maker"
          viewBox="0 0 200 200"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill="#FF0066"
            d="M42.6,-48C57.8,-38.1,74.4,-27.1,79.8,-11.8C85.2,3.4,79.3,22.9,67.1,33.7C54.9,44.4,36.3,46.5,19.5,51.7C2.8,56.9,-12,65.4,-28.2,64.9C-44.4,64.5,-62,55.2,-73.9,40.1C-85.7,24.9,-91.9,3.8,-84.1,-10.4C-76.3,-24.6,-54.6,-31.9,-38.3,-41.6C-22,-51.4,-11,-63.4,1.4,-65.1C13.7,-66.7,27.5,-57.9,42.6,-48Z"
            transform="translate(100 100)"
          />
        </svg>
        <a href="https://github.com/Developer-o7/">
          <div class="contact_icon"><i class="fa-brands fa-github"></i></div>
        </a>
      </div>

      <div class="contact_card col-3">
        <svg
          class="maker"
          viewBox="0 0 200 200"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill="#FF0066"
            d="M42.6,-48C57.8,-38.1,74.4,-27.1,79.8,-11.8C85.2,3.4,79.3,22.9,67.1,33.7C54.9,44.4,36.3,46.5,19.5,51.7C2.8,56.9,-12,65.4,-28.2,64.9C-44.4,64.5,-62,55.2,-73.9,40.1C-85.7,24.9,-91.9,3.8,-84.1,-10.4C-76.3,-24.6,-54.6,-31.9,-38.3,-41.6C-22,-51.4,-11,-63.4,1.4,-65.1C13.7,-66.7,27.5,-57.9,42.6,-48Z"
            transform="translate(100 100)"
          />
        </svg>
        <a href="https://instagram.com/muzaffar_8057"
          ><div class="contact_icon"><i class="fa-brands fa-instagram"></i></div
        ></a>
      </div>

      <div class="contact_card col-3">
        <svg
          class="maker"
          viewBox="0 0 200 200"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill="#FF0066"
            d="M42.6,-48C57.8,-38.1,74.4,-27.1,79.8,-11.8C85.2,3.4,79.3,22.9,67.1,33.7C54.9,44.4,36.3,46.5,19.5,51.7C2.8,56.9,-12,65.4,-28.2,64.9C-44.4,64.5,-62,55.2,-73.9,40.1C-85.7,24.9,-91.9,3.8,-84.1,-10.4C-76.3,-24.6,-54.6,-31.9,-38.3,-41.6C-22,-51.4,-11,-63.4,1.4,-65.1C13.7,-66.7,27.5,-57.9,42.6,-48Z"
            transform="translate(100 100)"
          />
        </svg>
        <a href="https://muzaffarmasordinov@gmail.com">
          <div class="contact_icon"><i class="fa-solid fa-envelope"></i></div
        ></a>
      </div>

      <div class="contact_card col-3">
        <svg
          class="maker"
          viewBox="0 0 200 200"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill="#FF0066"
            d="M42.6,-48C57.8,-38.1,74.4,-27.1,79.8,-11.8C85.2,3.4,79.3,22.9,67.1,33.7C54.9,44.4,36.3,46.5,19.5,51.7C2.8,56.9,-12,65.4,-28.2,64.9C-44.4,64.5,-62,55.2,-73.9,40.1C-85.7,24.9,-91.9,3.8,-84.1,-10.4C-76.3,-24.6,-54.6,-31.9,-38.3,-41.6C-22,-51.4,-11,-63.4,1.4,-65.1C13.7,-66.7,27.5,-57.9,42.6,-48Z"
            transform="translate(100 100)"
          />
        </svg>
        <a href="+998 99 133 80 57"
          ><div class="contact_icon"><i class="fa-solid fa-phone"></i></div
        ></a>
      </div>
    </div>
  </div>

  <footer>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <path
        fill="#ff0066"
        fill-opacity="1"
        d="M0,192L34.3,192C68.6,192,137,192,206,181.3C274.3,171,343,149,411,154.7C480,160,549,192,617,208C685.7,224,754,224,823,202.7C891.4,181,960,139,1029,128C1097.1,117,1166,139,1234,149.3C1302.9,160,1371,160,1406,160L1440,160L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z"
      ></path>
    </svg>
    <h3 class="design">
      Design by : <span class="footer_design"> Developer_o7</span>
    </h3>
  </footer>
</template>

<script setup>
</script>