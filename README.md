<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cars and Bikes Showroom</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 10px 20px;
      text-align: center;
    }
    nav {
      background-color: #444;
      color: #fff;
      text-align: center;
      padding: 10px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }
    section {
      padding: 20px;
    }
    .vehicle {
      margin-bottom: 20px;
    }
    .vehicle img {
      max-width: 100%;
      height: auto;
    }
    .vehicle h2 {
      margin-top: 10px;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Cars and Bikes Showroom</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Cars</a>
    <a href="#">Bikes</a>
    <a href="#">Contact Us</a>
  </nav>

  <section>
    <div class="vehicle">
      <img src="car1.jpg" alt="Car 1">
      <h2>Car 1</h2>
      <p>Description of Car 1 goes here.</p>
    </div>
    <div class="vehicle">
      <img src="car2.jpg" alt="Car 2">
      <h2>Car 2</h2>
      <p>Description of Car 2 goes here.</p>
    </div>
    <div class="vehicle">
      <img src="bike1.jpg" alt="Bike 1">
      <h2>Bike 1</h2>
      <p>Description of Bike 1 goes here.</p>
    </div>
    <div class="vehicle">
      <img src="bike2.jpg" alt="Bike 2">
      <h2>Bike 2</h2>
      <p>Description of Bike 2 goes here.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Cars and Bikes Showroom</p>
  </footer>

</body>
</html>
