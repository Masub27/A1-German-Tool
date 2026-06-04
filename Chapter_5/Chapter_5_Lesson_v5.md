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



# Kapitel 5

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">

<defs>
  <linearGradient id="bg5" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#f4f8ee"/>
    <stop offset="100%" stop-color="#ffffff"/>
  </linearGradient>

  <linearGradient id="panel5" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#ffffff" stop-opacity="0.98"/>
    <stop offset="100%" stop-color="#f8fbf5" stop-opacity="0.96"/>
  </linearGradient>

  <linearGradient id="accent5" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#8fa31f"/>
    <stop offset="100%" stop-color="#b9c94a"/>
  </linearGradient>

  <filter id="shadow5" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="0" dy="14" stdDeviation="16" flood-color="#7d8b2b" flood-opacity="0.18"/>
  </filter>

  <style><![CDATA[
    .chip5{font-family:Georgia,serif;font-size:24px;font-weight:700;fill:#ffffff;}
    .title5{font-family:Georgia,serif;font-size:64px;font-weight:700;fill:#6f7f1f;}
    .subtitle5{font-family:Arial,sans-serif;font-size:24px;fill:#5b6450;}
    .head5{font-family:Georgia,serif;font-size:30px;font-weight:700;fill:#7a8626;}
    .bullet5{font-family:Arial,sans-serif;font-size:21px;fill:#4e5648;}
    .footer5{font-family:Arial,sans-serif;font-size:20px;fill:#4e5648;}
    .iconText{font-family:Arial,sans-serif;font-size:58px;font-weight:700;fill:#8fa31f;opacity:.13;}
  ]]></style>
</defs>

<rect width="1600" height="900" fill="url(#bg5)"/>

<!-- soft decorative circles -->
<circle cx="1350" cy="120" r="120" fill="#dfe9b4" opacity="0.45"/>
<circle cx="1450" cy="760" r="170" fill="#eef4d4" opacity="0.65"/>
<circle cx="120" cy="760" r="150" fill="#e8f0c7" opacity="0.45"/>

<!-- main panel -->
<g filter="url(#shadow5)">
  <rect x="90" y="90" width="1420" height="720" rx="34" fill="url(#panel5)" stroke="#d8e3c2"/>
</g>

<!-- chip -->
<rect x="130" y="125" width="210" height="54" rx="16" fill="url(#accent5)"/>
<text x="235" y="160" text-anchor="middle" class="chip5">KAPITEL 5</text>

<!-- title -->
<text x="130" y="265" class="title5">Familie</text>
<text x="130" y="330" class="title5">und Freunde</text>

<text x="130" y="375" class="subtitle5">
Deutsch A1.1 • Personen vorstellen, beschreiben und über Beziehungen sprechen
</text>

<!-- decorative family icon -->
<g transform="translate(1120 145)">
  <circle cx="95" cy="65" r="34" fill="#d8e8a1" stroke="#9fb522" stroke-width="5"/>
  <circle cx="35" cy="95" r="28" fill="#e8f3c4" stroke="#9fb522" stroke-width="5"/>
  <circle cx="155" cy="95" r="28" fill="#e8f3c4" stroke="#9fb522" stroke-width="5"/>
  <circle cx="95" cy="150" r="24" fill="#f5f9e2" stroke="#9fb522" stroke-width="5"/>
  <path d="M95 100 L95 126" stroke="#9fb522" stroke-width="6" stroke-linecap="round"/>
  <path d="M60 110 C80 125 110 125 135 110" fill="none" stroke="#9fb522" stroke-width="6" stroke-linecap="round"/>
  <text x="95" y="230" text-anchor="middle" style="font-family:Arial;font-size:26px;font-weight:700;fill:#6f7f1f;">Familie</text>
</g>

<!-- Cards -->
<rect x="130" y="430" width="400" height="260" rx="24" fill="#f6f9f1" stroke="#dfe8ce"/>
<text x="160" y="480" class="head5">Wortschatz</text>
<text x="160" y="520" class="bullet5">• Familie und Verwandtschaft</text>
<text x="160" y="552" class="bullet5">• Freunde und Kontakte</text>
<text x="160" y="584" class="bullet5">• Aussehen und Charakter</text>
<text x="160" y="616" class="bullet5">• Beziehungen beschreiben</text>

<rect x="600" y="430" width="400" height="260" rx="24" fill="#f8faf4" stroke="#dfe8ce"/>
<text x="630" y="480" class="head5">Kommunikation</text>
<text x="630" y="520" class="bullet5">• Familie vorstellen</text>
<text x="630" y="552" class="bullet5">• Personen beschreiben</text>
<text x="630" y="584" class="bullet5">• Meinungen äußern</text>
<text x="630" y="616" class="bullet5">• über Freundschaft sprechen</text>

<rect x="1070" y="430" width="400" height="260" rx="24" fill="#f6f9f1" stroke="#dfe8ce"/>
<text x="1100" y="480" class="head5">Grammatik</text>
<text x="1100" y="520" class="bullet5">• Possessivartikel</text>
<text x="1100" y="552" class="bullet5">• Nominativ und Akkusativ</text>
<text x="1100" y="584" class="bullet5">• Adjektive prädikativ/adverbial</text>
<text x="1100" y="616" class="bullet5">• Indefinitpronomen</text>

<!-- bottom line -->
<line x1="130" y1="745" x2="1470" y2="745" stroke="#d8e3c2" stroke-width="2"/>

<text x="130" y="785" class="footer5">Deutsch A1.1</text>
<text x="1470" y="785" text-anchor="end" class="footer5">KursDaF • Kapitel 5</text>

</svg>

# 🤖 Kapitel 5 Chatbot 

<div id="c5bot" style="background:linear-gradient(135deg,#f7fbff,#fffdf5);border:3px solid #9fb522;border-radius:24px;padding:24px;box-shadow:0 10px 28px rgba(0,0,0,.14);font-family:Arial,sans-serif;">

<h2 style="margin-top:0;color:#6f7f1f;">🤖 Kapitel 5 Lernbot – Familie und Freunde</h2>

<div id="c5-output" style="background:white;border-left:8px solid #9fb522;border-radius:16px;padding:18px;min-height:180px;max-height:420px;overflow:auto;line-height:1.7;margin-bottom:14px;">
<b>Bot:</b> Hallo! Ask me about Kapitel 5: Familie, Geburtstag, Possessivartikel, Adjektive, Kontakte/Freunde und Indefinitpronomen 😊
</div>

<div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:18px;">
<input id="c5-input" placeholder="Example: family tree answers" style="flex:1;min-width:260px;padding:13px;border:2px solid #9fb522;border-radius:12px;font-size:16px;">
<button id="c5-ask" type="button" style="padding:13px 20px;border-radius:12px;border:none;background:#9fb522;color:white;font-weight:bold;cursor:pointer;">Ask</button>
<button id="c5-clear" type="button" style="padding:13px 20px;border-radius:12px;border:1px solid #9fb522;background:white;color:#6f8120;font-weight:bold;cursor:pointer;">Clear</button>
</div>

<h3 style="color:#6f7f1f;">💡 Quick Questions</h3>
<div id="c5-quick" style="display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:10px;"></div>

</div>

<script>
void setTimeout(function(){

  const output = document.getElementById("c5-output");
  const input = document.getElementById("c5-input");
  const askBtn = document.getElementById("c5-ask");
  const clearBtn = document.getElementById("c5-clear");
  const quickBox = document.getElementById("c5-quick");

  const questions = [
    "Chapter 5 overview",
    "Family tree answers",
    "Birthday listening answers",
    "Who is coming answers",
    "Possessive nominative table",
    "Verena and Aaron answers",
    "Possessive accusative table",
    "Possessive accusative rules",
    "Party picture answers",
    "Description listening answers",
    "Adjectives answers",
    "Adjectives rules",
    "Contacts or friends answers",
    "True false friends answers",
    "Indefinite pronouns examples",
    "Indefinite pronouns definitions",
    "Indefinite pronouns exercise answers",
    "Family vocabulary",
    "Describe people vocabulary",
    "Speaking practice"
  ];

  function cleanText(text){
    return String(text || "")
      .replace(/4938/g, "")
      .replace(/229/g, "")
      .replace(/\s+/g, " ")
      .trim();
  }

  function normalize(text){
    return cleanText(text)
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
           "<b style='color:#2768b3;font-size:17px;'>" + title + "</b><br><br>" + body + "</div>";
  }

  function answer(question){
    const q = normalize(question);

    if(hasAny(q, ["overview", "chapter 5", "kapitel 5", "about"])){
      return card("Kapitel 5 Overview",
        "Kapitel 5 heißt <b>Familie und Freunde</b>.<br><br>" +
        "Themen:<br>" +
        "• Familie und Verwandtschaft<br>" +
        "• Geburtstag und Gäste<br>" +
        "• Possessivartikel im Nominativ und Akkusativ<br>" +
        "• Personen beschreiben<br>" +
        "• Adjektive prädikativ und adverbial<br>" +
        "• Kontakte oder Freunde<br>" +
        "• Indefinitpronomen: man, alles, viel, etwas, nichts.");
    }

    if(hasAny(q, ["family tree answers", "familienstammbaum", "wer ist wer", "namen ergänzen", "names answers"])){
      return card("Familienstammbaum – Answers",
        "Die Mutter von Julian heißt <b>Verena</b>.<br>" +
        "Der Vater von Julian heißt <b>Alexander</b>.<br>" +
        "<b>Carla</b> ist die Schwester von Julian.<br>" +
        "Carla hat einen Freund. Er heißt <b>Jannis</b>.<br>" +
        "Verena hat eine Schwester. Sie heißt <b>Sonja</b>.<br>" +
        "Die Tochter von Sonja heißt <b>Susanne</b>.<br>" +
        "Der Sohn von Sonja heißt <b>Aaron</b>.<br>" +
        "Der Vater von Aaron und Susanne heißt <b>Matthias</b>.<br>" +
        "Der Bruder von Verena und Sonja heißt <b>Albert</b>.<br>" +
        "<b>Sonja</b> ist die Tante von Julian und Carla.<br>" +
        "<b>Susanne</b> ist die Nichte von Verena und Albert.<br>" +
        "Der Großvater heißt <b>Horst</b>.<br>" +
        "Die Großmutter heißt <b>Renate</b>.");
    }

    if(hasAny(q, ["birthday listening", "geburtstag", "meine mutter feiert", "teil 1 answers"])){
      return card("Meine Mutter feiert Geburtstag – Answers",
        "1. Die Mutter von <b>Julian</b> feiert Geburtstag.<br>" +
        "2. Der Gast Nummer 1 ist <b>der Hund</b>.");
    }

    if(hasAny(q, ["who is coming", "wer kommt", "kommt answers", "gäste answers"])){
      return card("Wer kommt? – Answers",
        "1. <b>Unsere Familie</b>.<br>" +
        "2. Meine Schwester, Carla, und <b>ihr Freund</b>.<br>" +
        "3. Mein Cousin, Aaron, und <b>seine Freundin</b>.<br>" +
        "4. <b>Meine Großeltern</b>.<br>" +
        "5. <b>Unser Hund</b>.");
    }

    if(hasAny(q, ["possessive nominative", "nominative table", "possessivartikel nominativ", "nominativ"])){
      return card("Possessivartikel im Nominativ",
        "Nominativ = subject form.<br><br>" +
        "<b>ich</b>: mein Vater / mein Buch / meine Mutter / meine Eltern<br>" +
        "<b>du</b>: dein Vater / dein Buch / deine Mutter / deine Eltern<br>" +
        "<b>er</b>: sein Vater / sein Buch / seine Mutter / seine Eltern<br>" +
        "<b>sie</b>: ihr Vater / ihr Buch / ihre Mutter / ihre Eltern<br>" +
        "<b>es</b>: sein Vater / sein Buch / seine Mutter / seine Eltern<br>" +
        "<b>wir</b>: unser Vater / unser Buch / unsere Mutter / unsere Eltern<br>" +
        "<b>ihr</b>: euer Vater / euer Buch / eure Mutter / eure Eltern<br>" +
        "<b>sie/Sie</b>: ihr/Ihr Vater / ihr/Ihr Buch / ihre/Ihre Mutter / ihre/Ihre Eltern.");
    }

    if(hasAny(q, ["verena and aaron", "verena", "aaron", "wer passt zu verena"])){
      return card("Verena und Aaron – Answers",
        "a. <b>Seine</b> Schwester ist Susanne. → Aaron<br>" +
        "b. <b>Ihr</b> Bruder ist Albert. → Verena<br>" +
        "c. <b>Seine</b> Eltern sind Sonja und Matthias. → Aaron<br>" +
        "d. <b>Sein</b> Cousin ist Julian. → Aaron<br>" +
        "e. <b>Ihre</b> Eltern sind Renate und Horst. → Verena<br>" +
        "f. <b>Ihre</b> Tochter ist Carla. → Verena");
    }

    if(hasAny(q, ["possessive accusative", "accusative table", "akkusativ table", "possessivartikel akkusativ", "akkusativ"])){
      return card("Possessivartikel im Akkusativ",
        "Akkusativ = object form after verbs like sehen, haben, fragen, mögen.<br><br>" +
        "<b>ich</b>: meinen Vater / mein Buch / meine Mutter / meine Eltern<br>" +
        "<b>du</b>: deinen Vater / dein Buch / deine Mutter / deine Eltern<br>" +
        "<b>er</b>: seinen Vater / sein Buch / seine Mutter / seine Eltern<br>" +
        "<b>sie</b>: ihren Vater / ihr Buch / ihre Mutter / ihre Eltern<br>" +
        "<b>es</b>: seinen Vater / sein Buch / seine Mutter / seine Eltern<br>" +
        "<b>wir</b>: unseren Vater / unser Buch / unsere Mutter / unsere Eltern<br>" +
        "<b>ihr</b>: euren Vater / euer Buch / eure Mutter / eure Eltern<br>" +
        "<b>sie/Sie</b>: ihren/Ihren Vater / ihr/Ihr Buch / ihre/Ihre Mutter / ihre/Ihre Eltern.");
    }

    if(hasAny(q, ["accusative rules", "akkusativ rules", "endungen", "mein meinen"])){
      return card("Akkusativ Rules",
        "1. Der Possessivartikel hat die gleichen <b>Endungen</b> wie der unbestimmte Artikel und der Negativartikel.<br><br>" +
        "2. Im Akkusativ hat nur <b>Maskulinum</b> eine andere Endung: <b>-en</b>.<br><br>" +
        "Examples:<br>" +
        "Nominativ: mein Vater<br>" +
        "Akkusativ: meinen Vater<br><br>" +
        "But:<br>meine Mutter, mein Buch, meine Eltern stay the same.");
    }

    if(hasAny(q, ["party picture", "bild personen", "person a", "person b", "party answers"])){
      return card("Geburtstagsfeier – Picture Answers",
        "A → <b>Carla</b><br>" +
        "B → <b>Horst</b><br>" +
        "C → <b>der Hund</b><br>" +
        "D → <b>Susanne</b><br>" +
        "E → <b>Jannis</b><br><br>" +
        "Reihenfolge im Gespräch:<br>" +
        "1. Carla<br>2. Jannis<br>3. Horst<br>4. Susanne<br>5. Hund");
    }

    if(hasAny(q, ["description listening", "was hören sie", "beschreibung answers", "carla ist", "hund ist"])){
      return card("Beschreibung – Listening Answers",
        "1. Carla ist <b>groß und schlank</b>.<br>" +
        "2. Ihre Haare sind <b>blond und lang</b>.<br>" +
        "3. Davide findet, Carla sieht <b>super aus</b>.<br>" +
        "4. Einen Freund haben heißt auf Deutsch <b>verliebt sein</b>.<br>" +
        "5. Davide findet, Jannis sieht <b>cool aus</b>.<br>" +
        "6. Julian meint, sein Opa sieht <b>noch sehr jung aus</b>.<br>" +
        "7. Der Opa von Julian ist <b>noch sehr fit</b>.<br>" +
        "8. Die Haare von Cousine Susanne sind <b>braun und lockig</b>.<br>" +
        "9. Julian findet, Susanne ist <b>intelligent</b>.<br>" +
        "10. Der Hund ist <b>dick, aber süß</b>.");
    }

    if(hasAny(q, ["adjectives answers", "adjektive answers", "markieren sie die adjektive"])){
      return card("Adjektive – Answers",
        "1. Meine Schwester ist sehr <b>schlank</b>.<br>" +
        "2. Meine Cousine kann sehr <b>schnell</b> rechnen.<br>" +
        "3. Die Haare von Susanne sind <b>lockig</b>.<br>" +
        "4. Mein Opa kocht sehr <b>gut</b>.<br>" +
        "5. Euer Hund sieht sehr <b>witzig</b> aus.");
    }

    if(hasAny(q, ["adjectives rules", "prädikativ", "praedikativ", "adverbial", "beschreibt nomen", "beschreibt verb"])){
      return card("Adjektive – prädikativ und adverbial",
        "<b>Beschreibt Nomen:</b><br>" +
        "1. schlank → beschreibt die Schwester<br>" +
        "3. lockig → beschreibt die Haare<br><br>" +
        "<b>Beschreibt Verb:</b><br>" +
        "2. schnell → beschreibt rechnen<br>" +
        "4. gut → beschreibt kochen<br>" +
        "5. witzig → in this exercise with <i>sieht ... aus</i><br><br>" +
        "Rules:<br>" +
        "1. sein definiert <b>eine Person oder einen Gegenstand</b>.<br>" +
        "2. kochen, rechnen, essen drücken <b>eine Handlung oder einen Zustand</b> aus.<br>" +
        "3. Die <b>Form</b> von Adjektiven ist prädikativ und adverbial identisch.");
    }

    if(hasAny(q, ["kontakte oder freunde", "contacts friends", "freunde machen viel gemeinsam", "friends answers"])){
      return card("Kontakte oder Freunde – Answers",
        "Für wen ist wichtig: <b>Freunde machen viel gemeinsam</b>?<br><br>" +
        "Correct:<br>" +
        "• <b>Alexandra</b><br>" +
        "• <b>Tim</b><br><br>" +
        "Reason:<br>" +
        "Alexandra says they often cook together.<br>" +
        "Tim says: Wir machen viel zusammen, das finde ich wichtig.");
    }

    if(hasAny(q, ["true false", "richtig falsch", "r f", "true false friends"])){
      return card("Kontakte oder Freunde – richtig/falsch",
        "1. Dominik findet, Freunde müssen offen sein. → <b>richtig</b><br>" +
        "2. Alexandra und ihre Freunde kochen oft zusammen. → <b>richtig</b><br>" +
        "3. Für Davide ist nur der Spaß wichtig. → <b>falsch</b><br>" +
        "4. Leon denkt, Freunde sind automatisch immer da. → <b>falsch</b><br>" +
        "5. Für Nina muss Freundschaft perfekt sein. → <b>falsch</b><br>" +
        "6. Tim findet, Kontakte im Internet sind keine Freunde. → <b>richtig</b>");
    }

    if(hasAny(q, ["indefinite pronouns examples", "indefinitpronomen examples", "man alles viel etwas nichts examples"])){
      return card("Indefinitpronomen – Examples",
        "<b>man</b>: Man muss viel zusammen machen.<br>" +
        "<b>alles</b>: Alles hat seinen Preis.<br>" +
        "<b>viel</b>: So kann man auch für das Leben viel lernen.<br>" +
        "<b>etwas</b>: Man muss für eine Freundschaft etwas tun.<br>" +
        "<b>nichts</b>: Nichts ist selbstverständlich.");
    }

    if(hasAny(q, ["indefinite pronouns definitions", "definitions", "wann benutzt man", "definitionen"])){
      return card("Indefinitpronomen – Definitions",
        "<b>alles</b> → 100% Sachen, Gegenteil von nichts<br>" +
        "<b>man</b> → generell für Personen, Personen sind nicht bekannt<br>" +
        "<b>nichts</b> → Null, Gegenteil von alles<br>" +
        "<b>viel</b> → die Menge ist groß<br>" +
        "<b>etwas</b> → die Menge ist klein; für Sachen/Gegenstände");
    }

    if(hasAny(q, ["indefinite pronouns exercise", "was passt", "viel alles etwas nichts man"])){
      return card("Indefinitpronomen – Exercise Answers",
        "1. Ich muss noch <b>viel</b> lernen.<br>" +
        "2. Ist <b>alles</b> klar?<br>" +
        "3. Ich habe nicht viel, aber <b>etwas</b> Hunger.<br>" +
        "4. Heute habe ich keine Lust. Ich mache <b>nichts</b>.<br>" +
        "5. Die Hausaufgabe ist perfekt, <b>alles</b> ist richtig.<br>" +
        "6. Heute bekommt <b>man</b> ein Getränk gratis.");
    }

    if(hasAny(q, ["family vocabulary", "vocabulary family", "verwandtschaft vocabulary"])){
      return card("Family Vocabulary",
        "der Vater, die Mutter, die Eltern, der Bruder, die Schwester, der Großvater, die Großmutter, die Großeltern, der Onkel, die Tante, der Cousin, die Cousine, der Neffe, die Nichte, der Enkel, die Enkelin, verheiratet, geschieden, ledig.");
    }

    if(hasAny(q, ["describe people vocabulary", "aussehen vocabulary", "character vocabulary"])){
      return card("Describe People – Vocabulary",
        "Aussehen:<br>groß, klein, schlank, dick, blond, braun, lockig, kurz, lang, fit, jung, alt.<br><br>" +
        "Charakter / Meinung:<br>sympathisch, intelligent, witzig, nett, loyal, ehrlich, offen, respektvoll, aufmerksam.");
    }

    if(hasAny(q, ["speaking practice", "conversation", "dialogue"])){
      return card("Speaking Practice",
        "A: Wer ist das?<br>" +
        "B: Das ist meine Mutter. Sie heißt Sara.<br>" +
        "A: Wie sieht sie aus?<br>" +
        "B: Sie ist groß. Ihre Haare sind braun und lang.<br>" +
        "A: Wie ist sie?<br>" +
        "B: Sie ist nett und hilfsbereit.<br><br>" +
        "Now change: Mutter → Vater / Schwester / Bruder / Freundin.");
    }

    return card("Question not found",
      "Ask about:<br>" +
      "• family tree answers<br>" +
      "• birthday listening answers<br>" +
      "• possessive nominative / accusative<br>" +
      "• party picture answers<br>" +
      "• adjectives answers<br>" +
      "• contacts or friends answers<br>" +
      "• indefinite pronouns answers");
  }

  function ask(q){
    const question = cleanText(q || input.value);
    if(!question) return;

    output.innerHTML += "<br><br><b>You:</b> " + question;
    output.innerHTML += "<br><b>Bot:</b> " + answer(question);
    input.value = "";
    output.scrollTop = output.scrollHeight;
  }

  askBtn.addEventListener("click", function(){ ask(); });

  clearBtn.addEventListener("click", function(){
    output.innerHTML = "<b>Bot:</b> Hallo! Ask me about Kapitel 5 😊";
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
    btn.textContent = cleanText(q);
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

# 👨‍👩‍👧 Familie und Verwandtschaft



 ## 1 Familie und Verwandtschaft

 ## a) Wer ist wer? Schreiben Sie die Namen in den Text. Hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_035.mp3?raw=true)

 ## 🌳 Familienstammbaum von Julian

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_5/chapter_5_1.jpeg?raw=true)

 ## ✍️ Text – Namen ergänzen

<div style="background:#ffffff;border:2px solid #dbe7ff;border-radius:22px;padding:22px;line-height:2;font-size:19px;">

Das ist Julian. Er ist 20 Jahre alt. Die Mutter von Julian heißt [[Verena]]. Der Vater von Julian, also der Mann von Verena, heißt [[Alexander]].[[Carla]] ist die Schwester von Julian. Sie hat einen Freund. Er heißt [[Jannis]] und lebt mit Carla zusammen.

Verena hat eine Schwester, sie heißt [[Sonja]]. Sie hat zwei Kinder, eine Tochter und einen Sohn. Die Tochter von Sonja heißt [[Susanne]], der Sohn von Sonja heißt [[Aaron]]. Aaron ist der Cousin und Susanne ist die Cousine von [[Julian]] und Carla.

Der Vater von Aaron und Susanne heißt [[Matthias]]. Er und Sonja sind nicht mehr verheiratet, sie sind geschieden.

Verena und Sonja haben auch einen Bruder, er heißt [[Albert]]. Er ist nicht verheiratet, er ist ledig.[[Sonja]] ist die Tante und Albert ist der Onkel von Julian und Carla. [[Susanne]] ist die Nichte und Aaron ist der Neffe von Verena und Albert.

Der Großvater von Julian heißt [[Horst]]. Die Frau von Horst, also die Großmutter von Julian, heißt [[Renate]]. Sie haben vier Enkel: Julian, Carla, Susanne und Aaron.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you practice <b>family relationships and family vocabulary in German</b>.

You need to read the family tree and complete the text with the correct names.

---

### Helpful vocabulary

- <b>die Mutter</b> = mother  
- <b>der Vater</b> = father  
- <b>die Schwester</b> = sister  
- <b>der Bruder</b> = brother  
- <b>der Cousin</b> = male cousin  
- <b>die Cousine</b> = female cousin  
- <b>die Tante</b> = aunt  
- <b>der Onkel</b> = uncle  
- <b>der Großvater</b> = grandfather  
- <b>die Großmutter</b> = grandmother  
- <b>der Neffe</b> = nephew  
- <b>die Nichte</b> = niece  

---

### Strategy

1️⃣ First, study the family tree carefully.  

2️⃣ Read the text sentence by sentence.  

3️⃣ Look for family relationship words like:
- Mother
- Father
- Sister
- Cousin
- Aunt
- Grandfather

4️⃣ Find the correct person in the family tree.

5️⃣ Write the correct name in the blank.

---

### Example

👉 “Die Mutter von Julian heißt …”

You must look for:
- Julian’s mother  
- then write her name.

---

🎧 Finally, listen to the audio and check your answers.

</details>

---

---

# 🎂 Meine Mutter feiert Geburtstag



 ## 1 🎉 Meine Mutter feiert Geburtstag

<div style="display:grid;grid-template-columns:1.2fr .8fr;gap:24px;align-items:center;">

<div>

 ## 🎧 a) Hören Sie Teil 1 vom Gespräch.

 ## Was ist richtig? Kreuzen Sie an.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_036.mp3?raw=true)

</div>

<div style="background:white;border-radius:20px;padding:16px;text-align:center;border:2px solid #ffd3b6;">

<div style="font-size:80px;">🎂</div>

<div style="font-size:22px;font-weight:700;color:#d26b3d;">
HAPPY Birthday 
</div>

</div>

</div>

---

<div style="display:grid;grid-template-columns:1fr 1fr;gap:22px;">

<div style="background:#ffffff;border:2px solid #dce8ff;border-radius:20px;padding:22px;line-height:2;">

### 1.

Die Mutter von

[[ ]] a. Davide  
[[x]] b. Julian

feiert Geburtstag.

</div>

<div style="background:#ffffff;border:2px solid #dce8ff;border-radius:20px;padding:22px;line-height:2;">

### 2.

Der Gast Nummer 1 ist

[[x]] a. der Hund  
[[ ]] b. Aaron

</div>

</div>

---

 ## 👨‍👩‍👧 b) Wer kommt?Hören Sie Teil 1 vom Gespräch noch einmal und kreuzen Sie an.

<div style="background:#ffffff;border:2px solid #dbe7ff;border-radius:22px;padding:24px;line-height:2;">

### 1.

[[x]] a. Unsere Familie.  
[[ ]] b. Eure Verwandtschaft.

---

### 2.

Meine Schwester, Carla, und

[[x]] a. ihr Freund.  
[[ ]] b. ihre Freundin.

---

### 3.

Mein Cousin, Aaron, und

[[x]] a. seine Freundin.  
[[ ]] b. sein Freund.

---

### 4.

[[ ]] a. Meine Eltern.  
[[x]] b. Meine Großeltern.

---

### 5.

[[ ]] a. Mein Hund.  
[[x]] b. Unser Hund.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you practice <b>listening comprehension about a birthday party and family members</b>.

You will hear Julian talking about his mother’s birthday and the guests for the party.

---

### Helpful vocabulary

- <b>Geburtstag feiern</b> = to celebrate a birthday  
- <b>der Gast</b> = guest  
- <b>die Familie</b> = family  
- <b>die Großeltern</b> = grandparents  
- <b>der Cousin</b> = male cousin  
- <b>die Freundin</b> = girlfriend / female friend  
- <b>der Freund</b> = boyfriend / male friend  
- <b>der Hund</b> = dog  

---

### Strategy

1️⃣ Listen carefully to the conversation.  

2️⃣ Focus on:
- Who celebrates the birthday?
- Who comes to the party?
- Which family members are mentioned?

3️⃣ Look for important keywords like:
- Mutter
- Familie
- Cousin
- Großeltern
- Freund / Freundin
- Hund

4️⃣ Choose the correct answer after listening.

---

### Listening Tip

Sometimes you do not need to understand every word.

👉 Listen for:
- Names
- Family words
- Repeated information

These help you find the correct answer quickly.

🎧 Listen again to check your answers.

</details>

---

---

# 📘 2 [GRAMMATIK KOMPAKT]

 # 🌟 [GRAMMATIK KOMPAKT] Possessivartikel im Nominativ



 ## a) Markieren Sie in 1b die Possessivartikel und ergänzen Sie die Tabelle.

<div style="overflow-x:auto;">

| Nominativ | Maskulinum | Neutrum | Femininum | Plural |
|---|---|---|---|---|
| ich | [[mein]] Vater | mein Buch | [[meine]] Mutter | [[meine]] Eltern |
| du | dein Vater | dein Buch | deine Mutter | deine Eltern |
| er / Julian | sein Vater | sein Buch | [[seine]] Mutter | seine Eltern |
| sie / Carla | [[ihr]] Vater | ihr Buch | ihre Mutter | ihre Eltern |
| es / das Kind | sein Vater | sein Buch | seine Mutter | seine Eltern |
| wir | unser Vater | unser Buch | [[unsere]] Mutter | unsere Eltern |
| ihr | euer Vater | euer Buch | eure Mutter | eure Eltern |
| sie / Sie | ihr / Ihr Vater | ihr / Ihr Buch | ihre / Ihre Mutter | ihre / Ihre Eltern |

</div>

---





 ## 👩‍👦 b) Wer passt zu Verena? Wer passt zu Aaron? Ordnern Sie zu.

 ![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_5/chapter_5_1.jpeg?raw=true)

<div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;align-items:center;">

<div style="background:#fff;border:2px solid #ffd7d7;border-radius:24px;padding:22px;text-align:center;">

<div style="font-size:72px;">![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_5/chapter_5_2.png?raw=true)</div>

<h2 style="color:#b34c4c;">Verena</h2>

</div>

<div style="background:#fff;border:2px solid #d7e6ff;border-radius:24px;padding:22px;text-align:center;">

<div style="font-size:72px;">![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_5/chapter_5_3.png?raw=true)</div>

<h2 style="color:#3f68b0;">Aaron</h2>

</div>

</div>

---

<div style="background:#ffffff;border:2px solid #dbe7ff;border-radius:22px;padding:24px;line-height:2.2;font-size:19px;">

a.~~__ Seine __~~Schwester ist Susanne.  

b. [[Ihr]] Bruder ist Albert.  

c. [[Seine]] Eltern sind Sonja und Matthias.  

d. [[Sein]] Cousin ist Julian.  

e. [[Ihre]] Eltern sind Renate und Horst.  

f. [[Ihre]] Tochter ist Carla.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you learn about <b>Possessivartikel (possessive articles)</b> in German.

Possessive articles show:
👉 who something belongs to.

Examples:
- My father
- Your mother
- His sister
- Her parents

---

### Helpful vocabulary

- <b>mein / meine</b> = my  
- <b>dein / deine</b> = your  
- <b>sein / seine</b> = his  
- <b>ihr / ihre</b> = her  
- <b>unser / unsere</b> = our  
- <b>euer / eure</b> = your (plural)

---

### Important grammar rule

The possessive article changes depending on:

1️⃣ The person  
(ich, du, er, sie, wir …)

2️⃣ the noun gender  
(maskulin, neutrum, feminin, plural)

Examples:

- mein Vater  
- meine Mutter  
- meine Eltern  

---

### Strategy for Part a)

Look at the noun carefully:

- der Vater → masculine  
- das Buch → neuter  
- die Mutter → feminine  
- die Eltern → plural  

Then choose the correct possessive article.

---

### Strategy for Part b)

Read the sentence carefully and ask:

👉 Who is the person?

- Verena → use <b>ihr / ihre</b>
- Aaron → use <b>sein / seine</b>

Example:

“___ Schwester ist Susanne.”

If the sentence is about Aaron:
➡ “Seine Schwester ist Susanne.”

---

🎯 Tip:

- <b>sein / seine</b> → for male persons  
- <b>ihr / ihre</b> → for female persons

</details>

---

---


# 🌟 [GRAMMATIK KOMPAKT] Possessivartikel im Akkusativ


<div style="display:flex;align-items:center;gap:18px;margin-bottom:22px;">

<div style="width:68px;height:68px;border-radius:50%;background:#9fb522;color:white;font-size:34px;font-weight:900;display:flex;align-items:center;justify-content:center;">
4
</div>

<div>
<h1 style="margin:0;color:#2d3d1c;font-size:38px;">
[GRAMMATIK KOMPAKT]
</h1>

<p style="margin-top:6px;font-size:24px;color:#555;">
Possessivartikel im Akkusativ
</p>
</div>

</div>

---

 ## ✨ a) Markieren Sie in 3 die possessivartikel und ergänzen Sie die Tabelle.

<div style="overflow-x:auto;">

<table style="width:100%;border-collapse:collapse;background:white;border-radius:22px;overflow:hidden;font-size:19px;min-width:1150px;">

<tr style="background:#9fb522;color:white;">

<th style="padding:16px;border:2px solid white;">
Akkusativ
</th>

<th style="padding:16px;border:2px solid white;">
Maskulinum<br>(Vater)
</th>

<th style="padding:16px;border:2px solid white;">
Neutrum<br>(Buch)
</th>

<th style="padding:16px;border:2px solid white;">
Femininum<br>(Mutter)
</th>

<th style="padding:16px;border:2px solid white;">
Plural<br>(Eltern)
</th>

</tr>

<!-- ich -->
<tr style="background:#ffffff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
ich
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
meinen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
mein
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
😊 [[meine]]
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
meine
</td>

</tr>

<!-- du -->
<tr style="background:#f8fbff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
du
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
deinen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
dein
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
deine
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
deine
</td>

</tr>

<!-- er -->
<tr style="background:#ffffff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
er (Julian)
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
seinen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
sein
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
seine
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
😊 [[seine]]
</td>

</tr>

<!-- sie -->
<tr style="background:#f8fbff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
sie (Carla)
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
ihren
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
ihr
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
ihre
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
ihre
</td>

</tr>

<!-- es -->
<tr style="background:#ffffff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
es (das Kind)
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
seinen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
sein
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
seine
</td>

<td style="padding:16px;border:1px solid #dfe8f5;color:#d14;font-weight:bold;">
seine
</td>

</tr>

<!-- wir -->
<tr style="background:#f8fbff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
wir
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
unseren
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
unser
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
unsere
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
unsere
</td>

</tr>

<!-- ihr -->
<tr style="background:#ffffff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
ihr
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
euren
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
euer
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
eure
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
eure
</td>

</tr>


<tr style="background:#f8fbff;">

<td style="padding:16px;font-weight:bold;border:1px solid #dfe8f5;">
sie / Sie
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
ihren / Ihren
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
ihr / Ihr
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
ihre / Ihre
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
ihre / Ihre
</td>

</tr>

</table>

</div>

---

 ## b) Schauen Sie die Tabellen in 2a und 4a an und ergänzen Sie die Regeln.

<div style="background:#eef7ff;border:2px solid #cfe3ff;border-radius:20px;padding:22px;margin-top:20px;line-height:2;font-size:20px;">

### Endungen • -en

1. Der Possessivartikel hat die gleichen  
😊 [[Endungen]] wie der Negativartikel / unbestimmte Artikel.

2. Akkusativ: Nur das Maskulinum hat eine andere Endung  
😊 [[-en]], der Rest ist wie im Nominativ.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you practice <b>Possessivartikel in the Akkusativ case</b>.

The Akkusativ is used for the <b>object</b> in a sentence.

Examples:
- Ich sehe meinen Vater.
- Carla besucht ihre Großeltern.

---

### Helpful vocabulary

- <b>mein / meine / meinen</b> = my  
- <b>dein / deine / deinen</b> = your  
- <b>sein / seine / seinen</b> = his  
- <b>ihr / ihre / ihren</b> = her  
- <b>unser / unsere / unseren</b> = our  

---

### Important grammar rule

⚠️ In the Akkusativ, only the <b>masculine form changes</b>.

Examples:

- der Vater → meinen Vater  
- der Bruder → deinen Bruder  
- der Onkel → seinen Onkel  

But:

- die Mutter → meine Mutter  
- das Buch → mein Buch  
- die Eltern → meine Eltern  

stay the same.

---

### Strategy for Part a)

1️⃣ Look at the person:
- ich
- du
- er
- sie
- wir …

2️⃣ Look at the noun gender:
- masculine
- neuter
- feminine
- plural

3️⃣ Choose the correct possessive article.

---

### Strategy for Part b)

Compare:
- Nominativ
- Akkusativ

👉 Try to find:
Which form changes?

You will see:
✅ Only masculine gets <b>-en</b> in Akkusativ.

Examples:

- mein Vater → meinen Vater  
- dein Bruder → deinen Bruder  
- sein Onkel → seinen Onkel  

---

🎯 Quick Tip

If the noun is masculine and in Akkusativ:
➡ add <b>-en</b>

</details>

---

---





# 🎉 Julian – seine Familie und Verwandtschaft



<div style="display:flex;align-items:center;gap:18px;margin-bottom:24px;">

<div style="width:68px;height:68px;border-radius:50%;background:#9fb522;color:white;font-size:34px;font-weight:900;display:flex;align-items:center;justify-content:center;">
1
</div>

<div>
<h1 style="margin:0;color:#2d3d1c;font-size:38px;">
Julian – seine Familie und Verwandtschaft
</h1>

<p style="margin-top:8px;font-size:22px;color:#555;">
 ## 🎂 Die Mutter von Julian feiert ihren Geburtstag. Betrachten Sie das Bild. Wer sind die Personen? Was vermuten Sie? 
</p>
</div>


</div>

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_5/chapter_5_4.png?raw=true)

---

 ## 🖼️ a) Wer sind die Personen?

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_038.mp3?raw=true)

<div style="background:white;border:2px solid #d9e7ff;border-radius:24px;padding:22px;">

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_5/familie_party.png?raw=true)

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;margin-top:22px;">

<div style="background:#eef7ff;border:2px solid #cfe3ff;border-radius:18px;padding:18px;">
<b>A</b> → [[Carla]]
</div>

<div style="background:#eefbea;border:2px solid #cfe7bf;border-radius:18px;padding:18px;">
<b>B</b> → [[Horst]]
</div>

<div style="background:#fff4fb;border:2px solid #efcad8;border-radius:18px;padding:18px;">
<b>C</b> → [[der Hund]]
</div>

<div style="background:#fff8ec;border:2px solid #f2d9a8;border-radius:18px;padding:18px;">
<b>D</b> → [[Susanne]]
</div>

<div style="background:#f8fbff;border:2px solid #d9e7ff;border-radius:18px;padding:18px;">
<b>E</b> → [[Jannis]]
</div>

</div>

</div>

---



 ## ✅ c) Hören Sie das Gespräch noch einmal. Was hören Sie? Kreuzen Sie an.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_038.mp3?raw=true)

<div style="background:white;border:2px solid #dbe8ff;border-radius:24px;padding:24px;overflow-x:auto;">

<table style="width:100%;border-collapse:collapse;font-size:19px;min-width:1000px;">

<tr style="background:#9fb522;color:white;">

<th style="padding:16px;border:2px solid white;text-align:left;">
Satz
</th>

<th style="padding:16px;border:2px solid white;">
a
</th>

<th style="padding:16px;border:2px solid white;">
b
</th>

</tr>

<tr>
<td style="padding:16px;border:1px solid #dfe8f5;">
1. Carla ist
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] groß und schlank
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] klein und schlank
</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:16px;border:1px solid #dfe8f5;">
2. Ihre Haare sind
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] braun und lang
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] blond und lang
</td>
</tr>

<tr>
<td style="padding:16px;border:1px solid #dfe8f5;">
3. Davide findet, Carla sieht
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] sympathisch aus
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] super aus
</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:16px;border:1px solid #dfe8f5;">
4. einen Freund haben heißt auf Deutsch
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] verlobt sein
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] verliebt sein
</td>
</tr>

