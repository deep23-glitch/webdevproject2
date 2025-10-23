<<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deep's Portfolio</title>
  <!-- Link to external CSS -->
  <link rel="stylesheet" href="style.css">
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;600&display=swap" rel="stylesheet">
</head>
<body>

  <header>
    <nav>
      <ul>
        <li><a href="#hero">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <h1>Hey, I'm Deep </h1>
    <p>A student developer who enjoys building cool web stuff.</p>
  </section>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <img src="file:///C:/Users/sanat/OneDrive/Documents/WhatsApp%20Image%202025-10-23%20at%2015.43.56_81eb311a.jpg" alt="Deep's photo" class="profile-pic">
      <p>Hi! I'm Deep, a college student learning web development. I like designing websites, writing clean code, and learning new technologies.</p>
    </section>

    <hr>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li><b>Portfolio Website</b> – My personal site built with HTML & CSS.</li>
        <li><b>Todo App</b> – Helps manage daily tasks easily.</li>
        <li><b>Mini Blog</b> – Simple layout for posting articles.</li>
      </ul>
    </section>

    <hr>

    <section id="skills">
      <h2>Skills</h2>
      <table>
        <tr>
          <th>Skill</th>
          <th>Proficiency</th>
        </tr>
        <tr>
          <td>HTML</td>
          <td>Intermediate</td>
        </tr>
        <tr>
          <td>CSS</td>
          <td>Beginner</td>
        </tr>
        <tr>
          <td>JavaScript</td>
          <td>Learning</td>
        </tr>
      </table>
    </section>

    <hr>

    <section id="contact">
      <h2>Contact Me</h2>
      <form action="#">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="you@example.com" required><br><br>

        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" placeholder="Write something..." required></textarea><br><br>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer>
    <p>Made by Deep | © 2025</p>
    <button id="topBtn">↑ Back to Top</button>
  </footer>

  <script>
    // Simple back-to-top button functionality
    document.getElementById('topBtn').addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  </script>

</body>
</html>
