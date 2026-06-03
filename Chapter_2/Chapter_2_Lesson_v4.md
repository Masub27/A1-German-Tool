<!--
author:   Kanwal & Makhdoom
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

# Studium und Freizeit

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/Chapter%202%20Introduction_1080p.mp4?raw=true)

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">

  <defs>

    <linearGradient id="bg2" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#f6faf2"/>
      <stop offset="100%" stop-color="#ffffff"/>
    </linearGradient>

    <linearGradient id="card2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="100%" stop-color="#f8fbf3"/>
    </linearGradient>

    <linearGradient id="green2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#98ab29"/>
      <stop offset="100%" stop-color="#b9ca49"/>
    </linearGradient>

    <filter id="shadow2" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="14" stdDeviation="18" flood-color="#80902d" flood-opacity="0.22"/>
    </filter>

    <style><![CDATA[
      .bigNo{
        font-family:Georgia, serif;
        font-size:180px;
        fill:#dce7bc;
        font-weight:700;
      }

      .title{
        font-family:Georgia, serif;
        font-size:70px;
        fill:#6f8120;
        font-weight:700;
      }

      .subtitle{
        font-family:Arial,sans-serif;
        font-size:24px;
        fill:#5f6952;
      }

      .head{
        font-family:Georgia, serif;
        font-size:28px;
        fill:#7b8b2b;
        font-weight:700;
      }

      .text{
        font-family:Arial,sans-serif;
        font-size:20px;
        fill:#4e5647;
      }

      .footer{
        font-family:Arial,sans-serif;
        font-size:18px;
        fill:#68715d;
      }

      .chip{
        font-family:Arial,sans-serif;
        font-size:22px;
        font-weight:700;
        fill:white;
      }
    ]]></style>

  </defs>

  <rect width="1600" height="900" fill="url(#bg2)"/>

  <circle cx="1350" cy="180" r="180" fill="#edf3db"/>
  <circle cx="240" cy="760" r="190" fill="#eef4df"/>
  <circle cx="1500" cy="760" r="120" fill="#f1f6e5"/>

  <g filter="url(#shadow2)">
    <rect x="90" y="90" width="1420" height="720" rx="34"
          fill="url(#card2)" stroke="#dfe7ca" stroke-width="2"/>
  </g>

  <rect x="120" y="120" width="240" height="56" rx="18"
        fill="url(#green2)"/>

  <text x="240" y="156" text-anchor="middle" class="chip">
    KAPITEL
  </text>

  <text x="140" y="320" class="bigNo">2</text>

  <text x="350" y="300" class="title">
    Studium
  </text>

  <text x="350" y="380" class="title">
    und Freizeit
  </text>

  <text x="350" y="445" class="subtitle">
    Freizeitaktivitäten • Hobbys • Sportarten • Universität
  </text>

  <!-- LEFT CARD -->
  <rect x="150" y="540" width="430" height="180" rx="24"
        fill="#f8fbf3" stroke="#dfe8cb"/>

  <text x="185" y="590" class="head">📘 Wortfelder</text>

  <text x="185" y="635" class="text">• Freizeitaktivitäten</text>
  <text x="185" y="670" class="text">• Hobbys und Sport</text>
  <text x="185" y="705" class="text">• Personen an der Universität</text>

  <!-- CENTER CARD -->
  <rect x="620" y="540" width="430" height="180" rx="24"
        fill="#f8fbf3" stroke="#dfe8cb"/>

  <text x="655" y="590" class="head">💬 Sprachhandlungen</text>

  <text x="655" y="635" class="text">• über Freizeit sprechen</text>
  <text x="655" y="670" class="text">• Vorlieben ausdrücken</text>
  <text x="655" y="705" class="text">• informelle E-Mails schreiben</text>

  <!-- RIGHT CARD -->
  <rect x="1090" y="540" width="320" height="180" rx="24"
        fill="#f8fbf3" stroke="#dfe8cb"/>

  <text x="1125" y="590" class="head">✏️ Grammatik</text>

  <text x="1125" y="635" class="text">• Artikel</text>
  <text x="1125" y="670" class="text">• Negation</text>
  <text x="1125" y="705" class="text">• Personalpronomen</text>

  <line x1="140" y1="770" x2="1460" y2="770"
        stroke="#dbe4c5" stroke-width="2"/>

  <text x="140" y="805" class="footer">
    Deutsch A1.1 • Kapitel 2 • Schritt für Schritt lernen
  </text>

  <text x="1460" y="805" text-anchor="end" class="footer">
    Studium • Freizeit • Kommunikation
  </text>

</svg>

---
# 🤖 Offline Chatbot – Kapitel 2 

<div id="c2bot" style="background:#f6faf2;border:2px solid #dbe8c8;border-radius:22px;padding:22px;max-width:1100px;margin:auto;font-family:Arial,sans-serif;">

<h2 style="color:#6f8120;">🤖 Kapitel 2 Lernbot – Studium und Freizeit</h2>

<div id="c2-output" style="background:white;border:1px solid #d8e6c8;border-radius:16px;padding:16px;min-height:220px;max-height:430px;overflow:auto;line-height:1.7;margin-bottom:14px;">
<b>Bot:</b> Hallo! Ask me about Kapitel 2: Uni, Freizeit, Buddy, Artikel, Negation, Akkusativ, E-Mail 😊
</div>

<input id="c2-input" placeholder="Example: difference between kein and nicht" style="width:68%;padding:12px;border-radius:12px;border:1px solid #b9cda0;">
<button id="c2-ask" type="button" style="padding:12px 16px;border-radius:12px;border:none;background:#7b8b2b;color:white;font-weight:bold;">Ask</button>
<button id="c2-clear" type="button" style="padding:12px 16px;border-radius:12px;border:1px solid #7b8b2b;background:white;color:#7b8b2b;font-weight:bold;">Clear</button>

<h3>💡 Quick Questions</h3>
<div id="c2-quick" style="display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:10px;margin-top:12px;"></div>

</div>

