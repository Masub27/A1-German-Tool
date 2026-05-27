<!--

author:   kanwal & Makhdoom
email:    masub.makhdoom@ovgu.de
date:     09/04/2026
version:  30.0.0
language: en
narrator: EU German

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

@style
<style>
:root{
  --green:#9fb522;
  --light:#f7faf0;
  --line:#d9dfc6;
  --blue:#eaf3ff;
  --text:#263238;
}
body{
  font-family: Arial, sans-serif;
}
.lesson-box{
  background: linear-gradient(135deg,#f7faf0,#ffffff);
  border: 2px solid var(--line);
  border-radius: 18px;
  padding: 22px;
  margin: 16px 0;
  box-shadow: 0 6px 18px rgba(0,0,0,.08);
}
.unit-title{
  display:flex;
  align-items:center;
  gap:14px;
  font-size:30px;
  font-weight:800;
  color:#2f3b1f;
}
.circle-no{
  width:48px;
  height:48px;
  border-radius:50%;
  background:var(--green);
  color:white;
  display:inline-flex;
  align-items:center;
  justify-content:center;
  font-size:26px;
  font-weight:800;
}
.task-title{
  font-size:19px;
  font-weight:700;
  color:#333;
  margin-bottom:12px;
}
.photo-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:24px;
}
.photo-card{
  border:2px solid #d7d7d7;
  border-radius:14px;
  background:#ffffff;
  padding:12px;
}
.photo-label{
  width:34px;
  height:34px;
  border-radius:50%;
  background:#ffffff;
  border:2px solid #cfcfcf;
  display:flex;
  align-items:center;
  justify-content:center;
  font-weight:800;
  margin-bottom:8px;
}
.scene{
  height:230px;
  border-radius:12px;
  background:linear-gradient(135deg,#dce8f5,#f5efe1);
  border:1px solid #ccc;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:#555;
  font-size:17px;
  padding:18px;
}
.answer-line{
  margin-top:12px;
  font-size:18px;
}
.dialogue{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:28px;
}
.dialogue-card{
  background:#ffffff;
  border:2px solid #e2e7d3;
  border-radius:16px;
  padding:18px;
}
.dialogue-card h3{
  margin-top:0;
  color:#627600;
}
.speaker1{
  color:#455a64;
  font-weight:700;
}
.speaker2{
  color:#795548;
  font-weight:700;
}
.line{
  margin:9px 0;
  line-height:1.45;
}
.info-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:22px;
}
.info-card{
  background:#ffffff;
  border-left:7px solid var(--green);
  border-radius:14px;
  padding:16px;
  box-shadow:0 3px 10px rgba(0,0,0,.06);
}
.speech-bubble{
  display:inline-block;
  background:#eaf3ff;
  border:2px solid #9bbce2;
  border-radius:14px;
  padding:14px 22px;
  font-size:20px;
  font-weight:600;
  margin-top:12px;
}
.small-note{
  font-size:15px;
  color:#666;
}
@media(max-width:800px){
  .photo-grid,.dialogue,.info-grid{
    grid-template-columns:1fr;
  }
}
</style>
@end
-->

# Research Notice

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">

<defs>

<linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
  <stop offset="0%" stop-color="#d7e06a"/>
  <stop offset="100%" stop-color="#c8d653"/>
</linearGradient>

<linearGradient id="glass" x1="0" y1="0" x2="1" y2="1">
  <stop offset="0%" stop-color="rgba(255,255,255,0.72)"/>
  <stop offset="100%" stop-color="rgba(255,255,255,0.38)"/>
</linearGradient>

<filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
  <feDropShadow dx="0" dy="12" stdDeviation="18"
                flood-color="#7f8d2d"
                flood-opacity="0.22"/>
</filter>

<filter id="blur">
  <feGaussianBlur stdDeviation="1.2"/>
</filter>

<style><![CDATA[

.bigWatermark{
  font-family:Arial,sans-serif;
  font-size:190px;
  font-weight:700;
  fill:#ffffff;
  opacity:0.22;
}

.midWatermark{
  font-family:Arial,sans-serif;
  font-size:72px;
  font-weight:700;
  fill:#ffffff;
  opacity:0.24;
}

.noticeTitle{
  font-family:Georgia,serif;
  font-size:60px;
  font-weight:700;
  fill:#9e1111;
}

.noticeText{
  font-family:Arial,sans-serif;
  font-size:34px;
  font-weight:600;
  fill:#222;
}

.footer{
  font-family:Arial,sans-serif;
  font-size:22px;
  fill:#555;
}

]]></style>

</defs>

<!-- Background -->
<rect width="1600" height="900" fill="url(#bg)"/>

<!-- Watermark -->
<g transform="rotate(-28 800 450)" filter="url(#blur)">

  <text x="120" y="470" class="bigWatermark">
    Kurs DaF
  </text>

  <text x="980" y="470"
        style="font-family:Arial,sans-serif;
               font-size:90px;
               font-weight:700;
               fill:white;
               opacity:0.22;">
    A1
  </text>

  <text x="320" y="590" class="midWatermark">
    Deutsch für Studium und Beruf
  </text>

  <text x="250" y="680" class="midWatermark">
    Kurs- und Übungsbuch mit Audios und Videos
  </text>

</g>

<!-- Watermark Device Icon -->
<g opacity="0.18" transform="translate(1180 520) scale(1.3)">

  <rect x="0" y="0" width="260" height="200"
        rx="20"
        fill="#ffffff"/>

  <path d="M70 60 L130 30 L190 60 L130 90 Z"
        fill="none"
        stroke="#222"
        stroke-width="8"/>

  <rect x="55" y="110" width="55" height="70"
        rx="8"
        fill="none"
        stroke="#222"
        stroke-width="7"/>

  <rect x="150" y="110" width="55" height="70"
        rx="8"
        fill="none"
        stroke="#222"
        stroke-width="7"/>

  <line x1="110" y1="145"
        x2="150" y2="145"
        stroke="#222"
        stroke-width="7"/>

</g>

<!-- Glass Card -->
<g filter="url(#shadow)">

  <rect x="150" y="110"
        width="1300"
        height="270"
        rx="34"
        fill="white"
        opacity="0.30"
        stroke="white"
        stroke-width="2"/>

  <!-- Glass Highlight -->
  <rect x="170" y="130"
        width="1260"
        height="90"
        rx="24"
        fill="white"
        opacity="0.18"/>

</g>

<!-- Notice Text -->
<text x="800"
      y="205"
      text-anchor="middle"
      class="noticeTitle">
  This is only for research purposes
</text>

<text x="800"
      y="280"
      text-anchor="middle"
      class="noticeTitle">
  not for publication.
</text>

<line x1="330" y1="325"
      x2="1270" y2="325"
      stroke="#caa5a5"
      stroke-width="3"/>

<!-- Footer Glass -->
<g filter="url(#shadow)">

  <rect x="390" y="735"
        width="820"
        height="72"
        rx="22"
        fill="white"
        opacity="0.28"
        stroke="white"
        stroke-width="1.5"/>

</g>

<text x="800"
      y="780"
      text-anchor="middle"
      class="footer">
  German A1.1 Learning Material • LiaScript Research Project
</text>

</svg>

# Kapitel 3

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">

<defs>
  <linearGradient id="bg3" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#f8faf4"/>
    <stop offset="100%" stop-color="#ffffff"/>
  </linearGradient>

  <linearGradient id="green3" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#93a82b"/>
    <stop offset="100%" stop-color="#bfd157"/>
  </linearGradient>

  <filter id="shadow3" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="0" dy="12" stdDeviation="18" flood-color="#7f8d2d" flood-opacity="0.20"/>
  </filter>

  <style><![CDATA[
    .num{
      font-family:Georgia,serif;
      font-size:170px;
      font-weight:700;
      fill:#dce7bf;
    }
    .title{
      font-family:Georgia,serif;
      font-size:58px;
      font-weight:700;
      fill:#7d9129;
    }
    .subtitle{
      font-family:Arial,sans-serif;
      font-size:25px;
      font-weight:600;
      fill:#4f584a;
    }
    .head{
      font-family:Georgia,serif;
      font-size:31px;
      font-weight:700;
      fill:#7d9129;
    }
    .text{
      font-family:Arial,sans-serif;
      font-size:23px;
      fill:#263238;
    }
    .chip{
      font-family:Arial,sans-serif;
      font-size:23px;
      font-weight:700;
      fill:#ffffff;
    }
    .footer{
      font-family:Arial,sans-serif;
      font-size:20px;
      fill:#6e7668;
    }
  ]]></style>
</defs>

<rect width="1600" height="900" fill="url(#bg3)"/>

<circle cx="1360" cy="150" r="190" fill="#edf4de"/>
<circle cx="250" cy="770" r="190" fill="#eff5e1"/>
<circle cx="1500" cy="760" r="120" fill="#f3f7ea"/>

<g filter="url(#shadow3)">
  <rect x="85" y="80" width="1430" height="740" rx="36" fill="#ffffff" stroke="#dce6cb" stroke-width="2"/>
</g>

<rect x="120" y="115" width="230" height="58" rx="18" fill="url(#green3)"/>
<text x="235" y="153" text-anchor="middle" class="chip">KAPITEL</text>

<text x="135" y="325" class="num">3</text>

<text x="360" y="275" class="title">Ein leerer Bauch</text>
<text x="360" y="345" class="title">studiert nicht gern</text>

<text x="360" y="415" class="subtitle">
Lebensmittel • Gerichte • Speiseplan • Café • Bestellen und Bezahlen
</text>

<!-- Left Card -->
<rect x="145" y="510" width="410" height="205" rx="24" fill="#f8fbf3" stroke="#dfe8cb"/>
<text x="180" y="560" class="head">📘 Wortfelder</text>
<text x="180" y="610" class="text">• Lebensmittel</text>
<text x="180" y="645" class="text">• Gerichte und Speisekarte</text>
<text x="180" y="680" class="text">• Wochentage</text>

