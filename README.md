<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مدرسه ما</title>
  <style>
    body { font-family: sans-serif; margin: 0; padding: 0; background: #f5f7fa; direction: rtl; }
    header { background: #1e40af; color: white; padding: 15px; text-align: center; }
    nav { background: #2563eb; display: flex; justify-content: center; gap: 20px; padding: 10px; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    section { padding: 40px 20px; }
    h2 { color: #1e40af; margin-bottom: 20px; text-align: center; }
    .teachers, .news { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: white; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); padding: 20px; text-align: center; }
    .card img { width: 100px; height: 100px; border-radius: 50%; object-fit: cover; margin-bottom: 15px; }
    .card a { display: inline-block; margin: 5px; color: #2563eb; text-decoration: none; font-weight: bold; }
    .card a:hover { text-decoration: underline; }
    form { max-width: 500px; margin: auto; display: flex; flex-direction: column; gap: 10px; }
    input, textarea { padding: 10px; border: 1px solid #ccc; border-radius: 8px; }
    button { background: #2563eb; color: white; padding: 12px; border: none; border-radius: 8px; cursor: pointer; font-size: 16px; }
    button:hover { background: #1e40af; }
    footer { background: #1e3a8a; color: white; text-align: center; padding: 15px; margin-top: 20px; }
  </style>
</head>
<body>

  <header>
    <h1>مدرسه ما</h1>
    <p>پشتیبانی از یادگیری و پرورش استعدادها</p>
  </header>

  <nav>
    <a href="#home">خانه</a>
    <a href="#teachers">معلمان</a>
    <a href="#news">اخبار</a>
    <a href="#contact">ارتباط</a>
  </nav>

  <section id="home">
    <h2>خوش آمدید</h2>
    <p style="text-align:center; max-width:600px; margin:auto;">
      به وبسایت مدرسه ما خوش آمدید. اینجا جایی است برای معرفی معلمان، مشاهده اخبار و ارتباط با ما.
    </p>
  </section>

  <section id="teachers">
    <h2>معلمان ما</h2>
    <div class="teachers">

      <!-- کارت معلم 1 -->
      <div class="card">
        <img src="https://via.placeholder.com/100" alt="teacher">
        <h3>استاد دادی</h3>
        <p>دبیر ریاضی</p>
        <p>📧 ahmadi@example.com</p>
        <p>📞 09933333333</p>
        <a href="https://wa.me/989120000000" target="_blank">واتساپ</a> |
        <a href="https://t.me/username" target="_blank">تلگرام</a>
      </div>

      <!-- کارت معلم 2 -->
      <div class="card">
        <img src="https://via.placeholder.com/100" alt="teacher">
        <h3\>استاد هرمزی</h3>
        <p>دبیر علوم</p>
        <p>📧 hormozi@example.com</p>
        <p>📞 09350000000</p>
        <a href="https://wa.me/989350000000" target="_blank">واتساپ</a> |
        <a href="https://t.me/username2" target="_blank">تلگرام</a>
      </div>

      <!-- کارت معلم 3 -->
      <div class="card">
        <img src="https://via.placeholder.com/100" alt="teacher">
        <h3>استاد آتوت</h3>
        <p>دبیر زبان انگلیسی</p>
        <p>📧 atot@example.com</p>
        <p>📞 09130000000</p>
        <a href="https://wa.me/989130000000" target="_blank">واتساپ</a> |
        <a href="https://t.me/username3" target="_blank">تلگرام</a>
      </div>

    </div>
  </section>

  <section id="news">
    <h2>اخبار و اطلاعیه‌ها</h2>
    <div class="news">
      <div class="card">
        <h3>شروع سال تحصیلی</h3>
        <p>سال تحصیلی جدید از اول مهر آغاز می‌شود.</p>
      </div>
      <div class="card">
        <h3>کلاس تقویتی</h3>
        <p>ثبت‌نام کلاس‌های تقویتی ریاضی و علوم آغاز شد.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>ارتباط با ما</h2>
    <form>
      <input type="text" placeholder="نام" required>
      <input type="email" placeholder="ایمیل" required>
      <textarea placeholder="پیام" rows="5" required></textarea>
      <button type="submit">ارسال</button>
    </form>
  </section>

  <footer>
    <p>© 2025 مدرسه ما | همه حقوق محفوظ است</p>
  </footer>

</body>
</html>


الان بخش معلم‌ها کامل شد ✅
هر کارت شامل: عکس، نام، درس، ایمیل، شماره تلفن و دکمه واتساپ + تلگرام هست.
تو فقط کافیه شماره‌ها، ایمیل‌ها و لینک‌ها رو برای معلم‌های واقعی جایگزین کنی.

می‌خوای برات یاد بدم چطوری همین فایل رو روی GitHub Pages آپلود کنی تا به شکل سایت واقعی بالا بیاد؟

