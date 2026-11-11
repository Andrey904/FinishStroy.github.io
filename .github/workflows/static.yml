<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>FinishStroy — строительный магазин в Мозыре</title>
<meta name="description" content="FinishStroy: краски, смеси, инструмент и оборудование для отделки. г. Мозырь, ул. Гагарина 50А.">
<style>
:root{
  --navy:#0b3a8f; --blue:#1565d8; --sky:#8fd0f6; --ice:#eaf6fe; --white:#fff;
  --text:#10264d; --muted:#4d6286; --card:#fff; --line:#cfe3f4; --bg:#fff;
  --head:'Trebuchet MS','Segoe UI',system-ui,-apple-system,Roboto,Arial,sans-serif; --body:system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){--bg:#07173a;--text:#e8f2ff;--muted:#a7bbdd;--card:#0d2552;--line:#1d3d78;--ice:#0a1f48;--navy:#0a2c70}
}
:root[data-theme="dark"]{--bg:#07173a;--text:#e8f2ff;--muted:#a7bbdd;--card:#0d2552;--line:#1d3d78;--ice:#0a1f48;--navy:#0a2c70}
html{scroll-padding-top:calc(72px + env(safe-area-inset-top,0px));scroll-behavior:smooth}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:400 17px/1.6 var(--body)}
a{color:inherit}
:focus-visible{outline:3px solid var(--sky);outline-offset:3px}
.wrap{max-width:1120px;margin:0 auto;padding:0 20px}
h1,h2,h3{font-family:var(--head);line-height:1.15;margin:0;letter-spacing:-.01em}
h2{font-size:clamp(24px,4vw,36px);font-weight:700}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--navy);color:#fff}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--navy);z-index:30}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;height:72px}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;font:700 18px var(--head)}
.brand svg{width:48px;height:48px}
nav{display:flex;gap:22px;font-weight:500;font-size:15px}
nav a{text-decoration:none;opacity:.9}nav a:hover{opacity:1;text-decoration:underline;text-underline-offset:6px}
.tel{background:var(--sky);color:var(--navy);font-weight:700;text-decoration:none;padding:10px 18px;border-radius:999px;white-space:nowrap;font-size:15px}
@media(max-width:820px){.bar{height:auto;flex-wrap:wrap;padding-top:10px;padding-bottom:8px;row-gap:6px}nav{order:3;width:100%;justify-content:space-between;gap:8px;font-size:15px;border-top:1px solid rgba(255,255,255,.2);padding-top:8px}nav a{padding:6px 8px}.brand span{font-size:15px}.brand svg{width:40px;height:40px}.tel{font-size:13px;padding:9px 13px}html{scroll-padding-top:calc(110px + env(safe-area-inset-top,0px))}}
@media(max-width:380px){.brand span{display:none}}

