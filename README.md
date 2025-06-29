# guest-house-website
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>King Sukh Guest House</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header id="home" class="home-section text-center text-light d-flex justify-content-center align-items-center">
        <div class="container">
            <ul class="home-nav">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#rooms">Rooms</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a class="book-now-btn" onclick="openWhatsApp()">Book Now</a></li>
            </ul>
            <p>WHERE COMFORT MEETS CHARM</p>
            <h1>Welcome to King Sukh Guest House</h1>
            <p>your tranquil escape nestled in the heart of Purulia...</p>
            <a href="#services" class="btn btn-primary mt-3">Explore Our Services</a>

        </div>
    </header>

    <section id="about">
        <div class="about-section">
            <div class="about-image">
                <img src="./assets/out (1).jpg" alt="About Us Image">
            </div>
            <div class="about-content">
                <h2>About Us</h2>
                <p>
                    Welcome to King Sukh Guest House, a place where comfort meets convenience.
                    We offer you a serene and comfortable stay, ensuring all your needs are met with the finest
                    services.
                </p>
                <p>
                    <strong>Address:</strong><br>
                    <a href="#map" id="about-address-link">Beside Barshal Water Tank, Manpur, Barhanti, West Bengal
                        723156</a>

                </p>
                <p>
                    <strong>Phone:</strong><br>
                    <a href="tel:+919007062180">+91 9007062180</a>
                </p>
                <button class="book-now-btn" onclick="openWhatsApp()">Book Now</button>

            </div>
        </div>
    </section>

    <section id="services" class="py-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8 text-center">
                    <h2 class="section-title mb-4">Services</h2>
                    <p class="section-subtitle mb-5">Strive Only For The Best.</p>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6">
                    <img src="assets/palash.webp" alt="Service Image" class="img-fluid">
                </div>
                <div class="col-lg-6">
                    <ul class="list-unstyled">
                        <li class="mb-4 d-flex align-items-center">
                            <span class="icon"><i class="fas fa-shield-alt"></i></span>
                            <span class="ml-3 service-text">High Class Security</span>
                        </li>
                        <li class="mb-4 d-flex align-items-center">
                            <span class="icon"><i class="fas fa-concierge-bell"></i></span>
                            <span class="ml-3 service-text">24 Hours Room Service</span>
                        </li>
                        <li class="mb-4 d-flex align-items-center">
                            <span class="icon"><i class="fas fa-utensils"></i></span>
                            <span class="ml-3 service-text">Restaurant</span>
                        </li>
                        <li class="mb-4 d-flex align-items-center">
                            <span class="icon"><i class="fas fa-map-signs"></i></span>
                            <span class="ml-3 service-text">Tourist Guide Support</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="rooms" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Our Rooms</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card room-card">
                        <img src="assets/small.jpg" class="card-img-top" alt="Standard Room">
                        <div class="card-body">
                            <h5 class="card-title">Standard Room</h5>
                            <p class="card-text">A comfortable room with modern amenities and a cozy atmosphere.</p>
                            <p><strong> Starting from: </strong> Rs. 1000/night</p>
                            <button class="book-now-btn" onclick="openWhatsApp()">Book Now</button>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card room-card">
                        <img src="assets/room1.jpg" class="card-img-top" alt="Deluxe Room">
                        <div class="card-body">
                            <h5 class="card-title">Deluxe Room</h5>
                            <p class="card-text">A luxurious room with a king-sized bed, private balcony, and a stunning
                                city view.</p>
                            <p><strong> Starting from: </strong> Rs. 1500/night</p>
                            <button class="book-now-btn" onclick="openWhatsApp()">Book Now</button>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card room-card">
                        <img src="assets/room-image-2.jpg" class="card-img-top" alt="Suite">
                        <div class="card-body">
                            <h5 class="card-title">Suite</h5>
                            <p class="card-text">An expansive suite with a separate living area, perfect for families or
                                long stays.</p>
                            <p><strong> Starting from: </strong> Rs. 2000/night</p>
                            <button class="book-now-btn" onclick="openWhatsApp()">Book Now</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="gallery" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Gallery</h2>
            <div class="row">
                <div class="col-md-3 gallery-item">
                    <img src="assets/palash.webp" class="img-fluid mb-4 gallery-img" alt="Gallery Image 1">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/mithonDam.webp" class="img-fluid mb-4 gallery-img" alt="Gallery Image 2">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/large.jpg" class="img-fluid mb-4 gallery-img" alt="Gallery Image 3">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/recep.jpg" class="img-fluid mb-4 gallery-img" alt="Gallery Image 4">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/room1.jpg" class="img-fluid mb-4 gallery-img" alt="Gallery Image 4">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/service.jpg" class="img-fluid mb-4 gallery-img" alt="Gallery Image 4">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/baranti.webp" class="img-fluid mb-4 gallery-img" alt="Gallery Image 4">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/flower.jpg" class="img-fluid mb-4 gallery-img" alt="Gallery Image 4">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/1.jpg" class="img-fluid mb-4 gallery-img" alt="Gallery Image 4">
                </div>
                <div class="col-md-3 gallery-item">
                    <img src="assets/out.jpg" class="img-fluid mb-4 gallery-img" alt="Gallery Image 4">
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-4 mb-5">
                    <div class="contact-info p-4 shadow-sm">
                        <h3 class="mb-4">Contact Info</h3>
                        <p><a href="#map" id="address-link">Beside Barshal Water Tank, Manpur, Barhanti, West Bengal
                                723156</a></p>
                        <p>Email: <a href="mailto:kkghosh0099@gmail.com">kkghosh0099@gmail.com</a></p>
                        <p>Phone: <a href="tel:+919007062180">+91 9007062180</a></p>
                        <div class="social-icons mt-4">
                            <a href="#home"><i class="fab fa-facebook-f"></i></a>
                            <a href="https://www.instagram.com/kingsukhguesthouse"><i class="fab fa-instagram"></i></a>
                            <a href="#home"><i class="fab fa-twitter"></i></a>
                            <a href="#home"><i class="fab fa-linkedin-in"></i></a>
                        </div>

                    </div>
                </div>
                <div class="col-lg-8">
                    <div class="contact-form p-4 shadow-sm">
                        <h3 class="mb-4">Send a Message</h3>
                        <form>
                            <div class="form-row mb-3">
                                <div class="form-group mb-3">
                                    <input type="text" class="form-control" placeholder="Your Name" required>
                                </div>
                                <div class="form-group mb-3">
                                    <input type="email" class="form-control" placeholder="Your Email" required>
                                </div>
                            </div>
                            <div class="form-group mb-3">
                                <input type="text" class="form-control" placeholder="Subject" required>
                            </div>
                            <div class="form-group mb-3">
                                <textarea class="form-control" rows="6" placeholder="Your Message" required></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary">Send Message</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="map">
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3656.5017351225665!2d86.85721547533088!3d23.58633237878266!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39f6e3fdd3ff9ebb%3A0x517a57e3f93c1807!2sKingsukh%20Guest%20House!5e0!3m2!1sen!2sin!4v1723582494923!5m2!1sen!2sin"
            width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"></iframe>

    </section>

    <footer>
        <div class="footer-column">
            <h3>King Sukh Guest House</h3>
            <p>Discover a world of comfort, luxury, and adventure as you explore our curated selection of hotels, making
                every moment of your getaway truly extraordinary.</p>
            <button class="book-now-btn" onclick="openWhatsApp()">Book Now</button>

        </div>
        <div class="footer-column">
            <h3>Quick Links</h3>
            <ul>
                <li><a href="#home">Browse Destinations</a></li>
                <li><a href="#home">Special Offers & Packages</a></li>
                <li><a href="#home">Room Types & Amenities</a></li>
                <li><a href="#home">Customer Reviews & Ratings</a></li>
                <li><a href="#home">Travel Tips & Guides</a></li>
            </ul>
        </div>
        <div class="footer-column">
            <h3>Our Services</h3>
            <ul>
                <li><a href="#home">Concierge Assistance</a></li>
                <li><a href="#home">Flexible Booking Options</a></li>
                <li><a href="#home">Airport Transfers</a></li>
                <li><a href="#home">Wellness & Recreation</a></li>
            </ul>
        </div>
        <div class="footer-column">
            <h3>Contact Us</h3>
            <p><a href="#map" id="address-link">Beside Barshal Water Tank, Manpur, Barhanti, West Bengal
                    723156</a></p>
            <p>Email: <a href="mailto:kkghosh0099@gmail.com">kkghosh0099@gmail.com</a></p>
            <p>Phone: <a href="tel:+919007062180">+91 9007062180</a></p>
            <div class="social-media-icons">
                <a href="#home"><img src="assets/facebook.png" alt="Facebook"></a>
                <a href="https://www.instagram.com/kingsukhguesthouse/"><img src="assets/instagram.png"
                        alt="Instagram"></a>
                <a href="#home"><img src="assets/youtube.png" alt="YouTube"></a>
                <a href="#home"><img src="assets/twitter.png" alt="Twitter"></a>
            </div>
        </div>
    </footer>

    <script src="scripts.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