<!-- Center Card -->
<rect x="600" y="510" width="480" height="205" rx="24" fill="#f8fbf3" stroke="#dfe8cb"/>
<text x="635" y="560" class="head">💬 Kommunikation</text>
<text x="635" y="610" class="text">• Speiseplan verstehen</text>
<text x="635" y="645" class="text">• im Café bestellen</text>
<text x="635" y="680" class="text">• Meinung äußern</text>

<!-- Right Card -->
<rect x="1135" y="510" width="310" height="205" rx="24" fill="#f8fbf3" stroke="#dfe8cb"/>
<text x="1170" y="560" class="head">✏️ Grammatik</text>
<text x="1170" y="610" class="text">• können, wollen</text>
<text x="1170" y="645" class="text">• möcht-, mögen</text>
<text x="1170" y="680" class="text">• denn, aber</text>

<line x1="140" y1="770" x2="1460" y2="770" stroke="#dbe4c5" stroke-width="2"/>

<text x="140" y="808" class="footer">
Deutsch A1.1 • Kapitel 3 • Kurs- und Übungsbuch
</text>

<text x="1460" y="808" text-anchor="end" class="footer">
Mensa • Café • Lebensmittel
</text>

</svg>

    --{{0}}--
Hello everyone! Welcome to Kapitel 3: Ein leerer Bauch studiert nicht gern. In this chapter, we learn important German words about food, meals, cafés, and university life. We talk about Lebensmittel, Gerichte, Speisekarten, and Wochentage. You will learn how to understand a Speiseplan and how to order food and drinks in a Café. You will also practice how to give your opinion about food and meals in German.
In grammar, we study the modal verbs können, wollen, möchten, and mögen. We also learn how to connect sentences with denn and aber.


# 🤖 Offline Chatbot – Kapitel 3

<div id="c3bot" style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:3px solid #9fb522;border-radius:22px;padding:24px;box-shadow:0 8px 22px rgba(0,0,0,.12);">

<h2>🤖 Kapitel 3 Lern-Bot</h2>

<p>Ask me about food, Mensa, Café, grammar, ordering, and sentence structure.</p>

<div id="c3-output" style="background:white;border-left:8px solid #9fb522;border-radius:16px;padding:18px;min-height:130px;line-height:1.7;margin-bottom:14px;">
<b>Bot:</b> Hallo! Ask me about Kapitel 3 😊
</div>

<input id="c3-input" placeholder="Example: What is denn?" style="width:72%;padding:13px;border:2px solid #9fb522;border-radius:12px;font-size:16px;">

<button id="c3-ask" type="button" style="padding:13px 18px;border-radius:12px;border:none;background:#9fb522;color:white;font-weight:bold;">
Ask
</button>

<button id="c3-clear" type="button" style="padding:13px 18px;border-radius:12px;border:1px solid #9fb522;background:white;color:#6f8120;font-weight:bold;">
Clear
</button>

<h3>💡 Quick Questions</h3>
<div id="c3-quick" style="display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:10px;"></div>

</div>

<script>
void setTimeout(function(){

  const output = document.getElementById("c3-output");
  const input = document.getElementById("c3-input");
  const askBtn = document.getElementById("c3-ask");
  const clearBtn = document.getElementById("c3-clear");
  const quickBox = document.getElementById("c3-quick");

  const questions = [
    "What is Chapter 3 about?",
    "What are Lebensmittel?",
    "What are Gerichte?",
    "What are Milchprodukte?",
    "What are Obst and Früchte?",
    "What are Gemüse words?",
    "What are Beilagen?",
    "What is Fleisch?",
    "What is Fisch?",
    "What is Mensa?",
    "What does Schnipo mean?",
    "What does vegan mean?",
    "What is können?",
    "What is wollen?",
    "What is möchten?",
    "What is mögen?",
    "What is denn?",
    "What is aber?",
    "How to order in a café?",
    "What is the sentence position rule?"
  ];

  function normalize(text){
    return String(text || "")
      .toLowerCase()
      .replace(/ä/g,"ae")
      .replace(/ö/g,"oe")
      .replace(/ü/g,"ue")
      .replace(/ß/g,"ss")
      .replace(/[^\w\s@.-]/g," ")
      .replace(/\s+/g," ")
      .trim();
  }

  function answer(q){
    q = normalize(q);

    if(q.includes("chapter 3") || q.includes("kapitel 3"))
      return "Kapitel 3 is about food, meals, Mensa, Café, ordering, paying, and grammar with können, wollen, möchten, mögen, denn and aber.";

    if(q.includes("lebensmittel"))
      return "Lebensmittel means food items. Examples: Quark, Wurst, Eier, Butter, Kartoffeln, Nudeln, Milch, Käse, Eis.";

    if(q.includes("gerichte"))
      return "Gerichte means dishes or meals. Examples: Milchreis mit Früchten, Lachs mit Reis, Rührei, Gulasch, Gemüse-Reis-Pfanne.";

    if(q.includes("milchprodukte"))
      return "Milchprodukte are dairy products. Examples: Quark, Butter, Milch, Käse, Eis.";

    if(q.includes("obst") || q.includes("fruechte") || q.includes("fruchte"))
      return "Obst / Früchte are fruits. Examples: Erdbeeren, Kirschen, Äpfel.";

    if(q.includes("gemuese") || q.includes("gemuse"))
      return "Gemüse means vegetables. Examples: Tomaten, Salat, Karotten, Paprika, Pilze or Champignons.";

    if(q.includes("beilagen"))
      return "Beilagen are side dishes. Examples: Kartoffeln, Nudeln, Pommes frites, Reis.";

    if(q.includes("fleisch"))
      return "Fleisch means meat. Examples: Wurst, Schnitzel, Hähnchen, Hackfleisch.";

    if(q.includes("fisch"))
      return "Fisch means fish. Examples: Hering and Lachs.";

    if(q.includes("mensa"))
      return "Mensa means university cafeteria. Students can eat there cheaply. Example: In der Mensa kann man gut und günstig essen.";

    if(q.includes("schnipo"))
      return "Schnipo means Schnitzel mit Pommes frites. It is a short informal word.";

    if(q.includes("vegan"))
      return "Vegan means no animal products. Example: Anne isst vegan und kann keine Milchprodukte essen.";

    if(q.includes("koennen") || q.includes("konnen"))
      return "können means can or be able to. Examples: ich kann, du kannst, er kann, wir können, ihr könnt, sie können.";

    if(q.includes("wollen"))
      return "wollen means want to. Examples: ich will, du willst, er will, wir wollen, ihr wollt, sie wollen.";

    if(q.includes("moechten") || q.includes("mochten"))
      return "möchten is polite and means would like. Example: Ich möchte einen Kaffee. Wir möchten gern bestellen.";

    if(q.includes("moegen") || q.includes("mogen"))
      return "mögen means to like. Examples: ich mag, du magst, er mag, wir mögen. Example: Ich mag keinen Fisch.";

    if(q.includes("denn"))
      return "denn means because. It connects two main clauses. Example: Ich esse vegan, denn ich liebe Tiere. The verb stays in position 2.";

    if(q.includes("aber"))
      return "aber means but. Example: Die Gemüsepizza ist vegetarisch, aber sie ist nicht vegan.";

    if(q.includes("order") || q.includes("bestellen") || q.includes("cafe"))
      return "To order in a café: Wir möchten gern bestellen. Ich nehme einen Espresso. Eine Cola, bitte. Wir möchten gern bezahlen.";

    if(q.includes("position") || q.includes("satzbau") || q.includes("word order"))
      return "German sentence rule: the conjugated verb stays in position 2. Example: Heute esse ich in der Mensa. Pizza gibt es am Donnerstag.";

    return "Ask me about Kapitel 3: Lebensmittel, Gerichte, Mensa, Café, können, wollen, möchten, mögen, denn, aber, or Satzbau.";
  }

  function ask(q){
    const question = q || input.value.trim();
    if(!question) return;

    output.innerHTML += "<br><br><b>You:</b> " + question;
    output.innerHTML += "<br><b>Bot:</b> " + answer(question);
    input.value = "";
    output.scrollTop = output.scrollHeight;
  }

  askBtn.addEventListener("click", function(){ ask(); });

  clearBtn.addEventListener("click", function(){
    output.innerHTML = "<b>Bot:</b> Hallo! Ask me about Kapitel 3 😊";
  });

  input.addEventListener("keydown", function(e){
    e.stopPropagation();
    if(e.key === "Enter"){
      e.preventDefault();
      ask();
    }
  });

  questions.forEach(function(q){
    const btn = document.createElement("button");
    btn.textContent = q;
    btn.style.padding = "10px 14px";
    btn.style.borderRadius = "12px";
    btn.style.border = "1px solid #cfe3ff";
    btn.style.background = "#eef7ff";
    btn.style.color = "#0b2a66";
    btn.style.fontWeight = "bold";
    btn.style.cursor = "pointer";
    btn.addEventListener("click", function(){ ask(q); });
    quickBox.appendChild(btn);
  });

}, 800);
</script>
# 3 Ein leerer Bauch studiert nicht gern

 ## 1 Gerichte und Lebensmittel

 ## a) Kennen Sie die Gerichte und Lebensmittel? Ordnen Sie sie den Kategorien zu. Was können Sie nicht zuordnen?

<div style="background:linear-gradient(135deg,#f4faf6,#ffffff);border:2px solid #d8e8d2;border-radius:24px;padding:24px;">

 ## 🍽️ Gerichte



![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_3/chapter3_1.jpg?raw=true)

</div>



---

 ## 🧺 Lebensmittel-Wörter

