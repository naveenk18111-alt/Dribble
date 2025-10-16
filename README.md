# Project Responsive Web Design using Bootstrap
# Date:16-10-2025
# Name: NAVEENKUMAR V
# Reg.No: 25016071

# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :

```

<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Responsive Webpage</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      scroll-behavior: smooth;
    }
    header, section, footer {
      padding: 60px 0;
    }
    footer {
      background-color: #212529;
      color: white;
      text-align: center;
      padding: 30px 0;
    }
    .shot-img {
      height: 200px;
      object-fit: cover;
      border-radius: 0.5rem;
    }
    .designer-avatar {
      width: 40px;
      height: 40px;
      object-fit: cover;
      border-radius: 50%;
    }
    .designer-meta {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-top: 0.5rem;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">DRIBBLE</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <header id="home" class="bg-light text-center">
    <div class="container mt-5 pt-5">
      <h1 class="display-4 fw-bold">Welcome to My Website</h1>
      <h4>WHAT ARE YOU WORKING ON?</h4>
      <p class="lead text-muted">DRIBBBLE is show and tell for designers</p>
      <a href="#about" class="btn btn-primary btn-lg mt-3">Learn More</a>
    </div>
  </header>
  <section id="about">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <img src="about us.png" class="img-fluid rounded shadow" alt="About image">
        </div>
        <div class="col-md-6">
          <h2>About Us</h2>
          <p>We are a creative agency passionate about design, technology, and user experience. Our goal is to help you bring your ideas to life with beautiful and functional digital products.</p>
          <ul>
            <li>Creative Web Design</li>
            <li>Modern Technologies</li>
            <li>Responsive and Fast</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
  <section id="Services class="bg-light>
  <section class="py-5">
    <div class="container">
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card border-0">
            <img src="space.jpeg" class="shot-img w-100" alt="Shot 1">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="space.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">Rohith</span>
              </div>
              <span class="text-danger">❤️ 13082007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="sriman.jpeg" class="shot-img w-100" alt="Shot 1">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="sriman.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">Sekar</span>
              </div>
              <span class="text-danger">❤️ 13082007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="thanzil.jpeg" class="shot-img w-100" alt="Shot 1">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="thanzil.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">Thanzil</span>
              </div>
              <span class="text-danger">❤️ 13082007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="catu.jpeg" class="shot-img w-100" alt="Shot 2">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="catu.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">Navaneeth</span>
              </div>
              <span class="text-danger">❤️ 23052007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="sea.jpeg" class="shot-img w-100" alt="Shot 3">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="sea.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">NAVIN</span>
              </div>
              <span class="text-danger">❤️ 23042007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="elephant.jpg" class="shot-img w-100" alt="Shot 1">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="elephant.jpg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">dharsan</span>
              </div>
              <span class="text-danger">❤️ 13082007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="sanke.jpeg" class="shot-img w-100" alt="Shot 1">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="sanke.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">Vedha</span>
              </div>
              <span class="text-danger">❤️ 13082007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="tiger.jpeg" class="shot-img w-100" alt="Shot 1">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="tiger.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">Balaji</span>
              </div>
              <span class="text-danger">❤️ 13082007</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0">
            <img src="dog.jpeg" class="shot-img w-100" alt="Shot 1">
            <div class="designer-meta">
              <div class="d-flex align-items-center gap-2">
                <img src="dog.jpeg" class="designer-avatar" alt="Avatar">
                <span class="fw-semibold">deepak</span>
              </div>
              <span class="text-danger">❤️ 13082007</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section id="contact">
    <div class="container">
      <div class="text-center mb-5">
        <h2>Contact Us</h2>
        <p class="text-muted">We'd love to hear from you!</p>
      </div>
      <div class="row justify-content-center">
        <div class="col-md-8">
          <form>
            <div class="mb-3">
              <label class="form-label">Name</label>
              <input type="text" class="form-control" placeholder="Enter your name">
            </div>
            <div class="mb-3">
              <label class="form-label">Email</label>
              <input type="email" class="form-control" placeholder="Enter your email">
            </div>
            <div class="mb-3">
              <label class="form-label">Message</label>
              <textarea class="form-control" rows="4" placeholder="Your message"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>
  </section>
  <footer>
    <div class="container">
      <p class="mb-0">&copy; 2025 DRIBBBLE. All rights reserved.</p>
    </div>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

# OUTPUT:

<img width="1919" height="1079" alt="Screenshot 2025-10-14 201728(1)" src="https://github.com/user-attachments/assets/af5f0ac6-bca0-4d58-8ab7-bd3433b4fb58" />
<img width="1919" height="1079" alt="Screenshot 2025-10-14 201741(2)" src="https://github.com/user-attachments/assets/21340ad2-b2b8-477e-9195-5b3221367601" />
<img width="1917" height="1078" alt="Screenshot 2025-10-14 201757(3)" src="https://github.com/user-attachments/assets/27dc5fb9-5a1d-4b3c-9b30-221a27955043" />
<img width="1919" height="1079" alt="Screenshot 2025-10-14 201814(4)" src="https://github.com/user-attachments/assets/62194efe-3a08-438c-a940-64f0bcf1909f" />



# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
