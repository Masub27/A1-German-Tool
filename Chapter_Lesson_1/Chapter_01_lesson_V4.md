<!--

author:   Kanwal & Makhdoom
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

# Kapitel 1

 

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bg1" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#f5f9ef"/>
      <stop offset="100%" stop-color="#ffffff"/>
    </linearGradient>

    <linearGradient id="panel1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="100%" stop-color="#f9fcf4"/>
    </linearGradient>

    <linearGradient id="accent1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#8fae2e"/>
      <stop offset="100%" stop-color="#b7cc4a"/>
    </linearGradient>

    <style>
      .title { font: 700 64px Georgia; fill:#6f7f1f; }
      .subtitle { font: 500 22px Arial; fill:#5b6450; }
      .chip { font: 700 24px Georgia; fill:white; }
      .head { font:700 28px Georgia; fill:#7a8626; }
      .text { font:500 20px Arial; fill:#4e5648; }
    </style>
  </defs>

  <rect width="1600" height="900" fill="url(#bg1)"/>

  <!-- Header -->
  <rect x="0" y="0" width="1600" height="110" fill="#eef3e6"/>

  <!-- Main Card -->
  <rect x="100" y="100" width="1400" height="700" rx="30"
        fill="url(#panel1)" stroke="#d8e3c2"/>

  <!-- Label -->
  <rect x="140" y="130" width="210" height="55" rx="16" fill="url(#accent1)"/>
  <text x="245" y="165" text-anchor="middle" class="chip">KAPITEL 1</text>

  <!-- Title -->
  <text x="140" y="260" class="title">Herzlich willkommen!</text>

  <text x="140" y="310" class="subtitle">
    Länder • Sprachen • Studium • Alphabet • Zahlen
  </text>

  <!-- LEFT: Wortfelder -->
  <rect x="140" y="360" width="400" height="300" rx="20"
        fill="#f6f9f1" stroke="#dfe8ce"/>

  <text x="170" y="410" class="head">Wortfelder</text>

  <text x="170" y="450" class="text">• Länder</text>
  <text x="170" y="485" class="text">• Sprachen</text>
  <text x="170" y="520" class="text">• Studienfächer</text>
  <text x="170" y="555" class="text">• Alphabet</text>
  <text x="170" y="590" class="text">• Zahlen</text>

  <!-- CENTER: Sprachhandlungen -->
  <rect x="600" y="360" width="400" height="300" rx="20"
        fill="#f8faf4" stroke="#dfe8ce"/>

  <text x="630" y="410" class="head">Sprachhandlungen</text>

  <text x="630" y="450" class="text">• sich begrüßen</text>
  <text x="630" y="485" class="text">• nach Befinden fragen</text>
  <text x="630" y="520" class="text">• sich vorstellen</text>
  <text x="630" y="555" class="text">• Namen buchstabieren</text>
  <text x="630" y="590" class="text">• Telefonnummer sagen</text>

  <!-- RIGHT: Grammatik -->
  <rect x="1060" y="360" width="400" height="300" rx="20"
        fill="#f6f9f1" stroke="#dfe8ce"/>

  <text x="1090" y="410" class="head">Grammatik</text>

  <text x="1090" y="450" class="text">• Aussagesatz</text>
  <text x="1090" y="485" class="text">• W-Fragen</text>
  <text x="1090" y="520" class="text">• Ja/Nein-Fragen</text>
  <text x="1090" y="555" class="text">• Verben im Präsens</text>
  <text x="1090" y="590" class="text">• Personalpronomen</text>

</svg>

    --{{0}}--

!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/Avatar_1_%E2%80%94_Welcome_%2B_Lesson_Overview.mp4?raw=true)

# 🤖 A1.1 Deutsch Lern-Bot

<div style="background:linear-gradient(135deg,#eef7f0,#ffffff);border:3px solid #9fb522;border-radius:22px;padding:25px;box-shadow:0 8px 22px rgba(0,0,0,.12);">

<div style="font-size:30px;font-weight:800;color:#2f3b1f;margin-bottom:10px;">

 🤖 A1.1 Deutsch Lern-Bot
</div>


<p style="font-size:17px;color:#333;">
Ask me questions about this German A1.1 lesson.
</p>

<input id="a1ChatInput"
       placeholder="Example: What is the difference between du and Sie?"
       style="width:100%;padding:14px;border:2px solid #9fb522;border-radius:12px;font-size:16px;">

<button id="a1AskButton" type="button"
        style="margin-top:12px;background:#9fb522;color:white;border:none;padding:12px 22px;border-radius:12px;font-size:16px;font-weight:bold;cursor:pointer;">
Ask Bot
</button>

<button id="a1ExampleButton" type="button"
        style="margin-top:12px;background:#527d9b;color:white;border:none;padding:12px 22px;border-radius:12px;font-size:16px;font-weight:bold;cursor:pointer;">
Show Example Questions
</button>

<div id="a1ChatAnswer"
     style="margin-top:20px;background:white;border-left:8px solid #9fb522;border-radius:16px;padding:18px;min-height:90px;font-size:17px;line-height:1.6;">
👋 Hallo! Ask me about alphabet, numbers, greetings, grammar, phone numbers, or introducing yourself.
</div>

</div>

<script>
(function () {
  const qa = [
    {
      keys: ["alphabet", "letters", "buchstaben", "abc"],
      answer: "The German alphabet helps you spell names, words and e-mail addresses. Special German letters are Ä, Ö, Ü and ß. Example: Ä wie Äpfel, Ö wie Öl, Ü wie Übung, ß wie Straße."
    },
    {
      keys: ["spell", "buchstabieren", "wie schreibt man das"],
      answer: "To ask spelling in German, say: Wie schreibt man das? Example: Pak is P-A-K. Girard is G-I-R-A-R-D."
    },
    {
      keys: ["numbers", "zahlen", "1 to 10", "eins"],
      answer: "Numbers 1 to 10 are: eins, zwei, drei, vier, fünf, sechs, sieben, acht, neun, zehn."
    },
    {
      keys: ["greeting", "hallo", "guten tag", "begrüßung"],
      answer: "German greetings are: Hallo, Guten Morgen, Guten Tag and Guten Abend. Goodbye can be Tschüss or Auf Wiedersehen."
    },
    {
      keys: ["name", "wie heißt du", "wie heissen sie", "wie heißen sie"],
      answer: "Informal: Wie heißt du? Answer: Ich bin Dana Pak. Formal: Wie heißen Sie? Answer: Ich heiße Sarah."
    },
    {
      keys: ["du", "sie", "formal", "informal", "difference"],
      answer: "Du is informal. Use du with friends, family and students. Sie is formal. Use Sie with teachers, professors, strangers and official situations."
    },
    {
      keys: ["woher kommst du", "where from", "origin", "herkunft"],
      answer: "Woher kommst du? means Where are you from? Formal: Woher kommen Sie? Answer: Ich komme aus Pakistan."
    },
    {
      keys: ["aus", "country", "land", "stadt"],
      answer: "Use aus for country or city of origin. Examples: aus Deutschland, aus Frankreich, aus Pakistan, aus Berlin, aus Nancy."
    },
    {
      keys: ["w questions", "w-fragen", "wie", "woher", "was"],
      answer: "W-Fragen begin with question words like Wie, Woher and Was. Examples: Wie heißt du? Woher kommst du? Was studierst du?"
    },
    {
      keys: ["verb", "verbs", "präsens", "present tense"],
      answer: "German present tense is called Präsens. The verb changes with the person. Example: ich komme, du kommst, er kommt, wir kommen, ihr kommt, sie kommen."
    },
    {
      keys: ["sein", "bin", "bist", "ist", "sind", "seid"],
      answer: "The verb sein is irregular: ich bin, du bist, er/sie/es ist, wir sind, ihr seid, sie/Sie sind."
    },
    {
      keys: ["sprechen", "sprichst", "spricht"],
      answer: "Sprechen changes in du and er/sie/es: ich spreche, du sprichst, er spricht, wir sprechen, ihr sprecht, sie sprechen."
    },
    {
      keys: ["ich bin", "ich"],
      answer: "Use Ich with another verb: Ich komme aus Madrid. Ich heiße Sarah. Use Ich bin for I am: Ich bin Sarah. Ich bin Student."
    },
    {
      keys: ["wie geht es dir", "wie geht es ihnen", "how are you"],
      answer: "Informal: Wie geht es dir? Formal: Wie geht es Ihnen? Answer: Mir geht es gut, danke."
    },
    {
      keys: ["word order", "wortstellung", "position"],
      answer: "German word order: W-question = question word + verb. Example: Woher kommst du? Yes/no question = verb first. Example: Kommst du morgen? Statement = verb position 2. Example: Ich komme aus Pakistan."
    },
    {
      keys: ["phone", "telefonnummer", "handynummer"],
      answer: "To ask for a phone number: Wie ist deine Telefonnummer? For mobile number: Wie ist deine Handynummer? Answer: Meine Handynummer ist ..."
    },
    {
      keys: ["email", "e-mail", "mail", "at", "punkt"],
      answer: "To ask for an e-mail address: Wie ist deine E-Mail-Adresse? Symbols: @ = at, . = Punkt, - = minus, _ = Unterstrich."
    },
    {
      keys: ["big numbers", "hundert", "tausend", "million"],
      answer: "Big numbers: 100 = einhundert, 200 = zweihundert, 1000 = eintausend, 10 000 = zehntausend, 1 000 000 = eine Million."
    },
    {
      keys: ["introduce", "introduction", "vorstellen"],
      answer: "Example introduction: Hallo, ich heiße Masub. Ich komme aus Pakistan. Ich wohne in Magdeburg. Ich spreche Urdu, Englisch und ein bisschen Deutsch."
    }
  ];

  function normalize(text) {
    return String(text || "")
      .toLowerCase()
      .replace(/ä/g, "ae")
      .replace(/ö/g, "oe")
      .replace(/ü/g, "ue")
      .replace(/ß/g, "ss")
      .replace(/[^\w\s@.-]/g, " ")
      .replace(/\s+/g, " ")
      .trim();
  }

  function askBot() {
    const input = document.getElementById("a1ChatInput");
    const output = document.getElementById("a1ChatAnswer");

    if (!input || !output) return;

    const q = normalize(input.value);

    if (!q) {
      output.innerHTML = "Please type a question. Example: <b>What is the difference between du and Sie?</b>";
      return;
    }

    let bestAnswer = "";
    let bestScore = 0;

    qa.forEach(function(item) {
      let score = 0;

      item.keys.forEach(function(key) {
        const k = normalize(key);

        if (q.includes(k)) {
          score += 10;
        }

        k.split(" ").forEach(function(word) {
          if (word.length > 3 && q.includes(word)) {
            score += 2;
          }
        });
      });

      if (score > bestScore) {
        bestScore = score;
        bestAnswer = item.answer;
      }
    });

    if (bestScore > 0) {
      output.innerHTML =
        "<b>Answer:</b><br>" +
        bestAnswer +
        "<br><br><b>Practice:</b> Read the German example aloud two times.";
    } else {
      output.innerHTML =
        "I am not sure. Ask about alphabet, numbers, greetings, du/Sie, W-Fragen, verbs, word order, phone numbers, e-mail, or introduction.";
    }
  }

  function showExamples() {
    const output = document.getElementById("a1ChatAnswer");
    if (!output) return;

    output.innerHTML =
      "<b>Example questions:</b><br>" +
      "1. What is the difference between du and Sie?<br>" +
      "2. How do I ask name in German?<br>" +
      "3. What means Woher kommst du?<br>" +
      "4. How do I conjugate kommen?<br>" +
      "5. What is sein?<br>" +
      "6. How do I ask phone number?<br>" +
      "7. How do I introduce myself?<br>" +
      "8. What are German numbers 1 to 10?";
  }

  function connectBot() {
    const askButton = document.getElementById("a1AskButton");
    const exampleButton = document.getElementById("a1ExampleButton");
    const input = document.getElementById("a1ChatInput");

    if (askButton) {
      askButton.onclick = function(event) {
        event.preventDefault();
        askBot();
        return false;
      };
    }

    if (exampleButton) {
      exampleButton.onclick = function(event) {
        event.preventDefault();
        showExamples();
        return false;
      };
    }

    if (input) {
      input.onkeydown = function(event) {
        if (event.key === "Enter") {
          event.preventDefault();
          askBot();
          return false;
        }
      };
    }
  }

  setTimeout(connectBot, 300);
  setTimeout(connectBot, 1000);
})();
</script>

# Hallo Deutschland!

 ## <span style="color:#006400;font-size:1.8em;font-weight:bold">
 Das Alphabet: Hören Sie die Buchstaben und sprechen Sie nach
</span>

?[](https://github.com/Masub27/Intro/blob/main/KursDaF_A1_KB_Track_001.mp3?raw=true)

    --{{0}}--

!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/Avatar%202%20%E2%80%94%20Alphabet%20%2B%20German%20Sound.mp4?raw=true)


 | Buchstabe | Lautschrift  | Beispielwort |
|-----------|-------------|--------------|
| A a       | [aː]        | Apfel        |
| B b       | [beː]       | Ball         |
| C c       | [tseː]      | Computer     |
| D d       | [deː]       | Dorf         |
| E e       | [eː]        | Elefant      |
| F f       | [ɛf]        | Fisch        |
| G g       | [geː]       | Garten       |
| H h       | [haː]       | Haus         |
| I i       | [iː]        | Igel         |
| J j       | [jɔt]       | Jagd         |
| K k       | [kaː]       | Kuchen       |
| L l       | [ɛl]        | Lampe        |
| M m       | [ɛm]        | Mond         |
| N n       | [ɛn]        | Nase         |
| O o       | [oː]        | Ostern       |
| P p       | [peː]       | Pferd        |
| Q q       | [kuː]       | Qualle       |
| R r       | [ɛʁ]        | Rose         |
| S s       | [ɛs]        | Sonne        |
| T t       | [teː]       | Tisch        |
| U u       | [uː]        | Uhr          |
| V v       | [faʊ]       | Vogel        |
| W w       | [veː]       | Wasser       |
| X x       | [ɪks]       | Xylophon     |
| Y y       | [ˈʏpsilɔn]  | Yoga         |
| Z z       | [tsɛt]      | Zebra        |
| Ä ä       | [ɛː]        | Äpfel        |
| Ö ö       | [øː]        | Öl           |
| Ü ü       | [yː]        | Übung        |
| ẞ ß       | [ɛsˈtsɛt]   | Straße       |



 



# Horen Sie die Zahlen und sprechen Sie nach. 

?[](https://github.com/Masub27/Thesis-collection/blob/main/KursDaF_A1_KB_Track_004.mp3?raw=true)


| Zahl | Deutsch    | Aussprache       |
|------|------------|------------------|
| 1    | eins       | [aɪns]           |
| 2    | zwei       | [tsvaɪ]          |
| 3    | drei       | [dʁaɪ]           |
| 4    | vier       | [fiːɐ̯]           |
| 5    | fünf       | [fʏnf]           |
| 6    | sechs      | [zɛks]           |
| 7    | sieben     | [ˈziːbn̩]         |
| 8    | acht       | [axt]            |
| 9    | neun       | [nɔɪ̯n]           |
| 10   | zehn       | [tseːn]          |

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/Avatar%203%20%E2%80%94%20Numbers%201%20to%2010_1080p.mp4?raw=true)

# Horen Sie und schreiben Sie die Namen

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/Avatar%204%20%E2%80%94%20Names%20%2B%20Spelling%20Practice_1080p.mp4?raw=true)

?[](https://github.com/Masub27/Thesis-collection/blob/main/KursDaF_A1_KB_Track_003.mp3?raw=true)

1)Nelson [[M]][[ü]][[l]][[l]][[e]][[r]]

2)Christen [[S]][[e]][[i]][[d]][[e]][[l]]

 ## Horen und Schreiben Sie die Telefonnummern.

 ?[](https://github.com/Masub27/Thesis-collection/blob/main/KursDaF_A1_KB_Track_005.mp3?raw=true)

1)Arek [[5]][[6]][[0]][[3]][[9]][[4]][[1]] 

2)Linus [[2]][[7]][[8]][[0]][[1]][[4]][[8]]    