<div style="background:#f8fbff;border:1px solid #d9e7ff;border-radius:20px;padding:18px;line-height:2;">

Quark · Wurst · Hering · Erdbeeren · Eier · Butter · Kirschen · Pilze / Champignons · Kartoffeln · Nudeln · Äpfel · Schnitzel · Tomaten · Salat · Karotten · Kuchen · Pommes frites · Milch · Paprika · Käse · Eis

</div>

---

 ## Ordnen Sie zu

<div style="display:grid;grid-template-columns:repeat(6,1fr);gap:14px;">

<div style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:18px;padding:16px;">
<h3>🥛 Milchprodukte</h3>

- [[Quark]]
- [[Butter]]
- [[Milch]]
- [[Käse]]
- [[Eis]]
</div>

<div style="background:#fff4f8;border:1px solid #efcad8;border-radius:18px;padding:16px;">
<h3>🍎 Obst / Früchte</h3>

- [[Erdbeeren]]
- [[Kirschen]]
- [[Äpfel]]
</div>

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:16px;">
<h3>🥕 Gemüse</h3>

- [[Pilze / Champignons]]
- [[Tomaten]]
- [[Salat]]
- [[Karotten]]
- [[Paprika]]
</div>

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:16px;">
<h3>🥔 Beilagen</h3>

- [[Kartoffeln]]
- [[Nudeln]]
- [[Pommes frites]]
</div>

<div style="background:#fff4f4;border:1px solid #efcaca;border-radius:18px;padding:16px;">
<h3>🥩 Fleisch</h3>

- [[Wurst]]
- [[Schnitzel]]
</div>

<div style="background:#f1fbff;border:1px solid #c9e8f5;border-radius:18px;padding:16px;">
<h3>🐟 Fisch</h3>

- [[Hering]]
- [[Lachs]]
</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you need to sort food words into the correct food categories.  
First, read each category title carefully:

- 🥛 Milchprodukte = Foods made from milk  
- 🍎 Obst / Früchte = Fruits  
- 🥕 Gemüse = Vegetables  
- 🥔 Beilagen = Side dishes served with meals  
- 🥩 Fleisch = Meat products  
- 🐟 Fisch = Fish and seafood  

Now look at each word and think:
“What type of food is this?”

For example:
- Butter and Käse come from milk → Milchprodukte  
- Erdbeeren and Äpfel are fruits → Obst  
- Kartoffeln and Nudeln are usually eaten beside meat or vegetables → Beilagen  

Try to connect the meaning of the word with the category before checking the answers.
</details>



---
# 1 Studium und Mensa: Das gehört zusammen

 ## a) Lesen Sie nur die Überschrift. Was meinen Sie: Was essen Studierende gern?

<div style="background:#f6f8f1;border:2px solid #dfe7cf;border-radius:22px;padding:24px;line-height:1.8;">

# DAS ESSEN STUDIERENDE IN DEUTSCHLAND

Was essen Studierende am liebsten?  
Studentenfutter und Schokolade?  

Wir fragen Ben; er ist 21 und studiert in Hamburg Physik.  
Ben isst am liebsten Schnipo.  

Das ist ein Schnitzel mit Pommes (frites).  

Anne, 22, und Mia, 23, studieren Medizin.  
Sie lieben Tiere und wollen kein Fleisch essen.  

Und Anne hat eine Laktoseintoleranz und kann keine Milchprodukte essen.  

Sie isst vegan, am liebsten Reis mit Gemüse wie Brokkoli, Tomaten und Karotten.  

Wie Ben, Mia und Anne essen in Hamburg täglich etwa 23000 Gäste in 13 Mensen und 22 Cafés.  

Studierende können dort gut und günstig essen.  

Ein Mensa-Gericht gibt es schon für 2,50 €.

---

Hier sind die Top 5 aus Hamburg:

🥇 Platz 1: Currywurst mit Pommes frites.  
🥈 Platz 2: Hähnchen mit Paprikareis.  
🥉 Platz 3: Jägerschnitzel mit Pommes frites.  
4️⃣ Platz 4: Spaghetti mit Hackfleischsoße.  
5️⃣ Platz 5: Gemüse-Reis-Pfanne.

---

Du willst lieber zu Hause essen?  
Hast du keine Küche und kannst abends nicht kochen?  

Das ist kein Problem:  
Du kannst das Mensa-Essen auch mitnehmen.

</div>

---

 ## b) Lesen Sie jetzt den Artikel. Vergleichen Sie Ihre Vermutungen mit den Informationen im Text.

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

💬

Wir glauben, Studierende essen am liebsten Döner Kebab.  

Platz 1 in Hamburg ist Currywurst mit Pommes frites.

</div>

---

 ## c) Lesen Sie den Artikel in 1a noch einmal. Was ist richtig, was ist falsch? Kreuzen Sie an.

<div style="background:#f8fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;line-height:2;">

1. Mia will kein Fleisch essen, sie ist Vegetarierin.  

[[x]] richtig  
[[ ]] falsch

---

2. Anne isst gern Milchprodukte.  

[[ ]] Richtig  
[[x]] Falsch

---

3. Anne, Ben und Mia wollen lieber zu Hause essen.  

[[ ]] Richtig  
[[x]] Falsch

---

4. Die Studierenden können das Mensa-Essen auch zu Hause essen.  

[[x]] Richtig  
[[ ]] Falsch

</div> 

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you first read the title and predict what students in Germany like to eat.  
Then you compare your ideas with the information in the article.

While reading, focus on:

- What Ben likes to eat  
- Why Anne does not eat milk products  
- Which foods are most popular in Hamburg  
- Why students often eat in the Mensa  

Important vocabulary:
- <b>Schnipo</b> = Schnitzel mit Pommes  
- <b>vegan</b> = No animal products  
- <b>Laktoseintoleranz</b> = Cannot eat milk products  
- <b>Mensa</b> = University cafeteria  

For part c:
- “richtig” = The statement matches the text  
- “falsch” = The statement does not match the text  

Read each sentence carefully and look for the exact information in the article before choosing the answer.

</details>

---

# 2 [GRAMMATIK KOMPAKT] Modalverb können und wollen – Formen und Bedeutung

 ## a) Markieren Sie in 1a und 1c die Formen von **können** und **wollen** und ergänzen Sie die Tabelle.

<div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;">

<div style="background:#eaf4f4;border-radius:16px;padding:16px;border:1px solid #c8dddd;">

<h3 style="margin-top:0;">können</h3>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:0;border:1px solid #ffffff;">

<div style="padding:10px;background:#d8eaea;">ich</div>
<div style="padding:10px;background:#d8eaea;">[[kann]]</div>

<div style="padding:10px;background:#eef7f7;">du</div>
<div style="padding:10px;background:#eef7f7;">[[kannst]]</div>

<div style="padding:10px;background:#d8eaea;">er / sie / es</div>
<div style="padding:10px;background:#d8eaea;">[[kann]]</div>

<div style="padding:10px;background:#eef7f7;">wir</div>
<div style="padding:10px;background:#eef7f7;">[[können]]</div>

<div style="padding:10px;background:#d8eaea;">ihr</div>
<div style="padding:10px;background:#d8eaea;">[[könnt]]</div>

<div style="padding:10px;background:#eef7f7;">sie / Sie</div>
<div style="padding:10px;background:#eef7f7;">[[können]]</div>

</div>
</div>

<div style="background:#eaf4f4;border-radius:16px;padding:16px;border:1px solid #c8dddd;">

<h3 style="margin-top:0;">wollen</h3>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:0;border:1px solid #ffffff;">

<div style="padding:10px;background:#d8eaea;">ich</div>
<div style="padding:10px;background:#d8eaea;">[[will]]</div>

<div style="padding:10px;background:#eef7f7;">du</div>
<div style="padding:10px;background:#eef7f7;">[[willst]]</div>

<div style="padding:10px;background:#d8eaea;">er / sie / es</div>
<div style="padding:10px;background:#d8eaea;">[[will]]</div>

<div style="padding:10px;background:#eef7f7;">wir</div>
<div style="padding:10px;background:#eef7f7;">[[wollen]]</div>

<div style="padding:10px;background:#d8eaea;">ihr</div>
<div style="padding:10px;background:#d8eaea;">[[wollt]]</div>

<div style="padding:10px;background:#eef7f7;">sie / Sie</div>
<div style="padding:10px;background:#eef7f7;">[[wollen]]</div>

</div>
</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you learn the modal verbs <b>können</b> (can / to be able to) and <b>wollen</b> (to want).

First, look at the subject pronoun:
- ich
- du
- er / sie / es
- wir
- ihr
- sie / Sie

Then choose the correct verb form for that subject.

Important patterns:

- <b>ich</b> and <b>er/sie/es</b> often have the same form  
  → ich kann / er kann  
  → ich will / er will

- <b>du</b> usually ends with <b>-st</b>  
  → du kannst  
  → du willst

- <b>wir</b> and <b>sie/Sie</b> use the infinitive form  
  → wir können  
  → sie wollen

- <b>ihr</b> usually ends with <b>-t</b>  
  → ihr könnt  
  → ihr wollt

Also notice:
- In <b>können</b>, the vowel changes from <b>ö → a</b> in singular forms:
  → kann, kannst

- In <b>wollen</b>, the singular forms use:
  → will, willst

Read each row carefully and match the verb form with the correct subject pronoun.

</details>

 ## b) Ergänzen Sie die Regeln.

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

1. können: Singular: 1. und [[3.]] Person keine Endung;  
1., 2., 3. Pers.: Vokalwechsel: [[ö]] → a.

---

2. wollen: Singular: 1. und [[3.]] Person keine Endung;  
1., 2., 3. Pers.: Vokalwechsel: [[o]] → i.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you analyze the grammar pattern of the modal verbs <b>können</b> and <b>wollen</b>.

