<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HONEYBEE</title>
</head>
<body>
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Honey Bee Products</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
    }

    /* HEADER */
    header {
      background: #fdd835;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: bold;
      color: #3e2723;
    }

    nav ul {
      display: flex;
      list-style: none;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      text-decoration: none;
      color: #3e2723;
      font-weight: 500;
    }

    .cta-button {
      background: #3e2723;
      color: #fff;
      padding: 8px 15px;
      text-decoration: none;
      border-radius: 5px;
    }

    /* FOOTER */
    footer {
      background: #3e2723;
      color: #fff;
      padding: 40px 20px;
    }

    .footer-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    .footer-column {
      flex: 1;
      margin: 15px;
      min-width: 200px;
    }

    .footer-column h4 {
      margin-bottom: 15px;
    }

    .footer-column ul {
      list-style: none;
    }

    .footer-column ul li {
      margin-bottom: 10px;
    }

    .footer-column ul li a {
      color: #fff;
      text-decoration: none;
    }

    .social-icons a {
      color: #fdd835;
      margin-right: 10px;
      font-size: 18px;
    }

    .newsletter input[type="email"] {
      padding: 8px;
      width: 70%;
      border: none;
      border-radius: 5px 0 0 5px;
    }

    .newsletter button {
      padding: 8px 15px;
      background: #fdd835;
      border: none;
      border-radius: 0 5px 5px 0;
      color: #3e2723;
      font-weight: bold;
      cursor: pointer;
    }

    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        align-items: flex-start;
      }
      .footer-container {
        flex-direction: column;
      }
    }
    .honey-section {
    padding: 50px;
    background-color: #fffbee;
    text-align: center;
    font-family: 'Segoe UI', sans-serif;
  }

  .honey-section h2 {
    font-size: 2rem;
    color: #3e2723;
  }

  .honey-section p {
    max-width: 800px;
    margin: 20px auto;
    font-size: 1.2rem;
    color: #4e342e;
  }

  .cta-button {
    display: inline-block;
    margin-top: 30px;
    padding: 12px 25px;
    background-color: #fdd835;
    color: #3e2723;
    font-weight: bold;
    border-radius: 5px;
    text-decoration: none;
  }

  .honey-image {
    margin: 30px auto;
    max-width: 300px;
    width: 100%;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }

  .honey-types {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
    margin-top: 40px;
  }

  .honey-type {
    width: 150px;
    text-align: center;
  }

  .honey-type img {
    width: 100%;
    border-radius: 10px;
  }

  .honey-type span {
    display: block;
    margin-top: 10px;
    font-weight: bold;
    color: #3e2723;
  }
  .honey-section {
  padding: 50px;
  background-color: #fffbee;
  text-align: center;
  font-family: 'Segoe UI', sans-serif;
  background-image: url('https://images.unsplash.com/photo-1604335399104-272b3bb2168e'); /* Background image */
  background-attachment: fixed;
  background-size: cover;
  color: #fff;
}
.honey-type img {
  width: 100%;
  border-radius: 10px;
  transition: transform 0.3s ease;
}

.honey-type:hover img {
  transform: scale(1.1); /* Image zoom effect */
}

.honey-type span {
  display: block;
  margin-top: 10px;
  font-weight: bold;
  color: #3e2723;
  transition: color 0.3s ease;
}

