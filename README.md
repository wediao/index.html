<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>星巴克中秋禮盒型錄</title>
  <style>
    :root{
      --brand:#0b5e3c;    /* 松針綠 */
      --brand-2:#1f8a70;  /* 青綠 */
      --ink:#4a3b2a;      /* 深咖 */
      --bg:#fffaf3;       /* 奶油米白 */
      --card:#ffffff;
      --moon:#ffd87a;     /* 明月金 */
      --dusk:#ffb5a7;     /* 晚霞粉 */
      --warn:#b71c1c;     /* 警示紅 */
      --section1:#fff7ec; /* 月光系列底 */
      --section2:#f3fbf7; /* 咖啡禮盒底 */
      --section3:#fbf6ef; /* 咖啡豆底 */
      --section4:#f4f7ff; /* 餅乾蛋捲底 */
    }
    *{box-sizing:border-box;}
    body{margin:0;font-family:"Microsoft JhengHei",system-ui,Arial;background:var(--bg);color:#333;}
    header{padding:28px 16px;text-align:center;
      background:radial-gradient(1200px 380px at 50% -120px,var(--moon) 0 40%,rgba(255,216,122,.0) 41%),
                 linear-gradient(90deg,var(--dusk),#fca885 35%,var(--brand-2));
      color:#fff;}
    header h1{margin:0 0 6px;font-size:28px;}
    header p{margin:0;opacity:.95;}
    .top-alert{max-width:1100px;margin:12px auto 0;padding:12px 16px;
      background:#eefaf3;border:1px solid #a8e0c2;border-radius:12px;
      color:#0b5e3c;font-weight:700;text-align:center;}
    .catalog{max-width:1100px;margin:14px auto 40px;padding:0 16px;
      display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));}
    .section{max-width:1100px;margin:28px auto 0;padding:20px;border-radius:16px;position:relative;overflow:hidden}
    .section h2{margin:0 0 12px 6px;color:var(--ink)}
    .section:nth-of-type(1){background:var(--section1);}
    .section:nth-of-type(2){background:var(--section2);}
    .section:nth-of-type(3){background:var(--section3);}
    .section:nth-of-type(4){background:var(--section4);}
    .section::after{content:"";position:absolute;left:0;right:0;bottom:-1px;height:26px;
      background:radial-gradient(20px 20px at 10% 0,rgba(255,255,255,.6),transparent 70%),
                 radial-gradient(24px 24px at 30% 0,rgba(255,255,255,.5),transparent 70%),
                 radial-gradient(22px 22px at 50% 0,rgba(255,255,255,.55),transparent 70%),
                 radial-gradient(26px 26px at 70% 0,rgba(255,255,255,.5),transparent 70%),
                 radial-gradient(18px 18px at 90% 0,rgba(255,255,255,.6),transparent 70%);
      opacity:.65;}
    .card{background:var(--card);border-radius:16px;padding:14px;
      box-shadow:0 8px 24px rgba(0,0,0,.08);position:relative;display:flex;flex-direction:column;}
    .card::before{content:"";position:absolute;inset:-1px;z-index:-1;filter:blur(18px);
      background:radial-gradient(60% 50% at 50% -10%,rgba(255,216,122,.35),transparent 60%);}
    .thumb{width:100%;aspect-ratio:4/3;object-fit:contain;border-radius:10px;background:#faf7f2;}
    .title{margin:10px 0 4px;font-size:18px;color:var(--brand);font-weight:700;}
    .price{margin:0 0 8px;font-size:16px;line-height:1.6;}
    .staff{display:block;color:var(--warn);font-weight:700;font-size:0.95rem;}
    .note{display:block;font-size:0.85rem;color:#666;margin-top:4px;}
    .desc{margin:0 0 12px;font-size:14px;color:#555;line-height:1.6;}
    .desc b{color:#c35400;font-weight:800;
      background:linear-gradient(#fff2,#fff2),linear-gradient(transparent 65%,#ffe6b6 0);
      background-clip:padding-box,content-box;}
    .notice{max-width:1000px;margin:40px auto;padding:20px;background:#fff8f2;
      border-radius:10px;border:1px solid #f2d5b3;}
    .notice h2{margin-top:0;color:#a0522d;}
    .notice ul{padding-left:20px;line-height:1.7;margin:0;}
    .notice li{margin-bottom:10px;}
    .notice .legal{margin-top:12px;font-size:12px;color:#888;}
    .ext-link{color:#006241;text-decoration:underline;}
    footer{text-align:center;font-size:12px;color:#666;padding:20px 12px 40px;}
    /* 螢光重點標示 */
.hl{
  font-weight: 800;
  background: linear-gradient(transparent 60%, #fff3a6 0);
  padding: 0 .15em;
  border-radius: 2px;
}

  </style>
</head>
<body>
  
  <header>
    <h1>星巴克中秋禮盒型錄</h1>
    
    <div class="top-alert">
      <p>定價 & 桃捷員工價（原價 8 折；咖啡豆品項為「先折再 8 折」）</p><br>
    🌕 單筆滿 <b>NT$5,000</b> 享 1 個免費宅配地點　
    ｜　⚠️ 僅限本檔使用，切勿至外面門市要求此團購價格
  </div>
  
  </header>

  <!-- 分類1：月光系列 -->
  <section class="section">
    <h2>🌕 月光系列</h2>
    <div class="catalog" id="moon"></div>
  </section>

  <!-- 分類2：咖啡禮盒 -->
  <section class="section">
    <h2>☕ 咖啡禮盒</h2>
    <div class="catalog" id="coffee"></div>
  </section>

  <!-- 分類3：咖啡豆雙星 -->
  <section class="section">
    <h2>🌱 咖啡豆雙星</h2>
    <div class="catalog" id="beans"></div>
  </section>

  <!-- 分類4：餅乾蛋捲 -->
  <section class="section">
    <h2>🍪 餅乾蛋捲</h2>
    <div class="catalog" id="snack"></div>
  </section>

  <!-- 注意事項 -->
<section class="notice">
  <h2>📌 購與取貨注意事項（重點）</h2>
  <ul>
    <li>
      🗓️ <b>結單時間：</b>
      <span class="hl">2025/09/16（二）23:59 截止</span>。
    </li>

    <li>
      💳 <b>付款方式：</b>
      僅限「<span class="hl">轉帳</span>」付款，請於結單前完成匯款；
      <span class="hl">逾期未付款視同放棄訂購</span>。
    </li>

    <li>
      🧾 <b>發票說明：</b>
      本次團購統一<span class="hl">開立單張發票</span>（由星巴克開立）。<br>
      若需特別開立<span class="hl">紙本發票／統編</span>，請另行聯絡
      <span class="hl">數發 88461 文琱</span> 協助處理，並需加收
      <span class="hl">50 元（掛號郵資＋往來門市跑腿費用）</span>，
      且<span class="hl">僅限您指定的單一門市取貨</span>。
    </li>

    <li>
      🏬 <b>取貨方式：</b><br>
      (1) 🚚 <b>宅配自領：</b> <span class="hl">8/21（四）行政大樓休息區</span> 領取。<br>
      (2) 🏪 <b>門市自取：</b> 憑提貨單（並會收到簡訊）領取；<span class="hl">下單時務必備註領取日期與「兩間」候選門市</span>。<br>
      ・範例：經國門市－桃園市桃園區經國路369號。<br>
      ・<span class="hl">以下門市無法取貨，請勿選擇：</span>
      離島門市、新光、漢神巨蛋 B1、京站 2、同領、興南、高雄榮總、左營高鐵、時代 B2、新竹台醫、板大遠百 9F、微風南山。
    </li>

    <li>
      🚚 <b>宅配服務：</b>
      <span class="hl">僅限桃捷團購宅配到貨</span>。
      單筆滿 <span class="hl">NT$5,000</span> 享 1 個免費宅配地點。<br>
      中秋物流高峰可能延遲，<span class="hl">取貨請往前抓一週</span> 以留容錯時間。<br>
      部分門市／離島不適用；非瑕疵品恕不退換貨。
    </li>
  </ul>
  <p class="legal">⚠️ 僅限本檔使用，切勿至外面門市要求此團購價格</p>
</section>


  <footer>
    <div>© 2025 桃捷員工專屬團購檔</div>
  </footer>

  <script>
    const products = {
      moon: [
        { name:"月光寶盒", price:2280, img:"major_01.png", desc:"紫色布面搭配木紋盒面與金色鎖扣。<br><b>禮盒內容：黑松露奶皇、棗泥核桃、蜂蜜柚香琴酒奶皇、草莓乳酪奶皇月餅＋西點</b>" },
        { name:"月光奏鳴曲", price:1180, img:"major_03.png", desc:"桃山餅皮海鹽焦糖藏芯月餅，融合義式咖啡粉。<b>禮盒內容：月餅＋布列塔尼＋達克瓦茲＋瑪德蓮＋燕麥餅乾</b>" },
        { name:"月光序曲", price:800, img:"major_05.png", desc:"<b>奶皇月餅 6 入</b>，奶香濃郁、鹹甜交織。" },
        { name:"月光樂園", price:550, img:"major_06.png", desc:"<b>蘋果鳳梨酥 4 入、可可鳳梨酥 4 入</b>，酸甜果香與可可風味交織。" }
      ],
      coffee: [
        { name:"VIA 分享禮盒", price:980, img:"coffee_05@2x.png", desc:"<b>任選三盒 VIA 咖啡（12 入）</b>，含哥倫比亞、星巴克經典、派克市場、義大利烘焙等。" },
        { name:"掛耳咖啡禮盒", price:660, img:"coffee_06@2x.png", desc:"<b>任選三盒掛耳咖啡（6 入）即折 60 元</b>，風味多選，沖泡便利。", preDiscount:60 },
        { name:"星巴克居家咖啡禮盒", price:1050, img:"coffee_01@2x.png", desc:"<b>結合掛耳、VIA 即溶咖啡多種風味</b>，內含 27 條多樣組合。" }
      ],
      beans: [
        { name:"咖啡雙星禮盒（自選兩包）", price:640, img:"coffee_07@2x.png", desc:"<b>任選 2 包咖啡豆（典藏除外）</b>。原價先折 30 元再享 8 折。<br><a class='ext-link' href='https://www.starbucks.com.tw/coffee/our-coffees.jspx?cat=bean' target='_blank'>咖啡豆口味請至官方頁面查看</a>", preDiscount:30 },
        { name:"季節咖啡雙星禮盒（自選兩包）", price:930, img:"coffee_11@2x.png", desc:"<b>任選 2 包季節咖啡豆</b>。原價先折 100 元再享 8 折。<br><a class='ext-link' href='https://www.starbucks.com.tw/coffee/our-coffees.jspx?cat=bean' target='_blank'>咖啡豆口味請至官方頁面查看</a>", preDiscount:100 }
      ],
      snack: [
        { name:"精選咖啡蛋捲禮盒", price:580, img:"minor_01@2x.png", desc:"<b>咖啡蛋捲 6 包（每包 9 支）</b>，酥脆香濃。" },
        { name:"臻選綜合蛋捲禮盒", price:580, img:"minor_02@2x.png", desc:"<b>咖啡、可可、紅茶、蜂蜜、起司、麥麩各 1 包（每包 9 支）</b>。" },
        { name:"綜合曲奇餅乾禮盒", price:520, img:"minor_06@2x.png", desc:"<b>多種口味曲奇餅乾</b>，鐵盒童趣可愛。" },
        { name:"海苔肉鬆薄餅禮盒", price:500, img:"minor_05@2x.png", desc:"<b>海苔肉鬆薄餅 6 包（每包 3 片）</b>。豬肉、豬油產地：台灣。" }
      ]
    };

    function currency(n){return "NT$ "+Math.round(n).toLocaleString("zh-Hant-TW");}
    function staffPrice(p){const base=(p.preDiscount?(p.price-p.preDiscount):p.price);return base*0.8;}
    function renderSection(id,list){
      document.getElementById(id).innerHTML=list.map(p=>{
        const staff=staffPrice(p);
        const calc=p.preDiscount?`（計價：${currency(p.price)} − ${currency(p.preDiscount)} 再 ×8折）`:`（計價：原價 ×8折）`;
        return `<article class="card">
          <img class="thumb" src="${p.img}" alt="${p.name}">
          <h2 class="title">${p.name}</h2>
          <p class="price">定價 ${currency(p.price)}<br>
            <span class="staff">桃捷員工價 ${currency(staff)}</span>
            <span class="note">${calc}</span>
            <span class="note">⚠️ 僅限本檔使用，切勿至外面門市要求此團購價格</span>
          </p>
          <p class="desc">${p.desc}</p>
        </article>`;
      }).join("");
    }
    renderSection("moon",products.moon);
    renderSection("coffee",products.coffee);
    renderSection("beans",products.beans);
    renderSection("snack",products.snack);
  </script>

  <!-- 月亮 + 兔子 -->
  <svg width="120" height="120" viewBox="0 0 120 120"
       style="position:fixed;right:18px;top:84px;opacity:.85;z-index:0;pointer-events:none">
    <defs>
      <radialGradient id="gMoon" cx="50%" cy="50%" r="60%">
        <stop offset="0%" stop-color="#fff6c9"/>
        <stop offset="70%" stop-color="#ffd87a"/>
        <stop offset="100%" stop-color="#f7c24f"/>
      </radialGradient>
    </defs>
    <circle cx="60" cy="60" r="54" fill="url(#gMoon)"/>
  </svg>
  <svg width="120" height="120" viewBox="0 0 120 120"
       style="position:fixed;left:14px;bottom:24px;opacity:.85;z-index:0;pointer-events:none">
    <path fill="#fff"
      d="M78 44c4 0 7-3 7-7s-3-7-7-7-7 3-7 7 3 7 7 7Zm-12 6c-9 0-18 7-19 16-6 1-11 5-11 10 0 6 7 10 16 10 8 0 12-2 19-8 3 3 7 5 12 5 8 0 14-5 14-12 0-6-4-10-10-12-1-7-10-9-21-9Z"/>
    <ellipse cx="32" cy="100" rx="22" ry="6" fill="rgba(0,0,0,.06)"/>
  </svg>
</body>
</html>