<tr>
<td style="padding:16px;border:1px solid #dfe8f5;">
5. Davide findet, Jannis sieht
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] cool aus
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] nicht cool aus
</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:16px;border:1px solid #dfe8f5;">
6. Julian meint, sein Opa sieht
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] noch sehr jung aus
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] schon alt aus
</td>
</tr>

<tr>
<td style="padding:16px;border:1px solid #dfe8f5;">
7. Der Opa von Julian ist
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] noch sehr fit
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] nicht mehr fit
</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:16px;border:1px solid #dfe8f5;">
8. Die Haare von Cousine Susanne sind
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] blond und lockig
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] braun und lockig
</td>
</tr>

<tr>
<td style="padding:16px;border:1px solid #dfe8f5;">
9. Julian findet, Susanne ist
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] intelligent
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] sympathisch
</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:16px;border:1px solid #dfe8f5;">
10. Der Hund ist
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[ ]] klein und kräftig
</td>
<td style="padding:16px;border:1px solid #dfe8f5;">
[[x]] dick, aber süß
</td>
</tr>

</table>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you practice <b>describing people and understanding spoken information</b>.

You will:
- Identify family members in a picture
- Describe appearance
- Understand opinions and descriptions from a conversation

---

### Helpful vocabulary

#### Family members
- <b>der Opa</b> = grandfather  
- <b>die Cousine</b> = female cousin  
- <b>der Freund</b> = boyfriend / male friend  
- <b>der Hund</b> = dog  

