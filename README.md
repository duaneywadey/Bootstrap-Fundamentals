# A step by step guide on how to use Bootstrap

# INTRO TO BOOTSTRAP
## Creating the bootstrap template

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <!--START HERE. This is where you can put anything to be seen on the page-->




    <!--UP TO HERE. This is where you can put anything to be seen on the page-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
</html>
```

## Add the container class to use Bootstrap's grid system.

```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>

    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
     -->



     <!-- CHANGES CAN BE SEEN HERE-->

    <div class="container">
      <h2>Lorem ipsum</h2>
      <p>Lorem ipsum dolor, sit amet, consectetur adipisicing elit. Beatae ipsum non deserunt omnis nostrum quaerat inventore sed odio! Modi reprehenderit doloribus inventore itaque voluptate tempora maiores delectus praesentium at libero.</p>
    </div>


     <!-- CHANGES CAN BE SEEN HERE-->



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```

## Adding the Navbar

```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>

    <!-- CHANGES CAN BE SEEN BELOW-->



  	<!-- START NAVBAR -->
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Disabled</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    <!-- END NAVBAR -->




    <!-- CHANGES CAN BE SEEN ABOVE-->



    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
    -->
    <div class="container">
      <h2>Lorem ipsum</h2>
      <p>Lorem ipsum dolor, sit amet, consectetur adipisicing elit. Beatae ipsum non deserunt omnis nostrum quaerat inventore sed odio! Modi reprehenderit doloribus inventore itaque voluptate tempora maiores delectus praesentium at libero.</p>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```

## Adding new links to our navbar

```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>


          <!-- CHANGES CAN BE SEEN BELOW-->




            <!-- NEW LINKS INSIDE THE NAVBAR -->
            <!-- STARTS HERE -->
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_1</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_2</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_3</a>
            </li>
            <!-- ENDS HERE -->





            <!-- CHANGES CAN BE SEEN ABOVE -->




            
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Disabled</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
    -->
    <div class="container">
      <h2>Lorem ipsum</h2>
      <p>Lorem ipsum dolor, sit amet, consectetur adipisicing elit. Beatae ipsum non deserunt omnis nostrum quaerat inventore sed odio! Modi reprehenderit doloribus inventore itaque voluptate tempora maiores delectus praesentium at libero.</p>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```

## Adding cards inside the container
```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>

            <!-- NEW LINKS INSIDE THE NAVBAR -->
            <!-- STARTS HERE -->
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_1</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_2</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_3</a>
            </li>
            <!-- ENDS HERE -->

            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>

              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                
                <!-- NEW LINKS INSIDE THE DROPDOWN -->
                <!-- STARTS HERE -->
                <li><a class="dropdown-item" href="#">New_Link_1</a></li>
                <li><a class="dropdown-item" href="#">New_Link_2</a></li>
                <li><a class="dropdown-item" href="#">New_Link_3</a></li>
                <li><a class="dropdown-item" href="#">New_Link_4</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Disabled</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    
    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
    -->
    <div class="container">
      

    <!-- CHANGES CAN BE SEEN BELOW-->




      <!-- A BOOTSTRAP CARD HAS BEEN CREATED -->  
      <!-- STARTS HERE -->
      <div class="card">

      </div>
      <!-- ENDS HERE -->





    <!-- CHANGES CAN BE SEEN ABOVE-->

    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```

## Adding content inside the card

```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>

            <!-- NEW LINKS INSIDE THE NAVBAR -->
            <!-- STARTS HERE -->
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_1</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_2</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_3</a>
            </li>
            <!-- ENDS HERE -->

            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>

              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                
                <!-- NEW LINKS INSIDE THE DROPDOWN -->
                <!-- STARTS HERE -->
                <li><a class="dropdown-item" href="#">New_Link_1</a></li>
                <li><a class="dropdown-item" href="#">New_Link_2</a></li>
                <li><a class="dropdown-item" href="#">New_Link_3</a></li>
                <li><a class="dropdown-item" href="#">New_Link_4</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Disabled</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    
    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
    -->
    <div class="container">


    <!-- CHANGES CAN BE SEEN BELOW-->


      
      <!-- A BOOTSTRAP CARD HAS BEEN CREATED. "mt" means margin-top -->  
      <!-- STARTS HERE -->
      <div class="card mt-4">

        <!-- CARD TITLE HAS BEEN ADDED -->
        <div class="card-header"><h2>Lorem Ipsum</h2></div>

        <!-- INSERTING CONTENT INSIDE THE CARD -->
        <div class="card-body">
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
        </div>

      </div>
      <!-- ENDS HERE -->





    <!-- CHANGES CAN BE SEEN ABOVE-->




    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```
# INTRODUCTION TO BOOTSTRAP'S GRID SYSTEM

## ROWS AND COLUMNS

```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>

            <!-- NEW LINKS INSIDE THE NAVBAR -->
            <!-- STARTS HERE -->
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_1</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_2</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_3</a>
            </li>
            <!-- ENDS HERE -->

            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>

              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                
                <!-- NEW LINKS INSIDE THE DROPDOWN -->
                <!-- STARTS HERE -->
                <li><a class="dropdown-item" href="#">New_Link_1</a></li>
                <li><a class="dropdown-item" href="#">New_Link_2</a></li>
                <li><a class="dropdown-item" href="#">New_Link_3</a></li>
                <li><a class="dropdown-item" href="#">New_Link_4</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Disabled</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    
    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
    -->

    <div class="container">



    <!-- CHANGES CAN BE SEEN BELOW-->




      <!-- The row class creates a horizontal row that contains columns --> 
      <div class="row">

        <!-- The col class creates a column with equal width. In this example, there are four columns in each row. --> 
        <div class="col">1</div>
        <div class="col">2</div>
        <div class="col">3</div>
        <div class="col">4</div>

      </div>
      
      <div class="row">
        <div class="col">1</div>
        <div class="col">2</div>
        <div class="col">3</div>
        <div class="col">4</div>
      </div>
    </div>





    <!-- CHANGES CAN BE SEEN ABOVE -->





    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```

## INSERTING CARDS INSIDE THE COL CLASS

```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>

            <!-- NEW LINKS INSIDE THE NAVBAR -->
            <!-- STARTS HERE -->
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_1</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_2</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_3</a>
            </li>
            <!-- ENDS HERE -->

            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>

              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                
                <!-- NEW LINKS INSIDE THE DROPDOWN -->
                <!-- STARTS HERE -->
                <li><a class="dropdown-item" href="#">New_Link_1</a></li>
                <li><a class="dropdown-item" href="#">New_Link_2</a></li>
                <li><a class="dropdown-item" href="#">New_Link_3</a></li>
                <li><a class="dropdown-item" href="#">New_Link_4</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Disabled</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    
    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
    -->

    <div class="container">

      <!-- The row class creates a horizontal row that contains columns --> 
      <div class="row">

        <!-- The col class creates a column with equal width. In this example, there are four columns in each row. --> 
        <div class="col">



        <!-- CHANGES CAN BE SEEN BELOW-->




          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>




        <!-- CHANGES CAN BE SEEN ABOVE -->


        </div>
        <div class="col">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>

      </div>

      <div class="row">
        <div class="col">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```

## 12-Column layout of bootstrap

```html
<!doctype html>
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>

            <!-- NEW LINKS INSIDE THE NAVBAR -->
            <!-- STARTS HERE -->
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_1</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_2</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">New_Link_3</a>
            </li>
            <!-- ENDS HERE -->

            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>

              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                
                <!-- NEW LINKS INSIDE THE DROPDOWN -->
                <!-- STARTS HERE -->
                <li><a class="dropdown-item" href="#">New_Link_1</a></li>
                <li><a class="dropdown-item" href="#">New_Link_2</a></li>
                <li><a class="dropdown-item" href="#">New_Link_3</a></li>
                <li><a class="dropdown-item" href="#">New_Link_4</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Disabled</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    
    <!-- Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them.
    -->

    <div class="container">
      <!-- If we indicate 12, it means it extends to all the columns -->
      <h3 class="mt-4 text-success">If we indicate 12, it means it extends to all the columns</h3>
      <div class="row">




      <!-- CHANGES CAN BE SEEN BELOW-->





        <div class="col-12">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
      </div>

      <!-- 12/2 = 6, so it only extends to two columns -->
      <h3 class="mt-4 text-success">12/2 = 6, so it only extends to two columns</h3>
      <div class="row">
        <div class="col-6">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
      </div>

      <!-- 12/3 = 4, so it extends to three columns -->
      <h3 class="mt-4 text-success">12/3 = 4, so it extends to three columns</h3>
      <div class="row">
        <div class="col-4">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
      </div>

      <!-- 12/4 = 3, so it extends to four columns -->
      <h3 class="mt-4 text-success">12/4 = 3, so it extends to four columns</h3>
      <div class="row">
        <div class="col-3">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col-3">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col-3">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>
        <div class="col-3">
          <div class="card mt-4">
            <div class="card-header"><h2>Lorem Ipsum</h2></div>
            <div class="card-body">
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed saepe veritatis laboriosam ea culpa quidem quae facilis adipisci. Repudiandae iure quo nam velit, eveniet id deserunt adipisci ipsa magni quam!</p>
            </div>
          </div>
        </div>




        <!-- CHANGES CAN BE SEEN ABOVE -->





      </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/
    bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>

  </body>
  </html>
```