Focus on two things:

### 1️⃣ Verb endings
Look at the singular forms carefully:

- ich kann / ich will  
- er kann / er will  

You can see:
- The <b>1st person singular</b> (ich)
- And the <b>3rd person singular</b> (er/sie/es)

have <b>no ending</b>.

That is why the missing answer is:
→ <b>3.</b>

---

### 2️⃣ Vowel change
Now compare the infinitive with the singular forms:

#### können
- können → kann
- The vowel changes:
→ <b>ö → a</b>

#### wollen
- wollen → will
- The vowel changes:
→ <b>o → i</b>

So this exercise helps you discover:
- Modal verbs often change vowels in singular forms
- And some singular forms have no personal ending.

</details>

 ## c) können hat hier zwei Bedeutungen. Welche Bedeutung passt? Kreuzen Sie an.

<div style="background:#f8fbff;border:1px solid #d9e7ff;border-radius:20px;padding:22px;line-height:2.1;">

### 1. Er kann gut kochen.

[[x]] Man ist fähig / kompetent  
[[ ]] Es ist (nicht) möglich



---

### 2. In der Mensa kann man auch vegan essen.

[[ ]] Man ist fähig / kompetent  
[[x]] Es ist (nicht) möglich

---

### 3. Das Essen kann man auch mitnehmen.

[[ ]] Man ist fähig / kompetent  
[[x]] Es ist (nicht) möglich

---

### 4. Sie kann Polnisch und Ungarisch sprechen.

[[x]] Man ist fähig / kompetent  
[[ ]] Es ist (nicht) möglich

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, the modal verb <b>können</b> has two different meanings.

You must decide:

### 1️⃣ Fähigkeit / Kompetenz
This means:
→ someone has a skill or ability  
→ “to be able to do something”

Examples:
- Er kann gut kochen.  
  = He is good at cooking.

- Sie kann Polnisch sprechen.  
  = She has the ability to speak Polish.

Look for:
- Languages
- Talents
- Skills
- Abilities

---

### 2️⃣ Möglichkeit
This means:
→ something is possible or allowed

Examples:
- In der Mensa kann man vegan essen.  
  = It is possible to eat vegan food there.

- Das Essen kann man mitnehmen.  
  = Taking the food away is possible.

Look for:
- Places
- Rules
- Options
- Possibilities

So before answering, ask yourself:

👉 Is the sentence about a person's skill?  
or  
👉 Is the sentence about what is possible?

</details>

---

 ## d) Ergänzen Sie das Modalverb: wollen oder können?

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

1. Mia liebt Tiere und [[will]] kein Fleisch essen.

2. Das ist toll: Du [[kannst]] in der Mensa gut und günstig essen.

3. Ich habe so viel Stress: Heute [[will]] ich lieber zu Hause essen.

4. Es gibt einen Service: Studierende [[können]] das Mensa-Essen auch mitnehmen.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must decide whether the sentence needs:
- <b>wollen</b> = to want / desire  
or  
- <b>können</b> = can / be able to / it is possible
To solve the task, read the meaning of each sentence carefully.

 ### Use <b>wollen</b> when:
 
- Someone has a wish
- Someone prefers something
- Someone decides to do something

Examples:

- Mia loves animals and does not want to eat meat.
- I want to stay at home today.

Look for:
👉 feelings, wishes, preferences, decisions

---

### Use <b>können</b> when:
- Something is possible
- A service or opportunity exists
- Someone is able to do something

Examples:
- You can eat cheaply in the Mensa.
- Students can take the food home.

Look for:
👉 possibility, opportunity, available service, ability

Before filling the blank, ask yourself:

👉 Is this sentence about a wish? → <b>wollen</b>  
👉 Or about a possibility/service? → <b>können</b>

</details>

---

# 3 [GRAMMATIK KOMPAKT]

 ## Modalverb können und wollen – Wortstellung im Satz

 ## a) Markieren Sie die Verben in den Sätzen mit können / wollen in 1a und ergänzen Sie die Tabelle.

<div style="background:#f6fbff;border:1px solid #dbe9f5;border-radius:20px;padding:20px;overflow-x:auto;">

| Position 1 | Position 2 |  | Satzende |
|---|---|---|---|
| Anne und Mia | [[wollen]] | kein Fleisch | essen |
| Du | [[kannst]] | das Mensa-Essen auch | mitnehmen |

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you learn the sentence structure with modal verbs like:

- <b>können</b>
- <b>wollen</b>

Look carefully at the two verbs in each sentence.

Example:
- Anne und Mia <b>wollen</b> kein Fleisch <b>essen</b>.

There are always:
1️⃣ a conjugated modal verb  
2️⃣ a second verb in the infinitive

---

### Important grammar rule:

In German modal verb sentences:

- The modal verb goes to <b>Position 2</b>
- The second verb goes to the <b>end of the sentence</b>

So:

| Part | Example |
|---|---|
| Position 2 | wollen / kannst |
| Sentence end | essen / mitnehmen |

---

To solve the table:

1️⃣ Find the modal verb first  
→ wollen / kannst

2️⃣ Then find the second action verb  
→ essen / mitnehmen

3️⃣ Put the second verb into the column “Satzende”.

Notice:
- <b>Mitnehmen</b> stays together at the end because it is the infinitive form.
- The modal verb changes according to the subject:
  → Du kannst  
  → Anne und Mia wollen

</details>

---

 ## b) Ergänzen Sie die Regel.

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

Wortstellung: Das Modalverb ist in Aussagesätzen und W-Fragen auf Position [[2]].

Der Infinitiv steht am [[Satzende]].

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

This exercise explains the word order in German sentences with modal verbs.

Look again at these examples:

- Anne und Mia <b>wollen</b> kein Fleisch essen.
- Du <b>kannst</b> das Mensa-Essen mitnehmen.

Notice two important things:

---

### 1️⃣ Position of the modal verb

In German:
- The conjugated modal verb comes in <b>Position 2</b>
- This happens in normal statements and W-questions

Examples:
- Ich <b>kann</b> gut kochen.
- Was <b>willst</b> du essen?

So the first missing answer is:
→ <b>2</b>

---

### 2️⃣ Position of the infinitive

The second verb stays in the infinitive form and moves to the <b>end of the sentence</b>.

Examples:
- Wir wollen Pizza <b>essen</b>.
- Du kannst das Essen <b>mitnehmen</b>.

So the second missing answer is:
→ <b>Satzende</b>

To solve this type of grammar question:
1️⃣ Find the conjugated modal verb  
2️⃣ Check its position in the sentence  
3️⃣ Find the infinitive verb at the end

</details>

---

 ## c) Was wollen Sie machen? Was können Sie machen? Schreiben Sie drei Sätze.

<div style="background:#f9fbff;border:1px solid #d8e6ff;border-radius:18px;padding:18px;line-height:2;">

1. [[Ich will Deutsch lernen.]]

2. [[Ich kann gut Gitarre spielen.]]

3. [[Ich will Kybernetik studieren.]]

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you write your own sentences using the modal verbs:

- <b>wollen</b> = what you want to do  
- <b>können</b> = what you are able to do

You should create simple personal sentences about:
- Studying
- Hobbies
- Languages
- Sports
- Music
- Daily activities

---

### Important sentence structure

With modal verbs:

- The modal verb goes to <b>Position 2</b>
- The second verb stays in the infinitive form at the <b>end</b>

Examples:
- Ich will Deutsch <b>lernen</b>.
- Ich kann gut Gitarre <b>spielen</b>.

---

To solve the task:

1️⃣ Start with the subject:
→ Ich

2️⃣ Choose a modal verb:
→ will / kann

3️⃣ Add an activity or ability:
→ Deutsch lernen  
→ Gitarre spielen  
→ Kybernetik studieren

4️⃣ Put the second verb at the end of the sentence.

You can also use your own ideas and hobbies.

</details>


---

 ## d) Sagen Sie die drei Sätze aus 3c. Die anderen raten: Welcher Satz ist nicht richtig?

<div style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:18px;padding:18px;line-height:2;">

💬 Nicht richtig ist:  
[[Ich will Kybernetik studieren.]]

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this speaking activity, you say three sentences about yourself.

- Two sentences should be true.
- One sentence should be false or invented.

The other students listen carefully and guess:
👉 Which sentence is not correct?

To solve the task:
1️⃣ Read all three sentences aloud.  
2️⃣ Think about which sentence sounds unusual or different.  
3️⃣ Use logic and personal information to guess the false sentence.

Example:
- Someone studies Electrical Engineering but says:
  “Ich will Kybernetik studieren.”
  → This sentence could be the incorrect one.

This activity helps practice:
- Modal verbs (<b>wollen</b>, <b>können</b>)
- Speaking
- Listening
- Guessing information about classmates

</details>

---

# 4 Ist das möglich?

 ## a) Lesen Sie die Beiträge im Erstsemesterforum zum Thema: Essen im Seminar. Wer findet, das ist möglich? Markieren Sie die Argumente pro und contra in zwei Farben.

<div style="background:#f6f8f1;border:2px solid #dfe7cf;border-radius:22px;padding:22px;line-height:1.9;">

### Fabia (19, Philosophie)

Kann ich im Seminar einen Snack essen, ist das okay?

---

### Ben (21, Physik)

Ich finde, im Seminar kannst du keine Eier oder Knoblauch essen!  
Das geht nicht, das riecht 😢 und stört.  
Das ist total unhöflich.

---

### Carla (23, Jura)

Warum nicht? Ich finde das okay.  
Essen ist sozial.  
Der Dozent hat manchmal auch einen Snack dabei.  
Das ist nicht unhöflich.  
Mit Hunger kann man auch nicht lernen.

</div>

