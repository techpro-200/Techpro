!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Search Bar Example</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }
    .search-container {
      width: 100%;
      background-color: #333;
      padding: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      position: fixed;
      top: 0;
      left: 0;
      z-index: 999;
    }
    .search-box {
      max-width: 600px;
      margin: auto;
      display: flex;
    }
    .search-box input[type="text"] {
      width: 100%;
      padding: 8px;
      border: none;
      border-radius: 4px 0 0 4px;
    }
    .search-box button {
      padding: 8px 15px;
      border: none;
      background-color: #00bfff;
      color: white;
      border-radius: 0 4px 4px 0;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <div class="search-container">
    <div class="search-box">
      <input type="text" placeholder="ابحث هنا...">
      <button>بحث</button>
    </div>
  </div>

  <!-- محتوى وهمي لتجربة التمرير -->
  <div style="margin-top: 80px; padding: 20px;">
    <p>مرحبا بك في موقعك!</p>
    <p>أضف هنا محتوى الموقع الخاص بك.</p>
  </div>

</body>
</html>

