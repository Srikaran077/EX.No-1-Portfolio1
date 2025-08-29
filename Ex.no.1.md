# Ex01 Portfolio
## Date:29-08-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Srikaran · Backend Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background-color: #ffffff;
      color: #333333;
      line-height: 1.6;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      background-color: #fff;
      border-bottom: 1px solid #f0f0f0;
      z-index: 10;
    }
    nav a {
      text-decoration: none;
      color: #ff6600;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ff3300;
    }
    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 2rem;
    }
    header h1 {
      font-size: 3.5rem;
      font-weight: 700;
      color: #333333;
    }
    header h2 {
      font-size: 1.5rem;
      font-weight: 500;
      margin-top: 0.5rem;
      color: #ff6600;
    }
    header img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      margin-top: 2rem;
      border: 4px solid #ff6600;
    }
    section {
      padding: 5rem 2rem;
      max-width: 800px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 2rem;
      color: #ff6600;
    }
    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 1rem;
    }
    .skill {
      background-color: #fff5e6;
      padding: 1rem;
      text-align: center;
      border-radius: 10px;
      border: 1px solid #ffcc99;
      font-weight: 500;
      transition: transform 0.3s;
    }
    .skill:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(255,102,0,0.2);
    }
    .contact-box {
      background-color: #fff5e6;
      padding: 2rem;
      border: 2px solid #ff6600;
      border-radius: 12px;
      max-width: 400px;
      margin: auto;
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 2rem;
      border-top: 1px solid #f0f0f0;
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #666666;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#skills">Skills</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <header id="home">
    <h1>Hi, I am Srikaran</h1>
    <h2>Backend Developer</h2>
    <img src="c:\Users\admin\Pictures\srikaran.jpeg" alt="Srikaran photo">
  </header>

  <section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
      <div class="skill">Python</div>
      <div class="skill">Node.js</div>
      <div class="skill">Express</div>
      <div class="skill">REST APIs</div>
      <div class="skill">PostgreSQL</div>
    </div>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p style="text-align:center; font-size:1.1rem;">
      I am Srikaran, a backend developer. I focus on building simple, efficient, and reliable backend systems using modern technologies.
    </p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact-box">
      <p>📧 Email: your.email@example.com</p>
      <p>💻 GitHub: github.com/srikaran</p>
      <p>🔗 LinkedIn: linkedin.com/in/srikaran</p>
    </div>
  </section>

  <footer>
    © <span id="year"></span> Srikaran · Portfolio Website
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

```
## OUTPUT
<img width="1872" height="896" alt="image" src="https://github.com/user-attachments/assets/173869de-211e-400e-a8da-341a3f9d9d26" />
<img width="1866" height="892" alt="image" src="https://github.com/user-attachments/assets/8e991567-5698-44d2-b281-3b0cf9c1fba0" />

<img width="1838" height="893" alt="image" src="https://github.com/user-attachments/assets/1bad62cf-ae8e-4a93-9e2e-e99bdb3f4bc5" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
