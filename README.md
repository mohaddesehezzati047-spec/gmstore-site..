[index.html](https://github.com/user-attachments/files/25077736/index.html)
<!doctype html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>GM Store | طبیعت، نسخهٔ سلامت</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;600;700&family=Montserrat:wght@600;700&display=swap');
    body {
      margin: 0;
      font-family: 'Vazirmatn', sans-serif;
      background-color: #0B0B0B;
      color: #fff;
    }
    header {
      background: #0B0B0B;
      border-bottom: 2px solid #D4AF37;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
    }
    header h1 {
      color: #D4AF37;
      font-family: 'Montserrat', sans-serif;
      font-size: 1.8rem;
      margin: 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 0.8rem;
      font-weight: 600;
    }
    nav a:hover { color: #D4AF37; }
    .hero {
      background: linear-gradient(rgba(11,11,11,0.6), rgba(11,11,11,0.6)), url('https://images.unsplash.com/photo-1600431521340-491eca880813?auto=format&fit=crop&w=1400&q=60') center/cover;
      text-align: center;
      padding: 100px 20px;
    }
    .hero h2 { color: #D4AF37; font-size: 2.2rem; margin-bottom: 1rem; }
    .hero p { font-size: 1.1rem; color: #eee; }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
      background-color: #111;
    }
    .product {
      background-color: #1a1a1a;
      border: 1px solid #333;
      border-radius: 12px;
      padding: 1rem;
      text-align: center;
      transition: transform 0.2s;
      font-size: 1.1rem;
    }
    .product:hover { transform: translateY(-4px); }
    .product button {
      background-color: #D4AF37;
      color: #0B0B0B;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
      margin-top: 0.8rem;
    }
    .product button:hover { background-color: #b9922e; }
    footer {
      text-align: center;
      background: #0B0B0B;
      border-top: 1px solid #333;
      color: #999;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>GM Store</h1>
    <nav>

</header>
        
  <section class="hero">
    <h2>طبیعت، نسخهٔ سلامت</h2>
    <p>جدیدترین محصولات گیاهی و طبیعی برای تندرستی شما</p>
  </section>

  <section id="products" class="products">
    <div class="product">دهانشویه با عصاره عناب<button><p>قیمت: 70,000 تومان</p></div>
    <div class="product">دهانشویه با عصاره پونه کوهی<button><p>قیمت: 58,000 تومان</p></div>
    <div class="product">دهانشویه با عصاره به<button><p>قیمت:  65,000تومان</p></div>
    <div class="product">کوکی سلامت<button><p>قیمت: 25,000 تومان</p></div>
  <div class="product">پنکیک رژیمی<button><p>قیمت:  30,000تومان</p></div>
  <div class="product">صابون حلزون<button><p>قیمت: 150,000 تومان</p></div>
<div class="product">کیک سلامت<button><p>قیمت: 30,000 تومان</p></div>
<div class="product">شمع<button><p>قیمت: 50,000 تومان</p></div>
<div class="product">پاستیل<button><p>قیمت: 50,000 تومان</p></div>
<div class="product">دهانشویه با عصاره میخک<button><p>قیمت:  65,000تومان</p></div>
<div class="product">
  دهانشویه با عصاره دارچین
  <button><p>قیمت:  65,000تومان</p></div>
</div>
</section>
  <section id="about" style="padding:2rem; text-align:center; background:#111;">
    <h2 style="color:#D4AF37;">درباره GM Store</h2>
    <p style="max-width:600px; margin:auto; color:#ccc;">
      GM Store با الهام از طبیعت، مجموعه‌ای از محصولات گیاهی اصیل و باکیفیت را برای سلامت جسم و آرامش ذهن شما فراهم کرده است.
    </p>
  </section>

  <section id="contact" style="padding:2rem; text-align:center;">
<section id="order" style="padding:2rem; text-align:center;">
  <h2 style="color:#D4AF37;">ثبت سفارش</h2>
   <form action="https://formspree.io/f/xdkyalyl" method="POST" style="margin-top:1rem;">
    <input type="text" name="name" placeholder="نام شما" required
      style="padding:0.6rem;border-radius:6px;border:none;width:250px;"><br><br>

    <input type="email" name="email" placeholder="ایمیل شما" required
      style="padding:0.6rem;border-radius:6px;border:none;width:250px;"><br><br>

    <input type="text" name="product" placeholder="نام محصول"
      style="padding:0.6rem;border-radius:6px;border:none;width:250px;"><br><br>

    <button type="submit"
      style="background-color:#D4AF37;color:#0B0B0B;border:none;padding:0.6rem 1rem;border-radius:6px;font-weight:bold;cursor:pointer;">
      ارسال سفارش
    </button>
  </form>
</section>

    <p>برای سفارش یا مشاوره، فقط ایمیل خود را وارد کنید:</p>
    <form onsubmit="event.preventDefault();alert('با تشکر! درخواست شما ثبت شد.');" style="margin-top:1rem;">
      <input type="email" placeholder="ایمیل شما" required style="padding:0.6rem;border-radius:6px;border:none;width:250px;">
      <button type="submit" style="background-color:#D4AF37;color:#0B0B0B;border:none;padding:0.6rem 1rem;border-radius:6px;font-weight:bold;cursor:pointer;">ارسال</button>
    </form>
  </section>

  <footer> 2026 GM Store — طبیعت، نسخهٔ سلامت</footer>
<script>
  // فعال کردن اسکرول نرم برای لینک‌های ناوبری
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
      e.preventDefault();
      document.querySelector(this.getAttribute('href')).scrollIntoView({
        behavior: 'smooth'

</body>
</html>
