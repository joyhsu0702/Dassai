<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#171714">
<meta name="description" content="汰暄酒業｜獺祭季節限定預購。聖夜限定發泡濁酒、寒造早槽三割九分、元旦限定二割三分。">
<title>獺祭季節限定預購｜汰暄酒業 TaiXuan Online Wine</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Noto+Serif+TC:wght@400;500;600;700;900&display=swap" rel="stylesheet">

<style>
:root {
  --bg: #171714;
  --bg-soft: #211e1b;
  --cream: #f4efe5;
  --gold: #d7b777;
  --gold-light: #f2dba7;
  --wine: #722e3c;
  --muted: #bdb5a8;
  --line: rgba(215,183,119,.28);
  --sans: "DM Sans", "Noto Serif TC", sans-serif;
  --serif: "Noto Serif TC", serif;
}

* { box-sizing: border-box; }

html {
  scroll-behavior: smooth;
  scroll-padding-top: 80px;
}

body {
  margin: 0;
  background: var(--bg);
  color: var(--cream);
  font-family: var(--sans);
  line-height: 1.85;
  -webkit-font-smoothing: antialiased;
}

a { color: inherit; text-decoration: none; }

button, a { -webkit-tap-highlight-color: transparent; }

img {
  display: block;
  max-width: 100%;
}

.container {
  width: min(1120px, calc(100% - 48px));
  margin-inline: auto;
}

.eyebrow {
  color: var(--gold);
  font-size: 11px;
  font-weight: 600;
  letter-spacing: .28em;
  text-transform: uppercase;
}

.section-heading {
  text-align: center;
  margin-bottom: 52px;
}

.section-heading h2 {
  margin: 12px 0;
  font-family: var(--serif);
  font-size: clamp(26px, 4vw, 42px);
  font-weight: 500;
  letter-spacing: .12em;
  line-height: 1.5;
}

.section-heading p {
  color: var(--muted);
  font-size: 13px;
  letter-spacing: .08em;
}

/* Navigation */

.nav {
  position: absolute;
  z-index: 20;
  inset: 0 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding: 22px 5%;
  border-bottom: 1px solid rgba(255,255,255,.12);
}

.brand {
  font-family: var(--serif);
  font-size: 16px;
  letter-spacing: .13em;
}

.brand small {
  display: block;
  color: var(--gold);
  font-family: var(--sans);
  font-size: 9px;
  letter-spacing: .22em;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 25px;
  font-size: 12px;
  color: #e5ded2;
}

.nav-links a:not(.nav-cta):hover {
  color: var(--gold-light);
}

.nav-cta {
  padding: 9px 17px;
  border: 1px solid var(--gold);
  color: var(--gold-light);
  transition: .25s;
}

.nav-cta:hover {
  background: var(--gold);
  color: var(--bg);
}

/* Hero */

.hero {
  position: relative;
  min-height: 760px;
  min-height: min(900px, 100svh);
  display: flex;
  align-items: center;
  overflow: hidden;
  background: #191815;
}

.hero-bg {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
  opacity: .57;
}

.hero::after {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(90deg, rgba(18,17,15,.96) 0%, rgba(18,17,15,.78) 42%, rgba(18,17,15,.22) 100%),
    linear-gradient(0deg, var(--bg) 0%, transparent 27%, transparent 85%, rgba(0,0,0,.35) 100%);
}

.hero-content {
  position: relative;
  z-index: 2;
  width: min(1120px, calc(100% - 48px));
  margin: 65px auto 0;
  padding-block: 70px;
}

.hero-kicker {
  display: flex;
  align-items: center;
  gap: 12px;
  color: var(--gold-light);
  font-size: 11px;
  letter-spacing: .3em;
}

.hero-kicker::before {
  content: "";
  width: 38px;
  height: 1px;
  background: var(--gold);
}

.hero h1 {
  margin: 28px 0 22px;
  font-family: var(--serif);
  font-size: clamp(43px, 7vw, 82px);
  font-weight: 500;
  line-height: 1.35;
  letter-spacing: .1em;
}

.hero h1 span {
  display: block;
  color: var(--gold-light);
}

.hero-description {
  max-width: 460px;
  color: #e3dace;
  font-size: 14px;
  letter-spacing: .1em;
  line-height: 2.2;
}

