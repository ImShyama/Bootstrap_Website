<!DOCTYPE html>
<html>
    <head>
        <title>Bootstrap Website</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
        <link href="https://fonts.googleapis.com/css?family=Josefin+Sans&display=swap" rel="stylesheet">
        <style>
            *{
                margin: 0; padding: 0; font-family: 'Josefin Sans', sans-serif;
            }
            /* Make the image fully responsive */
            .carousel-inner img {
                width: 100%;
                height: 100%;
            }
        </style>

    </head>
    <body>
        
        <header>
            <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
              <div class="container-fluid">
                <a class="navbar-brand" href="#">Travel Nepal</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>
              
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                      <a class="nav-link" href="index.html">Home <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="aboutus.html">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="services.html">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">Contact Us</a>
                    </li>
                  <!---  <li class="nav-item dropdown">
                      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Dropdown
                      </a>
                      <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Action</a>
                        <a class="dropdown-item" href="#">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Something else here</a>
                      </div>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
                    </li>
                  </ul>

                  -->
                  <form class="form-inline my-2 my-lg-0">
                    <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
                  </form>
                
                </div>
              </div>
              </nav>

  
              <div id="demo" class="carousel slide" data-ride="carousel">

                <!-- Indicators -->
                <ul class="carousel-indicators">
                  <li data-target="#demo" data-slide-to="0" class="active"></li>
                  <li data-target="#demo" data-slide-to="1"></li>
                  <li data-target="#demo" data-slide-to="2"></li>
                </ul>
                
                <!-- The slideshow -->
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="images/one.jpg" alt="MT. Everest" width="1100" height="500">
                  </div>
                  <div class="carousel-item">
                    <img src="images/two.jpg" alt="MT. Everest" width="1100" height="500">
                  </div>
                  <div class="carousel-item">
                    <img src="images/one.jpg" alt="MT. Everest" width="1100" height="500">
                  </div>
                </div>
                
                <!-- Left and right controls -->
                <a class="carousel-control-prev" href="#demo" data-slide="prev">
                  <span class="carousel-control-prev-icon"></span>
                </a>
                <a class="carousel-control-next" href="#demo" data-slide="next">
                  <span class="carousel-control-next-icon"></span>
                </a>
              </div>
              
        </header>
<!-----about us----->
        <section >
            <div class="container-fluid">
                <h1 class="text-center text-capitalize pt-5">About Us</h1>
                <hr class="w-25 mx-auto pt-5">
            
            <div class="row mb-5" >
                <div class="col-lg-6 col-md-6 col-12">
                    <img src="images/one.jpg" class="img-fluid">
                </div>
                <div class="col-lg-6 col-md-6 col-12">
                    <h1>Who I Am</h1>
                    <hr>
                    <p class="mt-5 mb-5">When you have a great story about 
                        how your product or service was built 
                        to change lives, share it. The 
                        "About Us" page is a great place
                        for it to live, too. Good stories 
                        humanize your brand, providing context
                        and meaning for your product.
                    </p>
                    <button class="btn bg-primary text-white">Know More</button>
                </div>

            </div>
            </div>
        </section>
<!----about us end------>

<!----services----->

<section >
  <div class="container">
      <h1 class="text-center text-capitalize pt-5">Services</h1>
      <hr class="w-25 mx-auto pt-5">

      <div class="row text-center mb-5">
        <div class="col-lg-4 col-md-4 col-12">
          <div class="card">
            <img src="images/two.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-4 col-12">
          <div class="card">
            <img src="images/two.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-4 col-12">
          <div class="card">
            <img src="images/two.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
        </div>
      </div>
  </div>
</section>

<!------services end------>

<!------contact demo------->

<section class="bg-primary">
  <article class="py-5 text-center text-white">
    <div>
      <h3 class="display-4">+91 1234567890</h3>
      <p >If you want best service call us now</p>
      <button class="btn btn-warning">Contact Now</button>
    </div>
  </article>
</section>

<!------contact demo end------->

<!-----galary start------>

<section>
    <div class="container">
        <h1 class="text-center text-capitalize pt-5">Galary</h1>
        <hr class="w-25 mx-auto pt-5">
      <div class="row">
      <div class="col-lg-4 col-md-2 col-12 mb-4">
        <img src="images/two.jpg" class="img-fluid">
      </div>
      <div class="col-lg-4 col-md-2 col-12 mb-4">
        <img src="images/two.jpg" class="img-fluid">
      </div>
      <div class="col-lg-4 col-md-2 col-12 mb-4">
        <img src="images/two.jpg" class="img-fluid">
      </div>
      <div class="col-lg-4 col-md-2 col-12 mb-4">
        <img src="images/two.jpg" class="img-fluid">
      </div>
      <div class="col-lg-4 col-md-2 col-12 mb-4">
        <img src="images/two.jpg" class="img-fluid">
      </div>
      <div class="col-lg-4 col-md-2 col-12 mb-4">
        <img src="images/two.jpg" class="img-fluid">
      </div>
    </div>  
    </div>
</section>

<!------galary end------->

<!------Register in short------>
<section class="bg-primary">
    <article class="py-5 ">
      <div class="text-center text-white">
        <h3 class="display-4">Want To Join</h3>
        <p >Be a part of Nepali Family.</p>
        <button class="btn btn-warning" data-toggle="modal" data-target="#myModal">Join Now</button>
      </div>
      <!-- The Modal -->
  <div class="modal fade" id="myModal">
      <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content">
        
          <!-- Modal Header -->
          <div class="modal-header">
            <h4 class="modal-title">SignUp</h4>
            <button type="button" class="close" data-dismiss="modal">&times;</button>
          </div>
          
          <!-- Modal body -->
          <div class="modal-body">
              <form action="/action_page.php">
                <div class="form-group">
                  <label for="email">Email address:</label>
                  <input type="email" class="form-control" id="email">
                </div>
                <div class="form-group">
                  <label for="pwd">Password:</label>
                  <input type="password" class="form-control" id="pwd">
                </div>
                <div class="form-group form-check">
                  <label class="form-check-label">
                    <input class="form-check-input" type="checkbox"> Remember me
                  </label>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
              </form>
          </div>
          
          <!-- Modal footer -->
          <div class="modal-footer">
            <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
          </div>
          
        </div>
      </div>
    </div>
  
    </article>
  </section>
  
  <!-- Register end -->

  <!-----Contect Us----->

  <section>
      <div class="container mb-5">
          <h1 class="text-center text-capitalize pt-5">Contect Us</h1>
          <hr class="w-25 mx-auto pt-5">
          <div class="w-50 mx-auto">
              <form action="/action_page.php">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="Text" class="form-control" id="name" placeholder="Enter Your Name" autocomplete="off">
                  </div>
                <div class="form-group">
                  <label for="email">Email address:</label>
                  <input type="email" class="form-control" id="email" placeholder="Enter Your Email" autocomplete="off">
                </div>
                <div class="form-group">
                  <label for="mbl">Mobile No:</label>
                  <input type="number" class="form-control" id="mbl" placeholder="Enter Your Mobile No." autocomplete="off">
                </div>
                <div class="form-group">
                  <label for="msg">Message</label>
                  <textarea class="form-control" placeholder="Enter Your Message"></textarea>
                </div>
                <div class="form-group form-check">
                  <label class="form-check-label">
                    <input class="form-check-input" type="checkbox"> Remember me
                  </label>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
              </form>
          </div>
  </section>

  <!--footer-->

  <footer>
    <p class="text-center bg-dark text-white">@Copyright Shyamanand Pandit</p>
  </footer>


        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

    </body>
</html>