3)Ella [[3]][[0]][[7]][[4]][[9]][[2]][[8]]  


<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for “Hören Sie und schreiben Sie die Namen”</b></summary>

In this listening exercise, you hear:
👂 first names and family names in German.

Your task:
✅ listen carefully  
✅ write the correct letters  
✅ pay attention to German pronunciation

---

## Helpful strategy

German names are often spelled:
🔤 letter by letter.

Listen carefully to:
- vowels
- umlauts
- double consonants

---

## Important pronunciation

### Umlauts

- ü sounds different from u
- Müller → Mü-ller

---

## Helpful listening tips

Focus on:
✅ the first letter  
✅ double letters  
✅ endings like:
- er
- el
- en

---

## Example

If you hear:
🗣️ Müller

You write:
✅ M ü l l e r

---

## Practice tip

Pause the audio after each name and repeat:
🗣️ Nelson Müller  
🗣️ Christen Seidel

This improves pronunciation and spelling.

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for “Hören und Schreiben Sie die Telefonnummern”</b></summary>

In this exercise, you listen to:
📞 German telephone numbers.

Your task:
✅ hear the numbers correctly  
✅ write each digit in the correct order

---

## Important listening strategy

German phone numbers are usually spoken:
🔢 digit by digit
or
🔢 in small number groups.

Listen carefully and slowly.

---

## Helpful number review

| Zahl | Deutsch |
|---|---|
| 0 | null |
| 1 | eins |
| 2 | zwei |
| 3 | drei |
| 4 | vier |
| 5 | fünf |
| 6 | sechs |
| 7 | sieben |
| 8 | acht |
| 9 | neun |

---

## Helpful trick

Write:
✏️ one number at a time.

Pause if necessary and check:
✅ order  
✅ repeated numbers  
✅ zero (null)

---

## Example

If you hear:
🗣️ fünf sechs null drei

You write:
✅ 5603

---

## Practice tip

Repeat the numbers aloud:
🗣️ fünf sechs null drei neun vier eins

This helps your listening and pronunciation.

</details>


# Hallo und guten Tag!

<div class="lesson-box">
  <div class="unit-title">
    <span class="circle-no">1</span>
    <span>Hallo und guten Tag!</span>
  </div>
</div>

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/Avatar%206%20%E2%80%94%20Greetings_%20Hallo%20und%20guten%20Tag_1080p.mp4?raw=true)

 ## a) Hören Sie die Gespräche 1 und 2. Welches Foto passt? Ordnen Sie zu.

<div class="lesson-box">

<div class="task-title">?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_007.mp3?raw=true)

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_008.mp3?raw=true)</div>

<div class="photo-grid">

<div class="photo-card">
  <div class="photo-label">A</div>

  <div class="scene">
    <img src="https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/Bildschirmfoto2023-06-06um13.32.41.png?raw=true" alt="Foto A" style="width:100%; height:260px; object-fit:cover; border-radius:12px;">
  </div>

  <div class="answer-line">
    a. Gespräch [[2]]
  </div>
</div>

<div class="photo-card">
  <div class="photo-label">B</div>

  <div class="scene">
    <img src="https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/image3.png?raw=true" alt="Foto B" style="width:100%; height:260px; object-fit:cover; border-radius:12px;">
  </div>

  <div class="answer-line">
    b. Gespräch [[1]]
  </div>
</div>

</div>
</div>



 ## b) Hören Sie die Gespräche noch einmal und lesen Sie mit.

<div class="lesson-box">

<div class="task-title">
Hören Sie die Gespräche 1 und 2 noch einmal und lesen Sie mit. Ergänzen Sie in Gespräch 2 den Familiennamen.
</div>

<div class="dialogue">

<div class="dialogue-card">
<h3>Gespräch 1</h3>

<div class="line"><span class="speaker1">●</span> Hallo. Ich bin Dana. Ich bin neu hier im Deutschkurs. Wie heißt du?</div>

<div class="line"><span class="speaker2">○</span> Hallo Dana. Ich heiße Sarah. Ich komme aus Frankreich, aus Nancy.</div>

<div class="line"><span class="speaker2">○</span> Und du, woher kommst du?</div>

<div class="line"><span class="speaker1">●</span> Ich komme aus Kasachstan, aus Almaty.</div>
</div>

<div class="dialogue-card">
<h3>Gespräch 2</h3>

<div class="line"><span class="speaker1">■</span> Guten Tag! Ich heiße Nora Klein. Ich bin Ihre Deutschlehrerin.</div>

<div class="line"><span class="speaker2">○</span> Guten Tag, Frau Klein. Ich bin Sarah.</div>

<div class="line"><span class="speaker1">■</span> Und wie ist Ihr Familienname?</div>

<div class="line"><span class="speaker2">○</span> Mein Familienname ist [[Girard]].</div>

<div class="line"><span class="speaker1">■</span> Entschuldigung, wie schreibt man das? Buchstabieren Sie das bitte.</div>

<div class="line"><span class="speaker2">○</span> [[G]] [[I]] [[R]] [[A]][[R]] [[D]]</div>

<div class="line"><span class="speaker1">■</span> Danke sehr. Und woher kommen Sie, Frau [[Girard]]?</div>

<div class="line"><span class="speaker2">○</span> Ich komme aus Nancy.</div>

<div class="line"><span class="speaker1">■</span> Vielen Dank! Und wie heißen Sie?</div>

<div class="line"><span class="speaker2">○</span> Ich bin Dana Pak. Dana ist mein Vorname und Pak ist mein Familienname.</div>

<div class="line"><span class="speaker1">■</span> Vielen Dank, Frau Pak. Willkommen im Kurs!</div>
</div>

</div>
</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1a</b></summary>

In this listening exercise, you hear:
🎧 two short conversations in a German course.

Your task:
✅ listen carefully  
✅ understand the situation  
✅ match the correct conversation with the correct photo

---

## Helpful strategy

Listen for:
👥 Who is speaking?
👩‍🏫 Teacher or students?
😊 Formal or informal conversation?

---

## Important clues

### Gespräch 1
You hear:
- “Hallo”
- “Wie heißt du?”
- “Woher kommst du?”

This is:
✅ informal language  
✅ student to student

Look for:
👩‍🎓 classmates / course participants

---

### Gespräch 2
You hear:
- “Guten Tag”
- “Frau Klein”
- “Wie ist Ihr Familienname?”

This is:
✅ formal language  
✅ teacher and student

Look for:
👩‍🏫 classroom / teacher situation

---

## Helpful vocabulary

- der Deutschkurs = German course
- die Deutschlehrerin = German teacher
- neu = new
- willkommen = welcome

---

## Listening tip

Do NOT only listen to single words.
Listen to:
✅ the situation  
✅ the relationship between speakers  
✅ formal vs informal speech

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1b</b></summary>

In this exercise, you:
🎧 listen and read the dialogues  
✍️ complete the family name and spelling

Your task:
✅ understand introductions  
✅ identify first name and family name  
✅ listen to spelling carefully

---

## Helpful vocabulary

- der Vorname = first name
- der Familienname = family name / surname
- buchstabieren = to spell
- Wie schreibt man das? = How do you write that?
- Willkommen im Kurs! = Welcome to the course!

---

## Important grammar

### Informal language

- Wie heißt du?
- Woher kommst du?

Used with:
👫 friends / classmates

---

### Formal language

- Wie heißen Sie?
- Woher kommen Sie?

Used with:
👩‍🏫 teachers / official situations

---

## Helpful listening strategy

When people spell names in German:
🔤 listen letter by letter.

Example:
🗣️ G – I – R – A – R – D

→ Girard

---

## Helpful tip

Pay attention to:
✅ capital letters in names  
✅ pronunciation of letters  
✅ repeated letters

---

## Practice tip

Read the dialogue aloud:

🗣️ Guten Tag, Frau Klein.  
🗣️ Mein Familienname ist Girard.

This improves:
✅ pronunciation  
✅ fluency  
✅ listening comprehension

</details>

---

## c) Hören Sie genau und schreiben Sie.

<div class="lesson-box">

<div class="task-title">?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_009.mp3?raw=true)</div>

1. Wie heiß [[t]] [[du]]?

2. Wie heiß [[en]] [[Sie]]?

</div>

---

 ## d) Lesen Sie die Gespräche noch einmal und vergleichen Sie.

<div class="lesson-box">

<div class="task-title">
Lesen Sie die Gespräche in 1b noch einmal und vergleichen Sie. Ergänzen Sie die Anrede.
</div>

<div class="info-grid">

<div class="info-card">
<h3>Informelle Anrede</h3>

<p><b>Studierende, Freunde, Familie</b></p>

<p>Vorname, z. B. Dana, Sarah → [[du]]</p>

<p class="small-note">Beispiel: Wie heißt du?</p>
</div>

<div class="info-card">
<h3>Formelle Anrede</h3>

<p><b>Lehrerin / Lehrer, Professorin / Professor, Fremde</b></p>

<p>Frau / Herr + Familienname, z. B. Herr Schulz, Frau Girard → [[Sie]]</p>

<p class="small-note">Beispiel: Wie heißen Sie?</p>
</div>

</div>
</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1c</b></summary>

In this listening exercise, you focus on:
🎧 German verb endings  
👥 informal and formal forms

Your task:
✅ listen carefully  
✅ complete the missing words  
✅ identify:
- du form
- Sie form

---

## Important grammar

### Informal form → du

Question:
🗣️ Wie heißt du?

Verb ending:
✅ -t

Example:
- heißen → heißt

---

### Formal form → Sie

Question:
🗣️ Wie heißen Sie?

Verb ending:
✅ -en

Example:
- heißen → heißen

---

## Helpful strategy

Listen for:
👂 the pronoun
- du
or
- Sie

This helps you choose the correct verb form.

---

## Important difference

| Informal | Formal |
|---|---|
| du | Sie |
| Wie heißt du? | Wie heißen Sie? |

---

## Listening tip

The pronunciation is different:

- heißt du → shorter ending
- heißen Sie → longer “-en” sound

Listen carefully to the verb ending.

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1d</b></summary>

In this exercise, you compare:
👥 informal language  
👩‍🏫 formal language

Your task:
✅ identify the correct form of address  
✅ choose:
- du
or
- Sie

---

## Informal address

Use:
👉 <b>du</b>

with:
- friends
- classmates
- family
- students of the same age

Examples:
- Hallo Dana.
- Wie heißt du?

Usually:
✅ first name only

---

## Formal address

Use:
👉 <b>Sie</b>

with:
- teachers
- professors
- strangers
- official situations

Examples:
- Guten Tag, Frau Girard.
- Wie heißen Sie?

Usually:
✅ Frau / Herr + family name

---

