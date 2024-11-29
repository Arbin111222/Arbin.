<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VideoCraft AI</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; }
    header { background: #333; color: white; padding: 10px 20px; }
    header h1 { margin: 0; font-size: 24px; }
    nav ul { list-style: none; padding: 0; margin: 0; display: flex; justify-content: center; }
    nav ul li { margin: 0 15px; }
    nav ul li a { color: white; text-decoration: none; font-size: 18px; }
    .hero { text-align: center; padding: 50px; background: linear-gradient(to right, #6a11cb, #2575fc); color: white; }
    .hero h1 { font-size: 3em; margin-bottom: 20px; }
    .hero p { font-size: 1.2em; }
    .hero button { padding: 10px 20px; background: #fff; color: #333; border: none; border-radius: 5px; cursor: pointer; margin: 10px; }
    .features { display: flex; flex-wrap: wrap; justify-content: center; padding: 20px; background: #f9f9f9; }
    .features div { flex: 1 1 300px; margin: 10px; padding: 20px; background: white; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); text-align: center; }
    .contact { padding: 20px; text-align: center; background: #eee; }
    .contact form { max-width: 500px; margin: 0 auto; }
    .contact input, .contact textarea { width: 100%; margin: 10px 0; padding: 10px; border: 1px solid #ccc; border-radius: 5px; }
    .contact button { padding: 10px 20px; background: #333; color: white; border: none; cursor: pointer; border-radius: 5px; }
    footer { background: #333; color: white; text-align: center; padding: 10px; margin-top: 20px; }
    @media (max-width: 600px) {
      .hero h1 { font-size: 2em; }
      .features { flex-direction: column; }
    }
  </style>
</head>
<body>

<header>
  <h1>VideoCraft AI</h1>
  <nav>
    <ul>
      <li><a href="#features">Features</a></li>
      <li><a href="#demo">AI Demo</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section class="hero">
  <h1>Create Stunning Videos in Minutes!</h1>
  <p>AI-powered video creation made easy.</p>
  <button>Try for Free</button>
  <button>Learn More</button>
</section>

<section id="features" class="features">
  <div>
    <h2>AI-Powered Tools</h2>
    <p>Automate video editing with advanced AI technology.</p>
  </div>
  <div>
    <h2>Customizable Templates</h2>
    <p>Choose from a variety of professional designs.</p>
  </div>
  <div>
    <h2>User-Friendly</h2>
    <p>Create videos effortlessly with an intuitive interface.</p>
  </div>
</section>

<section id="demo" class="features">
  <div>
    <h2>AI Demo (Coming Soon)</h2>
    <p>Experience the power of VideoCraft AI with our demo tools.</p>
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>Have questions? Reach out to us!</p>
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="_replyto" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  <p>&copy; 2024 VideoCraft AI. All rights reserved.</p>
</footer>

</body>
</html>