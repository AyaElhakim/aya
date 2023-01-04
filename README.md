<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AS CARS</title>
    <link rel="stylesheet" href="projet.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <!--Navbar-->
    <header>
        <!--Nav container-->
        <div class="nav container">
            <!--menu icon-->
            <i class='bx bx-menu' id="menu-icon"></i>
            <!--logo-->
            <a href="#" class="logo">AS.<span>Cars</span></a>
            <!--nav list-->
            <ul class="navbar">
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#cars">Cars</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#parts">Parts</a></li>
                <li><a href="#blog">Our Blog</a></li>
            </ul>
            <!--search icons-->
            <i class='bx bx-search' id="search-icon"></i>
            <!--search Box-->
            <div class="search-box container">
                <input type="search" name="" id="" placeholder="search here...">
            </div>
        </div>
    </header>
    <!--home-->
    <section class="home" id="home">
        <div class="home-text">
            <h1>We have Everything <br>Your <span>Car</span> Need ....</h1>
            <p>Dear customers welcome.</p>
      <!--home button-->
      <a href="#" class="btn">Discover Now</a>
        </div>
    </section>
    <!--car sections-->
    <section class="cars" id="cars">
        <div class="heading">
            <span>ALL Cars</span>
            <h2>We have all types Cars</h2>
            <p> Dear driver just choose the desired car and we will do the rest.</p>
        </div>
        <!--cars container-->
        <div class="cars-container container">
            <!--box 1-->
            <div class="box">
                <img src="1.jpeg" alt="">
                <h2>porche Car</h2>
            </div>
            <!--box 2-->
            <div class="box">
                <img src="2.jpeg" alt="">
                <h2>porche Car</h2>
            </div>
            <!--box 3-->
            <div class="box">
                <img src="3.jpeg" alt="">
                <h2>porche Car</h2>
            </div>
            <!--box 4-->
            <div class="box">
                <img src="4.jpeg" alt="">
                <h2>porche Car</h2>
            </div>
            <!--box 5-->
            <div class="box">
                <img src="5.jpeg" alt="">
                <h2>porche Car</h2>
            </div>
            <!--box 6-->
            <div class="box">
                <img src="6.jpeg" alt="">
                <h2>porche Car</h2>
            </div>
            
        </div>
    </section>
    <!--ABOUT-->
    <section class="about container" id="about"></section>
    <!--link to js-->
    <script src="projet.js"></script>

</body>
</html>
