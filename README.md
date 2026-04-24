<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقعي</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      text-align: center;
    }

    header {
      background: #ff1744;
      color: white;
      padding: 20px;
      font-size: 24px;
      font-weight: bold;
    }

    .desc {
      margin: 15px;
      color: #444;
    }

    .btn {
      display: inline-block;
      margin: 15px;
      padding: 12px 25px;
      background: black;
      color: white;
      text-decoration: none;
      border-radius: 8px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 10px;
      padding: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      transition: 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      margin: 20px;
      color: #777;
    }
  </style>
</head>

<body>

  <header>
    🎉 موقعي الجميل
  </header>

  <div class="desc">
    ده موقع بسيط معمول عشان تعرض صورك أو شغلك بسهولة 👌
  </div>

  <a class="btn" href="https://google.com" target="_blank">
    اضغط هنا
  </a>

  <div class="gallery">
    <img src="https://picsum.photos/400/300?1">
    <img src="https://picsum.photos/400/300?2">
    <img src="https://picsum.photos/400/300?3">
    <img src="https://picsum.photos/400/300?4">
  </div>

  <footer>
    © 2026 - موقعك
  </footer>

</body>
</html>