---

 ## b) Was denken Sie über das Thema? Schreiben Sie einen Forumsbeitrag.

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

💬

[[Ich finde, man kann im Seminar einen kleinen Snack essen.]]

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In these exercises, you read different opinions about eating during a seminar and then write your own opinion.

### Part a)
You must understand:
- Who thinks eating in class is okay
- Who thinks it is not okay
- Why they think that

Look for:
- Positive arguments (<b>pro</b>)
- Negative arguments (<b>contra</b>)

Example:
- Ben says eggs and garlic smell bad and disturb others  
  → this is a <b>contra</b> argument

- Carla says hungry students cannot learn well  
  → this is a <b>pro</b> argument

Try to identify:
- Words about politeness
- Smell
- Concentration
- Learning
- Social behavior

---

### Part b)
Now write your own forum opinion.

Use expressions like:
- <b>Ich finde …</b>
- <b>Man kann …</b>
- <b>Das ist okay / nicht okay.</b>

You can agree or disagree with the forum comments.

Remember:
- Use simple present tense
- Modal verbs like <b>können</b> are helpful
- Explain your opinion with a short reason

</details>

# 2 [GRAMMATIK KOMPAKT] Satzbau

 ## a) Was hören Sie? Kreuzen Sie an.
?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_023.mp3?raw=true)

1.

[[ ]] a. Ich esse gern Fisch.
[[x]] b. Fisch esse ich gern.

---

2.

[[x]] a. Die Mensa ist am Samstag geschlossen.
[[ ]] b. Am Samstag ist die Mensa geschlossen.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening exercise, you practice German sentence structure and word order.

Both sentences in each pair are grammatically possible in German, but you must choose the sentence you actually hear in the audio.

Listen carefully to:
- Which word comes first
- The position of the verb
- The sentence stress and emphasis

---

### Important grammar idea:

German sentences can begin with different elements.

Example:

- Ich esse gern Fisch.  
  → normal word order  
  → focus on “Ich”

- Fisch esse ich gern.  
  → object comes first  
  → stronger focus on “Fisch”

The verb still stays in <b>Position 2</b>.

---

Second example:

- Die Mensa ist am Samstag geschlossen.
- Am Samstag ist die Mensa geschlossen.

Both are correct German sentences, but:
- One focuses more on the place (“Die Mensa”)
- The other focuses more on the time (“Am Samstag”)

To solve the task:
1️⃣ Listen to the first word carefully  
2️⃣ Follow the word order in the audio  
3️⃣ Choose the sentence that exactly matches what you hear

</details>


---

 ## b) Ergänzen Sie die Regel.

Das Subjekt steht auf Position [[1]] oder nach dem Verb.

Das Verb bleibt immer auf Position [[2]].

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

This exercise explains an important German sentence structure rule.

Look at these examples again:

- Ich esse gern Fisch.  
- Fisch esse ich gern.

Notice:
- The subject (<b>ich</b>) is not always at the beginning.
- But the verb (<b>esse</b>) always stays in <b>Position 2</b>.

---

### Rule 1: Position of the subject

The subject can:
- Stand in <b>Position 1</b>
or
- Come after the verb

Examples:
- <b>Ich</b> esse gern Fisch.
- Fisch esse <b>ich</b> gern.

So the first missing answer is:
→ <b>1</b>

---

### Rule 2: Position of the verb

In German main sentences:
- The conjugated verb always stays in <b>Position 2</b>

Even if another word comes first.

Examples:
- Am Samstag <b>ist</b> die Mensa geschlossen.
- Fisch <b>esse</b> ich gern.

So the second missing answer is:
→ <b>2</b>

To solve this grammar task:
1️⃣ Find the verb first  
2️⃣ Count its position  
3️⃣ Then look for the subject

</details>


---

 ## c) Arbeiten Sie zu zweit. Fragen und Antworten Sie wie im Beispiel.

💬 Wann gibt es Pizza?

➡️ Pizza gibt es am Donnerstag.

➡️ Am Donnerstag gibt es Pizza.

---

 ## d) Und Sie: Was wollen Sie gern essen? Was essen Sie nicht gern order was können Sie nicht essen? Sprechen Sie zu zweit order in Kleingruppen.

💬 Ich esse gern Gemüse-Reis-Pfanne. 🥗🍚

# 3 [GRAMMATIK KOMPAKT] Konnektoren denn (Kausal) und aber (adversativ )

 ## a) Hören Sie und ergänzen Sie.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_024.mp3?raw=true)

<div style="background:#f8fbff;border:1px solid #d8e6ff;border-radius:18px;padding:18px;line-height:2;">

1. Milchreis kann ich leider nicht essen, [[denn]] ich habe eine Laktoseintoleranz.

2. Ich esse vegan, [[aber]] die Kürbissuppe kann ich nehmen.

</div>

---

 ## b) Schreiben Sie die Sätze aus 3a in die Tabelle.

<div style="background:#f6fbff;border-radius:18px;padding:18px;border:1px solid #dbe9f5;overflow-x:auto;">

| Hauptsatz 1 | Position 0 | Position 1 | Position 2 |  |
|---|---|---|---|---|
| Milchreis kann ich leider nicht essen, | [[denn]] | ich | habe | eine Laktoseintoleranz. |
| Ich esse vegan, | [[aber]] | die Kürbissuppe | kann | ich nehmen. |

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you analyze German sentence structure with the connectors:

- <b>denn</b> = because  
- <b>aber</b> = but

You must divide the sentence into parts and place them into the correct table columns.

---

### Important grammar rule

After <b>denn</b> and <b>aber</b>:

- The sentence structure stays normal
- The verb still stays in <b>Position 2</b>

Example:
- Ich habe eine Laktoseintoleranz
- Die Kürbissuppe kann ich nehmen

---

### How to solve the table

1️⃣ Find the connector word:
→ denn / aber

2️⃣ Put it into:
→ Position 0

3️⃣ Find the subject:
→ ich / die Kürbissuppe

4️⃣ Find the conjugated verb:
→ habe / kann

5️⃣ Put the remaining information into the last column.

Notice:
- <b>kann</b> stays in Position 2
- the subject can come after the verb in some German sentences

This exercise helps you understand:
- Sentence connectors
- Position 0
- Verb position
- Flexible German word order

</details>


---

 ## c) Ergänzen Sie die Regel.

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

Mit denn (Grund, kausal) und aber (Gegensatz, adversativ) kann man zwei Sätze verbinden.

denn und aber stehen auf Position [[0]].

Das konjugierte Verb steht auf Position [[2]].

Zwischen den Sätzen steht immer ein Komma.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

This exercise explains how German connects two main clauses using:

- <b>denn</b> = because (reason / cause)
- <b>aber</b> = but (contrast / opposite idea)

---

### Step 1: Understand the meaning

#### denn
Use <b>denn</b> when you explain a reason.

Example:
- Ich esse keinen Milchreis, <b>denn</b> ich habe eine Laktoseintoleranz.

👉 The second sentence explains the reason.

---

#### aber
Use <b>aber</b> when two ideas are different or opposite.

Example:
- Ich esse vegan, <b>aber</b> die Kürbissuppe kann ich nehmen.

👉 The second sentence shows a contrast.

---

### Step 2: Understand the sentence structure

With <b>denn</b> and <b>aber</b>:

- They stand before the second sentence
- This position is called <b>Position 0</b>

So the first missing answer is:
→ <b>0</b>

---

### Step 3: Find the verb position

In German main clauses:
- the conjugated verb always stays in <b>Position 2</b>

Examples:
- ich <b>habe</b> …
- die Kürbissuppe <b>kann</b> …

So the second missing answer is:
→ <b>2</b>

---

### Step 4: Punctuation

When connecting two main clauses with:
- denn
- aber

you must always use:
→ a comma (,)

</details>


---

 ## d) Ergänzen Sie denn oder aber.

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

1. Ich esse vegan, [[denn]] ich liebe Tiere.

2. Ich esse kein Fleisch, [[aber]] ich esse Fisch.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you choose between:

- <b>denn</b> = because / giving a reason  
- <b>aber</b> = but / showing contrast

To solve the task, compare the two parts of the sentence carefully.

---

### Use <b>denn</b> when:
the second sentence explains the reason for the first sentence.

Example:
- Ich esse vegan, <b>denn</b> ich liebe Tiere.
  → Why vegan?
  → Because the person loves animals.

Look for:
👉 explanations  
👉 causes  
👉 reasons

---

### Use <b>aber</b> when:
the second sentence is different or opposite.

Example:
- Ich esse kein Fleisch, <b>aber</b> ich esse Fisch.
  → The second idea contrasts with the first one.

Look for:
👉 differences  
👉 opposites  
👉 contrast

Before choosing the word, ask yourself:

👉 Is the second sentence a reason? → <b>denn</b>  
👉 Or is it a contrast/opposite idea? → <b>aber</b>

</details>


---

 ## e) Schreiben Sie die Sätze. Denken Sie auch an das Komma.

<div style="background:#f8fbff;border:1px solid #dbe7f5;border-radius:18px;padding:22px;line-height:2.1;">

### 1.

die Gemüsepizza – vegetarisch – ist – aber – nicht vegan – ist – sie –

✍️ ~~__Die Gemüsepizza ist vegetarisch, aber sie ist nicht vegan.__~~

---

### 2.

Olga – kocht – zu Hause – denn – heute – die Mensa – geschlossen – ist –

✍️ [[Olga kocht heute zu Hause, denn die Mensa ist geschlossen.]]

---

### 3.

Ben – Schnipo – isst – am liebsten – aber – nimmt – heute – Pizza mit Salami – er –

✍️ [[Ben isst am liebsten Schnipo, aber heute nimmt er Pizza mit Salami.]]

---

### 4.

die Studierenden – gern in der Mensa – essen – denn – sie – gut und günstig – ist –

