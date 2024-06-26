<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
    <title>Welcome to my Website</title>
  </head>
  <body>
    <nav>
      <div class="nav__bar">
        <a href="#"><span class="logo nav__logo">C</span> Carlo</a>
        <div class="nav__menu__btn" id="menu-btn">
          <i class="ri-menu-3-line"></i>
        </div>
      </div>
      <ul class="nav__links" id="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#certificates">Certificates</a></li>
        <li><a href="OJT.EXP - Copy.html">Practicum</a></li>
        <li><a href="#contact" class="btn">Contact</a></li>
      </ul>
      <a href="#contact" class="btn btn__large">Contact</a>
    </nav>
    <header class="section__container header__container" id="home">
      <div class="header__image">
        <img src="assets/Header (3).jpg" alt="header" />
      </div>
      <div class="header__content">
        <div>
          <h1>Carlo<br />Web<br />Designer</h1>
        </div>
        <p class="section__description">
          I'm a dedicated web developer with a creative flair and a penchant for
          turning lines of code into captivating online experiences. My journey
          in the digital realm began years ago, and I've since honed my skills
          in front-end development.
        </p>
        <div class="header__btn">
          <button class="btn">Hire Me Now</button>
        </div>
      </div>
    </header>
    <section class="section__container about__container" id="about">
      <div class="about__image">
        <img src="assets/bg.png" alt="bg" class="about__bg-1" />
        <img src="assets/bg.png" alt="bg" class="about__bg-2" />
        <img src="assets/About.jpg" alt="about" class="about__img" />
      </div>
      <div class="about__content">
        <h2 class="section__header">Bit About Me</h2>
        <p class="section__description">
          I am an enthusiastic web developer with a strong creative instinct and the ability to bring ideas to life. 
          My venture into web development started with a deep interest in coding and design, 
          evolving into a profession where I seamlessly integrate aesthetics with practicality. 
          Emphasizing user experience and a continuous effort to remain informed about current industry advancements, 
          I am devoted to crafting web solutions that surpass expectations.
        </p>
        <div class="about__btn">
          <p class="services-price-text mb-0"><a class="custom-btn btn custom-link" href="AGBONG_CV (1).pdf"> DOWNLOAD CV</a></p>
        </div>
      </div>
    </section>
    <section class="section__container service__container" id="portfolio">
      <h2 class="section__header">Portfolio</h2>
      <p class="section__description">
        Explore a showcase of my diverse projects, demonstrating my skills in
        web development, design, datasets and beyond. Each project reflects my passion
        for creating impactful and innovative digital experiences.
      </p>
      <div class="service__grid">
        <div class="service__card">
          <img src="XAMPP.png" alt="portfolio" />
          <span><i class="ri-window-fill"></i></span>
          <h4>XAMPP</h4>
          <p>
            XAMPP is a cross-platform web server that is free and open-source. XAMPP is a short form for Cross-Platform, Apache, MySQL, PHP, and Perl. 
            XAMPP is a popular cross-platform web server that allows programmers to write and test their code on a local webserver.
          </p>
        </div>
        <div class="service__card">
          <img src="ANDROID STUDIO.jpg" alt="portfolio" />
          <span><i class="ri-store-line"></i></span>
          <h4>ANDROID STUDIO</h4>
          <p>
            Android Studio is the official Integrated Development Environment (IDE) for Android App development. It is a powerful tool that allows developers to build high-quality applications for the Android platform.
          </p>
        </div>
        <div class="service__card">
          <img src="/VSCODE.jpg" alt="portfolio" />
          <span><i class="ri-smartphone-line"></i></span>
          <h4>VS CODE</h4>
          <p>
            Visual Studio (VS) Code is an open-source code editor primarily used to correct and repair cloud and web applications coding errors. 
            VS Code is developed by Microsoft and supports the macOS, Linux, and Windows operating systems. VS Code’s tools can be used to enhance the functionality of any written code.
          </p>
        </div>
        <div class="service__card">
          <img src="SPARK AR.png" alt="portfolio" />
          <span><i class="ri-share-fill"></i></span>
          <h4>META SPARK AR</h4>
          <p>
            Spark AR is a Facebook studio tool that allows users to build their own virtual and augmented reality effects. 
            Facebook has been consistently adding features to the platform since its introduction in 2017.
          </p>
        </div>
        <div class="service__card">
          <img src="ROBOFLOW.jpg" alt="portfolio" />
          <span><i class="ri-seo-line"></i></span>
          <h4>ROBOFLOW</h4>
          <p>
            Roboflow is an end-to-end computer vision platform that simplifies the process of building computer vision models. 
            Whether you’re a seasoned developer or just starting out, Roboflow empowers you to create your own computer vision applications.
          </p>
        </div>
        <div class="service__card">
          <img src="PACKET TRACER.jpg" alt="portfolio" />
          <span><i class="ri-share-circle-line"></i></span>
          <h4>CISCO PACKET TRACER</h4>
          <p>
            Packet Tracer is a cross-platform visual simulation tool designed by Cisco Systems that allows users to create network topologies and imitate modern computer networks.
            The software allows users to simulate the configuration of Cisco routers and switches using a simulated command line interface.
          </p>
        </div>
      </div>
    </section>
    <section class="section__container certificates__container" id="certificates">
      <h2 class="section__header">Certificates</h2>
      <p class="section__description">
        Acquiring certificates not only underscores my commitment to ongoing education but also serves as tangible evidence of my proactive approach to advancing my skills and knowledge within the field. 
        These certifications represent the culmination of dedicated effort and demonstrate my readiness to tackle new challenges with confidence and expertise. Furthermore, they validate my proficiency in specific areas, bolstering 
        my credibility as a competent and capable professional in the eyes of employers, clients, and peers alike.
      </p>
      <div class="portfolio__grid">
        <div class="portfolio__card">
          <img src="assets/Certificate1.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate2.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate3.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate4.JPG" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate5.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate6.png" alt="portfolio" />
        </div>
      </div>
      <section class="section__container service__container" id="portfolio">
        <h2 class="section__header">PROJECTS</h2>
        <p class="section__description">
          During my college days we made a lot of fun in programming course experience such as database,system adminstration, web development, game development,virtual reality and augmented reality this will showcase the dedication of my hardwork.
        </p>
        <div class="service__grid">
          <div class="service__card">
            <img src="VR.png" alt="portfolio" />
            <span><i class="ri-window-fill"></i></span>
            <h4>VIRTUAL REALITY</h4>
            <p>
             This was our project in 2nd year college to create a visual reality website through the use of vs code studio and internet resources.
            </p>
          </div>
          <div class="service__card">
            <img src="EXTENSION.png" alt="portfolio" />
            <span><i class="ri-store-line"></i></span>
            <h4>GOOGLE EXTENSION</h4>
            <p>
              One of my favorite project i created such extension in google that determine what is your weight base on your height and it appears if you are normal, above normal or obese.
            </p>
          </div>
          <div class="service__card">
            <img src="SYSAD.png" alt="portfolio" />
            <span><i class="ri-smartphone-line"></i></span>
            <h4>VIRTUAL MACHINE</h4>
            <p>
              During my 3rd year our professor gave us a project that creates a multi user in the windows 10 OS using Virtual Box Machine.
            </p>
          </div>
          <div class="service__card">
            <img src="BLENDER.png" alt="portfolio" />
            <span><i class="ri-share-fill"></i></span>
            <h4>BLENDER</h4>
            <p>
              This was one of my highlight projects before i created a lion masterpiece using the Blender 3.4v and adding movements and music effect to make it more realistic.
            </p>
          </div>
          <div class="service__card">
            <img src="ROBO.png" alt="portfolio" />
            <span><i class="ri-seo-line"></i></span>
            <h4>DATASET</h4>
            <p>
              Our capstone project sample dataset that i has made of several weeks to finish it is quiet hard at the start because you need to track one by one the object which is the fruitfly to get the specified numbers in total and gathered all the data using computer vision Roboflow.
            </p>
          </div>
          <div class="service__card">
            <img src="SPARK.png" alt="portfolio" />
            <span><i class="ri-share-circle-line"></i></span>
            <h4>FACE AI</h4>
            <p>
              Face AI is a fun project to create because you need to create it from the scratch and make your own idea of filter using Meta Spark Studio or Spark AR, It allows to use when it comes to upload from facebook or messenger once the filter uploaded the user may use the filter created in Spark AR it also allows multiple user if they have a link to the project.
            </p>
          </div>
        </div>
    </section>
   </div>
   <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/0kbGjTCuckVdXYU2VfyaDe?utm_source=generator" right="50%" left="505" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy">center</iframe>   
  </div>
    <section class="section__container contact__container" id="contact">
      <div class="logo">🡹</div>
      <h2 class="section__header">Let's Talk With Me!</h2>
      <p class="section__description">
        An open invitation to connect, and exploring collaborative opportunities
        on my personal portfolio website.
      </p>
      <div class="contact__socials">
        <a href="https://www.facebook.com/carlo.agbong"><i class="ri-facebook-fill"></i></a>
        <a href="https://www.instagram.com/carloescobio/"><i class="ri-instagram-fill"></i></a>
        <a href="https://github.com/IT-STATIC22"><i class="ri-github-fill"></i></a>
        <a href="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox"><i class="ri-google-fill"></i></a>
        <a href="https://www.messenger.com/t/7301008556595030"><i class="ri-messenger-line"></i></a>
      </div>
    </section>
    <footer class="footer">
      Copyright © 2024 Web Design Mastery. All rights reserved.
    </footer>
    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="main.js"></script>
  </body>
</html>


