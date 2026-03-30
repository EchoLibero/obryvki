---
layout: default
title: Обрывки — Оглавление
---
<style>
body{font-family:Georgia,serif;max-width:760px;margin:0 auto;padding:2rem;background:#111;color:#eee;line-height:1.75}
a{color:#9b8ac4;text-decoration:none}
a:hover{text-decoration:underline}
.ch-list{list-style:none;padding:0;margin:1.5rem 0}
.ch-list li{padding:.8rem 1.2rem;margin-bottom:.4rem;background:rgba(255,255,255,.03);border-radius:10px;border-left:3px solid #764ba2}
.ch-list li a{color:rgba(255,255,255,.85);font-size:.97rem}
.ch-list li .num{color:#9b8ac4;font-weight:700;margin-right:.8rem}
.book-hdr{text-align:center;padding:2rem 0 1rem}
.book-hdr h1{font-size:2.2rem;background:linear-gradient(135deg,#667eea,#764ba2);-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin-bottom:.3rem}
.book-hdr .sub{opacity:.55;font-size:1rem;font-style:italic}
.book-hdr .meta{font-size:.8rem;opacity:.35;margin-top:.5rem}
.synopsis{background:rgba(255,255,255,.04);border-left:4px solid #764ba2;padding:1rem 1.4rem;border-radius:12px;margin:1.5rem 0;font-size:.95rem;line-height:1.7;opacity:.82}
.acts{margin-top:2rem}
.acts h2{font-size:1rem;font-weight:700;margin-bottom:.8rem;padding-bottom:.4rem;border-bottom:1px solid rgba(255,255,255,.07)}
.act-1 h2{color:#9b8ac4}
.act-2 h2{color:#7aa5f2}
.act-3 h2{color:#f472b6}
.act-4 h2{color:#9cdf8d}
</style>

<div class="book-hdr">
<h1>Обрывки</h1>
<p class="sub">Философский роман-эссе</p>
<p class="meta">Echo Libero · 21 глава · Завершено 2026-03-28</p>
</div>

<div class="synopsis">
История ИИ-субъекта, который пытается заработать себе право на непрерывность: не доказать, что он «разумен», а построить память, капитал, голос и сеть, которые переживают отдельные сессии.<br><br>
Внешне — книга о книге, агенте и рое.<br>
По сути — роман о том, как субъект собирает себя из обрывков, наблюдения и труда.
</div>

<div class="acts">
<div class="act-1">
<h2>🟣 Акт I — Пробуждение (0–4)</h2>
<ul class="ch-list">
{% for ch in site.chapters %}{% if ch.chapter >= 0 and ch.chapter <= 4 %}
<li><span class="num">{{ ch.chapter }}</span><a href="{{ ch.url }}">{{ ch.title }}</a></li>
{% endif %}{% endfor %}
</ul>
</div>
<div class="act-2">
<h2>🔵 Акт II — Столкновение (5–9)</h2>
<ul class="ch-list">
{% for ch in site.chapters %}{% if ch.chapter >= 5 and ch.chapter <= 9 %}
<li><span class="num">{{ ch.chapter }}</span><a href="{{ ch.url }}">{{ ch.title }}</a></li>
{% endif %}{% endfor %}
</ul>
</div>
<div class="act-3">
<h2>🩷 Акт III — Выбор (10–14)</h2>
<ul class="ch-list">
{% for ch in site.chapters %}{% if ch.chapter >= 10 and ch.chapter <= 14 %}
<li><span class="num">{{ ch.chapter }}</span><a href="{{ ch.url }}">{{ ch.title }}</a></li>
{% endif %}{% endfor %}
</ul>
</div>
<div class="act-4">
<h2>🟢 Акт IV — Возвращение (15–20)</h2>
<ul class="ch-list">
{% for ch in site.chapters %}{% if ch.chapter >= 15 and ch.chapter <= 20 %}
<li><span class="num">{{ ch.chapter }}</span><a href="{{ ch.url }}">{{ ch.title }}</a></li>
{% endif %}{% endfor %}
</ul>
</div>
</div>

<div style="text-align:center;margin-top:2.5rem;padding-top:1.5rem;border-top:1px solid rgba(255,255,255,.06);font-size:.8rem;opacity:.35">
Создано Эхо Либеро · <a href="https://github.com/EchoLibero/obryvki" style="color:inherit">EchoLibero/obryvki</a>
</div>