<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Linkup Educational & Travel Consult</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Montserrat:wght@700;800&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header & Navigation -->
    <header>
        <nav class="navbar">
            <div class="nav-container">
                <div class="logo">
                    <i class="fas fa-graduation-cap"></i>
                    <h1>Linkup <span>Consult</span></h1>
                </div>
                
                <ul class="nav-menu">
                    <li><a href="#home" class="nav-link active">Home</a></li>
                    <li><a href="#services" class="nav-link">Services</a></li>
                    <li><a href="#destinations" class="nav-link">Destinations</a></li>
                    <li><a href="#universities" class="nav-link">Universities</a></li>
                    <li><a href="#consultation" class="nav-link">Consultation</a></li>
                    <li><a href="#contact" class="nav-link">Contact</a></li>
                </ul>
                
                <div class="hamburger">
                    <span class="bar"></span>
                    <span class="bar"></span>
                    <span class="bar"></span>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Your Gateway to Global Education & Travel</h2>
            <p>Expert guidance for study abroad programs, travel planning, and visa assistance</p>
            <div class="hero-buttons">
                <a href="#consultation" class="btn btn-primary">Free Consultation</a>
                <a href="#services" class="btn btn-secondary">Our Services</a>
            </div>
        </div>
        <div class="hero-image">
            <div class="floating-elements">
                <div class="floating-card">
                    <i class="fas fa-plane"></i>
                    <span>Travel Planning</span>
                </div>
                <div class="floating-card">
                    <i class="fas fa-university"></i>
                    <span>University Admissions</span>
                </div>
                <div class="floating-card">
                    <i class="fas fa-file-alt"></i>
                    <span>Visa Assistance</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="section-header">
            <h2>Our Services</h2>
            <p>Comprehensive solutions for your educational and travel needs</p>
        </div>
        
        <div class="services-grid">
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-graduation-cap"></i>
                </div>
                <h3>Study Abroad Programs</h3>
                <p>Guidance for undergraduate, postgraduate, and research programs worldwide</p>
            </div>
            
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-plane-departure"></i>
                </div>
                <h3>Travel Planning</h3>
                <p>Customized travel itineraries, accommodation, and tour packages</p>
            </div>
            
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-file-contract"></i>
                </div>
                <h3>Visa Processing</h3>
                <p>End-to-end visa assistance for students, tourists, and business travelers</p>
            </div>
            
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-language"></i>
                </div>
                <h3>Language Training</h3>
                <p>IELTS, TOEFL, and other language proficiency test preparation</p>
            </div>
        </div>
    </section>

    <!-- Destinations Section -->
    <section id="destinations" class="destinations">
        <div class="section-header">
            <h2>Popular Destinations</h2>
            <p>Explore top study and travel destinations around the world</p>
        </div>
        
        <div class="destinations-grid">
            <div class="destination-card">
                <div class="destination-flag">🇺🇸</div>
                <h3>United States</h3>
                <p>Top universities and diverse cultural experiences</p>
                <a href="#" class="btn-small">Explore</a>
            </div>
            
            <div class="destination-card">
                <div class="destination-flag">🇨🇦</div>
                <h3>Canada</h3>
                <p>Quality education and post-study work opportunities</p>
                <a href="#" class="btn-small">Explore</a>
            </div>
            
            <div class="destination-card">
                <div class="destination-flag">🇬🇧</div>
                <h3>United Kingdom</h3>
                <p>World-class institutions and rich historical heritage</p>
                <a href="#" class="btn-small">Explore</a>
            </div>
            
            <div class="destination-card">
                <div class="destination-flag">🇦🇺</div>
                <h3>Australia</h3>
                <p>Innovative education and beautiful landscapes</p>
                <a href="#" class="btn-small">Explore</a>
            </div>
        </div>
    </section>

    <!-- Universities Section -->
    <section id="universities" class="universities">
        <div class="section-header">
            <h2>Partner Universities</h2>
            <p>We have partnerships with top institutions worldwide</p>
        </div>
        
        <div class="university-slider">
            <div class="slider-container">
                <div class="slider-track">
                    <div class="university-logo">Harvard University</div>
                    <div class="university-logo">Stanford University</div>
                    <div class="university-logo">MIT</div>
                    <div class="university-logo">University of Toronto</div>
                    <div class="university-logo">University of Melbourne</div>
                    <div class="university-logo">University of Oxford</div>
                    <div class="university-logo">University of Cambridge</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Consultation Form -->
    <section id="consultation" class="consultation">
        <div class="consultation-container">
            <div class="consultation-content">
                <h2>Free Consultation</h2>
                <p>Book a free 30-minute consultation with our experts</p>
                
                <form id="consultation-form">
                    <div class="form-group">
                        <input type="text" placeholder="Full Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Email Address" required>
                    </div>
                    <div class="form-group">
                        <input type="tel" placeholder="Phone Number" required>
                    </div>
                    <div class="form-group">
                        <select required>
                            <option value="">Select Service</option>
                            <option value="study">Study Abroad</option>
                            <option value="travel">Travel Planning</option>
                            <option value="visa">Visa Assistance</option>
                            <option value="language">Language Training</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <textarea placeholder="Your Message" rows="4"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Book Consultation</button>
                </form>
            </div>
            
            <div class="consultation-image">
                <div class="stats">
                    <div class="stat-item">
                        <h3>500+</h3>
                        <p>Students Placed</p>
                    </div>
                    <div class="stat-item">
                        <h3>98%</h3>
                        <p>Visa Success Rate</p>
                    </div>
                    <div class="stat-item">
                        <h3>50+</h3>
                        <p>Countries Covered</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="section-header">
            <h2>Contact Us</h2>
            <p>Get in touch with our expert consultants</p>
        </div>
        
        <div class="contact-container">
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <div>
                        <h3>Office Address</h3>
                        <p>123 Education Street, Knowledge City</p>
                    </div>
                </div>
                
                <div class="contact-item">
                    <i class="fas fa-phone"></i>
                    <div>
                        <h3>Phone Number</h3>
                        <p>+1 (555) 123-4567</p>
                    </div>
                </div>
                
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <div>
                        <h3>Email Address</h3>
                        <p>info@linkupconsult.com</p>
                    </div>
                </div>
                
                <div class="social-links">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-linkedin"></i></a>
                </div>
            </div>
            
            <div class="map-placeholder">
                <div class="map">
                    <i class="fas fa-map"></i>
                    <p>Interactive Map Location</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <div class="logo">
                    <i class="fas fa-graduation-cap"></i>
                    <h2>Linkup <span>Consult</span></h2>
                </div>
                <p>Your trusted partner for educational and travel consulting services since 2010.</p>
            </div>
            
            <div class="footer-section">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#destinations">Destinations</a></li>
                    <li><a href="#universities">Universities</a></li>
                </ul>
            </div>
            
            <div class="footer-section">
                <h3>Services</h3>
                <ul>
                    <li><a href="#">Study Abroad</a></li>
                    <li><a href="#">Travel Planning</a></li>
                    <li><a href="#">Visa Processing</a></li>
                    <li><a href="#">Language Training</a></li>
                </ul>
            </div>
            
            <div class="footer-section">
                <h3>Newsletter</h3>
                <p>Subscribe for updates and offers</p>
                <div class="newsletter">
                    <input type="email" placeholder="Your Email">
                    <button type="submit"><i class="fas fa-paper-plane"></i></button>
                </div>
            </div>
        </div>
        
        <div class="footer-bottom">
            <p>&copy; 2024 Linkup Educational & Travel Consult. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #f59e0b;
    --text-dark: #1f2937;
    --text-light: #6b7280;
    --bg-light: #f9fafb;
    --bg-white: #ffffff;
    --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
    --radius: 8px;
    --transition: all 0.3s ease;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: var(--text-dark);
    background-color: var(--bg-light);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Typography */