---

#### Appearance and description
- <b>groß</b> = tall  
- <b>klein</b> = small  
- <b>schlank</b> = slim  
- <b>dick</b> = fat / chubby  
- <b>blond</b> = blond  
- <b>braun</b> = brown  
- <b>lockig</b> = curly  
- <b>süß</b> = cute  
- <b>fit</b> = fit / healthy  
- <b>intelligent</b> = intelligent  
- <b>cool</b> = cool  

---

### Important expression

<b>aussehen</b> = to look / appear

Examples:
- Carla sieht super aus.  
- Jannis sieht cool aus.  
- Der Opa sieht jung aus.  

---

### Strategy for Part a)

1️⃣ Look carefully at the picture.  

2️⃣ Match the letters (A–E) with the correct people.  

3️⃣ Use clues like:
- Age
- Hairstyle
- Gender
- Family relationships

---

### Strategy for Part c)

1️⃣ Listen carefully to the conversation.  

2️⃣ Focus on:
- Physical appearance
- Hair color
- Opinions
- Personality descriptions

3️⃣ Compare option a and option b carefully before choosing.

---

### Listening Tip

Do not translate every word.

🎧 Listen for important keywords like:
- Blond
- Lockig
- Groß
- Süß
- Intelligent
- Cool

These words help you find the correct answer quickly.