<script>
setTimeout(function(){

  const output = document.getElementById("c2-output");
  const input = document.getElementById("c2-input");
  const askBtn = document.getElementById("c2-ask");
  const clearBtn = document.getElementById("c2-clear");
  const quickBox = document.getElementById("c2-quick");

  const questions = [
    "Chapter 2 overview",
    "Uni und Freizeit vocabulary answers",
    "Verb combinations answers",
    "What is Buddy?",
    "Who is Daniel?",
    "Buddy interview answers",
    "Nominative article table",
    "ein eine kein keine explanation",
    "Erstsemester fragen answers",
    "Personal pronouns answers",
    "Daniel and Pablo languages",
    "Daniel and Pablo activities",
    "Daniel or Pablo answers",
    "Difference between nicht and kein",
    "Negation exercise answers",
    "Stress exercise answers",
    "Schwarzes Brett topics",
    "Advertisement answers",
    "Akkusativ table answers",
    "Akkusativ rules",
    "Article exercise answers",
    "Formal or informal email",
    "Unisport form example",
    "Email to Lars example"
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

  function hasAny(q, list){
    return list.some(function(x){ return q.includes(normalize(x)); });
  }

  function card(title, body){
    return "<div style='background:#f8fbff;border:1px solid #d9e7ff;border-radius:14px;padding:14px;margin-top:8px;'>" +
           "<b style='color:#2c5d9b;font-size:17px;'>" + title + "</b><br><br>" + body + "</div>";
  }

  function answer(question){
    const q = normalize(question);

    if(hasAny(q, ["overview", "chapter 2", "kapitel 2", "about chapter"])){
      return card("Kapitel 2 Overview",
        "Kapitel 2 heißt <b>Studium und Freizeit</b>.<br><br>" +
        "You learn:<br>" +
        "• Uni und Freizeit vocabulary<br>" +
        "• Buddy and Erstsemester<br>" +
        "• Freizeitaktivitäten<br>" +
        "• Artikel: ein/eine, der/die/das, kein/keine<br>" +
        "• Personalpronomen: er, es, sie<br>" +
        "• Negation: nicht and kein<br>" +
        "• Akkusativ<br>" +
        "• formal and informal emails.");
    }

    if(hasAny(q, ["uni und freizeit vocabulary", "vocabulary answers", "uni freizeit words", "words answers"])){
      return card("Uni und Freizeit – Vocabulary Answers",
        "1. die Filme<br>" +
        "2. das Keyboard<br>" +
        "3. die Bücher<br>" +
        "4. die Universität<br>" +
        "5. der Computer<br>" +
        "6. das Formular<br>" +
        "7. der Ball<br>" +
        "8. der Sport<br>" +
        "9. die Musik<br>" +
        "10. das Schach<br>" +
        "11. der Laptop<br>" +
        "12. die Salsa");
    }

    if(hasAny(q, ["verb combinations", "verbs go", "verben", "verb answers", "musik hören", "buecher lesen", "bücher lesen"])){
      return card("Verb Combinations – Answers",
        "Bücher lesen<br>" +
        "Filme sehen<br>" +
        "Musik hören<br>" +
        "Salsa tanzen<br>" +
        "Sport treiben<br>" +
        "Ball / Keyboard / Schach spielen<br>" +
        "ein Formular ausfüllen<br>" +
        "einen Computer / Laptop haben<br>" +
        "die Universität zeigen");
    }

    if(hasAny(q, ["buddy", "what is buddy"])){
      return card("Buddy",
        "Ein Buddy ist eine Studentin oder ein Student.<br><br>" +
        "A Buddy helps first-semester students. A Buddy:<br>" +
        "• kennt die Uni<br>" +
        "• begleitet Erstsemester<br>" +
        "• zeigt die Uni<br>" +
        "• gibt Tipps<br>" +
        "• organisiert Partys.");
    }

    if(hasAny(q, ["who is daniel", "daniel ist"])){
      return card("Who is Daniel?",
        "Daniel ist <b>Buddy</b>.<br><br>" +
        "Correct answer:<br>" +
        "a. Erstsemester ❌<br>" +
        "b. Buddy ✅");
    }

    if(hasAny(q, ["buddy interview", "interview answers", "daniel arbeitet", "buddy kennt"])){
      return card("Buddy Interview – Answers",
        "1. Daniel arbeitet → <b>d</b><br>" +
        "2. Der Buddy kennt → <b>c</b><br>" +
        "3. Die Erstsemester → <b>a</b><br>" +
        "4. Daniel findet, der Job → <b>b</b><br><br>" +
        "Complete meanings:<br>" +
        "Daniel arbeitet als Buddy.<br>" +
        "Der Buddy kennt die Uni und begleitet Erstsemester.<br>" +
        "Die Erstsemester sind neu und haben Fragen.<br>" +
        "Daniel findet, der Job als Buddy ist super.");
    }

    if(hasAny(q, ["nominative article", "nominativ artikel", "article table nominative", "artikel im nominativ"])){
      return card("Nominative Article Table",
        "<b>Unbestimmter Artikel:</b><br>" +
        "ein Job / ein Studium / eine Universität / — Sprachen<br><br>" +
        "<b>Negativartikel:</b><br>" +
        "kein Job / kein Studium / keine Universität / keine Sprachen<br><br>" +
        "<b>Bestimmter Artikel:</b><br>" +
        "der Job / das Studium / die Universität / die Sprachen<br><br>" +
        "<b>Personalpronomen:</b><br>" +
        "der Job → er<br>" +
        "das Studium → es<br>" +
        "die Universität → sie<br>" +
        "die Sprachen → sie");
    }

    if(hasAny(q, ["ein eine kein keine", "unbestimmter artikel", "negativartikel", "ein eine", "kein keine"])){
      return card("ein / eine / kein / keine",
        "<b>Nominativ:</b><br>" +
        "Maskulin: ein Job / kein Job<br>" +
        "Neutrum: ein Studium / kein Studium<br>" +
        "Feminin: eine Universität / keine Universität<br>" +
        "Plural: — Sprachen / keine Sprachen<br><br>" +
        "<b>Akkusativ:</b><br>" +
        "Maskulin changes:<br>" +
        "ein Computer → einen Computer<br>" +
        "kein Computer → keinen Computer<br>" +
        "der Computer → den Computer<br><br>" +
        "Neutrum stays same:<br>" +
        "ein Formular → ein Formular<br>" +
        "kein Formular → kein Formular<br><br>" +
        "Feminin stays same:<br>" +
        "eine Tasche → eine Tasche<br>" +
        "keine Tasche → keine Tasche<br><br>" +
        "Plural:<br>" +
        "Kurse / keine Kurse / die Kurse");
    }

    if(hasAny(q, ["erstsemester fragen", "article dialogue", "wer ist das artikel"])){
      return card("Erstsemester fragen – Answers",
        "1. Ist das <b>ein</b> Student?<br>" +
        "Nein, das ist <b>kein</b> Student, das ist <b>ein</b> Professor. <b>Der</b> Professor ist neu.<br><br>" +
        "2. Ist das <b>ein</b> Erstsemester?<br>" +
        "Nein, das ist <b>kein</b> Erstsemester. Das ist <b>ein</b> Buddy. <b>Der</b> Buddy ist sehr nett.<br><br>" +
        "3. Ist das <b>eine</b> Professorin?<br>" +
        "Nein, das ist <b>keine</b> Professorin. Das ist <b>eine</b> Lehrerin, <b>die</b> Deutschlehrerin.<br><br>" +
        "4. Sind das Lehrerinnen?<br>" +
        "Nein, das sind <b>keine</b> Lehrerinnen, das sind Studentinnen. <b>Die</b> Studentinnen sind neu an der Uni.");
    }

    if(hasAny(q, ["personal pronouns", "personalpronomen", "pronomen", "er es sie"])){
      return card("Personalpronomen – Answers",
        "1. Das Studium hier ist super. <b>Es</b> ist nicht einfach, aber ein Studium ist kein Hobby, <b>es</b> ist ein Job.<br><br>" +
        "2. Der Job hier ist neu. <b>Er</b> ist sehr interessant. Die Kollegen sind sehr nett. Ich habe Fragen und <b>sie</b> geben Tipps.<br><br>" +
        "3. Der Deutschkurs ist sehr wichtig. <b>Er</b> ist immer voll. Die Sprache ist nicht einfach, aber <b>sie</b> ist sehr interessant.");
    }

    if(hasAny(q, ["daniel and pablo languages", "sprachtandem", "who speaks what", "languages"])){
      return card("Daniel und Pablo – Languages",
        "Daniel spricht <b>Deutsch</b> und lernt <b>Spanisch</b>.<br>" +
        "Pablo spricht <b>Spanisch</b> und lernt <b>Deutsch</b>.");
    }

    if(hasAny(q, ["daniel and pablo activities", "freizeit activities", "activities answers", "what activities"])){
      return card("Daniel und Pablo – Freizeit Activities",
        "They talk about:<br>" +
        "✅ Musik hören<br>" +
        "✅ Sport treiben / machen<br>" +
        "✅ Schach spielen<br>" +
        "✅ Badminton spielen<br><br>" +
        "Final answer:<br>" +
        "Daniel und Pablo <b>spielen Badminton</b>.");
    }

    if(hasAny(q, ["daniel or pablo", "who says what", "d oder p"])){
      return card("Daniel oder Pablo – Answers",
        "a. <b>D</b> – Ich spreche kein Spanisch.<br>" +
        "b. <b>P</b> – Ich tanze nicht.<br>" +
        "c. <b>D</b> – Ich spiele kein Schach.<br>" +
        "d. <b>P</b> – Ich schwimme nicht gut.");
    }

    if(hasAny(q, ["nicht and kein", "kein and nicht", "difference between nicht and kein", "negation rule", "verneinung", "negation"])){
      return card("Difference between nicht and kein",
        "<b>kein / keine</b> negates nouns.<br>" +
        "Examples:<br>" +
        "Das ist <b>kein</b> Problem.<br>" +
        "Ein Studium ist <b>kein</b> Hobby.<br><br>" +
        "<b>nicht</b> negates verbs, adjectives, places, adverbs, or the whole sentence.<br>" +
        "Examples:<br>" +
        "Pablo kommt <b>nicht</b> aus Portugal.<br>" +
        "Yu spielt <b>nicht gut</b> Gitarre.<br>" +
        "Luis treibt <b>nicht gern</b> Sport.");
    }

    if(hasAny(q, ["negation exercise", "verneinen answers"])){
      return card("Negation Exercise – Answers",
        "1. Pablo kommt <b>nicht</b> aus Portugal.<br>" +
        "2. Yu spielt <b>nicht gut</b> Gitarre.<br>" +
        "3. Ein Studium ist <b>kein</b> Hobby.<br>" +
        "4. Luis treibt <b>nicht gern</b> Sport.<br>" +
        "5. Das ist <b>kein</b> Problem.");
    }

    if(hasAny(q, ["stress exercise", "wortakzent", "betont", "which word stressed"])){
      return card("Stress Exercise – Answers",
        "Anna.<br>" +
        "Anna und <b>Alex</b>.<br>" +
        "Anna und Alex <b>spielen</b>.<br>" +
        "Anna und Alex spielen <b>nicht</b>.<br>" +
        "Anna und Alex spielen nicht <b>gern</b>.<br>" +
        "Anna und Alex spielen nicht gern <b>Fußball</b>.<br>" +
        "Anna und Alex spielen nicht gern Fußball im <b>Stadion</b>.<br>" +
        "Anna und Alex spielen lieber <b>Volleyball</b> im Park.");
    }

    if(hasAny(q, ["schwarzes brett", "blackboard topics", "topics answers"])){
      return card("Schwarzes Brett – Topics",
        "Filme → <b>x</b><br>" +
        "Sport → <b>3, 4</b><br>" +
        "Musik → <b>1</b><br>" +
        "Sprachen → <b>x</b><br>" +
        "Technik → <b>2</b><br><br>" +
        "Two topics do not fit: Filme and Sprachen.");
    }

    if(hasAny(q, ["advertisement answers", "which advertisement", "anzeigen answers", "was passt"])){
      return card("Advertisement Answers",
        "1. Das Surfboard von Arthur ist neu. Er sucht einen Kurs. → Anzeige <b>3</b><br>" +
        "2. Yuma hat keinen Computer, aber sie sucht einen Computer, am liebsten einen Laptop. → Anzeige <b>2</b><br>" +
        "3. Tom und Finja lernen Gitarre und haben viele Fragen. → Anzeige <b>1</b>");
    }

    if(hasAny(q, ["akkusativ table", "accusative table", "akkusativ article", "accusative article"])){
      return card("Akkusativ Article Table",
        "<b>Nominativ:</b><br>" +
        "ein Computer / ein Surfboard / eine Tasche / — Kurse<br>" +
        "kein Computer / kein Surfboard / keine Tasche / keine Kurse<br>" +
        "der Computer / das Surfboard / die Tasche / die Kurse<br><br>" +
        "<b>Akkusativ:</b><br>" +
        "einen Computer / ein Surfboard / eine Tasche / — Kurse<br>" +
        "keinen Computer / kein Surfboard / keine Tasche / keine Kurse<br>" +
        "den Computer / das Surfboard / die Tasche / die Kurse");
    }

    if(hasAny(q, ["akkusativ rules", "accusative rules", "nominativ akkusativ", "accusative"])){
      return card("Akkusativ Rules",
        "1. The subject is in <b>Nominativ</b>.<br>" +
        "2. Many verbs need an <b>Akkusativ-Ergänzung</b>.<br>" +
        "3. Only <b>Maskulinum</b> changes in Akkusativ.<br><br>" +
        "Important verbs:<br>" +
        "haben, suchen, kaufen, brauchen<br><br>" +
        "Examples:<br>" +
        "Ich suche <b>einen Laptop</b>.<br>" +
        "Ich brauche <b>kein Formular</b>.<br>" +
        "Ich kaufe <b>ein Surfboard</b>.");
    }

    if(hasAny(q, ["article exercise", "passenden artikel", "haben sie laptops", "article answers"])){
      return card("Passende Artikel – Answers",
        "1. Haben Sie Laptops?<br>" +
        "Nein, wir haben <b>keine</b> Laptops. / Ja, hier sind <b>die</b> Laptops.<br><br>" +
        "2. Brauche ich <b>ein</b> Formular?<br>" +
        "Nein, Sie brauchen <b>kein</b> Formular. / Ja, hier ist <b>das</b> Formular.<br><br>" +
        "3. Suchen Sie <b>einen</b> Laptop?<br>" +
        "Nein, ich brauche <b>keinen</b> Laptop.<br><br>" +
        "4. Haben Sie <b>eine</b> Laptoptasche?<br>" +
        "Ja, <b>die</b> Laptoptasche ist gratis.");
    }

    if(hasAny(q, ["formal informal email", "formell informell", "email type"])){
      return card("Formal or Informal Email",
        "E-Mail 1 is <b>formell</b>.<br>" +
        "Clues: Sehr geehrter Herr Bauer, Sie, Vielen Dank, Mit freundlichen Grüßen.<br><br>" +
        "E-Mail 2 is <b>informell</b>.<br>" +
        "Clues: Hallo Daniel, du, Viele Grüße.");
    }

    if(hasAny(q, ["unisport form", "form example", "formular ausfuellen"])){
      return card("Unisport Form Example",
        "Sportart / Sportarten: Badminton, Yoga, Volleyball<br>" +
        "Name, Vorname: Masub Makhdoom<br>" +
        "Geschlecht: choose only one option: m / w / d<br>" +
        "Adresse: Magdeburg, Deutschland<br>" +
        "Telefonnummer: 015123456789<br>" +
        "E-Mail: masub@example.com<br>" +
        "Datum, Unterschrift: 15.05.2026 / Masub Makhdoom");
    }

    if(hasAny(q, ["email to lars", "mail to lars", "write email to lars"])){
      return card("Informal Email to Lars",
        "Hallo Lars,<br><br>" +
        "danke für deine Mail.<br>" +
        "Im Anhang findest du das Formular für die Anmeldung.<br><br>" +
        "Viele Grüße<br>" +
        "Masub");
    }

    return card("Question not found",
      "Please ask about one Chapter 2 section:<br>" +
      "• Uni und Freizeit vocabulary<br>" +
      "• Buddy<br>" +
      "• Artikel / Akkusativ<br>" +
      "• nicht / kein<br>" +
      "• Daniel und Pablo<br>" +
      "• Schwarzes Brett<br>" +
      "• E-Mail");
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
    output.innerHTML = "<b>Bot:</b> Hallo! Ask me about Kapitel 2 😊";
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

# 1 Uni und Freizeit

 ## a) Was ist das? Ordnen Sie zu.Gibt es das Wort auch in Ihrer Sprache oder in anderen Sprachen? Notieren Sie.

**Wörter:**  
der Ball · die Bücher · der Computer · die Filme · das Formular · das Keyboard · der Laptop · die Musik · die Salsa · das Schach · der Sport · die Universität

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_1.png?raw=true)

1. ~~__die Filme __~~ 
2. [[das Keyboard]]  
3. [[die Bücher]]  
4. [[die Universität]]  
5. [[der Computer]]  
6. [[das Formular]]  
7. [[der Ball]]  
8. [[der Sport]]  
9. [[die Musik]]  
10. [[das Schach]]  
11. [[der Laptop]]  
12. [[die Salsa]]

---
    --{{0}}--

!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/Avatar%20-%20Uni%20und%20Freizeit_1080p.mp4?raw=true)

 ## b) Was passt wo? Ordnen Sie die Verben zu.

**Verben:**  
ausfüllen · haben · hören · lesen · sehen · spielen · tanzen · treiben · zeigen

1. Bücher [[lesen]]  
2. Filme [[sehen]]  
3. Musik [[hören]]  
4. Salsa [[tanzen]]  
5. Sport [[treiben]]  
6. Ball / Keyboard / Schach [[spielen]]  
7. ein Formular [[ausfüllen]]  
8. einen Computer / Laptop [[haben]]  
9. die Universität [[zeigen]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1a – Was ist das? Ordnen Sie zu.</b></summary>

In this exercise, you learn:
🎓 University vocabulary  
🎵 Free time vocabulary  
🧠 German articles

Your task:
✅ Match the pictures with the correct words  
✅ Learn:
- der
- die
- das

---

## Important articles

| Article | Gender |
|---|---|
| der | masculine |
| die | feminine / plural |
| das | neuter |

---

## Helpful vocabulary

| German | English |
|---|---|
| der Ball | ball |
| die Bücher | books |
| der Computer | computer |
| die Filme | films |
| das Formular | form |
| das Keyboard | keyboard |
| der Laptop | laptop |
| die Musik | music |
| die Salsa | salsa |
| das Schach | chess |
| der Sport | sport |
| die Universität | university |

---

## Helpful strategy

Look carefully at:
🖼️ the pictures

Then ask:
👉 Is it:
- Sport?
- Music?
- Computer?
- University?

---

## Important tip

Some German words are international.

Examples:
- Computer
- Laptop
- Salsa
- Sport

They may look similar in your language.

---

## Practice tip

Read the words aloud:

🗣️ der Ball  
🗣️ die Musik  
🗣️ das Keyboard

This improves:
✅ Pronunciation  
✅ Vocabulary  
✅ Article memorization

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1b – Was passt wo? Ordnen Sie die Verben zu.</b></summary>

In this exercise, you practice:
🧩 verb combinations.

Your task:
✅ Connect verbs with the correct nouns  
✅ Learn common German expressions

---

## Important verb combinations

| Expression | English |
|---|---|
| Bücher lesen | read books |
| Filme sehen | watch films |
| Musik hören | listen to music |
| Salsa tanzen | dance salsa |
| Sport treiben | do sport |
| Schach spielen | play chess |
| ein Formular ausfüllen | fill out a form |
| einen Laptop haben | have a laptop |
| die Universität zeigen | show the university |

---

## Helpful strategy

Ask:
👉 What do we normally do with this thing?

Examples:
📚 Books → read  
🎵 Music → listen  
⚽ Sport → do/play

---

## Important grammar

Some verbs need Akkusativ.

Examples:
- einen Computer haben
- ein Formular ausfüllen

Notice:
✅ einen Computer (masculine Akkusativ)

---

## Helpful tip

One verb can work with several nouns.

Example:
🎮 spielen
- Ball spielen
- Keyboard spielen
- Schach spielen

---

## Practice tip

Say the combinations aloud:

🗣️ Musik hören  
🗣️ Sport treiben  
🗣️ Salsa tanzen

This improves:
✅ Fluency  
✅ Vocabulary  
✅ Sentence building

</details>

---

# 1 Sei ein Buddy – ein Programm für Erstsemester

    --{{0}}--

!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/Sei%20ein%20Buddy.mp4?raw=true)

 ## a) Lesen Sie das Interview mit Daniel im Unijournal. Wer ist Daniel? Kreuzen Sie an.

**Daniel ist**

[[ ]] a. Erstsemester  
[[x]] b. Buddy



---

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_2.png?raw=true)

 ## b) Lesen Sie das Interview in 1a noch einmal. Lesen Sie dann die Sätze und ordnen Sie zu.

<div style="display:grid;grid-template-columns:1fr 1fr;gap:22px;">

<!-- LEFT SIDE -->
<div style="background:#f8fbff;border:1px solid #d9e7ff;border-radius:18px;padding:20px;">

<h3 style="margin-top:0;color:#2c5d9b;">Fragen</h3>

1. Daniel arbeitet [[d]]

2. Der Buddy kennt [[c]]

3. Die Erstsemester [[a]]

4. Daniel findet, der Job [[b]]

</div>

<!-- RIGHT SIDE -->
<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:20px;">

<h3 style="margin-top:0;color:#8a6b00;">Sätze</h3>

* a. sind neu und haben Fragen. Der Buddy gibt Tipps.
 
* b. als Buddy ist super. Er organisiert Partys und übt Spanisch.
 
* c. die Uni und begleitet Erstsemester. Er zeigt die Uni.
 
* d. als Buddy. Ein Buddy ist eine Studentin oder ein Student.

</div>

</div>

---



 ## 2 [GRAMMATIK KOMPAKT] Bestimmter, unbestimmter Artikel und Negativartikel im Nominativ

 ## a) Suchen Sie in 1a und 1b und ergänzen Sie die Artikel und Negativartikel.

<div style="background:#f4faf8;border:1px solid #cdded8;border-radius:20px;padding:18px;">

|  | Maskulinum (M) | Neutrum (N) | Femininum (F) | Plural (M, N, F) |
|---|---|---|---|---|
| **unbestimmter Artikel** | [[ein]] Job | ein Studium | eine Uni(versität) | — Sprachen |
| **Negativartikel** | kein Job | [[kein]] Studium | keine Uni(versität) | keine Sprachen |
| **bestimmter Artikel** | der Job | das Studium | die Uni(versität) | die Sprachen |
| **Personalpronomen** | [[Er]] ist super. | [[Es]] ist nicht einfach. | [[Sie]] ist groß. | [[Sie]] sind interessant. |

</div>

---

 ## Merksatz

<div style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:16px;padding:16px;line-height:1.7;">
<b>ein / ein / eine / —</b> = Die Information ist neu.  
<br>
<b>der / das / die / die</b> = Die Information ist bekannt.
</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1a – Wer ist Daniel?</b></summary>

In this exercise, you practice:
🎓 university vocabulary  
👥 student support programmes  
📖 reading comprehension

Your task:
✅ Read the interview carefully  
✅ Understand what a <b>Buddy</b> is  
✅ Choose the correct answer

---

## Important vocabulary

| German | English |
|---|---|
| der Buddy | buddy / student helper |
| das Erstsemester | first-semester student |
| begleiten | accompany |
| Tipps geben | give tips |
| organisieren | organize |
| die Universität zeigen | show the university |

---

## Helpful strategy

Look for:
👉 What does Daniel do?

Ask yourself:
- Is he new at university?
- Or does he help new students?

---

## Important clue

A Buddy:
✅ Knows the university  
✅ Helps students  
✅ Answers questions  
✅ Gives tips

An Erstsemester:
✅ Is new at university

---

## Reading tip

Read these important sentences carefully:
🗣️ „Ein Buddy ist eine Studentin oder ein Student.“  
🗣️ „Der Buddy begleitet Erstsemester.“

These sentences help you find the correct answer.

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1b – Lesen Sie die Sätze und ordnen Sie zu.</b></summary>

In this exercise, you practice:
🧩 matching sentence parts  
📖 understanding interview information

Your task:
✅ connect the sentence beginnings with the correct endings

---

## Helpful strategy

Read:
1️⃣ The left side  
2️⃣ The right side  
3️⃣ Find the logical connection

---

## Important vocabulary

| German | English |
|---|---|
| arbeiten als Buddy | work as a buddy |
| die Uni kennen | know the university |
| Erstsemester | first-semester students |
| Tipps geben | give tips |
| organisieren | organize |
| begleiten | accompany |

---

## Helpful clue

Ask:
👉 What matches logically?

Example:
🗣️ „Daniel arbeitet …“  
→ What can someone work as?

Correct idea:
✅ als Buddy

---

## Grammar tip

Some sentences continue with:
- Verbs
- Explanations
- Additional information

Example:
🗣️ „Die Erstsemester …“  
→ What are they?

Possible clue:
✅ neu  
✅ haben Fragen

---

## Practice tip

Read the complete sentences aloud after matching:

🗣️ Daniel arbeitet als Buddy.  
🗣️ Die Erstsemester sind neu und haben Fragen.

This improves:
✅ Reading comprehension  
✅ Sentence structure  
✅ Speaking fluency

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2a – Artikel und Negativartikel ergänzen</b></summary>

In this exercise, you practice:
📚 German articles  
🧠 grammatical gender  
❌ negation with kein / keine

Your task:
✅ Complete the table with:
- bestimmter Artikel
- unbestimmter Artikel
- Negativartikel
- Personalpronomen

---

## Important articles

| Gender | Indefinite | Definite | Negative |
|---|---|---|---|
| Maskulin | ein | der | kein |
| Neutrum | ein | das | kein |
| Feminin | eine | die | keine |
| Plural | — | die | keine |

---

## Helpful vocabulary

| German | Gender |
|---|---|
| Job | Maskulin |
| Studium | Neutrum |
| Universität | Feminin |
| Sprachen | Plural |

---

## Personalpronomen

| Noun | Pronoun |
|---|---|
| der Job | er |
| das Studium | es |
| die Universität | sie |
| die Sprachen | sie |

---

## Important grammar rule

Use:
✅ <b>kein / keine</b> to negate nouns

Examples:
- kein Job
- keine Universität

---

## Helpful strategy

First ask:
👉 Is the noun:
- masculine?
- neuter?
- feminine?
- plural?

Then choose the correct article.

---

## Practice tip

Say the examples aloud:

🗣️ ein Job – kein Job  
🗣️ eine Universität – keine Universität  
🗣️ das Studium – es

This improves:
✅ Article memorization  
✅ Grammar accuracy  
✅ Speaking confidence

</details>

---

<details style="background:#f7f2ff;border:1px solid #d9c8f0;border-radius:14px;padding:14px;">
<summary><b>💡 Hint for Merksatz</b></summary>

This grammar rule is very important in German.

---

## New information

Use:
✅ ein / eine / ein

Examples:
- ein Job
- eine Universität
- ein Studium

Meaning:
➡️ The listener does not know the thing yet.

---

## Known information

Use:
✅ der / die / das

Examples:
- der Job
- die Universität
- das Studium

Meaning:
➡️ the thing is already known.

---

## Example

🗣️ Das ist <b>ein</b> Buddy.  
🗣️ <b>Der</b> Buddy ist sehr nett.

First mention:
➡️ ein Buddy

Second mention:
➡️ der Buddy

---

## Practice tip

Notice:
📌 First mention = unbestimmter Artikel  
📌 Second mention = bestimmter Artikel

This helps:
✅ Speaking  
✅ Writing  
✅ Reading German texts

</details>

## b) Wer ist das? Erstsemester fragen, Daniel antwortet. Welcher Artikel passt? Ergänzen Sie.

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/Erstsemester%20fragen_1080p.mp4?raw=true)

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_017.mp3?raw=true)

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_3.png?raw=true)

