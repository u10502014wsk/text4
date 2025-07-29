<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>法律AI分析系統</title>
<style>
/* 基本樣式 */
body {
background: #0e0e0e;
color: #f0f0f0;
font-family: "Segoe UI", sans-serif;
margin: 0;
line-height: 1.6;
}
header {
background: #111;
padding: 1rem 2rem;
display: flex;
justify-content: space-between;
align-items: center;
position: sticky;
top: 0;
z-index: 1000;
}
header h1 {
font-size: 1.5rem;
color: #00bcd4;
}
nav a {
color: #00bcd4;
margin-left: 1.5rem;
text-decoration: none;
font-weight: 500;
}
nav a:hover {
color: #fff;
}
.hero {
background: linear-gradient(145deg, #111, #222);
padding: 4rem 2rem;
text-align: center;
}
.hero h2 {
font-size: 2rem;
background: linear-gradient(90deg, #00bcd4, #0099cc);
-webkit-background-clip: text;
color: transparent;
}
.features {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 1.5rem;
padding: 3rem 2rem;
}
.card {
background: #1a1a1a;
padding: 1.5rem;
border-radius: 8px;
transition: transform 0.3s;
}
.card:hover {
transform: translateY(-5px);
}
.tech {
padding: 3rem 2rem;
background: #111;
}
.tech h2 {
text-align: center;
margin-bottom: 2rem;
}
.tech-list {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 1.5rem;
max-width: 800px;
margin: 0 auto;
}
.tech-item {
background: #1a1a1a;
padding: 1rem;
border-radius: 8px;
}
footer {
text-align: center;
padding: 2rem;
color: #666;
}
@media (max-width: 600px) {
header {
flex-direction: column;
align-items: flex-start;
}
nav {
margin-top: 1rem;
}
}
</style>
</head>
<body>
<header>
<h1>法律AI分析系統</h1>
<nav>
<a href="#features">功能</a>
<a href="#tech">技術</a>
<a href="#contact">聯絡</a>
</nav>
</header>
<section class="hero">
<h2>智能法律分析與案件分類解決方案</h2>
<p style="max-width: 600px; margin: 2rem auto; color: #ccc;">
利用自然語言處理與深度學習技術，提供車禍、智慧財產等案件類型自動分類與類案比對功能。
</p>
</section>
<section id="features" class="features">
<div class="card">
<h3>個人用戶</h3>
<p>輸入案件描述，即時獲得車禍、勞資糾紛等案件類型分類與相關法律建議。</p>
<button onclick="alert('功能即將開放！')">立即體驗</button>
</div>
<div class="card">
<h3>專業律師</h3>
<p>跨類型案件比對、快速定位類案、分析證據結構與訴訟策略。</p>
<button onclick="alert('功能即將開放！')">立即體驗</button>
</div>
<div class="card">
<h3>機構合作</h3>
<p>提供司法機關與律師事務所的大數據分析與案件管理解決方案。</p>
<button onclick="alert('功能即將開放！')">立即體驗</button>
</div>
</section>
<section id="tech" class="tech">
<h2>技術實現</h2>
<div class="tech-list">
<div class="tech-item">
<strong>中文語法分析</strong><br />
利用 HanLP 解析法律文本結構，提取主詞/行為/證據/法條。
</div>
<div class="tech-item">
<strong>主旨句提取</strong><br />
基於 BERT 模型，自動歸納判決書核心內容。
</div>
<div class="tech-item">
<strong>自動分類</strong><br />
按案件性質分類：車禍 → 智慧財產 → 勞資糾紛 → 土地買賣。
</div>
</div>
</section>
<footer id="contact">
<p>© 2024 法律AI分析系統. 保留所有權利。</p>
</footer>
</body>
</html>