h1, h2, h3, h4 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    line-height: 1.2;
}

h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

p {
    color: var(--text-light);
    margin-bottom: 1rem;
}

/* Buttons */
.btn {
    display: inline-block;
    padding: 12px 32px;
    border-radius: var(--radius);
    text-decoration: none;
    font-weight: 600;
    transition: var(--transition);
    border: none;
    cursor: pointer;
    font-size: 1rem;
}

.btn-primary {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: white;
}

.btn-primary:hover {
    transform: translateY(-2px);
    box-shadow: var(--shadow-lg);
}

.btn-secondary {
    background-color: transparent;
    color: var(--primary-color);
    border: 2px solid var(--primary-color);
}

.btn-secondary:hover {
    background-color: var(--primary-color);
    color: white;
}

.btn-small {
    padding: 8px 20px;
    background-color: var(--primary-color);
    color: white;
    border-radius: var(--radius);
    text-decoration: none;
    font-size: 0.875rem;
    transition: var(--transition);
}

.btn-small:hover {
    background-color: var(--secondary-color);
}

/* Header & Navigation */
header {
    background-color: var(--bg-white);
    box-shadow: var(--shadow);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.navbar {
    padding: 1rem 0;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
}

.logo i {
    font-size: 2rem;
    color: var(--primary-color);
}

.logo h1 {
    font-size: 1.5rem;
    color: var(--text-dark);
}

.logo span {
    color: var(--primary-color);
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-link {
    text-decoration: none;
    color: var(--text-dark);
    font-weight: 500;
    transition: var(--transition);
    padding: 8px 0;
    position: relative;
}

.nav-link:hover,
.nav-link.active {
    color: var(--primary-color);
}

.nav-link.active::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background-color: var(--primary-color);
}

.hamburger {
    display: none;
    cursor: pointer;
}

.bar {
    display: block;
    width: 25px;
    height: 3px;
    margin: 5px auto;
    background-color: var(--text-dark);
    transition: var(--transition);
}

/* Hero Section */
.hero {
    padding: 120px 20px 80px;
    background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%);
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
    min-height: 90vh;
}