</details>

---

---



# 🌟 [GRAMMATIK KOMPAKT] Adjektive – prädikativ und adverbial



<div style="display:flex;align-items:center;gap:18px;margin-bottom:24px;">

<div style="width:68px;height:68px;border-radius:50%;background:#9fb522;color:white;font-size:34px;font-weight:900;display:flex;align-items:center;justify-content:center;">
2
</div>

<div>
<h1 style="margin:0;color:#2d3d1c;font-size:38px;">
Adjektive – prädikativ und adverbial
</h1>


</div>

</div>

---

 ## 🧠 a) Markieren Sie die Adjektive 2b

<div style="background:white;border:2px solid #d9e7ff;border-radius:24px;padding:24px;line-height:2;font-size:21px;">

1. Meine Schwester ist sehr 😊[[schlank]].  

2. Meine Cousine kann sehr 😊[[schnell]] rechnen.  

3. Die Haare von Susanne sind 😊[[lockig]].  

4. Mein Opa kocht sehr 😊[[gut]].  

5. Euer Hund sieht sehr 😊[[witzig]] aus.

</div>

---

 ## ✅ b) Was beschreiben die Adjektive: das Nomen order das Verb? Lesen Sie die Sätze noch einmal und Kreuzen Sie an.

<div style="background:#f8fbff;border:2px solid #d9e7ff;border-radius:24px;padding:24px;overflow-x:auto;">