<div style="background:#f8fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;line-height:2;">

### 1.

• Ist das [[ein]] Student?  

○ Nein, das ist [[kein]] Student, das ist [[ein]] Professor.  [[Der]] Professor ist neu! Er kommt aus Indien.

---

### 2.

• Ist das [[ein]] Erstsemester?  

○ Nein, das ist [[kein]] Erstsemester. Das ist [[ein]] Buddy.  [[Der]] Buddy ist sehr nett.

---

### 3.

• Ist das [[eine]] Professorin?  

○ Nein, das ist [[keine]] Professorin. Das ist [[eine]] Lehrerin, [[die]] Deutschlehrerin.  

Sie heißt Frau Hansen.

---

### 4.

• Sind das  Lehrerinnen?  

○ Nein, das sind [[keine]] Lehrerinnen, das sind  Studentinnen.[[Die]] Studentinnen sind neu an der Uni.

</div>

---

 ## c) Personen an der Uni Greifswald. Ergänzen Sie die Personalpronomen.

**er • er • es • es • sie (Sg.) • sie (Pl.)**

<div style="background:#f6fff3;border:1px solid #d6ebc8;border-radius:18px;padding:18px;line-height:2;">

### 1.

Wir sind Erstsemester. Das Studium hier ist super.  [[Es]] ist nicht einfach, aber ein Studium ist kein Hobby, [[es]] ist ein Job!

