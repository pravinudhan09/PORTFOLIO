# PORTFOLIO

<!DOCTYPE html><html lang="en"><head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pravin Udhan - Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }body {
  background-color: #e0f0ff; /* Light blue background */
  color: #333;
  position: relative;
}

body::before {
  content: "";
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Artificial_Intelligence_logo.svg/2048px-Artificial_Intelligence_logo.svg.png');
  background-size: 60%;
  background-repeat: no-repeat;
  opacity: 0.05;
  width: 100%;
  height: 100%;
  z-index: 0;
  pointer-events: none;
  user-select: none;
}

header, nav, section {
  position: relative;
  z-index: 1;
}

header {
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
  text-align: center;
}

nav {
  display: flex;
  justify-content: center;
  gap: 2rem;
  background-color: #34495e;
  padding: 1rem;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

section {
  padding: 2rem;
  max-width: 900px;
  margin: auto;
}

.project {
  background: linear-gradient(135deg, #d0f0ff, #ffffff);
  border-left: 5px solid #3498db;
  padding: 1rem;
  margin-bottom: 1rem;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease-in-out;
}

.project:hover {
  transform: scale(1.02);
}

form {
  background: linear-gradient(135deg, #f0fbff, #ffffff);
  border-left: 5px solid #1abc9c;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

input, textarea {
  padding: 0.8rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  background-color: #2ecc71;
  color: white;
  padding: 0.8rem;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #27ae60;
}

.email-display {
  margin-bottom: 1rem;
  font-weight: bold;
  color: #2c3e50;
}

  </style>
</head><body>
  <header>
    <h1>Pravin Udhan</h1>
    <p>AI & ML Student | Python Developer | Web Developer</p>
  </header>  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I am a 3rd year AI & ML engineering student with strong skills in Python, Object-Oriented Programming, and Web Development. I enjoy building real-world applications and exploring new technologies.</p>
  </section>  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>Responsive website built using HTML, CSS, and JavaScript to showcase personal projects and contact information.</p>
    </div>
    <div class="project">
      <h3>To-Do List App</h3>
      <p>Simple Python CLI app that lets you add, view, and remove to-do items.</p>
    </div>
    <div class="project">
      <h3>Diabetes Prediction</h3>
      <p>Machine learning project to predict diabetes using health data. Built with Python and Scikit-learn.</p>
    </div>
    <div class="project">
      <h3>AI Bootcamp Repository</h3>
      <p>Check out my GitHub project: <a href="https://github.com/pravinudhan09/ai.bootcamp" target="_blank">AI Bootcamp on GitHub</a></p>
    </div>
  </section>  <section id="contact">
    <h2>Contact Me</h2>
    <p class="email-display">Email: <a href="mailto:foundineden20@gmail.com">foundineden20@gmail.com</a></p>
    <form action="https://formsubmit.co/foundineden20@gmail.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_next" value="https://your-portfolio.com/thank-you.html"><input type="text" name="name" placeholder="Your Name" required />
  <input type="email" name="email" placeholder="Your Email" required />
  <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
  <button type="submit">Send</button>
</form>

  </section></body></html>
