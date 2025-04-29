<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Raamnath | Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Courier New', Courier, monospace;
      margin: 0;
      padding: 0;
      background-color: #0b0c0c; /* Neutral background color */
      color: #c0ff00;
    }
    header {
      background-color: #1b3c1b;
      color: #c0ff00;
      padding: 2rem;
      text-align: center;
      animation: fadeInDown 1s ease-out;
    }
    section {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
      background: #1a1a1a;
      margin-top: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(192,255,0,0.3);
      transition: transform 0.3s;
      animation: fadeInUp 1.5s ease;
    }
    section:hover {
      transform: scale(1.01);
    }
    h1, h2 {
      margin-top: 0;
      color: #c0ff00;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #888;
      background-color: #1b3c1b;
      animation: fadeInUp 2s ease;
    }
    .button {
      display: inline-block;
      padding: 0.5rem 1rem;
      background-color: #2f4f2f;
      color: #c0ff00;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 1rem;
      transition: background-color 0.3s;
    }
    .button:hover {
      background-color: #3d603d;
    }
    .social-links {
      margin-top: 2rem;
      text-align: center;
    }
    .social-links a {
      color: #c0ff00;
      margin: 0 10px;
      font-size: 1.8rem;
      transition: transform 0.3s, color 0.3s, box-shadow 0.3s;
      display: inline-block;
    }
    .social-links a:hover,
    .social-links a:focus,
    .social-links a:active {
      transform: scale(1.2);  /* Slightly increase size on touch/click */
      color: #aaff00;         /* Change color to a neon yellow/green */
      box-shadow: 0 0 15px rgba(170, 255, 0, 0.5); /* Soft glowing effect */
    }
    .skills-list {
      list-style: none;
      padding-left: 0;
    }
    .skills-list li {
      background: #2a2a2a;
      margin: 0.5rem 0;
      padding: 0.5rem 1rem;
      border-radius: 20px;
      display: inline-block;
      color: #c0ff00;
      animation: fadeInUp 0.6s ease forwards;
      opacity: 0;
      transform: translateY(20px);
    }
    .skills-list li:nth-child(1) { animation-delay: 0.2s; }
    .skills-list li:nth-child(2) { animation-delay: 0.4s; }
    .skills-list li:nth-child(3) { animation-delay: 0.6s; }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #111;
      box-shadow: 0 2px 5px rgba(0,255,0,0.2);
      padding: 0.5rem;
      text-align: center;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #c0ff00;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #aaff00;
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

<header>
  <h1>Raamnath</h1>
  <p>Aspiring Developer | I Am the One Who Codes</p>
  <p>Walter White | I Am the One Who Knocks</p>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>Hello! I'm Raamnath, Currently pursuing my B.Tech IT at Sri Sairam Institute Of Technology. I enjoy learning new technologies and connecting with professionals in the industry.</p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <ul class="skills-list">
    <li>C</li>
    <li>C++</li>
    <li>Python</li>
  </ul>
</section>

<section id="projects">
  <h2>Projects</h2>
  <p>Check out my work on <a href="https://github.com/Raam1112" target="_blank">GitHub</a> 
</section>

<section id="contact">
  <a class="button" href="mailto:raamnathannamalai@gmail.com">Contact Me</a>
  <div class="social-links">
    <a href="https://linkedin.com/in/raamnath" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
    <a href="https://github.com/Raam1112" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
    <a href="mailto:raamnathannamalai@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
    <a href="https://facebook.com/raamnath1211" target="_blank" title="Facebook"><i class="fab fa-facebook"></i></a>
    <a href="https://twitter.com/Raamnath1211" target="_blank" title="Twitter"><i class="fab fa-twitter"></i></a>
    <a href="https://instagram.com/rockstar_raam" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
    <a href="https://leetcode.com/raam1211" target="_blank" title="LeetCode"><i class="fas fa-code"></i></a>
    <a href="https://skillrack.com/profile/501141/raamnath" target="_blank" title="SkillRack"><i class="fas fa-laptop-code"></i></a>
  </div>
</section>

<footer>
  © 2025 Raamnath. Stay Dangerous. Code Heisenberg-style.
</footer>

</body>
</html>