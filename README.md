# EX01 Developing a Simple Webserver
## Date:
30.03.2024
## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aadhithya</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        a{
            padding: 10px;
            color: brown;
            text-decoration: none;
        }
        a:hover{
            color:black;
        }
    </style>
</head>

<body>
    <div class="row" style="background-color:blanchedalmond">
        <div class="col-3 border">
            <a href=""></a>
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-linkedin"></i></a>
            <a href=""><i class="bi bi-pinterest"></i></a>
            <a href=""><i class="bi bi-whatsapp"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>

        </div>
        <div class="col-5 border">
            <a href="">Alumni</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">Events</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">Career</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">Login</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">SEC Portel</a><i class="bi bi-three-dots-vertical"></i>
        </div>
        <div class="col-4 border">
            <i class="bi bi-search"></i>
            <input type="text" name="" placeholder="Search">
        </div>
    </div>
    <div>
        <div>
            <div class="row">
                <div class="col-4">
                    <img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="" style="height: 100px;width:420px">
                </div>
                <div class="col-5" style="padding: 15px;">
                    <nav class="navbar navbar-expand-lg bg-body-tertiary">
                        <div class="container-fluid">
                          
                          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                          </button>
                          <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                              <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">Home</a>
                              </li>
                              <li class="nav-item">
                                <a class="nav-link" href="#">About</a>
                              </li>
                              <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                  Departments
                                </a>
                                <ul class="dropdown-menu">
                                  <li><a class="dropdown-item" href="#">Computer Science</a></li>
                                  <li><a class="dropdown-item" href="#">Information Technology</a></li>
                                  <li><a class="dropdown-item" href="#">Electronics and Communication</a></li>
                                  <li><a class="dropdown-item" href="#">Mechanical</a></li>
                                </ul>
                              </li>
                              <li class="nav-item">
                                <a class="nav-link" href="#">Life at SEC</a>
                              </li>
                              <li class="nav-item">
                                <a class="nav-link" href="#">Contact us</a>
                              </li>
                              <li class="nav-item">
                                <a class="nav-link" href="">SEC</a>
                              </li>
                            </ul>
                            
                          </div>
                        </div>
                      </nav>
                </div>
                <div class="col-3">

                </div>
            </div>
        </div>
    </div>
    


    <div id="carouselExampleIndicators" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="a2.jpeg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="a1.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="a3.jpg" class="d-block w-100" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>

</html>

```
## OUTPUT:

![output](https://github.com/AadhithyaRaj/simplewebserver/assets/128829484/56031bf8-597d-40f8-8992-08b5829a40d2)



## RESULT:
The program for implementing simple webserver is executed successfully.
