<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
    <style>
        #hero {
  background-color: #007bff;
  color: white;
  text-align: center;
  padding: 60px 20px;
}

#hero h1 {
  font-size: 36px;
}

#hero p {
  font-size: 18px;
  margin: 20px 0;
}

.cta-btn {
  padding: 15px 30px;
  background-color: #ffffff;
  color: #007bff;
  font-size: 18px;
  text-transform: uppercase;
  border-radius: 5px;
  text-decoration: none;
}

.cta-btn:hover {
  background-color: #0056b3;
  color: white;
}

#features {
  padding: 60px 20px;
  text-align: center;
}

#features h2 {
  font-size: 32px;
  margin-bottom: 40px;
}

.features-container {
  display: flex;
  justify-content: space-around;
  gap: 20px;
}

.feature {
  background-color: #f9f9f9;
  padding: 20px;
  border-radius: 8px;
  width: 30%;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.feature-icon {
  width: 50px;
  height: 50px;
  margin-bottom: 15px;
}

.feature h3 {
  font-size: 24px;
  margin-bottom: 10px;
}

.feature p {
  color: #666;
}

/* Responsive Layout for Mobile */
@media (max-width: 768px) {
  .features-container {
    flex-direction: column;
    align-items: center;
  }

  .feature {
    width: 80%;
    margin-bottom: 30px;
  }
}

footer {
  background-color: #333;
  color: white;
  padding: 40px 20px;
  text-align: center;
}

footer p {
  margin-bottom: 10px;
}

footer .social-links {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 20px;
}

footer .social-links li {
  margin: 0;
}

footer .social-links a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

footer .social-links a:hover {
  text-decoration: underline;
}

    </style>
<body>

    <section id="hero">
        <div class="hero-content">
          <h1>Computer and Hardware Suppliers</h1>
          <p>Providing top-notch technology solutions for your every need.</p>
          <a href="#features" class="cta-btn">Learn More</a>
        </div>
      </section>
      <section id="features">
        <h2>Key Features</h2>
        <div class="features-container">
          <div class="feature">
            <img src="icon1.png" alt="Feature 1" class="feature-icon">
            <h3>Quality Products</h3>
            <p>We offer the latest and best quality products to meet all your computing needs.</p>
          </div>
          <div class="feature">
            <img src="icon2.png" alt="Feature 2" class="feature-icon">
            <h3>Affordable Prices</h3>
            <p>Get the best deals and prices for high-end hardware and computer.</p>
          </div>
          <div class="feature">
            <img src="icon3.png" alt="Feature 3" class="feature-icon">
            <h3>Expert Support</h3>
            <p>Our experts are always available to provide you with technical support and advice.</p>
          </div>
        </div>
      </section>
      
      <footer id="contact">
        <p>Contact us at: iisalisuonline@gmail.com</p>
        <p>Follow us on:</p>
        <ul class="social-links">
          <li><a href="#">Facebook</a></li>
          <li><a href="#">Twitter</a></li>
          <li><a href="#">Instagram</a></li>
        </ul>
        <p>&copy; 2025 Fictional Product. All Rights Reserved.</p>
      </footer>
      
      
</body>
</html>
</html>