.hero-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 10px 24px;
  margin-top: 25px;
  color: var(--muted);
  font-size: 11px;
  letter-spacing: .1em;
}

.hero-meta span::before {
  content: "✦";
  margin-right: 8px;
  color: var(--gold);
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-top: 38px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 12px;
  min-height: 51px;
  padding: 13px 25px;
  border: 1px solid transparent;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: .1em;
  cursor: pointer;
  transition: transform .25s, background .25s, color .25s;
}

.btn:hover {
  transform: translateY(-2px);
}

.btn-gold {
  background: var(--gold-light);
  color: #21190e;
}

.btn-gold:hover {
  background: #fff0c8;
}

.btn-outline {
  border-color: rgba(244,239,229,.55);
  color: var(--cream);
}

.btn-outline:hover {
  border-color: var(--gold);
  color: var(--gold-light);
}

.hero-note {
  margin-top: 24px;
  color: #c4b9a7;
  font-size: 11px;
  letter-spacing: .08em;
}

/* Announcement */

.announcement {
  padding: 22px 20px;
  background: var(--wine);
  text-align: center;
  color: #fff4e7;
  font-size: 12px;
  letter-spacing: .08em;
}

.announcement strong {
  color: #f6dba8;
}

/* Intro */

.intro {
  padding: 110px 0 85px;
  text-align: center;
}

.intro-copy {
  max-width: 680px;
  margin: 24px auto 0;
  color: var(--muted);
  font-size: 14px;
  line-height: 2.2;
}

.intro-mark {
  width: 50px;
  height: 1px;
  margin: 30px auto;
  background: var(--gold);
}

/* Products */

.products {
  padding: 45px 0 110px;
}

