<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>[ابراهيم] | موقعي الشخصي</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: #0b1120;
      color: white;
      line-height: 1.8;
    }

    /* Navbar */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      padding: 15px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(11, 17, 32, 0.9);
      backdrop-filter: blur(10px);
      z-index: 1000;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #38bdf8;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-right: 20px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #38bdf8;
    }

    /* Hero */
    .hero {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 100px 20px 50px;
      background: radial-gradient(circle at top, #172554, #0b1120 60%);
    }

    .profile {
      max-width: 750px;
    }

    .profile img {
      width: 170px;
      height: 170px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #38bdf8;
      box-shadow: 0 0 35px rgba(56, 189, 248, 0.4);
      margin-bottom: 20px;
    }

    .profile h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .profile h1 span {
      color: #38bdf8;
    }

    .profile h2 {
      color: #94a3b8;
      font-size: 22px;
      margin-bottom: 20px;
    }

    .profile p {
      color: #cbd5e1;
      font-size: 18px;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #38bdf8;
      color: #06101d;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 25px rgba(56, 189, 248, 0.35);
    }

    /* Sections */
    section {
      padding: 90px 8%;
    }

    .section-title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 45px;
    }

    .section-title span {
      color: #38bdf8;
    }

    .about {
      max-width: 850px;
      margin: auto;
      text-align: center;
      color: #cbd5e1;
      font-size: 18px;
    }

    /* Skills */
    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      max-width: 900px;
      margin: auto;
    }

    .skill {
      background: #111827;
      padding: 25px;
      text-align: center;
      border-radius: 15px;
      border: 1px solid #1e293b;
      transition: 0.3s;
    }

    .skill:hover {
      transform: translateY(-5px);
      border-color: #38bdf8;
    }

    .skill h3 {
      color: #38bdf8;
      margin-bottom: 8px;
    }

    /* Contact */
    .contact {
      max-width: 700px;
      margin: auto;
      text-align: center;
    }

    .contact p {
      color: #cbd5e1;
      margin: 12px;
    }

    .contact a {
      color: #38bdf8;
      text-decoration: none;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 25px;
      background: #070c16;
      color: #64748b;
    }

    /* Mobile */
    @media (max-width: 600px) {
      nav {
        padding: 12px 5%;
      }

      nav a {
        margin-right: 8px;
        font-size: 13px;
      }

      .profile h1 {
        font-size: 36px;
      }

      .profile h2 {
        font-size: 18px;
      }

      .profile p {
        font-size: 16px;
      }

      section {
        padding: 70px 5%;
      }
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <nav>
    <div class="logo">[ابراهيم]</div>

    <div>
      <a href="#home">الرئيسية</a>
      <a href="#about">عني</a>
      <a href="#skills">مهاراتي</a>
      <a href="#contact">تواصل</a>
    </div>
  </nav>


  <!-- Home -->
  <section class="hero" id="home">

    <div class="profile">

      <!-- ضع صورتك باسم photo.jpg -->
      <img src="photo.jpg" alt="صورة [ابراهيم]">

      <h1>مرحباً، أنا <span>[ابراهيم]</span></h1>

      <h2>[طالب / مبرمج / مصمم / مطور ويب]</h2>

      <p>
        أنا شخص مهتم بالتكنولوجيا والبرمجة وتطوير مهاراتي.
        أعمل دائماً على تعلم أشياء جديدة وإنشاء مشاريع مفيدة.
      </p>

      <a href="#contact" class="btn">تواصل معي</a>

    </div>

  </section>


  <!-- About -->
  <section id="about">

    <h2 class="section-title">نبذة <span>عني</span></h2>

    <div class="about">
      <p>
        اسمي <strong>[ابراهيم]</strong>، أعيش في [مراكش] بالمغرب.
        أحب تعلم البرمجة والتكنولوجيا والعمل على تطوير نفسي.
        هدفي هو اكتساب مهارات قوية وإنشاء مشاريع مميزة في المستقبل.
      </p>
    </div>

  </section>


  <!-- Skills -->
  <section id="skills">

    <h2 class="section-title">مهاراتي</h2>

    <div class="skills">

      <div class="skill">
        <h3>HTML</h3>
        <p>إنشاء صفحات الويب</p>
      </div>

      <div class="skill">
        <h3>CSS</h3>
        <p>تصميم وتنسيق المواقع</p>
      </div>

      <div class="skill">
        <h3>JavaScript</h3>
        <p>إضافة التفاعل للمواقع</p>
      </div>

      <div class="skill">
        <h3>GitHub</h3>
        <p>إدارة ونشر المشاريع</p>
      </div>

    </div>

  </section>


  <!-- Contact -->
  <section id="contact">

    <h2 class="section-title">تواصل <span>معي</span></h2>

    <div class="contact">

      <p>📧 البريد الإلكتروني:</p>
      <p>
        <a href="mailto:[elaouniaibrahim2@gmail.com]">[elaouniaibrahim2@gmail.com]</a>
      </p>

      <p>💻 GitHub:</p>
      <p>
        <a href="[رابط حساب GitHub]">
          حسابي على GitHub
        </a>
      </p>

    </div>

  </section>


  <!-- Footer -->
  <footer>
    © 2026 [Brahim] — جميع الحقوق محفوظة
  </footer>

</body>
</html>