<table style="width:100%;border-collapse:collapse;font-size:20px;min-width:1000px;">

<tr style="background:#9fb522;color:white;">

<th style="padding:16px;border:2px solid white;text-align:left;">
Satz
</th>

<th style="padding:16px;border:2px solid white;">
beschreibt Nomen
</th>

<th style="padding:16px;border:2px solid white;">
beschreibt Verb
</th>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
1. Meine Schwester ist sehr ~~schlank~~.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(x)] Nomen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">

- [( )] Verb
</td>

</tr>

<tr style="background:#f8fbff;">

<td style="padding:16px;border:1px solid #dfe8f5;">
2. Meine Cousine kann sehr schnell rechnen.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] Nomen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(X)] Verb
</td>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
3. Die Haare von Susanne sind lockig.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(x)] Nomen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] Verb
</td>

</tr>

<tr style="background:#f8fbff;">

<td style="padding:16px;border:1px solid #dfe8f5;">
4. Mein Opa kocht sehr gut.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] Nomen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(x)] Verb
</td>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
5. Euer Hund sieht sehr witzig aus.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] Nomen
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(x)] Verb
</td>

</tr>

</table>

</div>

---

 ## 📘 c) Ergänzen Sie die Regeln

<div style="background:#eef7ff;border:2px solid #cfe3ff;border-radius:24px;padding:24px;line-height:2.1;font-size:21px;">

> eine Handlung oder einen Zustand · Form · eine Person oder einen Gegenstand

---

1. Das Verb <b>sein</b> definiert  
😊 [[eine Person oder einen Gegenstand]].  

Das Adjektiv beschreibt das Nomen (Subjekt).  
👉 Adjektiv = <b>prädikativ</b>

---

2. Verben wie <b>kochen, rechnen und essen</b> drücken  
😊 [[eine Handlung oder einen Zustand]] aus.  

Das Adjektiv beschreibt das Verb.  
👉 Adjektiv = <b>adverbial</b>

---

3. Im Deutschen ist die  
😊 [[Form]] von Adjektiven adverbial und prädikativ identisch.

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you learn about <b>German adjectives</b> and how they describe:

👉 A person or thing  
👉 Or an action

You will practice two grammar types:

- <b>prädikativ</b> adjectives  
- <b>adverbial</b> adjectives

---

### Helpful vocabulary

- <b>schlank</b> = slim  
- <b>schnell</b> = fast  
- <b>lockig</b> = curly  
- <b>gut</b> = good / well  
- <b>witzig</b> = funny  

---

### Important grammar idea

## 1️⃣ Prädikativ

The adjective describes a <b>person or thing (noun)</b>.

Usually with:
- sein
- aussehen

Examples:
- Meine Schwester ist schlank.  
- Die Haare sind lockig.  

👉 The adjective describes the noun.

---

## 2️⃣ Adverbial

The adjective describes an <b>action (verb)</b>.

Examples:
- Mein Opa kocht gut.  
- Meine Cousine rechnet schnell.  

👉 The adjective describes HOW someone does something.

---

### Strategy for Part a)

1️⃣ Find the describing word in each sentence.  

2️⃣ Ask:
- Which word gives more information?

That word is the adjective.

---

### Strategy for Part b)

Ask yourself:

👉 Does the adjective describe:
- a person / thing? → Nomen  
OR
- an action? → Verb

Examples:

- „Meine Schwester ist schlank.“  
➡ describes Schwester → Nomen

- „Mein Opa kocht gut.“  
➡ describes kocht → Verb

---

### Strategy for Part c)

Complete the grammar rules using the word box.

Focus on:
- Noun description
- Action description
- Adjective form

---

🎯 Important Tip

In German:
✅ Adjectives stay the SAME in:
- prädikativ
- adverbial

Examples:
- Sie ist schnell.  
- Sie rechnet schnell.  

The adjective form does not change.

</details>

---

---



# 🔊 [AUSSPRACHE] Kurze und lange Vokale

<div style="background:white;border:2px solid #d9e7ff;border-radius:24px;padding:24px;margin-top:24px;">

## 🎧 a) Ist der Vokal kurz (.) oder lang (-)? Hören Sie die Wörter und notieren Sie.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-kb_/KursDaF_A1_KB_Track_039.mp3?raw=true)

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:16px;margin-top:18px;">

<div style="background:#eef7ff;padding:16px;border-radius:18px;">1. Mutter</div>
<div style="background:#eefbea;padding:16px;border-radius:18px;">2. Familie</div>
<div style="background:#fff8ec;padding:16px;border-radius:18px;">3. Brüder</div>
<div style="background:#fff4fb;padding:16px;border-radius:18px;">4. lang</div>

<div style="background:#eef7ff;padding:16px;border-radius:18px;">5. ledig</div>
<div style="background:#eefbea;padding:16px;border-radius:18px;">6. kurz</div>
<div style="background:#fff8ec;padding:16px;border-radius:18px;">7. geschieden</div>
<div style="background:#fff4fb;padding:16px;border-radius:18px;">8. Sohn</div>

<div style="background:#eef7ff;padding:16px;border-radius:18px;">9. Tante</div>
<div style="background:#eefbea;padding:16px;border-radius:18px;">10. fit</div>
<div style="background:#fff8ec;padding:16px;border-radius:18px;">11. blond</div>
<div style="background:#fff4fb;padding:16px;border-radius:18px;">12. Vater</div>

