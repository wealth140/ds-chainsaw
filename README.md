# ds-chainsaw
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Church Website</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }
    .hero {
      background: url('https://via.placeholder.com/1500x500') no-repeat center center;
      background-size: cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .footer {
      background-color: #343a40;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .footer a {
      color: #ffc107;
      text-decoration: none;
    }
    .footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Church Name</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#sermons">Sermons</a></li>
        <li class="nav-item"><a class="nav-link" href="#events">Events</a></li>
        <li class="nav-item"><a class="nav-link" href="#donate">Donate</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section class="hero" id="home">
  <div class="container">
    <h1>Welcome to Our Church</h1>
    <p>Discover faith, hope, and love with our community.</p>
    <a href="#sermons" class="btn btn-primary btn-lg">Watch Sermons</a>
  </div>
</section>

<!-- Sermons Section -->
<section class="py-5" id="sermons">
  <div class="container">
    <h2 class="text-center mb-4">Sermons</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://via.placeholder.com/400x250" class="card-img-top" alt="Sermon">
          <div class="card-body">
            <h5 class="card-title">Sermon Title</h5>
            <p class="card-text">A brief description of the sermon goes here.</p>
            <a href="#" class="btn btn-primary">Watch Now</a>
          </div>
        </div>
      </div>
      <!-- Add more cards as needed -->
    </div>
  </div>
</section>

<!-- Events Section -->
<section class="bg-light py-5" id="events">
  <div class="container">
    <h2 class="text-center mb-4">Upcoming Events</h2>
    <ul class="list-group">
      <li class="list-group-item">
        <strong>Sunday Service</strong> - Every Sunday at 10:00 AM
      </li>
      <li class="list-group-item">
        <strong>Bible Study</strong> - Wednesdays at 7:00 PM
      </li>
      <li class="list-group-item">
        <strong>Community Outreach</strong> - December 15th at 2:00 PM
      </li>
    </ul>
  </div>
</section>

<!-- Donate Section -->
<section class="py-5 text-center" id="donate">
  <div class="container">
    <h2>Support Our Mission</h2>
    <p>Your contributions help us serve our community and spread the message of love.</p>
    <a href="#" class="btn btn-success btn-lg">Donate Now</a>
  </div>
</section>

<!-- Contact Section -->
<section class="py-5" id="contact">
  <div class="container">
    <h2 class="text-center mb-4">Contact Us</h2>
    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Name</label>
        <input type="text" class="form-control" id="name" placeholder="Your Name">
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" placeholder="Your Email">
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message</label>
        <textarea class="form-control" id="message" rows="5" placeholder="Your Message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Send Message</button>
    </form>
  </div>
</section>

<!-- Footer -->
<footer class="footer">
  <p>&copy; 2024 Church Name. All rights reserved. | <a href="#contact">Contact</a></p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>