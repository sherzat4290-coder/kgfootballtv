<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KGFOOTBALLTV AI</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#080d18;color:white;font-family:Arial,sans-serif}
header{padding:22px 6%;background:#101a2d;border-bottom:1px solid #263957}
.logo{font-size:25px;font-weight:900;color:#fff}
.logo span{color:#258cff}
header p{color:#9eacc3;margin-bottom:0}
main{max-width:1000px;margin:35px auto;padding:0 18px}
.hero{text-align:center;padding:35px 10px}
.hero h1{font-size:36px;margin:0 0 12px}
.hero h1 span{color:#258cff}
.hero p{color:#aab7ca}
.tools{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
.card{background:#111d31;border:1px solid #263957;border-radius:16px;padding:22px}
.card h2{font-size:20px;margin-top:0}
.card p{color:#9eacc3;font-size:14px}
textarea,select{width:100%;background:#080f1d;color:white;border:1px solid #344765;border-radius:9px;padding:13px;margin:10px 0;font-size:15px}
textarea{min-height:130px;resize:vertical}
button{width:100%;background:#1678ed;color:white;border:0;border-radius:9px;padding:14px;font-size:16px;font-weight:bold;cursor:pointer}
button:hover{background:#0861c9}
.result{white-space:pre-wrap;background:#080f1d;border-radius:9px;padding:13px;margin-top:14px;color:#dce8fa;min-height:45px}
footer{text-align:center;color:#75849d;padding:35px}
</style>
</head>
<body>
<header>
 <div class="logo">KG<span>FOOTBALL</span>TV</div>
 <p>Кыргыз футбол жаңылыктары үчүн AI студиясы</p>
</header>
<main>
 <section class="hero">
  <h1>FOOTBALL <span>AI STUDIO</span></h1>
  <p>Футбол контентин даярдоо эми оңой!</p>
 </section>
 <section class="tools">
  <div class="card">
   <h2>⚽ Кыргызча котормо</h2>
   <p>Футбол жаңылыгын бул жерге киргиз.</p>
   <textarea id="news" placeholder="Вставь футбольную новость..."></textarea>
   <button onclick="generate('translate')">Кыргызча которуу</button>
   <div class="result" id="translation">Натыйжа бул жерде чыгат.</div>
  </div>
  <div class="card">
   <h2>🎬 Reels сценарийи</h2>
   <p>Темаңды жаз, видео сценарийин даярда.</p>
   <textarea id="topic" placeholder="Например: Холанд против Мбаппе..."></textarea>
   <select id="duration">
    <option value="30 секунд">30 секунд</option>
    <option value="45 секунд">45 секунд</option>
    <option value="60 секунд">60 секунд</option>
   </select>
   <button onclick="generate('script')">Сценарий түзүү</button>
   <div class="result" id="script">Сценарий бул жерде чыгат.</div>
  </div>
  <div class="card">
   <h2>📰 Пост жана заголовок</h2>
   <p>Пост үчүн кызыктуу аталыш даярда.</p>
   <textarea id="post" placeholder="Футбол жаңылыгын киргиз..."></textarea>
   <button onclick="generate('post')">Заголовок түзүү</button>
   <div class="result" id="postresult">Натыйжа бул жерде чыгат.</div>
  </div>
 </section>
</main>
<footer>© 2026 KGFOOTBALLTV — Football Media Studio</footer>
<script>
function generate(type){
 alert("AI азырынча туташтырыла элек. Кийинки кадамда OpenAI API кошобуз!");
}
</script>
</body>
</html>