---

### 2.

Ich bin auch „Erstsemester“, der Job hier ist neu.  [[Er]] ist sehr interessant! Und die Kollegen sind sehr nett.  

Ich habe Fragen und [[sie]] geben Tipps.

---

### 3.

Der Deutschkurs ist sehr wichtig.  [[Er]] ist immer voll. Die Sprache ist nicht einfach, aber [[sie]] ist sehr interessant! 😊

</div>

---



 ## 3 [AUSSPRACHE] Wortakzent

 ## Hören Sie die Wörter und sprechen Sie nach. Klopfen Sie bei der Betonung.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_018.mp3?raw=true)

<div style="display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:18px;margin-top:18px;">

<div style="background:#f7fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;">
<h3 style="margin-top:0;color:#3f5f8f;">eine Silbe</h3>

- Deutsch
- Job
- Team

</div>

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;">
<h3 style="margin-top:0;color:#8b6a1f;">zwei Silben</h3>

- Sprachkurs
- Journal
- Fußball

</div>

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;">
<h3 style="margin-top:0;color:#3d7b31;">drei Silben</h3>

- Studium
- Studentin
- Professor

</div>

<div style="background:#fff4f8;border:1px solid #efcad8;border-radius:18px;padding:18px;">
<h3 style="margin-top:0;color:#9b4062;">vier Silben</h3>

- Universität
- Studierende
- Erstsemester

</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2b – Welcher Artikel passt?</b></summary>

In this exercise, you practice:
📚 German articles  
❌ negation with kein / keine  
🎓 university vocabulary

Your task:
✅ choose the correct article:
- ein / eine
- kein / keine
- der / die

---

## Important articles

| Gender | Indefinite | Negative | Definite |
|---|---|---|---|
| Maskulin | ein | kein | der |
| Neutrum | ein | kein | das |
| Feminin | eine | keine | die |
| Plural | — | keine | die |

---

## Helpful strategy

First ask:
👉 Is the noun:
- masculine?
- feminine?
- plural?

Then choose the article.

---

## Important vocabulary

| German | Gender |
|---|---|
| Student | Maskulin |
| Professor | Maskulin |
| Erstsemester | Maskulin |
| Buddy | Maskulin |
| Professorin | Feminin |
| Lehrerin | Feminin |
| Studentinnen | Plural |

---

## Helpful clue

When the answer is negative, use:
❌ kein / keine

Examples:
- kein Student
- keine Professorin

---

## Grammar tip

First mention:
✅ ein / eine

Second mention:
✅ der / die

Example:
🗣️ Das ist ein Buddy.  
🗣️ Der Buddy ist sehr nett.

---

## Practice tip

Read the sentences aloud:

🗣️ Das ist ein Professor.  
🗣️ Der Professor ist neu.

This improves:
✅ Article memorization  
✅ Speaking fluency  
✅ Grammar accuracy

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2c – Personalpronomen ergänzen</b></summary>

In this exercise, you practice:
🧠 personal pronouns

Your task:
✅ replace nouns with:
- er
- es
- sie

---

## Important pronouns

| Noun | Pronoun |
|---|---|
| der Job | er |
| das Studium | es |
| die Sprache | sie |
| die Kollegen | sie |

---

## Helpful strategy

Ask:
👉 What is the noun gender?

- masculine → er
- neuter → es
- feminine → sie
- plural → sie

---

## Important vocabulary

| German | Meaning |
|---|---|
| das Studium | studies |
| der Job | job |
| die Kollegen | colleagues |
| die Sprache | language |
| der Deutschkurs | German course |

---

## Helpful clue

Look at the noun before the blank.

Example:
🗣️ Das Studium hier ist super. ___ ist nicht einfach.

Question:
👉 What replaces „das Studium“?

Answer:
✅ es

---

## Practice tip

Read the examples aloud:

🗣️ Der Job ist interessant. Er ist neu.  
🗣️ Die Sprache ist schwer. Sie ist interessant.

This improves:
✅ Grammar understanding  
✅ Sentence building  
✅ Speaking confidence

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;">
<summary><b>💡 Hint for 3 – Aussprache: Wortakzent</b></summary>

In this exercise, you practice:
🎧 pronunciation  
🗣️ word stress (Wortakzent)

Your task:
✅ Listen carefully  
✅ Repeat the words  
✅ Clap on the stressed syllable

---

## Important rule

Every German word has:
✅ One stressed syllable

The stress is stronger and louder.

---

## Helpful strategy

Listen for:
👂 The strongest part of the word

Examples:

