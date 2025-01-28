<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Creativex_hub - Marketing Agency</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero-section {
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                  url('images/hero-bg.jpg') center/cover;
      padding: 120px 0;
    }
    .service-img {
      height: 200px;
      object-fit: cover;
    }
    .portfolio-card {
      transition: transform 0.3s;
    }
    .portfolio-card:hover {
      transform: translateY(-5px);
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">Creativex_hub</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#portfolio">Portfolio</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero-section text-white">
    <div class="container text-center">
      <h1 class="display-4 mb-4">Your Creative Marketing Partner</h1>
      <p class="lead mb-4">We help brands grow through innovative strategies and stunning visuals.</p>
      <a href="#contact" class="btn btn-primary btn-lg px-5">Get Started</a>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-5">
    <div class="container">
      <h2 class="text-center mb-5">Our Services</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card h-100 border-0 shadow">
            <img src="images/social-media.jpg" class="card-img-top service-img" alt="Social Media Marketing">
            <div class="card-body text-center">
              <h3>Social Media Marketing</h3>
              <p>Comprehensive social media strategies across all major platforms.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100 border-0 shadow">
            <img src="images/content-creation.jpg" class="card-img-top service-img" alt="Content Creation">
            <div class="card-body text-center">
              <h3>Content Creation</h3>
              <p>Professional photography, videography, and copywriting services.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100 border-0 shadow">
            <img src="images/seo.jpg" class="card-img-top service-img" alt="SEO Optimization">
            <div class="card-body text-center">
              <h3>SEO Optimization</h3>
              <p>Search engine optimization that drives organic traffic.</p>
            </div>
          </div>
        </div>
        <!-- Add more service cards following the same pattern -->
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-5">Our Work</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card portfolio-card h-100 shadow">
            <img src="images/target-scores-project.jpg" class="card-img-top" alt="Target Scores Project">
            <div class="card-body">
              <h4>Target Scores Platform</h4>
              <p>Golf scoring system development and marketing</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card portfolio-card h-100 shadow">
            <img src="images/tuttify-dashboard.jpg" class="card-img-top" alt="Tuttify Dashboard">
            <div class="card-body">
              <h4>Tuttify Analytics</h4>
              <p>Social media management dashboard design</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card portfolio-card h-100 shadow">
            <img src="images/video-campaign.jpg" class="card-img-top" alt="Video Campaign">
            <div class="card-body">
              <h4>Video Marketing</h4>
              <p>High-engagement social media video campaigns</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5">
    <div class="container">
      <div class="text-center mb-5">
        <h2>Let's Work Together</h2>
        <p class="lead">Ready to take your marketing to the next level?</p>
      </div>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <form>
            <div class="mb-3">
              <input type="text" class="form-control" placeholder="Your Name">
            </div>
            <div class="mb-3">
              <input type="email" class="form-control" placeholder="Your Email">
            </div>
            <div class="mb-3">
              <textarea class="form-control" rows="4" placeholder="Your Message"></textarea>
            </div>
            <button type="submit" class="btn btn-primary w-100">Send Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <footer class="bg-dark text-white py-4">
    <div class="container text-center">
      <div class="mb-3">
        <a href="https://instagram.com/Creativex_hub" target="_blank" class="text-white me-3">
          <i class="bi bi-instagram"></i> Instagram
        </a>
        <a href="https://upwork.com" target="_blank" class="text-white">
          <i class="bi bi-briefcase"></i> Upwork
        </a>
      </div>
      <p>&copy; 2023 Creativex_hub. All rights reserved.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>