.product-card {
  display: grid;
  grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
  align-items: stretch;
  margin-bottom: 78px;
  border: 1px solid var(--line);
  background: linear-gradient(135deg, #211f1b, #191815);
  overflow: hidden;
}

.product-card:nth-of-type(even) .product-image {
  order: 2;
}

.product-image {
  position: relative;
  min-width: 0;
  background: #28231e;
  overflow: hidden;
}

.product-image img {
  width: 100%;
  height: 100%;
  aspect-ratio: 1045 / 1567;
  object-fit: contain;
  object-position: center;
  transition: transform .65s ease;
}

.product-card:hover .product-image img {
  transform: scale(1.025);
}

.image-placeholder {
  position: absolute;
  inset: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 12px;
  padding: 25px;
  color: #bfb09a;
  background:
    radial-gradient(ellipse at center, #393028 0%, #24211d 70%);
  text-align: center;
  pointer-events: none;
}

.image-placeholder strong {
  font-family: var(--serif);
  font-size: 22px;
  font-weight: 400;
  letter-spacing: .12em;
}

.image-placeholder span {
  font-size: 10px;
  letter-spacing: .16em;
}

.product-image.has-image .image-placeholder {
  display: none;
}

.product-info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: clamp(25px, 5vw, 58px);
}

.product-number {
  color: var(--gold);
  font-family: var(--sans);
  font-size: 11px;
  letter-spacing: .24em;
}

.product-release {
  align-self: flex-start;
  margin: 16px 0 12px;
  padding: 4px 10px;
  border: 1px solid rgba(215,183,119,.4);
  color: var(--gold-light);
  font-size: 10px;
  letter-spacing: .1em;
}

.product-info h3 {
  margin: 0;
  font-family: var(--serif);
  font-size: clamp(23px, 2.6vw, 33px);
  font-weight: 500;
  line-height: 1.6;
}

.product-en {
  margin-top: 9px;
  color: #b5a995;
  font-size: 10px;
  letter-spacing: .15em;
  line-height: 1.8;
}

.product-rule {
  width: 45px;
  height: 1px;
  margin: 25px 0;
  background: var(--gold);
}

.product-tagline {
  margin: 0 0 18px;
  color: var(--gold-light);
  font-family: var(--serif);
  font-size: 17px;
  line-height: 1.8;
}

.product-description {
  margin: 0;
  color: #c9c1b5;
  font-size: 13px;
  line-height: 2.15;
}

.tasting-notes {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 22px;
}

.tasting-notes span {
  padding: 5px 10px;
  border: 1px solid rgba(244,239,229,.16);
  color: #e4d8c4;
  font-size: 10px;
}

.price-area {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 15px;
  margin-top: 32px;
  padding-top: 23px;
  border-top: 1px solid var(--line);
}

.price-label {
  display: block;
  color: var(--muted);
  font-size: 10px;
  letter-spacing: .1em;
}

.original-price {
  margin-top: 3px;
  color: #aaa196;
  font-size: 14px;
  text-decoration: line-through;
}

.sale-label {
  display: block;
  margin-top: 12px;
  color: var(--gold);
  font-size: 10px;
  letter-spacing: .1em;
}

.sale-price {
  color: var(--gold-light);
  font-family: var(--sans);
  font-size: clamp(31px, 3.5vw, 42px);
  font-weight: 600;
  line-height: 1.35;
  white-space: nowrap;
}

.sale-price small {
  font-size: 12px;
  font-weight: 400;
}

.saving {
  margin-top: 6px;
  color: #cdbb99;
  font-size: 11px;
}

.product-action {
  margin-top: 25px;
}

.product-action .btn {
  width: 100%;
}

/* Preorder */

.preorder {
  position: relative;
  padding: 95px 0;
  background: #eae1d2;
  color: #29221b;
  text-align: center;
}

.preorder .eyebrow {
  color: #7a5433;
}

.preorder h2 {
  margin: 15px 0;
  font-family: var(--serif);
  font-size: clamp(28px, 4vw, 42px);
  font-weight: 500;
  letter-spacing: .1em;
}

.preorder p {
  max-width: 580px;
  margin: 0 auto;
  color: #65594b;
  font-size: 13px;
  line-height: 2.1;
}

.preorder .btn {
  margin-top: 28px;
  background: #8d3d32;
  color: #fff7e9;
}

.preorder .btn:hover {
  background: #692a24;
}

.preorder-small {
  margin-top: 16px !important;
  font-size: 11px !important;
}

/* Contact */

.contact {
  padding: 95px 0 65px;
  text-align: center;
}

.contact h2 {
  margin: 13px 0;
  font-family: var(--serif);
  font-size: clamp(28px, 4vw, 40px);
  font-weight: 500;
  letter-spacing: .12em;
}

.contact-intro {
  color: var(--muted);
  font-size: 13px;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1px;
  margin: 42px 0;
  border: 1px solid var(--line);
  background: var(--line);
}

.contact-item {
  padding: 27px 15px;
  background: var(--bg);
}

.contact-item span {
  display: block;
  color: var(--gold);
  font-size: 10px;
  letter-spacing: .18em;
}

.contact-item p {
  margin: 10px 0 0;
  color: #e7ded0;
  font-size: 13px;
  overflow-wrap: anywhere;
}

.site-notice {
  max-width: 700px;
  margin: 0 auto 28px;
  padding: 17px 20px;
  border: 1px solid rgba(215,183,119,.3);
  color: #d8cbb8;
  font-size: 12px;
  line-height: 2;
}

.site-notice strong {
  color: var(--gold-light);
}

.contact-actions {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 13px;
}

.contact-actions .btn {
  min-width: 210px;
}

/* Footer */

.footer {
  padding: 28px 20px 105px;
  border-top: 1px solid var(--line);
  text-align: center;
}

.footer-brand {
  font-family: var(--serif);
  font-size: 14px;
  letter-spacing: .16em;
}

.footer-en {
  margin-top: 6px;
  color: #a99c89;
  font-size: 9px;
  letter-spacing: .22em;
}

.footer-legal {
  margin-top: 24px;
  color: #bcb1a0;
  font-size: 10px;
  letter-spacing: .1em;
}

/* Floating consultation */

.floating-cta {
  position: fixed;
  z-index: 100;
  right: 22px;
  bottom: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  min-height: 55px;
  padding: 0 23px;
  border: 1px solid #fff0c9;
  border-radius: 3px;
  background: #e8c77f;
  color: #24180c;
  box-shadow: 0 8px 32px rgba(0,0,0,.35);
  font-size: 13px;
  font-weight: 700;
  letter-spacing: .06em;
  transition: .25s;
}

.floating-cta:hover {
  background: #fff0c9;
  transform: translateY(-3px);
}

.floating-cta svg {
  width: 19px;
  height: 19px;
  flex: 0 0 auto;
}

/* Entrance animation */

.reveal {
  opacity: 0;
  transform: translateY(22px);
  transition: opacity .7s ease, transform .7s ease;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    scroll-behavior: auto !important;
    transition-duration: .01ms !important;
    animation-duration: .01ms !important;
  }

  .reveal {
    opacity: 1;
    transform: none;
  }
}

