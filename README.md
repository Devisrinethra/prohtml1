<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My DEXO Engine</title>

  <style>
    /* Basic reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Body styling with gradient background */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #8e44ad, #3498db); /* Elegant vibrant gradient */
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
    }

    /* Container */
    .container {
      text-align: center;
      background-color: rgba(255, 255, 255, 0.1); /* Glass effect */
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.25);
      backdrop-filter: blur(10px);
    }

    /* Website title */
    .site-title {
      font-size: 3rem;
      margin-bottom: 30px;
      color: #ffffff;
    }

    /* Search form */
    .search-form {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    /* Search box */
    .search-box {
      padding: 12px 16px;
      width: 300px;
      font-size: 16px;
      border: none;
      border-radius: 6px 0 0 6px;
      outline: none;
      background-color: #fff;
      color: #333;
    }

    /* Search button */
    .search-button {
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      background-color: #ffffff;
      color: #8e44ad;
      font-weight: bold;
      border-radius: 0 6px 6px 0;
      cursor: pointer;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    .search-button:hover {
      background-color: #8e44ad;
      color: #fff;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="site-title">My DEXO Engine</h1>
    <form action="#" method="GET" class="search-form">
      <input type="text" placeholder="Search..." name="query" class="search-box" />
      <button type="submit" class="search-button">Search</button>
    </form>
  </div>
</body>
</html>
