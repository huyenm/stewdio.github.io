<!DOCTYPE html>
<html>

<head>
    <meta http-equiv="Content-type" content="text/html; charset=UTF-8" />
    <meta name="viewport" content="width=deivece-width, initial-scale=1.0" />
    <title>Stewdio</title>
    <link rel="stylesheet" href="css/homepage.css" type="text/css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/f7b042f927.js" crossorigin="anonymous"></script>
</head>

<body>
    <section class="header">
        <nav>
            <a href="#"><img src="img/logo2 (2).png"></a>
            <div class="nav-links" id="navLinks">
                <i class="fas fa-times" onclick="hideMenu()"></i>
                </i>
                <ul>
                    <li><a href="#">home</a></li>
                    <li><a href="about.html">about</a></li>
                    <li><a href="service.html">services</a></li>
                    <li><a href="blog.html">blog</a></li>
                    <li><a href="contact.html">contact</a></li>
                </ul>
            </div>
            <i class="fas fa-bars" onclick="showMenu()"></i>
        </nav>

        <div class="text-box">
            <h1><b>Stewdio is a Brisbane-based full-service design studio that creates a cool and fun experience for
                    small passionate businesses with big dreams.</h1>
            <a href="about.html" class="hero-btn">About Us</a>
        </div>
    </section>

    <!--services-->
    <section class="service">
        <h2>Our Services</h2>

        <div class="row">
            <div class="service-col">
                <h3>Branding
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus
                        tenetur accusamus vero, quos ipsa porro quis voluptate accusantium, velit, in rerum reiciendis
                        vitae! Deserunt voluptatum, eos eaque earum non libero!</p>
                </h3>
            </div>

            <div class="service-col">
                <h3>Digital Solutions
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus
                        tenetur accusamus vero, quos ipsa porro quis voluptate accusantium, velit, in rerum reiciendis
                        vitae! Deserunt voluptatum, eos eaque earum non libero!</p>
                </h3>
            </div>

            <div class="service-col">
                <h3>Graphic Design
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus
                        tenetur accusamus vero, quos ipsa porro quis voluptate accusantium, velit, in rerum reiciendis
                        vitae! Deserunt voluptatum, eos eaque earum non libero!</p>
                </h3>
            </div>
        </div>
        <a href="service.html" class="hero-btn">click to view more</a>
    </section>

    <!--portfolio-->
    <section class="portfolio">
        <h2> Our Work</h2>

        <div class="row">
            <div class="portfolio-col">
                <img src="img/card1.jpg">
                <div class="layer">
                    <h3>Branding Identity</h3>
                </div>
            </div>

            <div class="portfolio-col">
                <img src="img/wallposter.jpg">
                <div class="layer">
                    <h3>Collateral</h3>
                </div>
            </div>

            <div class="portfolio-col">
                <img src="img/socialmedia2.jpg">
                <div class="layer">
                    <h3>Templates</h3>
                </div>
            </div>
        </div>

    </section>

    <!---blog-->

    <section class="blog">
        <h2>Our Blog</h2>

        <div class="row">
            <div class="blog-col">
                <img src="img/smartcity.jpg">
                <a href="blog.html" class="blog-title">Introduction to HTML/CSS</a>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid a in accusantium molestiae, omnis,
                    sit, itaque expedita repellat labore illo est? Velit magnam
                    quisquam eum voluptatum reiciendis minus eos magni.
                </p>
            </div>

            <div class="blog-col">
                <img src="img/smartcity.jpg">
                <a href="blog.html" class="blog-title">Introduction to HTML/CSS</a>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid a in accusantium molestiae, omnis,
                    sit, itaque expedita repellat labore illo est? Velit magnam
                    quisquam eum voluptatum reiciendis minus eos magni.
                </p>
            </div>

            <div class="blog-col">
                <img src="img/smartcity.jpg">
                <a href="blog.html" class="blog-title">Introduction to HTML/CSS</a>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid a in accusantium molestiae, omnis,
                    sit, itaque expedita repellat labore illo est? Velit magnam
                    quisquam eum voluptatum reiciendis minus eos magni.
                </p>
            </div>
        </div>
        <a href="" class="hero-btn">click to view more</a>
    </section>

    <!---about-->
    <section class="about">
        <h2> Who We Are</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid a in accusantium molestiae, omnis, sit,
            itaque expedita repellat labore illo est? Velit magnam
            quisquam eum voluptatum reiciendis minus eos magni.
        </p>

        </div>

        <div class="about-col">
            <img src="img/Team.png">

        </div>
        <a href="" class="hero-btn">work with us</a>

    </section>

    <!---call to action-->
    <section class="cta">
        <h2> Want to chat further about the studio or <br>the services we offer?</h2>
        <a href="" class="hero-btn pink-btn"> contact us</a>
    </section>


    <!--toggle menu-->
    <script>
        var navLinks = document.getElementById("navLinks");

        function showMenu() {
            navLinks.style.right = "0";
        }
        function hideMenu() {
            navLinks.style.right = "-200px";
        }
    </script>

</body>

<!--footer-->


<footer>
    <div class="container">
        <div class="social-icons-container">
            <a href=""><img src="img/facebook.svg" class="social-icon" alt="Facebook.icon" /></a>
            <a href=""><img src="img/pinterest.svg" class="social-icon" alt="Pinterest.icon" /></a>
            <a href="https://www.instagram.com/stewdiodesign_/"><img src="img/instagram.svg" class="social-icon"
                    alt="Instagram.icon" /></a>
            <p>designed with love by Minh Huyen<br> illustrated by Miri Park
            </p>
        </div>
    </div>
</footer>

</html>
