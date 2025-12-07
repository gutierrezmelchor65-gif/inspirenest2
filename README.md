<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>InspireNest | Inspire Every Heart</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background-color: #fdfcfb;
      color: #444;
      scroll-behavior: smooth;
    }

    header {
      background-color: #fbe8eb;
      text-align: center;
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    header h1 {
      margin: 0;
      color: #ff94a6;
    }

    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #555;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff94a6;
    }

    section {
      padding: 3rem 1rem;
      text-align: center;
    }

    .hero {
      background: linear-gradient(to right, #fbe8eb, #d7f9f8);
      padding: 5rem 1rem;
    }

    .hero h2 {
      color: #333;
      font-size: 2rem;
    }

    .btn {
      display: inline-block;
      background-color: #ff94a6;
      color: white;
      padding: 10px 20px;
      border-radius: 20px;
      text-decoration: none;
      margin-top: 15px;
      transition: background 0.3s;
    }

    .btn:hover {
      background-color: #ffb6c1;
    }

    .grid {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
    }

    .grid img {
      width: 250px;
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .grid img:hover {
      transform: scale(1.05);
    }

    blockquote {
      font-style: italic;
      background-color: #fbe8eb;
      padding: 1rem;
      border-radius: 10px;
      margin: 1rem auto;
      width: 70%;
      max-width: 600px;
    }

    form {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
      margin-top: 20px;
    }

    input, textarea {
      width: 80%;
      max-width: 400px;
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }

    button {
      background-color: #ff94a6;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 20px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background-color: #ffb6c1;
    }

    footer {
      background-color: #fbe8eb;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #555;
    }

    h2 {
      color: #444;
    }
  </style>
</head>
<body>
  <header>
    <h1>InspireNest</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#wallart">Wall Art</a>
      <a href="#ebooks">eBooks</a>
      <a href="#quotes">Quotes</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Inspire Every Heart, Spark Every Mind</h2>
    <p>Beautiful wall art, uplifting quotes, and fun eBooks for growing minds.</p>
    <a href="#wallart" class="btn">Explore Our Collection</a>
  </section>

  <section id="wallart">
    <h2>Motivational Wall Art</h2>
    <p>Decor that speaks to your soul and brightens your space.</p>
    <div class="grid">
      <img src="https://source.unsplash.com/400x400/?motivational,art" alt="Motivational Wall Art">
      <img src="https://source.unsplash.com/400x400/?quote,poster" alt="Quote Poster">
      <img src="https://source.unsplash.com/400x400/?home,decor" alt="Decor Wall Art">
    </div>
  </section>

  <section id="ebooks">
    <h2>Children’s eBooks</h2>
    <p>Inspiring stories and fun coloring books to grow creativity and confidence.</p>
    <div class="grid">
      <img src="https://source.unsplash.com/400x400/?kids,book" alt="Children Reading">
      <img src="https://source.unsplash.com/400x400/?coloring,book" alt="Coloring Book">
    </div>
  </section>

  <section id="quotes">
    <h2>Daily Motivation</h2>
    <blockquote>“Believe in yourself and all that you are.”</blockquote>
    <blockquote>“Small steps every day lead to big change.”</blockquote>
    <blockquote>“Dream. Create. Inspire.”</blockquote>
  </section>

  <section id="contact">
    <h2>We’d love to hear from you!</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 InspireNest | Made with 💕 to inspire creativity</p>
  </footer>
</body>
</html>
