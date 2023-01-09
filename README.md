<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/093223be76.js" crossorigin="anonymous"></script>
</head>
<body>
<div id="header">
    <div class="container">
        <nav>
            <img src="images/logo3.png" class="logo">
            <ul id="sidemenu">
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
                <i class="fa-solid fa-bars-staggered" onclick="closemenu()"></i>
            </ul>
            <i class="fa-solid fa-bars" onclick="openmenu()"></i>
        </nav>
        <div class="header-text">
            <p>Data Analyst</p>
            <h1>Hello! I'm <span>Jibril</span><br> and welcome to my website portfolio!</h1>
        </div>
    </div>
</div>
<!-- -------------About------------- -->
<div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="images/profile Jibril.png">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>Hi there! My name is Muhammad Jibril Handoyo and I am a beginner data analyst with a passion for turning data into actionable insights. 
                I recently graduated with a Bachelor's degree in Science Chemistry and have been honing my skills in data analysis through various projects and internships. 
                I am skilled in tools such as Jupyter Notebook, SQL, and Python, and have a strong understanding of statistical analysis and data visualization. 
                In my previous roles, I have helped organizations make data-driven decisions through the creation of reports and dashboards. 
                I am excited to continue growing and learning in the field of data analysis and to help organizations make informed, strategic decisions.
                </p>
                <div class="tab-titles">
                    <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                    <!-- <p class="tab-links" onclick="opentab('experience')">Experience</p> -->
                    <p class="tab-links" onclick="opentab('education')">Education</p>
                </div>
                <div class="tab-contents active-tab" id="skills">
                    <ul>
                        <li><span>Statistical Analysis</span><br>Statistical techniques to analyze data and identify trends and patterns.</li>
                        <li><span>Data Visualization</span><br>Create charts, graphs, and other visualizations to help explain data findings and conclusions.</li>
                        <li><span>Data Storytelling</span><br>Communicate data findings effectively to a non-technical audience.</li>
                        <li><span>Data Management</span><br>Organize and manage large datasets and to extract and manipulate data as needed.</li>
                    </ul>
                </div>
                <!-- <div class="tab-contents" id="experience">
                    <ul>
                        <li><span>2022</span><br>Data Analyst Bootcamp at Practicum Indonesia</li>
                        <li><span>2017</span><br>B.Sc from UIN Sunan Gunung Djati Bandung</li>
                        <li><span>Web Designer</span><br>Create and code internet sites and web pages</li>
                    </ul>
                </div> -->
                <div class="tab-contents" id="education">
                    <ul>
                        <li><span>2022 - 2023</span><br>Data Analyst Bootcamp at Practicum Indonesia.</li>
                        <li><span>2017 - 2022</span><br>B.Sc from UIN Sunan Gunung Djati Bandung.</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- -------------services------------- -->
<div id="services">
    <div class="container">
        <h1 class="sub-title">My Services</h1>
        <div class="services-list">
            <div>
                <i class="fa-sharp fa-solid fa-magnifying-glass-chart"></i>
                <h2>Data Analyst</h2>
                <p>Analyze and interpret data for clients, using tools such as Jupyter Notebook, SQL, and Python.</p>
                <!-- <a href="#">Learn more</a> -->
            </div>
            <div>
                <i class="fa-solid fa-mobile-screen-button"></i>
                <h2>Data Visualization</h2>
                <p>Create charts, graphs, and other visualizations to help clients understand and interpret their data.</p>
                <!-- <a href="#">Learn more</a> -->
            </div>
            <div>
                <i class="fa-solid fa-code"></i>
                <h2>Data Cleaning and Preparation</h2>
                <p>Help clients prepare their data for analysis by cleaning it and removing any errors or inconsistencies.</p>
                <!-- <a href="#">Learn more</a> -->
            </div>
            <div>
                <i class="fa-regular fa-comment"></i>
                <h2>Data Consulting</h2>
                <p>Provide advice and guidance to clients on how to collect, organize, and analyze their data to meet their business needs.</p>
                <!-- <a href="#">Learn more</a> -->
            </div>
        </div>
    </div>
</div>
<!-- -------------portfolio------------- -->
<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3>Social Media App</h3>
                    <p>Blabalbaablablabla</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3> Music App</h3>
                    <p>Blabalbaablablabla</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3>Online Shopping App</h3>
                    <p>Blabalbaablablabla</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
    <a href="#" class="btn">See more</a>
    </div>
</div>
<!-- -------------Contact------------- -->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-tittle">Contact Me</h1>
                <p><i class="fa-solid fa-paper-plane"></i> jibrilhandoyo@gmail.com</p>
                <p><i class="fa-solid fa-mobile"></i> 081912346572</p>
                <div class="social-icons">
                    <a href="https://www.facebook.com/jibril.handoyo/"><i class="fa-brands fa-facebook"></i></a>
                    <a href="https://twitter.com/JibrilHandoyo"><i class="fa-brands fa-twitter-square"></i></a>
                    <a href="https://www.instagram.com/jibril.han/"><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://www.linkedin.com/in/mjibrilhandoyo/"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="https://github.com/ShirotaT/"><i class="fa-brands fa-github"></i></a>
                </div>
                <a href="images/my-cv.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your email" pattern="[A-Za-z\._\-0-9]*[@][A-Za-z]*[\.][a-z]{2,4}$" required required>
                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright © 2023 Muhammad Jibril H. All Rights Reserved</p>
    </div>
</div>







<script>

    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");
    
    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link")
        document.getElementById(tabname).classList.add("active-tab")
    }
</script>

<script>
    var sidemenu = document.getElementById("sidemenu");
    function openmenu(){
        sidemenu.style.right = "0";
    }
    function closemenu(){
        sidemenu.style.right = "-200px";
    }
</script>

<script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbyfk_WJ4kiVF3sP_tU7u5g9LJabgSe7WIDv3oaRKjBgW1T_DXUdQ0UsmxwUWOQPQy31/exec'
    const form = document.forms['submit-to-google-sheet']
    const msg = document.getElementById("msg")
    form.addEventListener('submit', e => {
        e.preventDefault()
        fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML = "Message sent successfully"
            setTimeout(function(){
                msg.innerHTML = ""
            }, 5000)
            form.reset()
        })
        .catch(error => console.error('Error!', error.message))
    })
</script>
</body>
</html>