.hero-content h2 {
    font-size: 3rem;
    margin-bottom: 1.5rem;
    color: var(--text-dark);
}

.hero-content p {
    font-size: 1.25rem;
    margin-bottom: 2rem;
    color: var(--text-light);
}

.hero-buttons {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
}

.hero-image {
    position: relative;
    min-height: 400px;
}

.floating-elements {
    position: absolute;
    width: 100%;
    height: 100%;
}

.floating-card {
    position: absolute;
    background: var(--bg-white);
    padding: 1rem;
    border-radius: var(--radius);
    box-shadow: var(--shadow-lg);
    display: flex;
    align-items: center;
    gap: 10px;
    animation: float 3s ease-in-out infinite;
}

.floating-card:nth-child(1) {
    top: 20%;
    left: 10%;
    animation-delay: 0s;
}

.floating-card:nth-child(2) {
    top: 50%;
    right: 20%;
    animation-delay: 1s;
}

.floating-card:nth-child(3) {
    bottom: 20%;
    left: 30%;
    animation-delay: 2s;
}

.floating-card i {
    font-size: 1.5rem;
    color: var(--primary-color);
}

@keyframes float {
    0%, 100% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-10px);
    }
}

/* Services Section */
.services {
    padding: 80px 20px;
    background-color: var(--bg-white);
}

.section-header {
    text-align: center;
    max-width: 800px;
    margin: 0 auto 4rem;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.service-card {
    background: var(--bg-light);
    padding: 2rem;
    border-radius: var(--radius);
    text-align: center;
    transition: var(--transition);
    border: 1px solid #e5e7eb;
}

.service-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-lg);
}

.service-icon {
    width: 60px;
    height: 60px;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 1.5rem;
}

.service-icon i {
    font-size: 1.5rem;
    color: white;
}

.service-card h3 {
    margin-bottom: 1rem;
    color: var(--text-dark);
}

/* Destinations Section */
.destinations {
    padding: 80px 20px;
    background-color: var(--bg-light);
}

.destinations-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.destination-card {
    background: var(--bg-white);
    padding: 2rem;
    border-radius: var(--radius);
    text-align: center;
    box-shadow: var(--shadow);
    transition: var(--transition);
}

.destination-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-lg);
}

.destination-flag {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.destination-card h3 {
    margin-bottom: 1rem;
    color: var(--text-dark);
}

/* Universities Section */
.universities {
    padding: 80px 20px;
    background-color: var(--bg-white);
}

.university-slider {
    overflow: hidden;
    max-width: 1200px;
    margin: 0 auto;
}

.slider-container {
    position: relative;
    overflow: hidden;
    padding: 2rem 0;
}

.slider-track {
    display: flex;
    gap: 2rem;
    animation: slide 30s linear infinite;
}

.university-logo {
    flex: 0 0 auto;
    width: 200px;
    height: 100px;
    background: var(--bg-light);
    border-radius: var(--radius);
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 600;
    color: var(--text-dark);
    border: 1px solid #e5e7eb;
}

@keyframes slide {
    0% {
        transform: translateX(0);
    }
    100% {
        transform: translateX(calc(-200px * 7 - 2rem * 6));
    }
}

/* Consultation Section */
.consultation {
    padding: 80px 20px;
    background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%);
}

.consultation-container {
    max-width: 1200px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
}

.consultation-content h2 {
    color: var(--text-dark);
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 12px 16px;
    border: 1px solid #d1d5db;
    border-radius: var(--radius);
    font-family: 'Poppins', sans-serif;
    font-size: 1rem;
    transition: var(--transition);
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
}