<div style="background:#eef7ff;padding:16px;border-radius:18px;">13. Enkel</div>
<div style="background:#eefbea;padding:16px;border-radius:18px;">14. Großmutter</div>

</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you practice <b>German pronunciation</b>, especially:

🔊 Short vowels  
🔊 Long vowels

You will listen to German words and decide:

- Is the vowel short? → (.)  
- Is the vowel long? → (-)

---

### Important pronunciation idea

In German, vowel length can change:
- Pronunciation
- Rhythm
- Sometimes even meaning

Examples:

- <b>kurz</b> = short vowel  
- <b>lang</b> = long vowel  

---

### Helpful examples

#### 🔹 Short vowels (.)
spoken quickly

- Mutter  
- fit  
- blond  
- Tante  

👉 The vowel sound is short and fast.

---

#### 🔹 Long vowels (-)
spoken longer

- Sohn  
- Vater  
- Brüder  
- Familie  

👉 The vowel sound is stretched longer.

---

### Strategy

1️⃣ Listen carefully to the vowel sound.  

2️⃣ Focus only on the main vowel:
- a
- e
- i
- o
- u
- ä
- ö
- ü

3️⃣ Ask yourself:

👉 Does the vowel sound:
- quick and short? → (.)  
OR
- longer and stretched? → (-)

---

### Listening Tip

🎧 Listen more than once.

German pronunciation becomes easier when you:
- Repeat the words aloud
- Compare short and long sounds
- Speak slowly first

---

### Speaking Practice

Try to repeat the words after listening:

- Mutter  
- Familie  
- Sohn  
- Vater  
- fit  
- blond  

This improves your pronunciation and listening skills.

</details>

---

---



# 🌟 Kontakte oder Freunde?



<div style="display:flex;align-items:center;gap:18px;margin-bottom:24px;">

<div style="width:68px;height:68px;border-radius:50%;background:#9fb522;color:white;font-size:34px;font-weight:900;display:flex;align-items:center;justify-content:center;">
1
</div>

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_5/chapter_5_5.png?raw=true)

<div>
<h1 style="margin:0;color:#2d3d1c;font-size:38px;">
Kontakte oder Freunde?
</h1>

<p style="margin-top:8px;font-size:22px;color:#555;">
👫 Freundschaft und Kontakte
</p>
</div>

</div>

---

 ## 📖 a) Für wen ist wichtig: „Freunde machen viel gemeinsam“? Lesen Sie die Beiträge von Studierenden im Unijournal und Kreuzen Sie an.

<div style="background:white;border:2px solid #d9e7ff;border-radius:24px;padding:24px;">

## Kreuzen Sie an

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;margin-top:18px;">

<div style="background:#eef7ff;border:2px solid #cfe3ff;border-radius:18px;padding:18px;">
[[ ]] Dominik
</div>

<div style="background:#fff4fb;border:2px solid #efcad8;border-radius:18px;padding:18px;">
[[x]] Alexandra
</div>

<div style="background:#eefbea;border:2px solid #cfe7bf;border-radius:18px;padding:18px;">
[[ ]] Davide
</div>

<div style="background:#fff8ec;border:2px solid #f2d9a8;border-radius:18px;padding:18px;">
[[ ]] Leon
</div>

<div style="background:#f8fbff;border:2px solid #d9e7ff;border-radius:18px;padding:18px;">
[[ ]] Nina
</div>

<div style="background:#eef7ff;border:2px solid #cfe3ff;border-radius:18px;padding:18px;">
[[x]] Tim
</div>

</div>

</div>

---

 ## 💬 Beiträge der Studierenden

<div style="display:grid;grid-template-columns:1fr;gap:18px;margin-top:24px;">



<!-- Dominik -->
<div style="background:#eef7ff;border-left:8px solid #5b9cff;border-radius:20px;padding:22px;">

<h3 style="margin-top:0;color:#2b5f9b;">
👨 Dominik, 21 – Politikwissenschaft
</h3>

Kontakte sind keine Freunde, denn Freunde müssen loyal, ehrlich und offen sein.  
Ich kenne meine Freunde gut und wir diskutieren sehr offen.

</div>

<!-- Alexandra -->
<div style="background:#fff4fb;border-left:8px solid #e87ab1;border-radius:20px;padding:22px;">

<h3 style="margin-top:0;color:#a04668;">
👩 Alexandra, 23 – Romanistik
</h3>

Ich finde, man muss viel zusammen machen.  
Zum Beispiel kochen meine Freunde und ich oft etwas: Gemeinsam kochen und essen verbindet!  
Das kann man im Internet nicht erleben.

</div>

<!-- Davide -->
<div style="background:#eefbea;border-left:8px solid #76b852;border-radius:20px;padding:22px;">

<h3 style="margin-top:0;color:#3f7d2d;">
👨 Davide, 23 – Jura
</h3>

Echte Freunde? Meine Freunde sind witzig.  
Man hat Spaß zusammen, aber man hilft und gibt auch viel.  
Alles hat seinen Preis. Ich denke, nur so behält man seine Freunde.

</div>

<!-- Leon -->
<div style="background:#fff8ec;border-left:8px solid #f0b44c;border-radius:20px;padding:22px;">

<h3 style="margin-top:0;color:#9a6a11;">
👨 Leon, 19 – Informatik
</h3>

Freunde müssen immer da sein.  
Sie begleiten dein Leben.  
Man muss für eine Freundschaft etwas tun.  
Nichts ist selbstverständlich.

</div>

<!-- Nina -->
<div style="background:#f8fbff;border-left:8px solid #7b8cff;border-radius:20px;padding:22px;">

<h3 style="margin-top:0;color:#4353b3;">
👩 Nina, 22 – Wirtschaft
</h3>

Ich finde, Freundschaft muss nicht immer perfekt sein.  
Aber eine Sache finde ich sehr wichtig: Aufmerksamkeit und Respekt!  
So kann man auch für das Leben viel lernen.

</div>

<!-- Tim -->
<div style="background:#eefbea;border-left:8px solid #49a36d;border-radius:20px;padding:22px;">

<h3 style="margin-top:0;color:#2d7a4c;">
👨 Tim, 21 – Medienwissenschaften
</h3>

Ich habe nur zwei Freunde.  
Wir machen viel zusammen, das finde ich wichtig.  
Ich habe auch Kontakte im Internet, aber ich denke, das sind keine Freunde.  
Das ist meine Meinung: Qualität und nicht Quantität.

</div>

</div>

---

 ## ✅ b) Lesen Sie die Beiträge noch einmal.  Was ist richtig (r), was ist falsch (f)? Kreuzen Sie an.

<div style="background:white;border:2px solid #dbe8ff;border-radius:24px;padding:24px;overflow-x:auto;margin-top:24px;">

<table style="width:100%;border-collapse:collapse;font-size:20px;min-width:1000px;">

<tr style="background:#9fb522;color:white;">

<th style="padding:16px;border:2px solid white;text-align:left;">
Satz
</th>

<th style="padding:16px;border:2px solid white;">
r
</th>

<th style="padding:16px;border:2px solid white;">
f
</th>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
1. Dominik findet, Freunde müssen offen sein.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(x)] r
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(X)] f
</td>

</tr>

<tr style="background:#f8fbff;">

<td style="padding:16px;border:1px solid #dfe8f5;">
2. Alexandra und ihre Freunde kochen oft zusammen.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(X)] r
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] f
</td>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
3. Für Davide ist nur der Spaß wichtig.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] r
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(X)] f
</td>

</tr>

<tr style="background:#f8fbff;">

<td style="padding:16px;border:1px solid #dfe8f5;">
4. Leon denkt, Freunde sind automatisch immer da.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] r
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(x)] f
</td>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
5. Für Nina muss Freundschaft perfekt sein.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] r
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(X)] f
</td>

</tr>

<tr style="background:#f8fbff;">

<td style="padding:16px;border:1px solid #dfe8f5;">
6. Tim findet, Kontakte im Internet sind keine Freunde.
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [(X)] r
</td>

<td style="padding:16px;border:1px solid #dfe8f5;text-align:center;">
- [( )] f
</td>

</tr>

</table>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you read different opinions about <b>friendship and social contacts</b>.

Students from the university describe:
- what friendship means for them
- what is important in friendship
- whether internet contacts are real friends

---

### Helpful vocabulary

- <b>der Freund / die Freundin</b> = friend  
- <b>die Freundschaft</b> = friendship  
- <b>der Kontakt</b> = contact  
- <b>ehrlich</b> = honest  
- <b>loyal</b> = loyal  
- <b>offen</b> = open  
- <b>Respekt</b> = respect  
- <b>Aufmerksamkeit</b> = attention / care  
- <b>gemeinsam</b> = together  
- <b>verbinden</b> = to connect  

---

### Strategy for Part a)

Read each student text carefully.

Then ask yourself:

👉 Who thinks friends should do many things together?

Look for keywords like:
- zusammen
- gemeinsam
- kochen
- viel machen

These words help you find the correct people.

---

### Strategy for Part b)

Read each sentence again and compare it with the student texts.

Ask yourself:

✅ Is the information exactly the same?  
➡ mark <b>r</b> (richtig)

❌ Is the information different or incorrect?  
➡ mark <b>f</b> (falsch)

---

### Reading Tip

You do NOT need to understand every word.

Focus on:
- Important adjectives
- Opinions
- Repeated ideas

Examples:
- Loyal
- Ehrlich
- Offen
- Zusammen
- Respekt
- Freunde

These help you understand the meaning quickly.

---

🎯 Important Idea

Many students explain:
- Friendship needs trust
- Friendship needs time
- Friendship needs respect
- Internet contacts are not always real friends

</details>

---



# 🌟 Indefinitpronomen & Freunde



<div style="display:flex;align-items:center;gap:18px;margin-bottom:24px;">

<div style="width:68px;height:68px;border-radius:50%;background:#9fb522;color:white;font-size:34px;font-weight:900;display:flex;align-items:center;justify-content:center;">
2
</div>

<div>
<h1 style="margin:0;color:#2d3d1c;font-size:38px;">
[GRAMMATIK KOMPAKT]
</h1>