## Helpful vocabulary

- die Anrede = form of address
- informell = informal
- formell = formal
- der Vorname = first name
- der Familienname = family name

---

## Helpful strategy

Ask yourself:

👫 Are the speakers friends or classmates?
→ use <b>du</b>

👩‍🏫 Is one person a teacher or stranger?
→ use <b>Sie</b>

---

## Important tip

In German:
✅ first names often = informal  
✅ family names with Frau/Herr = formal

</details>

---

# 2 Grammatik kompakt: W-Fragen und Antworten

<div style="background:linear-gradient(135deg,#eef7f0,#ffffff); border:3px solid #9fb522; border-radius:22px; padding:25px; box-shadow:0 8px 22px rgba(0,0,0,.12);">

<div style="display:flex; align-items:center; gap:15px;">
<div style="width:50px; height:50px; border-radius:50%; background:#9fb522; color:white; display:flex; align-items:center; justify-content:center; font-size:26px; font-weight:bold;">2</div>
<div style="font-size:30px; font-weight:800; color:#2f3b1f;">[ GRAMMATIK KOMPAKT ] W-Fragen und Antworten</div>
<div style="margin-left:auto; background:#9fb522; color:white; padding:10px 18px; border-radius:8px; font-weight:bold;">1 A</div>
</div>

</div>

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/Avatar%209%20%E2%80%94%20W-Questions%20and%20Answers_1080p.mp4?raw=true)

 ## 2a) Ergänzen Sie Fragen und Antworten aus 1b.

<div style="background:#ffffff; border-radius:20px; padding:25px; border:2px solid #d6dfb8; box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="font-size:22px; font-weight:800; color:#4d6500; margin-bottom:15px;">🧩 Interaktive Grammatik-Tabelle</div>

<div style="display:grid; grid-template-columns:1fr 1fr; gap:25px;">

<div style="background:#eef8f7; border-radius:18px; padding:18px; border:2px solid #a8c8c4;">
<h3 style="margin-top:0; color:#1d4d4a;">W-Frage</h3>

| W-Frage | Verb | Person / Ergänzung |
|---|---|---|
| Wie | heißt | du? |
| [[Wie]] | [[heißen]] | Sie? |
| Woher | kommst | du? |
| [[Woher]] | [[kommen]] | Sie? |
| Wie | ist | Ihr Familienname? |

</div>

<div style="background:#f3f7e6; border-radius:18px; padding:18px; border:2px solid #c9d98b;">
<h3 style="margin-top:0; color:#526700;">Antwort</h3>

| Antwort | Verb | Ergänzung |
|---|---|---|
| Ich | [[heiße]] | Sarah. |
| Ich | bin | Dana Pak. |
| [[Ich]] | [[komme]] | aus Kasachstan. |
| Ich | komme | aus Nancy. |
| [[Mein Familienname]]    | [[ist]]   | Girard. |

</div>

</div>

</div>

---



 ## 🎧 2b) Welche Antwort passt? Ordnen Sie zu.

<div style="background:#ffffff; border-radius:20px; padding:25px; border:2px solid #d6dfb8; box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="font-size:22px; font-weight:800; color:#4d6500; margin-bottom:15px;">Ordnen Sie die Antworten zu.</div>

<div style="display:grid; grid-template-columns:1fr 1fr; gap:25px;">

<div style="background:#fff8e6; border-radius:18px; padding:18px; border:2px solid #e5c86b;">
<h3 style="margin-top:0;">❓ Fragen</h3>

1. Wie heißen Sie?  
2. Woher kommst du?  
3. Woher kommen Sie?  
4. Wie heißt du?  
5. Wie ist Ihr Familienname?  
6. Wie schreibt man das?

</div>

<div style="background:#eef8f7; border-radius:18px; padding:18px; border:2px solid #9fc9c4;">
<h3 style="margin-top:0;">✅ Antworten</h3>

* a. P – A – K.  
* b. Ich heiße Sarah Girard.  
* c. Aus Nancy. Und du?  
* d. Mein Familienname ist Girard.  
* e. Ich bin aus Kasachstan. Und Sie?  
* f. Ich bin Sarah.

</div>

</div>

</div>

---

 ## 🧠 Interaktive Zuordnung

Schreiben Sie den richtigen Buchstaben.

1. Wie heißen Sie? [[b]]  
2. Woher kommst du? [[c]]  
3. Woher kommen Sie? [[e]]  
4. Wie heißt du? [[f]]  
5. Wie ist Ihr Familienname? [[d]]  
6. Wie schreibt man das? [[a]]

---

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2a</b></summary>

In this grammar exercise, you practice:
❓ W-questions  
💬 answers in German

Your task:
✅ complete the questions  
✅ complete the answers  
✅ choose the correct verb forms

---

## Important W-questions

| German | English |
|---|---|
| Wie? | How / What |
| Woher? | Where from |

---

## Important question patterns

### Asking for a name

👫 Informal:
- Wie heißt du?

👩‍🏫 Formal:
- Wie heißen Sie?

---

### Asking about origin

👫 Informal:
- Woher kommst du?

👩‍🏫 Formal:
- Woher kommen Sie?

---

## Helpful grammar

### Verb position

In German questions:
✅ the verb comes in position 2.

Examples:
- Wie heißen Sie?
- Woher kommst du?

---

## Helpful answer patterns

### Name

- Ich heiße Sarah.
- Ich bin Dana Pak.

### Origin

- Ich komme aus Kasachstan.
- Ich komme aus Nancy.

### Family name

- Mein Familienname ist Girard.

---

## Important tip

Look carefully at:
👥 du or Sie

because the verb changes:

- du → kommst / heißt
- Sie → kommen / heißen

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2b</b></summary>

In this matching exercise, you connect:
❓ questions  
✅ correct answers

Your task:
✅ understand the meaning of each question  
✅ choose the matching answer

---

## Helpful strategy

First ask:
👉 What information does the question ask for?

Then choose the answer:
- name
- origin
- spelling
- family name

---

## Important question types

### Name

Question:
- Wie heißen Sie?
- Wie heißt du?

Answer:
- Ich heiße Sarah.
- Ich bin Sarah.

---

### Origin

Question:
- Woher kommst du?
- Woher kommen Sie?

Answer:
- Ich komme aus Kasachstan.
- Aus Nancy.

---

### Family name

Question:
- Wie ist Ihr Familienname?

Answer:
- Mein Familienname ist Girard.

---

### Spelling

Question:
- Wie schreibt man das?

Answer:
- P – A – K.

---

## Helpful tip

Look for key words:

| Question word | Expected answer |
|---|---|
| Wie heißen ...? | Name |
| Woher ...? | Country / city |
| Familienname | Surname |
| schreibt | Letters / spelling |

---

## Practice tip

Read the pairs aloud:

🗣️ Wie heißen Sie?  
🗣️ Ich heiße Sarah Girard.

🗣️ Woher kommst du?  
🗣️ Aus Nancy.

This improves:
✅ speaking  
✅ listening  
✅ grammar understanding

</details>

# 3 

<div style="background:linear-gradient(135deg,#eef7f0,#ffffff); border:3px solid #9fb522; border-radius:22px; padding:25px; box-shadow:0 8px 22px rgba(0,0,0,.12);">

<div style="display:flex; align-items:center; gap:15px;">
<div style="width:50px; height:50px; border-radius:50%; background:#9fb522; color:white; display:flex; align-items:center; justify-content:center; font-size:26px; font-weight:bold;">3</div>
<div style="font-size:28px; font-weight:800; color:#2f3b1f;">Woher kommen die Nobelpreisträgerinnen und Nobelpreisträger?</div>
</div>

</div>

---

 ## 3a) Woher kommen die Nobelpreisträger? Ergänzen Sie.
 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_010.mp3?raw=true)

<div style="background:#ffffff; border-radius:20px; padding:25px; border:2px solid #d6dfb8; box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="font-size:21px; font-weight:800; color:#4d6500;">🌍 Länder und Herkunft</div>

<div style="display:grid; grid-template-columns:repeat(3,1fr); gap:12px; margin-top:18px;">

<div style="background:#eef8f7; padding:12px; border-radius:12px;">aus China</div>
<div style="background:#eef8f7; padding:12px; border-radius:12px;">aus Großbritannien</div>
<div style="background:#eef8f7; padding:12px; border-radius:12px;">aus Österreich</div>

<div style="background:#f3f7e6; padding:12px; border-radius:12px;">aus den Niederlanden</div>
<div style="background:#f3f7e6; padding:12px; border-radius:12px;">aus der Schweiz</div>
<div style="background:#f3f7e6; padding:12px; border-radius:12px;">aus Deutschland</div>

<div style="background:#fff8e6; padding:12px; border-radius:12px;">aus Japan</div>
<div style="background:#fff8e6; padding:12px; border-radius:12px;">aus Peru</div>
<div style="background:#fff8e6; padding:12px; border-radius:12px;">aus den USA</div>

<div style="background:#eef3ff; padding:12px; border-radius:12px;">aus der Türkei</div>
<div style="background:#eef3ff; padding:12px; border-radius:12px;">aus Ghana</div>
<div style="background:#eef3ff; padding:12px; border-radius:12px;">aus Kanada</div>

<div style="background:#f6eefe; padding:12px; border-radius:12px;">aus Tansania</div>
<div style="background:#f6eefe; padding:12px; border-radius:12px;">aus dem Iran</div>

</div>

</div>

---

 ## 🏅  Ergänzen Sie die Herkunft.

<div style="background:#ffffff; border-radius:20px; padding:25px; border:2px solid #d6dfb8; box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="display:grid; grid-template-columns:1fr 1fr; gap:25px;">

<div style="background:#f7fbff; border-radius:18px; padding:18px; border:2px solid #b5d2ef;">

1. Kofi Annan — aus Ghana  
2. Shirin Ebadi — [[aus dem Iran]]  
3. Elfriede Jelinek — [[aus Österreich]]  
4. Orhan Pamuk — [[aus der Türkei]]  
5. Peter Grünberg — [[aus Deutschland]]  
6. Makoto Kobayashi — [[aus Japan]]  
7. Elinor Ostrom — [[aus den USA]]

</div>

<div style="background:#f7fbff; border-radius:18px; padding:18px; border:2px solid #b5d2ef;">

8. Mario Vargas Llosa — [[aus Peru]]  
9. Tu Youyou — [[aus China]]  
10. Ben Feringa — [[aus den Niederlanden]]  
11. Richard Henderson — [[aus Großbritannien]]  
12. Donna Strickland — [[aus Kanada]]  
13. Michel Mayor — [[aus der Schweiz]]  
14. Abdulrazak Gurnah — [[aus Tansania]]

</div>

</div>

</div>

---



 ## 3b) Ergänzen Sie.

<div style="background:linear-gradient(135deg,#fff8e6,#ffffff); border:2px solid #e5c86b; border-radius:20px; padding:25px;">

<div style="font-size:21px; font-weight:800; color:#7a5a00;">📌 Grammatikregel</div>

**aus + Land / Stadt:**  
aus Frankreich / aus Nancy.

**Aber:**  
aus der Schweiz, aus der [[Türkei]], aus den [[Niederlanden]], aus den [[USA]], aus dem [[Iran]]

</div>

@style
<style>
.chapter-box{
  background: linear-gradient(135deg,#fbfcf7,#ffffff);
  border: 2px solid #d9dfc6;
  border-radius: 18px;
  padding: 18px;
  margin: 18px 0;
  box-shadow: 0 6px 18px rgba(0,0,0,.08);
}
.subtask{
  font-size: 17px;
  font-weight: 700;
  margin: 10px 0 16px 0;
  color: #444;
}
.note-box{
  background:#f5f8e8;
  border-left:6px solid #9fb522;
  padding:12px 14px;
  border-radius:12px;
  margin:12px 0 18px 0;
}
.center-title{
  text-align:center;
  font-size:28px;
  font-weight:900;
  letter-spacing:1px;
  fill:#444;
}
.person-name{
  font-weight:900;
  fill:#597e9b;
}
.small-text{
  font-size:16px;
  fill:#333;
}
</style>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3a</b></summary>

In this listening and vocabulary exercise, you learn:
🌍 countries and origin in German.

Your task:
✅ listen carefully  
✅ identify the country  
✅ complete the sentence with:
👉 aus + country

---

## Important grammar

### Herkunft (origin)

German uses:
👉 <b>aus</b> = from

Examples:
- aus China
- aus Japan
- aus Peru

---

## Important special forms

Some countries use:
- der
- die
- den
- dem

Examples:

| Country | Correct form |
|---|---|
| die Schweiz | aus der Schweiz |
| die Türkei | aus der Türkei |
| die USA | aus den USA |
| die Niederlande | aus den Niederlanden |
| der Iran | aus dem Iran |

---

## Helpful listening strategy

Listen for:
👂 country names  
👂 nationality pronunciation  
👂 important articles:
- der
- die
- den
- dem

---

## Helpful vocabulary

- die Nobelpreisträgerin = female Nobel Prize winner
- der Nobelpreisträger = male Nobel Prize winner
- kommen aus = come from

---

## Helpful tip

Many countries have:
❌ no article

Examples:
- aus Deutschland
- aus Österreich
- aus Ghana

But some countries ALWAYS need an article:
✅ aus der Schweiz
✅ aus den USA

Pay attention to this difference.

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for Herkunft ergänzen</b></summary>

In this exercise, you match:
👤 Nobel Prize winners  
🌍 their countries

Your task:
✅ read the names  
✅ choose the correct country expression

---

## Helpful strategy

Focus on:
👉 the structure after <b>aus</b>

Examples:
- aus Peru
- aus China
- aus Österreich

BUT:
- aus der Türkei
- aus dem Iran
- aus den Niederlanden

---

## Important grammar rule

### No article

Most countries:
✅ aus + country

Examples:
- aus Ghana
- aus Kanada
- aus Japan

---

### With article

Some countries use articles.

Examples:
- die Türkei → aus der Türkei
- der Iran → aus dem Iran
- die USA → aus den USA

---

## Helpful memory trick

If the country has:
- der → aus dem
- die → aus der
- plural → aus den

---

## Example

🇨🇭 die Schweiz  
→ aus der Schweiz

🇺🇸 die USA  
→ aus den USA

🇮🇷 der Iran  
→ aus dem Iran

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3b</b></summary>

In this grammar exercise, you learn:
🌍 how to say origin with countries and cities.

---

## Basic rule

Use:
👉 <b>aus</b> + place

Examples:
- aus Frankreich
- aus Nancy
- aus Deutschland

---

## Special countries

Some countries use articles.

### Feminine countries

- die Schweiz
- die Türkei

Use:
✅ aus der ...

Examples:
- aus der Schweiz
- aus der Türkei

---

### Masculine countries

- der Iran

Use:
✅ aus dem ...

Example:
- aus dem Iran

---

### Plural countries

- die USA
- die Niederlande

Use:
✅ aus den ...

Examples:
- aus den USA
- aus den Niederlanden

---

## Helpful overview

| Country type | Example |
|---|---|
| no article | aus Deutschland |
| feminine | aus der Schweiz |
| masculine | aus dem Iran |
| plural | aus den USA |

---

## Helpful strategy

Ask yourself:
👉 Does the country have an article?

If yes:
✅ change the article after <b>aus</b>

</details>

---

## 1 Wer spricht ...? – Wer studiert ...?

<div class="chapter-box">

<div class="subtask">
>a) Lesen Sie die Porträts und die Kurzinterviews. Was ist richtig: a, b oder c? Kreuzen Sie an.  Manchmal passen zwei Antworten.
</div>