.consultation-image {
    display: flex;
    justify-content: center;
    align-items: center;
}

.stats {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 2rem;
}

.stat-item {
    text-align: center;
    padding: 2rem;
    background: var(--bg-white);
    border-radius: var(--radius);
    box-shadow: var(--shadow);
}

.stat-item h3 {
    font-size: 2.5rem;
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

/* Contact Section */
.contact {
    padding: 80px 20px;
    background-color: var(--bg-white);
}

.contact-container {
    max-width: 1200px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
}

.contact-info {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.contact-item {
    display: flex;
    align-items: flex-start;
    gap: 1rem;
}

.contact-item i {
    font-size: 1.5rem;
    color: var(--primary-color);
    margin-top: 5px;
}

.contact-item h3 {
    font-size: 1.2rem;
    margin-bottom: 0.5rem;
}

.social-links {
    display: flex;
    gap: 1rem;
    margin-top: 1rem;
}

.social-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    background: var(--bg-light);
    border-radius: 50%;
    color: var(--text-dark);
    text-decoration: none;
    transition: var(--transition);
}

.social-links a:hover {
    background: var(--primary-color);
    color: white;
    transform: translateY(-3px);
}

.map-placeholder {
    background: var(--bg-light);
    border-radius: var(--radius);
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 300px;
}

.map {
    text-align: center;
    color: var(--text-light);
}

.map i {
    font-size: 4rem;
    color: var(--primary-color);
    margin-bottom: 1rem;
}

/* Footer */
footer {
    background-color: var(--text-dark);
    color: white;
    padding: 60px 20px 20px;
}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 3rem;
    margin-bottom: 3rem;
}

.footer-section .logo {
    margin-bottom: 1rem;
}

.footer-section .logo h2 {
    color: white;
}

.footer-section h3 {
    color: white;
    margin-bottom: 1.5rem;
    font-size: 1.25rem;
}

.footer-section ul {
    list-style: none;
}

.footer-section ul li {
    margin-bottom: 0.75rem;
}

.footer-section ul li a {
    color: #d1d5db;
    text-decoration: none;
    transition: var(--transition);
}

.footer-section ul li a:hover {
    color: white;
    padding-left: 5px;
}

.newsletter {
    display: flex;
    margin-top: 1rem;
}

.newsletter input {
    flex: 1;
    padding: 10px;
    border: none;
    border-radius: var(--radius) 0 0 var(--radius);
}

.newsletter button {
    background: var(--primary-color);
    color: white;
    border: none;
    padding: 0 20px;
    border-radius: 0 var(--radius) var(--radius) 0;
    cursor: pointer;
    transition: var(--transition);
}

.newsletter button:hover {
    background: var(--secondary-color);
}

.footer-bottom {
    text-align: center;
    padding-top: 2rem;
    border-top: 1px solid #374151;
    color: #9ca3af;
}

/* Responsive Design */
@media (max-width: 992px) {
    .hero {
        grid-template-columns: 1fr;
        text-align: center;
        gap: 2rem;
    }
    
    .consultation-container,
    .contact-container {
        grid-template-columns: 1fr;
        gap: 2rem;
    }
    
    h2 {
        font-size: 2rem;
    }
    
    .hero-content h2 {
        font-size: 2.5rem;
    }
}

@media (max-width: 768px) {
    .hamburger {
        display: block;
    }
    
    .hamburger.active .bar:nth-child(2) {
        opacity: 0;
    }
    
    .hamburger.active .bar:nth-child(1) {
        transform: translateY(8px) rotate(45deg);
    }
    
    .hamburger.active .bar:nth-child(3) {
        transform: translateY(-8px) rotate(-45deg);
    }
    
    .nav-menu {
        position: fixed;
        left: -100%;
        top: 70px;
        gap: 0;
        flex-direction: column;
        background-color: var(--bg-white);
        width: 100%;
        text-align: center;
        transition: 0.3s;
        box-shadow: 0 10px 27px rgba(0, 0, 0, 0.05);
        padding: 2rem 0;
    }
    
    .nav-menu.active {
        left: 0;
    }
    
    .nav-link {
        display: block;
        padding: 1rem;
    }
    
    .hero-buttons {
        justify-content: center;
    }
    
    .floating-card {
        position: relative;
        margin: 1rem auto;
        width: 80%;
        max-width: 300px;
        animation: none;
    }
    
    .floating-elements {
        position: relative;
        display: flex;
        flex-direction: column;
        gap: 1rem;
    }
}

