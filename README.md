<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kai | Academic Website</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background-color: #f9f9f9;
      color: #222;
      line-height: 1.6;
    }
    header {
      background: #fff;
      padding: 2rem;
      border-bottom: 1px solid #eee;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #555;
    }
    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      font-size: 1.5rem;
      border-bottom: 2px solid #eee;
      padding-bottom: 0.5rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #888;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Kai</h1>
    <nav>
      <a href="#about">About Me</a>
      <a href="#research">Research</a>
      <a href="#publications">Publications</a>
      <a href="#gallery">Gallery</a>
      <a href="#notes">Notes</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        I am an math undergraduate student at the university of Michigan with deep interests in probability theory.
      </p>
    </section>

    <section id="research">
      <h2>Research</h2>
      <p>
        My research focuses on [brief summary of research interests]. I am particularly interested in [specific area/topic].
        I aim to contribute to the field through rigorous analysis and thoughtful inquiry.
      </p>
    </section>

    <section id="publications">
      <h2>Publications</h2>
      <ul>
        <li><strong>Title of Paper</strong>, Journal Name, Year.</li>
        <li><strong>Another Paper</strong>, Conference/Journal, Year.</li>
        <!-- Add more as needed -->
      </ul>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <div class="gallery">
        <img src="path/to/image1.jpg" alt="Description 1" />
        <img src="path/to/image2.jpg" alt="Description 2" />
        <img src="path/to/image3.jpg" alt="Description 3" />
        <!-- Add more images as desired -->
      </div>
    </section>

    <section id="notes">
      <h2>Notes</h2>
      <p>
        Here I share short reflections, academic ideas, or reading notes that I find insightful or thought-provoking.
      </p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>
        You can reach me at: <a href="mailto:kai@example.com">kai@example.com</a>
      </p>
    </section>
  </main>

  <footer>
    &copy; 2025 Kai. All rights reserved.
  </footer>
</body>
</html>