<div class="note-box">
<b>Merken Sie:</b><br>

</div>

<svg xmlns="http://www.w3.org/2000/svg" width="100%" viewBox="0 0 1200 980">

  <!-- Browser frame -->
  <rect x="20" y="20" width="1160" height="930" rx="18" ry="18" fill="#f3f0e7" stroke="#c8c4b6" stroke-width="3"/>
  <rect x="20" y="20" width="1160" height="42" rx="18" ry="18" fill="#e5e1d7" stroke="#c8c4b6" stroke-width="3"/>
  <circle cx="48" cy="42" r="6" fill="#a8a8a8"/>
  <circle cx="66" cy="42" r="6" fill="#a8a8a8"/>
  <circle cx="84" cy="42" r="6" fill="#a8a8a8"/>
  <rect x="110" y="31" width="980" height="20" rx="10" fill="#ffffff" stroke="#d0d0d0"/>

  <text x="600" y="105" text-anchor="middle" style="font-size:28px;font-weight:900;letter-spacing:1px;fill:#444;">
    STUDIERENDE INTERNATIONAL
  </text>

  <!-- Nicole portrait -->
  <circle cx="175" cy="165" r="95" fill="#d8e3ec" stroke="#7e93a4" stroke-width="6"/>
  <circle cx="175" cy="165" r="82" fill="#d7a47c"/>
  <ellipse cx="175" cy="110" rx="56" ry="36" fill="#2d1e1a"/>
  <rect x="123" y="110" width="104" height="70" rx="42" fill="#3a2a24"/>
  <circle cx="150" cy="160" r="9" fill="#222"/>
  <circle cx="200" cy="160" r="9" fill="#222"/>
  <circle cx="150" cy="160" r="3" fill="#fff"/>
  <circle cx="200" cy="160" r="3" fill="#fff"/>
  <path d="M145 190 Q175 212 205 190" stroke="#7a3325" stroke-width="5" fill="none" stroke-linecap="round"/>
  <rect x="128" y="150" width="40" height="24" rx="10" fill="none" stroke="#576b7c" stroke-width="3"/>
  <rect x="182" y="150" width="40" height="24" rx="10" fill="none" stroke="#576b7c" stroke-width="3"/>
  <line x1="168" y1="162" x2="182" y2="162" stroke="#576b7c" stroke-width="3"/>
  <rect x="130" y="226" width="90" height="24" rx="10" fill="#e9b44c"/>

  <!-- Nicole text -->
  <text x="330" y="130" style="font-size:16px;fill:#333;">
    <tspan x="330" dy="0">Das ist </tspan>
    <tspan style="font-weight:900;fill:#597e9b;">NICOLE DONGMO</tspan>
    <tspan>. Sie kommt aus Kamerun.</tspan>
    <tspan x="330" dy="26">Sie wohnt in Leipzig.</tspan>
  </text>

  <text x="330" y="190" style="font-size:16px;fill:#333;">
    <tspan x="330" dy="0">» Nicole, was studierst du?</tspan>
    <tspan x="330" dy="24">Ich studiere Informatik.</tspan>

    <tspan x="330" dy="36">» Welche Sprachen sprichst du?</tspan>
    <tspan x="330" dy="24">Ich spreche Französisch und ich lerne Deutsch</tspan>
    <tspan x="330" dy="24">und Englisch.</tspan>
  </text>

  <!-- Eivor + Fynn text -->
  <text x="90" y="380" style="font-size:16px;fill:#333;">
    <tspan x="90" dy="0">Das sind </tspan>
    <tspan style="font-weight:900;fill:#597e9b;">EIVOR LINDSTRÖM</tspan>
    <tspan> und </tspan>
    <tspan style="font-weight:900;fill:#597e9b;">FYNN NILSSON</tspan>
    <tspan>.</tspan>

    <tspan x="90" dy="24">Sie kommen aus Schweden. Sie wohnen in</tspan>
    <tspan x="90" dy="24">Potsdam und studieren in Berlin.</tspan>

    <tspan x="90" dy="38">» Eivor und Fynn, was studiert ihr?</tspan>
    <tspan x="90" dy="24">Wir studieren Medizin.</tspan>

    <tspan x="90" dy="36">» Wo wohnt ihr?</tspan>
    <tspan x="90" dy="24">Wir wohnen in Potsdam.</tspan>

    <tspan x="90" dy="36">» Welche Sprachen sprecht ihr?</tspan>
    <tspan x="90" dy="24">Wir sprechen Schwedisch, Dänisch, Englisch</tspan>
    <tspan x="90" dy="24">und ein bisschen Deutsch.</tspan>
  </text>

  <!-- Eivor + Fynn portrait -->
  <circle cx="955" cy="470" r="95" fill="#d8e3ec" stroke="#7e93a4" stroke-width="6"/>
  <!-- left face -->
  <circle cx="920" cy="468" r="38" fill="#f0c7a2"/>
  <ellipse cx="920" cy="438" rx="32" ry="20" fill="#8b4a2b"/>
  <circle cx="908" cy="468" r="4" fill="#222"/>
  <circle cx="932" cy="468" r="4" fill="#222"/>
  <path d="M907 486 Q920 494 933 486" stroke="#8b4a2b" stroke-width="3" fill="none" stroke-linecap="round"/>
  <!-- right face -->
  <circle cx="988" cy="470" r="38" fill="#ead4b8"/>
  <ellipse cx="988" cy="440" rx="34" ry="21" fill="#2f2f35"/>
  <circle cx="976" cy="470" r="4" fill="#222"/>
  <circle cx="1000" cy="470" r="4" fill="#222"/>
  <path d="M975 488 Q988 495 1001 488" stroke="#7a4c2e" stroke-width="3" fill="none" stroke-linecap="round"/>
  <rect x="963" y="460" width="20" height="16" rx="6" fill="none" stroke="#576b7c" stroke-width="2"/>
  <rect x="993" y="460" width="20" height="16" rx="6" fill="none" stroke="#576b7c" stroke-width="2"/>
  <line x1="983" y1="468" x2="993" y2="468" stroke="#576b7c" stroke-width="2"/>
  <rect x="892" y="505" width="126" height="26" rx="10" fill="#d9dde8"/>

  <!-- Gabriel portrait -->
  <circle cx="170" cy="760" r="95" fill="#d8e3ec" stroke="#7e93a4" stroke-width="6"/>
  <circle cx="170" cy="760" r="76" fill="#c98e62"/>
  <ellipse cx="170" cy="714" rx="48" ry="26" fill="#30251f"/>
  <rect x="128" y="772" width="84" height="20" rx="10" fill="#3e2b24"/>
  <circle cx="145" cy="755" r="5" fill="#222"/>
  <circle cx="195" cy="755" r="5" fill="#222"/>
  <path d="M148 785 Q170 798 192 785" stroke="#6d3728" stroke-width="4" fill="none" stroke-linecap="round"/>
  <path d="M126 706 L214 706 L197 678 L143 678 Z" fill="#f0c12e" stroke="#c4971b" stroke-width="3"/>
  <rect x="132" y="826" width="76" height="22" rx="10" fill="#83a9d8"/>

  <!-- Gabriel text -->
  <text x="330" y="700" style="font-size:16px;fill:#333;">
    <tspan x="330" dy="0">Das ist </tspan>
    <tspan style="font-weight:900;fill:#597e9b;">GABRIEL MÁRQUEZ</tspan>
    <tspan>. Er kommt aus</tspan>
    <tspan x="330" dy="24">Kolumbien und wohnt in Berlin.</tspan>

    <tspan x="330" dy="38">» Gabriel, was studierst du?</tspan>
    <tspan x="330" dy="24">Ich arbeite schon, ich bin Architekt.</tspan>

    <tspan x="330" dy="36">» Welche Sprachen sprichst du?</tspan>
    <tspan x="330" dy="24">Ich spreche Spanisch, Portugiesisch und Englisch.</tspan>
    <tspan x="330" dy="24">Und ich lerne Deutsch.</tspan>
  </text>

</svg>

</div>

---

 

**1. Wer spricht Englisch?**

[[ ]] a. Nicole  
[[X]] b. Eivor + Fynn  
[[X]] c. Gabriel  

---

**2. Wer spricht Französisch?**

[[X]] a. Nicole  
[[ ]] b. Eivor + Fynn  
[[ ]] c. Gabriel  

---

**3. Wer studiert?**

[[X]] a. Nicole  
[[X]] b. Eivor + Fynn  
[[ ]] c. Gabriel  

---

**4. Wer arbeitet schon?**

[[ ]] a. Nicole  
[[ ]] b. Eivor + Fynn  
[[X]] c. Gabriel  

---

**5. Wer lernt Deutsch?**

[[X]] a. Nicole  
[[ ]] b. Eivor + Fynn  
[[X]] c. Gabriel  

---

**6. Wer wohnt in Berlin?**

[[ ]] a. Nicole  
[[ ]] b. Eivor + Fynn  
[[X]] c. Gabriel  

---

 ## b) Markieren Sie die zentralen Informationen in den Texten in 1a und ergänzen Sie die Tabelle.

<div class="chapter-box">

| Information | Nicole | Eivor und Fynn | Gabriel |
|-------------|--------|----------------|---------|
| Land        | [[Kamerun]] | [[Schweden]] | [[Kolumbien]] |
| Wohnort     | [[Leipzig]] | [[Potsdam]] | [[Berlin]] |
| Studienfach | [[Informatik]] | [[Medizin]] | [[-]] |
| Beruf       | [[-]] | [[-]] | [[Architekt]] |
| Sprachen    | [[Französisch]] / lernt [[Deutsch]] und [[Englisch]] | [[Schwedisch]], [[Dänisch]], [[Englisch]] und ein bisschen [[Deutsch]] | [[Spanisch]], [[Portugiesisch]], [[Englisch]] / lernt [[Deutsch]] |

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1a</b></summary>

In this reading exercise, you read short portraits and interviews about three people:

👩 Nicole  
👫 Eivor + Fynn  
👨 Gabriel

Your task:
✅ read the texts carefully  
✅ find who speaks which language  
✅ find who studies or works  
✅ sometimes choose two correct answers

---

## Helpful reading strategy

Look for these keywords:

### Languages
- Ich spreche ...
- Wir sprechen ...
- ich lerne ...

### Study
- Ich studiere ...
- Wir studieren ...

### Work
- Ich arbeite schon.
- Ich bin Architekt.

### Place of residence
- Sie wohnt in ...
- Sie wohnen in ...
- Er wohnt in ...

---

## Important detail

Sometimes a person:
✅ speaks a language  
or  
✅ learns a language

These are not exactly the same.

Example:
- Nicole spricht Französisch.
- Nicole lernt Deutsch und Englisch.

So read carefully before choosing.

---

## Helpful trick

For every question, ask:

👉 Which person has this information in the text?

Then underline the exact sentence.

Example:
Question: Wer arbeitet schon?  
Text: „Ich arbeite schon, ich bin Architekt.“  
Answer: Gabriel.

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1b</b></summary>

In this table exercise, you collect central information from the portraits.

Your task:
✅ find country  
✅ find city  
✅ find study subject  
✅ find profession  
✅ find languages

---

## Helpful vocabulary

| German | English |
|---|---|
| Land | country |
| Wohnort | place of residence |
| Studienfach | study subject |
| Beruf | profession |
| Sprachen | languages |

