<!--

author:   Masub Makhdoom
email:    masub.makhdoom@ovgu.de
date:     27/01/2026
version:  30.0.0
language: en
narrator: UK English Female

repository: https://github.com/LiaScript/docs

logo:     img/logo.png

comment:  This document shall provide an entire compendium and course on the
          development of Open-courSes with [LiaScript](https://LiaScript.github.io).
          As the language and the systems grows, also this document will be updated.
          Feel free to fork or copy it, translations are very welcome...

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

link: https://raw.githubusercontent.com/OVGU-VET-TechEd/Integrating_AI_in_TVET_UNESCO/refs/heads/main/VorlageUN.css

link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css

import:   https://raw.githubusercontent.com/liaTemplates/ABCjs/main/README.md

link:     https://fonts.googleapis.com/css2?family=Noto+Sans+Egyptian+Hieroglyphs
          https://fonts.googleapis.com/css2?family=Noto+Sans+Ogham

font:     Noto Sans Egyptian Hieroglyphs, Noto Sans Ogham

-->

# Kapitel 1 – Übungsmaterial
## Difficult

---

# 1. Hören

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio_Test/VD.mp3?raw=true)

1. [[082481999]]  
2. [[03515482380]]  
3. [[03017741228]]

---

# 2. Lesen

Das ist Timo Schmidt. Er kommt aus Tübingen. Er wohnt in Brasilien. Er spricht Deutsch und Spanisch.

1. Wie heißt er?  
   [[Timo Schmidt]]

2. Woher kommt er?  
   [[Tübingen]]

3. Wo wohnt er?  
   [[Brasilien]]

---

# 3. Schreiben

> Sehen Sie das Bild. Füllen Sie dann die formelle Vorstellung aus.

<svg xmlns="http://www.w3.org/2000/svg" width="960" height="360" viewBox="0 0 960 360">
  <rect width="960" height="360" fill="#eef6ff"/>
  <rect x="30" y="25" width="900" height="310" rx="22" fill="#ffffff" stroke="#cfe3ff" stroke-width="3"/>

  

  <rect x="345" y="60" width="500" height="50" rx="12" fill="#e8f4ff"/>
  <text x="370" y="92" font-size="23" font-family="Arial" fill="#0b2a66">👤 First Name: Daniel</text>

  <rect x="345" y="125" width="500" height="50" rx="12" fill="#eefbea"/>
  <text x="370" y="157" font-size="23" font-family="Arial" fill="#1f6b2d">👤 Family Name : Weber</text>

  <rect x="345" y="190" width="500" height="50" rx="12" fill="#fff7e8"/>
  <text x="370" y="222" font-size="23" font-family="Arial" fill="#9a5b00">🌍 Country: Österreich</text>

  <text x="45" y="315" font-size="18" font-family="Arial" fill="#5b6780">Hinweis: Schreiben Sie formell.</text>
</svg>
 ### Füllen Sie aus:

1. Guten Tag.  
2. Ich heiße [[Daniel Weber]].  
3. [[ Mein Vorname ]] ist Daniel.  
4. [[ Mein Familienname ]] ist Weber.  
5. Ich komme aus [[Österreich]].

# 🤖 My Bot

<section style="border:1px solid #ddd;border-radius:16px;padding:14px;max-width:900px;background:#fafafa">
  <h3 style="margin:0 0 8px 0"> Please click the Start button to initiate the interaction 😊</h3>

  <div id="bot-box"
       style="min-height:180px;white-space:pre-wrap;overflow:auto;border:1px solid #eee;border-radius:12px;padding:12px;background:white">
  </div>

  <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px">
    <button id="btn-start" style="padding:10px 14px;border-radius:12px;border:1px solid #ddd;background:#fff;cursor:pointer">
      Start
    </button>
    <button id="btn-yes" disabled style="padding:10px 14px;border-radius:12px;border:1px solid #ddd;background:#fff;cursor:pointer">
      ✅ Yes
    </button>
    <button id="btn-no" disabled style="padding:10px 14px;border-radius:12px;border:1px solid #ddd;background:#fff;cursor:pointer">
      ❌ No
    </button>
  </div>

  <div id="bot-links" style="margin-top:12px;display:none;padding:10px;border-radius:12px;border:1px dashed #ddd;background:#fff">
  </div>
</section>

<script>
(() => {
  const box = document.getElementById("bot-box");
  const links = document.getElementById("bot-links");
  const btnStart = document.getElementById("btn-start");
  const btnYes = document.getElementById("btn-yes");
  const btnNo = document.getElementById("btn-no");

  // Very Difficult → Mixed
  const NEXT_TITLE = "Next Category: Mixed";
  const NEXT_LINK  = "https://liascript.github.io/course/?https://raw.githubusercontent.com/Masub27/A1-German-Tool/refs/heads/main/Audio_Test/mixed.md";

  // Optional back link to Difficult
  const BACK_TITLE = "Go back to Difficult";
  const BACK_LINK  = "https://liascript.github.io/course/?https://raw.githubusercontent.com/Masub27/A1-German-Tool/refs/heads/main/Audio_Test/Difficult.md";

  // Repeat same category
  const REVIEW_TITLE = "Repeat / Review this category";
  const REVIEW_LINK  = "#";

  function say(text) {
    box.textContent += (box.textContent ? "\n\n" : "") + text;
    box.scrollTop = box.scrollHeight;
  }

  function enableAnswers() {
    btnYes.disabled = false;
    btnNo.disabled = false;
  }

  function disableAll() {
    btnStart.disabled = true;
    btnYes.disabled = true;
    btnNo.disabled = true;
  }

  function showLinks(html) {
    links.style.display = "block";
    links.innerHTML = html;
  }

  btnStart.addEventListener("click", () => {
    box.textContent = "";
    links.style.display = "none";
    links.innerHTML = "";
    say("❓ Are you satisfied with your performance?");
    say("👇 Click on the options below to see what is next.");
    enableAnswers();
  });

  btnYes.addEventListener("click", () => {
    disableAll();
    say("🎉 Congratulations!");
    say("✅ You have completed difficult level.");
    say("🎯 You are now ready for very difficult level.");
    showLinks(`
      <div style="font-size:16px"><b>Go next:</b></div>
      <ul style="margin:8px 0 0 18px">
        <li>➡️ <a href="${NEXT_LINK}" target="_blank" rel="noopener">${NEXT_TITLE}</a></li>
      </ul>
    `);
  });

  btnNo.addEventListener("click", () => {
    disableAll();
    say("💡 No worries — this difficulty level is quite challenging.");
    say("📌 My honest suggestion: you should try moderate level and then move to  difficult level again.");
    say("🔁 Or repeat the same difficulty level once more.");
    showLinks(`
      <div style="font-size:16px"><b>Choose:</b></div>
      <ul style="margin:8px 0 0 18px">
        <li>🔁 <a href="${REVIEW_LINK}">${REVIEW_TITLE}</a></li>
        <li>⬅️ <a href="${BACK_LINK}" target="_blank" rel="noopener">${BACK_TITLE}</a></li>
        <li>➡️ Continue anyway: <a href="${NEXT_LINK}" target="_blank" rel="noopener">${NEXT_TITLE}</a></li>
      </ul>
    `);
  });
})();
</script>