<p style="margin-top:8px;font-size:24px;color:#555;">
Indefinitpronomen: man · alles · viel · etwas · nichts
</p>
</div>

</div>

---

 ## ✍️ a) Schreiben Sie einen Satz aus 1a an die passende Stelle.

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px;">

<div style="background:#eef7ff;border:2px solid #cfe3ff;border-radius:22px;padding:22px;">

<h3 style="margin-top:0;color:#245f9c;">👤 man</h3>

<div style="background:white;border-radius:14px;padding:16px;line-height:1.8;">
Man muss viel zusammen machen.
</div>

</div>

<div style="background:#eefbea;border:2px solid #cfe7bf;border-radius:22px;padding:22px;">

<h3 style="margin-top:0;color:#3d7b31;">✅ alles</h3>

<div style="background:white;border-radius:14px;padding:16px;line-height:1.8;">
Alles hat seinen Preis.
</div>

</div>

<div style="background:#fff8ec;border:2px solid #f2d9a8;border-radius:22px;padding:22px;">

<h3 style="margin-top:0;color:#9a6a11;">📚 viel</h3>

<div style="background:white;border-radius:14px;padding:16px;line-height:1.8;">
So kann man auch für das Leben viel lernen.
</div>

</div>

<div style="background:#fff4fb;border:2px solid #efcad8;border-radius:22px;padding:22px;">

<h3 style="margin-top:0;color:#a04668;">✨ etwas</h3>

<div style="background:white;border-radius:14px;padding:16px;line-height:1.8;">
Man muss für eine Freundschaft etwas tun.
</div>

</div>

<div style="background:#f8fbff;border:2px solid #d9e7ff;border-radius:22px;padding:22px;">

<h3 style="margin-top:0;color:#4353b3;">🚫 nichts</h3>

<div style="background:white;border-radius:14px;padding:16px;line-height:1.8;">
Nichts ist selbstverständlich.
</div>

</div>

</div>

---

 ## 🧠 b) Wann benutzt man diese Pronomen?

<div style="background:white;border:2px solid #dbe8ff;border-radius:24px;padding:24px;margin-top:24px;">

<table style="width:100%;border-collapse:collapse;font-size:20px;min-width:950px;">

<tr style="background:#9fb522;color:white;">

<th style="padding:16px;border:2px solid white;">
Pronomen
</th>

<th style="padding:16px;border:2px solid white;">
Definition
</th>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
<b>alles</b>
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
100 % (Sachen), Gegenteil von nichts
</td>

</tr>

<tr style="background:#f8fbff;">

<td style="padding:16px;border:1px solid #dfe8f5;">
<b>man</b>
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
generell für Personen, Personen sind nicht bekannt
</td>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
<b>nichts</b>
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
Null, Gegenteil von alles
</td>

</tr>

<tr style="background:#f8fbff;">

<td style="padding:16px;border:1px solid #dfe8f5;">
<b>viel</b>
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
die Menge ist groß
</td>

</tr>

<tr>

<td style="padding:16px;border:1px solid #dfe8f5;">
<b>etwas</b>
</td>

<td style="padding:16px;border:1px solid #dfe8f5;">
die Menge ist klein; braucht man für Sachen / Gegenstände
</td>

</tr>

</table>

</div>

---

 ## 📝 c) Was passt? Ergänzen Sie die Indefinitpronomen aus 2a.

<div style="background:white;border:2px solid #dbe8ff;border-radius:24px;padding:24px;line-height:2.2;margin-top:24px;">

### 1.
Ich muss noch [[viel]] lernen.

---

### 2.
Ist [[alles]] klar?

---

### 3.
Ich habe nicht viel, aber [[etwas]] Hunger.

---

### 4.
Heute habe ich keine Lust. Ich mache [[nichts]].

---

### 5.
Die Hausaufgabe ist perfekt, [[alles]] ist richtig.

---

### 6.
Heute bekommt [[man]] ein Getränk gratis.

</div>

---

 ## 💬 3 Was sind Freunde für Sie?

<div style="background:linear-gradient(135deg,#fff4fb,#f7fbff);border:2px solid #ead5e6;border-radius:26px;padding:26px;margin-top:28px;">

<h2 style="margin-top:0;color:#a04668;">
🤝 a) Wie müssen Freunde sein?
</h2>

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px;margin-top:20px;">

<div style="background:white;border-radius:18px;padding:20px;border:2px solid #dbe8ff;">
💡 loyal  
</div>

<div style="background:white;border-radius:18px;padding:20px;border:2px solid #dbe8ff;">
💡 ehrlich  
</div>

<div style="background:white;border-radius:18px;padding:20px;border:2px solid #dbe8ff;">
💡 offen  
</div>

<div style="background:white;border-radius:18px;padding:20px;border:2px solid #dbe8ff;">
💡 freundlich  
</div>

<div style="background:white;border-radius:18px;padding:20px;border:2px solid #dbe8ff;">
💡 hilfsbereit  
</div>

<div style="background:white;border-radius:18px;padding:20px;border:2px solid #dbe8ff;">
💡 respektvoll  
</div>

</div>

</div>

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you learn about <b>Indefinitpronomen (indefinite pronouns)</b> in German.

These pronouns are used when:
- A person is not specific
- The amount is not exact
- Or we speak generally about things and people

---

### Helpful vocabulary

- <b>man</b> = people / one / someone generally  
- <b>alles</b> = everything  
- <b>viel</b> = much / a lot  
- <b>etwas</b> = something / a little  
- <b>nichts</b> = nothing  

---

### Important meanings

#### 👤 man
Used for people in general.

Example:
- Man lernt Deutsch.  
(People learn German.)

---

#### ✅ alles
Means 100%.

Example:
- Alles ist richtig.  
(Everything is correct.)

---

#### 📚 viel
Means a large amount.

Example:
- Ich muss viel lernen.  

---

#### ✨ etwas
Means a small amount or something.

Example:
- Ich habe etwas Hunger.  

---

#### 🚫 nichts
Means zero or nothing.

Example:
- Ich mache nichts.  

---

### Strategy for Part a)

Read the sentences carefully.

Then match:
- The meaning
- The pronoun
- And the example sentence

---

### Strategy for Part b)

Focus on the definitions.

Ask yourself:

👉 Is it:
- Everything?
- Nothing?
- A lot?
- A little?
- People in general?

This helps you choose the correct pronoun.

---

### Strategy for Part c)

Read the sentence carefully and think about the meaning.

Examples:

- Large amount → <b>viel</b>  
- Zero → <b>nichts</b>  
- General people → <b>man</b>  
- 100% → <b>alles</b>  

---

🎯 Important Tip

Indefinite pronouns are very common in everyday German.

You hear them often in:
- Conversations
- University life
- Emails
- Opinions
- Descriptions

</details>

---

---





# 🌟 Kapitel 5 – Übersicht


 ## 👨‍👩‍👧 Familie und Freunde vorstellen

<div style="background:white;border:2px solid #d9e7ff;border-radius:24px;padding:24px;line-height:2;">

<div style="background:#eef7ff;border-left:8px solid #5b9cff;border-radius:16px;padding:18px;margin-bottom:18px;">

<b>Das ist meine Mutter.</b>  
Sie heißt …  
Ihre …  
Ihr …

</div>

<div style="background:#fff4fb;border-left:8px solid #e87ab1;border-radius:16px;padding:18px;margin-bottom:18px;">

<b>Und das ist meine / mein …</b>  
Sie / Er …  
Ihre / Seine …  
Ihr / Sein …

</div>

<div style="background:#eefbea;border-left:8px solid #76b852;border-radius:16px;padding:18px;">

<b>Das sind meine Großeltern.</b>  
Sie …

</div>

</div>

---

 ## 😊 Aussehen und Charakter beschreiben

<div style="background:white;border:2px solid #eadff4;border-radius:24px;padding:24px;">

<div style="display:grid;grid-template-columns:1fr 1fr;gap:18px;">

<div style="background:#eef7ff;border-radius:18px;padding:18px;">

• Mein(e) … ist … (Adjektiv).  

• Ich finde, er/sie/es ist … (Adjektiv).  

• Er / Sie / Es sieht … aus.  

• Ich finde, er/sie/es sieht … aus.

</div>

<div style="background:#fff4fb;border-radius:18px;padding:18px;">

• Seine / Ihre Haare sind …  

• Freunde müssen … sein.  

• Ich finde, Freunde müssen … sein.

</div>

</div>

</div>

---

 ## 📘 Possessivartikel im Nominativ

<div style="background:white;border:2px solid #dbe8ff;border-radius:24px;padding:24px;overflow-x:auto;">

<table style="width:100%;border-collapse:collapse;font-size:18px;text-align:center;">

<tr style="background:#d9ecf7;">
<th style="padding:12px;border:1px solid white;">Nominativ</th>
<th style="padding:12px;border:1px solid white;">M</th>
<th style="padding:12px;border:1px solid white;">N</th>
<th style="padding:12px;border:1px solid white;">F</th>
<th style="padding:12px;border:1px solid white;">Plural</th>
</tr>

<tr>
<td style="padding:10px;border:1px solid #dfe8f5;"><b>ich</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">mein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">mein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">meine</td>
<td style="padding:10px;border:1px solid #dfe8f5;">meine</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:10px;border:1px solid #dfe8f5;"><b>du</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">dein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">dein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">deine</td>
<td style="padding:10px;border:1px solid #dfe8f5;">deine</td>
</tr>

<tr>
<td style="padding:10px;border:1px solid #dfe8f5;"><b>er</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">sein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">sein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">seine</td>
<td style="padding:10px;border:1px solid #dfe8f5;">seine</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:10px;border:1px solid #dfe8f5;"><b>sie</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihr</td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihr</td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihre</td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihre</td>
</tr>

<tr>
<td style="padding:10px;border:1px solid #dfe8f5;"><b>es</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">sein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">sein</td>
<td style="padding:10px;border:1px solid #dfe8f5;">seine</td>
<td style="padding:10px;border:1px solid #dfe8f5;">seine</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:10px;border:1px solid #dfe8f5;"><b>wir</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">unser</td>
<td style="padding:10px;border:1px solid #dfe8f5;">unser</td>
<td style="padding:10px;border:1px solid #dfe8f5;">unsere</td>
<td style="padding:10px;border:1px solid #dfe8f5;">unsere</td>
</tr>

