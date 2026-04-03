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
## Moderate

---

# 1. Hören
?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio_Test/M.mp3?raw=true)

1. [[Hallo]]  
2. [[Ich heiße Luis]]  
3. [[Ich komme aus Spanien]]  
4. [[Wie heißt du?]]  
5. [[Woher kommst du?]]

---

# 2. Lesen

Das ist Zeynep. Sie kommt aus Stuttgart. Sie wohnt in Shanghai.

1. Woher kommt sie?  
   [[Stuttgart]]

2. Wo wohnt sie?  
   [[Shanghai]]

---

# 3. Schreiben

> Sehen Sie das Bild. Füllen Sie dann die Sätze aus.

<svg xmlns="http://www.w3.org/2000/svg" width="950" height="360" viewBox="0 0 950 360">
  <rect width="950" height="360" fill="#eef6ff"/>
  <rect x="30" y="25" width="890" height="310" rx="22" fill="#ffffff" stroke="#cfe3ff" stroke-width="3"/>

  <circle cx="140" cy="115" r="40" fill="#d9ecff"/>
  <rect x="95" y="160" width="90" height="58" rx="18" fill="#d9ecff"/>
  <rect x="85" y="235" width="110" height="35" rx="10" fill="#e8f4ff"/>
  <text x="110" y="259" font-size="20" font-family="Arial" fill="#0b2a66">Mila</text>

  <rect x="255" y="50" width="560" height="45" rx="12" fill="#e8f4ff"/>
  <text x="280" y="79" font-size="22" font-family="Arial" fill="#0b2a66">👤 Person: Mila</text>

  <rect x="255" y="110" width="560" height="45" rx="12" fill="#eefbea"/>
  <text x="280" y="139" font-size="22" font-family="Arial" fill="#1f6b2d">🏙 Stadt: Berlin</text>

  <rect x="255" y="170" width="560" height="45" rx="12" fill="#fff7e8"/>
  <text x="280" y="199" font-size="22" font-family="Arial" fill="#9a5b00">🎓 Studium: Medizin</text>

  <rect x="255" y="230" width="560" height="45" rx="12" fill="#f3edff"/>
  <text x="280" y="259" font-size="22" font-family="Arial" fill="#5b3ea6">🗣 Sprache: Deutsch und Englisch</text>

  <text x="45" y="315" font-size="18" font-family="Arial" fill="#5b6780">Hinweis: Schreiben Sie über eine Person.</text>
</svg>

  ## Füllen Sie aus:

1. [[ Das ist ]] Mila.  
2. [[ Sie wohnt in ]] Berlin.  
3. [[ Sie studiert ]] Medizin.  
4. [[ Sie spricht ]] Deutsch und Englisch.

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
    say("✅ You have completed moderate  level.");
    say("🎯 You are now ready to move next difficult level.");
    showLinks(`
      <div style="font-size:16px"><b>Go next:</b></div>
      <ul style="margin:8px 0 0 18px">
        <li>➡️ <a href="${NEXT_LINK}" target="_blank" rel="noopener">${NEXT_TITLE}</a></li>
      </ul>
    `);
  });

  btnNo.addEventListener("click", () => {
    disableAll();
    say("💡 No worries — this moderate  level is quite challenging.");
    say("📌 My honest suggestion: you should try very easy  and then move to  difficult level again.");
    say("🔁 Or repeat the same moderate  level once more.");
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
