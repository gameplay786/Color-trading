<!doctype html>

<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>कृषि लैंडिंग पेज — शानदार ओके</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent1:#22c1c3;
      --accent2:#f7797d;
      --accent3:#ffd166;
      --glass: rgba(255,255,255,0.06);
      --muted: rgba(255,255,255,0.75);
      --shadow: 0 10px 30px rgba(2,6,23,0.6);
    }
    *{box-sizing:border-box}
    body{font-family: 'Segoe UI', Roboto, Noto Sans, Arial; margin:0; background: linear-gradient(180deg,#071426 0%, #0b1628 100%); color: #fff; -webkit-font-smoothing:antialiased}
    .container{max-width:1000px;margin:40px auto;padding:24px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:16px;padding:28px;box-shadow:var(--shadow);display:grid;grid-template-columns:1fr 420px;gap:24px;align-items:center}
    .headline{font-size:34px;line-height:1.05;margin:0 0 12px;font-weight:800}
    .headline .glow{display:inline-block;padding:6px 12px;border-radius:10px;background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#08121a}
    .sub{color:var(--muted);margin-bottom:16px}
    .features{display:flex;gap:12px;flex-wrap:wrap;margin-top:8px}
    .pill{background:var(--glass);padding:10px 12px;border-radius:999px;font-weight:600}
    .color-lines{height:8px;border-radius:6px;margin:16px 0;display:flex;overflow:hidden}
    .color-lines > span{flex:1}
    .c1{background:linear-gradient(90deg,#22c1c3,#f7797d)}
    .c2{background:linear-gradient(90deg,#f7797d,#ffd166)}
    .c3{background:linear-gradient(90deg,#ffd166,#22c1c3)}
    .lead-form{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:22px;border-radius:12px}
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px}
    input,select,button,textarea{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.06);background:transparent;color:#fff;font-size:15px}
    .row{display:flex;gap:12px}
    .row .half{flex:1}
    .cta{margin-top:12px}
    .btn-primary{background:linear-gradient(90deg,var(--accent1),var(--accent2));border:none;color:#08121a;font-weight:800;padding:12px;border-radius:12px;cursor:pointer}
    .small{font-size:13px;color:var(--muted);margin-top:8px}
    .hero-img{border-radius:12px;overflow:hidden;background:linear-gradient(180deg,#08323a,#06202b);padding:16px;text-align:center}
    .hero-img img{max-width:100%;height:auto;border-radius:8px}
    footer{margin-top:18px;color:var(--muted);font-size:13px;text-align:center}
    @media (max-width:880px){.card{grid-template-columns:1fr;}.container{margin:16px;padding:16px}.headline{font-size:28px}}
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div>
        <h1 class="headline">🌾 <span class="glow">शानदार ओके</span> — खेती की सफलता का नया नाम</h1>
        <p class="sub">आधुनिक तकनीक + विशेषज्ञ मार्गदर्शन = बेहतर फसल और बढ़ता मुनाफा। अभी जुड़िए और पाएं प्रतिदिन उपयोगी कृषि सलाह, मौसम-आधारित टिप्स और सरकारी योजनाओं की जानकारी।</p><div class="color-lines" aria-hidden="true">
      <span class="c1"></span>
      <span class="c2"></span>
      <span class="c3"></span>
    </div>

    <div class="features">
      <div class="pill">✅ नई खेती की तकनीकें</div>
      <div class="pill">✅ मौसम के अनुसार फसल चयन</div>
      <div class="pill">✅ सरकारी योजनाएँ एवं सब्सिडी</div>
      <div class="pill">✅ विशेषज्ञों की वीडियो सलाह</div>
    </div>

    <p class="small">हमारी टीम छोटे और बड़े किसानों के लिए आसान, व्यावहारिक और स्थानीय भाषा में समाधान बनाती है।</p>
  </div>

  <aside>
    <div class="lead-form">
      <h3 style="margin:0 0 8px">मुफ्त मार्गदर्शिका पाएं</h3>
      <p style="margin:0 0 12px;color:var(--muted)">अपना नाम और मोबाइल नंबर भरें — हमारी टीम आपसे संपर्क करेगी।</p>

      <form id="leadForm" onsubmit="return submitForm(event)">
        <label for="name">नाम</label>
        <input id="name" name="name" type="text" placeholder="आपका नाम" required />

        <label for="phone" style="margin-top:10px">मोबाइल नंबर</label>
        <input id="phone" name="phone" type="tel" placeholder="10-digit मोबाइल नंबर" pattern="[0-9]{10}" required />

        <label for="crop" style="margin-top:10px">मुख्य फसल (यदि हो)</label>
        <select id="crop" name="crop">
          <option value="">-- चुनें --</option>
          <option>गेहूँ</option>
          <option>धान</option>
          <option>मकई</option>
          <option>सब्ज़ियाँ</option>
          <option>फल</option>
          <option>अन्य</option>
        </select>

        <div class="cta">
          <button class="btn-primary" type="submit">अभी पंजीकरण करें</button>
        </div>

        <p class="small">हम आपका डेटा सुरक्षित रखते हैं — केवल संपर्क हेतु उपयोग होगा।</p>
      </form>
    </div>

    <div style="height:14px"></div>

    <div class="hero-img">
      <img alt="kisan" src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" />
      <p style="margin-top:10px;font-size:13px;color:var(--muted)">स्थानीय विशेषज्ञों से जुड़ें — सही समय पर सही सलाह।</p>
    </div>
  </aside>
</div>

<footer>
  © <span id="year"></span> शानदार ओके — किसानों के लिए सरल और प्रभावी समाधान
</footer>

  </div>  <script>
    // वर्ष सेट करें
    document.getElementById('year').textContent = new Date().getFullYear();

    function submitForm(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const phone = document.getElementById('phone').value.trim();
      if(!/^\d{10}$/.test(phone)){
        alert('कृपया 10 अंकों का मान्य मोबाइल नंबर दर्ज करें।');
        return false;
      }

      // यहाँ आप AJAX से अपने बैकएंड को पोस्ट कर सकते हैं।
      // अभी बस धन्यवाद संदेश दिखा रहे हैं।
      alert(name + '\n\nधन्यवाद! आपकी जानकारी मिल गई है। हमारी टीम शीघ्र संपर्क करेगी।');
      document.getElementById('leadForm').reset();
      return false;
    }
  </script></body>
</html>
