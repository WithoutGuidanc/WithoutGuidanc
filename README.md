<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>محمد خالد | بدون حدود</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Cairo', sans-serif;
    }

    body {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 4rem 1rem 2rem;
      background: rgba(0, 0, 0, 0.2);
    }

    header h1 {
      font-size: 3rem;
      color: #00d4ff;
      animation: fadeInDown 1s ease forwards;
    }

    header p {
      font-size: 1.2rem;
      color: #b0e0e6;
      animation: fadeInDown 1.5s ease forwards;
    }

    .section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }

    .section-title {
      font-size: 2rem;
      border-bottom: 2px solid #00d4ff;
      margin-bottom: 1rem;
      display: inline-block;
    }

    .skills, .tools {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .badge {
      background: #00d4ff;
      color: #000;
      padding: 0.5rem 1rem;
      border-radius: 30px;
      font-weight: bold;
      box-shadow: 0 0 10px #00d4ff;
      transition: transform 0.3s;
    }

    .badge:hover {
      transform: scale(1.05);
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 10px;
      overflow: hidden;
    }

    table thead {
      background: #00d4ff;
      color: #000;
    }

    table th, table td {
      padding: 1rem;
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: rgba(0, 0, 0, 0.3);
      font-size: 0.9rem;
    }

    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-30px); }
      100% { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://raw.githubusercontent.com/WithoutGuidanc/WithoutGuidanc/main/beb8bd9d-324d-41af-be81-f6ed56475718.png" alt="شعار" width="120" style="border-radius: 50%; box-shadow: 0 0 10px #00d4ff;">
    <h1>محمد خالد</h1>
    <p>مطور ويب | صانع لغات برمجة | مطور أنظمة</p>
  </header>

  <section class="section">
    <h2 class="section-title">🌟 الرؤية والمقولة</h2>
    <p>"هدفي أن أوصل البرمجة المفيدة للعالم بلغة يفهمها الجميع وبطريقة تلهمهم للتجربة والتطوير بلا حدود"</p>
  </section>

  <section class="section">
    <h2 class="section-title">🧰 الأدوات والتقنيات</h2>
    <div class="tools">
      <span class="badge">Termux</span>
      <span class="badge">Git</span>
      <span class="badge">C++</span>
      <span class="badge">HTML</span>
      <span class="badge">CSS</span>
      <span class="badge">Sass</span>
      <span class="badge">JavaScript</span>
      <span class="badge">React</span>
      <span class="badge">Spck Editor</span>
    </div>
  </section>

  <section class="section">
    <h2 class="section-title">🚀 أهم المشاريع</h2>
    <table>
      <thead>
        <tr>
          <th>📁 اسم المشروع</th>
          <th>الوصف</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>nujz</strong></td>
          <td>لغة برمجة جديدة بالكامل بتصميم نحوي خاص ومترجم خاص بها.</td>
        </tr>
        <tr>
          <td><strong>موقع nujz</strong></td>
          <td>موقع توثيقي للغة، يعرض خصائصها وأمثلة عليها ويوفر محرر مباشر.</td>
        </tr>
        <tr>
          <td><strong>محرر Nujz</strong></td>
          <td>محرر أكواد تفاعلي يدعم لغة nujz ومكتوب بتقنيات ويب حديثة.</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section class="section">
    <h2 class="section-title">📬 تواصل معي</h2>
    <p>📧 <a href="mailto:mohammed.khaled.abdullah.mauhod@gmail.com" style="color:#00d4ff">mohammed.khaled.abdullah.mauhod@gmail.com</a></p>
    <p>📘 <a href="https://www.facebook.com/share/1AG2Por8g8/" style="color:#00d4ff">فيسبوك</a></p>
    <p>🔗 <a href="#" style="color:#00d4ff">LinkedIn</a> (تعديل لاحق)</p>
  </section>

  <footer>
    تصميم وتنفيذ © محمد خالد – بدون حدود ❤️
  </footer>
</body>
</html>
