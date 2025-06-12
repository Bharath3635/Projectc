<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Responsive Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>My Website</h1>
    <nav>
      <button id="menu-toggle">☰</button>
      <ul id="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home">
      <h2>Welcome to My Website</h2>
      <p>This is the landing page content.</p>
    </section>

    <section id="about">
      <h2>About</h2>
      <p>Information about the website or person.</p>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <p>Some placeholder images here.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" /><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" /><br>
        <input type="submit" value="Submit" />
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Website</p>
  </footer>

  <script>
    // Simple mobile menu toggle
    document.getElementById('menu-toggle').addEventListener('click', function () {
      document.getElementById('nav-links').classList.toggle('show');
    });
  </script>
</body>
</html>
