Ex-01 : To-create-a-web-Portfolio-CV-using-HTML-CSS
Aim:-
To create a web Portfolio CV using HTML CSS

Algorithm:-
Step 1:
index.html: The main HTML file.

Step 2:
style.css: The CSS file for styling the portfolio.

Step 3:
Add content to the portfolio

Step 4:
Link the CSS file

Step 5:
Style the portfolio using CSS

Step 6:
Publish your portfolio

Program:-
Index.html
```
<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.0/css/line.css">
        <link rel="stylesheet" href="./packages/css/swiper-bundle.min.css">
        <link rel="stylesheet" href="./packages/css/styles.css">

        <title>Sarankumar</title>
    </head>
    <body>
        <!--==================== HEADER ====================-->
        <header class="header" id="header">
            <nav class="nav container">
                <a href="#" class="nav__logo">ANTONYJOHNKENNADY D</a>
                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list grid">
                        <li class="nav__item">
                            <a href="#home" class="nav__link">
                                <i class="uil uil-estate nav__icon"></i>Home
                            </a>
                        </li>
                        <li class="nav__item">
                            <a href="#about" class="nav__link">
                                <i class="uil uil-user nav__icon"></i>About
                            </a>
                        </li>
                        <li class="nav__item">
                            <a href="#skills" class="nav__link">
                                <i class="uil uil-file-alt nav__icon"></i>Skills
                            </a>
                        </li>

                        <li class="nav__item">
                            <a href="#contact" class="nav__link">
                                <i class="uil uil-message nav__icon"></i>Contact                               
                            </a>
                        </li>
                    </ul>
                    <i class="uil uil-times nav__close" id="nav-close"></i>
                </div>
                </div>
            </nav>
        </header>

        <!--==================== MAIN ====================-->
        <main class="main">
            <!--==================== HOME ====================-->
            <section class="home section" id="home">
                <div class="home__container container grid">
                    <div class="home__content grid">
                        <div class="home__social">
                            <a href="https://www.linkedin.com/in/prashanna-sathiyamoorthy-194704153/" target="_blank" class="home__social-icon">
                                <i class="uil uil-linkedin-alt"></i>
                            </a>
                            <a href="https://twitter.com/prashanna01" target="_blank" class="home__social-icon">
                                <i class="uil uil-twitter-alt"></i>
                            </a>
                            <a href="https://www.github.com" target="_blank" class="home__social-icon">
                                <i class="uil uil-github-alt"></i>
                            </a>
                        </div>

                        <div class="home__img">
                            <svg class="home__blob" viewBox="0 0 200 187" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                                <mask id="mask0" mask-type="alpha">
                                    <path d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547 
                                    130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775 
                                    97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666 
                                    0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"/>
                                </mask>
                                <g mask="url(#mask0)">
                                    <path d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 
                                    165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 
                                    129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 
                                    -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"/>
                                    <image class="home__blob-img" x="" xlink:href="packages/images/antoo.jpg"/>
                                </g>
                            </svg>
                        </div>

                        <div class="home__data">
                            <h1 class="home__title">Hi, I'am AntonyJohnKennady D</h1>
                            <h3 class="home__subtitle">Web Developer</h3>
                            <a href="#contact" class="button button--flex home__button">
                                Contact Me<i class="uil uil-message button__icon"></i>
                            </a>
                        </div>
                    </div>

                    <div class="home__scroll">
                        <a href="#about" class="home__scroll-button button--flex">
                            <i class="uil uil-mouse-alt home__scroll-mouse"></i>
                            <span class="home__scroll-name">Scroll Down</span>
                            <i class="uil uil-arrow-down home__scroll-arrow"></i>
                        </a>
                    </div>
                </div>
            </section>

            <!--==================== ABOUT ====================-->
            <section class="about section" id="about">
                <h2 class="section__title">About Me</h2>
                <span class="section__subtitle">My Introduction</span>

                <div class="about__container container grid">
                    <div class="about__data">
                        <p class="about__description">
                            Hello there! I'm AntonyJohnKennady D, a dedicated web developer with a deep love for crafting beautiful and functional websites. I thrive on the creative challenges that web development presents, constantly seeking innovative solutions to bring ideas to life on the digital canvas.
                        </p>
                        <p class="about__description">My journey in web development began 2 Years. Since then, I have honed my skills in front-end and back-end development, embracing the ever-evolving technologies and frameworks that power the web. Whether it's HTML, CSS, JavaScript, or the latest libraries like React and Vue.js, I'm constantly expanding my knowledge to stay ahead in this dynamic field.</p>
                        <p class="about__description">Collaboration is at the heart of my approach to web development. I thrive in interdisciplinary teams, valuing effective communication and the power of collective creativity. I enjoy working closely with designers, UX specialists, and clients to understand their vision and translate it into a digital reality that exceeds expectations.</p>
                    </div>
                </div>
            </section>

            <!--==================== SKILLS ====================-->
            <section class="skills section" id="skills">
                <h2 class="section__title">Skills</h2>
                <span class="section__subtitle">My technical level</span>

                <div class="skills__container container grid">
                    <div>
                         <!--==================== SKILL-1 ====================-->
                        <div class="skills__content skills__open">
                            <div class="skills__header">
                                <i class="uil uil-analytics skills__icon"></i>
                               <div>
                                   <h1 class="skills__title">Web Developer</h1>
                                   <span class="skills__subtitle"></span>
                               </div>

                               <i class="uil uil-angle-down skills__arrow"></i>
                            </div>
                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">Python</h3>
                                        <span class="skills__number">60%</span>
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percentage skills__python"></span>
                                    </div>
                                </div>
                               <div class="skills__data">
                                   <div class="skills__titles">
                                       <h3 class="skills__name">HTML</h3>
                                       <span class="skills__number">90%</span>
                                   </div>
                                   <div class="skills__bar">
                                       <span class="skills__percentage skills__tab"></span>
                                   </div>
                               </div>
                               <div class="skills__data">
                                   <div class="skills__titles">
                                       <h3 class="skills__name">CSS</h3>
                                       <span class="skills__number">90%</span>
                                   </div>
                                   <div class="skills__bar">
                                       <span class="skills__percentage skills__sql"></span>
                                   </div>
                               </div>
                               <div class="skills__data">
                                   <div class="skills__titles">
                                       <h3 class="skills__name">Java</h3>
                                       <span class="skills__number">70%</span>
                                   </div>
                                   <div class="skills__bar">
                                       <span class="skills__percentage skills__google"></span>
                                   </div>
                               </div>
                            </div>
                        </div>
              <!--==================== QUALIFICATION ====================-->
        <section class="qualification__section">
            <h2 class="section__title">Qualification</h2>
            <span class="section__subtitle">My personal journey</span>

            <div class="qualification__container container">
                <div class="qualification__tabs">
                    <div class="qualification__button button--flex qualification__active" data-target='#education'>
                        <i class="uil uil-graduation-cap qualification__icon"></i>
                        Education
                    </div>

                    <div class="qualification__button button--flex" data-target="#work">
                        <i class="uil uil-briefcase-alt qualification__icon"></i>
                        Work
                    </div>
                </div>

                <div class="qualification__sections">
            <!--==================== QUALIFICATION CONTENT 1 ====================-->
            <div class="qualification__content qualification__active" data-content id="education">
             <!--==================== QUALIFICATION 1 ====================--> 
             <div class="qualification__data">
                 <div>
                     <h3 class="qualification__title">B.E </h3>
                     <span class="qualification__subtitle">Saveetha Engineering College</span>
                     <div class="qualification__calendar">
                        <i class="uil uil-calendar-alt"></i>
                        2021 - 2025
                     </div>
                 </div>

                 <div>
                     <span class="qualification__rounder"></span>
                     <span class="qualification__line"></span>
                 </div>
             </div>
             
    
            <!--==================== QUALIFICATION 4 ====================--> 
            <div class="qualification__data">
                <div></div>
                <div>
                    <span class="qualification__rounder"></span>
                   <!-- <span class="qualification__line"></span> -->
                </div>

                <div>
                    <h3 class="qualification__title">Data Analyst Professional Certification</h3>
                    <span class="qualification__subtitle">Google | Coursera - Online</span>
                    <div class="qualification__calendar">
                       <i class="uil uil-calendar-alt"></i>
                       2021
                    </div>
                </div>

                
            </div>
            </div>
            
            <!--==================== QUALIFICATION CONTENT 2 ====================-->
            <div class="qualification__content" data-content id="work">
                <!--==================== QUALIFICATION 1 ====================--> 
                <div class="qualification__data">
                    <div>
                        <h3 class="qualification__title">Trainee Banking Assistant</h3>
                        <span class="qualification__subtitle">DFCC Head Office - Colombo</span>
                        <div class="qualification__calendar">
                           <i class="uil uil-calendar-alt"></i>
                           2017 - 2019
                        </div>
                    </div>
   
                    <div>
                        <span class="qualification__rounder"></span>
                        <span class="qualification__line"></span>
                    </div>
                </div>
                
                <!--==================== QUALIFICATION 2 ====================--> 
                <div class="qualification__data">
                   <div></div>
                   <div>
                      <span class="qualification__rounder"></span>
                      <span class="qualification__line"></span>
                   </div>
   
                   <div>
                       <h3 class="qualification__title">Banking Assistant</h3>
                       <span class="qualification__subtitle">DFCC Head Office - Colombo</span>
                       <div class="qualification__calendar">
                          <i class="uil uil-calendar-alt"></i>
                          2019 - 2020
                       </div>
                   </div>
               </div> 
   
               <!--==================== QUALIFICATION 3 ====================--> 
               <div class="qualification__data">
                   <div>
                       <h3 class="qualification__title">Data Analyst - Digital banking</h3>
                       <span class="qualification__subtitle">DFCC Head Office - Colombo</span>
                       <div class="qualification__calendar">
                          <i class="uil uil-calendar-alt"></i>
                          2020 - Present
                       </div>
                   </div>
   
                   <div>
                       <span class="qualification__rounder"></span>
                       <!-- <span class="qualification__line"></span> -->
                   </div>
               </div> 
          
               </div> 
             
               </div>
            </div>
        </section>
      

        <!--==================== CONTACT ME ====================-->
        <section class="contact section" id="contact">
            <h2 class="section__title">Contact me</h2>
            <span class="section__subtitle">Get in touch</span>

            <div class="contact__container container grid">
                <div>
                    <div class="contact__information">
                        <i class="uil uil-phone-alt contact__icon"></i>

                        <div>
                            <h3 class="contact__title">Call me</h3>
                            <span class="contatc__subtitle">(+91) 7305439794</span>
                        </div>
                    </div>

                    <div class="contact__information">
                        <i class="uil uil-envelope contact__icon"></i>

                        <div>
                            <h3 class="contact__title">E-mail</h3>
                            <span class="contatc__subtitle">antonyjohnkennady2004@gmail.com</span>
                        </div>
                    </div>

                    <div class="contact__information">
                        <i class="uil uil-map-marker contact__icon"></i>

                        <div>
                            <h3 class="contact__title">Location</h3>
                            <span class="contatc__subtitle">Chennai, Tamil Nadu</span>
                        </div>
                    </div>
                </div>

                <form action="" class="contact__form grid">
                    <div class="contact__inputs grid">
                        <div class="contact__content">
                            <label for="" class="contact__label">Name</label>
                            <input type="text" class="contact__input">
                        </div>

                        <div class="contact__content">
                            <label for="" class="contact__label">E-mail</label>
                            <input type="email" class="contact__input">
                        </div>
                    </div>

                    <div class="contact__content">
                        <label for="" class="contact__label">Subject</label>
                        <input type="text" class="contact__input">
                    </div>

                    <div class="contact__content">
                        <label for="" class="contact__label">Description</label>
                        <textarea name="" id="" cols="0" rows="7" class="contact__input"></textarea>
                    </div>

                    <div>
                        <a href="#" class="button button--flex">
                            Send message
                            <i class="uil uil-message button__icon"></i>
                        </a>
                    </div>
                </form>
            </div>

        </section>
    </main>

    <!--==================== FOOTER ====================-->
    <footer class="footer">

        <div class="footer__bg">
            <div class="footer__container container grid">
                <div>
                    <h1 class="footer__title">AntonyJohnKennady D</h1>
                    <span class="footer__subtitle">Web Developer</span>
                </div>

                <ul class="footer__links">
                    <li class="nav__item">
                        <a href="#home" class="nav__link">
                            <i class="uil uil-estate nav__icon"></i>Home
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#about" class="nav__link">
                            <i class="uil uil-user nav__icon"></i>About
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#contact" class="nav__link">
                            <i class="uil uil-message nav__icon"></i>Contact                               
                        </a>
                    </li>
                </ul>

                <div class="footer__socials">
                    <a href="https://www.facebook.com/prashanna.drashan" target="_blank" class="footer__social">
                        <i class="uil uil-facebook"></i>
                    </a>
                    <a href="https://www.instagram.com/prashanna01/" target="_blank" class="footer__social">
                        <i class="uil uil-instagram"></i>
                    </a>
                    <a href="https://twitter.com/prashanna01" target="_blank" class="footer__social">
                        <i class="uil uil-twitter-alt"></i>
                    </a>
                </div>
            </div>
            <p class="footer__copy">&#169; AJK. All rights reserved.</p>
        </div>
    </footer>

    <!--==================== SCROLL TOP ====================-->
    <a href="#" class="scrollup" id="scroll-up">
        <i class="uil uil-arrow-up scrollup__icon"></i>
    </a>

</body>

</html>
```
Style.Css
```
/* ==================== GOOGLE FONTS ====================*/
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap");

/*==================== VARIABLES CSS ====================*/
:root {
  --header-height: 3rem;

  /*========== Colors ==========*/
  /* Change favorite color */
  --hue-color: 190; /*Purple 250 - Green 142 - Blue 230 - Pink 340*/

  /* HSL color mode */
  --first-color: hsl(var(--hue-color), 69%, 61%);
  --first-color-second: hsl(var(--hue-color), 69%, 61%);
  --first-color-alt: hsl(var(--hue-color), 57%, 53%);
  --first-color-lighter: hsl(var(--hue-color), 92%, 85%);
  --title-color: hsl(var(--hue-color), 8%, 15%);
  --text-color: hsl(var(--hue-color), 8%, 45%);
  --text-color-light: hsl(var(--hue-color), 8%, 65%);
  --input-color: hsl(var(--hue-color), 70%, 96%);
  --body-color: hsl(var(--hue-color), 60%, 99%);
  --container-color: #ff5252;
  --scroll-bar-color: hsl(var(--hue-color), 12%, 90%);
  --scroll-thumb-color: hsl(var(--hue-color), 12%, 80%);

  /*========== Font and typography ==========*/
  --body-font: "Poppins", sans-serif;

  /* .5rem = 8px, 1rem = 16px, 1.5rem = 24px ... */
  --big-font-size: 2rem;
  --h1-font-size: 1.5rem;
  --h2-font-size: 1.25rem;
  --h3-font-size: 1.125rem;
  --normal-font-size: 0.938rem;
  --small-font-size: 0.813rem;
  --smaller-font-size: 0.75rem;

  /*========== Font weight ==========*/
  --font-medium: 500;
  --font-semi-bold: 600;

  /*========== Margenes Bottom ==========*/
  /* .25rem = 4px, .5rem = 8px, .75rem = 12px ... */
  --mb-0-25: 0.25rem;
  --mb-0-5: 0.5rem;
  --mb-0-75: 0.75rem;
  --mb-1: 1rem;
  --mb-1-5: 1.5rem;
  --mb-2: 2rem;
  --mb-2-5: 2.5rem;
  --mb-3: 3rem;

  /*========== z index ==========*/
  --z-tooltip: 10;
  --z-fixed: 100;
  --z-modal: 1000;
}

/* Font size for large devices */
@media screen and (min-width: 968px) {
  :root {
    --big-font-size: 3rem;
    --h1-font-size: 2.25rem;
    --h2-font-size: 1.5rem;
    --h3-font-size: 1.25rem;
    --normal-font-size: 1rem;
    --small-font-size: 0.875rem;
    --smaller-font-size: 0.813rem;
  }
}

/*========== Variables Dark theme ==========*/
body.dark-theme {
  /* HSL color mode */
  --first-color-second: hsl(var(--hue-color), 30%, 8%);
  --title-color: hsl(var(--hue-color), 8%, 95%);
  --text-color: hsl(var(--hue-color), 8%, 45%);
  --text-color-light: hsl(var(--hue-color), 8%, 75%);
  --input-color: hsl(var(--hue-color), 29%, 16%);
  --body-color: hsl(var(--hue-color), 28%, 12%);
  --container-color: hsl(var(--hue-color), 29%, 16%);
  --scroll-bar-color: hsl(var(--hue-color), 12%, 48%);
  --scroll-thumb-color: hsl(var(--hue-color), 12%, 36%);
}

/*========== Button Dark/Light ==========*/
.nav__btns {
  display: flex;
  align-items: center;
}

.change-theme {
  font-size: 1.25rem;
  color: var(--title-color);
  margin-right: var(--mb-1);
  cursor: pointer;
}

.change-theme:hover {
  color: var(--first-color);
}

/*==================== BASE ====================*/

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0 0 var(--header-height) 0;
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  background-color: var(--body-color);
  color: var(--text-color);
}

h1,
h2,
h3,
h4 {
  color: var(--title-color);
  font-weight: var(--font-semi-bold);
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

img {
  width: 100%;
  height: auto;
}

/*==================== REUSABLE CSS CLASSES ====================*/
.section {
  padding: 2rem 0 4rem;
  margin-bottom: 40px;
}

.section__title {
  font-size: var(--h1-font-size);
}

.section__subtitle {
  display: block;
  font-size: var(--small-font-size);
  margin-bottom: var(--mb-2);
}

.section__title,
.section__subtitle {
  text-align: center;
}

/*==================== LAYOUT ====================*/

.container {
  max-width: 1300px;
  margin-left: var(--mb-1-5);
  margin-right: var(--mb-1-5);
}

.grid {
  display: grid;
  gap: 1.5rem;
}

.header {
  width: 90%;
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: var(--z-fixed);
  background-color: var(--body-color);
}

/*==================== NAV ====================*/
.nav {
  max-width: 968px;
  height: var(--header-height);
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav__logo,
.nav__toggle {
  color: var(--title-color);
  font-weight: var(--font-medium);
}

.nav__logo:hover {
  color: var(--first-color);
}

.nav__toggle {
  font-size: 1.1rem;
  cursor: pointer;
}

.nav__toggle:hover {
  color: var(--first-color);
}

@media screen and (max-width: 767px) {
  .nav__menu {
    position: fixed;
    bottom: -100%;
    left: 0;
    width: 100%;
    background-color: var(--body-color);
    padding: 2rem 1.5rem 4rem;
    box-shadow: 0 -1px 4px rgba(0, 0, 0, 0.15);
    border-radius: 1.5rem 1.5rem 0 0;
    transition: 0.3s;
  }
}

.nav__list {
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
}
.nav__link {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: var(--small-font-size);
  color: var(--title-color);
  font-weight: var(--font-medium);
}

.nav__link:hover {
  color: var(--first-color);
}

.nav__icon {
  font-size: 1.2rem;
}

.nav__close {
  position: absolute;
  right: 1.3rem;
  bottom: 0.5rem;
  font-size: 1.5rem;
  cursor: pointer;
  color: var(--first-color);
}

.nav__close:hover {
  color: var(--first-color-alt);
}

/* show menu */
.show-menu {
  bottom: 0;
}

/* Active link */
.active-link {
  color: var(--first-color);
}

/* Change background header */
.scroll-header {
  box-shadow: 0 -1px 4px rgba(0, 0, 0, 0.15);
}

/*==================== HOME ====================*/

.home__container {
  gap: 1rem;
}

.home__content {
  grid-template-columns: 0.5fr 3fr;
  padding-top: 3.5rem;
  align-items: center;
}

.home__social {
  display: grid;
  grid-template-columns: max-content;
  row-gap: 1rem;
}

.home__social-icon {
  font-size: 1.25rem;
  color: var(--first-color);
}

.home__social-icon:hover {
  color: var(--first-color-alt);
}

.home__blob {
  width: 200px;
  fill: var(--first-color);
}

.home__blob-img {
  width: 220px;
}

.home__data {
  grid-column: 1/3;
}

.home__title {
  font-size: var(--big-font-size);
}

.home__subtitle {
  font-size: var(--h3-font-size);
  color: var(--text-color);
  font-weight: var(--font-medium);
  margin-bottom: var(--mb-0-75);
}

.home__description {
  margin-bottom: var(--mb-2);
}

.home__scroll {
  display: none;
}

.home__scroll-button {
  color: var(--first-color);
  transition: 0.3s;
}

.home__scroll-button:hover {
  transform: translateY(0.25rem);
}

.home__scroll-mouse {
  font-size: 2rem;
}

.home__scroll-name {
  font-size: var(--small-font-size);
  color: var(--title-color);
  font-weight: var(--font-medium);
  margin-right: var(--mb-0-25);
}

.home__scroll-arrow {
  font-size: 1.25rem;
}
/*==================== BUTTONS ====================*/

.button {
  display: inline-block;
  background-color: var(--first-color);
  color: #ffff;
  padding: 1rem;
  border-radius: 0.5rem;
  font-weight: var(--font-medium);
}

.button:hover {
  background-color: var(--first-color-alt);
}

.button__icon {
  font-size: 1.2rem;
  margin-left: var(--mb-0-5);
  transition: 0.3s;
}

.button--white {
  background-color: #fff;
  color: var(--first-color);
}

.button--white:hover {
  background-color: #fff;
}

.button--flex {
  display: inline-flex;
  align-items: center;
  transition: 0.3s;
}

.button--small {
  padding: 0.75rem 1rem;
}

.button--link {
  padding: 0;
  background-color: transparent;
  color: var(--first-color);
}

.button--link:hover {
  background-color: transparent;
  color: var(--first-color-alt);
}

/*==================== ABOUT ====================*/
.about__img {
  width: 200px;
  border-radius: 0.5rem;
  justify-self: center;
  align-items: center;
}

.about__description {
  text-align: center;
  width: 220%;
  margin-bottom: var(--mb-2-5);
}

.about__info {
  display: flex;
  justify-content: space-evenly;
  margin-bottom: var(--mb-2-5);
}

.about__info-title {
  font-size: var(--h2-font-size);
  font-weight: var(--font-semi-bold);
  color: var(--title-color);
  text-align: center;
  width: 100;
}

.about__info-name {
  font-size: var(--smaller-font-size);
  text-align: center;
  width: 300;
}

.about__info-title,
.about__info-name {
  display: block;
  text-align: center;
}

.about__buttons {
  display: flex;
  justify-content: center;
}

/*==================== SKILLS ====================*/

.skills__container {
  row-gap: 0;
}

.skills__header {
  display: flex;
  align-items: center;
  margin-bottom: var(--mb-2-5);
  cursor: pointer;
}

.skills__icon,
.skills__arrow {
  font-size: 2rem;
  color: var(--first-color);
}

.skills__icon {
  margin-right: var(--mb-0-75);
}

.skills__title {
  font-size: var(--h3-font-size);
}

.skills__subtitle {
  font-size: var(--small-font-size);
  color: var(--text-color-light);
}

.skills__arrow {
  margin-left: auto;
  transition: 0.4s;
}

.skills__list {
  row-gap: 1.5rem;
  padding-left: 2.7rem;
}

.skills__titles {
  display: flex;
  justify-content: space-between;
  margin-bottom: var(--mb-0-5);
}

.skills__name {
  font-size: var(--normal-font-size);
  font-weight: var(--font-medium);
}

.skills__bar,
.skills__percentage {
  height: 5px;
  border-radius: 0.25rem;
}

.skills__bar {
  background-color: var(--first-color-lighter);
}

.skills__percentage {
  display: block;
  background-color: var(--first-color);
}

.skills__html {
  width: 90%;
}

.skills__css {
  width: 80%;
}

.skills__js {
  width: 60%;
}

.skills__wordpress {
  width: 70%;
}

.skills__python {
  width: 60%;
}

.skills__tab {
  width: 70%;
}

.skills__sql {
  width: 50%;
}

.skills__google {
  width: 70%;
}

.skills__bank {
  width: 80%;
}

.skills__google {
  width: 70%;
}

.skills__counter {
  width: 80%;
}

.skills__office {
  width: 90%;
}

.skills__close .skills__list {
  height: 0;
  overflow: hidden;
}

.skills__open .skills__list {
  height: max-content;
  margin-bottom: var(--mb-2-5);
}

.skills__open .skills__arrow {
  transform: rotate(-180deg);
}

/*==================== QUALIFICATION ====================*/
.qualification__tabs {
  display: flex;
  justify-content: space-evenly;
  margin-bottom: var(--mb-2);
}

.qualification__button {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
  cursor: pointer;
}

.qualification__button:hover {
  color: var(--first-color);
}

.qualification__icon {
  font-size: 1.8rem;
  margin-right: var(--mb-0-25);
}

.qualification__data {
  display: grid;
  grid-template-columns: 1fr max-content 1fr;
  column-gap: 1.5rem;
}

.qualification__title {
  font-size: var(--normal-font-size);
  font-weight: var(--font-medium);
}

.qualification__subtitle {
  display: inline-block;
  font-size: var(--small-font-size);
  margin-bottom: var(--mb-1);
}

.qualification__calendar {
  font-size: var(--smaller-font-size);
  color: var(--text-color-light);
  /* margin-bottom: var(--mb-1) */
}

.qualification__rounder {
  display: inline-block;
  width: 13px;
  height: 13px;
  background-color: var(--first-color);
  border-radius: 50%;
}

.qualification__line {
  display: block;
  width: 1px;
  height: 100%;
  background-color: var(--first-color);
  transform: translate(6px, -7px);
}

.qualification__content[data-content] {
  display: none;
}

.qualification__active[data-content] {
  display: block;
}

.qualification__button.qualification__active {
  color: var(--first-color);
}


/*==================== PROJECT IN MIND ====================*/
.project {
  text-align: center;
}

.project__bg {
  background-color: var(--first-color-second);
  padding-top: 3rem;
}

.project__title {
  font-size: var(--h2-font-size);
  margin-bottom: var(--mb-0-75);
}

.project__description {
  margin-bottom: var(--mb-1-5);
}

.project__title,
.project__description {
  color: #fff;
}

.project__img {
  width: 232px;
  justify-self: center;
}

/*==================== TESTIMONIAL ====================*/
.testimonial__data,
.testimonial__header {
  display: flex;
}

.testimonial__data {
  justify-content: space-between;
  margin-bottom: var(--mb-1);
}

.testimonial__img {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  margin-right: var(--mb-0-75);
}

.testimonial__name {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
}

.testimonial__client {
  font-size: var(--small-font-size);
  color: var(--text-color-light);
}

.testimonial__description {
  margin-bottom: var(--mb-2-5);
}

.testimonial__icon-star {
  color: var(--first-color);
}

.swiper-container .swiper-pagination-testimonial {
  bottom: 0;
}

/*==================== CONTACT ME ====================*/
.contact__container {
  row-gap: 3rem;
}

.contact__information {
  display: flex;
  margin-bottom: var(--mb-2);
}

.contact__icon {
  font-size: 1.5rem;
  color: var(--first-color);
  margin-right: var(--mb-0-75);
}

.content__title {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
}

.contact__subtitle {
  font-size: var(--small-font-size);
  color: var(--text-color-light);
}

.contact__content {
  background-color: var(--input-color);
  border-radius: 0.5rem;
  padding: 0.75rem 1rem 0.25rem;
}

.contact__label {
  font-size: var(--smaller-font-size);
  color: var(--title-color);
}

.contact__input {
  width: 100%;
  background-color: var(--input-color);
  color: var(--text-color);
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  border: none;
  outline: none;
  padding: 0.25rem 0.5rem 0.5rem 0;
}

/*==================== FOOTER ====================*/
.footer {
  padding-top: 2rem;
}

.footer__container {
  row-gap: 3.5rem;
}

.footer__bg {
  background-color: var(--first-color-second);
  padding: 2rem 0 3rem;
}

.footer__title {
  font-size: var(--h1-font-size);
  margin-bottom: var(--mb-0-25);
}

.footer__subtitle {
  font-size: var(--small-font-size);
}

.footer__links {
  display: flex;
  flex-direction: column;
  row-gap: 1.5rem;
}

.footer__link:hover {
  color: var(--first-color-lighter);
}

.footer__social {
  font-size: 1.25rem;
  margin-right: var(--mb-1-5);
}

.footer__social:hover {
  color: var(--first-color-lighter);
}

.footer__copy {
  font-size: var(--smaller-font-size);
  text-align: center;
  color: var(white);
  margin-top: var(--mb-3);
}

.footer__title,
.footer__subtitle,
.footer__link,
.footer__social {
  color: #fff;
}

/*========== SCROLL UP ==========*/
.scrollup {
  position: fixed;
  right: 1rem;
  bottom: -20%;
  background-color: var(--first-color);
  opacity: 0.8;
  padding: 0 0.3rem;
  border-radius: 0.4rem;
  z-index: var(--z-tooltip);
  transition: 0.4s;
}

.scrollup:hover {
  background-color: var(--first-color-alt);
}

.scrollup__icon {
  font-size: 1.5rem;
  color: #fff;
}

/* Show scroll */
.show-scroll {
  bottom: 5rem;
}

/*========== SCROLL BAR ==========*/
::-webkit-scrollbar {
  width: 0.6rem;
  background-color: var(--scroll-bar-color);
  border-radius: 0.5rem;
}

::-webkit-scrollbar-thumb {
  background-color: var(--scroll-thumb-color);
  border-radius: 0.5rem;
}

::-webkit-scrollbar-thumb:hover {
  background-color: var(--text-color-light);
}

/*==================== MEDIA QUERIES ====================*/
/* For small devices */
@media screen and (max-width: 380px) {
  .container {
    margin-left: var(--mb-1);
    margin-right: var(--mb-1);
  }

  .nav__menu {
    padding: 2rem 0.25rem 4rem;
  }

  .nav__list {
    column-gap: 0;
  }

  .home__content {
    grid-template-columns: 0.35fr 3fr;
  }

  .home__blob {
    width: 250px;
  }

  .home__social-icon {
    width: 30px;
  }

  .home__subtitle {
    font-size: 24px;
  }

  .home__description {
    font-size: 18px;
  }

  .home__button {
    font-size: 20px;
  }

  .skills__title {
    font-size: var(--normal-font-size);
  }
  .qualification__data {
    gap: 0.5rem;
  }

  .services__container {
    grid-template-columns: max-content;
    justify-content: center;
  }

  .services__content {
    padding-right: 3.5rem;
  }
  .services__modal {
    padding: 0 0.5rem;
  }

  .project__img {
    width: 200px;
  }

  .testimonial__header,
  .testimonial__data {
    flex-direction: column;
    align-items: center;
  }

  .testimonial__img {
    margin-right: 0;
    margin-bottom: var(--mb-0-25);
  }

  .testimonial__data,
  .testimonial__description {
    text-align: center;
  }
}

/* For medium devices */
@media screen and (min-width: 568px) {
  .home__content {
    grid-template-columns: max-content 1fr 1fr;
  }

  .home__data {
    grid-column: initial;
  }
  .home__img {
    order: 1;
    justify-self: center;
  }

  .about__container,
  .skills_container,
  .portfolio__content,
  .project__container,
  .contact__container,
  .footer__container {
    grid-template-columns: repeat(2, 1fr);
  }

  .qualification__sections {
    display: grid;
    grid-template-columns: 0.6fr;
    justify-content: center;
  }

  @media screen and (min-width: 768px) {
    .container {
      margin-left: auto;
      margin-right: auto;
    }

    .body {
      margin: 0;
    }
    .section {
      padding: 6rem 0 2rem;
    }
    .section__subtitle {
      margin-bottom: 4rem;
    }
    .header {
      top: 0;
      bottom: initial;
    }

    .header,
    .main,
    .footer__container {
      padding: 0 1rem;
    }

    .nav {
      height: calc(var(--header-height) + 1.5rem);
      column-gap: 1rem;
    }
    .nav__icon,
    .nav__close,
    .nav__toggle {
      display: none;
    }

    .nav__list {
      display: flex;
      column-gap: 2rem;
    }

    .nav__menu {
      margin-left: auto;
    }
    .change-theme {
      margin: 0;
    }

    .home__container {
      row-gap: 5rem;
    }

    .home__content {
      padding-top: 5.5rem;
      column-gap: 2rem;
    }
    .home__blob {
      width: 270px;
    }
    .home__scroll {
      display: block;
    }
    .home__scroll-button {
      margin-left: 3rem;
    }
    .about__container {
      column-gap: 5rem;
    }
    .about__img {
      width: 350px;
    }
    .about__description {
      text-align: initial;
    }
    .about__info {
      justify-content: space-between;
    }
    .about__buttons {
      justify-content: initial;
    }
    .qualification__tabs {
      justify-content: center;
    }
    .qualification__button {
      margin: 0 var(--mb-1);
    }

    .qualification__sections {
      grid-template-columns: 0.5fr;
    }
    .services__container {
      grid-template-columns: repeat(3, 218px);
      justify-content: center;
    }
    .services__icon {
      font-size: 2rem;
    }
    .services__content {
      padding: 6rem 0 2rem 2.5rem;
    }

    .services__modal-content {
      width: 450px;
    }
    .portfolio__img {
      width: 320px;
    }
    .portfolio__content {
      align-items: center;
    }
    .project {
      text-align: initial;
    }
    .project__bg {
      background: none;
    }
    .project__container {
      background-color: var(--first-color-second);
      border-radius: 1rem;
      padding: 3rem 2.5rem 0;
      grid-template-columns: 1fr max-content;
      column-gap: 3rem;
    }
    .project__data {
      padding-top: 0.8rem;
    }
    .footer__container {
      grid-template-columns: repeat(3, 1fr);
    }
    .footer__bg {
      padding: 3rem 0 3.5rem;
    }

    .footer__links {
      flex-direction: row;
      column-gap: 2rem;
    }
    .footer__socials {
      justify-self: flex-end;
    }
    .footer__copy {
      margin-top: 4.5rem;
      color: rgb(255, 255, 255);
    }
  }
}

/* For large devices */
@media screen and (min-width: 1024px) {
  body {
    margin: 0;
  }

  .header,
  .main,
  .footer__container {
    padding: 0;
  }
  .home__blob {
    width: 320px;
  }
  .home__social {
    transform: translateX(-6rem);
  }
  .services__container {
    grid-template-columns: repeat(3, 238px);
  }
  .portfolio__content {
    column-gap: 5rem;
  }

  .project__container {
    padding-bottom: 30px;
  }

  .swiper-portfolio-icon {
    font-size: 3.5rem;
  }
  .swiper-button-prev {
    left: -3.5rem;
  }
  .swiper-button-next {
    right: -3.5rem;
  }
  .swiper-container-horizontal > .swiper-pagination-bullets {
    bottom: -4.5rem;
  }

  .contact__form {
    width: 460px;
  }
  .contact__inputs {
    grid-template-columns: repeat(2, 1fr);
  }
}


```
Output:-


![op1](https://github.com/AntonyJohnKennady/portfolio/assets/127506261/fb7078d5-6ab9-4f95-a906-7f34014d6fc9)
![op2](https://github.com/AntonyJohnKennady/portfolio/assets/127506261/4974a095-197d-4b5f-86f7-b6e00a804580)
![op3](https://github.com/AntonyJohnKennady/portfolio/assets/127506261/974d29f1-09ab-43f0-9fd6-850602d3f41c)
![op4](https://github.com/AntonyJohnKennady/portfolio/assets/127506261/05bb4778-374c-45cf-81c2-879f4d4b9796)
![op5](https://github.com/AntonyJohnKennady/portfolio/assets/127506261/a7fad792-fca4-46c0-ba93-5e64a776ea72)
![op6](https://github.com/AntonyJohnKennady/portfolio/assets/127506261/4c9d3ecf-d81f-4301-bf25-cfa9b9de41d6)

Result:-
Thus the program To created a web Portfolio/CV using HTML & CSS Successfully.
