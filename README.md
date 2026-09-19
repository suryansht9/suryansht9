<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Suryansh Tripathi | Data Science Student & Developer</title>
  <meta name="description" content="Official portfolio of Suryansh Tripathi, a fifth-semester BCA Data Science student exploring AI, machine learning, web development, app development and automation.">
  <meta name="keywords" content="Suryansh Tripathi, Data Science, Python, React, AI, Machine Learning, Web Developer">
  <link rel="icon" href="logo3.jpg.png">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="assets/vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="assets/vendor/aos/aos.css" rel="stylesheet">
  <link href="assets/css/main.css" rel="stylesheet">

  <style>
    :root { --accent: #6c63ff; --accent-2: #00bfa6; }
    body { font-family: Inter, sans-serif; }
    h1,h2,h3,h4,h5 { font-family: Poppins, sans-serif; }
    .hero-content .eyebrow { color: var(--accent-2); font-weight: 700; letter-spacing: 2px; text-transform: uppercase; }
    .hero-content h1 { font-size: clamp(2.5rem, 6vw, 5rem); font-weight: 800; line-height: 1.08; }
    .hero-content .lead { max-width: 680px; font-size: 1.15rem; }
    .gradient-text { background: linear-gradient(90deg, #6c63ff, #00bfa6); -webkit-background-clip: text; background-clip: text; color: transparent; }
    .feature-card, .learning-card, .project-card { height: 100%; padding: 28px; border-radius: 18px; background: var(--surface-color, #fff); box-shadow: 0 10px 35px rgba(0,0,0,.06); }
    .feature-card .icon, .learning-card .icon { font-size: 2rem; color: var(--accent); margin-bottom: 16px; }
    .skill-pill { display: inline-block; margin: 5px; padding: 9px 14px; border-radius: 30px; background: rgba(108,99,255,.10); color: inherit; font-weight: 600; }
    .timeline-item { border-left: 3px solid var(--accent); padding: 0 0 25px 25px; margin-left: 8px; }
    .cta-box { border-radius: 24px; padding: 45px; background: linear-gradient(135deg, #17152f, #29245b); color: #fff; }
    .btn-accent { background: var(--accent); color: #fff; border: 0; padding: 12px 24px; border-radius: 30px; }
    .btn-accent:hover { background: #5148e8; color: #fff; }
    .section-subtitle { max-width: 720px; margin: 0 auto; }
    .tech-icon { width: 42px; height: 42px; object-fit: contain; margin: 8px; }
    .mini-label { font-size: .8rem; letter-spacing: 1px; text-transform: uppercase; opacity: .7; font-weight: 700; }
  </style>
</head>

<body class="index-page">

<header id="header" class="header dark-background d-flex flex-column">
  <i class="header-toggle d-xl-none bi bi-list"></i>
  <div class="profile-img"><img src="myprofile1.jpeg" alt="Portrait of Suryansh Tripathi" class="img-fluid rounded-circle"></div>
  <a href="index.html" class="logo d-flex align-items-center justify-content-center"><h3 class="sitename">Suryansh Tripathi</h3></a>

  <div class="social-links text-center">
    <a href="https://x.com/suryansht910" aria-label="X"><i class="bi bi-twitter-x"></i></a>
    <a href="https://www.instagram.com/suryansh_tripathii/" aria-label="Instagram"><i class="bi bi-instagram"></i></a>
    <a href="https://www.linkedin.com/in/suryansh-tripathi-5b3384242" aria-label="LinkedIn"><i class="bi bi-linkedin"></i></a>
    <a href="https://github.com/suryansht9" aria-label="GitHub"><i class="bi bi-github"></i></a>
  </div>

  <nav id="navmenu" class="navmenu">
    <ul>
      <li><a href="#hero" class="active"><i class="bi bi-house navicon"></i>Home</a></li>
      <li><a href="#about"><i class="bi bi-person navicon"></i>About</a></li>
      <li><a href="#skills"><i class="bi bi-code-slash navicon"></i>Skills</a></li>
      <li><a href="#journey"><i class="bi bi-signpost-split navicon"></i>Learning Journey</a></li>
      <li><a href="#projects"><i class="bi bi-folder2-open navicon"></i>Projects</a></li>
      <li><a href="#services"><i class="bi bi-layers navicon"></i>What I Explore</a></li>
      <li><a href="#contact"><i class="bi bi-envelope navicon"></i>Contact</a></li>
    </ul>
  </nav>
</header>

<main class="main">

<section id="hero" class="hero section dark-background">
  <img src="myprofile3.jpeg" alt="Suryansh Tripathi" class="hero-img" data-aos="fade-in">
  <div class="container hero-content" data-aos="fade-up" data-aos-delay="100">
    <p class="eyebrow">Welcome to my digital space</p>
    <h1>Suryansh<br><span class="gradient-text">Tripathi</span></h1>
    <p class="lead">I'm a <span class="typed" data-typed-items="Fifth-Semester Data Science Student,AI/ML Explorer,Web Developer,Automation Enthusiast,Creative Problem Solver">Fifth-Semester Data Science Student</span></p>
    <p class="mt-3">I learn, experiment, and build at the intersection of <strong>data, technology, and creativity.</strong></p>
    <div class="mt-4 d-flex flex-wrap gap-3">
      <a href="#about" class="btn btn-accent">Explore My Journey <i class="bi bi-arrow-right"></i></a>
      <a href="#contact" class="btn btn-outline-light rounded-pill px-4 py-3">Let's Connect <i class="bi bi-send"></i></a>
    </div>
  </div>
</section>

<section id="about" class="about section">
  <div class="container section-title" data-aos="fade-up">
    <h2>About Me</h2>
    <p class="section-subtitle">A curious learner growing from a programming student into a future data-driven developer.</p>
  </div>

  <div class="container" data-aos="fade-up" data-aos-delay="100">
    <div class="row gy-4 align-items-center">
      <div class="col-lg-4"><img src="myprofile4.jpeg" class="img-fluid rounded-4" alt="Suryansh Tripathi working on technology"></div>
      <div class="col-lg-8 content">
        <p class="lead">Hello! I'm Suryansh Tripathi, a fifth-semester <strong>BCA Data Science student at the University of Allahabad.</strong></p>
        <p>I am passionate about understanding how software, data, artificial intelligence, and automation can be used to solve meaningful problems. My journey began with programming and web development, and it is now expanding toward data analytics, machine learning, modern frontend development, and app development.</p>
        <p>I believe in learning through practical work: writing code, building small projects, debugging mistakes, improving designs, and documenting what I discover.</p>
        <div class="row mt-3">
          <div class="col-md-6"><p><i class="bi bi-mortarboard-fill"></i> <strong>Education:</strong> BCA (Data Science)</p><p><i class="bi bi-calendar3"></i> <strong>Current stage:</strong> Fifth semester</p></div>
          <div class="col-md-6"><p><i class="bi bi-geo-alt-fill"></i> <strong>Based in:</strong> India</p><p><i class="bi bi-envelope-fill"></i> <strong>Email:</strong> suryanshtripathi778@gmail.com</p></div>
        </div>
        <p class="mt-3"><strong>My mindset:</strong> Learn → Build → Debug → Improve → Share.</p>
      </div>
    </div>
  </div>
</section>

<section id="skills" class="skills section light-background">
  <div class="container section-title" data-aos="fade-up">
    <h2>My Skills & Technology Stack</h2>
    <p class="section-subtitle">Technologies I have learned, practiced, or am actively exploring.</p>
  </div>
  <div class="container" data-aos="fade-up" data-aos-delay="100">
    <div class="row gy-4">
      <div class="col-lg-6"><div class="feature-card"><div class="icon"><i class="bi bi-terminal"></i></div><h3>Programming</h3><p>Building logic, strengthening fundamentals, and practicing problem solving.</p>
        <span class="skill-pill">Python</span><span class="skill-pill">Java</span><span class="skill-pill">C</span>
      </div></div>
      <div class="col-lg-6"><div class="feature-card"><div class="icon"><i class="bi bi-window-stack"></i></div><h3>Web Development</h3><p>Creating responsive, interactive, and user-friendly web experiences.</p>
        <span class="skill-pill">HTML5</span><span class="skill-pill">CSS3</span><span class="skill-pill">JavaScript</span><span class="skill-pill">React.js</span>
      </div></div>
      <div class="col-lg-6"><div class="feature-card"><div class="icon"><i class="bi bi-bar-chart-line"></i></div><h3>Data & Databases</h3><p>Learning to organize, process, analyze, and understand data.</p>
        <span class="skill-pill">MySQL</span><span class="skill-pill">Pandas</span><span class="skill-pill">NumPy</span><span class="skill-pill">Data Analytics</span>
      </div></div>
      <div class="col-lg-6"><div class="feature-card"><div class="icon"><i class="bi bi-tools"></i></div><h3>Tools & Platforms</h3><p>Using developer tools and automation platforms to improve productivity.</p>
        <span class="skill-pill">Git</span><span class="skill-pill">GitHub</span><span class="skill-pill">VS Code</span><span class="skill-pill">Google Apps Script</span><span class="skill-pill">Automation</span><span class="skill-pill">Android Studio</span>
      </div></div>
    </div>
  </div>
</section>

<section id="journey" class="resume section">
  <div class="container section-title" data-aos="fade-up">
    <h2>My Learning Journey</h2>
    <p class="section-subtitle">From foundational programming to a broader exploration of data science and intelligent applications.</p>
  </div>
  <div class="container">
    <div class="timeline-item" data-aos="fade-up"><span class="mini-label">Foundation</span><h3>Programming & Web Basics</h3><p>Developed foundations in C, Java, Python, HTML, CSS, JavaScript, and basic database concepts.</p></div>
    <div class="timeline-item" data-aos="fade-up"><span class="mini-label">Project-based learning</span><h3>Building Practical Applications</h3><p>Worked on mini-projects such as a calculator, expense tracker, quiz app, restaurant page, trip budget planner, and C programming projects.</p></div>
    <div class="timeline-item" data-aos="fade-up"><span class="mini-label">Current focus · Fifth semester</span><h3>Data Science & Modern Development</h3><p>Expanding knowledge of data analysis, Python libraries, React.js, automation, Git/GitHub, and Android Studio.</p></div>
    <div class="timeline-item" data-aos="fade-up"><span class="mini-label">Next milestone</span><h3>AI/ML & Portfolio Projects</h3><p>Working toward practical machine learning workflows, AI-powered applications, stronger analytics projects, and more polished software experiences.</p></div>
  </div>
</section>

<section id="projects" class="services section light-background">
  <div class="container section-title" data-aos="fade-up">
    <h2>Selected Project Experience</h2>
    <p class="section-subtitle">Small projects that represent my learning through implementation.</p>
  </div>
  <div class="container"><div class="row gy-4">
    <div class="col-lg-4 col-md-6"><div class="project-card"><i class="bi bi-calculator fs-1 gradient-text"></i><h3 class="mt-3">Calculator App</h3><p>A frontend project using HTML, CSS, and JavaScript to practice interface design and user interactions.</p><a href="project using html,css ,js/calculator.html">View project <i class="bi bi-arrow-up-right"></i></a></div></div>
    <div class="col-lg-4 col-md-6"><div class="project-card"><i class="bi bi-wallet2 fs-1 gradient-text"></i><h3 class="mt-3">Expense Tracker</h3><p>A practical interface concept for recording and organizing expenses through web technologies.</p><a href="project using html,css ,js/Expense.html">View project <i class="bi bi-arrow-up-right"></i></a></div></div>
    <div class="col-lg-4 col-md-6"><div class="project-card"><i class="bi bi-patch-question fs-1 gradient-text"></i><h3 class="mt-3">Quiz App</h3><p>An interactive quiz project focused on JavaScript logic, user interaction, and frontend structure.</p><a href="project using html,css ,js/quiz.html">View project <i class="bi bi-arrow-up-right"></i></a></div></div>
    <div class="col-lg-4 col-md-6"><div class="project-card"><i class="bi bi-bank fs-1 gradient-text"></i><h3 class="mt-3">Bank Management</h3><p>A C programming project created to practice programming fundamentals and structured logic.</p><a href="C projects/Bank_management_system.c">View source <i class="bi bi-arrow-up-right"></i></a></div></div>
    <div class="col-lg-4 col-md-6"><div class="project-card"><i class="bi bi-map fs-1 gradient-text"></i><h3 class="mt-3">Trip Budget Planner</h3><p>A web project focused on planning and organizing travel-related budget information.</p><a href="project using html,css ,js/trip.html">View project <i class="bi bi-arrow-up-right"></i></a></div></div>
    <div class="col-lg-4 col-md-6"><div class="project-card"><i class="bi bi-cup-hot fs-1 gradient-text"></i><h3 class="mt-3">Restaurant Page</h3><p>A frontend practice project exploring page layout, styling, and user-facing presentation.</p><a href="project using html,css ,js/Restro.html">View project <i class="bi bi-arrow-up-right"></i></a></div></div>
  </div></div>
</section>

<section id="services" class="services section">
  <div class="container section-title" data-aos="fade-up">
    <h2>What I Explore</h2>
    <p class="section-subtitle">The areas I want to understand more deeply and apply through future projects.</p>
  </div>
  <div class="container"><div class="row gy-4">
    <div class="col-lg-4 col-md-6"><div class="learning-card"><div class="icon"><i class="bi bi-robot"></i></div><h3>AI & Machine Learning</h3><p>Exploring the foundations of intelligent systems, machine learning concepts, and practical AI use cases.</p></div></div>
    <div class="col-lg-4 col-md-6"><div class="learning-card"><div class="icon"><i class="bi bi-graph-up-arrow"></i></div><h3>Data Analytics</h3><p>Learning how to clean, analyze, visualize, and communicate insights from data.</p></div></div>
    <div class="col-lg-4 col-md-6"><div class="learning-card"><div class="icon"><i class="bi bi-code-square"></i></div><h3>React Development</h3><p>Improving component-based frontend development and interactive user experiences.</p></div></div>
    <div class="col-lg-4 col-md-6"><div class="learning-card"><div class="icon"><i class="bi bi-lightning-charge"></i></div><h3>Automation</h3><p>Exploring Google Apps Script and automation workflows that reduce repetitive tasks.</p></div></div>
    <div class="col-lg-4 col-md-6"><div class="learning-card"><div class="icon"><i class="bi bi-phone"></i></div><h3>Android Development</h3><p>Exploring app development workflows and mobile application concepts using Android Studio.</p></div></div>
    <div class="col-lg-4 col-md-6"><div class="learning-card"><div class="icon"><i class="bi bi-git"></i></div><h3>Developer Workflow</h3><p>Practicing version control, project organization, debugging, and consistent improvement.</p></div></div>
  </div></div>
</section>

<section class="section">
  <div class="container" data-aos="fade-up">
    <div class="cta-box text-center">
      <p class="mini-label">Let's create something useful</p>
      <h2 class="text-white">Ideas are better when we build them.</h2>
      <p class="mt-3">I am open to learning opportunities, collaborations, project discussions, and meaningful connections.</p>
      <a href="#contact" class="btn btn-accent mt-3">Start a Conversation <i class="bi bi-arrow-right"></i></a>
    </div>
  </div>
</section>

<section id="contact" class="contact section light-background">
  <div class="container section-title" data-aos="fade-up">
    <h2>Contact Me</h2>
    <p class="section-subtitle">Have an idea, opportunity, or project discussion? Feel free to reach out.</p>
  </div>
  <div class="container"><div class="row gy-4">
    <div class="col-lg-5">
      <div class="info-wrap">
        <div class="info-item d-flex"><i class="bi bi-geo-alt flex-shrink-0"></i><div><h3>Location</h3><p>India</p></div></div>
        <div class="info-item d-flex"><i class="bi bi-envelope flex-shrink-0"></i><div><h3>Email</h3><p><a href="mailto:suryanshtripathi778@gmail.com">suryanshtripathi778@gmail.com</a></p></div></div>
        <div class="info-item d-flex"><i class="bi bi-globe flex-shrink-0"></i><div><h3>Portfolio</h3><p><a href="https://suryansht9.netlify.app">suryansht9.netlify.app</a></p></div></div>
        <div class="info-item d-flex"><i class="bi bi-linkedin flex-shrink-0"></i><div><h3>LinkedIn</h3><p><a href="https://www.linkedin.com/in/suryansh-tripathi-5b3384242">Connect professionally</a></p></div></div>
      </div>
    </div>
    <div class="col-lg-7">
      <form action="https://formsubmit.co/suryanshtripathi778@gmail.com" method="POST" class="php-email-form">
        <input type="text" name="_honey" style="display:none">
        <input type="hidden" name="_captcha" value="false">
        <input type="hidden" name="_subject" value="New message from Suryansh's Portfolio">
        <div class="row gy-4">
          <div class="col-md-6"><label for="name-field">Your Name</label><input type="text" name="name" id="name-field" class="form-control" required></div>
          <div class="col-md-6"><label for="email-field">Your Email</label><input type="email" name="email" id="email-field" class="form-control" required></div>
          <div class="col-md-12"><label for="subject-field">Subject</label><input type="text" name="subject" id="subject-field" class="form-control" required></div>
          <div class="col-md-12"><label for="message-field">Message</label><textarea name="message" id="message-field" class="form-control" rows="7" required></textarea></div>
          <div class="col-md-12 text-center"><button type="submit" class="btn btn-accent">Send Message <i class="bi bi-send"></i></button></div>
        </div>
      </form>
    </div>
  </div></div>
</section>

</main>

<footer id="footer" class="footer position-relative light-background">
  <div class="container text-center">
    <p>Designed and built with curiosity by <strong>Suryansh Tripathi</strong> ✨</p>
    <p><small>Learning today. Building tomorrow. 🚀</small></p>
  </div>
</footer>

<a href="#" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>
<div id="preloader"></div>

<script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
<script src="assets/vendor/aos/aos.js"></script>
<script src="assets/vendor/typed.js/typed.umd.js"></script>
<script src="assets/js/main.js"></script>
</body>
</html>