✍️ [[Die Studierenden essen gern in der Mensa, denn sie ist gut und günstig.]]

---

### 5.

Mia – in Hamburg – studiert – aber – kommt – sie – aus Süddeutschland –

✍️ [[Mia studiert in Hamburg, aber sie kommt aus Süddeutschland.]]

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must build correct German sentences from mixed words.

To solve the task:

### Step 1️⃣ Find the subject
Look for the person or thing doing the action.

Examples:
- die Gemüsepizza
- Olga
- Ben
- die Studierenden
- Mia

---

### Step 2️⃣ Find the conjugated verb
The conjugated verb must stay in <b>Position 2</b>.

Examples:
- ist
- kocht
- nimmt
- essen
- studiert

---

### Step 3️⃣ Look for the connector
You must connect two main clauses using:

- <b>denn</b> = reason
- <b>aber</b> = contrast

Examples:
- vegan, <b>aber</b> …
- zu Hause, <b>denn</b> …

Remember:
👉 Put a comma before <b>denn</b> and <b>aber</b>.

---

### Step 4️⃣ Build the second sentence
After:
- denn
- aber

the sentence structure stays normal:
- subject
- verb
- other information

Examples:
- denn die Mensa ist geschlossen
- aber sie kommt aus Süddeutschland

---

Important:
- German verbs stay in Position 2
- Use commas correctly
- Read the sentence logically before writing it

</details>

# 4 Was wollen wir heute kochen?

 ## a) Lesen Sie den Chat von Ben und Mia.Was kochen sie?

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_3/chapter3_4.png?raw=true)

 ## b) Arbeiten Sie zu zweit.

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

💬 Was wollen Sie zusammen kochen?

💬 Können Sie ein gemeinsames Gericht finden?

💬 Schreiben Sie einen Chat wie in 4a.

</div>

# 3C Im Café Campus

 ## a) Mia, Olga und Ben sind im Café Campus. Lesen Sie die Speisekarte. Kennen Sie die Gerichte? Was meinen Sie?

<div style="background:#fff7f3;border:1px solid #f1d2c4;border-radius:22px;padding:24px;">

# ☕ CAFÉ CAMPUS

<div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;">

<div style="background:#fffdfb;border-radius:18px;padding:18px;border:1px solid #efd6ca;">

## 🍽 HAMBURG HERZHAFT

__Hamburg-Mittagessen:__

* Rundstück warm — 5,50 €  
*  Fischbrötchen, Stück — 3,50 €  
*  Heringssalat — 6,90 €  
*  Labskaus — 9,90 €  
*  Birnen, Bohnen & Speck — 7,90 €  
*  Toast Hawaii — 4,50 €

</div>

<div style="background:#fffdfb;border-radius:18px;padding:18px;border:1px solid #efd6ca;">

## 🍰 HAMBURG SÜSS

__Hamburg-Frühstück:__

*  2 Franzbrötchen, Tee und ein Glas O-Saft — 5,90 €  
*  Butterkuchen, Stück — 2,50 €  
*  Käsekuchen, Stück — 2,90 €  
*  Kirschtorte, Stück — 3,20 €  
*  Franzbrötchen, Stück — 2,20 €  
*  Rote Grütze mit Vanillesoße — 3,50 €

</div>

</div>

---

<div style="background:#fff;border-radius:16px;padding:18px;border:1px solid #efd6ca;margin-top:20px;">

## 🥤 GETRÄNKE

* Tee mit Milch (Glas), Kaffee (Tasse), heiße Schokolade (Tasse), Espresso — 2,50 €

<br>

* Kaffee (Kännchen), Tee (Kännchen), Cola (Flasche), Wasser (Flasche) — 4,50 €

</div>

</div>

---

<div style="background:#f8fbff;border:1px solid #d8e6ff;border-radius:18px;padding:18px;line-height:2;">

💬 Was ist ein Rundstück?

💬 Ich weiß es nicht. Das ist vielleicht eine Pizza.

</div>

---

 ## b) Hören Sie das Gespräch. Welche Definition passt? Ordnen Sie zu.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_025.mp3?raw=true)

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;overflow-x:auto;">

a. ist ein Brötchen. Das Brötchen ist süß, mit Zimt und Zucker.

b. ist der Hamburger aus Hamburg.

c. ist eine Süßspeise aus Erdbeeren und Kirschen mit Vanillesoße.

d. ist ein Gericht aus Fleisch mit Kartoffeln, rote Beete und Spiegelei.

---

| | |
|---|---|
| 1. Labskaus | [[ d ]] |
| 2. Rote Grütze | [[ c ]] |
| 3. Rundstück warm | [[ b ]] |
| 4. Franzbrötchen | [[ a ]] |

---



</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening exercise, you must match each traditional German food with the correct definition.

To solve the task:

### Step 1️⃣ Listen for keywords
Pay attention to:
- ingredients
- sweet or salty food
- meat or dessert
- bread or meal

---

### Step 2️⃣ Understand the definitions

#### a.
- sweet bread
- cinnamon and sugar
👉 This describes a sweet bakery product.

---

#### b.
- “Hamburger from Hamburg”
👉 This is not the modern burger from fast food.
Think about a traditional sandwich or bread dish from Hamburg.

---

#### c.
- dessert
- strawberries and cherries
- vanilla sauce
👉 This is a sweet fruit dessert.

---

#### d.
- meat
- potatoes
- beetroot
- fried egg
👉 This is a heavy traditional warm meal.

---

### Step 3️⃣ Match the food names

- <b>Labskaus</b> → traditional warm meat dish  
- <b>Rote Grütze</b> → sweet fruit dessert  
- <b>Rundstück warm</b> → warm Hamburg sandwich  
- <b>Franzbrötchen</b> → sweet cinnamon pastry

Listen carefully for:
- food ingredients
- whether the dish is sweet or savory
- words like Zucker, Fleisch, Erdbeeren, Brötchen

</details>

---

# 2 Mia, Olga und Ben möchten bestellen

 ## a) Was sagen die Gäste (G), im Café Campus, was sagt die Bedienung (B)? Markieren Sie in 2 unterschiedliche Farben: gelb (B), blau (G).

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

*   🥛[[B]] Sehr gern. Was möchtet ihr trinken?
*   🍝[[G]] Wollen wir noch Kuchen essen? Der schmeckt hier toll!
*   ☕️[[G]] Ich nehme einen Espresso. Und du Mia?
*   🍡[[B]] Okay. Franzbrötchen, zwei Stück, und die Rote Grütze. Vielen Dank!
*   🥤[[G]] Eine Cola, bitte.
*   🫖[[G]] Und ich nehme einen Tee.
*   🫘[[G]] Ich nehme die Rote Grütze.
*   🍪[[B]] Wir haben heute Käsekuchen, Kirschtorte, Butterkuchen und natürlich Franzbrötchen.
*   🍽️[[G]] Hallo. Wir möchten gern bestellen.
*   🍩[[G]] Dann nehme ich ein Franzbrötchen. Ich mag Zimt, sehr lecker!
*   🌰[[G]] Ich auch. Ich nehme auch ein Franzbrötchen, und du Olga?
*   ☕️[[B]] Gut. Einen Espresso, eine Flasche Cola, ein Glas Tee. Möchtet ihr auch etwas essen?

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must identify:
- what the guests (<b>G</b>) say
- and what the café worker / waitress (<b>B</b>) says.

To solve the task, think about:
👉 Who usually asks questions in a café?  
👉 Who orders food and drinks?  
👉 Who writes down the order?

---

### The guests (G) usually:

- Order food or drinks
- Choose something from the menu
- Talk to friends
- Say what they want

Typical expressions:
- Ich nehme …
- Und du?
- Wollen wir …?
- Eine Cola, bitte.



### The waitress / café worker (B) usually:

- Welcomes customers
- Asks what they want
- Lists food options
- Repeats the order

Typical expressions:
- Was möchtet ihr trinken?
- Möchtet ihr auch etwas essen?
- Wir haben heute …
- Vielen Dank!

---

### Strategy for solving the task:

1️⃣ Read each sentence carefully  
2️⃣ Ask:
- Is this sentence ordering something? → probably <b>G</b>
- Is this sentence serving/helping customers? → probably <b>B</b>

3️⃣ Use the café situation and conversation flow to decide correctly.

</details>

---



## 🎧 Sortieren Sie die Sätze und schreiben Sie das Gespräch. Hören Sie dann noch einmal zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_026.mp3?raw=true)


<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:22px;padding:22px;line-height:2;">

## 🧾 Café Campus

*   🥛[[2]] Sehr gern. Was möchtet ihr trinken?
*   🍝[[7]] Wollen wir noch Kuchen essen? Der schmeckt hier toll!
*   ☕️[[3]] Ich nehme einen Espresso. Und du Mia?
*   🍡[[12]] Okay. Franzbrötchen, zwei Stück, und die Rote Grütze. Vielen Dank!
*   🥤[[4]] Eine Cola, bitte.
*   🫖[[5]] Und ich nehme einen Tee.
*   🫘[[11]] Ich nehme die Rote Grütze.
*   🍪[[8]] Wir haben heute Käsekuchen, Kirschtorte, Butterkuchen und natürlich Franzbrötchen.
*   🍽️[[1]] Hallo. Wir möchten gern bestellen.
*   🍩[[9]] Dann nehme ich ein Franzbrötchen. Ich mag Zimt, sehr lecker!
*   🌰[[10]] Ich auch. Ich nehme auch ein Franzbrötchen, und du Olga?
*   ☕️[[6]] Gut. Einen Espresso, eine Flasche Cola, ein Glas Tee. Möchtet ihr auch etwas essen?

</div>

---



 ## c) Die Rechnung. Was ist richtig? Hören Sie das Gespräch und kreuzen Sie an.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_027.mp3?raw=true)

