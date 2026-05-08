<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ubuntu Rail Solutions</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins', sans-serif;
    }

    body{
      background:#f4f6f8;
      color:#222;
      line-height:1.6;
    }

    header{
      background:#0d1b2a;
      padding:20px 8%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:sticky;
      top:0;
      z-index:1000;
    }

    .logo{
      color:#fff;
      font-size:28px;
      font-weight:700;
    }

    .logo span{
      color:#fca311;
    }

    nav a{
      color:#fff;
      text-decoration:none;
      margin-left:25px;
      font-weight:500;
      transition:0.3s;
    }

    nav a:hover{
      color:#fca311;
    }

    .hero{
      height:90vh;
      background:
      linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
      url('https://images.unsplash.com/photo-1474487548417-781cb71495f3?q=80&w=1600&auto=format&fit=crop');
      background-size:cover;
      background-position:center;
      display:flex;
      align-items:center;
      padding:0 8%;
      color:white;
    }

    .hero-content{
      max-width:650px;
    }

    .hero h1{
      font-size:58px;
      line-height:1.1;
      margin-bottom:20px;
    }

    .hero p{
      font-size:18px;
      margin-bottom:35px;
      color:#ddd;
    }

    .btn{
      display:inline-block;
      padding:14px 30px;
      background:#fca311;
      color:#fff;
      text-decoration:none;
      border-radius:5px;
      margin-right:15px;
      transition:0.3s;
      font-weight:600;
    }

    .btn:hover{
      background:#ff8800;
      transform:translateY(-3px);
    }

    .section{
      padding:90px 8%;
    }

    .section-title{
      text-align:center;
      margin-bottom:60px;
    }

    .section-title h2{
      font-size:40px;
      color:#0d1b2a;
      margin-bottom:10px;
    }

    .section-title p{
      color:#666;
    }

    .about{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:50px;
      align-items:center;
    }

    .about img{
      width:100%;
      border-radius:12px;
    }

    .about-text h3{
      font-size:32px;
      margin-bottom:20px;
      color:#0d1b2a;
    }

    .services-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:30px;
    }

    .service-card{
      background:white;
      padding:35px;
      border-radius:12px;
      box-shadow:0 5px 15px rgba(0,0,0,0.08);
      transition:0.3s;
    }

    .service-card:hover{
      transform:translateY(-8px);
    }

    .service-card h3{
      margin-bottom:15px;
      color:#0d1b2a;
    }

    .stats{
      background:#0d1b2a;
      color:white;
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
      text-align:center;
      gap:30px;
    }

    .stat-box h2{
      font-size:45px;
      color:#fca311;
    }

    .projects{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
      gap:25px;
    }

    .projects img{
      width:100%;
      height:250px;
      object-fit:cover;
      border-radius:12px;
    }

    .cta{
      background:#fca311;
      color:white;
      text-align:center;
      padding:80px 8%;
    }

    .cta h2{
      font-size:42px;
      margin-bottom:20px;
    }

    footer{
      background:#0d1b2a;
      color:white;
      padding:40px 8%;
      text-align:center;
    }

    footer p{
      margin:10px 0;
    }

    @media(max-width:900px){

      .hero h1{
        font-size:42px;
      }

      .about{
        grid-template-columns:1fr;
      }

      nav{
        display:none;
      }

    }

  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <div class="logo">Ubuntu <span>Rail</span></div>

    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Services</a>
      <a href="#">Projects</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-content">
      <h1>Reliable Railway Construction & Infrastructure Solutions</h1>

      <p>
        Ubuntu Rail Solutions specializes in railway maintenance,
        civil works, infrastructure support, and construction services
        across South Africa.
      </p>

      <a href="#" class="btn">Request a Quote</a>
      <a href="#" class="btn">Our Services</a>
    </div>
  </section>

  <!-- STATS -->
  <section class="section stats">

    <div class="stat-box">
      <h2>13+</h2>
      <p>Years Experience</p>
    </div>

    <div class="stat-box">
      <h2>18</h2>
      <p>Employees Supported</p>
    </div>

    <div class="stat-box">
      <h2>100%</h2>
      <p>Safety Focused</p>
    </div>

    <div class="stat-box">
      <h2>SA</h2>
      <p>Nationwide Service</p>
    </div>

  </section>

  <!-- ABOUT -->
  <section class="section">

    <div class="section-title">
      <h2>About Us</h2>
      <p>Professional railway construction and maintenance specialists</p>
    </div>

    <div class="about">

      <img src="https://images.unsplash.com/photo-1519003722824-194d4455a60c?q=80&w=1400&auto=format&fit=crop" alt="Railway">

      <div class="about-text">
        <h3>Building Reliable Rail Infrastructure</h3>

        <p>
          Ubuntu Rail Solutions is a proudly South African company
          specializing in railway construction, maintenance, and
          infrastructure support services.
        </p>

        <br>

        <p>
          We combine technical expertise, safety compliance,
          and reliable project delivery to support rail
          operations and infrastructure development.
        </p>

      </div>

    </div>

  </section>

  <!-- SERVICES -->
  <section class="section">

    <div class="section-title">
      <h2>Our Services</h2>
      <p>Reliable and professional railway support solutions</p>
    </div>

    <div class="services-grid">

      <div class="service-card">
        <h3>Railway Maintenance</h3>
        <p>Track inspections, repairs, and maintenance support services.</p>
      </div>

      <div class="service-card">
        <h3>Sleeper Replacement</h3>
        <p>Professional sleeper replacement and railway track upgrades.</p>
      </div>

      <div class="service-card">
        <h3>Civil Works</h3>
        <p>Drainage systems, retaining walls, gabions, and site works.</p>
      </div>

      <div class="service-card">
        <h3>Infrastructure Support</h3>
        <p>Railway infrastructure development and project support services.</p>
      </div>

    </div>

  </section>

  <!-- PROJECTS -->
  <section class="section">

    <div class="section-title">
      <h2>Our Projects</h2>
      <p>Delivering quality railway infrastructure solutions</p>
    </div>

    <div class="projects">

      <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1400&auto=format&fit=crop">

      <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?q=80&w=1400&auto=format&fit=crop">

      <img src="https://images.unsplash.com/photo-1500534314209-a25ddb2bd429?q=80&w=1400&auto=format&fit=crop">

    </div>

  </section>

  <!-- CTA -->
  <section class="cta">

    <h2>Looking For Reliable Railway Infrastructure Support?</h2>

    <p>Partner with Ubuntu Rail Solutions for professional railway services.</p>

    <br>

    <a href="#" class="btn">Contact Us Today</a>

  </section>

  <!-- FOOTER -->
  <footer>

    <h2>Ubuntu Rail Solutions</h2>

    <p>Railway Construction & Maintenance Specialists</p>

    <p>083 702 9417 | 063 366 0607</p>

    <p>info@ubunturail.co.za</p>

    <p>© 2026 Ubuntu Rail Solutions. All Rights Reserved.</p>

  </footer>

</body>
</html>
