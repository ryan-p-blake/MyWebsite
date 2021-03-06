<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Ryan Blake Personal Website</title>
    <meta name="description" content="The HTML5 Herald">
    <meta name="author" content="SitePoint">

    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.7.1/p5.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.7.1/addons/p5.dom.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.7.1/addons/p5.sound.min.js"></script>
    <script src="target.js"></script>
    <script src="pellet.js"></script>
    <script src="ship.js"></script>
    <script src="sketch.js"></script>


</head>


<link rel="stylesheet" href="style.css">

<header class="index">
    <nav>

        <div class="row">

            <img src="resources/img/logo.png" alt="logo" class="logo-black">
            <ul class="main-nav js--main-nav">
                <li><a href="resume.html">Resume</a></li>
                <li><a href="aboutme.html">About Me</a></li>
            </ul>
            <a class="mobile-nav-icon js--nav-icon"><i class="ion-navicon-round"></i></a>
        </div>
    </nav>
    
    <div class="hero-text-box">
        <h1>I'm Ryan Blake</h1>
    </div>

</header>

<body>
    <section class="section-steps" id="works">
        <div class="row">
            <h2>Projects</h2>
        </div>
        <div class="row">
            <div class="col span-1-of-2 steps-box">
                
                
                <div class="works-step clearfix">
                    <h3>Arduino Bluetooth Project</h3>
                    <p>
                        I have experience working with the Arduino microcontroller. My favorite project pertaining to this is an app that allowed me to remotely turn on and off christmas lights. To do this I wired a relay and bluetooth controller to an Arduino and created a basic android app to communicate with the setup.<br><br> I overcame many challenges and learned throughout this process, especially in regard to getting the bluetooth controller and my app to properly communicate. I did this by referencing both bluetooth projects created by other makers, and reading the specification sheets for the controller. Armed with more information I was able to configure the ports properly and solve the largest Christmas crisis of our century, having to get up to turn on and off Christmas lights each day. <br><br>
                    </p>
                </div>

                <img src="img/arduino-img.jpg" class="img">

                <div class="works-step clearfix">
                    <h3>Sludge Project</h3>
                    <p>

                        <br><br>
                        I worked in a physical science class on a project where we had to separate and identify all of the components in an unknown mixture. In this I worked with a small team to test, record, and separate each of the “sludged” components. <br><br>In this, we worked on a detailed analysis including validation and ample troubleshooting.One of the challenges we faced in this project was classifying a piece of PVC piping floating in the mixture. Our teacher enjoyed adding unusual items to the mixtures and ours was no exception. The challenge came from how most of the tests we were using were intended to work on substances like alcohols and elements, not PVC. <br><br>We ended up creating our own verification processes by testing how a piece of PVC reacted under different conditions and comparing it to our sample. We were presented with the problem of scientifically classifying piping and were able to do so by using what we had learned from classifying elements.<br><br>
                    </p>
                    <img src="img/beaker.jpg" class="img-2">

                </div>
                <div class="works-step clearfix">
                    <h3>P5.js Space Invaders</h3>
                    <p>
                        P5.js is an open source platform for interactive, graphical experiences. Essentially, it is a library that allows you to draw shapes to a window and easily process user input. I have used this library to code a version of Space Invaders!
                        <br><br>
                        For this project I took an object oriented approach. This involved setting up classes for the aliens and ships. I took a bottom-up approach, coding each of the base classes, then adding features and game logic. Aptly titled Not Space Invaders, the final product came out as follows.

                        
                        <br><br>
                    </p>
                    <p class="shooter"><br>
                    Use the Arrow Keys to move left and right, spacebar to shoot. <br> Shoot all the ships to win! If you get overwhelmed by alien circles you will lose. 
                    </p>
                    <iframe style="width: 640px; height:360px;overflow:hidden;" scrolling="no" frameborder="o" src="https://editor.p5js.org/rblake3244/embed/jPBrmlOm" class="iframe"></iframe>
                </div>

            </div>
        </div>
    </section>
</body>
<footer>
    <div class="row">
        <div class="col span-1-of-2">
            <ul class="footer-nav">
                <li><a href="index.html">Home</a></li>
                <li><a href="resume.html">Resume</a></li>
                <li><a href="aboutme.html">About Me</a></li>
                <li><a href="index.html">Projects</a></li>

            </ul>
        </div>
        <div class="col span-1-of-2">

        </div>
    </div>
    <div class="row">
        <p class="footer-p">
            I designed this website using HTML and CSS
        </p>
    </div>
</footer></html>
