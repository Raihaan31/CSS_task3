<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sticky Header with Logo</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Sticky Header */
    header {
      position: sticky;
      top: 0;
      background-color: #fff;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      z-index: 999;
    }

    .logo img {
      height: 40px;
      width: auto;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #007BFF;
    }

    /* Page Content */
    main {
      padding: 20px;
      height: 2000px;
      background: linear-gradient(#f9f9f9, #e0e0e0);
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="SEC-Logo-1.png" alt="Logo" />
    </div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Welcome to the Page</h1>
    <p>Scroll down to see the sticky header stay at the top.</p>
  </main>

</body>
</html>
