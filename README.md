<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | CV</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="header-content">
            <img src="your-photo.jpg" alt="Your Photo" class="profile-photo">
            <div>
                <h1>Your Name</h1>
                <h2>Professional Title</h2>
            </div>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Me</h2>
        <img src="about-photo.jpg" alt="About Me" class="section-photo">
        <p>Write a brief introduction about yourself here.</p>
    </section>
    
    <section id="experience">
        <h2>Experience</h2>
        <ul>
            <li>Job Title - Company Name (Year - Year)</li>
            <li>Job Title - Company Name (Year - Year)</li>
            <!-- Add more items if needed -->
        </ul>
    </section>
    
    <section id="education">
        <h2>Education</h2>
        <ul>
            <li>Degree - Institution Name (Year - Year)</li>
            <li>Degree - Institution Name (Year - Year)</li>
            <!-- Add more items if needed -->
        </ul>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <div class="skill-bar">
            <div class="skill-bar-inner" data-percentage="80%"></div>
        </div>
        <div class="skill-bar">
            <div class="skill-bar-inner" data-percentage="70%"></div>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
        <p>Phone: (123) 456-7890</p>
        <!-- Add more contact details if needed -->
        <button id="contact-modal-btn">Contact Me</button>
    </section>
    
    <section id="testimonials" class="testimonials">
        <h2>Testimonials</h2>
        <div class="testimonial active">
            <p>"John is a highly skilled and dedicated professional."</p>
            <p>- Jane Doe</p>
        </div>
        <div class="testimonial">
            <p>"His work ethic and attention to detail are unmatched."</p>
            <p>- Richard Roe</p>
        </div>
    </section>
    
    <div id="contact-modal" class="modal">
        <div class="modal-content">
            <span class="close-btn">&times;</span>
            <h2>Contact Information</h2>
            <p>Email: your.email@example.com</p>
            <p>Phone: (123) 456-7890</p>
            <!-- Add more contact details if needed -->
        </div>
    </div>
    
    <footer>
        <p>&copy; 2025 Your Name</p>
    </footer>

    <div class="blank-space"></div>
    
    <script src="script.js"></script>
</body>
</html>
