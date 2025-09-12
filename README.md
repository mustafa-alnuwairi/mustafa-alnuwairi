<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>CodeRush – بوابة التعلم</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    :root{--bg:#0d0d0d;--accent:#ff0040;--text:#f1f1f1;--card:#1a1a1a;}
    *{margin:0;padding:0;box-sizing:border-box;}
    body{font-family:'Cairo',sans-serif;background:var(--bg);color:var(--text);line-height:1.8;min-height:100vh;display:flex;flex-direction:column;}
    header{height:100vh;background:linear-gradient(135deg,#0d0d0d,#8b0000);display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:20px;}
    header h1{font-size:3rem;margin:.5rem 0;}
    header p{max-width:600px;font-size:1.2rem;}
    .btn{display:inline-block;padding:15px 35px;border:2px solid var(--accent);color:var(--accent);text-decoration:none;font-weight:700;border-radius:50px;transition:.4s;}
    .btn:hover{background:var(--accent);color:#fff;transform:translateY(-3px);}
    nav{position:fixed;top:0;width:100%;background:#00000090;backdrop-filter:blur(10px);padding:10px 20px;z-index:999;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;}
    nav .lang-switch select{padding:5px 10px;border-radius:20px;border:none;font-weight:700;}
    .lang-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:20px;max-width:900px;margin:40px auto;padding:0 20px;}
    .lang-card{background:var(--card);border-radius:15px;padding:20px;text-align:center;transition:.3s;}
    .lang-card:hover{transform:translateY(-5px);}
    .lang-card i{font-size:2.5rem;color:var(--accent);}
    .lang-card h3{margin:10px 0 0;font-size:1.1rem;}
    footer{background:#000;text-align:center;padding:20px;font-size:.9rem;}
  </style>
</head>

<body>
  <header>
    <h1>CodeRush</h1>
    <p>أول بوابة عربية لتعلّم 10 لغات برمجة – بدون تحميل، بدون تعقيد</p>
    <a href="#langs" class="btn">اختر لغتك الآن</a>
  </header>

  <!-- ===== شبكة اللغات الكاملة (10 لغات) ===== -->
  <section id="langs" class="lang-grid">
    <div class="lang-card"><a href="langs/html.html"><i class="fab fa-html5" style="color:#e34f26;"></i><h3>HTML</h3></a></div>
    <div class="lang-card"><a href="langs/css.html"><i class="fab fa-css3-alt" style="color:#1572b6;"></i><h3>CSS</h3></a></div>
    <div class="lang-card"><a href="langs/js.html"><i class="fab fa-js-square" style="color:#f7df1e;"></i><h3>JavaScript</h3></a></div>
    <div class="lang-card"><a href="langs/python.html"><i class="fab fa-python" style="color:#3776ab;"></i><h3>Python</h3></a></div>
    <div class="lang-card"><a href="langs/c-cpp.html"><i class="fas fa-code" style="color:#00599c;"></i><h3>C / C++</h3></a></div>
    <div class="lang-card"><a href="langs/sql.html"><i class="fas fa-database" style="color:#336791;"></i><h3>SQL</h3></a></div>
    <div class="lang-card"><a href="langs/java.html"><i class="fab fa-java" style="color:#f89820;"></i><h3>Java</h3></a></div>
    <div class="lang-card"><a href="langs/swift.html"><i class="fab fa-swift" style="color:#fa7343;"></i><h3>Swift</h3></a></div>
    <div class="lang-card"><a href="langs/go.html"><i class="fas fa-code" style="color:#00add8;"></i><h3>Go</h3></a></div>
    <div class="lang-card"><a href="langs/kotlin.html"><i class="fas fa-rocket" style="color:#7f52ff;"></i><h3>Kotlin</h3></a></div>
  </section>

  <footer>
    تحتاج مساعدة؟ تواصل عبر واتساب: <a href="https://wa.me/201001029046" style="color:var(--accent);">01001029046</a>
  </footer>
</body>
</html>
