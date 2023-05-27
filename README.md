```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dakhnistan Studios</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>Dakhnistan Studios</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About Us</h2>
        <p>We are a creative studio based in Dakhnistan. We specialize in web design, graphic design, and animation. We love to create beautiful and functional websites that showcase our clients' vision and brand identity.</p>
      </section>
      <section id="projects">
        <h2>Our Projects</h2>
        <div class="grid">
          <!-- Add your project images and links here -->
          <div class="card">
            <img src="project1.jpg" alt="Project 1">
            <div class="card-content">
              <h3>Project 1</h3>
              <p>A brief description of the project.</p>
              <a href="#" class="button">View Project</a>
            </div>
          </div>
          <!-- Repeat for other projects -->
        </div>
      </section>
      <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or inquiries, please feel free to contact us using the form below. We will get back to you as soon as possible.</p>
        <form action="#" method="post">
          <!-- Add your form fields here -->
          <div class="form-group">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
          </div>
          <!-- Repeat for other fields -->
          <div class="form-group">
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" required></textarea>
          </div>
          <div class="form-group">
            <button type="submit" class="button">Send Message</button>
          </div>
        </form>
      </section>
    </main>
    <footer>
      <p>&copy; 2023 Dakhnistan Studios. All rights reserved.</p>
    </footer>
  </div>  
</body>
</html>

```