---

## Helpful strategy

Read one person at a time.

### Step 1
Find Nicole’s information and fill the Nicole column.

### Step 2
Find Eivor and Fynn’s information and fill their column.

### Step 3
Find Gabriel’s information and fill the Gabriel column.

---

## Important clues in the text

### Nicole
- kommt aus Kamerun
- wohnt in Leipzig
- studiert Informatik
- spricht Französisch
- lernt Deutsch und Englisch

### Eivor und Fynn
- kommen aus Schweden
- wohnen in Potsdam
- studieren Medizin
- sprechen Schwedisch, Dänisch, Englisch und ein bisschen Deutsch

### Gabriel
- kommt aus Kolumbien
- wohnt in Berlin
- arbeitet schon
- ist Architekt
- spricht Spanisch, Portugiesisch und Englisch
- lernt Deutsch

---

## Helpful tip

Use “-” when there is no information or when the person does not study/work in that category.

Example:
Gabriel does not study now, so:
Studienfach = -

</details>

---

# 🟢 [ GRAMMATIK KOMPAKT ] Verben im Präsens

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_Lesson_1/GRAMMATIK%20KOMPAKT%20_720p.mp4?raw=true)

<div class="page-box">

<div class="unit-header">
  <span class="circle-no">2</span>
  <span></span>
</div>

<div class="task-title">
a) Markieren Sie die Verben in 1a. Ergänzen Sie dann die Tabelle.
</div>

| Person | heißen | kommen | wohnen | studieren | arbeiten | sprechen | sein |
|---|---|---|---|---|---|---|---|
| ich | heiß-e | komm-e | wohn-e | studier-e | arbeit-e | sprech-e | bin |
| du | heiß-t | komm-st | wohn-st | studier-st | arbeit-est | <span class="red">sprich-st</span> | <span class="red">bist</span> |
| er / sie / es | heiß-t | komm-t | wohn-t | studier-t | arbeit-et | <span class="red">sprich-t</span> | ist |
| wir | heiß-en | komm-en | wohn-en | studier-en | arbeit-en | sprech-en | <span class="red">sind</span> |
| ihr | heiß-t | komm-t | wohn-t | studier-t | arbeit-et | sprech-t | <span class="red">seid</span> |
| sie / Sie | heiß-en | komm-en | wohn-en | studier-en | arbeit-en | sprech-en | sind |



</div>

---

 

 ## 🧩b) Ergänzen Sie die korrekte Verbform.

<div class="page-box">

<div class="task-title"></div>

<div class="card">

### 1.

😊[[Seid]] ihr auch hier im Deutschkurs?  
Wie [[heißt]] ihr?  
Woher [[kommt]] ihr?  
Was [[studiert]] ihr?

<div class="note">
Verben: kommen, studieren, heißen, sein
</div>

</div>

<div class="card">

### 2.

Das [[sind]] Olivia und Noah.  
Sie [[sind]] neu im Deutschkurs.  
Olivia [[kommt]] aus Kanada.  
Sie [[studiert]] Informatik.  
Noah [[kommt]] aus den USA.  
Er [[studiert]] Chemie.

<div class="note">
2 × sein, 2 × studieren, 2 × kommen
</div>

</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for Grammatik Kompakt – Verben im Präsens (a)</b></summary>

In this grammar exercise, you learn:
🧩 German verbs in the Präsens (present tense).

Your task:
✅ recognize verb endings  
✅ complete the conjugation table  
✅ compare different persons:
- ich
- du
- er/sie/es
- wir
- ihr
- sie/Sie

---

## Important grammar rule

German verbs change depending on:
👤 the person

Example:
- ich komme
- du kommst
- wir kommen

---

## Typical verb endings

| Person | Ending |
|---|---|
| ich | -e |
| du | -st |
| er/sie/es | -t |
| wir | -en |
| ihr | -t |
| sie/Sie | -en |

---

## Important irregular verbs

### sprechen

Notice:
⚠️ vowel change

- du sprichst
- er spricht

NOT:
❌ sprechst

---

### sein

This verb is completely irregular.

| Person | sein |
|---|---|
| ich | bin |
| du | bist |
| er/sie/es | ist |
| wir | sind |
| ihr | seid |
| sie/Sie | sind |

---

## Helpful strategy

Look for:
✅ verb stem  
✅ verb ending

Example:
- wohn-en → wohnst
- arbeit-en → arbeitet

---

## Helpful tip

Some verbs need:
👉 extra “e”

Example:
- arbeiten → du arbeitest

because pronunciation is easier.

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for Verben im Präsens (b)</b></summary>

In this exercise, you complete sentences with the correct verb form.

Your task:
✅ identify the subject  
✅ choose the correct verb  
✅ conjugate the verb correctly

---

## Helpful strategy

### Step 1
Find the subject:

- ich
- du
- er
- sie
- wir
- ihr
- Sie

### Step 2
Choose the correct ending.

---

## Important example

### ihr

For:
👉 ihr

Most verbs end with:
✅ -t

Examples:
- ihr kommt
- ihr studiert
- ihr heißt

---

## Important exception

### sein

For:
👉 ihr

The correct form is:
✅ seid

NOT:
❌ sind

---

## Helpful examples from the exercise

### Questions

- Seid ihr auch hier im Deutschkurs?
- Wie heißt ihr?
- Woher kommt ihr?
- Was studiert ihr?

---

### Statements

- Das sind Olivia und Noah.
- Olivia kommt aus Kanada.
- Noah studiert Chemie.

---

## Helpful vocabulary

| German | English |
|---|---|
| der Deutschkurs | German course |
| studieren | to study |
| neu | new |
| Chemie | chemistry |
| Informatik | computer science |

---

## Important tip

Pay attention to:
👥 singular or plural

Examples:
- Olivia kommt
- Olivia und Noah sind

</details>

---

## 🟨 c) Was passt: Ich oder Ich bin? Ergänzen Sie.

<div class="page-box">

<div class="task-title"></div>

<div class="two-grid">

<div class="card">

1. .[[Ich bin]] aus Deutschland.  
2. .[[Ich]] komme aus Madrid.  
3. .[[Ich]] heiße Sarah.

</div>

<div class="card">

4. .[[Ich bin]] Sarah.  
5. .[[Ich bin]] Deutschlehrer.  
6. .[[Ich]] studiere Medizin.

</div>

</div>

<div class="note">
<b>📌 Regel:</b> Satzanfang, Namen und Nomen schreibt man groß.
</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for c) Ich oder Ich bin?</b></summary>

In this grammar exercise, you practice:
👤 introductions in German.

Your task:
✅ choose:
- <b>Ich</b>
or
- <b>Ich bin</b>

✅ complete the sentences correctly

---

## Important grammar rule

### Use “Ich bin” with:

✅ names  
✅ professions  
✅ nationality / origin

Examples:
- Ich bin Sarah.
- Ich bin Deutschlehrer.
- Ich bin aus Deutschland.

---

## Use “Ich” with verbs

When another verb follows:
✅ use only “Ich”

Examples:
- Ich komme aus Madrid.
- Ich heiße Sarah.
- Ich studiere Medizin.

---

## Helpful structure

| Sentence type | Correct form |
|---|---|
| name / profession | Ich bin |
| action verb | Ich |

---

## Important examples

### With “sein”

- Ich bin Sarah.
- Ich bin Lehrer.
- Ich bin aus Deutschland.

---

### With another verb

- Ich heiße Sarah.
- Ich komme aus Madrid.
- Ich studiere Medizin.

---

## Helpful strategy

Ask yourself:

👉 Is there another verb in the sentence?

YES:
✅ use “Ich”

NO:
✅ use “Ich bin”

---

## Helpful vocabulary

| German | English |
|---|---|
| studieren | to study |
| Medizin | medicine |
| Deutschlehrer | German teacher |
| kommen aus | come from |

---

## Important writing rule

📌 In German:
✅ sentence beginnings are capitalized  
✅ names are capitalized  
✅ nouns are capitalized

Examples:
- Deutschland
- Medizin
- Deutschlehrer

</details>

---

# 🟢 Wer ist das?

<div class="page-box">

<div class="task-title">d) Schreiben Sie Sätze.</div>

<div class="two-grid">

<div class="card">

## 👨 Nelson Müller

* **Land:** Ghana  
* **Wohnort:** Essen  
* **Beruf:** Koch und Musiker  
* **Sprachen:** Deutsch, Englisch  

#### Interaktiv

Das ist [[Nelson Müller]].  
Er kommt aus [[Ghana]].  
Er wohnt in [[Essen]].  
Er ist [[Koch und Musiker]].  
Er spricht [[Deutsch und Englisch]].

</div>

<div class="card">

## 👩 Christiane Seidel

* **Land:** USA  
* **Wohnort:** Hamburg und New York  
* **Beruf:** Schauspielerin  
* **Sprachen:** Deutsch, Dänisch, Englisch  

#### Interaktiv

Das ist [[Christiane Seidel]].  
Sie kommt aus den [[USA]].  
Sie wohnt in [[Hamburg und New York]].  
Sie ist [[Schauspielerin]].  
Sie spricht [[Deutsch, Dänisch und Englisch]].

</div>

</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for „Wer ist das?“</b></summary>

In this writing exercise, you describe:
👤 a person  
🌍 their country  
🏠 where they live  
💼 their profession  
🗣️ the languages they speak

Your task:
✅ write complete German sentences  
✅ use:
- er / sie
- kommt aus
- wohnt in
- ist
- spricht

---

## Helpful sentence patterns

### Name

- Das ist Nelson Müller.
- Das ist Christiane Seidel.

---

### Country / Origin

Use:
👉 kommen aus

Examples:
- Er kommt aus Ghana.
- Sie kommt aus den USA.

---

## Important grammar

Some countries need articles.

Example:
- die USA → aus den USA

NOT:
❌ aus USA

---

### Place of residence

Use:
👉 wohnen in

Examples:
- Er wohnt in Essen.
- Sie wohnt in Hamburg und New York.

---

### Profession

Use:
👉 sein

Examples:
- Er ist Koch und Musiker.
- Sie ist Schauspielerin.

---

### Languages

Use:
👉 sprechen

Examples:
- Er spricht Deutsch und Englisch.
- Sie spricht Deutsch, Dänisch und Englisch.

---

## Helpful vocabulary

| German | English |
|---|---|
| der Koch | cook |
| der Musiker | musician |
| die Schauspielerin | actress |
| sprechen | to speak |
| wohnen | to live |
| kommen aus | to come from |

---

## Helpful strategy

Write the information step by step:

1️⃣ Name  
2️⃣ Country  
3️⃣ City  
4️⃣ Profession  
5️⃣ Languages

---

## Important tip

Remember:
✅ nouns and languages begin with capital letters in German.

Examples:
- Deutsch
- Englisch
- Musiker
- Schauspielerin

</details>

---

# Wie geht es dir? Wie geht es Ihnen?

<div style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:2px solid #d9dfc6;border-radius:18px;padding:22px;margin:16px 0;box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="display:flex;align-items:center;gap:14px;font-size:28px;font-weight:800;color:#2f3b1f;">
<span style="width:44px;height:44px;border-radius:50%;background:#9fb522;color:white;display:inline-flex;align-items:center;justify-content:center;font-size:24px;font-weight:800;">1</span>
<span>Wie geht es dir? Wie geht es Ihnen?</span>
</div>

</div>

---

 ## a) Hören und lesen Sie die Gespräche

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">
~~__KB:11,12__~~
?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_011.mp3?raw=true)

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_012.mp3?raw=true)  
Hören und lesen Sie die Gespräche. Welches ist formell, welches informell?

<div style="display:grid;grid-template-columns:1fr 1fr;gap:22px;margin-top:18px;">

<div style="background:#f7fbff;border:2px solid #d6e8f7;border-radius:16px;padding:18px;">

### Gespräch 1

* ● Hallo Sarah. Wie geht es dir?  
* ○ Hallo Niklas. Mir geht es super. Und dir?  
* ● Mir geht es auch sehr gut, danke.  
* ○ Das ist Dana.  
* ● Hallo Dana. Woher kommst du?  
* ○ Ich komme aus Almaty.  
* ● Studierst du auch Biologie?  
* ○ Nein, ich studiere Chemie.  
* ● Kommt ihr morgen zur Party?  
* ○ Ja, wir kommen natürlich.  
* ● Super. Bis morgen. Tschüss.  
* ○ Tschüss!

</div>

<div style="background:#fffaf0;border:2px solid #ead8b8;border-radius:16px;padding:18px;">

### Gespräch 2

* ● Guten Morgen, Frau Klein. Wie geht es Ihnen?  
* ■ Mir geht es gut, vielen Dank. Und Ihnen?  
* ● Danke, mir geht es auch gut.  
* ■ Kommen Sie morgen Abend zum Kurs?  
* ● Ja, ich komme natürlich.  
* ■ Sehr schön. Auf Wiedersehen.  
* ● Bis morgen. Auf Wiedersehen.

</div>

</div>
</div>

---

 ## Interaktive Aufgabe: formell oder informell?

<div style="background:linear-gradient(135deg,#eef8e8,#ffffff);border:2px solid #cdddb2;border-radius:16px;padding:20px;margin:16px 0;">

1. Gespräch 1 ist [[informell]].  
2. Gespräch 2 ist [[formell]].

**Merken Sie:**  
Gespräch 1 benutzt **du / dir / ihr**.  
Gespräch 2 benutzt **Sie / Ihnen** und **Frau Klein**.

