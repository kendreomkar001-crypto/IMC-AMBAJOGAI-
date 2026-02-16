<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>IMC AMBAJOGAI</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: linear-gradient(to right, #eef2f3, #d9e4f5);
}

/* Header */
header {
  background: linear-gradient(to right, #1e3c72, #2a5298);
  color: white;
  padding: 25px;
  text-align: center;
}

.logo {
  width: 80px;
  border-radius: 50%;
  margin-bottom: 10px;
}

/* Navigation */
nav {
  background: white;
  padding: 12px;
  text-align: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

nav a {
  color: #1e3c72;
  text-decoration: none;
  margin: 12px;
  font-weight: 600;
}

nav a:hover {
  color: #ff6600;
}

/* Sections */
section {
  max-width: 950px;
  margin: 30px auto;
  background: white;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

h2 {
  color: #1e3c72;
  margin-bottom: 15px;
  border-left: 5px solid #ff6600;
  padding-left: 10px;
}

/* Formula Box */
.formula-box {
  background: #f8fbff;
  border-left: 5px solid #2a5298;
  padding: 15px;
  margin: 12px 0;
  border-radius: 6px;
}

/* YouTube Section */
.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 15px;
}

iframe {
  width: 100%;
  height: 200px;
  border-radius: 8px;
}

/* Footer */
footer {
  background: #1e3c72;
  color: white;
  text-align: center;
  padding: 18px;
  margin-top: 30px;
}

/* Mobile */
@media (max-width: 600px) {
  section {
    margin: 15px;
  }
}
</style>
</head>

<body>

<header>

  <!-- Website Logo (Same as YouTube) -->
  <img src="logo.png" class="logo" alt="IMC Logo">

  <h1>IMC AMBAJOGAI</h1>
  <p>Study & Information Platform</p>

  <!-- YouTube Link -->
  <p>
    📺 Our Channel:
    <a href="https://youtube.com/@idealmathsclassesambajogai3869?si=JGjGszI1Ee0xGEjT"
       style="color:#ffd700;" target="_blank">
       Ideal Maths Classes
    </a>
  </p>

</header>

<nav>
  <a href="#home">Home</a>
  <a href="#study">Study</a>
  <a href="#algebra">Algebra</a>
  <a href="#videos">Videos</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home">
  <h2>Welcome</h2>
  <p>Welcome to IMC AMBAJOGAI. Learn easily with videos, notes, and formulas.</p>
</section>

<section id="study">
  <h2>Study Materials</h2>
  <ul>
    <li>📘 Mathematics</li>
    <li>📗 Science</li>
    <li>📙 English</li>
    <li>📕 Exam Preparation</li>
  </ul>
</section>

<section id="algebra">
  <h2>Algebra Formulas</h2>

  <div class="formula-box">(a + b)² = a² + 2ab + b²</div>
  <div class="formula-box">(a − b)² = a² − 2ab + b²</div>
  <div class="formula-box">a² − b² = (a − b)(a + b)</div>
  <div class="formula-box">(a + b)³ = a³ + b³ + 3ab(a + b)</div>
  <div class="formula-box">x = (-b ± √(b² − 4ac)) / 2a</div>

</section>

<!-- YouTube Videos -->
<section id="videos">
  <h2>YouTube Learning Videos</h2>

  <p>Watch our latest maths classes from YouTube:</p><br>

  <div class="video-grid">

    <!-- Replace VIDEO_ID with your real video IDs -->

    <iframe src="https://www.youtube.com/embed/VIDEO_ID_1"
    allowfullscreen></iframe>

    <iframe src="https://www.youtube.com/embed/VIDEO_ID_2"
    allowfullscreen></iframe>

    <iframe src="https://www.youtube.com/embed/VIDEO_ID_3"
    allowfullscreen></iframe>

    <iframe src="https://www.youtube.com/embed/VIDEO_ID_4"
    allowfullscreen></iframe>

  </div>

</section>

<section id="about">
  <h2>About Us</h2>
  <p>IMC AMBAJOGAI provides quality maths education with videos and notes.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>📧 Email: imcambajogai@gmail.com</p>
  <p>📞 Phone: +91-XXXXXXXXXX</p>
</section>

<footer>
  <p>© 2026 IMC AMBAJOGAI | All Rights Reserved</p>
</footer>

</body>
</html>
