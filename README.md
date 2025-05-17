# Mom-blog
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mom Moments with Emily</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fffafc;
      color: #444;
    }
    header {
      background: linear-gradient(to right, #ffd6e0, #d0f0fd);
      padding: 2em;
      text-align: center;
      color: #333;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
    }
    nav {
      background: #fbefff;
      text-align: center;
      padding: 1em;
    }
    nav a {
      margin: 0 1em;
      text-decoration: none;
      color: #7b5e9f;
      font-weight: bold;
    }
    .content {
      max-width: 900px;
      margin: 2em auto;
      padding: 0 1em;
    }
    .photo-gallery {
      display: flex;
      gap: 1em;
      flex-wrap: wrap;
      justify-content: center;
    }
    .photo-gallery img {
      width: 200px;
      border-radius: 10px;
      object-fit: cover;
    }
    .articles {
      margin-top: 3em;
    }
    .article {
      background: #fff0f5;
      padding: 1em 1.5em;
      border-radius: 10px;
      margin-bottom: 2em;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    .article h2 {
      margin-top: 0;
      color: #c77dff;
    }
    footer {
      text-align: center;
      background: #e2f0cb;
      padding: 1.5em;
      margin-top: 3em;
    }
    .social-icons a {
      margin: 0 10px;
      font-size: 1.5em;
      text-decoration: none;
      color: #7d6b91;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mom Moments with Emily</h1>
    <p>Sharing the chaos, joy, and beauty of motherhood — one story at a time</p>
  </header>

  <nav>
    <a href="#photos">Photos</a>
    <a href="#articles">Articles</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="content">
    <section id="photos">
      <h2 style="color:#ffa6c1;">Photo Gallery</h2>
      <div class="photo-gallery">
        <img src="https://via.placeholder.com/200x200.png?text=Baby+Smiles" alt="Baby smiles">
        <img src="https://via.placeholder.com/200x200.png?text=Mom+and+Me" alt="Mom and Me">
        <img src="https://via.placeholder.com/200x200.png?text=Family+Walk" alt="Family Walk">
        <!-- Add more photos here -->
      </div>
    </section>

    <section id="articles" class="articles">
      <h2 style="color:#9ad0ec;">Recent Articles</h2>
      
      <div class="article">
        <h2>The Day I Became a Mom</h2>
        <p>From the moment I held my son for the first time, my entire world shifted. Here’s what I felt in that whirlwind of emotion and love...</p>
        <p><em>Posted on May 16, 2025</em></p>
      </div>

      <div class="article">
        <h2>What They Don't Tell You About the First Week Home</h2>
        <p>Between sore boobs, sleepless nights, and magical baby coos, here’s how we survived our first week as a family of three.</p>
        <p><em>Posted on May 10, 2025</em></p>
      </div>

      <!-- Add more articles here -->
    </section>
  </div>

  <footer id="contact">
    <h3>Let's Connect!</h3>
    <div class="social-icons">
      <a href="https://instagram.com/" target="_blank">Instagram</a>
      <a href="https://facebook.com/" target="_blank">Facebook</a>
      <a href="mailto:youremail@example.com">Email</a>
    </div>
    <p>© 2025 Mom Moments with Emily</p>
  </footer>
</body>
</html>
