<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Innovative IT Solutions for Your Business">
    <meta name="author" content="RaysunTech Solutions">
    <meta name="keywords" content="IT solutions, web design, cloud services, IT consulting">
    <meta name="theme-color" content="#4682b4">
    <title>Raysun Tech - IT Services</title>
    <link rel="favicon.ico" type="image/x-icon" href="favicon.ico">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    <link rel="stylesheet" href="styles.css">
    <style>
        :root {
            --primary-color: #4682b4;
            --secondary-color: #66a188;
            --text-color: #333;
            --light-bg: #f0f8ff;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--light-bg);
            line-height: 1.6;
        }

        /* Navigation styles */
        .navbar {
            background-color: rgba(255, 255, 255, 0.95);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 1rem 0;
        }

        /* Hero section styles */
        .hero-section {
            background: linear-gradient(rgba(70, 130, 180, 0.8), rgba(70, 130, 180, 0.9)),
                        url('hero-bg.jpg') center/cover;
            padding: 150px 0;
            color: white;
        }

        .hero-section h1 {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
            animation: fadeInUp 1s ease;
        }

        /* Services section styles */
        .services-section .col-md-4 {
            transition: transform 0.3s ease;
            padding: 2rem;
        }

        .services-section .col-md-4:hover {
            transform: translateY(-10px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        /* Testimonials styles */
        .testimonials-section {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
        }

        .testimonial-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            margin: 1rem;
        }

        /* Button styles */
        .btn {
            padding: 0.8rem 2rem;
            border-radius: 30px;
            text-transform: uppercase;
            font-weight: 500;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background-color: var(--primary-color);
            border: none;
        }

        .btn-primary:hover {
            background-color: darken(var(--primary-color), 10%);
            transform: translateY(-2px);
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive images */
        .img-fluid {
            transition: transform 0.3s ease;
        }

        .img-fluid:hover {
            transform: scale(1.05);
        }

        /* Footer enhancements */
        .footer-section {
            background: linear-gradient(45deg, #333 0%, #222 100%);
        }

        .social-links a {
            transition: color 0.3s ease;
        }

        .social-links a:hover {
            color: var(--primary-color) !important;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <img src="logo.png" alt="RaysunTech Logo" height="40">
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Page -->
    <header class="hero-section">
        <div class="container text-center">
            <h1>Innovative IT Solutions for Your Business</h1>
            <p>Providing top-notch web design, cloud services, and IT consulting.</p>
            <a href="tel:+0728964904" class="btn btn-primary">Contact Us</a>
            <a href="mailto:raysuntech@gmail.com" class="btn btn-secondary">Get a Quote</a>
        </div>
    </header>

    <section id="services" class="services-section py-5">
        <div class="container">
            <h2 class="text-center">Our Services</h2>
            <div class="row">
                <div class="col-md-4 text-center">
                    <i class="fas fa-laptop-code fa-3x"></i>
                    <h3>Web Design and Development</h3>
                    <p>Creating stunning and responsive websites tailored to your business needs.</p>
                    
                </div>
                <div class="col-md-4 text-center">
                    <i class="fas fa-cloud fa-3x"></i>
                    <h3>Cloud Services</h3>
                    <p>Offering scalable and secure cloud solutions on AWS, Azure, and Google Cloud.</p>
                </div>
                <div class="col-md-4 text-center">
                    <i class="fas fa-cogs fa-3x"></i>
                    <h3>IT Consulting</h3>
                    <p>Providing expert IT consulting to optimize your business operations.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="testimonials" class="testimonials-section py-5 bg-light">
        <div class="container">
            <h2 class="text-center">What Our Clients Say</h2>
            <div class="row">
                <div class="col-md-4 text-center testimonial-card">
                    <p>"Raysun Tech transformed our online presence with a stunning website."</p>
                    <p>- Jiresse Mungaza</p><br>
                    <a href="http://powerfumigationsa.co.za" target="_blank">powerfumigationsa.co.za</a> 
                </div>
                <div class="col-md-4 text-center testimonial-card">
                    <p>"Excellent IT consulting services that helped us streamline our operations."</p>
                    <p>- Nosipho</p><br>
                    <a href="http://numberonebuilds.co.za" target="_blank">numberonebuilds.co.za</a>
                </div>
            </div>
        </div>
    </section>

    <!-- About Page -->
    <section id="about" class="about-section py-5">
        <div class="container">
            <h2 class="text-center">About Us</h2>
            <p>Our mission is to provide innovative IT solutions that drive business success. We value integrity, excellence, and customer satisfaction.</p>
            <h3 class="text-center">Meet the Team</h3>
            <div class="row justify-content-center">
                <div class="col-md-4 text-center">
                    <img src="image1.jpg" alt="Team Member 1" class="img-fluid rounded-circle">
                    <h4>Denis Kasala</h4>
                    <p>CEO</p>
                    <div class="social-links mt-3">
                        <a href="https://github.com/yourprofile" class="text-dark mx-2"><i class="fab fa-github"></i></a>
                        <a href="https://twitter.com/yourprofile" class="text-dark mx-2"><i class="fab fa-twitter"></i></a>
                        <a href="https://linkedin.com/in/yourprofile" class="text-dark mx-2"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Page -->
    <section id="contact" class="contact-section py-5">
        <div class="container">
            <h2 class="text-center">Contact Us</h2>
            <ul class="list-unstyled text-center">
                <li><strong>Email:</strong> raysuntech@gmail.com</li>
                <li><strong>Contact Number:</strong> 01123456543</li>
                <li><strong>Address:</strong> 26 1st Ave</li>
            </ul>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer-section py-4 bg-dark text-white">
        <div class="container text-center">
            <p>&copy; 2023 Raysun Tech. All rights reserved.</p>
            <div class="social-links">
                <a href="#" class="text-white mx-2"><i class="fab fa-twitter"></i></a>
                <a href="#" class="text-white mx-2"><i class="fab fa-linkedin-in"></i></a>
            </div>
            <div class="mt-3">
                <a href="#" class="text-white mx-2" data-toggle="modal" data-target="#termsModal">Terms</a>
                <a href="#" class="text-white mx-2" data-toggle="modal" data-target="#privacyModal">Privacy Policy</a>
            </div>
        </div>
    </footer>

    <!-- Modals -->
    <!-- Terms Modal -->
    <div class="modal fade" id="termsModal" tabindex="-1" role="dialog" aria-labelledby="termsModalLabel" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="termsModalLabel">Terms and Conditions</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <p>Welcome to Raysun Tech. These terms and conditions outline the rules and regulations for the use of our website.</p>
                    <p>By accessing this website we assume you accept these terms and conditions. Do not continue to use Raysun Tech if you do not agree to all of the terms and conditions stated on this page.</p>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>

    <!-- Privacy Policy Modal -->
    <div class="modal fade" id="privacyModal" tabindex="-1" role="dialog" aria-labelledby="privacyModalLabel" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="privacyModalLabel">Privacy Policy</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <p>Your privacy is important to us. It is Raysun Tech's policy to respect your privacy regarding any information we may collect from you across our website.</p>
                    <p>We only ask for personal information when we truly need it to provide a service to you. We collect it by fair and lawful means, with your knowledge and consent.</p>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Navbar color change on scroll
        window.addEventListener('scroll', function() {
            if (window.scrollY > 50) {
                document.querySelector('.navbar').style.backgroundColor = '#fff';
            } else {
                document.querySelector('.navbar').style.backgroundColor = 'rgba(255, 255, 255, 0.95)';
            }
        });

        // Add animation class to elements when they come into view
        const animateOnScroll = function() {
            const elements = document.querySelectorAll('.services-section .col-md-4, .testimonial-card');
            elements.forEach(element => {
                if (element.getBoundingClientRect().top < window.innerHeight) {
                    element.classList.add('animate__animated', 'animate__fadeInUp');
                }
            });
        };
        window.addEventListener('scroll', animateOnScroll);
    </script>
</body>
</html>
