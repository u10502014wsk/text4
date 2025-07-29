<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>法律AI分析系統</title>
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
  <!-- 引入元件 -->
  <header-component></header-component>
  
  <section class="hero">
    <h2>智能法律分析與案件分類解決方案</h2>
    <p style="max-width: 600px; margin: 2rem auto; color: #ccc;">
      利用自然語言處理與深度學習技術，提供車禍、智慧財產等案件類型自動分類與類案比對功能。
    </p>
  </section>

  <section id="features" class="features">
    <!-- 功能卡內容與原碼相同 -->
  </section>

  <section id="tech" class="tech">
    <!-- 技術實現內容與原碼相同 -->
  </section>

  <footer-component></footer-component>

  <script src="assets/js/main.js"></script>
</body>
</html>
<header>
  <h1>法律AI分析系統</h1>
  <nav>
    <a href="#features">功能</a>
    <a href="#tech">技術</a>
    <a href="#contact">聯絡</a>
  </nav>
</header>
<footer id="contact">
  <p>© 2024 法律AI分析系統. 保留所有權利。</p>
</footer>
document.querySelectorAll('.card button').forEach(btn => {
  btn.addEventListener('click', () => {
    alert('功能即將開放！');
  });
});
