<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>АКТ студенттерінің оқу порталы</title>
<style>
:root{--navy:#14213d;--blue:#2563eb;--sky:#eaf2ff;--ink:#1f2937;--muted:#64748b;--white:#fff;--line:#dbe4f0}
*{box-sizing:border-box} body{margin:0;font-family:Arial,Helvetica,sans-serif;background:#f4f7fb;color:var(--ink);line-height:1.6}
header{background:linear-gradient(120deg,#14213d,#2563eb);color:white;padding:52px 20px 44px;text-align:center}
header .tag{display:inline-block;padding:6px 13px;border:1px solid #ffffff70;border-radius:30px;font-size:13px;letter-spacing:1px}
h1{font-size:clamp(30px,5vw,48px);margin:15px 0 8px} header p{max-width:720px;margin:0 auto;color:#e6efff}
nav{background:white;position:sticky;top:0;z-index:5;display:flex;justify-content:center;gap:22px;flex-wrap:wrap;padding:14px;border-bottom:1px solid var(--line)}
nav a{color:var(--navy);text-decoration:none;font-weight:700;font-size:14px} nav a:hover{color:var(--blue)}
main{max-width:1050px;margin:34px auto;padding:0 18px}
section{background:white;border:1px solid var(--line);border-radius:18px;padding:28px;margin:22px 0;box-shadow:0 8px 25px #14213d0a}
h2{color:var(--navy);margin:0 0 14px;font-size:25px}
.lead{font-size:17px;color:#475569}
.hero-img{width:100%;height:260px;object-fit:cover;border-radius:14px;margin-top:14px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:14px}
.card{background:var(--sky);padding:18px;border-radius:14px}
.card h3{margin:0 0 6px;color:var(--navy)}
table{width:100%;border-collapse:collapse;margin-top:12px;overflow:hidden;border-radius:10px}
th,td{border:1px solid var(--line);padding:12px;text-align:left}
th{background:#dce9ff;color:var(--navy)} tr:nth-child(even) td{background:#f8faff}
ul{padding-left:22px} li{margin:5px 0}
a{color:#1d4ed8}
form{display:grid;gap:13px;max-width:650px}
label{font-weight:700;color:var(--navy)}
input,select,textarea{width:100%;padding:12px;border:1px solid #cbd5e1;border-radius:9px;font:inherit;background:white}
fieldset{border:1px solid var(--line);border-radius:10px;padding:14px}
fieldset label{font-weight:400;margin-right:18px}
button{background:var(--blue);color:white;border:0;padding:13px 22px;border-radius:9px;font-weight:700;cursor:pointer}
button:hover{background:#1d4ed8}
.note{font-size:13px;color:var(--muted)}
footer{text-align:center;padding:28px;background:var(--navy);color:#dbeafe;margin-top:40px}
@media(max-width:600px){section{padding:20px}nav{gap:12px}.hero-img{height:190px}th,td{padding:8px;font-size:13px}}
</style>
</head>
<body>
<header>
  <span class="tag">БІЛІМ • ТЕХНОЛОГИЯ • ДАМУ</span>
  <h1>АКТ студенттерінің оқу порталы</h1>
  <p>Ақпараттық-коммуникациялық технологиялар саласындағы білім, цифрлық дағдылар және студенттік өмір туралы ақпараттық веб-парақша.</p>
</header>
<nav>
  <a href="#about">Басты бет</a><a href="#directions">Бағыттар</a><a href="#schedule">Кесте</a><a href="#resources">Ресурстар</a><a href="#suzh">СӨЖ</a><a href="#form">Кері байланыс</a>
</nav>
<main>
<section id="about">
  <h2>Портал туралы</h2>
  <p class="lead">Бұл веб-сайт АКТ саласында білім алып жүрген студенттерге арналған. Мұнда оқу бағыттары, цифрлық құралдар, сабақ кестесінің үлгісі және студент туралы мәлімет енгізу формасы берілген.</p>
  <p>Ақпараттық-коммуникациялық технологиялар ақпаратты жинау, сақтау, өңдеу және таратуға арналған заманауи құралдар мен әдістерді қамтиды. АКТ білім беру, ғылым, экономика және күнделікті өмірде кеңінен қолданылады.</p>
  <img class="hero-img" src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=1400&q=80" alt="Компьютермен жұмыс істеп отырған студенттер">
</section>
<section id="directions">
  <h2>Оқу бағыттары</h2>
  <div class="grid">
    <div class="card"><h3>Веб-әзірлеу</h3><p>HTML және CSS көмегімен веб-беттердің құрылымы мен дизайнын жасау.</p></div>
    <div class="card"><h3>Деректермен жұмыс</h3><p>Ақпаратты кестелерде сақтау, жүйелеу және талдау.</p></div>
    <div class="card"><h3>Цифрлық сауаттылық</h3><p>Интернет ресурстарын қауіпсіз әрі тиімді пайдалану.</p></div>
  </div>
</section>
<section id="schedule">
  <h2>Сабақ кестесінің үлгісі</h2>
  <p>Төмендегі кесте оқу аптасын ұйымдастыруға арналған үлгі болып табылады.</p>
  <table>
    <thead><tr><th>Күн</th><th>Пән</th><th>Уақыты</th><th>Аудитория</th></tr></thead>
    <tbody>
      <tr><td>Дүйсенбі</td><td>Ақпараттық технологиялар</td><td>09:00–10:30</td><td>205</td></tr>
      <tr><td>Сейсенбі</td><td>Веб-технологиялар</td><td>10:40–12:10</td><td>310</td></tr>
      <tr><td>Сәрсенбі</td><td>Деректер қоры</td><td>09:00–10:30</td><td>212</td></tr>
      <tr><td>Бейсенбі</td><td>Компьютерлік графика</td><td>12:20–13:50</td><td>108</td></tr>
    </tbody>
  </table>
</section>
<section id="resources">
  <h2>Пайдалы ресурстар</h2>
  <p>Веб-технологияларды үйренуге арналған сенімді оқу материалдары:</p>
  <ul>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn_web_development" target="_blank" rel="noopener">MDN Web Docs</a> — HTML, CSS және веб-әзірлеу бойынша нұсқаулықтар.</li>
    <li><a href="https://github.com/" target="_blank" rel="noopener">GitHub</a> — жобалар кодын сақтау және бөлісу платформасы.</li>
    <li><a href="https://www.wix.com/" target="_blank" rel="noopener">Wix</a> — сайтты визуалды редактор арқылы құрастыру платформасы.</li>
  </ul>
</section>
<section id="suzh">
  <h2>СӨЖ тапсырмаларының кестесі</h2>
  <p>Студенттің өзіндік жұмысына арналған тапсырмалар мен бағалау көрсеткіштерінің үлгісі.</p>
  <table>
    <thead><tr><th>№</th><th>СӨЖ тақырыбы</th><th>Орындау мерзімі</th><th>Балл</th><th>Орындалуы</th></tr></thead>
    <tbody>
      <tr><td>1</td><td>HTML құрылымын зерттеу</td><td>1-апта</td><td>20</td><td>Орындалды</td></tr>
      <tr><td>2</td><td>CSS арқылы веб-бетті безендіру</td><td>2-апта</td><td>20</td><td>Орындалуда</td></tr>
      <tr><td>3</td><td>GitHub платформасымен жұмыс</td><td>3-апта</td><td>20</td><td>Жоспарда</td></tr>
      <tr><td>4</td><td>Жеке веб-сайт жобасын әзірлеу</td><td>4-апта</td><td>40</td><td>Жоспарда</td></tr>
    </tbody>
  </table>
  <p class="note">Кестедегі тақырыптар, мерзімдер мен балдар — тапсырманы көрсетуге арналған үлгі деректер.</p>
</section>
<section id="form">
  <h2>Студент туралы мәлімет</h2>
  <p>Форманы толтыру арқылы студент өз оқу бағыты мен қызығушылығы туралы ақпарат енгізе алады.</p>
  <form onsubmit="event.preventDefault(); alert('Мәлімет үлгі ретінде енгізілді. Бұл демонстрациялық форма, деректер серверге жіберілмейді.');">
    <div><label for="fullname">Аты-жөні</label><input id="fullname" name="fullname" type="text" placeholder="Аты-жөніңізді енгізіңіз" required></div>
    <div><label for="specialty">Мамандығы</label><input id="specialty" name="specialty" type="text" placeholder="Мысалы: Ақпараттық жүйелер"></div>
    <div><label for="course">Курс</label><select id="course" name="course"><option>1-курс</option><option>2-курс</option><option>3-курс</option><option>4-курс</option></select></div>
    <fieldset><legend>Қызығушылық бағыты</legend>
      <label><input type="checkbox" name="interest" value="web"> Веб-әзірлеу</label>
      <label><input type="checkbox" name="interest" value="design"> Дизайн</label>
      <label><input type="checkbox" name="interest" value="data"> Деректер</label>
    </fieldset>
    <div><label for="aboutstudent">Өзіңіз туралы</label><textarea id="aboutstudent" name="aboutstudent" rows="4" placeholder="Қысқаша ақпарат жазыңыз..."></textarea></div>
    <button type="submit">Жіберу</button>
    <p class="note">Ескерту: бұл оқу тапсырмасына арналған демонстрациялық форма. Енгізілген мәліметтер сақталмайды және серверге жіберілмейді.</p>
  </form>
</section>
</main>
<footer>© 2026 АКТ студенттерінің оқу порталы · Оқу мақсатында әзірленді</footer>
</body>
</html> 