🗣️ Fuß-ball  
🗣️ Stu-di-um  
🗣️ U-ni-ver-si-tät

---

## Word groups

### One syllable
Short words:
- Deutsch
- Job
- Team

Stress:
✅ Only one syllable

---

### Two syllables

Examples:
- Sprachkurs
- Journal
- Fußball

Usually:
✅ First syllable is stressed

---

### Three syllables

Examples:
- Studium
- Studentin
- Professor

Listen carefully to:
🎧 The strongest syllable

---

### Four syllables

Examples:
- Universität
- Studierende
- Erstsemester

Longer words need:
✅ Slower pronunciation

---

## Practice tip

Clap while speaking:

👏 Fuß-ball  
👏 Stu-di-um  
👏 U-ni-ver-si-tät

This improves:
✅ Pronunciation  
✅ Rhythm  
✅ Listening skills

</details>

---



# 1 Endlich Freizeit!

 ## a) Daniel und Pablo machen ein Sprachtandem. Wer spricht und wer lernt welche Sprache?
 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_019.mp3?raw=true)

<div style="background:#f7fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;line-height:2;">

1. Daniel spricht [[Deutsch]] und lernt [[Spanisch]].

2. Pablo spricht [[Spanisch]] und lernt [[Deutsch]].

</div>



---

 ## b) Daniel und Pablo planen ein Treffen. Über welche Freizeitaktivitäten sprechen sie?
 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_020.mp3?raw=true)

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_4.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_5.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_6.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_7.png?raw=true)

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_8.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_9.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_10.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/chapter2_11.png?raw=true)

[[ ]] Bücher, Zeitschriften lesen  
[[x]] Musik hören  
[[ ]] Freunde treffen  
[[ ]] Gitarre spielen
[[x]] Sport treiben / machen  
[[ ]] Filme, Serien schauen / sehen  
[[x]] Schach spielen  
[[x]] Badminton spielen 

---

 ## c) Hören Sie das ganze Gespräch und notieren Sie: Was sagt Daniel (D), was sagt Pablo (P)?

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_019.mp3?raw=true)

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_020.mp3?raw=true)



<div style="background:#f9fbff;border:1px solid #d8e6ff;border-radius:18px;padding:18px;line-height:2;">

a. [[D]] Ich spreche kein Spanisch.

b. [[P]] Ich tanze nicht.

c. [[D]] Ich spiele kein Schach.

d. [[P]] Ich schwimme nicht gut.

</div>

---

 ## Daniel und Pablo …

[[x]] a. spielen Badminton.  
[[ ]] b. sprechen nur Deutsch.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1a – Wer spricht und wer lernt welche Sprache?</b></summary>

In this exercise, you practice:
🗣️ languages  
👂 listening comprehension  
🌍 language exchange vocabulary

Your task:
✅ Listen carefully  
✅ Identify:
- Who speaks a language
- Who learns a language

---

## Important vocabulary

| German | English |
|---|---|
| sprechen | to speak |
| lernen | to learn |
| Deutsch | German |
| Spanisch | Spanish |
| das Sprachtandem | language tandem |

---

## Helpful strategy

Listen for:
👂 „Ich spreche …“  
👂 „Ich lerne …“

These phrases give the answer directly.

---

## Important idea

A Sprachtandem means:
✅ Two people help each other learn languages

Example:
- One person speaks German
- The other speaks Spanish

---

## Helpful clue

Ask:
👉 Who is German?  
👉 Who speaks Spanish?

Then match:
- Speak
- Learn

---

## Practice tip

Say the sentences aloud:

🗣️ Daniel spricht Deutsch.  
🗣️ Pablo lernt Deutsch.

This improves:
✅ Pronunciation  
✅ Listening skills  
✅ Sentence building

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1b – Freizeitaktivitäten</b></summary>

In this exercise, you practice:
🎧 listening comprehension  
🎯 Freizeit vocabulary

Your task:
✅ Listen carefully  
✅ Mark the activities Daniel and Pablo talk about

---

## Important vocabulary

| German | English |
|---|---|
| Musik hören | listen to music |
| Sport treiben | do sport |
| Schach spielen | play chess |
| Badminton spielen | play badminton |
| Freunde treffen | meet friends |
| Filme sehen | watch films |

---

## Helpful strategy

Listen for:
👂 activity verbs

Examples:
- spielen
- hören
- machen
- treiben

---

## Important clue

Not every picture is correct.

You must:
✅ Listen carefully  
❌ Do not choose all pictures

---

## Helpful listening tip

If you hear:
🗣️ „Ich spiele …“

Then look for:
🎮 games or sports

If you hear:
🗣️ „Ich höre gern Musik.“

Then choose:
🎵 Musik hören

---

## Practice tip

Read the activities aloud:

🗣️ Sport treiben  
🗣️ Schach spielen  
🗣️ Musik hören

This improves:
✅ Vocabulary  
✅ Speaking  
✅ Listening recognition

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1c – Was sagt Daniel? Was sagt Pablo?</b></summary>

In this exercise, you practice:
👂 detailed listening  
🧠 identifying speakers

Your task:
✅ decide:
- Daniel (D)
- Pablo (P)

---

## Important vocabulary

| German | English |
|---|---|
| kein Spanisch sprechen | not speak Spanish |
| tanzen | dance |
| Schach spielen | play chess |
| schwimmen | swim |

---

## Helpful strategy

Listen carefully to:
🎧 The voice  
🎧 The language information  
🎧 Hobbies and abilities

---

## Important clue

Ask:
👉 Who learns German?  
👉 Who speaks Spanish?  
👉 Who likes sport?  

This helps identify:
- Daniel
- Pablo

---

## Grammar tip

Notice negation:
❌ kein Spanisch  
❌ nicht gut  
❌ nicht tanzen

Examples:
🗣️ Ich spreche kein Spanisch.  
🗣️ Ich schwimme nicht gut.

---

## Practice tip

Repeat the sentences aloud:

🗣️ Ich spreche kein Spanisch.  
🗣️ Ich tanze nicht.

This improves:
✅ Pronunciation  
✅ Listening  
✅ Negation structures

</details>

---

<details style="background:#f7f2ff;border:1px solid #d9c8f0;border-radius:14px;padding:14px;">
<summary><b>💡 Hint for „Daniel und Pablo …“</b></summary>

In this exercise, you practice:
🎧 understanding the final result of the conversation

Your task:
✅ Decide what Daniel and Pablo do together

---

## Helpful strategy

Listen for:
👂 their final plan

Ask:
👉 What activity do they choose together?

---

## Important vocabulary

| German | English |
|---|---|
| Badminton spielen | play badminton |
| nur Deutsch sprechen | speak only German |

---

## Important clue

A Sprachtandem usually means:
✅ Speaking different languages together

So ask:
👉 Do they only speak German?
👉 Or do they also do activities together?

---

## Listening tip

The answer usually comes:
📌 near the end of the conversation

Listen especially for:
🗣️ „Wir spielen …“

</details>

---

# 2 [GRAMMATIK KOMPAKT] Negation
    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/GRAMMATIK%20KOMPAKT_1080p.mp4?raw=true)
 ## a) Markieren Sie nicht und kein / keine in 1c und ergänzen Sie die Regel.

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

1. 😊[[kein / keine]] verneint Nomen.

2. 😊[[nicht]] am Satzende verneint den ganzen Satz.

3. 😊[[nicht]] verneint auch was / wo / wie / … man etwas macht.

<br>

Beispiele:

• Pablo spricht nicht gut Deutsch.  
• Pablo hört nicht gern Musik.  
• Pablo kommt nicht aus Portugal.

</div>

---

 ## b) Verneinen Sie.

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

1. Pablo kommt aus Portugal.  
~~Pablo kommt nicht aus Portugal.~~

2. Yu spielt gut Gitarre.  
[[Yu spielt nicht gut Gitarre.]]

3. Ein Studium ist ein Hobby.  
[[Ein Studium ist kein Hobby.]]

4. Luis treibt gern Sport.  
[[Luis treibt nicht gern Sport.]]

5. Das ist ein Problem.  
[[Das ist kein Problem.]]

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2a – Negation</b></summary>

In this exercise, you practice:
❌ negation in German

Your task:
✅ Understand the difference between:
- nicht
- kein / keine

---

## Important rule

### 1. kein / keine

Use:
✅ kein / keine

to negate:
📌 nouns

Examples:
- kein Hobby
- keine Musik
- kein Problem

---

### 2. nicht

Use:
✅ nicht

to negate:
- verbs
- adjectives
- places
- adverbs
- complete sentences

Examples:
- nicht gut
- nicht gern
- nicht aus Portugal

---

## Helpful strategy

Ask:
👉 Is it a noun?

YES → use:
✅ kein / keine

NO → use:
✅ nicht

---

## Important examples

| Sentence | Why? |
|---|---|
| Das ist kein Problem. | Problem = noun |
| Pablo spricht nicht gut Deutsch. | gut = adjective/adverb |
| Pablo kommt nicht aus Portugal. | place information |
| Pablo hört nicht gern Musik. | gern = adverb |

---

## Helpful grammar tip

### kein changes like articles

| Gender | Form |
|---|---|
| Maskulin | kein |
| Neutrum | kein |
| Feminin | keine |
| Plural | keine |

---

## Practice tip

Read aloud:

🗣️ Das ist kein Problem.  
🗣️ Ich spiele nicht gut Fußball.  
🗣️ Pablo kommt nicht aus Portugal.

This improves:
✅ Grammar accuracy  
✅ Pronunciation  
✅ Sentence structure

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;">
<summary><b>💡 Hint for 2b – Verneinen Sie</b></summary>

In this exercise, you practice:
❌ making negative sentences

Your task:
✅ Change positive sentences into negative sentences

---

## Helpful strategy

First ask:
👉 What should be negated?

- noun?
→ kein / keine

- adjective / verb / place / adverb?
→ nicht

---

## Important examples

| Positive | Negative |
|---|---|
| Das ist ein Problem. | Das ist kein Problem. |
| Pablo kommt aus Portugal. | Pablo kommt nicht aus Portugal. |
| Luis treibt gern Sport. | Luis treibt nicht gern Sport. |

