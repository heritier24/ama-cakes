<template>
  <div>
    <!-- Topbar Start -->
    <div class="container-fluid px-0 d-none d-lg-block">
      <div class="row gx-0">
        <div class="col-lg-4 text-center bg-secondary py-3">
          <div class="d-inline-flex align-items-center justify-content-center">
            <i class="bi bi-envelope fs-1 text-primary me-3"></i>
            <div class="text-start">
              <h6 class="text-uppercase mb-1">Email Us</h6>
              <span>info@example.com</span>
            </div>
          </div>
        </div>
        <div class="col-lg-4 text-center bg-primary border-inner py-3">
          <div class="d-inline-flex align-items-center justify-content-center">
            <a href="#" class="navbar-brand">
              <h1 class="m-0 text-uppercase text-white">
                <i class="fa fa-birthday-cake fs-1 text-dark me-3"></i>Ama Cakes
                Arts
              </h1>
            </a>
          </div>
        </div>
        <div class="col-lg-4 text-center bg-secondary py-3">
          <div class="d-inline-flex align-items-center justify-content-center">
            <i class="bi bi-phone-vibrate fs-1 text-primary me-3"></i>
            <div class="text-start">
              <h6 class="text-uppercase mb-1">Call Us</h6>
              <span>+012 345 6789</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Topbar End -->

    <!-- Navbar Start -->
    <nav
      class="navbar navbar-expand-lg bg-dark navbar-dark shadow-sm py-3 py-lg-0 px-3 px-lg-0"
    >
      <a href="index.html" class="navbar-brand d-block d-lg-none">
        <h1 class="m-0 text-uppercase text-white">
          <i class="fa fa-birthday-cake fs-1 text-primary me-3"></i>Ama Cakes
          Arts
        </h1>
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarCollapse"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <div class="navbar-nav ms-auto mx-lg-auto py-0">
          <a href="/" class="nav-item nav-link">Home</a>
          <a href="/about" class="nav-item nav-link active">About Us</a>
          <a href="/menu" class="nav-item nav-link">Menu & Pricing</a>
          <a href="/chefs" class="nav-item nav-link">Master Chefs</a>
          <div class="nav-item dropdown">
            <a
              href="#"
              class="nav-link dropdown-toggle"
              data-bs-toggle="dropdown"
              >Pages</a
            >
            <div class="dropdown-menu m-0">
              <a href="service.html" class="dropdown-item">Our Service</a>
              <a href="testimonial.html" class="dropdown-item">Testimonial</a>
            </div>
          </div>
          <a href="/contact" class="nav-item nav-link">Contact Us</a>
        </div>
      </div>
    </nav>
    <!-- Navbar End -->

    <!-- Page Header Start -->
    <div class="container-fluid bg-dark bg-img p-5 mb-5">
      <div class="row">
        <div class="col-12 text-center">
          <h1 class="display-4 text-uppercase text-white">About Us</h1>
          <a href="">Home</a>
          <i class="far fa-square text-primary px-2"></i>
          <a href="">About</a>
        </div>
      </div>
    </div>
    <!-- Page Header End -->

    <!-- About Start -->
    <div class="container-fluid pt-5">
      <div class="container">
        <div
          class="section-title position-relative text-center mx-auto mb-5 pb-3"
          style="max-width: 600px"
        >
          <h2 class="text-primary font-secondary">About Us</h2>
          <h1 class="display-4 text-uppercase">Welcome To Ama Cakes</h1>
        </div>
        <div class="row gx-5">
          <div class="col-lg-5 mb-5 mb-lg-0" style="min-height: 400px">
            <div class="position-relative h-100">
              <img
                class="position-absolute w-100 h-100"
                src="img/about.jpg"
                style="object-fit: cover"
              />
            </div>
          </div>
          <div class="col-lg-6 pb-5">
            <h4 class="mb-4">
              Tempor erat elitr rebum clita. Diam dolor diam ipsum erat lorem
              sed stet labore lorem sit clita duo
            </h4>
            <p class="mb-5">
              Tempor erat elitr at rebum at at clita. Diam dolor diam ipsum et
              tempor sit. Clita erat ipsum et lorem et sit, sed stet no labore
              lorem sit. Sanctus clita duo justo et tempor eirmod magna dolore
              erat amet magna
            </p>
            <div class="row g-5">
              <div class="col-sm-6">
                <div
                  class="d-flex align-items-center justify-content-center bg-primary border-inner mb-4"
                  style="width: 90px; height: 90px"
                >
                  <i class="fa fa-heartbeat fa-2x text-white"></i>
                </div>
                <h4 class="text-uppercase">100% Healthy</h4>
                <p class="mb-0">
                  Labore justo vero ipsum sit clita erat lorem magna clita
                  nonumy dolor magna dolor vero
                </p>
              </div>
              <div class="col-sm-6">
                <div
                  class="d-flex align-items-center justify-content-center bg-primary border-inner mb-4"
                  style="width: 90px; height: 90px"
                >
                  <i class="fa fa-award fa-2x text-white"></i>
                </div>
                <h4 class="text-uppercase">Award Winning</h4>
                <p class="mb-0">
                  Labore justo vero ipsum sit clita erat lorem magna clita
                  nonumy dolor magna dolor vero
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- About End -->

    <!-- Facts Start -->
    <div class="container-fluid bg-img py-5 mb-5">
      <div class="container py-5">
        <div class="row gx-5 gy-4">
          <div class="col-lg-3 col-md-6">
            <div class="d-flex">
              <div
                class="bg-primary border-inner d-flex align-items-center justify-content-center mb-3"
                style="width: 60px; height: 60px"
              >
                <i class="fa fa-star text-white"></i>
              </div>
              <div class="ps-4">
                <h6 class="text-primary text-uppercase">Our Experience</h6>
                <h1 class="display-5 text-white mb-0" data-toggle="counter-up">
                  12345
                </h1>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="d-flex">
              <div
                class="bg-primary border-inner d-flex align-items-center justify-content-center mb-3"
                style="width: 60px; height: 60px"
              >
                <i class="fa fa-users text-white"></i>
              </div>
              <div class="ps-4">
                <h6 class="text-primary text-uppercase">Cake Specialist</h6>
                <h1 class="display-5 text-white mb-0" data-toggle="counter-up">
                  12345
                </h1>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="d-flex">
              <div
                class="bg-primary border-inner d-flex align-items-center justify-content-center mb-3"
                style="width: 60px; height: 60px"
              >
                <i class="fa fa-check text-white"></i>
              </div>
              <div class="ps-4">
                <h6 class="text-primary text-uppercase">Complete Project</h6>
                <h1 class="display-5 text-white mb-0" data-toggle="counter-up">
                  12345
                </h1>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="d-flex">
              <div
                class="bg-primary border-inner d-flex align-items-center justify-content-center mb-3"
                style="width: 60px; height: 60px"
              >
                <i class="fa fa-mug-hot text-white"></i>
              </div>
              <div class="ps-4">
                <h6 class="text-primary text-uppercase">Happy Clients</h6>
                <h1 class="display-5 text-white mb-0" data-toggle="counter-up">
                  12345
                </h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Facts End -->

    <!-- Footer Start -->
    <div class="container-fluid bg-img text-secondary" style="margin-top: 90px">
      <div class="container">
        <div class="row gx-5">
          <div class="col-lg-4 col-md-6 mb-lg-n5">
            <div
              class="d-flex flex-column align-items-center justify-content-center text-center h-100 bg-primary border-inner p-4"
            >
              <a href="index.html" class="navbar-brand">
                <h1 class="m-0 text-uppercase text-white">
                  <i class="fa fa-birthday-cake fs-1 text-dark me-3"></i>Ama
                  Cakes Arts
                </h1>
              </a>
              <p class="mt-3">
                Lorem diam sit erat dolor elitr et, diam lorem justo labore amet
                clita labore stet eos magna sit. Elitr dolor eirmod duo tempor
                lorem, elitr clita ipsum sea. Nonumy rebum et takimata ea
                takimata amet gubergren, erat rebum magna lorem stet eos. Diam
                amet et kasd eos duo dolore no.
              </p>
            </div>
          </div>
          <div class="col-lg-8 col-md-6">
            <div class="row gx-5">
              <div class="col-lg-4 col-md-12 pt-5 mb-5">
                <h4 class="text-primary text-uppercase mb-4">Get In Touch</h4>
                <div class="d-flex mb-2">
                  <i class="bi bi-geo-alt text-primary me-2"></i>
                  <p class="mb-0">Muhima, Near Hospital</p>
                </div>
                <div class="d-flex mb-2">
                  <i class="bi bi-envelope-open text-primary me-2"></i>
                  <p class="mb-0">amacakesart@gmail.com</p>
                </div>
                <div class="d-flex mb-2">
                  <i class="bi bi-telephone text-primary me-2"></i>
                  <p class="mb-0">+250 784 315 934</p>
                </div>
                <div class="d-flex mt-4">
                  <a
                    class="btn btn-lg btn-primary btn-lg-square border-inner rounded-0 me-2"
                    href="#"
                    ><i class="fab fa-twitter fw-normal"></i
                  ></a>
                  <a
                    class="btn btn-lg btn-primary btn-lg-square border-inner rounded-0 me-2"
                    href="#"
                    ><i class="fab fa-facebook-f fw-normal"></i
                  ></a>
                  <a
                    class="btn btn-lg btn-primary btn-lg-square border-inner rounded-0 me-2"
                    href="#"
                    ><i class="fab fa-linkedin-in fw-normal"></i
                  ></a>
                </div>
              </div>
              <div class="col-lg-4 col-md-12 pt-0 pt-lg-5 mb-5">
                <h4 class="text-primary text-uppercase mb-4">Quick Links</h4>
                <div class="d-flex flex-column justify-content-start">
                  <a class="text-secondary mb-2" href="#"
                    ><i class="bi bi-arrow-right text-primary me-2"></i>Home</a
                  >
                  <a class="text-secondary mb-2" href="#"
                    ><i class="bi bi-arrow-right text-primary me-2"></i>About
                    Us</a
                  >
                  <a class="text-secondary mb-2" href="#"
                    ><i class="bi bi-arrow-right text-primary me-2"></i>Our
                    Services</a
                  >
                  <a class="text-secondary mb-2" href="#"
                    ><i class="bi bi-arrow-right text-primary me-2"></i>Meet The
                    Team</a
                  >
                  <a class="text-secondary mb-2" href="#"
                    ><i class="bi bi-arrow-right text-primary me-2"></i>Latest
                    Blog</a
                  >
                  <a class="text-secondary" href="#"
                    ><i class="bi bi-arrow-right text-primary me-2"></i>Contact
                    Us</a
                  >
                </div>
              </div>
              <div class="col-lg-4 col-md-12 pt-0 pt-lg-5 mb-5">
                <h4 class="text-primary text-uppercase mb-4">Newsletter</h4>
                <p>Amet justo diam dolor rebum lorem sit stet sea justo kasd</p>
                <form action="">
                  <div class="input-group">
                    <input
                      type="text"
                      class="form-control border-white p-3"
                      placeholder="Your Email"
                    />
                    <button class="btn btn-primary">Sign Up</button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      class="container-fluid text-secondary py-4"
      style="background: #111111"
    >
      <div class="container text-center">
        <p class="mb-0">
          &copy;
          <a class="text-white border-bottom" href="#">Ama Cakes Arts</a>. All
          Rights Reserved.
        </p>
      </div>
    </div>
    <!-- Footer End -->

    <!-- Back to Top -->
    <a href="#" class="btn btn-primary border-inner py-3 fs-4 back-to-top"
      ><i class="bi bi-arrow-up"></i
    ></a>
  </div>
</template>