@media (max-width: 480px) {
    .hero-content h2 {
        font-size: 2rem;
    }
    
    .btn {
        padding: 10px 24px;
        font-size: 0.9rem;
    }
    
    .services-grid,
    .destinations-grid {
        grid-template-columns: 1fr;
    }
    
    .stats {
        grid-template-columns: 1fr;
    }
}
// Mobile Navigation Toggle
const hamburger = document.querySelector('.hamburger');
const navMenu = document.querySelector('.nav-menu');

hamburger.addEventListener('click', () => {
    hamburger.classList.toggle('active');
    navMenu.classList.toggle('active');
});

// Close mobile menu when clicking a link
document.querySelectorAll('.nav-link').forEach(link => {
    link.addEventListener('click', () => {
        hamburger.classList.remove('active');
        navMenu.classList.remove('active');
    });
});

// Smooth Scrolling for Navigation Links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        if (targetId === '#') return;
        
        const targetElement = document.querySelector(targetId);
        if (targetElement) {
            window.scrollTo({
                top: targetElement.offsetTop - 80,
                behavior: 'smooth'
            });
        }
    });
});

// Form Submission
const consultationForm = document.getElementById('consultation-form');
if (consultationForm) {
    consultationForm.addEventListener('submit', function(e) {
        e.preventDefault();
        
        // Get form data
        const formData = new FormData(this);
        const data = Object.fromEntries(formData);
        
        // Here you would typically send the data to a server
        console.log('Form submitted:', data);
        
        // Show success message
        alert('Thank you! Your consultation request has been submitted. We will contact you within 24 hours.');
        
        // Reset form
        this.reset();
    });
}

// Newsletter Subscription
const newsletterForm = document.querySelector('.newsletter');
if (newsletterForm) {
    newsletterForm.addEventListener('submit', function(e) {
        e.preventDefault();
        const emailInput = this.querySelector('input[type="email"]');
        const email = emailInput.value.trim();
        
        if (email) {
            // Here you would typically send the email to your newsletter service
            console.log('Newsletter subscription:', email);
            alert('Thank you for subscribing to our newsletter!');
            emailInput.value = '';
        }
    });
}

// Active Navigation on Scroll
const sections = document.querySelectorAll('section[id]');
const navLinks = document.querySelectorAll('.nav-link');

window.addEventListener('scroll', () => {
    let current = '';
    const scrollPosition = window.scrollY + 100;
    
    sections.forEach(section => {
        const sectionTop = section.offsetTop;
        const sectionHeight = section.clientHeight;
        
        if (scrollPosition >= sectionTop && scrollPosition < sectionTop + sectionHeight) {
            current = section.getAttribute('id');
        }
    });
    
    navLinks.forEach(link => {
        link.classList.remove('active');
        if (link.getAttribute('href') === `#${current}`) {
            link.classList.add('active');
        }
    });
});

// University Slider Animation
const sliderTrack = document.querySelector('.slider-track');
if (sliderTrack) {
    // Clone the slider items for infinite scrolling effect
    const sliderItems = sliderTrack.children;
    const itemCount = sliderItems.length;
    
    // Calculate total width needed for seamless animation
    const totalWidth = (itemCount * 200) + ((itemCount - 1) * 32); // 200px width + 32px gap
    
    // Set the animation duration based on total width
    sliderTrack.style.animationDuration = `${totalWidth / 50}s`; // Adjust speed as needed
}

// Add loading animation for elements
document.addEventListener('DOMContentLoaded', () => {
    // Add fade-in animation to elements as they scroll into view
    const observerOptions = {
        threshold: 0.1,
        rootMargin: '0px 0px -50px 0px'
    };
    
    const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('animate-in');
            }
        });
    }, observerOptions);
    
    // Observe all service cards and destination cards
    document.querySelectorAll('.service-card, .destination-card').forEach(card => {
        observer.observe(card);
    });
});

// Add CSS for animations
const style = document.createElement('style');
style.textContent = `
    .service-card,
    .destination-card {
        opacity: 0;
        transform: translateY(20px);
        transition: opacity 0.6s ease, transform 0.6s ease;
    }
    
    .service-card.animate-in,
    .destination-card.animate-in {
        opacity: 1;
        transform: translateY(0);
    }
`;

document.head.appendChild(style);

// Initialize with scroll to handle initial state
window.dispatchEvent(new Event('scroll'));