@media (max-width: 760px) {
  .container { width: min(100% - 32px, 560px); }

  .nav {
    padding: 17px 20px;
  }

  .brand { font-size: 14px; }

  .nav-links { gap: 0; }

  .nav-links a:not(.nav-cta) { display: none; }

  .nav-cta {
    padding: 8px 12px;
    font-size: 11px;
  }

  .hero {
    min-height: 760px;
    min-height: 94svh;
  }

  .hero-bg {
    object-position: 60% center;
  }

  .hero::after {
    background:
      linear-gradient(90deg, rgba(18,17,15,.88), rgba(18,17,15,.52)),
      linear-gradient(0deg, var(--bg) 0%, transparent 35%);
  }

  .hero-content {
    width: calc(100% - 40px);
    margin-top: 55px;
    padding-block: 55px;
  }

  .hero h1 {
    font-size: clamp(39px, 10vw, 58px);
    letter-spacing: .06em;
  }

  .hero-description {
    max-width: 390px;
    font-size: 13px;
  }

  .hero-actions .btn {
    flex: 1 1 145px;
    padding-inline: 12px;
  }

  .intro { padding: 78px 0 55px; }

  .section-heading { margin-bottom: 35px; }

  .products { padding: 30px 0 65px; }

  .product-card {
    grid-template-columns: 1fr;
    margin-bottom: 45px;
  }

  .product-card:nth-of-type(even) .product-image {
    order: 0;
  }

  .product-image img {
    width: min(100%, 470px);
    height: auto;
    margin: 0 auto;
    aspect-ratio: 1045 / 1567;
    object-fit: contain;
  }

  .product-info {
    padding: 28px 23px 30px;
  }

  .product-info h3 { font-size: 27px; }

  .price-area { gap: 10px; }

  .sale-price { font-size: 34px; }

  .preorder { padding: 72px 0; }

  .contact { padding: 72px 0 45px; }

  .contact-grid { grid-template-columns: 1fr; }

  .contact-item { padding: 19px 12px; }

  .contact-item p { margin-top: 5px; }

  .floating-cta {
    right: 14px;
    bottom: 14px;
    min-height: 51px;
    padding: 0 17px;
    font-size: 12px;
  }

  .footer { padding-bottom: 90px; }
}

@media (max-width: 380px) {
  .hero h1 { font-size: 36px; }

  .hero-actions { flex-direction: column; }

  .price-area {
    align-items: flex-start;
    flex-direction: column;
  }

  .sale-price { font-size: 36px; }
}
</style>
</head>

<body>

<!-- 導覽列 -->
<header class="nav">
  <a class="brand" href="#top">
    汰暄酒業
    <small>TAIXUAN ONLINE WINE</small>
  </a>

  <nav class="nav-links" aria-label="主要導覽">
    <a href="#products">限定酒款</a>
    <a href="#contact">聯絡我們</a>
    <a class="nav-cta" href="https://reurl.cc/dO1Rey"
       target="_blank" rel="noopener noreferrer">立即洽詢 ↗</a>
  </nav>
</header>

<main id="top">

<!-- Hero 主視覺
     將 hero.jpg 放在 index.html 同一資料夾。
     建議圖片尺寸：1920 × 1080 px。
-->
<section class="hero">
  <img class="hero-bg" src="./hero.jpg"
       alt="獺祭季節限定清酒預購主視覺"
       fetchpriority="high"
       onerror="this.style.display='none'">

  <div class="hero-content">
    <div class="hero-kicker">SEASONAL SAKE COLLECTION</div>

    <h1>
      獺祭
      <span>季節限定預購</span>
    </h1>

    <p class="hero-description">
      為冬日與新年，預留一份值得期待的清酒時光。<br>
      從聖夜的細緻氣泡，到新年限定的純米大吟釀，<br>
      三款季節之選，為重要時刻留下風味記憶。
    </p>

    <div class="hero-meta">
      <span>三款季節限定</span>
      <span>限量預購</span>
      <span>汰暄酒業精選</span>
    </div>

    <div class="hero-actions">
      <a class="btn btn-gold" href="#products">
        探索限定酒款 <span>↓</span>
      </a>
      <a class="btn btn-outline"
         href="https://reurl.cc/dO1Rey"
         target="_blank" rel="noopener noreferrer">
        預購與庫存洽詢 ↗
      </a>
    </div>

    <p class="hero-note">
      ※ 預計到貨時間依各酒款標示，實際到貨以供應情況為準。
    </p>
  </div>