<div style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:18px;padding:18px;line-height:2;">

### 1.

Sie bezahlen

 [[x]] zusammen.
 [[ ]] getrennt.

---

### 2.

Sie bezahlen

 [[ ]] 17,40 Euro.
 [[x]] 19,00 Euro.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening exercise, you focus on paying in a café or restaurant.

You must listen for:
- How the people want to pay
- And the final amount of money

---

### Important vocabulary

#### bezahlen
= To pay

#### zusammen bezahlen
= To pay together  
(one bill for everyone)

#### getrennt bezahlen
= To pay separately  
(each person pays individually)

---

### Strategy for Question 1

Listen carefully for words like:
- Zusammen
- Getrennt
- Alles zusammen
- Jeder einzeln

These words help you understand how they pay.

---

### Strategy for Question 2

Listen carefully to:
- Numbers
- Prices
- Euro and Cent

German numbers in listening exercises can be difficult.

Example:
- Siebzehn Euro vierzig = 17,40 €
- Neunzehn Euro = 19,00 €

Pay attention:
- Sometimes students confuse 17 and 19
- Listen to the ending carefully:
  → siebzehn  
  → neunzehn

---

To solve the task:
1️⃣ Listen once for the situation  
2️⃣ Listen again for keywords and numbers  
3️⃣ Focus especially on the final payment sentence

</details>


# 3 [AUSSPRACHE] Vokale a, e, i(e), o, u, ä, ö, ü

 ## a) Hören Sie die Wörter und sprechen Sie nach.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_028.mp3?raw=true)

<div style="background:#f8fbff;border:1px solid #d9e7ff;border-radius:20px;padding:20px;line-height:2;">



### 🔊 <span style="color:#e74c3c;font-weight:bold;">a</span>:
bez<span style="color:#e74c3c;font-weight:bold;">a</span>hlen – zus<span style="color:#e74c3c;font-weight:bold;">a</span>mmen

### 🔊 <span style="color:#3498db;font-weight:bold;">e</span>:
s<span style="color:#3498db;font-weight:bold;">e</span>hr – l<span style="color:#3498db;font-weight:bold;">e</span>cker

### 🔊 <span style="color:#2ecc71;font-weight:bold;">i</span>:
v<span style="color:#2ecc71;font-weight:bold;">ie</span>l – tr<span style="color:#2ecc71;font-weight:bold;">i</span>nken

### 🔊 <span style="color:#f39c12;font-weight:bold;">o</span>:
die C<span style="color:#f39c12;font-weight:bold;">o</span>la – t<span style="color:#f39c12;font-weight:bold;">o</span>ll

### 🔊 <span style="color:#9b59b6;font-weight:bold;">u</span>:
der K<span style="color:#9b59b6;font-weight:bold;">u</span>chen – der Z<span style="color:#9b59b6;font-weight:bold;">u</span>cker

### 🔊 <span style="color:#16a085;font-weight:bold;">ä</span>:
der K<span style="color:#16a085;font-weight:bold;">ä</span>se – die G<span style="color:#16a085;font-weight:bold;">ä</span>ste

### 🔊 <span style="color:#d35400;font-weight:bold;">ö</span>:
das Br<span style="color:#d35400;font-weight:bold;">ö</span>tchen – ich m<span style="color:#d35400;font-weight:bold;">ö</span>chte

### 🔊 <span style="color:#c0392b;font-weight:bold;">ü</span>:
s<span style="color:#c0392b;font-weight:bold;">ü</span>ß – das St<span style="color:#c0392b;font-weight:bold;">ü</span>ck

</div>

---


# 4 [GRAMMATIK KOMPAKT] Modalverben möcht- und mögen

 ## a) Markieren Sie in 2a die Formen von möcht- und mögen. Ergänzen Sie die Tabelle.

<div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;">

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;overflow-x:auto;">

## ✨ möcht-

|  |  |
|---|---|
| ich | möchte |
| du | möchtest |
| er / sie / es | möchte |
| wir | [[ möchten ]] |
| ihr | [[ möchtet ]] |
| sie / Sie | möchten |

</div>

<div style="background:#f7fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;overflow-x:auto;">

## 💬 mögen

|  |  |
|---|---|
| ich | mag |
| du | magst |
| er / sie / es | mag |
| wir | mögen |
| ihr | mögt |
| sie / Sie | mögen |

</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you compare the verbs:

- <b>möcht-</b> = would like  
- <b>mögen</b> = to like

Both verbs are used to talk about:
- wishes
- preferences
- likes

---

### Step 1️⃣ Understand the meaning

#### möcht-
Use this when ordering or expressing a polite wish.

Examples:
- Ich möchte einen Tee.
- Wir möchten bestellen.

👉 polite request / wish

---

#### mögen
Use this to say what you like.

Examples:
- Ich mag Pizza.
- Wir mögen Musik.

👉 personal preference

---

### Step 2️⃣ Look at the verb forms

Notice the patterns:

#### Singular
- ich → möchte / mag
- du → möchtest / magst
- er/sie/es → möchte / mag

👉 1st and 3rd person singular are the same again.

---

#### Plural
- wir → möchten / mögen
- ihr → möchtet / mögt
- sie/Sie → möchten / mögen

Look carefully at:
- Plural endings
- The difference between singular and plural forms

---

### Step 3️⃣ Fill the missing forms

To solve the missing blanks:
1️⃣ Find the subject pronoun  
2️⃣ Match the correct verb ending  
3️⃣ Compare singular and plural patterns

Especially remember:
- wir and sie/Sie often use similar forms
- ihr usually ends with <b>-t</b>

</details>

---

 ## b) Ergänzen Sie die korrekte Endung.

<div style="background:#f9fbff;border:1px solid #dbe9f5;border-radius:18px;padding:18px;line-height:2;">

1. Was möcht[[et]] ihr?

2. Was möcht[[en]] Sie?

3. Möcht[[est]] du Tee?

4. Ich möcht[[e]] eine Cola.

5. Wir möcht[[en]] Tee.

6. Was möcht[[e]] Ben?

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you complete the correct endings of the verb <b>möchten</b>.

To solve the task:

### Step 1️⃣ Identify the subject pronoun

Look carefully at:
- ihr
- Sie
- du
- Ich
- Wir
- Ben

The verb ending changes depending on the subject.

---

### Step 2️⃣ Remember the pattern of <b>möchten</b>

| Pronoun | Form |
|---|---|
| ich | möchte |
| du | möchtest |
| er / sie / es | möchte |
| wir | möchten |
| ihr | möchtet |
| sie / Sie | möchten |

---

### Step 3️⃣ Match the correct ending

Examples:

- <b>ihr</b> usually ends with → <b>-t</b>
  → möchtet

- <b>du</b> usually ends with → <b>-st</b>
  → möchtest

- <b>wir</b> and <b>Sie</b> usually end with → <b>-en</b>
  → möchten

- <b>ich</b> and <b>er/sie/es</b> usually end with → <b>-e</b>
  → möchte

---

### Helpful trick

Before writing the ending:
1️⃣ Find the subject  
2️⃣ Say the full verb form in your head  
3️⃣ Then write only the missing ending

</details>

---

 ## c) Wer mag was? Ordnen Sie zu.

<div style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:18px;padding:18px;line-height:2;">

1. Ben isst gern Hamburger. ➜ [[c]]

2. Mia und Anne essen vegetarisch. ➜ [[a]]

3. Olga isst gern Käse. ➜ [[b]]

---

a. Sie mögen kein Fleisch.

b. Sie mag Milchprodukte.

c. Er mag Fastfood.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you match people with the correct preference sentence.

Focus on:
- what each person likes or dislikes
- the pronouns
- singular and plural forms of <b>mögen</b>

---

### Step 1️⃣ Read the first sentence carefully

Example:
- Ben isst gern Hamburger.

Ask yourself:
👉 What category is a hamburger?
→ Fastfood

So:
- “Er mag Fastfood.” matches Ben.

---

### Step 2️⃣ Watch the pronouns

#### Ben
= one male person
→ use:
- er
- mag

#### Olga
= one female person
→ use:
- sie
- mag

#### Mia und Anne
= two people
→ use:
- sie
- mögen

---

### Step 3️⃣ Understand the food categories

- Hamburger → Fastfood
- vegetarisch → no meat
- Käse → milk product

This exercise helps you connect:
- Food vocabulary
- Personal preferences
- Mögen forms
- Pronouns

</details>

---

 ## d) Ergänzen Sie die Regel.

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

1. möcht-: 1. und [[3]]. Person sind gleich.

möcht- bezeichnet einen Wunsch wie wollen, aber höflicher:

Ich will einen Kaffee. = eher unhöflich  
Ich möchte einen Kaffee. = höflich

---

2. mögen:

Singular: 1. und [[3]]. Person keine Endung.

1., 2., 3. Pers.: Vokalwechsel: ö ➜ [[a]].

mögen bezeichnet eine Vorliebe / Präferenz.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you analyze the grammar patterns of <b>möcht-</b> and <b>mögen</b>.

You must look carefully at:
- verb endings
- vowel changes
- meaning differences

---

### Part 1️⃣ möcht-

Look at the singular forms:

- ich möchte
- er/sie/es möchte

You can see:
👉 the <b>1st person</b> and <b>3rd person</b> are the same.

So the missing answer is:
→ <b>3.</b>

---

### Meaning of <b>möchte</b>

- <b>wollen</b> = direct / sometimes less polite
- <b>möchte</b> = polite wish

Examples:
- Ich will einen Kaffee.
- Ich möchte einen Kaffee.

Both mean similar things, but:
👉 <b>möchte</b> sounds more polite in cafés, restaurants, or formal situations.

---

### Part 2️⃣ mögen

Look at the singular forms:

