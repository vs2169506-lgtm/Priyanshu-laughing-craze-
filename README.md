<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Priyanshu Laughing Craze</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
      box-sizing: border-box;
    }

    body {
      background-color: #0e0f11;
      font-family: 'Segoe UI', sans-serif;
      color: #ffffff;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #141e30, #243b55);
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 36px;
      color: #66fcf1;
      text-shadow: 0 0 10px #0ff;
    }

    header p {
      font-size: 18px;
      color: #c5c6c7;
      margin: 10px 0;
    }

    .cta-button {
      background: linear-gradient(135deg, #ff416c, #ff4b2b);
      color: white;
      padding: 15px 25px;
      border: none;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 20px;
      display: inline-block;
      box-shadow: 0 0 15px #ff4b2b99;
      transition: 0.3s ease;
    }

    .cta-button:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #ff4b2b;
    }

    nav {
      background: #1f2833;
      padding: 10px;
      display: flex;
      justify-content: center;
      gap: 30px;
    }

    nav a {
      color: #66fcf1;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
    }

    nav a:hover {
      text-shadow: 0 0 10px #45a29e;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      margin-bottom: 20px;
      color: #0ff;
      border-bottom: 2px solid #45a29e;
      display: inline-block;
    }

    .posts {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .post-card {
      background-color: #1f1f1f;
      padding: 20px;
      border-left: 5px solid #66fcf1;
      border-radius: 10px;
      box-shadow: 0 0 10px #45a29e40;
    }

    .post-card h3 {
      color: #66fcf1;
      margin-bottom: 10px;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }

    .gallery img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      border: 3px solid #66fcf1;
      box-shadow: 0 0 10px #45a29e;
    }

    .contact p {
      font-size: 16px;
      margin: 10px 0;
    }

    footer {
      background: #1f2833;
      padding: 20px;
      text-align: center;
      font-size: 14px;
      color: #c5c6c7;
      border-top: 2px solid #66fcf1;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Priyanshu Laughing Craze</h1>
    <p>Welcome to my fun, comedy, and creative world!</p>
    <a class="cta-button" href="https://www.youtube.com/@PriyanshuLaughingCraze" target="_blank">
      🔴 Watch on YouTube
    </a>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#posts">Posts</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Posts Section -->
  <section id="posts">
    <h2>My Latest Posts</h2>
    <div class="posts">
      <div class="post-card">
        <h3>🤣 Epic Prank Video!</h3>
        <p>Don’t miss this crazy prank — laughter guaranteed!</p>
      </div>
      <div class="post-card">
        <h3>🔥 Short Comedy #14</h3>
        <p>New reel dropped on my channel — go check it now.</p>
      </div>
      <div class="post-card">
        <h3>🎥 BTS Moments</h3>
        <p>Behind the scenes fun with my team during shoot.</p>
      </div>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery">
    <h2>My Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200.png?text=My+Photo+1" alt="Photo 1">
      <img src="https://via.placeholder.com/300x200.png?text=My+Photo+2" alt="Photo 2">
      <img src="https://via.placeholder.com/300x200.png?text=My+Photo+3" alt="Photo 3">
      <img src="https://via.placeholder.com/300x200.png?text=My+Photo+4" alt="Photo 4">
    </div>
    <p style="text-align:center; color:#bbb; margin-top:15px;">You can replace these with your real images anytime.</p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: priyanshu@example.com</p>
    <p>Instagram: @priyanshu.laughs</p>
    <p>YouTube: <a href="https://www.youtube.com/@PriyanshuLaughingCraze" style="color:#66fcf1;" target="_blank">@PriyanshuLaughingCraze</a></p>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Priyanshu Laughing Craze. All rights reserved.
  </footer>

</body>
</html>