</section>

<div class="announcement">
  <strong>SEASONAL PRE-ORDER</strong>
  &nbsp; 三款季節限定・即日起開放預購洽詢
</div>

<!-- 品牌引言 -->
<section class="intro container reveal">
  <div class="eyebrow">A MOMENT WORTH CELEBRATING</div>
  <h2 class="section-heading" style="margin:0">
    讓每一場相聚，<br>都有值得珍藏的理由。
  </h2>
  <div class="intro-mark"></div>
  <p class="intro-copy">
    聖誕晚餐、新年團聚，或是獻給重要之人的一份心意。
    獺祭以不同季節限定酒款，為冬日餐桌帶來多一分期待。
    三款風格各異的季節之選，現在就為喜愛的酒款預留名額。
  </p>
</section>

<!-- 三款商品 -->
<section class="products" id="products">
  <div class="container">

    <div class="section-heading reveal">
      <div class="eyebrow">THE LIMITED COLLECTION</div>
      <h2>三款限定・依季節而生</h2>
      <p>Seasonal Releases · Pre-order Prices</p>
    </div>

    <!-- 酒款 01
         圖片尺寸 1045 × 1567 px
         請將圖片命名為 dassai-christmas.jpg
    -->
    <article class="product-card reveal">
      <div class="product-image">
        <img src="./dassai-christmas.jpg"
             alt="獺祭 聖夜限定 純米大吟釀二割三分 發泡濁酒"
             loading="lazy"
             onload="this.parentElement.classList.add('has-image')"
             onerror="this.style.display='none'">
        <div class="image-placeholder">
          <strong>聖夜限定</strong>
          <span>IMAGE 01 · 1045 × 1567 PX</span>
          <span>請放入 dassai-christmas.jpg</span>
        </div>
      </div>

      <div class="product-info">
        <div class="product-number">01 / CHRISTMAS EDITION</div>
        <div class="product-release">預計 12 月下旬到貨</div>

        <h3>獺祭 聖夜限定<br>純米大吟釀二割三分 發泡濁酒</h3>

        <div class="product-en">
          DASSAI CHRISTMAS LIMITED<br>
          JUNMAI DAIGINJO 23% SPARKLING NIGORI
        </div>

        <div class="product-rule"></div>

        <p class="product-tagline">
          聖誕限定・如香檳般細緻的氣泡。
        </p>

        <p class="product-description">
          嚴選山田錦，精米至 23%，以瓶內二次發酵工法
          打造細緻氣泡。淡雅桃香與蜂蜜般的香甜氣息交織，
          綿密氣泡伴隨優雅口感，為節慶餐桌增添迷人風采。
          適合聖誕聚會、浪漫晚餐與精緻節慶贈禮。
        </p>

        <div class="tasting-notes">
          <span>山田錦・精米 23%</span>
          <span>瓶內二次發酵</span>
          <span>細緻氣泡</span>
          <span>桃香・蜂蜜香</span>
        </div>

        <div class="price-area">
          <div>
            <span class="price-label">建議售價</span>
            <div class="original-price">NT$ 4,380 / 瓶</div>
            <span class="sale-label">季節限定預購價</span>
          </div>
          <div style="text-align:right">
            <div class="sale-price">3,900<small> 元</small></div>
            <div class="saving">每瓶現省 NT$ 480</div>
          </div>
        </div>

        <div class="product-action">
          <a class="btn btn-gold"
             href="https://reurl.cc/dO1Rey"
             target="_blank" rel="noopener noreferrer">
            洽詢聖夜限定預購 <span>↗</span>
          </a>
        </div>
      </div>
    </article>

    <!-- 酒款 02
         圖片尺寸 1045 × 1567 px
         請將圖片命名為 dassai-hayazoe.jpg
    -->
    <article class="product-card reveal">
      <div class="product-image">
        <img src="./dassai-hayazoe.jpg"
             alt="獺祭 寒造早槽 三割九分"
             loading="lazy"
             onload="this.parentElement.classList.add('has-image')"
             onerror="this.style.display='none'">
        <div class="image-placeholder">
          <strong>寒造早槽</strong>
          <span>IMAGE 02 · 1045 × 1567 PX</span>
          <span>請放入 dassai-hayazoe.jpg</span>
        </div>
      </div>

      <div class="product-info">
        <div class="product-number">02 / WINTER EDITION</div>
        <div class="product-release">預計 1 月中旬到貨</div>

        <h3>獺祭<br>寒造早槽 三割九分</h3>

        <div class="product-en">
          DASSAI HAYAZOE<br>
          JUNMAI DAIGINJO 39%
        </div>

        <div class="product-rule"></div>

        <p class="product-tagline">
          冬季限定・收藏生酒的鮮活風味。
        </p>

        <p class="product-description">
          以生酒風格呈現清新而富有活力的香氣，
          展現奔放華麗的氣息與爽快口感。
          細膩香氣與鮮活層次相互交織，
          為喜愛新鮮感與清酒細節的品飲者，
          帶來值得期待的冬季限定體驗。
        </p>

        <div class="tasting-notes">
          <span>三割九分・精米 39%</span>
          <span>生酒風格</span>
          <span>清新爽快</span>
          <span>香氣鮮活</span>
        </div>

        <div class="price-area">
          <div>
            <span class="price-label">建議售價</span>
            <div class="original-price">NT$ 1,950 / 瓶</div>
            <span class="sale-label">季節限定預購價</span>
          </div>
          <div style="text-align:right">
            <div class="sale-price">1,750<small> 元</small></div>
            <div class="saving">每瓶現省 NT$ 200</div>
          </div>
        </div>

        <div class="product-action">
          <a class="btn btn-gold"
             href="https://reurl.cc/dO1Rey"
             target="_blank" rel="noopener noreferrer">
            洽詢寒造早槽預購 <span>↗</span>
          </a>
        </div>
      </div>
    </article>

    <!-- 酒款 03
         圖片尺寸 1045 × 1567 px
         請將圖片命名為 dassai-newyear.jpg
    -->
    <article class="product-card reveal">
      <div class="product-image">
        <img src="./dassai-newyear.jpg"
             alt="獺祭元旦限定 純米大吟釀二割三分"
             loading="lazy"
             onload="this.parentElement.classList.add('has-image')"
             onerror="this.style.display='none'">
        <div class="image-placeholder">
          <strong>元旦限定</strong>
          <span>IMAGE 03 · 1045 × 1567 PX</span>
          <span>請放入 dassai-newyear.jpg</span>
        </div>
      </div>

      <div class="product-info">
        <div class="product-number">03 / NEW YEAR EDITION</div>
        <div class="product-release">預計 1 月中下旬到貨</div>

        <h3>獺祭元旦限定<br>純米大吟釀 二割三分</h3>

        <div class="product-en">
          DASSAI NEW YEAR LIMITED<br>
          JUNMAI DAIGINJO 23%
        </div>

        <div class="product-rule"></div>

        <p class="product-tagline">
          以一瓶獺祭，迎接新年的美好。
        </p>

        <p class="product-description">
          嚴選山田錦，精米至 23%，展現高精米度帶來的
          細緻與優雅。旨味甜馥、酒體豐潤飽滿，
          口感細膩，餘韻優雅悠長。
          無論新年團聚、重要宴席，或贈予親友與重要客戶，
          都是一份充滿心意的節慶之選。
        </p>

        <div class="tasting-notes">
          <span>山田錦・精米 23%</span>
          <span>純米大吟釀</span>
          <span>豐潤旨味</span>
          <span>優雅悠長</span>
        </div>

        <div class="price-area">
          <div>
            <span class="price-label">建議售價</span>
            <div class="original-price">NT$ 5,290 / 瓶</div>
            <span class="sale-label">季節限定預購價</span>
          </div>
          <div style="text-align:right">
            <div class="sale-price">4,800<small> 元</small></div>
            <div class="saving">每瓶現省 NT$ 490</div>
          </div>
        </div>

        <div class="product-action">
          <a class="btn btn-gold"
             href="https://reurl.cc/dO1Rey"
             target="_blank" rel="noopener noreferrer">
            洽詢元旦限定預購 <span>↗</span>
          </a>
        </div>
      </div>
    </article>

  </div>
