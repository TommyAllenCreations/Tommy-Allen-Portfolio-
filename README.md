Tommy Allen Creations
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tommy Allen | Creative Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #121212;
      color: #e0e0e0;
    }
    header {
      background: #1f1f1f;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h1, h2 {
      color: #ffffff;
    }
    .gallery img, video {
      width: 100%;
      max-width: 480px;
      margin: 20px 10px;
      border-radius: 8px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #aaa;
    }
  </style>
</head>
<body>

<header>
  <h1>Tommy Allen</h1>
  <p>Creative Director & Visual Storyteller</p>
  <nav>
    <a href="#about">About</a>
    <a href="#work">My Work</a>
    <a href="#videos">Videos</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>
    I’m a dynamic and results-driven creative with extensive experience in editing, photography, and media design. I’m passionate about leadership and telling impactful stories through visual art and digital media.
  </p>
</section>

<section id="work">
  <h2>My Work</h2>
  <div class="gallery">
    <!-- 🔻 ADD YOUR IMAGES BELOW -->
    <img src="assets/cecred-ad.jpeg" alt="Cécred Ad">
    <img src="assets/project2.jpg" alt="Another Project">
  </div>
</section>

<section id="videos">
  <h2>Video Clips</h2>
  <div class="gallery">
    <!-- 🔻 ADD YOUR VIDEO CLIPS BELOW -->
    <video controls>
      <source src="assets/cecred-tiktok.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <video controls>
      <source src="assets/apple-training.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:natea887@gmail.com">natea887@gmail.com</a></p>
  <p>Phone: <a href="tel:+17039868412">(703) 986-8412</a></p>
</section>

<footer>
  &copy; 2025 Tommy Allen
</footer>

</body>
</html>
