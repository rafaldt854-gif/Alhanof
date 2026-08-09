# Alhanof
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>الهنوف - GSAP Animation</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #1a1a2e;
      color: #e94560;
      font-family: 'Arial', sans-serif;
      overflow: hidden;
    }

    .name-title {
      font-size: 5rem;
      font-weight: bold;
      letter-spacing: 2px;
      text-shadow: 0 0 20px rgba(233, 69, 96, 0.5);
    }
  </style>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
</head>
<body>

  <div class="name-title" id="name">الهنوف</div>

  <script>
    gsap.from("#name", {
      duration: 2,
      scale: 0.2,
      opacity: 0,
      rotation: 360,
      ease: "back.out(1.7)"
    });
  </script>

</body>
</html>