</section>

<!-- 預購 CTA -->
<section class="preorder">
  <div class="container reveal">
    <div class="eyebrow">RESERVE YOUR SEASONAL SELECTION</div>
    <h2>限定的季節，值得提前珍藏。</h2>
    <p>
      三款獺祭季節限定酒款，依各自時程陸續到貨。<br>
      歡迎聯絡汰暄酒業，洽詢預購、數量與到貨安排。
    </p>

    <a class="btn"
       href="https://reurl.cc/dO1Rey"
       target="_blank" rel="noopener noreferrer">
      立即洽詢・預留心儀酒款 ↗
    </a>

    <p class="preorder-small">
      限定酒款數量與供貨情況依實際供應為準。
    </p>
  </div>
</section>

<!-- 聯絡資訊 -->
<section class="contact" id="contact">
  <div class="container reveal">
    <div class="eyebrow">CONTACT & CONSULTATION</div>
    <h2>汰暄酒業</h2>
    <p class="contact-intro">
      您的精品酒款選品與預購諮詢夥伴
    </p>

    <div class="contact-grid">
      <div class="contact-item">
        <span>PHONE</span>
        <p><a href="tel:0223650988">02-2365-0988</a></p>
      </div>

      <div class="contact-item">
        <span>ADDRESS</span>
        <p>台北市大安區新生南路三段20號之一 1F</p>
      </div>

      <div class="contact-item">
        <span>BUSINESS HOURS</span>
        <p>09:00–17:00<br>週末及例假日公休</p>
      </div>
    </div>

    <div class="site-notice">
      <strong>官網暫時維護中</strong><br>
      官網預計下週一恢復正常使用。維護期間，
      歡迎透過下方線上洽詢按鈕，直接聯絡汰暄酒業，
      詢問酒款資訊與預購事宜。
    </div>

    <div class="contact-actions">
      <a class="btn btn-gold"
         href="https://reurl.cc/dO1Rey"
         target="_blank" rel="noopener noreferrer">
        線上預購洽詢 ↗
      </a>

      <a class="btn btn-outline" href="tel:0223650988">
        <span>☎</span> 直接致電
      </a>
    </div>
  </div>
