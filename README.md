# Project Responsive Web Design using Bootstrap
## Date:13-05-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>contact us</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body style="background-color: rgb(0, 255, 42);">


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PARVEZ Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">HAIR CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
              <li><a class="dropdown-item" href="#">BODY CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="container py-5">
    <h1 class="text-center mb-4">Contact Us</h1>
    <div class="row">
      <div class="col-md-6">
        <h3>INFO</h3>
        <p>PARVEZ Pharma</p>
        <p>PARVEZ Pharma
           MILLET Nagar,
           Chennai,
           PINCODE-600015.
        </p>
        <p>Phone Number: <a href="tel:+1234567890">1253698745</a></p>
        <p>Email: <a href="samcha:info@yourcompany.com">info@Samcha.com</a></p>
      </div>
      <div class="col-md-6">
        <h3>To stay in touch with us </h3>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(173, 199, 69);" class="text-center py-3">
    <p>&copy; 2024 PARVEZ Pharma MOHAMMED PARVEZ(212223040113)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
event.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Events</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" crossorigin="anonymous">
</head>
<body style="background-color: rgb(0, 255, 68);">

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PARVEZ Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">HAIR CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
              <li><a class="dropdown-item" href="#">BODY CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-5">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="7..jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Researchers target neurogenesis in new approach to treat Parkinson's disease</h5>
            <p class="card-text" style="font-size: large;">Researchers at the University of Toronto have found a way to better control the preclinical generation of key neurons depleted in Parkinson's disease, pointing toward a new approach for a disease with no cure and few effective treatments.

            </p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="8..jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Melanoma in darker skin tones</h5>
            <p class="card-text" style="font-size: large;">Melanoma, an aggressive form of skin cancer that accounts for 75% of all skin-cancer-related deaths, is often detected later in people with darker skin complexions -- and the consequences can be devastating, a Mayo Clinic study reveals.

            </p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="9..jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Coronavirus disease (COVID-19)</h5>
            <p class="card-text" style="font-size: large;">Although COVID-19 defines the symptomatic disease caused by SARS-CoV-2, the cases are presented in this dashboard meet one of two alternate definitions of confirmed case of SARS-CoV-2 infection in international surveillance reporting:Governments.


            </p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer style="background-color: rgb(173, 199, 69);" class="text-center py-3">
    <p>&copy; 2024 PARVEZ Pharma MOHAMMED PARVEZ(212223040113)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
products.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body style="background-color: rgb(0, 255, 68);">


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PARVEZ Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">HAIR CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
              <li><a class="dropdown-item" href="#">BODY CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="4..jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Neurocalm</h5>
            <p class="card-text">Neurocalm is a medication designed to alleviate symptoms of anxiety and promote relaxation by regulating neurotransmitter activity in the brain. It helps manage anxiety disorders, including generalized anxiety disorder and panic disorder.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="5..jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> Diabetes</h5>
            <p class="card-text">Diabetes is a chronic medical condition characterized by high levels of glucose (sugar) in the blood. It occurs when the body either doesn't produce enough insulin or can't effectively use the insulin it produces.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="6..jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> Bloodpressure</h5>
            <p class="card-text"> Blood pressure is the force exerted by the blood against the walls of the arteries as it flows through the circulatory system.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer style="background-color: rgb(175, 199, 69);" class="text-center py-3">
    <p>&copy; 2024 PARVEZ Pharma MOHAMMED PARVEZ(212223040113)</p>
  </footer>

</body>
</html>
```
```
app.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
<body style="background-color: rgb(0, 255, 68);">

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PARVEZ Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">HAIR CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
              <li><a class="dropdown-item" href="#">BODY CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>Global Health and Access to Medicines</h1>
      <p class="lead">Our aim is to provide healthcare and medicines to people in all over country.</p>
      <a href="#" class="btn btn-primary btn-lg">MORE INFO</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="1..jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">UPDATION</h5>
            <p class="card-text">We are prone to update our machines to more enhanced way to make sure of your health needs</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="2..jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">QUALITY</h5>
            <p class="card-text">Our commitment to quality ensures the safety and cleanliness of rooms to avoid spreading od disease.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="3..jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient Care</h5>
            <p class="card-text">We are so kind to our patient.Its our responsibility to take a complete care of them.Every patient is equal to us no matter they are rich or poor.We respect our patients.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(166, 199, 69);" class="text-center py-3">
    <p>&copy; 2024 PARVEZ Pharma MOHAMMED PARVEZ(212223040113) </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-05-13 182337.png>)
![alt text](<Screenshot 2024-05-13 182348.png>)
![alt text](<Screenshot 2024-05-13 182359.png>)
![alt text](<Screenshot 2024-05-13 182409.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