---

## Helpful clue

Look for:
- ein / eine
→ often changes to:
- kein / keine

Example:
🗣️ ein Hobby → kein Hobby

---

## Important grammar

Usually:
✅ nicht comes before:
- gut
- gern
- places

Examples:
- nicht gut
- nicht gern
- nicht aus Portugal

---

## Practice tip

Say the pairs aloud:

🗣️ Das ist ein Problem.  
🗣️ Das ist kein Problem.

🗣️ Luis treibt gern Sport.  
🗣️ Luis treibt nicht gern Sport.

This improves:
✅ Fluency  
✅ Negation structures  
✅ Speaking confidence

</details>

# 3 Treibst du gern Sport?

 ## b) Welches Wort pro Satz ist betont?
 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_021.mp3?raw=true)

<div style="background:#f8fbff;border:1px solid #d8e6ff;border-radius:18px;padding:18px;line-height:2;">

😊[[Anna]].  

Anna und [[Alex]].  

Anna und Alex [[spielen]].  

Anna und Alex spielen [[nicht]].  

Anna und Alex spielen nicht [[gern]].  

Anna und Alex spielen nicht gern [[Fußball]].  

Anna und Alex spielen nicht gern Fußball im [[Stadion]].  

Anna und Alex spielen lieber [[Volleyball]] im Park.  

Und am liebsten schauen sie Fußball im Stadion!

</div>

---

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3b – Welches Wort ist betont?</b></summary>

In this exercise, you practice:
🎧 sentence stress  
🗣️ pronunciation and intonation

Your task:
✅ Listen carefully  
✅ Identify:
📌 Which word is stressed in each sentence

---

## Important rule

In German:
✅ One word is usually stronger than the others

The stressed word:
- is louder
- is clearer
- gets more attention

---

## Helpful strategy

Listen for:
👂 the strongest word in the sentence

Ask:
👉 Which information is important?

---

## Example

🗣️ Anna und Alex spielen nicht gern Fußball.

Possible stress:
- Anna
- spielen
- nicht
- Fußball

Each stress changes:
📌 meaning and focus

---

## Important clue

The sentence becomes longer step by step.

Notice:
✅ every new sentence stresses a different word

---

## Helpful meaning

| Stressed word | Focus |
|---|---|
| Anna | person |
| spielen | action |
| nicht | negation |
| gern | feeling |
| Fußball | activity |
| Stadion | place |
| Volleyball | contrast |

---

## Listening tip

Listen for:
🎧 Louder pronunciation  
🎧 Longer pronunciation  
🎧 Stronger rhythm

---

## Practice tip

Read aloud and stress the bold word:

🗣️ **Anna**.  
🗣️ Anna und Alex **spielen**.  
🗣️ Anna und Alex spielen nicht **gern** Fußball.  
🗣️ Anna und Alex spielen lieber **Volleyball**.

This improves:
✅ Pronunciation  
✅ Sentence melody  
✅ Speaking confidence

</details>

# 1 Suchen und finden

 ## a) Schwarzes Brett Uni Greifswald Zu welchem Thema passen die Anzeigen? Lesen Sie und ordern Sie zu. Zwei Themen passen nicht.

 ## SCHWARZES BRETT

<div style="background:#d9c2a3;border-radius:24px;padding:28px;border:4px solid #c5ab88;">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:22px;">

<div style="background:#fffef8;border-radius:14px;padding:18px;transform:rotate(-2deg);box-shadow:0 6px 12px rgba(0,0,0,0.12);">

### 1

🎸  
Gitarre, Bass oder Keyboard lernen!  
Musikstudent gibt Kurse (privat oder Gruppe).  

Jonas:  
01577-12341234  
www.DC-AC.io

</div>

<div style="background:#fffef8;border-radius:14px;padding:18px;transform:rotate(2deg);box-shadow:0 6px 12px rgba(0,0,0,0.12);">

### 2

💻  
Wer braucht einen LAPTOP?  

Nur 120 €!  
Der Laptop ist 4 Jahre alt und funktioniert sehr gut!  
Und: Die Tasche ist gratis!

Infos: Fatih  
0171-944882143

</div>

<div style="background:#fffef8;border-radius:14px;padding:18px;transform:rotate(-1deg);box-shadow:0 6px 12px rgba(0,0,0,0.12);">

### 3

🏄‍♂️  
UNISPORT SPEZIAL:  

Testest du gern Sportarten?  
Zum Semesterbeginn sind das Sportprogramm und die Kurse eine Woche gratis!  

Surfen, Beachvolleyball, Yoga, Badminton …

Anmeldung:  
www.unisportGW.de

</div>

<div style="background:#fffef8;border-radius:14px;padding:18px;transform:rotate(2deg);box-shadow:0 6px 12px rgba(0,0,0,0.12);">

### 4

🏄  
Ich suche ein Surfboard!  

Du surfst nicht mehr, aber du hast ein Board?  
Ich kaufe es!

Adriana  
Tel. 01501 98754210

</div>

</div>
</div>

---

<div style="background:#f7fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;line-height:2;">

Filme [[x]]  

Sport 3,[[4]]  

Musik [[1]]  

Sprachen [[x]]  

Technik [[2]]

</div>

---



 ## b) Was passt?

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:2;">

1. Das Surfboard von Arthur ist neu. Er sucht einen Kurs.  
➡ Anzeige [[3]]

2. Yuma hat keinen Computer, aber sie sucht einen Computer, am liebsten einen Laptop.  
➡ Anzeige [[2]]

3. Tom und Finja lernen Gitarre und haben viele Fragen.  
➡ Anzeige [[1]]

</div>

---

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 1a – Schwarzes Brett: Themen zuordnen</b></summary>

In this exercise, you practice:
📖 reading advertisements  
🎓 University vocabulary  
🧩 Matching topics

Your task:
✅ Read the advertisements carefully  
✅ Match them with the correct topic

---

## Important topics

| Thema | Meaning |
|---|---|
| Filme | films |
| Sport | sport |
| Musik | music |
| Sprachen | languages |
| Technik | technology |

---

## Helpful strategy

Ask:
👉 What is the advertisement about?

Look for:
- Music instruments
- Laptops
- Sport activities
- Surfboards

---

## Important vocabulary

| German | English |
|---|---|
| der Laptop | laptop |
| der Kurs | course |
| das Surfboard | surfboard |
| die Anmeldung | registration |
| gratis | free |
| die Tasche | bag |

---

## Helpful clues

🎸 Gitarre / Keyboard  
➡ probably Musik

💻 Laptop  
➡ probably Technik

🏄 Surfen / Yoga / Badminton  
➡ probably Sport

---

## Important note

Two topics:
❌ Do not match any advertisement

So:
✅ Not every topic has an advertisement

---

## Practice tip

Read the advertisements aloud.

This improves:
✅ Reading comprehension  
✅ Vocabulary  
✅ Pronunciation

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;">
<summary><b>💡 Hint for 1b – Was passt?</b></summary>

In this exercise, you practice:
🧠 understanding advertisements  
🎯 matching people with offers

Your task:
✅ Decide:
Which advertisement matches the person?

---

## Helpful strategy

First read:
👤 what the person wants

Then ask:
👉 Which advertisement fits?

---

## Important examples

### Example 1

Arthur:
🏄 Has a surfboard  
🏫 Wants a course

Look for:
✅ Sport courses

---

### Example 2

Yuma:
💻 Needs a computer

Look for:
✅ Laptop advertisement

---

### Example 3

Tom und Finja:
🎸 Learn guitar  
❓ Have questions

Look for:
✅ Music lessons

---

## Helpful vocabulary

| German | English |
|---|---|
| suchen | search for |
| lernen | learn |
| Kurs | course |
| Computer | computer |
| Laptop | laptop |
| Gitarre | guitar |

---

## Reading tip

Underline important information:

Example:
🗣️ „sucht einen Laptop“  
➡ look for:
💻 Laptop advertisement

---

## Practice tip

Read the sentences aloud:

🗣️ Yuma sucht einen Laptop.  
🗣️ Tom und Finja lernen Gitarre.

This improves:
✅ Reading skills  
✅ Vocabulary  
✅ Speaking confidence

</details>


# 2 [GRAMMATIK KOMPAKT]

 ## Bestimmter, unbestimmter Artikel und Negativartikel im Nominativ und Akkusativ

 ### a) Ergänzen Sie die Tabelle.

<div style="background:#f6fbff;border-radius:18px;padding:18px;border:1px solid #dbe9f5;overflow-x:auto;">

|  | Maskulinum (M) | Neutrum (N) | Femininum (F) | Plural (M, N, F) |
|---|---|---|---|---|
| **Nominativ** | ein Computer | ein Surfboard | eine Tasche | [[—]] Kurse |
|  | kein Computer | kein Surfboard | keine Tasche | keine Kurse |
|  | der Computer | [[das]] Surfboard | [[die]] Tasche | [[die]] Kurse |
| **Akkusativ** | [[einen]] Computer | [[ein]] Surfboard | eine Tasche |  Kurse |
|  | ~~keinen~~ Computer | kein Surfboard | keine Tasche | keine Kurse |
|  | den Computer | das Surfboard | die Tasche | die Kurse |

</div>

---


 ## c) Ergänzen Sie die Regeln.

**Maskulinum • Nominativ • Ergänzung**

<div style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:18px;padding:18px;line-height:2;">

1. Das Subjekt (wer? / was?) steht im [[Nominativ]].  
(z. B. Der Computer / Die Kurse / … ist / sind gratis / …)

2. Viele Verben brauchen eine [[Ergänzung]] im Akkusativ (wen? / was?).  
(z. B. Sie / Er hat keinen Computer / sucht einen Kurs / kauft ein Surfboard / braucht einen Laptop.)

3. Akkusativ: Nur das [[Maskulinum]] hat eine andere Endung, der Rest ist wie im Nominativ 😊

</div>

---

 ## d) Ergänzen Sie die passenden Artikel.

<div style="background:#fffdf4;border:1px solid #efe2a9;border-radius:18px;padding:18px;line-height:2;">

