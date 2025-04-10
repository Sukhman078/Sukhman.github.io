<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sukhman | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #0d0d0d;
      color: #f5f5f5;
      scroll-behavior: smooth;
    }
    nav {
      background: rgba(0, 0, 0, 0.8);
      padding: 10px 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: #00ffe1;
      font-weight: bold;
      text-decoration: none;
    }
    section {
      padding: 80px 20px;
      max-width: 900px;
      margin: auto;
      border-bottom: 1px solid #2c2c2c;
      position: relative;
      z-index: 1;
    }
    #intro {
      position: relative;
      color: #fff;
      text-align: center;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    #intro video {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: 0;
    }
    #intro .content {
      position: relative;
      z-index: 1;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 30px;
      border-radius: 10px;
    }
    h1, h2 {
      color: #00ffe1;
    }
    a {
      color: #00ffe1;
    }
    iframe {
      width: 100%;
      max-width: 800px;
      height: 450px;
      margin-top: 20px;
      border: none;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#intro">Intro</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="intro">
    <video autoplay muted loop>
      <source src="space.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div class="content">
      <h1>Hello, I'm Sukhman 👋</h1>
      <p>
        I’m from Punjab, India and currently reside in Vancouver, BC.  
        I constantly challenge myself with new things.  
        When I’m not making assignments (like this one :), you can find me in the gym, playing sports, or interacting with new humans.
      </p>
    </div>
  </section>

  <section id="projects">
    <h2>Featured Video</h2>
    <p>Here’s something cool I’ve worked on recently:</p>
    <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <p>You can view or download my resume here:</p>
    <a href="resume.pdf" target="_blank">View My Resume (PDF)</a>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📧 Email: <a href="mailto:you@example.com">you@example.com</a></p>
    <p>🐙 GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
  </section>

</body>
</html>
