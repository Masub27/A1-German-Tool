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
## Very Easy

> Thema: Begrüßung, Name, Herkunft, Sprache

---

# 1. Hören

> Hören Sie und wählen Sie die richtige Antwort.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio_Test/V.S.mp3?raw=true)

1. Was sagt die Frau?

   [[x]] Guten Tag.
   [[ ]] Auf Wiedersehen.
   [[ ]] Bis morgen.

2. Wie heißt die Frau?

   [[x]] Angelika Kessler
   [[ ]] Emma Larsson
   [[ ]] Paula Koch

3. Woher kommt Frau Larsson?

   [[ ]] Berlin
   [[x]] Stockholm
   [[ ]] Wien

---

# 2. Lesen

> Lesen Sie den Text und beantworten Sie die Fragen.

Anna: Hallo! Ich heiße Anna Meier. Ich komme aus Deutschland. Ich wohne in Berlin. Ich spreche Deutsch und Englisch.

1. Wie heißt sie? 
   [[Anna Meier]]

2. Woher kommt sie?  
   [[aus Deutschland]]

3. Wo wohnt sie?  
   [[in Berlin]]

4. Welche Sprachen spricht sie?  
   [[Deutsch und Englisch]]

---

# 3. Schreiben

> Füllen Sie die Lücken aus.

1. Ich heiße [[Masub]]  
2. Ich komme aus [[Pakistan]]  
3. Ich spreche [[English]]
---

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
    say("✅ You have completed very easy level.");
    say("🎯 You are now ready for next easy level.");
    showLinks(`
      <div style="font-size:16px"><b>Go next:</b></div>
      <ul style="margin:8px 0 0 18px">
        <li>➡️ <a href="${NEXT_LINK}" target="_blank" rel="noopener">${NEXT_TITLE}</a></li>
      </ul>
    `);
  });

  btnNo.addEventListener("click", () => {
    disableAll();
    say("💡 No worries ");
    
    say("🔁 repeat the same level once more.");
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