</div>

---

 ## b) Hören und sprechen Sie mit

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

**KB 11–12 🔊**  
Hören und lesen Sie die Gespräche in 1a noch einmal und sprechen Sie mit.

### Informell

**A:** Hallo Sarah. Wie geht es dir?  
**B:** Hallo Niklas. Mir geht es super. Und dir?  
**A:** Mir geht es auch sehr gut, danke.

### Formell

**A:** Guten Morgen, Frau Klein. Wie geht es Ihnen?  
**B:** Mir geht es gut, vielen Dank. Und Ihnen?  
**A:** Danke, mir geht es auch gut.

</div>

---

 ## c) Aussprache: Satzmelodie

<div style="background:#ffffff;border-left:8px solid #8ab6d6;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">
~~__KB:13__~~
?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_013.mp3?raw=true) 
Wie hören Sie die Sätze? Kreuzen Sie an.

<div style="background:#eef5f2;border:2px solid #c5d6d3;border-radius:14px;padding:16px;margin:14px 0;">

**↗** = Melodie steigt  
**↘** = Melodie fällt

</div>

1. Wie geht es dir?  
[[ ]] a. ↘  
[[x]] b. ↗  

2. Danke. Mir geht es gut.  
[[ ]] a. ↘  
[[x]] b. ↗  

3. Studierst du auch Biologie?  
[[x]] a. ↘  
[[ ]] b. ↗  

4. Nein, ich studiere Chemie.  
[[ ]] a. ↘  
[[x]] b. ↗  

</div>

---

 ## d) Ergänzen Sie die Regeln

<div style="background:linear-gradient(135deg,#eef8e8,#ffffff);border:2px solid #cdddb2;border-radius:16px;padding:20px;margin:16px 0;">

**KB 13 🔊**  
Hören Sie die Sätze in 1c noch einmal und ergänzen Sie die Regeln. Sprechen Sie die Sätze nach.

| Satztyp | Satzmelodie |
|---|---|
| Antwort / Aussage | [[↘]] |
| W-Frage | [[↘]] |
| Ja/Nein-Frage | [[↗]] |

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1a – Hören und lesen Sie die Gespräche</b></summary>

In this exercise, you practice:
🎧 listening  
🗣️ greetings and introductions  
👥 formal and informal communication

Your task:
✅ listen carefully  
✅ read the dialogues  
✅ identify:
- formal conversation
or
- informal conversation

---

## Important difference

### Informal conversation

Used with:
👫 friends  
👩‍🎓 classmates  
👨‍👩‍👧 family

Important words:
- du
- dir
- ihr

Examples:
- Wie geht es dir?
- Woher kommst du?
- Kommt ihr morgen?

---

### Formal conversation

Used with:
👩‍🏫 teachers  
👨 strangers  
🏢 official situations

Important words:
- Sie
- Ihnen
- Frau + Familienname

Examples:
- Wie geht es Ihnen?
- Kommen Sie morgen?
- Frau Klein

---

## Helpful listening strategy

Listen for:
👂 pronouns
- du
or
- Sie

This immediately shows:
✅ informal
or
✅ formal

---

## Helpful vocabulary

| German | English |
|---|---|
| Wie geht es dir? | How are you? informal |
| Wie geht es Ihnen? | How are you? formal |
| die Party | party |
| der Kurs | course |
| studieren | to study |

---

## Important tip

German changes:
✅ pronouns  
✅ verb forms  
✅ greetings

depending on the situation.

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for formell oder informell?</b></summary>

In this exercise, you decide:
👥 formal
or
👫 informal

Your task:
✅ identify the language style  
✅ complete the sentences correctly

---

## Informell

Conversation 1 uses:
- du
- dir
- ihr

Examples:
- Wie geht es dir?
- Woher kommst du?
- Kommt ihr morgen?

This is:
✅ informal language

---

## Formell

Conversation 2 uses:
- Sie
- Ihnen
- Frau Klein

Examples:
- Wie geht es Ihnen?
- Kommen Sie morgen?

This is:
✅ formal language

---

## Helpful rule

| Situation | Pronoun |
|---|---|
| friends / students | du |
| teacher / stranger | Sie |

---

## Helpful tip

If you see:
👩‍🏫 Frau / Herr + family name

it is usually:
✅ formal

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1b – Hören und sprechen Sie mit</b></summary>

In this speaking exercise, you practice:
🗣️ pronunciation  
🎧 listening  
💬 short conversations

Your task:
✅ listen carefully  
✅ repeat the sentences  
✅ copy the rhythm and pronunciation

---

## Helpful speaking strategy

Focus on:
✅ pronunciation  
✅ sentence melody  
✅ stress  
✅ polite expressions

---

## Important expressions

### Informal

- Hallo Sarah.
- Wie geht es dir?
- Mir geht es super.

---

### Formal

- Guten Morgen, Frau Klein.
- Wie geht es Ihnen?
- Vielen Dank.

---

## Helpful pronunciation tip

German greetings are often spoken:
😊 clearly and politely.

Examples:
🗣️ Guten Morgen  
🗣️ Vielen Dank  
🗣️ Auf Wiedersehen

---

## Practice tip

Repeat slowly first:
1️⃣ read  
2️⃣ listen  
3️⃣ repeat aloud

This improves:
✅ fluency  
✅ confidence  
✅ pronunciation

</details>

---

<details style="background:#eef3ff;border:1px solid #cfdcff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1c – Aussprache: Satzmelodie</b></summary>

In this pronunciation exercise, you learn:
🎵 German sentence melody (intonation).

Your task:
✅ listen carefully  
✅ decide:
- rising melody ↗
or
- falling melody ↘

---

## Important rule

### W-questions

Usually:
↘ falling melody

Examples:
- Woher kommst du?
- Wie geht es dir?

---

### Yes/No questions

Usually:
↗ rising melody

Examples:
- Studierst du auch Biologie?
- Kommen Sie morgen?

---

### Statements / answers

Usually:
↘ falling melody

Examples:
- Mir geht es gut.
- Ich studiere Chemie.

---

## Helpful listening strategy

Listen to:
🎧 the END of the sentence.

Does the voice:
⬆️ go up?
or
⬇️ go down?

---

## Helpful overview

| Sentence type | Melody |
|---|---|
| Aussage | ↘ |
| W-Frage | ↘ |
| Ja/Nein-Frage | ↗ |

---

## Practice tip

Say the sentences aloud:

🗣️ Wie geht es dir? ↘  
🗣️ Studierst du Biologie? ↗

This helps your pronunciation sound more natural.

</details>

---

<details style="background:#f5f8e8;border:1px solid #d8e3b0;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1d – Ergänzen Sie die Regeln</b></summary>

In this grammar and pronunciation exercise, you summarize:
🎵 German sentence melody rules.

Your task:
✅ choose the correct melody  
✅ complete the table

---

## Important pronunciation rules

### Aussage / Antwort

Normal statements:
✅ falling melody ↘

Examples:
- Ich studiere Chemie.
- Mir geht es gut.

---

### W-Fragen

Questions with:
- Wie
- Woher
- Was

usually:
✅ falling melody ↘

Examples:
- Wie geht es dir?
- Woher kommst du?

---

### Ja/Nein-Fragen

Questions answered with:
- ja
or
- nein

usually:
✅ rising melody ↗

Examples:
- Studierst du Biologie?
- Kommen Sie morgen?

---

## Helpful strategy

Ask yourself:
👉 Can I answer with ja/nein?

YES:
✅ ↗ rising melody

NO:
✅ ↘ falling melody

</details>

---

# Grammatik kompakt: W-Fragen, Ja/Nein-Fragen, Antworten / Aussagesätze

<div style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:2px solid #d9dfc6;border-radius:18px;padding:22px;margin:16px 0;box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="display:flex;align-items:center;gap:14px;font-size:26px;font-weight:800;color:#2f3b1f;">
<span style="width:44px;height:44px;border-radius:50%;background:#9fb522;color:white;display:inline-flex;align-items:center;justify-content:center;font-size:24px;font-weight:800;">2</span>
<span>[ GRAMMATIK KOMPAKT ] W-Fragen, Ja/Nein-Fragen, Antworten / Aussagesätze</span>
</div>

</div>

---

 ## 2a) Ergänzen Sie die Tabelle

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

Ergänzen Sie die Tabelle mit den Informationen aus 1a.

### Fragen

| Position 1 | Position 2 | Ergänzung |
|---|---|---|
| Woher | [[kommt]] | Dana? |
| Was | [[studiert]] | Dana? |
| [[Studierst]] | du | auch Biologie? |
| [[Kommt]] | ihr | morgen zur Party? |

### Antworten

| Position 1 | Position 2 | Ergänzung |
|---|---|---|
| Dana | [[kommt]] | aus Almaty. |
| Sie | [[studiert]] | Chemie. |
| Nein, ich | [[studiere]] | Chemie. |
| Ja, wir | [[kommen]] | zur Party. |

</div>

---

 ## 2b) Ergänzen Sie die Regel

<div style="background:linear-gradient(135deg,#eef8e8,#ffffff);border:2px solid #cdddb2;border-radius:16px;padding:20px;margin:16px 0;">

1. Ja/Nein-Fragen: konjugiertes Verb auf Position [[1]].  
2. W-Fragen und Antworten / Aussagesätze: konjugiertes Verb auf Position [[2]].  
3. Frage: Am Ende steht ein Fragezeichen [[??]].  
4. Aussagesatz: Am Ende steht ein Punkt [[.]].

</div>

---

 ## Grammatik-Hilfe

<div style="background:#ffffff;border-left:8px solid #8ab6d6;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

### W-Frage

| Position 1 | Position 2 | Ende |
|---|---|---|
| Woher | kommst | du? |
| Was | studierst | du? |
| Wie | geht | es dir? |

**Regel:** W-Frage + Verb + Person / Ergänzung

---

### Ja/Nein-Frage

| Position 1 | Position 2 | Ende |
|---|---|---|
| Studierst | du | Biologie? |
| Kommst | du | morgen? |
| Kommt | ihr | zur Party? |

**Regel:** Verb + Person + Ergänzung

---

### Aussagesatz

| Position 1 | Position 2 | Ende |
|---|---|---|
| Ich | studiere | Chemie. |
| Dana | kommt | aus Almaty. |
| Wir | kommen | zur Party. |

**Regel:** Subjekt + Verb + Ergänzung

</div>

---

 ## 2c) Schreiben Sie die Sätze

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

Schreiben Sie die Sätze in Ihr Heft.

1. aus Deutschland · Frau Klein · kommt · .  
2. aus Deutschland · Frau Klein · kommt · ?  
3. du · Französisch · sprichst · ?  
4. studiere · Chemie · ich · in Marburg · .  
5. Dana · morgen · zur Party · kommt · ?  
6. wohnt · Sarah · in Marburg · .

### Interaktive Lösung

1. Frau Klein kommt aus Deutschland. 
2. [[Kommt Frau Klein aus Deutschland?]]  
3. [[Sprichst du Französisch?]]  
4. [[Ich studiere Chemie in Marburg.]]  
5. [[Kommt Dana morgen zur Party?]]  
6. [[Sarah wohnt in Marburg.]]

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2a – Ergänzen Sie die Tabelle</b></summary>

In this grammar exercise, you learn:
❓ W-questions  
❓ Yes/No questions  
💬 answers and statements

Your task:
✅ complete the tables  
✅ identify the verb position  
✅ compare question types

---

## Important grammar rule

### W-Questions

W-questions begin with:
- Woher
- Was
- Wie

The verb is in:
✅ Position 2

Examples:
- Woher kommt Dana?
- Was studiert Dana?

---

## Yes/No Questions

These questions begin directly with the verb.

The verb is in:
✅ Position 1

Examples:
- Studierst du Biologie?
- Kommt ihr morgen?

---

## Statements / Answers

Statements usually begin with:
👤 subject

The verb is in:
✅ Position 2

Examples:
- Dana kommt aus Almaty.
- Wir kommen zur Party.

---

## Helpful overview

| Sentence type | Verb position |
|---|---|
| W-Frage | Position 2 |
| Ja/Nein-Frage | Position 1 |
| Aussage | Position 2 |

---

## Helpful strategy

Look at the FIRST word:

### Starts with:
- Woher
- Was
- Wie

➡️ W-question

---

### Starts with a verb:
- Studierst
- Kommst
- Kommt

➡️ Yes/No question

---

### Starts with a subject:
- Dana
- Ich
- Wir

➡️ Statement / answer

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2b – Ergänzen Sie die Regel</b></summary>

In this exercise, you summarize:
📌 important German sentence rules.

Your task:
✅ complete the grammar rules  
✅ identify:
- verb position
- punctuation

---

## Important grammar rules

### Ja/Nein-Fragen

The conjugated verb is in:
✅ Position 1

Examples:
- Kommst du morgen?
- Studierst du Chemie?

---

### W-Fragen

The conjugated verb is in:
✅ Position 2

Examples:
- Woher kommst du?
- Was studierst du?

---

### Aussagen / Antworten

The conjugated verb is also in:
✅ Position 2

Examples:
- Ich studiere Chemie.
- Dana kommt aus Almaty.

---

## Important punctuation

### Question

At the end:
✅ ?

Examples:
- Wie heißt du?
- Kommst du morgen?

---

### Statement

At the end:
✅ .

Examples:
- Ich studiere Chemie.
- Sarah wohnt in Marburg.

