<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio -kula sekhar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    nav {
      background-color: #4CAF50;
      padding: 1rem;
      text-align: center;
    }
    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin-right: 15px;
    }
    
      
    .hero {
      background-color: #333;
      color: white;
      padding: 100px 20px;
    }



    nav ul li a {
      color: rgb(24, 4, 4);
      text-decoration: none;
      font-weight: bold;
    }
    .social-links {
      margin-top: 10px;
    }
    .social-links a {
      margin-right: 15px;
      color: rgba(227, 23, 23, 0.621);
      text-decoration:dashed;
    }
    .hero {
      background-color: #333;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 50px;
    }
    .hero p {
      font-size: 24px;
    }
    section {
      padding: 40px 20px;
      margin: 20px 0;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }
    h2 {
      text-align: center;
      color: #4CAF50;
      font-size: 32px;
    }
    .project-container {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .project {
      width: 30%;
      background-color: #f9f9f9;
      padding: 20px;
      margin: 10px;
      border: 1px solid #ddd;
      text-align: center;
    }
    .project a {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      text-decoration: none;
    }
    .project a:hover {
      background-color: #45a049;
    }
    ul {
      list-style: none;
      padding: 0;
      text-align: center;
    }
    ul li {
      display: inline-block;
      background-color: #ddd;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 5px;
    }
    form {
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
      background-color: #f4f4f4;
      border: 1px solid #ddd;
    }
    form label {
      display: block;
      margin-top: 10px;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ddd;
    }
    form button {
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    form button:hover {
      background-color: #45a049;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: white;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#achievements">Achievements</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="hero">
      <img src="image.png" height="200" width="200"
      <br>
      <h1>Hi, I'm Kula sekhar</h1>
      <p>BTech Student at Lovely Professional University | Full Stack Developer | Tech Enthusiast</p>
      <div class="social-links">
         
        <a href="https://www.instagram.com/sekhar_1436?igsh=MTZmcThrbGR5OTIxeA==" target="_blank">Instagram</a> &nbsp; &nbsp; &nbsp; &nbsp;
        <a href="https://www.linkedin.com/in/sekhar-kula-277462324?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">LinkedIn</a>&nbsp; &nbsp; &nbsp;
        <a href="https://github.com/sekhar107" target="_blank">GitHub</a>
      </div>
    </div>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a BTech student at Lovely Professional University (LPU) specializing in Computer Science Engineering. I have a strong passion for technology, programming, and solving real-world problems. My interests include web development.
      
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project-container">
      <div class="project">
        <h3>Online Exam Portal</h3>
        <p>A web-based platform for conducting exams, featuring real-time results and analytics. Built using React, Node.js, and MongoDB.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>Attendance Management System</h3>
        <p>An automated system for managing attendance records, using facial recognition and machine learning algorithms.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>Portfolio Website</h3>
        <p>This personal portfolio site, showcasing my skills, projects, and achievements in web development.</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5, CSS3, JavaScript</li>
      
      <li>Python, Data Science</li>
      
     
    </ul>
  </section>

  <!-- Achievements Section -->
  <section id="achievements">
    <h2>Achievements</h2>
    <ul>
      <li>Participated in CYBER SECURITY & ETHICAL HACKING wokshop</li>
   
      <li>Completed certification in Machine Learning from Coursera.</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>If you'd like to get in touch, feel free to contact me via the form below:</p>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="4" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 kula sekhar. BTech CSE Student at LPU. All rights reserved.</p>
  </footer>

</body>
</html>

