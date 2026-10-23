<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- SEO Best Practices -->
  <title>Alex Morgan | Front-End Developer Portfolio</title>
  <meta name="description" content="Portfolio of Alex Morgan, a front-end web developer specializing in responsive design, accessible interfaces, and modern JavaScript applications.">
  <meta name="author" content="Alex Morgan">

  <!-- External Stylesheet Link -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Skip Link for Keyboard Accessibility -->
  <a href="#main-content" class="skip-link">Skip to main content</a>

  <!-- Header Section with Navigation -->
  <header role="banner">
    <div class="logo">
      <a href="#about-me">Alex Morgan</a>
    </div>
    <nav role="navigation" aria-label="Main Navigation">
      <ul>
        <li><a href="#about-me">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Content Container -->
  <main id="main-content">

    <!-- About Me Section -->
    <section id="about-me" aria-labelledby="about-heading">
      <h2 id="about-heading">About Me</h2>
      <p>
        Hi! I'm a passionate front-end developer dedicated to building responsive, accessible, and user-friendly web interfaces. I focus on writing clean, semantic code and leveraging modern web technologies to craft smooth digital experiences.
      </p>
    </section>

    <!-- Projects Section -->
    <section id="projects" aria-labelledby="projects-heading">
      <h2 id="projects-heading">Projects</h2>
      
      <!-- Project 1 -->
      <article class="project-card">
        <figure>
          <img src="https://via.placeholder.com/600x350" alt="Screenshot of the interactive task management dashboard showing active kanban boards">
          <figcaption>TaskFlow — Interactive productivity and Kanban dashboard</figcaption>
        </figure>
        <h3>TaskFlow Web App</h3>
        <p>A full-featured Kanban board featuring real-time task drag-and-drop, persistent local storage, and high-contrast accessibility mode.</p>
        <a href="https://github.com" target="_blank" rel="noopener noreferrer" aria-label="View source code for TaskFlow Web App on GitHub">View on GitHub</a>
      </article>

      <!-- Project 2 -->
      <article class="project-card">
        <figure>
          <img src="https://via.placeholder.com/600x350" alt="Preview of an e-commerce storefront showcasing product grid with filter drawer">
          <figcaption>ShopLite — Responsive storefront with dynamic cart calculations</figcaption>
        </figure>
        <h3>ShopLite E-Commerce</h3>
        <p>A lightweight, responsive e-commerce catalog featuring client-side filtering, accessible modals, and seamless cart state synchronization.</p>
        <a href="https://github.com" target="_blank" rel="noopener noreferrer" aria-label="View source code for ShopLite E-Commerce on GitHub">View on GitHub</a>
      </article>
    </section>

    <!-- Skills Section -->
    <section id="skills" aria-labelledby="skills-heading">
      <h2 id="skills-heading">Skills & Technologies</h2>
      <ul class="skills-list">
        <li>Semantic HTML5</li>
        <li>Responsive CSS3 & Flexbox / CSS Grid</li>
        <li>Modern JavaScript (ES6+)</li>
        <li>Web Accessibility (WCAG 2.1 & WAI-ARIA)</li>
        <li>Git & GitHub Version Control</li>
        <li>RESTful APIs & Asynchronous Programming</li>
      </ul>
    </section>

    <!-- Contact Section with Accessible Form -->
    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Get in Touch</h2>
      <form action="#" method="POST" class="contact-form">
        <div class="form-group">
          <label for="full-name">Full Name <span aria-hidden="true">*</span></label>
          <input type="text" id="full-name" name="name" required aria-required="true" autocomplete="name">
        </div>

        <div class="form-group">
          <label for="email-address">Email Address <span aria-hidden="true">*</span></label>
          <input type="email" id="email-address" name="email" required aria-required="true" autocomplete="email">
        </div>

        <div class="form-group">
          <label for="message">Your Message <span aria-hidden="true">*</span></label>
          <textarea id="message" name="message" rows="5" required aria-required="true"></textarea>
        </div>

        <button type="submit">Send Message</button>
      </form>
    </section>

  </main>

  <!-- Footer Section -->
  <footer role="contentinfo">
    <p>&copy; 2026 Alex Morgan. Built with semantic HTML, modern CSS, and AI assistance.</p>
  </footer>

</body>
</html>