---

## Helpful tip

Always check:
1️⃣ sentence beginning  
2️⃣ verb position  
3️⃣ punctuation at the end

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for Grammatik-Hilfe</b></summary>

This section gives you:
📚 grammar structure examples.

Use it as a model for:
✅ writing questions  
✅ writing statements  
✅ checking verb position

---

## W-Frage structure

Pattern:
✅ W-word + verb + person

Examples:
- Woher kommst du?
- Was studierst du?
- Wie geht es dir?

---

## Ja/Nein-Frage structure

Pattern:
✅ Verb + person + information

Examples:
- Studierst du Biologie?
- Kommst du morgen?
- Kommt ihr zur Party?

---

## Aussagesatz structure

Pattern:
✅ Subject + verb + information

Examples:
- Ich studiere Chemie.
- Dana kommt aus Almaty.
- Wir kommen zur Party.

---

## Helpful strategy

Ask yourself:

### Is there a W-word?
➡️ W-question

### Does the sentence start with a verb?
➡️ Yes/No question

### Does the sentence start with a subject?
➡️ Statement

---

## Important tip

In German:
✅ the conjugated verb is very important.

Always check:
👀 where the verb stands in the sentence.

</details>

---

<details style="background:#eef3ff;border:1px solid #cfdcff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2c – Schreiben Sie die Sätze</b></summary>

In this writing exercise, you build:
✍️ correct German sentences.

Your task:
✅ put the words in the correct order  
✅ choose:
- statement
or
- question

✅ use correct punctuation

---

## Helpful strategy

### Step 1

Check:
❓ Is it a question?
or
💬 a statement?

---

## Statement structure

Pattern:
✅ Subject + verb + information

Example:
- Frau Klein kommt aus Deutschland.
- Sarah wohnt in Marburg.

---

## Question structure

Pattern:
✅ Verb + subject + information

Examples:
- Kommt Frau Klein aus Deutschland?
- Sprichst du Französisch?

---

## Helpful examples

### Statement

❌ aus Deutschland Frau Klein kommt

✅ Frau Klein kommt aus Deutschland.

---

### Question

❌ du Französisch sprichst

✅ Sprichst du Französisch?

---

## Important punctuation

### Question
➡️ use:
✅ ?

### Statement
➡️ use:
✅ .

---

## Helpful tip

Always look for:
👀 the verb

In German:
✅ the verb usually comes very early in the sentence.

</details>

---

# Telefonnummern

<div style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:2px solid #d9dfc6;border-radius:18px;padding:22px;margin:16px 0;box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="display:flex;align-items:center;gap:14px;font-size:28px;font-weight:800;color:#2f3b1f;">
<span style="width:44px;height:44px;border-radius:50%;background:#9fb522;color:white;display:inline-flex;align-items:center;justify-content:center;font-size:24px;font-weight:800;">3</span>
<span>Telefonnummern</span>
</div>

</div>

---

## 3a) Zahlen von 1 bis 10

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

**a) Sagen Sie die Zahlen von 1 bis 10.**

| Zahl | Deutsch |
|---|---|
| 1 | eins |
| 2 | zwei |
| 3 | drei |
| 4 | vier |
| 5 | fünf |
| 6 | sechs |
| 7 | sieben |
| 8 | acht |
| 9 | neun |
| 10 | zehn |

</div>

---



## 3b) Welche Vorwahl hören Sie?

<div style="background:#ffffff;border-left:8px solid #8ab6d6;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_014.mp3?raw=true) 
Welche Vorwahl hören Sie: a, b oder c? Kreuzen Sie an.

<div style="display:grid;grid-template-columns:repeat(4,1fr);gap:18px;margin-top:16px;">

<div style="background:#f7fbff;border:2px solid #d6e8f7;border-radius:14px;padding:16px;">
<b>1.</b><br><br>
- [[ ]] a. 080  
- [[x]] b. 089  
- [[ ]] c. 098   
</div>

<div style="background:#f7fbff;border:2px solid #d6e8f7;border-radius:14px;padding:16px;">
<b>2.</b><br><br>
- [[x]] a. 040  
- [[ ]] b. 042  
- [[ ]] c. 043  
</div>

<div style="background:#f7fbff;border:2px solid #d6e8f7;border-radius:14px;padding:16px;">
<b>3.</b><br><br>
- [[ ]] a. 0210  
- [[X]] b. 0221  
- [[ ]] c. 0232  
</div>

<div style="background:#f7fbff;border:2px solid #d6e8f7;border-radius:14px;padding:16px;">
<b>4.</b><br><br>
- [[ ]] a. 07071  
- [[ ]] b. 07093  
- [[x]] c. 07972  
</div>

</div>

<div style="background:#fffaf0;border:2px solid #ead8b8;border-radius:14px;padding:16px;margin-top:18px;">

**Merken Sie:**  
Jede Stadt hat eine Vorwahlnummer.

Beispiele:  
München: **089**  
Berlin: **030**

Auch jede Handynummer hat eine Vorwahl, z. B. **0176**, **0157**, **0171**.

</div>

</div>

---

 ## 3c) Telefonnummer und E-Mail-Adresse notieren

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_015.mp3?raw=true)  
Hören Sie das Gespräch. Notieren Sie die Telefonnummern und die E-Mail-Adresse.

1. Telefonnummer: [[3446203]]  
2. Handynummer: [[01692831572]]  
3. E-Mail-Adresse: [[niklas.ab88@xpu.de]]

<div style="background:#eef5f2;border:2px solid #c5d6d3;border-radius:14px;padding:16px;margin-top:18px;">

### Zeichen bei E-Mail-Adressen

| Zeichen | Deutsch |
|---|---|
| @ | at |
| - | minus |
| . | Punkt |
| _ | Unterstrich |

</div>

</div>

---

 ## 3d) Partnerarbeit: Fragen und notieren

<div style="background:#ffffff;border-left:8px solid #8ab6d6;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

**d) Arbeiten Sie zu zweit. Fragen Sie und notieren Sie die Telefonnummer und die E-Mail-Adresse. Schreiben Sie in Ihr Heft.**

<div style="display:grid;grid-template-columns:1fr 1fr;gap:22px;margin-top:16px;">

<div style="background:#f7fbff;border:2px solid #d6e8f7;border-radius:16px;padding:18px;">
<div style="border:2px solid #9ea9a9;border-radius:8px;padding:12px 18px;background:white;margin-bottom:12px;font-weight:600;">
Wie ist deine Handynummer?
</div>
<div style="border:2px solid #9ea9a9;border-radius:8px;padding:12px 18px;background:#eef8e8;font-weight:600;">
Meine Handynummer ist 0157–765 43 21.
</div>
</div>

<div style="background:#f7fbff;border:2px solid #d6e8f7;border-radius:16px;padding:18px;">
<div style="border:2px solid #9ea9a9;border-radius:8px;padding:12px 18px;background:white;margin-bottom:12px;font-weight:600;">
Wie ist deine E-Mail-Adresse?
</div>
<div style="border:2px solid #9ea9a9;border-radius:8px;padding:12px 18px;background:#eef8e8;font-weight:600;">
Meine E-Mail-Adresse ist …
</div>
</div>

</div>

</div>


<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3b – Welche Vorwahl hören Sie?</b></summary>

In this listening exercise, you practice:
📞 German area codes (Vorwahl).

Your task:
✅ listen carefully  
✅ identify the correct number  
✅ choose:
- a
- b
- c

---

## Important vocabulary

| German | English |
|---|---|
| die Vorwahl | area code |
| die Telefonnummer | telephone number |
| die Handynummer | mobile number |

---

## Helpful listening strategy

Focus on:
👂 every single number

German phone numbers are often spoken:
🔢 digit by digit

Example:
- null acht neun
→ 089

---

## Important examples

| City | Area code |
|---|---|
| Berlin | 030 |
| München | 089 |

---

## Mobile prefixes in Germany

Common mobile prefixes:
- 0176
- 0157
- 0171

---

## Helpful tip

Listen carefully to:
✅ null (0)
✅ neun (9)
✅ zwei (2)

Some numbers sound similar.

---

## Practice tip

Repeat the numbers aloud:

🗣️ null acht neun  
🗣️ null vier null  
🗣️ null zwei zwei eins

This improves:
✅ listening  
✅ pronunciation  
✅ number recognition

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3c – Telefonnummer und E-Mail-Adresse notieren</b></summary>

In this exercise, you practice:
📞 phone numbers  
📧 e-mail addresses

Your task:
✅ listen carefully  
✅ write the correct numbers  
✅ write the correct e-mail address

---

## Helpful listening strategy

### Phone numbers

Write:
✏️ one number at a time

Listen for:
- repeated numbers
- zero (null)
- long number groups

---

## E-mail addresses

Listen carefully to:
✅ letters  
✅ symbols  
✅ spelling

---

## Important symbols

| Symbol | German |
|---|---|
| @ | at |
| . | Punkt |
| - | minus |
| _ | Unterstrich |

---

## Helpful example

🗣️ niklas punkt ab acht acht at xpu punkt de

→ niklas.ab88@xpu.de

---

## Important tip

German speakers often:
🔤 spell names letter by letter.

Listen carefully for:
- capitals
- repeated letters
- numbers in usernames

---

## Practice tip

Say the e-mail address aloud slowly:

🗣️ niklas punkt ab acht acht at xpu punkt de

This improves:
✅ listening  
✅ spelling  
✅ pronunciation

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3d – Partnerarbeit</b></summary>

In this speaking exercise, you practice:
🗣️ asking for contact information.

Your task:
✅ ask questions  
✅ answer politely  
✅ note phone numbers and e-mail addresses

---

## Important questions

### Mobile number

🗣️ Wie ist deine Handynummer?

Answer:
🗣️ Meine Handynummer ist …

---

### E-mail address

🗣️ Wie ist deine E-Mail-Adresse?

Answer:
🗣️ Meine E-Mail-Adresse ist …

---

## Helpful speaking strategy

Speak:
✅ slowly  
✅ clearly  
✅ number by number

---

## Helpful pronunciation

### Example number

0157–765 43 21

can be spoken:
🗣️ null eins fünf sieben …

---

## Helpful tip

When listening:
✏️ write immediately

This helps avoid mistakes with:
- long numbers
- letters
- symbols

---

## Practice tip

Work with a partner:
👥 ask and answer several times.

This improves:
✅ fluency  
✅ listening  
✅ pronunciation  
✅ confidence

</details>



# Hundert – tausend – hunderttausend

<div style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:2px solid #d9dfc6;border-radius:18px;padding:22px;margin:16px 0;box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="display:flex;align-items:center;gap:14px;font-size:28px;font-weight:800;color:#2f3b1f;">
<span style="width:44px;height:44px;border-radius:50%;background:#9fb522;color:white;display:inline-flex;align-items:center;justify-content:center;font-size:24px;font-weight:800;">4</span>
<span>Hundert – tausend – hunderttausend</span>
</div>

</div>

---

 ## 4a) Hören Sie die Zahlen und sprechen Sie nach

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:16px;padding:20px;margin:16px 0;box-shadow:0 4px 14px rgba(0,0,0,.08);">

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_016.mp3?raw=true)
Hören Sie die Zahlen und sprechen Sie nach.

<div style="display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:16px;">

<div style="background:#eef5f2;border:2px solid #c5d6d3;border-radius:14px;padding:16px;">

| Zahl | Deutsch |
|---|---|
| 11 | elf |
| 12 | zwölf |
| 13 | dreizehn |
| 14 | vierzehn |
| 15 | fünfzehn |
| 16 | sechzehn |
| 17 | siebzehn |
| 18 | achtzehn |
| 19 | neunzehn |

</div>

<div style="background:#eef5f2;border:2px solid #c5d6d3;border-radius:14px;padding:16px;">

| Zahl | Deutsch |
|---|---|
| 20 | zwanzig |
| 21 | einundzwanzig |
| 30 | dreißig |
| 40 | vierzig |
| 50 | fünfzig |
| 60 | sechzig |
| 70 | siebzig |
| 80 | achtzig |
| 90 | neunzig |

</div>

<div style="background:#eef5f2;border:2px solid #c5d6d3;border-radius:14px;padding:16px;">

| Zahl | Deutsch |
|---|---|
| 100 | einhundert |
| 101 | einhunderteins |
| 199 | einhundertneunundneunzig |
| 200 | zweihundert |
| 1000 | eintausend |
| 10 000 | zehntausend |
| 100 000 | einhunderttausend |
| 1 000 000 | eine Million |
| 1 000 000 000 | eine Milliarde |

</div>

</div>

<div style="background:#fffaf0;border:2px solid #ead8b8;border-radius:14px;padding:16px;margin-top:18px;">

**Achtung:**  
13 = dreizehn  
21 = einundzwanzig

</div>

</div>

---


# Sich begrüßen und sich vorstellen

<div style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:2px solid #d9dfc6;border-radius:18px;padding:22px;margin:16px 0;box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="font-size:28px;font-weight:800;color:#2f3b1f;margin-bottom:18px;">
💬 Sich begrüßen und sich vorstellen
</div>