</section>

</main>

<footer class="footer">
  <div class="footer-brand">汰暄酒業</div>
  <div class="footer-en">TAIXUAN ONLINE WINE · FINE WINE · EXCEPTIONAL LIFE</div>
  <div class="footer-legal">
    未滿十八歲禁止飲酒｜飲酒過量，有害健康
  </div>
</footer>

<!-- 全站右側固定洽詢按鈕 -->
<a class="floating-cta"
   href="https://reurl.cc/dO1Rey"
   target="_blank"
   rel="noopener noreferrer"
   aria-label="立即聯絡汰暄酒業進行獺祭預購洽詢">

  <svg viewBox="0 0 24 24" fill="none"
       stroke="currentColor" stroke-width="1.8"
       stroke-linecap="round" stroke-linejoin="round"
       aria-hidden="true">
    <path d="M21 11.5a8.4 8.4 0 0 1-.9 3.8
      8.5 8.5 0 0 1-7.6 4.7
      8.4 8.4 0 0 1-3.8-.9L3 21l1.9-5.7
      A8.4 8.4 0 0 1 4 11.5
      8.5 8.5 0 0 1 8.7 3.9
      8.4 8.4 0 0 1 12.5 3h.5
      a8.5 8.5 0 0 1 8 8.5Z"/>
  </svg>

  <span>立即預購洽詢</span>
  <span aria-hidden="true">↗</span>
</a>

<script>
/* 滾動顯示動畫 */
(function () {
  const elements = document.querySelectorAll(".reveal");

  if (!("IntersectionObserver" in window)) {
    elements.forEach(function (element) {
      element.classList.add("visible");
    });
    return;
  }

  const observer = new IntersectionObserver(function (entries) {
    entries.forEach(function (entry) {
      if (entry.isIntersecting) {
        entry.target.classList.add("visible");
        observer.unobserve(entry.target);
      }
    });
  }, {
    threshold: 0.08,
    rootMargin: "0px 0px -35px 0px"
  });

  elements.forEach(function (element) {
    observer.observe(element);
  });
})();
</script>

</body>
</html>
