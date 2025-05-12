# Portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VyasPortfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
   

</head>
<body>
    <div class="container">
        <!-- Background Video -->
        <video class="back-vid" loop autoplay muted playsinline
             src="videos/galaxy.mp4" type="video/mp4">
        </video>

        <!-- Header Section -->
        <header>
            <div class="left">
                <img src="images/photo-11.jpg" alt="logo">
                <h1><span style="color: #00ff00;">Prot</span>Folio</h1>
            </div>

            <!-- Navigation Links -->
            <ul>
             <li> <a href="#home">Home</a></li>
             <li>  <a href="#about">About</a></li>
              <li>   <a href="#skills">Skills</a></li>
             <li> <a href="#projects">Projects</a></li>
            <li> <a href="#contact">Contact</a></li>
            </ul>

            <!-- Social Icons -->
            <div class="box-icons">
            
                <a href="https://www.linkedin.com/in/mahimaluru-sathish-chandra-vyas-835656316?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app " target="_blank">
                    <i class='bx bxl-linkedin'></i>
                </a>
            
                <a href="https://www.instagram.com/invites/contact/?igsh=1c67hhcqicn24&utm_content=w25gkac"><i class='bx bxl-instagram'></i></a>
                <a href="https://x.com/vyas03977689286?t=rbxUrAvA_vVeScKg3XE1CA&s=08"><i class='bx bxl-twitter'></i></a>
                <a href="https://www.facebook.com/share/16G9wkU8fH/"><i class='bx bxl-facebook'></i></a>
            </div>
        </header>

        <div class="blackhole-box">
            <video loop autoplay muted playsinline>
                <source src="videos/blackhole.mp4" type="video/mp4">
            </video>
        </div>

        <!-- Hero Section -->
        <section class="hero" id="home" >
            <div class="hero-info autoBlur">
                <div class="hero-info-title"> <!-- Corrected class name -->
                    <i class='bx bxl-sketch'></i> Java Full Stack Developer
                </div>
                <h1> <span class="gradient" >SathishCha</span>ndraVyas</h1>
                <p>I Am a skilled Java Full Stack Developer with knowledge of HTML, CSS, JavaScript, Core Java, Advanced Java, JDBC, MySQL. I can develop both frontend and backend applications, build user-friendly interfaces, and write efficient backend code. Passionate about learning new technologies and solving real-world problems.</p>
                <button onclick="document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });">
                    <i class='bx bx-send'></i> Contact Me
                  </button>
                  
            </div>
            <div class="hero-vid-box">
                <video class="hero-video" loop muted autoplay playsinline>
                    <source src="videos/hero-video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
            
            <div class="scroll-down"></div>
        </section>
        <section class="info-section" id="about">
            <h1 class="section-title autoDisplay"><span class="gradient"> My Hello,</span>There👋</h1>
          
            <div class="info-cards">
                  <img src="images/grid1.png" alt="card-image">
                  <div>
                      <h1>Hi there, I’m Sathish</h1>
                      <p>
                        I Am a passionate Java Full Stack Developer with expertise in building scalable, secure, and user-friendly web applications. Skilled in Java, Spring Boot, Hibernate, REST APIs, React, JavaScript, HTML, CSS, and MySQL, I develop end-to-end solutions with clean, efficient code. I enjoy solving complex problems, collaborating in Agile teams, and continuously learning new technologies to deliver high-quality software. I am committed to creating impactful solutions that meet both user and business needs.
                  </div>
            </div>
          </section>
          
        </section>
        <section class="My-Projects" id="projects">
            <h1 class="Section-title autoDisplay" >MY<span class="gradient"> PROJECTS</span>💻</h1>
        
              <div class="project-card">
                <div class="project-vidbox autoBlur">
                    <video src="videos/Business Analysis Presentation.mp4"></video>
                </div>
                <div class="project-info fadeInRight">
                    <h1> <span class="gradient" >Expenses</span>Tracker</h1>
                    <p>An Expense Tracker is a simple tool to record, manage, and categorize daily expenses. It helps users monitor spending, control budgets, and achieve financial goals with better money management.</p>
            
                </div>
              </div>
              <div class="project-card">
                <div class="project-vidbox">
                    <video src="videos/banking1.mp4" controls autoplay></video>
                </div>
                <div class="project-info fadeInRight">
                    <h1> <span class="gradient" >Banking</span>Applicayion</h1>
                    <p>Banking management systems are crucial for efficient operations, managing customer accounts, loans, and transactions. They ensure security, accuracy, and regulatory compliance. These systems improve operational efficiency and customer satisfaction. They are vital for risk management and maintaining the bank's stability.
                    </p>
                </div>
              </div>
              <div class="project-card">
                <div class="project-vidbox autoBlur">
                    <video src="videos/port.recording.mp4"></video>
                </div>
                <div class="project-info fadeInRight">
                    <h1> <span class="gradient" >PortFolio</span>Website</h1>
                    <p>A Resume highlights your expertise, strengths, and accomplishments in a way that’s accessible to potential employers, clients, or collaborators. It typically includes sections like an about me, projects, skills, and contact information, offering a clear view of what you can offer. This is an essential tool for personal branding and career development, showcasing your talents creatively and professionally.</p>
                   
                </div>
              </div>
        </section>
        <section class="skills-section" id="skills">
            <h1 class="Section-title autoDisplay">MY<span class="gradient"> SKILLS</span>💪</h1>
            <div class="skills-box">
                <img src="images/digital brain.png" alt="skills-image" class="skills-image">
                <div class="designer autoDisplay">
                    <h1 class="gradient">Designer<i class='bx bx-laptop'></i></h1>
                    <p>Front-end developer with expertise in HTML, CSS, and JavaScript, specializing in creating responsive and visually appealing user interfaces.</p>
                </div>
            
                <div class="developer autoDisplay">
                    <h1 class="gradient">Developer💻</h1>
                    <p>Full-stack development knowledge with backend integration, databases, and RESTful APIs to create complete web applications.</p>
                </div>
                <div class=" slider" reverse="true" style="--width:100px; --height:100px ;--quantiry:9;">
                    <div class="list">
                        <div class="item" style="--position:1"><img src="images/java.io1.svg" alt="slider-image"></div>
                        <div class="item" style="--position:2"><img src="images/1.png" alt="slider-image"></div>
                        <div class="item" style="--position:3"><img src="images/spring.1.png" alt="slider-image"></div>
                        <div class="item" style="--position:4"><img src="images/java.log.svg" alt="slider-image"></div>
                        <div class="item" style="--position:5"><img src="images/html.3.png" alt="slider-image"></div>
                        <div class="item" style="--position:6"><img src="images/6.png" alt="slider-image"></div>
                        <div class="item" style="--position:7"><img src="images/boot.1.png" alt="slider-image"></div>
                        <div class="item" style="--position:8"><img src="images/git" alt="slider-image"></div>
                        <div class="item" style="--position:9"><img src="images/java.1.png" alt="slider-image"></div>
                        <div class="item" style="--position:9"><img src="images/vs.png" alt="slider-image"></div>
                    </div>
                </div>
            </div>
        </section>
            <section class="contact-section" id="contact">
                <h1 class="section-title  autoDisplay">Let<span class="gradient">'s Talk</span>😊</h1>
                <div class="social-box autoBlur">
                    <a href="#"><i class='bx bxs-phone-call'></i>+916281433776</a>
                    <a href="#"><i class='bx bxl-gmail'></i>sathishmahimaluru7@gmail.com</a>
                    <a href="http://Wa.me/91+6281433776"><i class='bx bxl-whatsapp'></i>WhatsApp </a>
                    <div class="social-icons">
                        <a href="https://www.linkedin.com/in/mahimaluru-sathish-chandra-vyas-835656316?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class='bx bxl-linkedin'></i></a>
                        <a href="https://www.instagram.com/invites/contact/?igsh=1c67hhcqicn24&utm_content=w25gkac"><i class='bx bxl-instagram'></i></a>
                        <a href="Check out vyas (@vyas03977689286): https://x.com/vyas03977689286?t=rbxUrAvA_vVeScKg3XE1CA&s=08"><i class='bx bxl-twitter'></i></a>
                        <a href="https://www.facebook.com/share/16G9wkU8fH/"><i class='bx bxl-facebook'></i></a>
                    </div>
                    
                </div>

                    <form id="contact-form" class="contact-box autoBlur">
                        <p>Feel free to get in touch! Whether you have a project idea, a collaboration opportunity, or simply want to connect, I'm always open to discussing innovative concepts.</p>
                        <label for="subject">Subject:</label>
                        <input type="text" id="subject" name="subject" placeholder="Enter Subject" required>
                    
                        <label for="message">Message:</label>
                        <textarea id="message" name="message" rows="6" placeholder="Your Message" required></textarea>
                    
                        <button type="submit"> <i class='bx bx-send'></i> SendMessage</button>
                    </form>

            </section>  
            <footer>
           
                    <h1>Copyright @Sathish, Made With ❤️ By SathishChandraVyasCode .</h1>
            
            </footer>   
</div>
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>

<script src="script.js"></script>

</body>
</html>
