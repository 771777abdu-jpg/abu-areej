<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>أبو أريج للدهانات</title>
  <style>
    body {
      margin:0;
      font-family:"Tahoma","Noto Naskh Arabic",sans-serif;
      background:#fff; /* خلفية عادية */
      color:#222;
      line-height:1.6;
    }
    header {
      background:rgba(11,116,222,0.95);
      color:#fff;
      text-align:center;
      padding:60px 20px;
    }
    header h1{
      margin:0;
      font-size:38px;
      display:inline-block;
      vertical-align:middle;
    }
    header p{margin:10px 0 0;font-size:20px;}
    nav {
      background:#fff;
      box-shadow:0 2px 6px rgba(0,0,0,0.05);
      position:sticky;
      top:0;
      z-index:10;
    }
    nav ul{margin:0;list-style:none;display:flex;justify-content:center;padding:0;}
    nav li{margin:0;}
    nav a {
      display:block;
      padding:14px 20px;
      color:#0b74de;
      text-decoration:none;
      font-weight:600;
      transition:.3s;
    }
    nav a:hover{background:#f0f6ff;}
    section{max-width:1100px;margin:auto;padding:60px 20px;}
    h2{color:#0b74de;margin-bottom:20px;text-align:center;font-size:28px;}
    .about,.contact{text-align:center;}
    .services ul{list-style:disc;padding-right:20px;text-align:right;font-size:18px;}
    .gallery{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
      gap:25px;
      margin-top:20px;
    }
    .gallery img{
      width:100%;
      border-radius:12px;
      box-shadow:0 4px 15px rgba(0,0,0,0.2);
      transition:transform .3s;
    }
    .gallery img:hover{
      transform:scale(1.03);
    }
    .btn{
      display:inline-block;
      margin-top:20px;
      background:#0b74de;
      color:#fff;
      padding:12px 24px;
      border-radius:8px;
      text-decoration:none;
      font-weight:bold;
      transition:.3s;
    }
    .btn:hover{background:#094f9d;}
    footer{
      background:#0b74de;
      color:#fff;
      text-align:center;
      padding:20px;
      margin-top:40px;
    }
  </style>
</head>
<body>
  <!-- رأس الموقع -->
  <header>
    <h1>أبو أريج للدهانات</h1>
    <p>خبرة في جميع أعمال الدهانات والديكورات الداخلية والخارجية</p>
  </header>

  <!-- قائمة التنقل -->
  <nav>
    <ul>
      <li><a href="#about">من نحن</a></li>
      <li><a href="#services">الخدمات</a></li>
      <li><a href="#gallery">واجهات الأعمال</a></li>
      <li><a href="#contact">تواصل معنا</a></li>
    </ul>
  </nav>

  <!-- قسم التعريف -->
<section id="about" class="about">
  <h2>من نحن</h2>
  <p>
    أنا <strong>أبو أريج</strong>، معلم دهانات بخبرة واسعة في تنفيذ جميع أنواع الدهانات الداخلية والخارجية. 
    أعمل باحترافية عالية مع الحرص على أدق التفاصيل، باستخدام أجود المواد وأحدث الأساليب لضمان جودة تدوم لسنوات طويلة.
  </p>
  <p>
    أقدم حلول متكاملة تناسب ذوق العميل واحتياجاته، بداية من اختيار الألوان المناسبة وحتى التنفيذ بدقة عالية، 
    مع التزام تام بالمواعيد وأسعار تنافسية. رؤيتي هي أن أجعل كل مشروع تحفة فنية تعكس جمال المكان وتبرز ذوق العميل بأفضل صورة.
  </p>

  <h3>لماذا تختارنا؟</h3>
  <ul style="list-style:none; padding:0; text-align:right; font-size:18px; line-height:1.8;">
    <li>🎨 تشكيلة واسعة من الألوان والديكورات</li>
    <li>🏠 خبرة في الفلل، الشقق، والمباني التجارية</li>
    <li>⏱ التزام كامل في المواعيد</li>
    <li>✅ جودة مضمونة باستخدام مواد أصلية</li>
    <li>🤝 رضا العميل هو أولويتنا</li>
  </ul>
</section>

  <!-- الخدمات -->
  <section id="services" class="services">
    <h2>الخدمات</h2>
    <ul>
      <li>دهانات واجهات خارجية مقاومة للعوامل الجوية</li>
      <li>دهانات داخلية بجميع الألوان والديكورات</li>
      <li>تنفيذ ديكورات زخرفية حديثة</li>
      <li>إصلاح وتجديد الواجهات</li>
      <li>استشارات احترافية في اختيار الألوان</li>
    </ul>
  </section>

  <!-- معرض الصور -->
  <section id="gallery">
    <h2>واجهات الأعمال</h2>
    <div class="gallery">
      <img src="Room1.jpg" alt="واجهة 1">
      <img src="Room2.jpg" alt="واجهة 2">
      <img src="Room3.jpg" alt="واجهة 3">
      <img src="Room4.jpg" alt="واجهة 4">
<img src="Room5.jpg" alt="واجهة 5">
    </div>
  </section>

  <!-- التواصل -->
  <section id="contact" class="contact">
    <h2>تواصل معنا</h2>
    <p>📞 الجوال: <strong>0544410752</strong></p>
    <p>
      💬 واتساب: 
      <a class="btn" href="https://wa.me/966544410752" target="_blank">تواصل عبر واتساب</a>
    </p>
  </section>

  <!-- الفوتر -->
  <footer>
    <p>© 2025 جميع الحقوق محفوظة — أبو أريج للدهانات</p>
  </footer>
</body>
</html>