.honey-type:hover span {
  color: #fdd835; /* Highlight text on hover */
}
.cta-button {
  display: inline-block;
  margin-top: 30px;
  padding: 12px 25px;
  background-color: #fdd835;
  color: #3e2723;
  font-weight: bold;
  border-radius: 5px;
  text-decoration: none;
  position: sticky;
  top: 80%; /* Stick near the bottom of the screen */
  z-index: 999;
}
html {
  scroll-behavior: smooth;
}
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <div class="logo">HoneyBee Naturals</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#shop">Shop</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <a href="#shop" class="cta-button">Shop Now</a>
  </header>

  <!-- MAIN CONTENT (placeholder) -->
  <main><section class="honey-section" id="about-honey">
    <h2>Why Choose Our Honey?</h2>
    <img src="https://images.unsplash.com/photo-1609422011080-846f8c38a979" alt="Jar of Pure Honey" class="honey-image">
  
    <p>
      Our honey isn’t just sweet — it’s nature’s gold. At <strong>HoneyBee Naturals</strong>, we offer a wide variety of 
      <strong>100% pure, raw, and unfiltered honey</strong> straight from our trusted local beekeepers.
    </p>
    <p>
      From the floral notes of <strong>Wildflower Honey</strong> to the rich taste of <strong>Forest and Himalayan Honey</strong>, 
      each jar is packed with natural enzymes, antioxidants, and unbeatable flavor.
    </p>
    <p>
      No additives. No processing. Just <strong>pure, healthy goodness</strong> — the way nature intended.
    </p>
  
    <div class="honey-types">
      <div class="honey-type">
        <img src="https://images.unsplash.com/photo-1621795474932-e89e8e0e88fd" alt="Wildflower Honey">
        <span>Wildflower</span>
      </div>
      <div class="honey-type">
        <img src="https://images.unsplash.com/photo-1604335399104-272b3bb2168e" alt="Forest Honey">
        <span>Forest</span>
      </div>
      <div class="honey-type">
        <img src="https://images.unsplash.com/photo-1633613286993-7ac2b6b9f1f7" alt="Himalayan Honey">
        <span>Himalayan</span>
      </div>
    </div>
  
    <a href="#shop" class="cta-button">Explore Our Honey Collection</a>
  </section>
    <!-- Your page content goes here -->
  </main>
  <section style="padding: 50px; background-color: #fdd835; text-align: center;">
    <h2 style="font-size: 2rem; color: #3e2723;">What Our Customers Are Saying</h2>
  
    <div class="testimonials" style="display: flex; justify-content: center; gap: 30px; flex-wrap: wrap; margin-top: 40px;">
      <div class="testimonial" style="width: 250px; background-color: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
        <p style="font-style: italic;">"Best honey I've ever tasted! The Wildflower Honey is so pure and rich in flavor!"</p>
        <h4 style="color: #3e2723;">Emily R.</h4>
        <p style="font-size: 0.9rem; color: #4e342e;">Verified Buyer</p>
      </div>
  
      <div class="testimonial" style="width: 250px; background-color: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
        <p style="font-style: italic;">"Himalayan Honey has become my go-to! It's natural, delicious, and perfect in my tea."</p>
        <h4 style="color: #3e2723;">John D.</h4>
        <p style="font-size: 0.9rem; color: #4e342e;">Verified Buyer</p>
      </div>
  
      <div class="testimonial" style="width: 250px; background-color: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
        <p style="font-style: italic;">"I love the taste and benefits of your honey. It's my family's go-to for health!"</p>
        <h4 style="color: #3e2723;">Samantha T.</h4>
        <p style="font-size: 0.9rem; color: #4e342e;">Verified Buyer</p>
      </div>
    </div>
  </section>
  
  <!-- FOOTER -->
  <footer>
    <div class="footer-container">
      <div class="footer-column">
        <h4>About Us</h4>
        <p>Pure honey from our local bee farms, 100% natural and eco-friendly. Supporting bees, supporting life.</p>
      </div>
      <div class="footer-column">
        <h4>Quick Links</h4>
        <ul>
          <li><a href="#shop">Our Products</a></li>
          <li><a href="#faq">FAQs</a></li>
          <li><a href="#blog">Blog</a></li>
        </ul>
      </div>
      <div class="footer-column">
        <h4>Connect</h4>
        <div class="social-icons">
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
        </div>
      </div>
      <div class="footer-column">
        <h4>Newsletter</h4>
        <form class="newsletter">
          <input type="email" placeholder="Enter your email">
          <button type="submit">Subscribe</button>
          
        </form>
      </div>
    </div>
    <div class="footer-column">
        <h4>Contact Us</h4>
        <p><i class="fas fa-phone"></i> 03182430536</p>
        <p><i class="fas fa-envelope"></i> support@honeybee.com</p>
    </div>
    <p></p> ></p style>="text-align:center; margin-top: 20px;">&copy; 2025 HoneyBee Naturals. All rights reserved.</p>
  </footer>

</body>
</html>

</body>
</html>
