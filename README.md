<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/23330d1986.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header"> 
        <div class="container">
            <nav>
               <img src="LOGO.png" class="logo">
                <ul>
                    <li><a href="#Home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#studentai">Student A.I</a></li>
                    
                </ul>
            </nav>
            <div id="Home" class="header-text">
                <p>FRONTEND DEVELOPER</p>
                <h1>Hi, I'm <span>Haneef Shaik</span><br>from Kakinada</h1>
            </div>
        </div>
    </div>
    
    <!-- About Section -->
   
    <div class="about" id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1"> 
                    <img src="image 21.jpg" alt="About Image">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <h6 id="pt"> I'm a passionate front-end developer with a keen eye for design and a strong foundation in creating responsive, user-friendly websites. My expertise lies in translating design concepts into functional, interactive, and accessible web pages using the latest technologies. With experience in HTML, CSS, JavaScript, and various front-end frameworks, I enjoy crafting clean and efficient code that brings ideas to life</h6>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab(event, 'Skills')">Skills</p>
                        <p class="tab-links" onclick="opentab(event, 'Languages')">Languages</p>
                        <p class="tab-links" onclick="opentab(event, 'Education')">Education</p>
                        <p class="tab-links" onclick="opentab(event, 'Experience')">Experience</p>
                    </div>
                    <div class="tab-contents active-tab" id="Skills">
                        <ul>
                            <li><span>UI/UX</span><br>Designing Web interface</li>
                            <li><span>Web Development</span><br>Web app Development</li>
                            <li><span>Editing</span><br>Posters and banners making for marketing</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="Languages">
                        <ul>
                            <li><span>Front-End</span></li>
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>JavaScript</li>
                            <li><span>Frameworks</span></li>
                            <li>React</li>
                            <li><span>Back-End</span></li>
                            <li>Python</li>
                            <li>SQL</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="Education">
                        <ul>
                            <li><span>2027</span><br>Designing Web Training</li>
                            <li><span>2025-2027</span><br>P.G from AKNU Rajahmundry</li>
                            <li><span>2022-2025</span><br>U.G from P.R Govt(A) College Kakinada.</li>
                        </ul>
                    </div> 
                    <div class="tab-contents" id="Experience">
                        <ul>
                            <li><span>2021-2022</span><br>Front-End Developer at ABC Tech Solutions, Remote<br><br>
                                Developed and maintained responsive web applications using HTML, CSS, and JavaScript, enhancing user experience and performance.
                                Collaborated with designers to implement user-friendly interfaces, resulting in a 20% increase in user engagement.
                            </li>
                            <li><span>2022-2023</span><br>Junior Front-End Developer at XYZ Web Services, Kakinada<br><br>
                                Assisted in building single-page applications (SPAs) using React, improving site functionality and load times.
                                Created reusable components and improved website responsiveness, leading to a 15% decrease in bounce rate.
                            </li>
                        </ul>
                    </div>
                </div>  
            </div>
        </div>
    </div>
    
    <!-- Services Section -->
    <div id="services">
        <div class="container">
            <h1 class="sub-title" id="My services">My Services</h1>
            <div class="services-list">
                <div class="service-item"> 
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Design</h2>
                    <p>Creating the visual layout and look of websites for an appealing user experience.</p>
                    <a href="#">Learn More</a>
                </div>
                <div class="service-item">
                    <i class="fa-solid fa-compass-drafting"></i>
                    <h2>App Design</h2>
                    <p>Designing the interface and user experience for mobile and desktop applications.</p>
                    <a href="#">Learn More</a>
                </div>
                <div class="service-item">
                    <i class="fa-brands fa-artstation"></i>
                    <h2>UI/UX Design</h2>
                    <p>UI focuses on the visual elements of an interface, while UX optimizes the overall user experience for ease and satisfaction.</p>
                    <a href="#">Learn More</a>
                </div>
            </div>
        </div>
    </div>
    
    <!-- Portfolio Section -->
    <div id="portfolio" >
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="work.jpg" alt="Work 1">
                    <div class="layer">
                        <h3>SINGLE PAGE APPLICATION</h3>
                        <p>SPAs load a single HTML page and update content dynamically, providing a faster user experience. Popular frameworks include React and Angular.</p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>  
                    </div>
                </div>
                <div class="work">
                    <img src="work2.jpg" alt="Work 2">
                    <div class="layer">
                        <h3>J.S APPLICAION</h3>
                        <p>JavaScript powers dynamic web applications, enabling interactive features on websites and server-side operations.</p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>  
                    </div>
                </div>
                <div class="work">
                    <img src="work3.jpg" alt="Work 3">
                    <div class="layer">
                        <h3>WEB APPLICAION</h3>
                        <p>Web development involves creating websites, focusing on both the front-end (user interface) and back-end (server and database) aspects.</p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>  
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See More</a>
        </div>
    </div>
    
    <!-- Contact Section -->
    <div id="contact">
        <div class="container">
            <h1 id="form">Contact Form</h1>
            <div class="row">
                <!-- Left side for contact details -->
                <div class="contact-left">
                    <div class="sub-title">
                        <h1>Contact Me</h1> 
                        <p><i class="fa-duotone fa-solid fa-paper-plane"></i>haneefshaik1144@gmail.com</p>
                        <p><i class="fa-solid fa-phone"></i>8010320018</p>
                        <div class="social-icons">
                            <a href="https://github.com/haneef008"><i class="fa-brands fa-github"></i></a>
                            <a href="https://www.linkedin.com/in/haneef-sk-58a064307?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class="fa-brands fa-linkedin"></i></a>
                            <a href=""><i class="fa-brands fa-facebook"></i></a>
                            <a href=""><i class="fa-brands fa-twitter-square"></i></a>
                        </div>
                        <a href="cv.pdf" class="btn2">Download CV</a>
                    </div>
                </div>
                <!-- Right side for the contact form -->
                <div class="contact-right">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Enter Name" required>
                        <input type="email" name="Email" placeholder="Enter email" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit">Submit</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
    <h1 id="studentai" >Student A.I</h1>
    <iframe class="stai"
    src="https://www.chatbase.co/chatbot-iframe/mDOVPPcO04FN7vY2J4avI"
    width="100%"
    style="height: 100px; min-height: 450px;width: 70%;"
    frameborder="0"
    ></iframe>
    <script>
        function opentab(event, tabname) {
            var tablinks = document.getElementsByClassName("tab-links");
            var tabcontents = document.getElementsByClassName("tab-contents");
            
            // Remove active class from all links and contents
            for (var tablink of tablinks) {
                tablink.classList.remove("active-link");
            }
            for (var tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab");
            }
            
            // Add active class to clicked link and corresponding content
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>
  <script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbwrzsMH2Ioym5FO8YpSAmOk5Wpf8uCYezQZDYQiIwRVLCSJftyq81lFUkTbzaAJuwnL/exec'
    const form = document.forms['submit-to-google-sheet']
  
    form.addEventListener('submit', e => {
        e.preventDefault()
        fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => {
                console.log('Success!', response)
                form.reset(); // This line will clear the form fields after submission
            })
            .catch(error => console.error('Error!', error.message))
    })
</script>
</div>
<div class="copyright">
    <p>copyright © Haneef.Made with <i class="fa-sharp-duotone fa-solid fa-heart"></i> by Tech Learner</p>
   </div>
   <script>
    // Menu Close Functionality
    document.getElementById('close-btn').addEventListener('click', function() {
        document.getElementById('menu').style.display = 'none';
    });

    // Menu Toggle Functionality for smaller screens
    document.getElementById('menu-btn').addEventListener('click', function() {
        const menu = document.getElementById('menu');
        if (menu.style.display === 'none' || menu.style.display === '') {
            menu.style.display = 'block';
        } else {
            menu.style.display = 'none';
        }
    });
</script>
<!--student ai-
<script>
    window.embeddedChatbotConfig = {
    chatbotId: "TQ_VVLFvm9ZGBUkf86tiL",
    domain: "www.chatbase.co"
    }
    </script>
    <script
    src="https://www.chatbase.co/embed.min.js"
    chatbotId="TQ_VVLFvm9ZGBUkf86tiL"
    domain="www.chatbase.co"
    defer>
    </script>
-->
</body>
</html>
