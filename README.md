<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Radici Experience</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }

    header {
      background: url('https://images.unsplash.com/photo-olive-grove') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
      text-align: center;
      background-color: #000;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      background: #6b8e23;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .feature {
      background: #f4f4f4;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }

    .highlight {
      background: #fafafa;
      text-align: center;
      font-style: italic;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
    }

    form button {
      background: #6b8e23;
      color: white;
      padding: 10px 20px;
      border: none;
    }
  </style>
</head>

<body>

<!-- HERO -->
<header>
  <h1>Radici Experience</h1>
  <p>Live the Roots of Italy</p>
  <p>Authentic cultural immersion in Italian rural life</p>
  <a href="#contact" class="btn">Apply Now</a>
</header>

<!-- ABOUT -->
<section>
  <h2>About</h2>
  <p>
    Radici—Italian for “roots”—represents a return to what truly matters:
    land, culture, food, and human connection.
  </p>
  <p>
    We offer immersive experiences where you live and participate in
    authentic Italian rural life, far beyond traditional tourism.
  </p>
</section>

<!-- EXPERIENCE -->
<section>
  <h2>The Experience</h2>

  <div class="features">
    <div class="feature">
      <h3>🌿 Farm Life</h3>
      <p>Participate in olive harvesting and learn traditional techniques.</p>
    </div>

    <div class="feature">
      <h3>🍝 Food & Culture</h3>
      <p>Enjoy cooking classes and meals with local families.</p>
    </div>

    <div class="feature">
      <h3>🏡 Local Living</h3>
      <p>Stay in countryside homes and explore nearby villages.</p>
    </div>
  </div>
</section>

<!-- UNIQUE -->
<section class="highlight">
  <h2>Not a Tour. A Return to the Roots.</h2>
  <p>
    Connect with land, people, and traditions through meaningful experiences.
  </p>
</section>

<!-- PROGRAM -->
<section>
  <h2>Sample Program</h2>
  <p><strong>Duration:</strong> 7 Days</p>
  <ul>
    <li>Olive harvesting experience</li>
    <li>Cooking classes</li>
    <li>Wine and olive oil tasting</li>
    <li>Village visits</li>
    <li>Farm-to-table meals</li>
  </ul>
</section>

<!-- PRICING -->
<section>
  <h2>Pricing</h2>
  <p>
    Starting from <strong>€1,500 per person</strong>
  </p>
  <p>
    Includes accommodation, meals, activities, and local transport.
  </p>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Join the Experience</h2>

  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea placeholder="Tell us about your interest"></textarea>
    <button type="submit">Submit</button>
  </form>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Radici Experience | Italy</p>
</footer>

</body>
</html>