- ich mag
- du magst
- er/sie/es mag

Notice:
- 1st and 3rd person singular have no ending
- The vowel changes from:
  → <b>ö → a</b>

Example:
- mögen → mag

So the missing answers are:
→ <b>3.</b>
→ <b>a</b>

---

### Meaning of <b>mögen</b>

Use <b>mögen</b> for:
- Likes
- Preferences
- Favorite things

Examples:
- Ich mag Pizza.
- Sie mögen Musik.

👉 It expresses preference, not a polite request.

</details>

---

# 5 Wir bestellen

 ## a) Arbeiten Sie zu dritt.

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

👥 Sie sind mit einer Freundin / einem Freund im Café Kontor.

☕ Im Café Kontor sagt man Sie.

💬 Fragen Sie die Freundin / den Freund, was sie / er gern möchte.

📱 Lesen Sie dann die Sprachnachricht von Ihrem Freund, Vitus.

</div>

---

<div style="background:#f7fbff;border:1px solid #d9e7ff;border-radius:16px;padding:16px;line-height:1.8;">

📩

Sorry, ich bin zu spät.

Ich nehme einen Espresso und ein Franzbrötchen.

Danke!  
LG Vitus

</div>

---

 ## b) [MEDIATION] Bestellen Sie nun für Ihre Freundin / Ihren Freund, für Vitus und für Sie selbst. Wechseln Sie die Rollen.

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

💬 Hallo. Wir möchten gern bestellen.

💬 Sehr gern. Was möchten Sie …?



</div>


# Bestellen und bezahlen im Café

<div style="background:#f8fbff;border:1px solid #dbe7f5;border-radius:20px;padding:20px;overflow-x:auto;">

| Gäste | Bedienung |
|---|---|
| Wir möchten gern bestellen. | Ja, gern. |
| Ich nehme / Wir nehmen … | Was möchten Sie / möchtet ihr trinken? |
| … bitte. | Möchten Sie / Möchtet ihr auch etwas essen? |
|  | Wir haben heute … |
|  | Gut / Okay. Ein(en) … |
| Wir möchten gern bezahlen. | Zusammen oder getrennt? |
| Getrennt / Zusammen. | Das macht … |
|  | Vielen Dank. |

</div>

---

 ## Modalverben können und wollen

<div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;">

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;overflow-x:auto;">

## können

|  |  |
|---|---|
| ich | kann |
| du | kannst |
| er / sie / es | kann |
| wir | können |
| ihr | könnt |
| sie / Sie | können |

</div>

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;overflow-x:auto;">

## wollen

|  |  |
|---|---|
| ich | will |
| du | willst |
| er / sie / es | will |
| wir | wollen |
| ihr | wollt |
| sie / Sie | wollen |

</div>

</div>

---

 ## Modalverben – Wortstellung im Satz

<div style="background:#f7fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;overflow-x:auto;">

| Position 1 | Position 2 |  | Satzende |
|---|---|---|---|
| Was | wollen | Studierende am liebsten | essen? |
| Studierende | können | dort gut und günstig | essen. |
| Du | kannst | das Mensa-Essen auch | mitnehmen. |

</div>

---

 ## Konnektor denn und aber

<div style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:18px;padding:18px;overflow-x:auto;">

| Hauptsatz 1 | Position 0 | Position 1 | Position 2 |  |
|---|---|---|---|---|
| Anne kann keine Milchprodukte essen, | denn | sie | hat | eine Laktoseintoleranz. |
| Ich esse vegan, | aber | die Kürbissuppe | kann | ich nehmen. |

</div>

---

 ## Modalverben möcht-, mögen

<div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;">

<div style="background:#f8fbff;border:1px solid #dbe7f5;border-radius:18px;padding:18px;overflow-x:auto;">

## möcht-

|  |  |
|---|---|
| ich | möchte |
| du | möchtest |
| er / sie / es | möchte |
| wir | möchten |
| ihr | möchtet |
| sie / Sie | möchten |

</div>

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;overflow-x:auto;">

## mögen

|  |  |
|---|---|
| ich | mag |
| du | magst |
| er / sie / es | mag |
| wir | mögen |
| ihr | mögt |
| Sie / sie | mögen |

</div>

</div>

---

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;font-size:22px;line-height:2;">

💬 Wir möchten gern bestellen.

💬 Ich mag keinen Fisch.

</div>

# Lösungen / Answer Key – Kapitel 3

## 1 Gerichte und Lebensmittel

 ## Ordnen Sie zu

* **Milchprodukte:** Quark, Butter, Milch, Käse, Eis  
* **Obst / Früchte:** Erdbeeren, Kirschen, Äpfel  
* **Gemüse:** Pilze / Champignons, Tomaten, Salat, Karotten, Paprika  
* **Beilagen:** Kartoffeln, Nudeln, Pommes frites  
* **Fleisch:** Wurst, Schnitzel  
* **Fisch:** Hering, Lachs  

---

## 1 Studium und Mensa: Das gehört zusammen

 ## b)
Wir glauben, Studierende essen am liebsten Döner Kebab.  
Platz 1 in Hamburg ist Currywurst mit Pommes frites.

 ## c) Richtig oder falsch
1. richtig  
2. falsch  
3. falsch  
4. richtig  

---

## 2 Grammatik Kompakt – können und wollen

 ## a) Tabelle

**können:**  
* ich kann  
* du kannst  
* er/sie/es kann  
* wir können  
* ihr könnt  
* sie/Sie können  

**wollen:**  
* ich will  
* du willst  
* er/sie/es will  
* wir wollen  
* ihr wollt  
* sie/Sie wollen  

 ## b) Regeln
1. 3. / ö  
2. 3. / o → i  

 ## c) Bedeutung von können
1. Man ist fähig / kompetent  
2. Es ist möglich  
3. Es ist möglich  
4. Man ist fähig / kompetent  

 ## d) wollen oder können
1. will  
2. kannst  
3. will  
4. können  

---

## 3 Grammatik Kompakt – Wortstellung

 ## a)
1. Anne und Mia wollen kein Fleisch essen.  
2. Du kannst das Mensa-Essen auch mitnehmen.

 ## b)
* Modalverb: Position 2  
* Infinitiv: Satzende  

 ## c)
1. Ich will Deutsch lernen.  
2. Ich kann gut Gitarre spielen.  
3. Ich will Kybernetik studieren.  

 ## d)
Nicht richtig ist: Ich will Kybernetik studieren.

---

## 4 Ist das möglich?

 ## a)
**Contra:** Ben findet Essen im Seminar nicht möglich.  
Argumente: Eier oder Knoblauch riechen, stören und sind unhöflich.

**Pro:** Carla findet Essen im Seminar möglich.  
Argumente: Essen ist sozial; der Dozent hat manchmal auch einen Snack; mit Hunger kann man nicht lernen.

 ## b)
Ich finde, man kann im Seminar einen kleinen Snack essen.

---

## 2 Grammatik Kompakt – Satzbau

 ## a)
1. b. Fisch esse ich gern.  
2. a. Die Mensa ist am Samstag geschlossen.

 ## b)
* Subjekt: Position 1 oder nach dem Verb  
* Verb: Position 2  

---

## 3 Grammatik Kompakt – denn und aber

 ## a)
1. denn  
2. aber  

 ## b)
1. denn / ich / habe / eine Laktoseintoleranz  
2. aber / die Kürbissuppe / kann / ich nehmen  

 ## c)
Position 0  
Position 2  
Komma zwischen den Sätzen  

 ## d)
1. denn  
2. aber  

 ## e)
1. Die Gemüsepizza ist vegetarisch, aber sie ist nicht vegan.  
2. Olga kocht heute zu Hause, denn die Mensa ist geschlossen.  
3. Ben isst am liebsten Schnipo, aber heute nimmt er Pizza mit Salami.  
4. Die Studierenden essen gern in der Mensa, denn sie ist gut und günstig.  
5. Mia studiert in Hamburg, aber sie kommt aus Süddeutschland.  

---

## 3C Im Café Campus

 ## b) Definitionen
1. Labskaus → d  
2. Rote Grütze → c  
3. Rundstück warm → b  
4. Franzbrötchen → a  

---

 ## 2 Mia, Olga und Ben möchten bestellen

 ## a) Gäste oder Bedienung
1. B  
2. G  
3. G  
4. B  
5. G  
6. G  
7. G  
8. B  
9. G  
10. G  
11. G  
12. B  

 ## Sortieren Sie das Gespräch
1. Hallo. Wir möchten gern bestellen.  
2. Sehr gern. Was möchtet ihr trinken?  
3. Ich nehme einen Espresso. Und du Mia?  
4. Eine Cola, bitte.  
5. Und ich nehme einen Tee.  
6. Gut. Einen Espresso, eine Flasche Cola, ein Glas Tee. Möchtet ihr auch etwas essen?  
7. Wollen wir noch Kuchen essen? Der schmeckt hier toll!  
8. Wir haben heute Käsekuchen, Kirschtorte, Butterkuchen und natürlich Franzbrötchen.  
9. Dann nehme ich ein Franzbrötchen. Ich mag Zimt, sehr lecker!  
10. Ich auch. Ich nehme auch ein Franzbrötchen, und du Olga?  
11. Ich nehme die Rote Grütze.  
12. Okay. Franzbrötchen, zwei Stück, und die Rote Grütze. Vielen Dank!  

 ## c) Die Rechnung
1. zusammen  
2. 19,00 Euro  

---

## 4 Grammatik Kompakt – möcht- und mögen

 ## a) 
* wir möchten  
* ihr möchtet  

 ## b)
1. et  
2. en  
3. est  
4. e  
5. en  
6. e  

 ## c)
1. c  
2. a  
3. b  

 ## d)
 
1. 3  
2. 3 
3. a  