<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Website Profil</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,300;0,400;0,700;1,700&family=Ubuntu:wght@400;500;700&display=swap" rel="stylesheet" />
    <!-- fonts -->

    <!-- feather icons start-->
    <script src="https://unpkg.com/feather-icons"></script>

    <!-- navbar start -->
    <section>
      <nav class="navbar">
        <a href="#" class="navbar-logo">Kenangan<span>Senja</span></a>
        <div class="navbar-nav active">
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#menu">Menu</a>
          <a href="#contact">Contact</a>
        </div>
        <div class="navbar-ektra">
          <a href="#" id="search"><i data-feather="search"></i></a>
          <a href="#" id="shopping-cart"><i data-feather="shopping-cart"></i></a>
          <a href="#" id="hamburger-menu"><i data-feather="menu"></i></a>
        </div>
      </nav>
    </section>
    <!-- navbar end end-->

    <!-- hero section start  -->
    <section class="hero" id="home">
      <main class="content">
        <h1>Mari Nikmat Secangkir <span>Kopi</span></h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        <a href="#" class="cta">Beli Sekarang</a>
      </main>
    </section>
    <!-- hero section end -->

    <!-- about section start -->
    <section class="about" id="about">
      <h2><span>Tentang</span> kami</h2>
      <div class="row">
        <div class="about-img">
          <img src="img/project2.jpg" alt="About me" />
        </div>
        <div class="content">
          <h3>Kenapa memilih kopi kami</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore blanditiis, rerum deserunt natus incidunt necessitatibus.</p>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quia similique iure distinctio cumque obcaecati repudiandae eaque! Eligendi voluptate aliquid dignissimos.</p>
        </div>
      </div>
    </section>
    <!-- about section end -->

    <!-- menu section start -->
    <section class="menu" id="menu">
      <h2><span>Menu</span> kami</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae ex repellat commodi animi numquam assumenda.</p>
      <div class="row">
        <div class="menu-card">
          <img class="menu-card-img" src="img/project3.jpg" alt="Espresso" />
          <h3 class="menu-card-tittle">- Espresso -</h3>
          <p class="menu-card-harga">IDR 15k</p>
        </div>
        <div class="menu-card">
          <img class="menu-card-img" src="img/project3.jpg" alt="Espresso" />
          <h3 class="menu-card-tittle">- Espresso -</h3>
          <p class="menu-card-harga">IDR 15k</p>
        </div>
        <div class="menu-card">
          <img class="menu-card-img" src="img/project3.jpg" alt="Espresso" />
          <h3 class="menu-card-tittle">- Espresso -</h3>
          <p class="menu-card-harga">IDR 15k</p>
        </div>
        <div class="menu-card">
          <img class="menu-card-img" src="img/project3.jpg" alt="Espresso" />
          <h3 class="menu-card-tittle">- Espresso -</h3>
          <p class="menu-card-harga">IDR 15k</p>
        </div>
        <div class="menu-card">
          <img class="menu-card-img" src="img/project3.jpg" alt="Espresso" />
          <h3 class="menu-card-tittle">- Espresso -</h3>
          <p class="menu-card-harga">IDR 15k</p>
        </div>
        <div class="menu-card">
          <img class="menu-card-img" src="img/project3.jpg" alt="Espresso" />
          <h3 class="menu-card-tittle">- Espresso -</h3>
          <p class="menu-card-harga">IDR 15k</p>
        </div>
      </div>
    </section>
    <!-- menu section end -->

    <!-- contact section start -->
    <section class="contact" id="contact">
      <h2><span>Kontak </span> Kami</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perspiciatis, debitis.</p>
      <div class="row">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d126881.56976850284!2d106.73539441429578!3d-6.387671390915933!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69e95620a297d3%3A0x1cfd4042316fb217!2sKota%20Depok%2C%20Jawa%20Barat!5e0!3m2!1sid!2sid!4v1681711599008!5m2!1sid!2sid"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          class="map"
        ></iframe>
        <form action="">
          <div class="input-group">
            <i data-feather="user"></i>
            <input type="text" placeholder="nama" />
          </div>
          <div class="input-group">
            <i data-feather="mail"></i>
            <input type="text" placeholder="email" />
          </div>
          <div class="input-group">
            <i data-feather="phone"></i>
            <input type="text" placeholder="no hp" />
          </div>
          <button type="submit" class="btn">Kirim pesan</button>
        </form>
      </div>
    </section>
    <!-- contact section end -->

    <!-- footer section start -->

    <footer>
      <div class="social">
        <a href="#"><i data-feather="instagram"></i></a>
        <a href="#"><i data-feather="twitter"></i></a>
        <a href="#"><i data-feather="twitch"></i></a>
      </div>
      <div class="links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Contact</a>
      </div>
      <div class="credit">
        <p>Created by <a href="">muhammad noval m</a>. | &copy; 2023.</p>
      </div>
    </footer>

    <!-- footer section end -->

    <script>
      feather.replace();
    </script>
    <!-- feather icons end -->

    <!-- my javascript -->
    <script src="script.js"></script>
  </body>
</html>
