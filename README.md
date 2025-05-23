# Tommy-Allen-Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tommy Allen | Creative Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="logo">TA</div>
    <nav>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#media">Media</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Tommy Allen</h1>
    <p>Creative Director & Visual Storyteller</p>
  </section>

  <section id="about" class="content-section">
    <h2>About Me</h2>
    <p>
      I’m a dynamic and results-driven creative with extensive experience in editing and media software including iMovie, iOS, Photography, and Photoshop. I'm passionate about leadership, creative direction, and making impactful connections through design and media.
    </p>
  </section>

  <section id="portfolio" class="content-section">
    <h2>Portfolio</h2>
    <div class="portfolio-grid">
      <div class="item">
        <img src="assets/cecred-ad.jpeg" alt="Cécred Ad" />
        <p>Cécred TikTok Campaign</p>
      </div>
      <!-- Add more projects as needed -->
    </div>
  </section>

  <section id="media" class="content-section">
    <h2>Media Samples</h2>
    <video controls width="100%">
      <source src="assets/your-video.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </section>

  <section id="contact" class="content-section">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:natea887@gmail.com">natea887@gmail.com</a></p>
    <p>Phone: <a href="tel:+17039868412">(703) 986-8412</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Tommy Allen</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #121212;
  color: #e0e0e0;
  line-height: 1.6;
}
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background: #1a1a1a;
}
.logo {
  font-size: 1.5rem;
  font-weight: bold;
}
nav a {
  margin-left: 1.5rem;
  color: #fff;
  text-decoration: none;
}
.hero {
  text-align: center;
  padding: 5rem 2rem;
}
.hero h1 {
  font-size: 3rem;
}
.content-section {
  padding: 4rem 2rem;
}
.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}
.item img {
  width: 100%;
  border-radius: 8px;
}
footer {
  text-align: center;
  padding: 2rem;
  background: #1a1a1a;
  color: #aaa;
}
a {
  color: #03dac6;
}