<tr>
<td style="padding:10px;border:1px solid #dfe8f5;"><b>ihr</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">euer</td>
<td style="padding:10px;border:1px solid #dfe8f5;">euer</td>
<td style="padding:10px;border:1px solid #dfe8f5;">eure</td>
<td style="padding:10px;border:1px solid #dfe8f5;">eure</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:10px;border:1px solid #dfe8f5;"><b>sie / Sie</b></td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihr / Ihr</td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihr / Ihr</td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihre / Ihre</td>
<td style="padding:10px;border:1px solid #dfe8f5;">ihre / Ihre</td>
</tr>

</table>

</div>

---

 ## 📕 Possessivartikel im Akkusativ

<div style="background:white;border:2px solid #ead5e6;border-radius:24px;padding:24px;overflow-x:auto;">

<table style="width:100%;border-collapse:collapse;font-size:18px;text-align:center;">

<tr style="background:#f6dbe8;">
<th style="padding:12px;border:1px solid white;">Akkusativ</th>
<th style="padding:12px;border:1px solid white;">M</th>
<th style="padding:12px;border:1px solid white;">N</th>
<th style="padding:12px;border:1px solid white;">F</th>
<th style="padding:12px;border:1px solid white;">Plural</th>
</tr>

<tr>
<td style="padding:10px;border:1px solid #eadff4;"><b>ich</b></td>
<td style="padding:10px;border:1px solid #eadff4;">meinen</td>
<td style="padding:10px;border:1px solid #eadff4;">mein</td>
<td style="padding:10px;border:1px solid #eadff4;">meine</td>
<td style="padding:10px;border:1px solid #eadff4;">meine</td>
</tr>

<tr style="background:#fff7fb;">
<td style="padding:10px;border:1px solid #eadff4;"><b>du</b></td>
<td style="padding:10px;border:1px solid #eadff4;">deinen</td>
<td style="padding:10px;border:1px solid #eadff4;">dein</td>
<td style="padding:10px;border:1px solid #eadff4;">deine</td>
<td style="padding:10px;border:1px solid #eadff4;">deine</td>
</tr>

<tr>
<td style="padding:10px;border:1px solid #eadff4;"><b>er</b></td>
<td style="padding:10px;border:1px solid #eadff4;">seinen</td>
<td style="padding:10px;border:1px solid #eadff4;">sein</td>
<td style="padding:10px;border:1px solid #eadff4;">seine</td>
<td style="padding:10px;border:1px solid #eadff4;">seine</td>
</tr>

<tr style="background:#fff7fb;">
<td style="padding:10px;border:1px solid #eadff4;"><b>sie</b></td>
<td style="padding:10px;border:1px solid #eadff4;">ihren</td>
<td style="padding:10px;border:1px solid #eadff4;">ihr</td>
<td style="padding:10px;border:1px solid #eadff4;">ihre</td>
<td style="padding:10px;border:1px solid #eadff4;">ihre</td>
</tr>

<tr>
<td style="padding:10px;border:1px solid #eadff4;"><b>wir</b></td>
<td style="padding:10px;border:1px solid #eadff4;">unseren</td>
<td style="padding:10px;border:1px solid #eadff4;">unser</td>
<td style="padding:10px;border:1px solid #eadff4;">unsere</td>
<td style="padding:10px;border:1px solid #eadff4;">unsere</td>
</tr>

</table>

</div>

---

 ## ✨ Adjektive – prädikativ und adverbial

<div style="display:grid;grid-template-columns:1fr 1fr;gap:22px;margin-top:24px;">

<div style="background:#eef7ff;border:2px solid #cfe3ff;border-radius:24px;padding:22px;">

<h3 style="margin-top:0;color:#245f9c;">
Prädikativ
</h3>

<b>Adjektiv beschreibt Nomen (Subjekt)</b>

<div style="margin-top:16px;line-height:2;">
• Meine Schwester ist sehr groß.  
• Die Haare von Susanne sind lockig.
</div>

</div>

<div style="background:#fff4fb;border:2px solid #efcad8;border-radius:24px;padding:22px;">

<h3 style="margin-top:0;color:#a04668;">
Adverbial
</h3>

<b>Adjektiv beschreibt Verb</b>

<div style="margin-top:16px;line-height:2;">
• Mein Opa kocht sehr gut.  
• Meine Cousine rechnet schnell.  
• Euer Hund sieht sehr witzig aus.
</div>

</div>

</div>

---

 ## 🧠 Indefinitpronomen

<div style="background:white;border:2px solid #dbe8ff;border-radius:24px;padding:24px;overflow-x:auto;margin-top:24px;">

<table style="width:100%;border-collapse:collapse;font-size:18px;">

<tr style="background:#d9ecf7;">
<th style="padding:14px;border:1px solid white;">Pronomen</th>
<th style="padding:14px;border:1px solid white;">Beispiel</th>
</tr>

<tr>
<td style="padding:12px;border:1px solid #dfe8f5;"><b>man</b></td>
<td style="padding:12px;border:1px solid #dfe8f5;">Man muss für eine Freundschaft etwas tun.</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:12px;border:1px solid #dfe8f5;"><b>viel</b></td>
<td style="padding:12px;border:1px solid #dfe8f5;">Aber man hilft und gibt auch viel.</td>
</tr>

<tr>
<td style="padding:12px;border:1px solid #dfe8f5;"><b>etwas</b></td>
<td style="padding:12px;border:1px solid #dfe8f5;">Meine Freunde und ich kochen oft etwas.</td>
</tr>

<tr style="background:#f8fbff;">
<td style="padding:12px;border:1px solid #dfe8f5;"><b>nichts</b></td>
<td style="padding:12px;border:1px solid #dfe8f5;">Nichts ist selbstverständlich.</td>
</tr>

<tr>
<td style="padding:12px;border:1px solid #dfe8f5;"><b>alles</b></td>
<td style="padding:12px;border:1px solid #dfe8f5;">Alles hat seinen Preis.</td>
</tr>

</table>

</div>

# ✅ Kapitel 5 – Lösungen

---

# 👨‍👩‍👧 Familie und Verwandtschaft

 ## 1a) Namen ergänzen

1. Verena  
2. Alexander  
3. Carla  
4. Jannis  
5. Sonja  
6. Susanne  
7. Aaron  
8. Julian  
9. Matthias  
10. Albert  
11. Sonja  
12. Susanne  
13. Horst  
14. Renate  

---

# 🎂 Meine Mutter feiert Geburtstag

 ## a) Was ist richtig?

1. b) Julian  
2. a) der Hund  

---

 ## b) Wer kommt?

1. a) Unsere Familie  
2. a) ihr Freund  
3. a) seine Freundin  
4. b) Meine Großeltern  
5. b) Unser Hund  

---

# 📘 Possessivartikel im Nominativ

 ## a) Tabelle

- mein  
- meine  
- meine  
- seine  
- ihr  
- unsere  

---

 ## b) Verena oder Aaron?

a) Seine  
b) Ihre  
c) Seine  
d) Sein  
e) Ihre  
f) Ihre  

---

# 📕 Possessivartikel im Akkusativ

 ## a) Tabelle

- meine  
- seine  

---

 ## b) Regeln

1. Endungen  
2. -en  

---

# 🎉 Personen auf der Party

 ## a) Wer sind die Personen?

A → Carla  
B → Horst  
C → der Hund  
D → Susanne  
E → Jannis  

---

 ## c) Was hören Sie?

1. groß und schlank  
2. blond und lang  
3. super aus  
4. verliebt sein  
5. cool aus  
6. noch sehr jung aus  
7. noch sehr fit  
8. braun und lockig  
9. intelligent  
10. dick, aber süß  

---

# 🌟 Adjektive – prädikativ und adverbial

## a) Adjektive markieren

1. schlank  
2. schnell  
3. lockig  
4. gut  
5. witzig  

---

 ## b) Nomen oder Verb?

1. beschreibt Nomen  
2. beschreibt Verb  
3. beschreibt Nomen  
4. beschreibt Verb  
5. beschreibt Verb  

---

 ## c) Regeln

1. eine Person oder einen Gegenstand  
2. eine Handlung oder einen Zustand  
3. Form  

---

# 🔊 Aussprache – kurze und lange Vokale

1. Mutter → kurz  
2. Familie → lang  
3. Brüder → lang  
4. lang → lang  
5. ledig → lang  
6. kurz → kurz  
7. geschieden → lang  
8. Sohn → lang  
9. Tante → kurz  
10. fit → kurz  
11. blond → kurz  
12. Vater → lang  
13. Enkel → kurz  
14. Großmutter → lang  

---

# 🌟 Kontakte oder Freunde?

 ## a) Wer findet wichtig: „Freunde machen viel gemeinsam“?

- Alexandra  
- Tim  

---

 ## b) Richtig oder falsch?

1. richtig  
2. richtig  
3. falsch  
4. falsch  
5. falsch  
6. richtig  

---

# 🌟 Indefinitpronomen

 ## a) Sätze

- man → Man muss viel zusammen machen.  
- alles → Alles hat seinen Preis.  
- viel → So kann man auch für das Leben viel lernen.  
- etwas → Man muss für eine Freundschaft etwas tun.  
- nichts → Nichts ist selbstverständlich.  

---

 ## c) Ergänzen Sie

1. viel  
2. alles  
3. etwas  
4. nichts  
5. alles  
6. man  

---

# 🧠 Wichtiger Wortschatz

 ## Familie

- der Vater  
- die Mutter  
- die Schwester  
- der Bruder  
- die Tante  
- der Onkel  
- der Cousin  
- die Cousine  
- der Großvater  
- die Großmutter  

---

 ## Adjektive

- groß  
- klein  
- schlank  
- blond  
- lockig  
- intelligent  
- witzig  
- fit  
- sympathisch  

---

# 🎓 Kapitel 5 Grammatik – Kurzüberblick

 ## Possessivartikel

- mein / meine  
- dein / deine  
- sein / seine  
- ihr / ihre  
- unser / unsere  
- euer / eure  

---

 ## Indefinitpronomen

- man  
- alles  
- viel  
- etwas  
- nichts
