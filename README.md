# HTML-project<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css"
    integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css" />
  <link rel="icon" type="image/x-icon" href="img/f-icon.png">



  <title>FIINIX</title>
</head>

<body data-bs-spy="scroll" data-bs-target=".navbar">
  <div class="banner2">

    <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-white">
      <div class="container">
        <a class="navbar-brand logo-text" href="#">Fiinix</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">

            <li class="nav-item">
              <a class="nav-link" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#services">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#portfolio">Projects</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#features">Media</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#team">Our Business</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#testimonials">Career</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact Us</a>
            </li>
          </ul>
        </div>
      </div>
  </div>
  </nav>

  <section id="home">
    <div class="container text-center">
      <div class="row justify-content-center">
        <div class="col-md-10">
          <h1 class="text-warning display-4">WE ARE CREATIVE AGENCY, CREATIVE PEOPLE</h1>
          <p class="text-white">A great building must begin with the immeasurable, must go through measurable means when
            it is being designed, and in the end must be unmeasured.</p>
          <a href="#contact" class="btn btn-brand">Contact</a>
        </div>
      </div>
    </div>
  </section>

  <section id="services">
    <div class="container">
      <div class="row">
        <div class="col-12 section-intro">
          <h1>Our Services</h1>
          <div class="hline"></div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4 col-sm-6 p-4">
          <div class="icon-box">
            <img src="img/highway-icon.jpg">
            <i class='bx bxs-landscape'></i>
          </div>
          <h4 class="title-sm mt-4">Highway</h4>
          <p class="cl">It is an engineering descipline that involves the planning, design, construction, operation, and
            maintenance to ensure safe and effective transportation of people and goods.</p>
        </div>
        <div class="col-lg-4 col-sm-6 p-4">
          <div class="icon-box">
            <img src="img/bridges-icon.png">
            <i class='bx bxs-coffee'></i>
          </div>
          <h4 class="title-sm mt-4">Bridges</h4>
          <p class="cl">The bridge industry is moving toward mechanized construction because this saves labour, shortens
            project duration and improves quality and we use latest technology to modernise the bridges.</p>
        </div>
        <div class="col-lg-4 col-sm-6 p-4">
          <div class="icon-box">
            <img src="img/train-track.png" <i class='bx bxs-image'></i>
          </div>
          <h4 class="title-sm mt-4">Train Track</h4>
          <p class="cl">The track system is the most critical part of the railway infrastructure that ensures a safe and
            smooth train ride for train passengers and we use good quality of material and ensures that no one face any
            problem.</p>
        </div>
        <div class="col-lg-4 col-sm-6 p-4">
          <div class="icon-box">
            <img src="img/building-icon.png">
            <i class='bx bxs-check-shield'></i>
          </div>
          <h4 class="title-sm mt-4">Buildings</h4>
          <p class="cl">Buildings serve several societal needs – primarily as shelter from weather, security, living
            space, privacy, to store belongings, and to comfortably live and work and we use latest technology and good
            quality of raw materail so that no problem will come in future.

          </p>
        </div>

      </div>
    </div>
  </section>




  <section id="Media">
    <h1 class="text-center">Media</h1>
    <div class="container1">
      <div class="swiper">
              <div class="swiper-wrapper">
          <div class="swiper-slide"><img src="img/bld1.jpg"> </div>
          <div class="swiper-slide"><img src="img/bld2.jpg"> </div>
          <div class="swiper-slide"><img src="img/brdg1.jpg"> </div>
          <div class="swiper-slide"><img src="img/brdg2.jpg"> </div>
          <div class="swiper-slide"><img src="img/trck1.jpg"> </div>
          ...
        </div>
        <div class="swiper-pagination"></div>
        <div class="swiper-button-prev"></div>
        <div class="swiper-button-next"></div>
        <div class="swiper-scrollbar"></div>
      </div>


    </div>
  </section>


  </section>


  <section id="contact">
    <div class="container">
      <div class="row align-items-center">
        <h3>Contact Us</h3>
        <div class="col-lg-4">
          <img src="img/cntct.jpg" alt="">
        </div>
        <div class="col-lg-6 offset-lg-1">
          <form>
            <div class="mb-3">
              <small>Name</small>
              <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            </div>
            <div class="mb-3">
              <small>Email</small>
              <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            </div>
            <div class="mb-3">
              <small>Message</small>
              <textarea name="" id="" cols="30" rows="4" class="form-control"></textarea>
            </div>
            <button type="submit" class="btn btn-brand">Submit</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <section id="cta" class="py-5">
    <div class="container py-4">
      <div class="row justify-content-center">
        <div class="col-md-6">
          <h3 class="text-white">Let's build something great.</h3>
        </div>
        <div class="col-auto">
          <a href="#" class="btn btn-light">Get Started</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="footer-top">
      <div class="container">
        <div class="row gy-5">
          <div class="col-md-4">
            <h4 class="logo-text">Fiinix</h4>
            <p class="text-dark">A great building must begin with the immeasurable, must go through measurable means
              when it is being designed, and in the end must be unmeasured.</p>
            <div class="social-icons">
              <a href="#"><i class="bx bxl-facebook"></i></a>
              <a href="#"><i class="bx bxl-twitter"></i></a>
              <a href="#"><i class="bx bxl-instagram"></i></a>
              <a href="#"><i class="bx bxl-github"></i></a>
            </div>
          </div>
          <div class="col-md-2">
            <h5 class="title-sm">Navigation</h5>
            <div class="footer-links">
              <a href="#">Services</a>
              <a href="#">Our Work</a>
              <a href="#">Team</a>
              <a href="#">Blog</a>
            </div>
          </div>
          <div class="col-md-2">
            <h5 class="title-sm">More</h5>
            <div class="footer-links">
              <a href="#">FAQ's</a>
              <a href="#">Privacy & Policy</a>
              <a href="#">Liscences</a>
            </div>
          </div>
          <div class="col-md-2">
            <h5 class="title-sm">Contact</h5>
            <div class="footer-links">
              <p class="mb text-dark">NH-44, LPU, Phagwara,Punjab,
                14401
              </p>
              <p class="mb text-dark">+91-0123456789</p>
              <p class="mb text-dark">vivekrajpoot2515@gmail.com</p>
              <p class="mb text-dark">poorna.trishitha@gmail.com</p>
              <p class="mb text-dark">gowriveeraboina@gmail.com</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="container">
        <div class="row justify-content-between gy-3">
          <div class="col-md-6">
            <p class="mb-0 text-dark">© Agency2022. All rights reserved</p>
          </div>
          <div class="col-auto">
            <p class="mb-0"></p>
          </div>
        </div>
      </div>
    </div>
  </footer>


  <!-- Optional JavaScript; choose one of the two! -->
  <script src="js/bootstrap.bundle.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>
  <script>
    const swiper = new Swiper('.swiper', {


      loop: true,


      pagination: {
        el: '.swiper-pagination',
        clickable: true,
      },


      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },


    });

  </script>
</body>

</html>
