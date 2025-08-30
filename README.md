[index.html](https://github.com/user-attachments/files/22056914/index.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>تهنئة بالمولد النبوي الشريف</title>
  <link href="https://fonts.googleapis.com/css2?family=Amiri&family=Cairo:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Amiri', 'Cairo', serif;
      background: radial-gradient(circle at center, #0f3d0f, #001a00);
      color: #fff;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    h1 {
      font-size: 2.8em;
      color: gold;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.8);
      margin-bottom: 20px;
      animation: fadeIn 2s ease-in-out;
    }

    h2 {
      font-size: 2.2em;
      margin-top: 10px;
      color: #fff;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.6);
      animation: fadeIn 3s ease-in-out;
    }

    .stars {
      position: absolute;
      width: 100%;
      height: 100%;
      background: transparent url('https://i.ibb.co/2k8PrdB/stars.png') repeat;
      animation: moveStars 60s linear infinite;
      opacity: 0.4;
    }

    @keyframes moveStars {
      from { background-position: 0 0; }
      to { background-position: -10000px 5000px; }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 600px) {
      h1 { font-size: 2em; }
      h2 { font-size: 1.5em; }
    }
  </style>
</head>
<body>
  <div class="stars"></div>
  <h1>🌙 كل عام وأنتم بخير بمناسبة المولد النبوي الشريف 🌙</h1>
  <h2>كل عام وأنت بخير يا <span style="color: gold;">محمد</span> 🌸</h2>

  <!-- 
    ✅ ملاحظة:
    لتغيير الاسم: عدل النص داخل span
    مثال:
    <span style="color: gold;">أحمد</span>
  -->
</body>
</html>