### 1.

Haben Sie  Laptops?  

Nein, wir haben k[[eine]] Laptops. /  
Ja, hier sind d[[ie]] Laptops. Sie sind neu.

---

### 2.

Brauche ich e[[in]] Formular?  

Nein, Sie brauchen k[[ein]] Formular. /  
Ja, hier ist d[[as]] Formular. Es ist für die Anmeldung.

---

### 3.

Suchen Sie e[[inen]] Laptop?  

Nein, ich brauche k[[einen]] Laptop.

---

### 4.

Haben Sie e[[ine]] Laptoptasche?  

Ja, d[[ie]] Laptoptasche ist gratis.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2a – Artikel im Nominativ und Akkusativ</b></summary>

In this exercise, you practice:
📚 German articles  
🧠 Nominativ and Akkusativ

Your task:
✅ Complete the article table correctly

---

## Important grammar

### Nominativ
Use for:
✅ Subject (wer? / was?)

Examples:
- der Computer ist neu.
- die Kurse sind gratis.

---

### Akkusativ
Use for:
✅ object (wen? / was?)

Examples:
- Ich suche einen Laptop.
- Sie kauft ein Surfboard.

---

## Important rule

Only:
✅ Maskulinum changes in Akkusativ.

---

## Article overview

| Case | Maskulin | Neutrum | Feminin | Plural |
|---|---|---|---|---|
| Nominativ | ein | ein | eine | — |
| Akkusativ | einen | ein | eine | — |

---

## Negative articles

| Case | Maskulin | Neutrum | Feminin | Plural |
|---|---|---|---|---|
| Nominativ | kein | kein | keine | keine |
| Akkusativ | keinen | kein | keine | keine |

---

## Definite articles

| Case | Maskulin | Neutrum | Feminin | Plural |
|---|---|---|---|---|
| Nominativ | der | das | die | die |
| Akkusativ | den | das | die | die |

---

## Helpful strategy

Ask:
👉 Is the noun:
- subject?
→ Nominativ

or:
- object?
→ Akkusativ

---

## Practice tip

Read aloud:

🗣️ der Computer  
🗣️ den Computer

🗣️ ein Laptop  
🗣️ einen Laptop

This improves:
✅ Grammar understanding  
✅ Article memorization  
✅ Speaking fluency

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 2c – Regeln ergänzen</b></summary>

In this exercise, you practice:
📖 grammar rules

Your task:
✅ Complete the rules with:
- Maskulinum
- Nominativ
- Ergänzung

---

## Helpful strategy

### Step 1

Ask:
👉 Who or what does the action?

This is:
✅ Nominativ

---

### Step 2

Ask:
👉 What does the person have / buy / need / search?

This is:
✅ Akkusativ-Ergänzung

---

## Important verbs

These verbs often need Akkusativ:

- haben
- suchen
- kaufen
- brauchen

Examples:
🗣️ Ich suche einen Kurs.  
🗣️ Sie braucht einen Laptop.

---

## Important grammar rule

Only:
✅ Maskulinum changes in Akkusativ.

Example:
- der Laptop → den Laptop
- ein Laptop → einen Laptop

But:
- das Surfboard → das Surfboard
- die Tasche → die Tasche

stay the same.

---

## Practice tip

Compare:

🗣️ Der Computer ist neu.  
🗣️ Ich kaufe den Computer.

This helps:
✅ Understand cases  
✅ Recognize Akkusativ  
✅ Improve sentence building

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;">
<summary><b>💡 Hint for 2d – Passende Artikel ergänzen</b></summary>

In this exercise, you practice:
🧩 choosing the correct article

Your task:
✅ Complete:
- ein / eine / einen
- kein / keine / keinen
- der / die / das

---

## Helpful strategy

First ask:
👉 Which gender?

- der Laptop → Maskulin
- das Formular → Neutrum
- die Tasche → Feminin
- die Laptops → Plural

---

## Important rule

### Akkusativ Maskulin changes

| Nominativ | Akkusativ |
|---|---|
| ein Laptop | einen Laptop |
| kein Laptop | keinen Laptop |
| der Laptop | den Laptop |

---

## Important clue

Plural:
✅ Always:
- die
- keine

Examples:
- die Laptops
- keine Laptops

---

## Helpful examples

🗣️ Ich brauche ein Formular.  
🗣️ Ich brauche keinen Laptop.  
🗣️ Die Tasche ist gratis.

---

## Practice tip

Read the examples aloud:

🗣️ einen Laptop  
🗣️ keinen Laptop  
🗣️ das Formular  
🗣️ die Laptops

This improves:
✅ Article memorization  
✅ Akkusativ understanding  
✅ Speaking confidence

</details>

---

# 3 Die Anmeldung

 ## a) Sie schreiben eine E-Mail an das Unisport-Team und bekommen eine Antwort.

 ### Welche E-Mail ist formell, welche informell?

<div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;">

<div style="background:#f8fbff;border:1px solid #d9e7ff;border-radius:18px;padding:18px;line-height:1.8;">

📧

Sehr geehrter Herr Bauer,

wie teste ich das Gratis-Sportprogramm?  
Ist die Anmeldung online? Oder haben Sie ein Formular?

Vielen Dank.

Mit freundlichen Grüßen  
Daniel Scherer

<br>

[[x]] formell  
[[ ]] informell

</div>

<div style="background:#eefbea;border:1px solid #cfe7bf;border-radius:18px;padding:18px;line-height:1.8;">

📧

Hallo Daniel,

danke für die Mail. Wir sagen lieber „du“, ok? 😊  
Im Anhang findest du das Formular für die Anmeldung. Bitte ausfüllen und dann scannen und mailen.

Viele Grüße  
Lars

<br>

[[ ]] formell  
[[x]] informell

</div>

</div>

---

 ## b) Sie testen das Gratis-Sportprogramm. Füllen Sie das Formular aus.

<div style="background:#ffffff;border:2px solid #d9d9d9;border-radius:18px;padding:24px;line-height:2;">

# ANMELDUNG: Unisport Spezial

 Ja, ich teste das Gratis-Sportprogramm (eine Woche).

---

Sportart / Sportarten (maximal 3):  
[[Badminton, Yoga, Volleyball]]

Name, Vorname:  
[[Masub Makhdoom]]

Geschlecht:  
* [[x]] m  
* [[ ]] w   
* [[ ]] d

Adresse:  
[[Magdeburg, Deutschland]]

Telefonnummer:  
[[015123456789]]

E-Mail:  
[[masub@example.com]]

Datum, Unterschrift:  
[[15.05.2026 / Masub Makhdoom]]

</div>

---

 ## 4 Vielen Dank und viele Grüße!

 ## Sie mailen das Formular zurück an Lars.

 ### Schreiben Sie eine kurze informelle E-Mail wie in 3a.

<div style="background:#f6fbff;border:1px solid #dbe9f5;border-radius:18px;padding:18px;line-height:1.9;">

📧

Hallo Lars,

danke für deine Mail.  
Im Anhang findest du das Formular für die Anmeldung.

Viele Grüße  
Masub

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3a – Formell oder informell?</b></summary>

In this exercise, you practice:
📧 writing and understanding emails  
🗣️ formal and informal language

Your task:
✅ Decide:
- Formell
- Informell

---

## Important difference

### Formell
Use with:
- Professors
- Teachers
- Offices
- Unknown people

Typical words:
- Sehr geehrte/r …
- Sie / Ihnen
- Mit freundlichen Grüßen

---

### Informell
Use with:
- Friends
- Classmates
- Buddies

Typical words:
- Hallo …
- du / dir
- Viele Grüße

---

## Helpful strategy

Look for:
👉 Sie or du?

If you see:
✅ Sie
➡ formal

If you see:
✅ du
➡ informal

---

## Important vocabulary

| German | English |
|---|---|
| die Anmeldung | registration |
| das Formular | form |
| der Anhang | attachment |
| ausfüllen | fill out |
| scannen | scan |

---

## Helpful clue

Example:
🗣️ „Sehr geehrter Herr Bauer“  
➡ formal

🗣️ „Hallo Daniel“  
➡ informal

---

## Practice tip

Read both emails aloud.

Notice:
✅ Greeting  
✅ Pronouns  
✅ Ending

This improves:
✅ Email writing  
✅ Communication skills  
✅ Formal/informal understanding

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint for 3b – Formular ausfüllen</b></summary>

In this exercise, you practice:
📝 filling out forms

Your task:
✅ Complete the registration form with personal information

---

## Important vocabulary

| German | English |
|---|---|
| die Sportart | sport activity |
| der Vorname | first name |
| der Nachname | family name |
| das Geschlecht | gender |
| die Adresse | address |
| die Telefonnummer | phone number |
| die Unterschrift | signature |

---

## Helpful strategy

Write:
✅ Complete information  
✅ Clear spelling  
✅ Correct format

---

## Important note

You can choose:
🏸 up to three sports

Example:
- Badminton
- Yoga
- Volleyball

---

## Helpful grammar

German forms often use:
- Name, Vorname
- Telefonnummer
- Datum

Be careful with:
✅ Capitalization

---

## Practice tip

Practice saying your information aloud:

🗣️ Ich heiße …  
🗣️ Meine Telefonnummer ist …  
🗣️ Meine E-Mail-Adresse ist …

This improves:
✅ Speaking  
✅ Spelling  
✅ Everyday communication

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;">
<summary><b>💡 Hint for 4 – Informelle E-Mail schreiben</b></summary>

In this exercise, you practice:
📧 writing an informal email

Your task:
✅ Write:
- Greeting
- Short message
- Ending

---

## Structure of an informal email

### 1. Greeting
Examples:
- Hallo Lars,
- Hi Anna,

---

### 2. Message
Examples:
- danke für deine Mail.
- Im Anhang findest du das Formular.

---

### 3. Ending
Examples:
- Viele Grüße
- Bis bald
- Tschüss

---

## Important vocabulary

| German | English |
|---|---|
| die Mail | email |
| der Anhang | attachment |
| das Formular | form |
| zurückmailen | send back by email |

---

## Helpful clue

