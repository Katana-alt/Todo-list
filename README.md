# Todo-list
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Todoist | Home</title>
  <link rel="stylesheet" type="text/css" href="./static/index.css">
  <link rel="stylesheet" href="./static/testimonials.css">
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700" rel="stylesheet">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.4.1/css/all.css" 
    integrity="sha384-5sAR7xN1Nv6T6+dT2mhtzEpVJvfS3NScPQTrOxhwjIuvcA67KV2R5Jz6kr4abQsz" crossorigin="anonymous">
  <style>
    /* General Page Styling */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f2f5;
      color: #333;
    }

    /* Navigation Bar */
    nav {
      background-color: #2c3e50;
      padding: 20px 0;
      text-align: center;
    }

    nav ul {
      list-style: none;
      padding: 0;
    }

    nav ul li {
      display: inline;
      margin-right: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      font-size: 18px;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #3498db;
    }

    /* Hero Section */
    #hero {
      background: linear-gradient(to right, #3498db, #8e44ad);
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    #hero h1 {
      font-size: 3.5rem;
      margin: 20px 0;
    }

    #hero p {
      font-size: 1.2rem;
      margin-bottom: 40px;
    }

    .cta-button {
      background-color: #e74c3c;
      padding: 15px 30px;
      color: white;
      font-size: 1.1rem;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .cta-button:hover {
      background-color: #c0392b;
    }

    /* Features Section */
    #features {
      background-color: #fff;
      padding: 60px 20px;
      text-align: center;
    }

    #features h2 {
      font-size: 2.5rem;
      margin-bottom: 40px;
      color: #2c3e50;
    }

    .feature {
      display: inline-block;
      width: 30%;
      padding: 20px;
      text-align: left;
      margin: 10px;
      background-color: #ecf0f1;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .feature:hover {
      transform: translateY(-10px);
    }

    .feature-icon {
      font-size: 2.5rem;
      color: #3498db;
    }

    .feature-content h3 {
      font-size: 1.5rem;
      color: #2c3e50;
    }

    .feature-content p {
      font-size: 1rem;
      color: #7f8c8d;
    }

    /* About Section */
    #about {
      background-color: #f9f9f9;
      padding: 60px 20px;
      text-align: center;
    }

    #about h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #2c3e50;
    }

    #about p {
      font-size: 1.1rem;
      color: #7f8c8d;
      margin-bottom: 40px;
      line-height: 1.6;
    }

    /* Testimonials Section */
    #testimonials {
      background-color: #fff;
      padding: 60px 20px;
      text-align: center;
    }

    .testimonial-card {
      background-color: #f8f9fa;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      margin: 20px;
      display: inline-block;
      width: 30%;
      text-align: center;
    }

    .testimonial-logo {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    .testimonial-text {
      font-size: 1.2rem;
      color: #7f8c8d;
      margin-bottom: 20px;
    }

    #author-details {
      font-size: 1rem;
      color: #3498db;
    }

    /* Footer */
    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px 0;
    }

    footer p {
      font-size: 1rem;
      margin: 0;
    }

    .social-icons {
      margin-top: 10px;
    }

    .social-icons a {
      color: white;
      font-size: 1.5rem;
      margin: 0 10px;
      transition: color 0.3s ease;
    }

    .social-icons a:hover {
      color: #3498db;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <section class="logo">
        <a href="#"><img src="./images/logo.png" alt="Logo"></a>
      </section>
      <li><a class="cta-button navigation" href="./login.html">Login</a></li>
      <li><a class="cta-button navigation" href="#about">About</a></li>
      <li><a class="cta-button navigation" href="#testimonials">Testimonials</a></li>
      <li><a class="cta-button navigation" href="#features">Features</a></li>
    </ul>
  </nav>
  
  <!-- Hero Section -->
  <section id="hero">
    <div class="hero-content">
      <h1>Welcome to Todoist</h1>
      <p>Are you an individual looking to stay organized, or a team looking to organize tasks among team members?
        Then look no further, Todoist has got you covered
      </p>
      <a href="./signup.html" class="cta-button">Get Started</a>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features">
    <div class="container">
      <h2>Key Features</h2>
      <div class="feature">
        <i class="fas fa-check-circle feature-icon"></i>
        <div class="feature-content">
          <h3>Task Creation</h3>
          <p>Easily create and organize tasks with a simple and user-friendly interface.</p>
        </div>
      </div>
      <div class="feature">
        <i class="fas fa-check-circle feature-icon"></i>
        <div class="feature-content">
          <h3>Priority Management</h3>
          <p>Prioritize your tasks and focus on what's most important to optimize your productivity</p>
        </div>
      </div>
      <div class="feature">
        <i class="fas fa-check-circle feature-icon"></i>
        <div class="feature-content">
          <h3>Notifications and Reminders</h3>
          <p>Stay informed with timely notifications and reminders, keeping you on top of your tasks and deadlines</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2>About</h2>
      <p>Discover the ultimate task management app that brings organization and efficiency to your daily life. Todoist is designed for both individuals and teams, offering seamless task creation, deadline tracking, and collaboration features. Stay on top of your tasks, streamline teamwork, and achieve your goals with ease. Experience the power of our task management app and transform the way you work today.</p>
      <a href="#signup" class="cta-button">Sign Up Now</a>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials">
    <div class="testimonial-card">
        <img src="./images/ebenezer.png" alt="Author 1 Logo" class="testimonial-logo">
        <p class="testimonial-text">Todoist has to be the best task organizer I have used in my whole career.</p>
        <p id="author-details">Ebenezer Akhonya, DevOps Engineer. 10xCoders</p>
    </div>
    <div class="testimonial-card">
        <img src="https://cdn.pixabay.com/photo/2015/03/03/18/58/woman-657753_640.jpg" alt="Author 2 Logo" class="testimonial-logo">
        <p class="testimonial-text">This Task organizer is really great. I recommend it to any person/team who would like to stay organized.</p>
        <p id="author-details">Jane Doe, CTO, Our Startup</p>
    </div>
    <div class="testimonial-card">
      <img src="https://cdn.pixabay.com/photo/2016/11/29/13/55/man-1870016_640.jpg" alt="Author 3 Logo" class="testimonial-logo">
      <p class="testimonial-text">This Task organizer is really great. I recommend it to any person/team who would like to stay organized.</p>
      <p id="author-details">Sherlock Holmes, Frontend Dev, Cumberbatch Inc.</p>
    </div>
  </section>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Todoist. All rights reserved.</p>
    <div class="social-icons">
      <a href="https://github.com/Katana-alt" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github"></i>
      </a>
      <a href="https://twitter.com/Kitsao_katana" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-twitter"></i>
      </a>
    </div>
  </footer>
</body>
</html>
