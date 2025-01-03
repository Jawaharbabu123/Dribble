# Project Responsive Web Design using Bootstrap
## Date:30-12-2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-light border-bottom">
    <div class="container">
        <a class="navbar-brand" href="index.html">Dribbble</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#cards">Discover</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="jobs.html">Jobs</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="signup.html">Sign Up</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="login.html">Login</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<div class="container text-center py-5">
    <h1>Discover the world’s top designers and creatives</h1>
    <p class="text-muted">Showcase your work, discover new projects, and get inspired.</p>
</div>

<div id="cards" class="container">
    <div class="row g-4">
        <div class="col-md-4 col-sm-6">
            <div class="card">
                <img src="naruto.jpeg" class="card-img-top" alt="Design">
                <div class="card-body">
                    <h5 class="card-title">Naruto</h5>
                    <p class="card-text">DATTEBAYO!</p>
                </div>
            </div>
        </div>
        <div class="col-md-4 col-sm-6">
            <div class="card">
                <img src="saveetha photos.jpeg" class="card-img-top" alt="Design">
                <div class="card-body">
                    <h5 class="card-title">Saveetha</h5>
                    <p class="card-text">Saveetha Engineering College - School / College / Coaching /</p>
                </div>
            </div>
        </div>
        <div class="col-md-4 col-sm-6">
            <div class="card">
                <img src="vijay tvk.webp" class="card-img-top" alt="Design">
                <div class="card-body">
                    <h5 class="card-title">TVK</h5>
                    <p class="card-text">The Tamilaga Vettri Kazhagam </p>
                </div>
            </div>
        </div>
        <div class="col-md-4 col-sm-6">
            <div class="card">
                <img src="biriyani photos.jpeg" class="card-img-top" alt="Design">
                <div class="card-body">
                    <h5 class="card-title">Biriyani</h5>
                    <p class="card-text">Biryani is a mixed rice dish popular in South Asia</p>
                </div>
            </div>
        </div>
        <div class="col-md-4 col-sm-6">
            <div class="card">
                <img src="chrome photo.png" class="card-img-top" alt="Design">
                <div class="card-body">
                    <h5 class="card-title">Chrome</h5>
                    <p class="card-text">Google Chrome is a fast web browser available at no charge. </p>
                </div>
            </div>
        </div>
        <div class="col-md-4 col-sm-6">
            <div class="card">
                <img src="hospital photos.jpeg" class="card-img-top" alt="Design">
                <div class="card-body">
                    <h5 class="card-title">Hospital</h5>
                    <p class="card-text">A hospital is a healthcare institution providing patient treatment with specialized health science and auxiliary healthcare staff and medical equipment. </p>
                </div>
            </div>
        </div>
    </div>
</div>

<footer class="footer mt-5">
    <div class="container text-center">
        <p>Designed by Jawahar(24004142)</p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot (5).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
