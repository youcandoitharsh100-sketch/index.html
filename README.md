<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sketching Harshly - Art Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f8f9fa;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #ffafbd, #ffc3a0);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    nav {
      background: #ffffff;
      padding: 10px 20px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      display: flex;
      justify-content: center;
      gap: 30px;
    }

    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    .about, .contact {
      background: #fff;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .contact input, .contact textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    .contact button {
      margin-top: 15px;
      padding: 10px 20px;
      background: #ff7f50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #eee;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sketching Harshly</h1>
    <p>Welcome to my world of art ✨</p>
  </header>

  <nav>
    <a href="#gallery">Gallery</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="gallery">
    <h2>🎨 My Art Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x400?text=Art+1" alt="Art 1"/>
      <img src="https://via.placeholder.com/300x400?text=Art+2" alt="Art 2"/>
      <img src="https://via.placeholder.com/300x400?text=Art+3" alt="Art 3"/>
      <img src="https://via.placeholder.com/300x400?text=Art+4" alt="Art 4"/>
    </div>
  </section>

  <section id="about" class="about">
    <h2>👨‍🎨 About Me</h2>
    <p>
      Hi! I'm Harsh, a passionate young artist who brings thoughts and feelings to life on paper. 
      I love experimenting with colors, anime styles, and raw emotion through my artwork.
    </p>
  </section>

  <section id="contact" class="contact">
    <h2>📧 Contact Me</h2>
    <p>Have a question or want to collaborate? Send me a message!</p>
    <input type="text" placeholder="Your Name" />
    <input type="email" placeholder="Your Email" />
    <textarea rows="4" placeholder="Your Message"></textarea>
    <button>Send</button>
  </section>

  <footer>
    © 2025 Sketching Harshly. All rights reserved.
  </footer>

</body>
</html>
