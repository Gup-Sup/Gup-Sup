## <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gup Sup</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #fefefe;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #ff6a00, #ee0979);
      color: white;
      padding: 4rem 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background: #fff;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      text-decoration: none;
      color: #333;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ee0979;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: 3rem auto;
    }

    .section-title {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 2rem;
      color: #ff6a00;
    }

    .blog-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }

    .blog-card {
      background: white;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.3s;
    }

    .blog-card:hover {
      transform: translateY(-5px);
    }

    .blog-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .blog-card-content {
      padding: 1rem;
    }

    .blog-card-content h3 {
      color: #ee0979;
      margin-bottom: 0.5rem;
    }

    .blog-card-content p {
      font-size: 0.95rem;
      line-height: 1.4;
    }

    .showing {
      background: #f8f8f8;
      padding: 3rem 1rem;
      text-align: center;
    }

    .showing img {
      width: 100%;
      max-width: 800px;
      margin-top: 1rem;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 3rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Gup Sup</h1>
    <p>Your place for stories, talks, and creativity 🌟</p>
  </header>

  <nav>
    <a href="#blog">Blog</a>
    <a href="#showing">Showing</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="container" id="blog">
    <h2 class="section-title">Latest Gup</h2>
    <div class="blog-grid">
      <div class="blog-card">
        <img src="https://source.unsplash.com/400x300/?talk,people" alt="Blog Image">
        <div class="blog-card-content">
          <h3>Midnight Thoughts</h3>
          <p>A story about conversations that hit different under the stars.</p>
        </div>
      </div>
      <div class="blog-card">
        <img src="https://source.unsplash.com/400x300/?coffee,chat" alt="Blog Image">
        <div class="blog-card-content">
          <h3>Coffee Gup Sup</h3>
          <p>Exploring how caffeine brings out the best banter in friends.</p>
        </div>
      </div>
      <div class="blog-card">
        <img src="https://source.unsplash.com/400x300/?city,nights" alt="Blog Image">
        <div class="blog-card-content">
          <h3>Urban Echoes</h3>
          <p>What people say in passing, and why it matters more than we think.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="showing" id="showing">
    <h2 class="section-title">Showing</h2>
    <p>Check out our featured content or upcoming event!</p>
    <img src="https://source.unsplash.com/800x400/?event,stage" alt="Featured Media">
  </section>

  <footer id="contact">
    <p>© 2025 Gup Sup | Let's talk at <a href="mailto:gupsup@example.com" style="color: #ff6a00;">gupsup@example.com</a></p>
  </footer>

</body>
</html>
 there 👋

<!--
**Gup-Sup/Gup-Sup** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