Because Lars says:
🗣️ „du“

You should also use:
✅ Informal language

---

## Practice tip

Read your email aloud.

Check:
✅ Greeting  
✅ Polite message  
✅ Ending

This improves:
✅ Email writing  
✅ Communication  
✅ German sentence structure

</details>


## Sich begrüßen und sich vorstellen

<div style="background:#f8fbfa;border:1px solid #dbe7e3;border-radius:18px;padding:18px;overflow-x:auto;">

| Thema | Fragen | Antworten |
|---|---|---|
| **Begrüßung** | Hallo! / Guten Morgen / Tag / Abend! | Hallo! / Guten Morgen / Tag / Abend! |
| **Nach Befinden fragen** | Wie geht es dir / Ihnen? | (Danke.) Mir geht es gut / sehr gut. |
| **Name** | Wie heißt du? / Wie heißen Sie? | Ich heiße / Ich bin / Mein Name ist Dana Pak. |
|  | Wie ist dein / Ihr Vorname? | Mein Vorname ist Dana. |
|  | Wie ist dein / Ihr Familienname? | Mein Familienname ist Pak. |
|  | Wie schreibt man das? | P – A – K |
|  | Buchstabieren Sie das bitte. | P – A – K |
| **Herkunft (Land, Stadt)** | Woher kommst du / kommen Sie? | Ich komme aus Kasachstan, aus Almaty. |
| **Sprachen** | Welche Sprache(n) sprichst du / sprechen Sie? | Ich spreche Kasachisch und Deutsch. |
| **Studium** | Was studierst du / studieren Sie? | Ich studiere Medizin / Architektur / … |
|  |  | Ich arbeite schon, ich bin Architekt / … |
| **Beruf** | Was bist du / sind Sie von Beruf? | Ich bin Architekt / Lehrerin / … |
| **Wohnort** | Wo wohnst du / wohnen Sie? | Ich wohne in Marburg. |
| **Telefonnummer** | Wie ist deine / Ihre Telefonnummer? | Meine Telefonnummer ist 06420 – 390809. |
|  | Wie ist deine / Ihre Handynummer? | Meine Handynummer ist 0169 – 2831572. |
| **E-Mail-Adresse** | Wie ist deine / Ihre E-Mail-Adresse? | Meine E-Mail-Adresse ist d.pak@kursdaf.de |
| **Verabschiedung** | Auf Wiedersehen. / Tschüss. | Auf Wiedersehen. / Tschüss. |

</div>

---

 ## Verben im Präsens und Personalpronomen im Nominativ

<div style="background:#f9fcfb;border:1px solid #dce9e5;border-radius:18px;padding:18px;overflow-x:auto;">

|  | kommen | wohnen | studieren | arbeiten | heißen | sprechen | sein |
|---|---|---|---|---|---|---|---|
| ich | komme | wohne | studiere | arbeite | heiße | spreche | bin |
| du | kommst | wohnst | studierst | arbeitest | heißt | sprichst | bist |
| er / sie / es | kommt | wohnt | studiert | arbeitet | heißt | spricht | ist |
| wir | kommen | wohnen | studieren | arbeiten | heißen | sprechen | sind |
| ihr | kommt | wohnt | studiert | arbeitet | heißt | sprecht | seid |
| sie / Sie | kommen | wohnen | studieren | arbeiten | heißen | sprechen | sind |

</div>

---

 ## Wortstellung in W-Fragen, Ja/Nein-Fragen und Antworten

<div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;">

<div style="background:#eef8f6;border:1px solid #d5ebe5;border-radius:18px;padding:16px;">

 ## W-Fragen

| Position 1 | Position 2 |  |
|---|---|---|
| Woher | kommen | Sie? |
| Wie | heißen | Sie? |

</div>

<div style="background:#f8fbff;border:1px solid #dbe6f4;border-radius:18px;padding:16px;">

## Antworten / Aussagesätze

| Position 1 | Position 2 |  |
|---|---|---|
| Ich | komme | aus Kasachstan. |
| Ich | heiße | Dana Pak. |

</div>

</div>

---

<div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;">

<div style="background:#fff9f2;border:1px solid #f1dfc5;border-radius:18px;padding:16px;">

## Ja/Nein-Fragen

| Position 1 | Position 2 |  |
|---|---|---|
| Studierst | du | auch Biologie? |
| Kommen | Sie | morgen zum Kurs? |

</div>

<div style="background:#f7fcf5;border:1px solid #dcebd5;border-radius:18px;padding:16px;">

## Antworten / Aussagesätze

|  | Position 1 | Position 2 |  |
|---|---|---|---|
| Nein, | ich | studiere | Chemie. |
| Ja, | ich | komme | natürlich. |

</div>

</div>

# ✅ Lösungen – Kapitel 2: Studium und Freizeit

---

## 1 Uni und Freizeit

 ## 1a) Was ist das?

1. die Filme  
2. das Keyboard  
3. die Bücher  
4. die Universität  
5. der Computer  
6. das Formular  
7. der Ball  
8. der Sport  
9. die Musik  
10. das Schach  
11. der Laptop  
12. die Salsa  

 ## 1b) Verben zuordnen

1. Bücher lesen  
2. Filme sehen  
3. Musik hören  
4. Salsa tanzen  
5. Sport treiben  
6. Ball / Keyboard / Schach spielen  
7. ein Formular ausfüllen  
8. einen Computer / Laptop haben  
9. die Universität zeigen  

---

## 1 Sei ein Buddy – ein Programm für Erstsemester

 ## 1a) Wer ist Daniel?

Daniel ist:  
b. Buddy

 ## 1b) Sätze zuordnen

1. Daniel arbeitet → d  
2. Der Buddy kennt → c  
3. Die Erstsemester → a  
4. Daniel findet, der Job → b  

---

## 2 Grammatik kompakt: Artikel im Nominativ

 ## 2a) Tabelle

* Unbestimmter Artikel:  
ein Job / ein Studium / eine Universität / — Sprachen

* Negativartikel:  
kein Job / kein Studium / keine Universität / keine Sprachen

* Bestimmter Artikel:  
der Job / das Studium / die Universität / die Sprachen

* Personalpronomen:  
Er / Es / Sie / Sie

---

 ## 2b) Welcher Artikel passt?

1. Ist das ein Student?  
Nein, das ist kein Student, das ist ein Professor. Der Professor ist neu.

2. Ist das ein Erstsemester?  
Nein, das ist kein Erstsemester. Das ist ein Buddy. Der Buddy ist sehr nett.

3. Ist das eine Professorin?  
Nein, das ist keine Professorin. Das ist eine Lehrerin, die Deutschlehrerin.

4. Sind das Lehrerinnen?  
Nein, das sind keine Lehrerinnen, das sind Studentinnen. Die Studentinnen sind neu an der Uni.

---

 ## 2c) Personalpronomen

1. Es / es  
2. Er / sie  
3. Er / sie  

---


## 1 Endlich Freizeit!

 ## 1a) Sprachtandem

1. Daniel spricht Deutsch und lernt Spanisch.  
2. Pablo spricht Spanisch und lernt Deutsch.

 ## 1b) Freizeitaktivitäten

Richtig sind:

- Musik hören  
- Sport treiben / machen  
- Schach spielen  
- Badminton spielen  

 ## 1c) Daniel oder Pablo?

* a. D — Ich spreche kein Spanisch.  
* b. P — Ich tanze nicht.  
* c. D — Ich spiele kein Schach.  
* d. P — Ich schwimme nicht gut.

* Daniel und Pablo:  
a. spielen Badminton.

---

## 2 Grammatik kompakt: Negation

 ## 2a) Regel

1. kein / keine verneint Nomen.  
2. nicht am Satzende verneint den ganzen Satz.  
3. nicht verneint auch was / wo / wie man etwas macht.

 ## 2b) Verneinen Sie

1. Pablo kommt nicht aus Portugal.  
2. Yu spielt nicht gut Gitarre.  
3. Ein Studium ist kein Hobby.  
4. Luis treibt nicht gern Sport.  
5. Das ist kein Problem.

---

## 3 Treibst du gern Sport?

 ## 3b) Betonung

1. Anna  
2. Alex  
3. spielen  
4. nicht  
5. gern  
6. Fußball  
7. Stadion  
8. Volleyball  

---

## 1 Suchen und finden

 ## 1a) Schwarzes Brett

* Filme → x  
* Sport → 3, 4  
* Musik → 1  
* Sprachen → x  
* Technik → 2  

 ## 1b) Was passt?

1. Anzeige 3  
2. Anzeige 2  
3. Anzeige 1  

---

## 2 Grammatik kompakt: Nominativ und Akkusativ

 ## 2a) Tabelle

__Nominativ: __ 

* ein Computer / ein Surfboard / eine Tasche / — Kurse  
* kein Computer / kein Surfboard / keine Tasche / keine Kurse  
* der Computer / das Surfboard / die Tasche / die Kurse  

~~__Akkusativ:  __~~

* einen Computer / ein Surfboard / eine Tasche / — Kurse  
* keinen Computer / kein Surfboard / keine Tasche / keine Kurse  
* den Computer / das Surfboard / die Tasche / die Kurse  

 ## 2c) Regeln

1. Nominativ  
2. Ergänzung  
3. Maskulinum  

 ## 2d) Passende Artikel

1. keine / die  
2. ein / kein / das  
3. einen / keinen  
4. eine / die  

---

## 3 Die Anmeldung

 ## 3a) Formell oder informell?

* E-Mail 1: formell  
* E-Mail 2: informell  

 ## 3b) Formular

* Sportart / Sportarten: Badminton, Yoga, Volleyball  
* Name, Vorname: Masub Makhdoom  
* Geschlecht: m  
* Adresse: Magdeburg, Deutschland  
* Telefonnummer: 015123456789  
* E-Mail: masub@example.com  
* Datum, Unterschrift: 15.05.2026 / Masub Makhdoom  

---

 # 4 Vielen Dank und viele Grüße!

Hallo Lars,

danke für deine Mail.  
Im Anhang findest du das Formular für die Anmeldung.

Viele Grüße  
Masub