| Thema | Fragen / Redemittel | Antworten / Redemittel |
|---|---|---|
| **Begrüßung** | Hallo! / Guten Morgen! / Guten Tag! / Guten Abend! | Hallo! / Guten Morgen! / Guten Tag! / Guten Abend! |
| **Nach Befinden fragen** | Wie geht es dir / Ihnen? | Danke. Mir geht es gut / sehr gut. |
| **Name** | Wie heißt du? / Wie heißen Sie?<br>Wie ist dein / Ihr Vorname?<br>Wie ist dein / Ihr Familienname?<br>Wie schreibt man das?<br>Buchstabieren Sie das bitte. | Ich heiße / Ich bin / Mein Name ist Dana / Dana Pak.<br>Mein Vorname ist Dana.<br>Mein Familienname ist Pak.<br>P – A – K.<br>P – A – K. |
| **Herkunft<br>(Land, Stadt)** | Woher kommst du / kommen Sie? | Ich komme aus Kasachstan, aus Almaty. |
| **Sprachen** | Welche Sprache(n) sprichst du / sprechen Sie? | Ich spreche Kasachisch und Deutsch. |
| **Studium** | Was studierst du / studieren Sie? | Ich studiere Medizin / Architektur / …<br>Ich arbeite schon, ich bin Architekt / … |
| **Beruf** | Was bist du / sind Sie von Beruf? | Ich bin Architekt / Lehrerin / … |
| **Wohnort** | Wo wohnst du / wohnen Sie? | Ich wohne in Marburg. |
| **Telefonnummer** | Wie ist deine / Ihre Telefonnummer?<br>Wie ist deine / Ihre Handynummer? | Meine Telefonnummer ist 06420–390809.<br>Meine Handynummer ist 0169–2831572. |
| **E-Mail-Adresse** | Wie ist deine / Ihre E-Mail-Adresse? | Meine E-Mail-Adresse ist d.pak@kursdaf.de. |
| **Verabschiedung** | Auf Wiedersehen. / Tschüss. | Auf Wiedersehen. / Tschüss. |

</div>



---

 ## Verben im Präsens und Personalpronomen im Nominativ

<div style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:2px solid #d9dfc6;border-radius:18px;padding:22px;margin:16px 0;box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="font-size:26px;font-weight:800;color:#2f3b1f;margin-bottom:12px;">
📘 Verben im Präsens und Personalpronomen im Nominativ
</div>

| Personalpronomen | kommen | wohnen | studieren | arbeiten | heißen | sprechen | sein |
|---|---|---|---|---|---|---|---|
| ich | komme | wohne | studiere | arbeite | heiße | spreche | **bin** |
| du | kommst | wohnst | studierst | arbeitest | heißt | sprichst | **bist** |
| er / sie / es | kommt | wohnt | studiert | arbeitet | heißt | spricht | **ist** |
| wir | kommen | wohnen | studieren | arbeiten | heißen | sprechen | **sind** |
| ihr | kommt | wohnt | studiert | arbeitet | heißt | sprecht | **seid** |
| sie / Sie | kommen | wohnen | studieren | arbeiten | heißen | sprechen | **sind** |

</div>

---

 ## Wortstellung in W-Fragen, Ja/Nein-Fragen und Antworten / Aussagesätzen

<div style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:2px solid #d9dfc6;border-radius:18px;padding:22px;margin:16px 0;box-shadow:0 6px 18px rgba(0,0,0,.08);">

<div style="font-size:26px;font-weight:800;color:#2f3b1f;margin-bottom:12px;">
🧩 Wortstellung
</div>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:22px;">

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:14px;padding:16px;">

### W-Fragen

| Position 1 | Position 2 | Ende |
|---|---|---|
| Woher | kommen | Sie? |
| Wie | heißen | Sie? |

</div>

<div style="background:#ffffff;border-left:8px solid #8ab6d6;border-radius:14px;padding:16px;">

### Antworten / Aussagesätze

| Position 1 | Position 2 | Ende |
|---|---|---|
| Ich | komme | aus Kasachstan. |
| Ich | heiße | Dana Pak. |

</div>

<div style="background:#ffffff;border-left:8px solid #9fb522;border-radius:14px;padding:16px;">

### Ja/Nein-Fragen

| Position 1 | Position 2 | Ende |
|---|---|---|
| Studierst | du | auch Biologie? |
| Kommen | Sie | morgen zum Kurs? |

</div>

<div style="background:#ffffff;border-left:8px solid #8ab6d6;border-radius:14px;padding:16px;">

### Antworten / Aussagesätze

| Position 1 | Position 2 | Ende |
|---|---|---|
| Nein, ich | studiere | Chemie. |
| Ja, ich | komme | natürlich. |

</div>

</div>

</div>

---

# ✅ Lösungen – Kapitel 1

---

# Hallo Deutschland!

## Das Alphabet

 ## Lösung
1. A a – Apfel  
2. B b – Ball  
3. C c – Computer  
4. D d – Dorf  
5. E e – Elefant  
6. F f – Fisch  
7. G g – Garten  
8. H h – Haus  
9. I i – Igel  
10. J j – Jagd  
11. K k – Kuchen  
12. L l – Lampe  
13. M m – Mond  
14. N n – Nase  
15. O o – Ostern  
16. P p – Pferd  
17. Q q – Qualle  
18. R r – Rose  
19. S s – Sonne  
20. T t – Tisch  
21. U u – Uhr  
22. V v – Vogel  
23. W w – Wasser  
24. X x – Xylophon  
25. Y y – Yoga  
26. Z z – Zebra  
27. Ä ä – Äpfel  
28. Ö ö – Öl  
29. Ü ü – Übung  
30. ẞ ß – Straße

---

 ## Zahlen 1–10

* 1 = eins  
* 2 = zwei  
* 3 = drei  
* 4 = vier  
* 5 = fünf  
* 6 = sechs  
* 7 = sieben  
* 8 = acht  
* 9 = neun  
* 10 = zehn

---

# Hören Sie und schreiben Sie die Namen

1. Nelson Müller  
2. Christen Seidel

---

 ## Telefonnummern

1. Arek → 5603941  
2. Linus → 2780148  
3. Ella → 3074928

---

# 1 Hallo und guten Tag!

 ## 1a)

1. Foto A → Gespräch 2  
2. Foto B → Gespräch 1

---

 ## 1b)

* Familienname: Girard
 
* Buchstabieren:
* G – I – R – A – R – D
 
* Woher kommen Sie, Frau Girard?  
* → aus Nancy

* Dana Pak:
* Vorname → Dana  
* Familienname → Pak

---

 ## 1c)

1. Wie heiß[t] [du]?  
2. Wie heiß[en] [Sie]?

---

 ## 1d)

1. Informelle Anrede → du  
2. Formelle Anrede → Sie

---

# 2 Grammatik kompakt – W-Fragen und Antworten

 ## 2a)

 ## W-Fragen

1. Wie heißen Sie?  
2. Woher kommen Sie?

 ## Antworten

1. Ich heiße Sarah.  
2. Ich komme aus Kasachstan.  
3. Mein Familienname ist Girard.

---

 ## 2b)

* 1 → b  
* 2 → c  
* 3 → e  
* 4 → f  
* 5 → d  
* 6 → a

---

# 3 Woher kommen die Nobelpreisträger?

 ## 3a)

1. Kofi Annan → aus Ghana  
2. Shirin Ebadi → aus dem Iran  
3. Elfriede Jelinek → aus Österreich  
4. Orhan Pamuk → aus der Türkei  
5. Peter Grünberg → aus Deutschland  
6. Makoto Kobayashi → aus Japan  
7. Elinor Ostrom → aus den USA  
8. Mario Vargas Llosa → aus Peru  
9. Tu Youyou → aus China  
10. Ben Feringa → aus den Niederlanden  
11. Richard Henderson → aus Großbritannien  
12. Donna Strickland → aus Kanada  
13. Michel Mayor → aus der Schweiz  
14. Abdulrazak Gurnah → aus Tansania

---

 ## 3b)

* aus der Türkei  
* aus den Niederlanden  
* aus den USA  
* aus dem Iran

---

# Wer spricht …? Wer studiert …?

 ## 1a)

 ## Wer spricht Englisch?
* ✔ Eivor + Fynn  
* ✔ Gabriel

 ## Wer spricht Französisch?
✔ Nicole

 ## Wer studiert?
* ✔ Nicole  
* ✔ Eivor + Fynn

 ## Wer arbeitet schon?
✔ Gabriel

 ## Wer lernt Deutsch?
* ✔ Nicole  
* ✔ Gabriel

 ## Wer wohnt in Berlin?
✔ Gabriel

---

 ## 1b)

| Information | Nicole | Eivor und Fynn | Gabriel |
|---|---|---|---|
| Land | Kamerun | Schweden | Kolumbien |
| Wohnort | Leipzig | Potsdam | Berlin |
| Studienfach | Informatik | Medizin | - |
| Beruf | - | - | Architekt |
| Sprachen | Französisch, Deutsch, Englisch | Schwedisch, Dänisch, Englisch, Deutsch | Spanisch, Portugiesisch, Englisch, Deutsch |

---

# Verben im Präsens

 ## a)

| Person | heißen | kommen | wohnen | studieren | arbeiten | sprechen | sein |
|---|---|---|---|---|---|---|---|
| ich | heiße | komme | wohne | studiere | arbeite | spreche | bin |
| du | heißt | kommst | wohnst | studierst | arbeitest | sprichst | bist |
| er/sie/es | heißt | kommt | wohnt | studiert | arbeitet | spricht | ist |
| wir | heißen | kommen | wohnen | studieren | arbeiten | sprechen | sind |
| ihr | heißt | kommt | wohnt | studiert | arbeitet | sprecht | seid |
| sie/Sie | heißen | kommen | wohnen | studieren | arbeiten | sprechen | sind |

---

 ## b)

 ## 1

1. Seid ihr auch hier im Deutschkurs?  
2. Wie heißt ihr?  
3. Woher kommt ihr?  
4. Was studiert ihr?

---

 ## 2

1. Das sind Olivia und Noah.  
2. Sie sind neu im Deutschkurs.  
3. Olivia kommt aus Kanada.  
4. Sie studiert Informatik.  
5. Noah kommt aus den USA.  
6. Er studiert Chemie.

---

 ## c)

1. Ich bin aus Deutschland.  
2. Ich komme aus Madrid.  
3. Ich heiße Sarah.  
4. Ich bin Sarah.  
5. Ich bin Deutschlehrer.  
6. Ich studiere Medizin.

---

# Wer ist das?

 ## Nelson Müller

1. Das ist Nelson Müller.  
2. Er kommt aus Ghana.  
3. Er wohnt in Essen.  
4. Er ist Koch und Musiker.  
5. Er spricht Deutsch und Englisch.

---

 ## Christiane Seidel

1. Das ist Christiane Seidel.  
2. Sie kommt aus den USA.  
3. Sie wohnt in Hamburg und New York.  
4. Sie ist Schauspielerin.  
5. Sie spricht Deutsch, Dänisch und Englisch.

---

# Wie geht es dir? Wie geht es Ihnen?

 ## a)

1. Gespräch 1 → informell  
2. Gespräch 2 → formell

---

 ## c) Satzmelodie

* 1 → ↗  
* 2 → ↘  
* 3 → ↗  
* 4 → ↘

---

 ## d)

| Satztyp | Satzmelodie |
|---|---|
| Antwort / Aussage | ↘ |
| W-Frage | ↘ |
| Ja/Nein-Frage | ↗ |

---

# Grammatik kompakt – W-Fragen / Ja-Nein-Fragen

 ## 2a)

 ## Fragen

1. Woher kommt Dana?  
2. Was studiert Dana?  
3. Studierst du auch Biologie?  
4. Kommt ihr morgen zur Party?

---

 ## Antworten

1. Dana kommt aus Almaty.  
2. Sie studiert Chemie.  
3. Nein, ich studiere Chemie.  
4. Ja, wir kommen zur Party.

---

 ## 2b)

1. Position 1  
2. Position 2  
3. ?  
4. .

---

 ## 2c)

1. Frau Klein kommt aus Deutschland.  
2. Kommt Frau Klein aus Deutschland?  
3. Sprichst du Französisch?  
4. Ich studiere Chemie in Marburg.  
5. Kommt Dana morgen zur Party?  
6. Sarah wohnt in Marburg.

---

# Telefonnummern

 ## 3a)

* 1 = eins  
* 2 = zwei  
* 3 = drei  
* 4 = vier  
* 5 = fünf  
* 6 = sechs  
* 7 = sieben  
* 8 = acht  
* 9 = neun  
* 10 = zehn

---

 ## 3b)

* 1 → 089  
* 2 → 040  
* 3 → 0221  
* 4 → 07972

---

 ## 3c)

* Telefonnummer → 3446203  
* Handynummer → 01692831572  
* E-Mail-Adresse → niklas.ab88@xpu.de

---

 ## Hundert – tausend – hunderttausend

 ## 4a)

* 11 → elf  
* 12 → zwölf  
* 13 → dreizehn  
* 14 → vierzehn  
* 15 → fünfzehn  
* 16 → sechzehn  
* 17 → siebzehn  
* 18 → achtzehn  
* 19 → neunzehn  

* 20 → zwanzig  
* 21 → einundzwanzig  
* 30 → dreißig  
* 40 → vierzig  
* 50 → fünfzig  
* 60 → sechzig  
* 70 → siebzig  
* 80 → achtzig  
* 90 → neunzig  

* 100 → einhundert  
* 101 → einhunderteins  
* 199 → einhundertneunundneunzig  
* 200 → zweihundert  
* 1000 → eintausend  
* 10 000 → zehntausend  
* 100 000 → einhunderttausend  
* 1 000 000 → eine Million  
* 1 000 000 000 → eine Milliarde






