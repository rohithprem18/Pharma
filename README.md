# Project Responsive Web Design using Bootstrap
## Date: 09.05.2024

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
home.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy - Home</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">RP Pharmacy ⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="prod.html" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="prod.html" >Ayurveda</a>
                                <a class="dropdown-item" href="prod.html">Skin Care</a>
                                <a class="dropdown-item" href="prod.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <div class="container mt-5">
        <div class="row">
            <div class="col-md-6">
                <br>
                <h1>Welcome to Our RP Pharmacy</h1>
                <img src="HOMe.png" alt="" class="img-fluid">
            </div>
            
            <div class="col-md-6">
                <p class="lead" style="font-weight: bold;"> <br> <strong> We provide high-quality pharmaceutical products to our customers.</strong> 
                </p>
                <p>
                    RP Pharmacy is a subsidiary of RP Hospitals, a highly regarded pharmacy chain in India. It is the largest and first-ever Omni-Channel Pharmacy network in Asia, with a vast network of over 5500 outlets strategically located in key locations across the country. The delivery service covers over 19000+ pin codes, making it highly accessible to people throughout India.
                </p>
                <p>
                    The pharmacy is accredited with an International Quality Certification, which speaks to its commitment to providing authentic and reasonably priced medication round the clock. The 24-hour pharmacies and home delivery network are designed to ensure customers' convenience, while the customer care is available at any time of the day.
                </p>
                <p>
                    Quality is the foundation of RP Pharmacy's operations. Over the last two decades, the pharmacy has gained extensive experience in pharmacy operations management, and it is dedicated to offering the best services in the industry. The pharmacy is adequately stocked with a comprehensive range of medicines, over-the-counter (OTC), and fast-moving consumer goods (FMCG) products. The qualified and experienced staff are available to address all your needs.
                </p>
    
            </div>
            <body style="background-image: url('bg.jpg'); background-size: cover; background-repeat: no-repeat;">

        </div>
    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy; RP Pharmacy. Designed By Rohith Prem S </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>

prod.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy - Products</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<style>
     .product-card {
    height: 680px; 
    border: 5px solid black; 
    margin-bottom: 40px;
}

</style>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">RP Pharmacy ⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="prod.html" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="prod.html" >Ayurveda</a>
                                <a class="dropdown-item" href="prod.html">Skin Care</a>
                                <a class="dropdown-item" href="prod.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
        <br> <br> <br> <br>
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="prod1.png" class="card-img-top product-image" alt="Medicine 1">
                    <div class="card-body">
                        <h5 class="card-title">Zandu Nityam Ayurvedic Laxative, 30 Tablets</h5>
                        <p class="card-text">With Zandu Nityam Tablet, you can experience the freedom of a healthy and regular bowel movement. These tablets work gently yet effectively.
                        </p>
                        <p class="card-text" align="center"> <b>Rate: Rs 100 /- </b></p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="prod2.png" class="card-img-top product-image" alt="Medicine 2">
                    <div class="card-body">
                        <h5 class="card-title">Supradyn Daily Multivitamin Builds Energy 60 Tablets</h5>
                        <p class="card-text">This complex blend includes the active form of vitamin B12 known as methylcobalamin, which plays a pivotal role in boosting energy levels.</p>
                        <p class="card-text" align="center"> <b>Rate: Rs 250 /- </b></p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="prod3.png" class="card-img-top product-image" alt="Medicine 3">
                    <div class="card-body">
                        <h5 class="card-title">Rablet 20 Tablet 15's</h5>
                        <p class="card-text">Rablet 20 Tablet 15's belongs to a group of antiulcer medicines called proton pump inhibitors used to treat duodenal ulcers, gastro-oesophageal reflux disease (reflux of gastric contents into the oesophagus), heartburn, erosive oesophagitis (acid-related damage to the lining of the oesophagus), infections caused by Helicobacter pylori when given along with an antibiotic, and Zollinger-Ellison syndrome.</p>
                        <p class="card-text" align="center"> <b>Rate: Rs 250 /- </b></p>
                    </div>
                </div>
            </div>
        </div>

    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy; RP Pharmacy. Designed By Rohith Prem S </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>

about.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - RP Pharmacy</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        .product-card {
            height: 680px;
            border: 5px solid black;
            margin-bottom: 40px;
        }
    </style>
</head>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">RP Pharmacy ⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="prod.html" id="navbarDropdown" role="button"
                                data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="prod.html">Ayurveda</a>
                                <a class="dropdown-item" href="prod.html">Skin Care</a>
                                <a class="dropdown-item" href="prod.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <br> <br> <br> <br>
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-12">
                <h2 class="text-center">About RP Pharmacy</h2>
                <img src="download.png" alt="RP Pharmacy Logo" style="display: block; margin: auto; width: 200px; height: auto;">
                <p class="text-center">RP Pharmacy is a trusted provider of high-quality pharmaceutical products
                    since 20XX. We are committed to improving the health and well-being of our customers by offering a
                    wide range of medicines, supplements, and healthcare products.</p>
                <p class="text-center">Our team of experienced pharmacists and healthcare professionals ensures that
                    every product we offer meets the highest standards of safety and efficacy. We strive to provide
                    exceptional customer service and personalized care to all our clients.</p>
                <p class="text-center">At RP Pharmacy, your health is our priority. We are dedicated to helping you
                    lead a healthier and happier life.</p>
            </div>
        </div>
        <body style="background-image: url('bg.jpg'); background-size: cover; background-repeat: no-repeat;">

    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy; RP Pharmacy. Designed By Rohith Prem S </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>

contact.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - RP Pharmacy</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        .product-card {
            height: 680px;
            border: 5px solid black;
            margin-bottom: 40px;
        }
    </style>
</head>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">RP Pharmacy ⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="prod.html" id="navbarDropdown" role="button"
                                data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="prod.html">Ayurveda</a>
                                <a class="dropdown-item" href="prod.html">Skin Care</a>
                                <a class="dropdown-item" href="prod.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <br> <br> <br> <br>
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-12">
                <h2 class="text-center">About RP Pharmacy</h2>
                <img src="download.png" alt="RP Pharmacy Logo" style="display: block; margin: auto; width: 200px; height: auto;">
                <p class="text-center">RP Pharmacy is a trusted provider of high-quality pharmaceutical products
                    since 20XX. We are committed to improving the health and well-being of our customers by offering a
                    wide range of medicines, supplements, and healthcare products.</p>
                <p class="text-center">Our team of experienced pharmacists and healthcare professionals ensures that
                    every product we offer meets the highest standards of safety and efficacy. We strive to provide
                    exceptional customer service and personalized care to all our clients.</p>
                <p class="text-center">At RP Pharmacy, your health is our priority. We are dedicated to helping you
                    lead a healthier and happier life.</p>
            </div>
        </div>
        <body style="background-image: url('bg.jpg'); background-size: cover; background-repeat: no-repeat;">

    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy; RP Pharmacy. Designed By Rohith Prem S </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
```

## OUTPUT:
![alt text](<Screenshot (75).png>)
![alt text](<Screenshot (76).png>)
![alt text](<Screenshot (77).png>)
![alt text](<Screenshot (78).png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
