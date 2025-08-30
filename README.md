<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Favourite Entertainment</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #111;
      color: #fff;
    }
    header {
      background: #e50914;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #000;
      padding: 0.5rem;
    }
    nav a {
      color: #fff;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #e50914;
    }
    .container {
      padding: 2rem;
    }
    .movies {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1rem;
    }
    .movie {
      background: #222;
      border-radius: 8px;
      overflow: hidden;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.4);
    }
    .movie img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }
    .movie h3 {
      margin: 0.5rem;
    }
    .movie a {
      display: inline-block;
      margin: 0.5rem;
      padding: 0.5rem 1rem;
      background: #e50914;
      color: #fff;
      border-radius: 4px;
      text-decoration: none;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Favourite Entertainment</h1>
    <p>Your #1 source for movies, shows, and entertainment</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#movies">Movies</a>
    <a href="#categories">Categories</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="home">
    <h2>Featured Movies</h2>
    <div class="movies">
      <div class="movie">
        <img src="https://via.placeholder.com/200x300" alt="Movie Poster">
        <h3>Movie Title 1</h3>
        <a href="#">Watch / Download</a>
      </div>
      <div class="movie">
        <img src="https://via.placeholder.com/200x300" alt="Movie Poster">
        <h3>Movie Title 2</h3>
        <a href="#">Watch / Download</a>
      </div>
      <div class="movie">
        <img src="https://via.placeholder.com/200x300" alt="Movie Poster">
        <h3>Movie Title 3</h3>
        <a href="#">Watch / Download</a>
      </div>
    </div>
  </div>

  <div class="container" id="about">
    <h2>About Us</h2>
    <p>Welcome to Favourite Entertainment! We provide movie trailers, reviews, and entertainment content. Stay tuned for updates and enjoy endless fun.</p>
  </div>

  <div class="container" id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@favouriteentertainment.com</p>
    <p>WhatsApp: +234 8141636549</p>
  </div>

  <footer>
    <p>&copy; 2025 Favourite Entertainment. All rights reserved.</p>
  </footer>
</body>
</html>
