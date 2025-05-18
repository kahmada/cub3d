<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Khadija Ahmada - UI/UX Designer & Frontend Developer</title>
    <meta name="description" content="Portfolio of Khadija Ahmada - UI/UX Designer and Frontend Developer specializing in creating beautiful, responsive websites and applications." />
    <meta name="author" content="Khadija Ahmada" />

    <meta property="og:title" content="Khadija Ahmada - UI/UX Designer & Frontend Developer" />
    <meta property="og:description" content="Portfolio of Khadija Ahmada - UI/UX Designer and Frontend Developer specializing in creating beautiful, responsive websites and applications." />
    <meta property="og:type" content="website" />
    <meta property="og:image" content="https://lovable.dev/opengraph-image-p98pqg.png" />

    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:site" content="@khadija_ahmada" />
    <meta name="twitter:image" content="https://lovable.dev/opengraph-image-p98pqg.png" />
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  </head>

  <body>
    <div id="root"></div>
    <!-- IMPORTANT: DO NOT REMOVE THIS SCRIPT TAG OR THIS VERY COMMENT! -->
    <script src="https://cdn.gpteng.co/gptengineer.js" type="module"></script>
    <script type="module" src="/src/main.tsx"></script>
  </body>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Khadija Ahmada - UI/UX Designer & Frontend Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    /* Reset and base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    html {
      scroll-behavior: smooth;
    }
    
    body {
      font-family: 'Inter', sans-serif;
      background-color: #080323;
      color: #fff;
      overflow-x: hidden;
    }
    
    a {
      text-decoration: none;
      color: inherit;
    }
    
    .container {
      width: 100%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    
    section {
      padding: 80px 0;
    }
    
    /* Header styles */
    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      padding: 20px 0;
      transition: all 0.3s ease;
      z-index: 1000;
    }
    
    header.scrolled {
      background-color: rgba(26, 31, 44, 0.8);
      backdrop-filter: blur(10px);
      padding: 12px 0;
      box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
    }
    
    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      background-color: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(5px);
      border-radius: 50px;
      padding: 8px 16px;
    }
    
    nav ul li {
      margin: 0 10px;
      position: relative;
    }
    
    nav ul li a {
      font-size: 16px;
      opacity: 0.8;
      transition: opacity 0.3s;
      padding: 5px 10px;
    }
    
    nav ul li a:hover {
      opacity: 1;
    }
    
    nav ul li.active a {
      opacity: 1;
      font-weight: 500;
    }
    
    nav ul li.active::after {
      content: '';
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 100%;
      height: 2px;
      background: linear-gradient(to right, #9b87f5, #f586a4);
      border-radius: 2px;
    }
    
    /* Hero section */
    .hero {
      min-height: 80vh;
      display: flex;
      align-items: center;
      padding-top: 80px;
      position: relative;
      overflow: hidden;
    }
    
    .hero-content {
      display: flex;
      flex-direction: column;
      gap: 40px;
      flex-wrap: wrap;
    }
    
    @media (min-width: 768px) {
      .hero-content {
        flex-direction: row;
      }
    }
    
    .hero-text {
      flex: 1;
      max-width: 600px;
    }
    
    .hero-text h1 {
      font-size: 48px;
      margin-bottom: 20px;
      line-height: 1.2;
    }
    
    .gradient-text {
      background: linear-gradient(to right, #9b87f5, #f586a4);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }
    
    .hero-text p {
      font-size: 18px;
      opacity: 0.8;
      margin-bottom: 30px;
      line-height: 1.6;
    }
    
    .cta-button {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: linear-gradient(to right, #9b87f5, #f586a4);
      color: white;
      padding: 12px 24px;
      border-radius: 50px;
      font-weight: 500;
      transition: all 0.3s ease;
    }
    
    .cta-button:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 25px rgba(155, 135, 245, 0.3);
    }
    
    .hero-image {
      flex: 1;
      position: relative;
    }
    
    .profile-img {
      width: 500px;
      height: 400px;
      /* max-width: 400px; */
      aspect-ratio: 1;
      object-fit: cover;
      border-radius: 16px;
      border: 4px solid rgba(238, 8, 8, 0.1);
      transform: rotate(3deg);
      animation: float 6s ease-in-out infinite;
    }
    
    .blur-circle {
      position: absolute;
      width: 250px;
      height: 250px;
      border-radius: 50%;
      filter: blur(80px);
      z-index: -1;
    }
    
    .blur-circle-1 {
      background-color: rgba(155, 135, 245, 0.2);
      top: 10%;
      right: -5%;
      animation: spin 8s linear infinite;
    }
    
    .blur-circle-2 {
      background-color: rgba(245, 134, 164, 0.2);
      bottom: -10%;
      right: 20%;
    }
    
    /* About section */
    .about {
      padding:  0;
      position: relative;
      overflow: hidden;
    }
    
    .section-title {
      font-size: 36px;
      text-align: center;
      margin-bottom: 20px;
    }
    
    .section-desc {
      text-align: center;
      max-width: 600px;
      margin: 0 auto 60px;
      opacity: 0.8;
    }
    
    .skills-container {
      display: flex;
      /* flex-wrap: wrap; */
      justify-content: center;
      gap: 60px;
    }
    
    .skill-bubble {
      background: linear-gradient(135deg, rgba(0, 0, 0, 0.4), rgba(220, 129, 223, 0.4));
      backdrop-filter: blur(10px);
      border-radius: 10px;
      width: 350px;
      height: 350px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }
    
    .skill-bubble h3 {
      margin-bottom: 30px;
      color: rgb(149, 74, 164);
    }
    
    .skill-bubble p {
      /* margin-bottom: 120px; */
      color: #c9b4c5;
      font-size: 14px;
      opacity: 8;
    }
    
    /* Projects section */
    .projects {
      padding: 120px 0;
    }
    
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 24px;
      margin-top: 60px;
    }
    
    .project-card {
      border-radius: 12px;
      overflow: hidden;
      transition: all 0.3s ease;
    }
    
    .project-img-container {
      aspect-ratio: 16/9;
      overflow: hidden;
    }
    
    .project-img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.5s ease;
    }
    
    .project-card:hover .project-img {
      transform: scale(1.05);
    }
    
    .project-info {
      padding: 16px;
      background-color: rgba(0, 0, 0, 0.5);
      backdrop-filter: blur(5px);
    }
    
    .project-info h3 {
      margin-bottom: 8px;
    }
    
    .project-meta {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 8px;
    }
    
    .project-category {
      opacity: 0.7;
      font-size: 14px;
    }
    
    .project-link {
      color: #9b87f5;
      font-size: 14px;
      display: flex;
      align-items: center;
      gap: 4px;
    }
    
    .project-link:hover {
      color: #f586a4;
    }
    
    /* Process section */
    .process {
      padding: 120px 0;
    }
    
    .process-content {
      display: flex;
      flex-direction: column;
      gap: 40px;
    }
    
    @media (min-width: 768px) {
      .process-content {
        flex-direction: row;
      }
      
      .process-text, .process-image {
        flex: 1;
      }
    }
    
    .process-text {
      display: flex;
      flex-direction: column;
      gap: 24px;
    }
    
    .process-text p {
      font-size: 18px;
      line-height: 1.6;
    }
    
    .process-list {
      list-style-position: inside;
      display: flex;
      flex-direction: column;
      gap: 12px;
      opacity: 0.8;
      padding-left: 20px;
    }
    
    .process-image {
      position: relative;
    }
    
    .process-img {
      max-width: 100%;
      border-radius: 12px;
      border: 4px solid rgba(155, 135, 245, 0.2);
    }
    
    .process-quote {
      position: absolute;
      bottom: -40px;
      right: -40px;
      max-width: 300px;
      padding: 16px;
      background: linear-gradient(135deg, rgba(155, 135, 245, 0.2), rgba(245, 134, 164, 0.2));
      backdrop-filter: blur(10px);
      border-radius: 12px;
      border: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    /* Contact section */
    .contact {
      padding: 120px 0;
    }
    
    .contact-form {
      max-width: 500px;
      margin: 0 auto;
      background-color: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(5px);
      padding: 32px;
      border-radius: 16px;
      border: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    .form-group {
      margin-bottom: 20px;
    }
    
    .form-group label {
      display: block;
      margin-bottom: 8px;
      font-size: 14px;
      font-weight: 500;
    }
    
    .form-group input,
    .form-group textarea {
      width: 100%;
      padding: 12px 16px;
      border-radius: 8px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      background-color: rgba(0, 0, 0, 0.3);
      color: white;
      font-family: 'Inter', sans-serif;
      transition: all 0.3s ease;
    }
    
    .form-group input:focus,
    .form-group textarea:focus {
      outline: none;
      border-color: #9b87f5;
      box-shadow: 0 0 0 2px rgba(155, 135, 245, 0.3);
    }
    
    .form-group textarea {
      min-height: 150px;
      resize: vertical;
    }
    
    .submit-btn {
      width: 100%;
      padding: 12px;
      border: none;
      background: linear-gradient(to right, #9b87f5, #f586a4);
      color: white;
      font-weight: 500;
      border-radius: 8px;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    
    .submit-btn:hover {
      transform: scale(1.02);
      box-shadow: 0 5px 15px rgba(155, 135, 245, 0.3);
    }
    
    .social-links {
      display: flex;
      justify-content: center;
      gap: 24px;
      margin-top: 32px;
      padding-top: 24px;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    .social-link {
      opacity: 0.8;
      transition: all 0.3s ease;
    }
    
    .social-link:hover {
      opacity: 1;
      color: #9b87f5;
      transform: scale(1.1);
    }
    
    /* Footer */
    footer {
      padding: 32px 0;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    .footer-content {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 16px;
    }
    
    @media (min-width: 768px) {
      .footer-content {
        flex-direction: row;
        justify-content: space-between;
      }
    }
    
    .copyright {
      font-size: 14px;
      opacity: 0.6;
    }
    
    .footer-nav ul {
      display: flex;
      gap: 24px;
      list-style: none;
    }
    
    .footer-nav a {
      font-size: 14px;
      opacity: 0.6;
      transition: opacity 0.3s;
    }
    
    .footer-nav a:hover {
      opacity: 1;
    }
    
    /* Rain animation */
    .rain-container {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 1000;
      overflow: hidden;
    }
    
    .raindrop {
      position: absolute;
      top: -20px;
      background: linear-gradient(to bottom, #9b87f5, #f586a4);
      animation: falling linear infinite;
    }
    
    /* Animations */
    @keyframes float {
      0%, 100% { transform: translateY(0) rotate(3deg); }
      50% { transform: translateY(-10px) rotate(3deg); }
    }
    
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    
    @keyframes falling {
      0% {
        transform: translateY(-10px) rotate(0deg);
        opacity: 0;
      }
      10% { opacity: 1; }
      90% { opacity: 1; }
      100% {
        transform: translateY(100vh) rotate(20deg);
        opacity: 0;
      }
    }
    
    /* Animation classes */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.8s ease, transform 0.8s ease;
    }
    
    .fade-in.visible {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body>
  <!-- Rain Animation -->
  <div id="rain-container" class="rain-container"></div>
  
  <!-- Header with navigation -->
  <header id="header">
    <div class="container">
      <nav>
        <ul>
          <li class="active"><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#process">Process</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
  
  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="container">
      <div class="hero-content">
        <div class="hero-text fade-in">
          <h1>I'm <span class="gradient-text">Khadija Ahmada</span>, <br>
          <span class="gradient-text">UI/UX designer and front-end developer</span></h1>
          
          <p>My goal is to create visually appealing, intuitive, and responsive 
          digital experiences. I bring both creativity and technical 
          expertise to every project, from wireframes to fully functional websites.</p>
          
          <a href="#projects" class="cta-button">
            Projects
            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M5 12h14"></path>
              <path d="m12 5 7 7-7 7"></path>
            </svg>
          </a>
        </div>
        
        <div class="hero-image fade-in">
          <div class="blur-circle blur-circle-1"></div>
          <div class="blur-circle blur-circle-2"></div>
          <img src="./img/dija copy.jpg" alt="Khadija Ahmada" class="profile-img">
        </div>
      </div>
    </div>
  </section>
  
  <!-- About Section -->
  <section id="about" class="about">
    <div class="container">
      <h2 class="section-title fade-in">
        About <span class="gradient-text">Me</span>
      </h2>
      
      <p class="section-desc fade-in">
        I specialize in creating engaging digital experiences with an eye for detail and a passion for usability
      </p>
      
      <div class="skills-container">
        <div class="skill-bubble fade-in">
          <h3>Collaboration</h3>
          <p>I'm a flexible team player, comfortable adapting to feedback, shifting priorities, and evolving needs</p>
        </div>
        
        <div class="skill-bubble fade-in">
          <h3>Design Process</h3>
          <p>I love working closely with cross-functional teams to build intuitive and efficient interfaces</p>
        </div>
        
        <div class="skill-bubble fade-in">
          <h3>Tech Stack</h3>
          <p>Figma, HTML/CSS, JavaScript, frameworks (React, Next), C/C++, Docker, Shell</p>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Projects Section -->
  <section id="projects" class="projects">
    <div class="container">
      <h2 class="section-title fade-in">
        Things I've <span class="gradient-text">Built</span>
      </h2>
      
      <p class="section-desc fade-in">
        Explore my portfolio of projects showcasing my skills in UI/UX design and front-end development
      </p>
      
      <div class="project-grid">
        <div class="project-card fade-in">
          <div class="project-img-container">
            <img src="./img/2.png" alt="KaffeeZeit" class="project-img">
          </div>
          <div class="project-info">
            <h3>KaffeeZeit</h3>
            <div class="project-meta">
              <p class="project-category">Trading website</p>
              <a href="https://github.com/kahmada/cub3d.git" class="project-link">
                see the project
                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M5 12h14"></path>
                  <path d="m12 5 7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
        
        <div class="project-card fade-in">
          <div class="project-img-container">
            <img src="./img/11.png" alt="TradeSync" class="project-img">
          </div>
          <div class="project-info">
            <h3>TradeSync</h3>
            <div class="project-meta">
              <p class="project-category">Trading website</p>
              <a href="https://github.com/kahmada/cub3d.git" class="project-link">
                see the project
                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M5 12h14"></path>
                  <path d="m12 5 7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
        
        <div class="project-card fade-in">
          <div class="project-img-container">
            <img src="./img/66.png" alt="CryptoFlow" class="project-img">
          </div>
          <div class="project-info">
            <h3>CryptoFlow</h3>
            <div class="project-meta">
              <p class="project-category">Trading website</p>
              <a href="./pijama/index.html" class="project-link">
                see the project
                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M5 12h14"></path>
                  <path d="m12 5 7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>

        <div class="project-card fade-in">
          <div class="project-img-container">
            <img src="./img/cub.png" alt="CryptoFlow" class="project-img">
          </div>
          <div class="project-info">
            <h3>CryptoFlow</h3>
            <div class="project-meta">
              <p class="project-category">Trading website</p>
              <a href="https://github.com/kahmada/cub3d.git" class="project-link">
                see the project
                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M5 12h14"></path>
                  <path d="m12 5 7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
        <div class="project-card fade-in">
          <div class="project-img-container">
            <img src="./img/minishell.jpeg" alt="CryptoFlow" class="project-img">
          </div>
          <div class="project-info">
            <h3>CryptoFlow</h3>
            <div class="project-meta">
              <p class="project-category">Trading website</p>
              <a href="https://github.com/kahmada/cub3d.git" class="project-link">
                see the project
                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M5 12h14"></path>
                  <path d="m12 5 7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
        
        <div class="project-card fade-in">
          <div class="project-img-container">
            <img src="./img/d2.jpeg" alt="EventHub" class="project-img">
          </div>
          <div class="project-info">
            <h3>EventHub</h3>
            <div class="project-meta">
              <p class="project-category">Trading website</p>
              <a href="https://github.com/kahmada/cub3d.git" class="project-link">
                see the project
                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M5 12h14"></path>
                  <path d="m12 5 7 7-7 7"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Process Section -->
  <section id="process" class="process">
    <div class="container">
      <h2 class="section-title fade-in">
        Behind the <span class="gradient-text">Scenes</span>
      </h2>
      
      <div class="process-content">
        <div class="process-text fade-in">
          <p>
            I combine user research, wireframes, and prototyping 
            to create clean, responsive designs. I work closely with 
            teams and stay flexible through every stage 
            — from concept to launch.
          </p>
          
          <ul class="process-list">
            <li>Thorough user research to understand needs and pain points</li>
            <li>Low and high-fidelity wireframes that establish clear information hierarchy</li>
            <li>Interactive prototypes to test functionality and user flows</li>
            <li>Responsive implementation with clean, maintainable code</li>
            <li>Collaborative approach with continuous feedback loops</li>
          </ul>
        </div>
        
        <div class="process-image fade-in">
          <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b" alt="Design process" class="process-img">
          <div class="process-quote">
            <p>"The best designs come from understanding the problem deeply and iterating quickly based on feedback."</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Contact Section -->
  <section id="contact" class="contact">
    <div class="container">
      <h2 class="section-title fade-in">
        Let's Build <span class="gradient-text">Something Together</span>
      </h2>
      
      <p class="section-desc fade-in">
        Have a project in mind or just want to chat? Feel free to reach out!
      </p>
      
      <div class="contact-form fade-in">
        <form id="contactForm">
          <div class="form-group">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
          </div>
          
          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
          </div>
          
          <div class="form-group">
            <label for="message">Message</label>
            <textarea id="message" name="message" required></textarea>
          </div>
          
          <button type="submit" class="submit-btn">Send Message</button>
        </form>
        
        <div class="social-links">
          <a href="https://github.com/kahmada" class="social-link">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"></path>
              <path d="M9 18c-4.51 2-5-2-7-2"></path>
            </svg>
          </a>
          
          <a href="https://www.linkedin.com/in/khadija-ahmada-4385a6355/" class="social-link">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
              <rect width="4" height="12" x="2" y="9"></rect>
              <circle cx="4" cy="4" r="2"></circle>
            </svg>
          </a>
          
          <a href="mailto:khadijaahmada148@gmail.com" class="social-link">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <rect width="20" height="16" x="2" y="4" rx="2"></rect>
              <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path>
            </svg>
          </a>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Footer -->
  <footer>
    <div class="container">
      <div class="footer-content" style="justify-content: center;">
        <p class="copyright">&copy; 2025 Khadija Ahmada. All rights reserved.</p>
        
        <!-- <div class="footer-nav">
          <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div> -->
      </div>
    </div>
  </footer>
  
  <script>
    // Rain animation
    const createRain = () => {
      const rainContainer = document.getElementById('rain-container');
      const raindropsCount = 50;
      
      for (let i = 0; i < raindropsCount; i++) {
        const drop = document.createElement('div');
        drop.classList.add('raindrop');
        
        // Random properties
        const left = Math.random() * 100;
        const width = Math.random() * 2 + 1;
        const height = Math.random() * 10 + 10;
        const animationDuration = Math.random() * 1 + 0.5;
        const animationDelay = Math.random() * 3;
        const opacity = Math.random() * 0.7 + 0.3;
        
        // Apply styles
        drop.style.left = `${left}%`;
        drop.style.width = `${width}px`;
        drop.style.height = `${height}px`;
        drop.style.animationDuration = `${animationDuration}s`;
        drop.style.animationDelay = `${animationDelay}s`;
        drop.style.opacity = opacity;
        
        rainContainer.appendChild(drop);
      }
      
      // Hide the rain animation after 6 seconds
      setTimeout(() => {
        rainContainer.style.display = 'none';
      }, 6000);
    };
    
    // Scroll effects
    const handleScroll = () => {
      const elements = document.querySelectorAll('.fade-in');
      const header = document.getElementById('header');
      const scrollPosition = window.scrollY;
      
      // Header effect
      if (scrollPosition > 50) {
        header.classList.add('scrolled');
      } else {
        header.classList.remove('scrolled');
      }
      
      // Active navigation links
      const sections = ['home', 'about', 'projects', 'process', 'contact'];
      let currentSection = 'home';
      
      for (const section of sections) {
        const element = document.getElementById(section);
        if (element) {
          const offsetTop = element.offsetTop - 100;
          if (scrollPosition >= offsetTop) {
            currentSection = section;
          }
        }
      }
      
      const navItems = document.querySelectorAll('nav ul li');
      navItems.forEach(item => {
        item.classList.remove('active');
        const link = item.querySelector('a');
        if (link && link.getAttribute('href') === `#${currentSection}`) {
          item.classList.add('active');
        }
      });
      
      // Fade in elements when they become visible
      elements.forEach(element => {
        const elementTop = element.getBoundingClientRect().top;
        const isVisible = elementTop < window.innerHeight - 100;
        
        if (isVisible) {
          element.classList.add('visible');
        }
      });
    };
    
    // Handle form submission
    const handleFormSubmit = (event) => {
      event.preventDefault();
      
      const name = document.getElementById('name').value;
      const email = document.getElementById('email').value;
      const message = document.getElementById('message').value;
      
      console.log('Form submitted:', { name, email, message });
      alert('Thank you for your message! I\'ll get back to you soon.');
      
      event.target.reset();
    };
    
    // Initialize
    document.addEventListener('DOMContentLoaded', () => {
      createRain();
      handleScroll(); // Run once on load
      
      window.addEventListener('scroll', handleScroll);
      
      const contactForm = document.getElementById('contactForm');
      if (contactForm) {
        contactForm.addEventListener('submit', handleFormSubmit);
      }
    });
  </script>
</body>
</html>