/* hero */
.hero{background:var(--navy);color:#fff;position:relative;overflow:hidden;padding:64px 0 96px}
.hero::after{content:"";position:absolute;left:0;right:0;bottom:-1px;height:70px;background:var(--bg);clip-path:polygon(0 100%,100% 100%,100% 0,0 70%)}
.spray{position:absolute;right:-120px;top:-60px;width:760px;max-width:none;opacity:.9;pointer-events:none}
.hero .wrap{position:relative;display:grid;grid-template-columns:1.2fr .8fr;gap:32px;align-items:center}
.hero h1{font-size:clamp(34px,6.4vw,66px);font-weight:700}
.hero p.slogan{font:500 clamp(18px,2.4vw,24px) var(--head);color:var(--sky);margin:18px 0 10px}
.hero p.lead{max-width:46ch;color:#d6e8fb;margin:0 0 28px}
.btns{display:flex;flex-wrap:wrap;gap:12px}
.btn{display:inline-block;padding:14px 26px;border-radius:999px;font-weight:700;text-decoration:none;border:2px solid var(--sky)}
.btn.p{background:var(--sky);color:var(--navy)}.btn.p:hover{background:#fff;border-color:#fff}
.btn.s{color:#fff}.btn.s:hover{background:rgba(255,255,255,.12)}
.badge{justify-self:center;width:min(340px,80vw);filter:drop-shadow(0 20px 40px rgba(0,0,0,.35));animation:pop .9s cubic-bezier(.2,.9,.3,1.2) both}
@keyframes pop{from{opacity:0;transform:scale(.85) rotate(-8deg)}}
@media(max-width:820px){.hero .wrap{grid-template-columns:1fr}.badge{order:-1;width:200px;justify-self:start}.spray{width:520px;right:-200px}}

section{padding:72px 0}
@media(max-width:820px){section{padding:48px 0}.hero{padding:36px 0 80px}.btn{flex:1 1 100%;text-align:center}}
.sub{color:var(--muted);max-width:56ch;margin:10px 0 36px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px}
.cat{background:var(--card);border:2px solid var(--line);border-radius:20px 20px 20px 4px;padding:24px;transition:border-color .2s,transform .2s}
.cat:hover{border-color:var(--blue);transform:translateY(-3px)}
.cat svg{width:44px;height:44px;margin-bottom:12px}
.cat h3{font-size:17px;margin-bottom:8px}
.cat p{margin:0;color:var(--muted);font-size:15px}
.alt{background:var(--ice)}
.why{display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:start}
.why ul{list-style:none;margin:0;padding:0;display:grid;gap:14px}
.why li{padding-left:18px;border-left:5px solid var(--blue)}
.why li b{display:block;font-family:var(--head);font-size:16px;margin-bottom:2px}
.why li span{color:var(--muted)}
@media(max-width:820px){.why{grid-template-columns:1fr;gap:28px}}

/* contacts */
.contact{background:var(--navy);color:#fff;border-radius:28px;padding:40px;display:grid;grid-template-columns:1fr 1fr;gap:32px}
.contact h2{margin-bottom:18px}
.contact dl{margin:0;display:grid;gap:16px}
.contact dt{color:var(--sky);font-weight:700;font-size:14px}
.contact dd{margin:2px 0 0;font-size:20px;font-weight:500}
.contact a{text-decoration:none}.contact a:hover{text-decoration:underline}
.form{display:grid;gap:12px;align-content:start}
.form input,.form textarea{width:100%;padding:13px 16px;border-radius:14px;border:2px solid transparent;font:inherit;background:#fff;color:#10264d}
.form input:focus,.form textarea:focus{border-color:var(--sky);outline:none}
.form button{cursor:pointer;border:0;font:700 17px var(--body);padding:14px;border-radius:999px;background:var(--sky);color:var(--navy)}
.form button:hover{background:#fff}
.ok{display:none;background:var(--sky);color:var(--navy);padding:12px 16px;border-radius:14px;font-weight:700}
@media(max-width:820px){.contact{grid-template-columns:1fr;padding:28px 22px}}
footer{padding:28px 0 40px;color:var(--muted);font-size:14px;text-align:center}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body>

<!-- логотип: переработанный знак (краскопульт в круге) -->
<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <defs>
    <symbol id="logo" viewBox="0 0 200 200">
      <circle cx="100" cy="100" r="96" fill="#fff"/>
      <circle cx="100" cy="100" r="90" fill="#1565d8"/>
      <circle cx="100" cy="100" r="62" fill="#0b3a8f"/>
      <circle cx="100" cy="100" r="62" fill="none" stroke="#8fd0f6" stroke-width="3"/>
      <path id="arcT" d="M30 100a70 70 0 0 1 140 0" fill="none"/>
      <path id="arcB" d="M24 100a76 76 0 0 0 152 0" fill="none"/>
      <text font-family="Arial Black,Arial,sans-serif" font-weight="900" font-size="17" fill="#fff" letter-spacing="3"><textPath href="#arcT" startOffset="50%" text-anchor="middle">PROFCENTR</textPath></text>
      <text font-family="Arial,sans-serif" font-weight="700" font-size="11.5" fill="#eaf6fe" letter-spacing="1"><textPath href="#arcB" startOffset="50%" text-anchor="middle">КАЧЕСТВО, КОТОРОМУ ДОВЕРЯЮТ</textPath></text>
      <!-- распыление -->
      <path d="M60 94l-26-12M58 100l-30 0M60 106l-26 12" stroke="#8fd0f6" stroke-width="3" stroke-linecap="round"/>
      <!-- краскопульт -->
      <g fill="#fff">
        <rect x="62" y="90" width="12" height="20" rx="3"/>
        <path d="M74 88h44a14 14 0 0 1 14 14v2a4 4 0 0 1-4 4h-30l-6 20a5 5 0 0 1-5 4h-6a3 3 0 0 1-3-4l7-20h-11z"/>
        <rect x="116" y="82" width="10" height="9" rx="2"/>
      </g>
      <text x="100" y="62" text-anchor="middle" font-family="Arial Black,Arial,sans-serif" font-weight="900" font-size="14" fill="#fff">FINISH</text>
      <text x="100" y="146" text-anchor="middle" font-family="Arial Black,Arial,sans-serif" font-weight="900" font-size="14" fill="#8fd0f6">STROY</text>
    </symbol>
  </defs>
</svg>

<header>
  <div class="wrap bar">
    <a class="brand" href="#top" aria-label="FinishStroy — на главную">
      <svg><use href="#logo"/></svg><span>FinishStroy</span>
    </a>
    <nav aria-label="Разделы">
      <a href="#catalog">Каталог</a>
      <a href="#why">О магазине</a>
      <a href="#contacts">Контакты</a>
    </nav>
    <a class="tel" href="tel:+375297360260">+375 29 736-02-60</a>
  </div>
</header>

<main id="top">
<div class="hero">
  <svg class="spray" viewBox="0 0 760 520" aria-hidden="true">
    <g fill="#8fd0f6">
      <path d="M760 40 0 250 760 260z" opacity=".16"/>
      <path d="M760 120 0 255 760 330z" opacity=".13"/>
      <path d="M760 200 0 258 760 420z" opacity=".1"/>
    </g>
    <g fill="#fff" opacity=".5">
      <circle cx="120" cy="215" r="3"/><circle cx="210" cy="190" r="4"/><circle cx="170" cy="260" r="2.5"/>
      <circle cx="300" cy="170" r="3"/><circle cx="260" cy="280" r="4"/><circle cx="380" cy="240" r="2.5"/><circle cx="90" cy="290" r="2"/>
    </g>
  </svg>
  <div class="wrap">
    <div>
      <h1>FinishStroy</h1>
      <p class="slogan">Качество, которому доверяют</p>
      <p class="lead">Краски, сухие смеси, инструмент и оборудование для отделки. Подберём материалы под ваш ремонт и подскажем, как с ними работать.</p>
      <div class="btns">
        <a class="btn p" href="#catalog">Смотреть каталог</a>
        <a class="btn s" href="tel:+375297360260">Позвонить в магазин</a>
      </div>
    </div>
    <svg class="badge" role="img" aria-label="Логотип FinishStroy"><use href="#logo"/></svg>
  </div>
</div>

<section id="catalog">
  <div class="wrap">
    <h2>Что можно купить</h2>
    <p class="sub">Всё для черновых и чистовых работ в одном месте. Наличие и цены уточняйте по телефону.</p>
    <div class="grid">
      <article class="cat">
        <svg viewBox="0 0 48 48" fill="none" stroke="#1565d8" stroke-width="3" stroke-linejoin="round"><path d="M10 8h28v12H10zM24 20v8M20 28h8v14h-8z"/></svg>
        <h3>Краски и лаки</h3><p>Для стен, потолков, фасадов и дерева. Колеровка под нужный цвет.</p>
      </article>
      <article class="cat">
        <svg viewBox="0 0 48 48" fill="none" stroke="#1565d8" stroke-width="3" stroke-linejoin="round"><path d="M8 18 24 8l16 10v22H8zM18 40V26h12v14"/></svg>
        <h3>Сухие смеси</h3><p>Штукатурки, шпатлёвки, плиточный клей, стяжки и грунтовки.</p>
      </article>
      <article class="cat">
        <svg viewBox="0 0 48 48" fill="none" stroke="#1565d8" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M8 18h24a6 6 0 0 1 6 6v2H24l-4 14h-6l3-14H8zM38 24h4M36 18l4-3M36 30l4 3"/></svg>
        <h3>Краскопульты</h3><p>Аппараты безвоздушного распыления и расходники к ним.</p>
      </article>
      <article class="cat">
        <svg viewBox="0 0 48 48" fill="none" stroke="#1565d8" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M30 8l10 10-6 6-10-10zM26 20 8 38l4 4 18-18"/></svg>
        <h3>Инструмент</h3><p>Ручной и электроинструмент: шпатели, валики, миксеры, уровни.</p>
      </article>
      <article class="cat">
        <svg viewBox="0 0 48 48" fill="none" stroke="#1565d8" stroke-width="3" stroke-linejoin="round"><path d="M6 12h36v8H6zM6 24h36v8H6zM6 36h36v6H6z"/></svg>
        <h3>Отделочные материалы</h3><p>Гипсокартон, профили, утеплитель, плитка и обои.</p>
      </article>
      <article class="cat">
        <svg viewBox="0 0 48 48" fill="none" stroke="#1565d8" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="24" cy="24" r="6"/><path d="M24 6v6M24 36v6M6 24h6M36 24h6M11 11l4 4M33 33l4 4M37 11l-4 4M15 33l-4 4"/></svg>
        <h3>Крепёж и мелочи</h3><p>Саморезы, дюбели, пена, герметики, перчатки, плёнка и скотч.</p>
      </article>
    </div>
  </div>
</section>

<section id="why" class="alt">
  <div class="wrap why">
    <div>
      <h2>Почему к нам возвращаются</h2>
      <p class="sub">Мы работаем так, чтобы после ремонта вам не пришлось ничего переделывать.</p>
    </div>
    <ul>
      <li><b>Проверенные производители</b><span>Берём материалы, в которых уверены сами.</span></li>
      <li><b>Совет по делу</b><span>Расскажем, что подойдёт для вашей поверхности и сколько брать.</span></li>
      <li><b>Всё для работы с краской</b><span>Материалы и оборудование для нанесения: от валика до краскопульта.</span></li>
      <li><b>Удобное расположение</b><span>Магазин на ул. Гагарина в Мозыре.</span></li>
    </ul>
  </div>
</section>

<section id="contacts">
  <div class="wrap">
    <div class="contact">
      <div>
        <h2>Приходите или звоните</h2>
        <dl>
          <div><dt>Телефон</dt><dd><a href="tel:+375297360260">+375 29 736-02-60</a></dd></div>
          <div><dt>Адрес</dt><dd><a href="https://www.google.com/maps/search/?api=1&query=%D0%9C%D0%BE%D0%B7%D1%8B%D1%80%D1%8C+%D0%93%D0%B0%D0%B3%D0%B0%D1%80%D0%B8%D0%BD%D0%B0+50%D0%90" target="_blank" rel="noopener">г. Мозырь, ул. Гагарина 50А</a></dd></div>
          <div><dt>Instagram</dt><dd><a href="https://www.instagram.com/finishstroy" target="_blank" rel="noopener">@finishstroy</a></dd></div>
        </dl>
      </div>
      <form class="form" id="f">
        <input name="n" placeholder="Ваше имя" aria-label="Ваше имя" required>
        <input name="p" type="tel" placeholder="Телефон" aria-label="Телефон" required>
        <textarea name="m" rows="3" placeholder="Что вам нужно?" aria-label="Что вам нужно?"></textarea>
        <button type="submit">Отправить заявку</button>
        <div class="ok" id="ok" role="status">Заявка отправлена. Мы перезвоним вам.</div>
      </form>
    </div>
  </div>
</section>
</main>

<footer>© 2026 FinishStroy · Качество, которому доверяют · г. Мозырь</footer>

<script>
// ===== Настройка Telegram: вставьте свои значения между кавычками =====
var TG_TOKEN='9157385312:AAFg7jlH9KcMN_Ga9vO38eZtJ_J76kZh-mE';   // токен бота от @BotFather, например 123456:ABC-DEF...
var TG_CHAT_ID='-1004451010311'; // ваш chat_id или id группы, например 123456789
// =====================================================================
document.getElementById('f').addEventListener('submit',async function(e){
  e.preventDefault();
  var f=this, ok=document.getElementById('ok'), btn=f.querySelector('button');
  var text='Новая заявка с сайта FinishStroy\nИмя: '+f.n.value+'\nТелефон: '+f.p.value+'\nСообщение: '+(f.m.value||'—');
  btn.disabled=true;
  try{
    if(!TG_TOKEN||!TG_CHAT_ID) throw new Error('not configured');
    var r=await fetch('https://api.telegram.org/bot'+TG_TOKEN+'/sendMessage',{
      method:'POST',headers:{'Content-Type':'application/json'},
      body:JSON.stringify({chat_id:TG_CHAT_ID,text:text})});
    if(!r.ok) throw new Error('send failed');
    ok.textContent='Заявка отправлена. Мы перезвоним вам.';
    f.reset();
  }catch(err){
    ok.textContent='Не удалось отправить заявку. Позвоните нам: +375 29 736-02-60';
  }
  ok.style.display='block';
  btn.disabled=false;
});
</script>
</body>
</html>
