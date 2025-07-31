<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Simple Responsive Page</title>
  <style>
    /* Basic reset */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      padding: 20px;
      background-color: #f4f4f4;
    }

    header {
      background: #333;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }

    nav {
      margin: 20px 0;
      text-align: center;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    nav a:hover {
      color: #007bff;
    }

    main {
      max-width: 900px;
      margin: 0 auto;
      background: white;
      padding: 20px;
      border-radius: 5px;
    }

    .flex-container {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .box {
      flex: 1 1 250px;
      background: #007bff;
      color: white;
      padding: 20px;
      border-radius: 5px;
      min-width: 250px;
      text-align: center;
    }

    footer {
      margin-top: 30px;
      text-align: center;
      color: #666;
      font-size: 0.9em;
    }

    /* Responsive tweak */
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>My Simple Responsive Webpage</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <section class="flex-container">
      <div class="box">
        <h2>Box 1</h2>
        <p>This is a responsive box that adjusts with screen size.</p>
      </div>
      <div class="box">
        <h2>Box 2</h2>
        <p>Resize your browser to see the effect.</p>
      </div>
      <div class="box">
        <h2>Box 3</h2>
        <p>Simple and clean layout.</p>
      </div>
    </section>
  </main>

  <footer>
    &copy; 2025 Your Name. All rights reserved.
  </footer>
</body>
</html>
