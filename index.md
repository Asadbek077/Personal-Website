<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="styles.css">
	<link rel="stylesheet" href="responsive.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css"/>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"/>

</head>
<body onload="newFunction()">
    <div id="loader">
        <div></div>
        <div></div>
        <div></div>
    </div>
    <section1 style="display:none;" id="myDiv" class="animate-bottom">
    <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">Portfolio</a></div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About</a></li>
                <li><a href="#services" class="menu-btn">Services</a></li>
                <li><a href="#skills" class="menu-btn">Skills</a></li>
                <li><a href="#teams" class="menu-btn">Works</a></li>
                <li><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>

    <!-- home section start -->
    <section class="home" id="home">
      <div class="max-width">
          <div class="row">
            <div class="home-content">
                <div class="text-1">Hello, my name is</div>
                <div class="text-2">Asad</div>
                <div class="text-3">And I'm a <span class="typing"></span></div>
                <a href="#">Hire me</a>
            </div>
          </div>
      </div>
    </section>

    <!-- about section start -->
    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About me</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="photo.jpg" alt="">
                </div>
                <div class="column right">
                    <div class="text">I'm Asad and I'm a <span class="typing-2"></span></div>
                    <p>I was born in 2001, from my childhood I was interested in Information Systems, and recently started learning Web-Development, starting from Front-End. Now I have profound knowledge about the technologies that are important for Web-sites' client side.</p>
                    <a href="Asadbek-Khojimatov(1).pdf" download="Asadbek-Khojimatov(1).pdf">Download CV</a>
                </div>
            </div>
        </div>
    </section>

    <!-- services section start -->
    <section class="services" id="services">
        <div class="max-width">
            <h2 class="title">My services</h2>
            <div class="serv-content">
                <div class="card">
                    <div class="box">
                        <i class="fas fa-paint-brush"></i>
                        <div class="text">Web Design</div>
                        <p>Design of several types of web-site through Figma, with prototyping.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <i class="fas fa-chart-line"></i>
                        <div class="text">Advertising</div>
                        <p>Advertisement of your product and services through particular platforms.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <i class="fas fa-code"></i>
                        <div class="text">Web layout</div>
                        <p>Client side of the web-site (HTML5, CSS3, JavaScript, JQuery, Bootstrap)</p>
                    </div>
                </div>
               </div>
            </div>
        </div>
    </section>

    <!-- skills section start -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">My skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My creative skills & experiences.</div>
                    <p>As I mentioned below I have some relevant skills to Front-End. And hopefully my skills will be helpful for you.</p>
                    <a href="#">Read more</a>
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>HTML</span>
                            <span>90%</span>
                        </div>
                        <div class="line html"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>CSS</span>
                            <span>80%</span>
                        </div>
                        <div class="line css"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>JavaScript</span>
                            <span>60%</span>
                        </div>
                        <div class="line js"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>JQuery</span>
                            <span>50%</span>
                        </div>
                        <div class="line jq"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Bootstrap</span>
                            <span>70%</span>
                        </div>
                        <div class="line bs"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- teams section start -->
    <section class="teams" id="teams">
        <div class="max-width">
            <h2 class="title">My recent works</h2>
            <div class="carousel owl-carousel">
                <div class="card">
                    <a href="index1.html">
                    <div class="box">
                        <img src="calculator.jpeg" alt="calculator">
                        <div class="text">Calculator</div>
                        <p>Sweet convenient calculator made with HTML, CSS, JavaScript</p>
                    </div>
                    </a>
                </div>
                <div class="card">
                    <a href="index2.html">
                    <div class="box">
                        <img src="https://e7.pngegg.com/pngimages/549/560/png-clipart-computer-icons-login-scalable-graphics-email-accountability-blue-logo-thumbnail.png" alt="login">
                        <div class="text">Login Form</div>
                        <p>Simple login form and convenient login form</p>
                    </div>
                    </a>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-4.jpeg" alt="">
                        <div class="text">Project 1</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-5.jpeg" alt="">
                        <div class="text">Project 1</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-5.jpeg" alt="">
                        <div class="text">Project 1</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-5.jpeg" alt="">
                        <div class="text">Project 1</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/profile-5.jpeg" alt="">
                        <div class="text">Project 1</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- contact section start -->
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact me</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Get in Touch</div>
                    <p>Do not hesitate to contact me, I am always available 24/7.</p>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Asad</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">Uzbekistan, Tashkent</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-phone"></i>
                            <div class="info">
                                <div class="head">Phone number:</div>
                                <div class="sub-title">+998 99 889 01 33</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">asadbekkhojimatov@gmail.com</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message me</div>
                    <form class="contact-form" action="#" method="POST">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" class="fullname" placeholder="Name">
                            </div>
                            <div class="field email">
                                <input type="text" class="email-input" placeholder="Email">
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" class="subject" placeholder="Subject">
                        </div>
                        <div class="field textarea">
                            <textarea class="message" cols="30" rows="10" placeholder="Message.."></textarea>
                        </div>
                        <div class="button-area">
                            <button class="send-msg" type="submit" name="send">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- footer section start -->
    <footer>
        <span>Created By <a href="https://www.codingnepalweb.com">Asadbek Khojimatov</a> | <span class="far fa-copyright"></span> 2021e All rights reserved.</span>
    </footer>
</section1> 
    <script src="main.js"></script>
</body>
</html>