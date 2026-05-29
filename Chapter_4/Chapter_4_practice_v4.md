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
# Kapitel 4
<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bg4" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#f3f8ef"/>
      <stop offset="100%" stop-color="#ffffff"/>
    </linearGradient>

    <linearGradient id="panel4" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.98"/>
      <stop offset="100%" stop-color="#f8fbf5" stop-opacity="0.96"/>
    </linearGradient>

    <linearGradient id="accent4" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#96a826"/>
      <stop offset="100%" stop-color="#b9c94a"/>
    </linearGradient>

    <filter id="shadow4" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="14" stdDeviation="16" flood-color="#7d8b2b" flood-opacity="0.18"/>
    </filter>

    <style><![CDATA[
      .chip{font-family:Georgia; font-size:24px; font-weight:700; fill:#ffffff;}
      .title{font-family:Georgia; font-size:64px; font-weight:700; fill:#6f7f1f;}
      .subtitle{font-family:Arial; font-size:22px; fill:#5b6450;}
      .head{font-family:Georgia; font-size:30px; font-weight:700; fill:#7a8626;}
      .bullet{font-family:Arial; font-size:20px; fill:#4e5648;}
      .footer{font-family:Arial; font-size:20px; fill:#4e5648;}
      .small{font-family:Arial; font-size:16px; fill:#6a7261;}
    ]]></style>
  </defs>

  <rect width="1600" height="900" fill="url(#bg4)"/>

  <g filter="url(#shadow4)">
    <rect x="90" y="90" width="1420" height="720" rx="30" fill="url(#panel4)" stroke="#d8e3c2"/>
  </g>

  <rect x="130" y="125" width="210" height="54" rx="16" fill="url(#accent4)"/>
  <text x="235" y="160" text-anchor="middle" class="chip">KAPITEL 4</text>

  <!-- TITLE FIXED -->
  <text x="130" y="270" class="title">13:00 Uhr: Mensa,</text>
  <text x="130" y="330" class="title">Sprechstunde oder Kochen?</text>

  <!-- Card 1 -->
  <rect x="130" y="380" width="400" height="320" rx="22" fill="#f6f9f1" stroke="#dfe8ce"/>
  <text x="160" y="430" class="head">Uhrzeiten</text>
  <text x="160" y="470" class="bullet">• Uhrzeiten</text>
  <text x="160" y="500" class="bullet">• Tageszeiten</text>
  <text x="160" y="530" class="bullet">• Monate</text>
  <text x="160" y="560" class="bullet">• Jahreszeiten</text>
  <text x="160" y="590" class="bullet">• Aufgaben an der Universität</text>
  <text x="160" y="620" class="bullet">• Tätigkeiten im Haushalt</text>

  <!-- Card 2 -->
  <rect x="600" y="380" width="400" height="320" rx="22" fill="#f8faf4" stroke="#dfe8ce"/>
  <text x="630" y="430" class="head">Zeitangaben</text>
  <text x="630" y="470" class="bullet">• Zeitangaben im Gespräch verstehen</text>
  <text x="630" y="500" class="bullet">• Uhrzeiten verstehen und sagen</text>
  <text x="630" y="530" class="bullet">• sich verabreden</text>
  <text x="630" y="560" class="bullet">• Daten verstehen</text>
  <text x="630" y="590" class="bullet">• Termine mündlich weitergeben</text>
  <text x="630" y="620" class="bullet">• formelle / informelle E-Mail</text>

  <!-- Card 3 -->
  <rect x="1070" y="380" width="400" height="320" rx="22" fill="#f6f9f1" stroke="#dfe8ce"/>
  <text x="1100" y="430" class="head">Grammatik</text>
  <text x="1100" y="470" class="bullet">• Modalverben im Präsens: müssen</text>
  <text x="1100" y="500" class="bullet">• temporale Präpositionen</text>
  <text x="1100" y="530" class="bullet">• um, am, im, von … bis</text>
  <text x="1100" y="560" class="bullet">• trennbare Vorsilben</text>

  <line x1="130" y1="760" x2="1470" y2="760" stroke="#d8e3c2"/>
  <text x="130" y="800" class="footer">Deutsch A1.1</text>
</svg>

# 🤖 Offline Chatbot

<div id="c4learnbot" style="background:linear-gradient(135deg,#f7faf0,#ffffff);border:3px solid #9fb522;border-radius:24px;padding:24px;box-shadow:0 10px 28px rgba(0,0,0,.14);font-family:Arial,sans-serif;">

<h2 style="margin-top:0;color:#6f7f1f;">🤖 Kapitel 4 Practice Lernbot</h2>

<p style="font-size:17px;line-height:1.6;">
Ask me about <b>Uhrzeit</b>, <b>müssen</b>, <b>Tageszeiten</b>, <b>Daten</b>, <b>temporale Präpositionen</b>, <b>E-Mail</b>, <b>Social Cooking</b>, <b>trennbare Verben</b>, <b>Meinung</b>, and <b>Veranstaltungen</b>.
</p>

<div id="c4l-output" style="background:white;border-left:8px solid #9fb522;border-radius:16px;padding:18px;min-height:170px;max-height:380px;overflow:auto;line-height:1.7;margin-bottom:14px;">
<b>Bot:</b> Hallo! Ask me a Kapitel 4 question 😊
</div>

<div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:18px;">
<input id="c4l-input" placeholder="Example: Explain müssen" style="flex:1;min-width:260px;padding:13px;border:2px solid #9fb522;border-radius:12px;font-size:16px;">
<button id="c4l-ask" type="button" style="padding:13px 20px;border-radius:12px;border:none;background:#9fb522;color:white;font-weight:bold;cursor:pointer;">Ask</button>
<button id="c4l-clear" type="button" style="padding:13px 20px;border-radius:12px;border:1px solid #9fb522;background:white;color:#6f8120;font-weight:bold;cursor:pointer;">Clear</button>
</div>

<h3 style="color:#6f7f1f;">💡 Quick Questions</h3>
<div id="c4l-quick" style="display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:10px;"></div>

</div>

<script>
void setTimeout(function(){

  const output = document.getElementById("c4l-output");
  const input = document.getElementById("c4l-input");
  const askBtn = document.getElementById("c4l-ask");
  const clearBtn = document.getElementById("c4l-clear");
  const quickBox = document.getElementById("c4l-quick");

  const questions = [
    "What is Kapitel 4 about?",
    "Explain müssen",
    "How do I conjugate müssen?",
    "Explain word order with müssen",
    "Difference between müssen können wollen",
    "Explain Uhrzeiten",
    "What does halb vier mean?",
    "What does Viertel nach mean?",
    "What does Viertel vor mean?",
    "Explain Tageszeiten",
    "Explain dates in German",
    "Explain months and seasons",
    "When do we use am?",
    "When do we use im?",
    "When do we use um?",
    "Explain von bis",
    "How to write a formal email?",
    "How to write an informal email?",
    "What is Social Cooking?",
    "Explain kitchen vocabulary",
    "What are separable verbs?",
    "Explain einkaufen",
    "Explain ausfüllen",
    "Explain einladen",
    "How do I express opinions?",
    "Explain Veranstaltungen",
    "What are W-Fragen?",
    "Give speaking practice"
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

    if(hasAny(q, ["kapitel 4", "chapter 4", "overview", "about"])){
      return card("Kapitel 4 Overview",
        "Kapitel 4 is about time, appointments, university tasks, household activities, dates, emails, Social Cooking, separable verbs, opinions, and events.<br><br>" +
        "Main learning goals:<br>" +
        "• say times and dates<br>" +
        "• arrange meetings<br>" +
        "• use müssen, können, wollen<br>" +
        "• use am, im, um, von ... bis<br>" +
        "• write formal and informal emails<br>" +
        "• use separable verbs.");
    }

    if(hasAny(q, ["uni und haushalt", "university household", "prüfung", "klausur", "referat", "zimmer"])){
      return card("Uni und Haushalt",
        "Important phrases:<br><br>" +
        "• eine Prüfung haben = to have an exam<br>" +
        "• eine Klausur schreiben = to take/write an exam<br>" +
        "• ein Zimmer aufräumen = to tidy a room<br>" +
        "• ein Referat halten = to give a presentation<br><br>" +
        "Example:<br>Ich muss morgen eine Klausur schreiben.");
    }

    if(hasAny(q, ["müssen", "muessen", "must", "have to"])){
      return card("Modalverb müssen",
        "<b>müssen</b> means <i>must / have to</i>.<br><br>" +
        "Conjugation:<br>" +
        "ich muss<br>" +
        "du musst<br>" +
        "er/sie/es muss<br>" +
        "wir müssen<br>" +
        "ihr müsst<br>" +
        "sie/Sie müssen<br><br>" +
        "Examples:<br>" +
        "Ich muss lernen.<br>" +
        "William muss drei Klausuren schreiben.<br>" +
        "Wir müssen ein Referat halten.");
    }

    if(hasAny(q, ["word order", "satzbau", "position 2", "infinitive", "verb at the end"])){
      return card("Word Order with Modal Verbs",
        "With modal verbs:<br><br>" +
        "✅ modal verb = Position 2<br>" +
        "✅ main verb = infinitive at the end<br><br>" +
        "Examples:<br>" +
        "William muss viel lernen.<br>" +
        "Ich muss heute mein Zimmer aufräumen.<br>" +
        "Wann müsst ihr das Referat halten?<br><br>" +
        "Structure:<br>Subject / question word + modal verb + middle + infinitive.");
    }

    if(hasAny(q, ["müssen können wollen", "muessen koennen wollen", "difference between müssen", "difference between koennen", "difference between wollen"])){
      return card("müssen, können, wollen",
        "<b>müssen</b> = must / have to<br>" +
        "Ich muss arbeiten.<br><br>" +
        "<b>können</b> = can / be able to<br>" +
        "Ich kann Freunde treffen.<br><br>" +
        "<b>wollen</b> = want to<br>" +
        "Wir wollen einen Film sehen.<br><br>" +
        "All three are modal verbs. The second verb goes to the end.");
    }

    if(hasAny(q, ["uhrzeit", "uhrzeiten", "time", "clock", "halb", "viertel", "nach", "vor"])){
      return card("Uhrzeiten",
        "Important informal time words:<br><br>" +
        "• Viertel nach = quarter past<br>" +
        "• halb = half to the next hour<br>" +
        "• Viertel vor = quarter to<br>" +
        "• nach = after<br>" +
        "• vor = before<br><br>" +
        "Examples:<br>" +
        "Viertel nach zwei = 02:15<br>" +
        "halb vier = 03:30<br>" +
        "Viertel vor elf = 10:45<br><br>" +
        "Important: halb vier means 3:30, not 4:30.");
    }

    if(hasAny(q, ["halb vier", "halb zwölf", "halb zwoelf", "halb"])){
      return card("halb + next hour",
        "In German, <b>halb</b> uses the next hour.<br><br>" +
        "halb vier = 03:30 / 15:30<br>" +
        "halb sieben = 06:30 / 18:30<br>" +
        "halb zwölf = 11:30<br><br>" +
        "Think: halfway to the next hour.");
    }

    if(hasAny(q, ["tageszeiten", "morning", "evening", "morgens", "abends", "nachts", "vormittags"])){
      return card("Tageszeiten",
        "Tageszeiten are parts of the day:<br><br>" +
        "• der Morgen / morgens<br>" +
        "• der Vormittag / vormittags<br>" +
        "• der Mittag / mittags<br>" +
        "• der Nachmittag / nachmittags<br>" +
        "• der Abend / abends<br>" +
        "• die Nacht / nachts<br><br>" +
        "Examples:<br>Morgens trinke ich Kaffee.<br>Abends lerne ich Deutsch.");
    }

    if(hasAny(q, ["daten", "date", "dates", "ordinal", "zwölfte", "achten", "monat", "monate"])){
      return card("Dates in German",
        "German dates use ordinal numbers.<br><br>" +
        "Today is:<br>der zwölfte März<br><br>" +
        "With <b>am</b>:<br>am zwölften März<br><br>" +
        "Examples:<br>" +
        "12.3. = der zwölfte März / am zwölften März<br>" +
        "8.9. = der achte September / am achten September<br>" +
        "6.5. = der sechste Mai / am sechsten Mai.");
    }

    if(hasAny(q, ["months", "seasons", "monate", "jahreszeiten", "frühling", "sommer", "herbst", "winter"])){
      return card("Monate und Jahreszeiten",
        "Frühling: März, April, Mai<br>" +
        "Sommer: Juni, Juli, August<br>" +
        "Herbst: September, Oktober, November<br>" +
        "Winter: Dezember, Januar, Februar<br><br>" +
        "Example:<br>Im Sommer habe ich Ferien.");
    }

    if(hasAny(q, ["am", "use am"])){
      return card("When do we use am?",
        "Use <b>am</b> for:<br><br>" +
        "• days: am Montag<br>" +
        "• dates: am fünften Februar<br>" +
        "• parts of the day: am Abend, am Nachmittag<br><br>" +
        "Examples:<br>Am Mittwoch muss ich lernen.<br>Die Prüfung ist am fünften Februar.");
    }

    if(hasAny(q, ["im", "use im"])){
      return card("When do we use im?",
        "Use <b>im</b> for:<br><br>" +
        "• months: im August<br>" +
        "• seasons: im Sommer, im Winter<br><br>" +
        "Examples:<br>Ich habe im August Ferien.<br>Im Herbst beginnt das Semester.");
    }

    if(hasAny(q, ["um", "use um"])){
      return card("When do we use um?",
        "Use <b>um</b> for exact clock times.<br><br>" +
        "Examples:<br>" +
        "um zwei<br>" +
        "um 14 Uhr<br>" +
        "um halb acht<br>" +
        "um Viertel nach drei");
    }

    if(hasAny(q, ["von bis", "vom bis", "von ... bis", "period"])){
      return card("von ... bis / vom ... bis zum",
        "Use <b>von ... bis</b> for time periods:<br>" +
        "von Montag bis Freitag<br>" +
        "von drei bis fünf<br><br>" +
        "Use <b>vom ... bis zum</b> with dates:<br>" +
        "vom ersten Juli bis zum einunddreißigsten August.");
    }

    if(hasAny(q, ["email", "e-mail", "formal", "informal", "formelle", "informelle", "termin"])){
      return card("Formal and Informal E-Mail",
        "Formal email:<br>" +
        "Sehr geehrte Frau Müller,<br>" +
        "Haben Sie am Montag Sprechstunde?<br>" +
        "Mit freundlichen Grüßen<br><br>" +
        "Informal email:<br>" +
        "Lieber Florian,<br>" +
        "Hast du am 18. September Sprechstunde?<br>" +
        "Viele Grüße<br><br>" +
        "Formal uses <b>Sie</b>. Informal uses <b>du</b>.");
    }

    if(hasAny(q, ["social cooking", "cooking", "kochen", "zutaten", "spülmaschine", "geschirr", "abwaschen"])){
      return card("Social Cooking",
        "Social Cooking means cooking together with other people.<br><br>" +
        "Important words:<br>" +
        "• die Zutaten = ingredients<br>" +
        "• das Geschirr = dishes<br>" +
        "• die Spülmaschine = dishwasher<br>" +
        "• abwaschen = wash dishes<br>" +
        "• abtrocknen = dry dishes<br>" +
        "• einkaufen = go shopping<br><br>" +
        "Example:<br>Die Gäste bringen die Zutaten mit.");
    }

    if(hasAny(q, ["w fragen", "w-fragen", "question words", "wer", "was", "wo", "wie", "wann"])){
      return card("W-Fragen",
        "Important W-question words:<br><br>" +
        "• Wer? = Who?<br>" +
        "• Was? = What?<br>" +
        "• Wo? = Where?<br>" +
        "• Wie? = How?<br>" +
        "• Wann? = When?<br><br>" +
        "Examples:<br>" +
        "Was kann Social Cooking sein?<br>" +
        "Wie funktioniert Social Cooking?<br>" +
        "Wo kochen alle das Essen?<br>" +
        "Wer muss das Geschirr abwaschen?");
    }

    if(hasAny(q, ["trennbare", "separable", "vorsilbe", "einkaufen", "ausfüllen", "ausfuellen", "einladen", "teilnehmen", "aufraeumen", "aufräumen"])){
      return card("Trennbare Verben",
        "Separable verbs split in normal sentences.<br><br>" +
        "Examples:<br>" +
        "ausfüllen → Ich fülle das Formular aus.<br>" +
        "mitbringen → Die Gäste bringen die Zutaten mit.<br>" +
        "einkaufen → Wir kaufen heute ein.<br>" +
        "aufräumen → Ich räume mein Zimmer auf.<br><br>" +
        "Rule:<br>conjugated verb = Position 2, prefix = end of sentence.");
    }

    if(hasAny(q, ["ausschlafen", "einladen", "conjugate einladen", "conjugate ausschlafen"])){
      return card("ausschlafen und einladen",
        "ausschlafen:<br>" +
        "ich schlafe aus<br>" +
        "du schläfst aus<br>" +
        "er/sie/es schläft aus<br>" +
        "wir schlafen aus<br><br>" +
        "einladen:<br>" +
        "ich lade ein<br>" +
        "du lädst ein<br>" +
        "er/sie/es lädt ein<br>" +
        "wir laden ein<br><br>" +
        "Notice: du and er/sie/es have vowel changes.");
    }

    if(hasAny(q, ["stress", "betonung", "betont", "pronunciation", "aussprache"])){
      return card("Stress in Separable Verbs",
        "In many separable verbs, the prefix is stressed.<br><br>" +
        "Examples:<br>" +
        "AUSfüllen<br>" +
        "MITbringen<br>" +
        "ABwaschen<br>" +
        "EINkaufen<br><br>" +
        "Non-separable verbs often stress the middle/root:<br>" +
        "erGÄNzen, verGLEIchen, beSTELLen.");
    }

    if(hasAny(q, ["meinung", "opinion", "positive", "negative", "spannend", "stressig", "gefährlich", "komisch"])){
      return card("Seine Meinung äußern",
        "Use <b>Ich finde ...</b> to express opinions.<br><br>" +
        "Positive words:<br>" +
        "eine tolle Idee, interessant, lustig, spannend<br><br>" +
        "Negative words:<br>" +
        "gefährlich, komisch, stressig, keine tolle Idee<br><br>" +
        "Examples:<br>" +
        "Ich finde das spannend.<br>" +
        "Ich finde das stressig.");
    }

    if(hasAny(q, ["veranstaltungen", "events", "party", "konzert", "beachvolleyball", "einladung"])){
      return card("Veranstaltungen",
        "Important event words:<br><br>" +
        "• die Klausur = exam<br>" +
        "• die Party = party<br>" +
        "• das Konzert = concert<br>" +
        "• das Beachvolleyballspiel = beach volleyball game<br>" +
        "• das Turnier = tournament<br>" +
        "• teilnehmen = participate<br><br>" +
        "For an event, ask:<br>" +
        "Wann? Was? Wer? Wo? Wie?");
    }

    if(hasAny(q, ["speaking", "practice", "conversation", "dialogue"])){
      return card("Speaking Practice",
        "Practice dialogue:<br><br>" +
        "A: Gehen wir heute in die Mensa?<br>" +
        "B: Gern. Geht es um halb vier?<br>" +
        "A: Das geht leider nicht. Ich muss lernen.<br>" +
        "B: Kannst du um vier?<br>" +
        "A: Ja, das passt gut.<br><br>" +
        "Now change the time and activity.");
    }

    if(hasAny(q, ["vocabulary", "words", "important words"])){
      return card("Kapitel 4 Vocabulary",
        "Important words:<br><br>" +
        "die Klausur, die Prüfung, das Referat, die Sprechstunde, die Mensa, die Uhrzeit, der Termin, die Tageszeit, der Monat, die Jahreszeit, die Zutaten, das Geschirr, die Spülmaschine, die Veranstaltung, das Turnier.");
    }

    return card("Question not found",
      "Ask about:<br>" +
      "• müssen<br>" +
      "• Uhrzeiten<br>" +
      "• Tageszeiten<br>" +
      "• Daten<br>" +
      "• am / im / um<br>" +
      "• E-Mail<br>" +
      "• Social Cooking<br>" +
      "• trennbare Verben<br>" +
      "• Meinung<br>" +
      "• Veranstaltungen");
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
    output.innerHTML = "<b>Bot:</b> Hallo! Ask me a Kapitel 4 question 😊";
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

# 1 Uni und Haushalt

 ## Ergänzen Sie die passenden Verben. Zwei Verben passen nicht.

>**Verben:** aufräumen · haben · halten · lernen · schreiben · sprechen

1. eine Prüfung ~~haben~~


2. eine Klausur [[schreiben]]


3. ein Zimmer [[aufräumen]]


4. ein Referat [[halten]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Uni und Haushalt</b></summary>

In this exercise, you match:
✅ nouns  
with  
✅ the correct verbs.

---

## Helpful strategy

Ask yourself:

👉 What do people normally do?

Examples:

- eine Klausur → schreiben  
- ein Zimmer → aufräumen  
- ein Referat → halten  

---

## Important vocabulary

| Nomen | Verb |
|---|---|
| die Prüfung | haben |
| die Klausur | schreiben |
| das Zimmer | aufräumen |
| das Referat | halten |

---

## Two verbs do NOT fit

⚠️ Not every verb matches.

You must choose:
✅ the most logical verb.

---

## Helpful examples

🗣️ Ich habe eine Prüfung.  
🗣️ Wir schreiben eine Klausur.  
🗣️ Er räumt sein Zimmer auf.  
🗣️ Sie hält ein Referat.

---

## Grammar tip

Some verbs are separable:

✅ aufräumen → räumt … auf

Example:

🗣️ Ich räume mein Zimmer auf.

---

## Practice tip

Read the noun first:
👉 “eine Klausur”

Then ask:
👉 “What do students do with a Klausur?”

✅ schreiben

</details>


---

# 2 [GRAMMATIK KOMPAKT] Modalverb **müssen**

 ## a) Ergänzen Sie die passenden Formen von **müssen**.

Alle haben viel zu tun:

William [[muss]] (1) drei Klausuren schreiben.  


William und Chiara [[müssen]] (2) ein Referat halten.  


Wir [[müssen]] (3) viel lernen.  


Nur Moritz [[muss]] (4) nicht lernen, aber er [[muss]] (5) arbeiten.  


Was [[müsst]] (6) ihr machen?  


---

 ## b) Wo steht **müssen**? Schreiben Sie die Sätze in die Tabelle.

1. lernen · William · muss · viel · .  
2. muss · heute mein Zimmer · aufräumen · ich · .  
3. ihr · halten · das Referat · müsst · wann · ?  
4. wir · warum · arbeiten · am Sonntag · müssen · ?  
5. schreiben · viele · du · musst · Klausuren · .  
6. ein Formular · die Studierenden · ausfüllen · müssen · .

| Nr. | Position 1 | Position 2 | Mitte | Satzende |
|----|------------|------------|-------|----------|
| 1 | [[William]] | [[muss]] | [[viel]] | [[lernen.]] |
| 2 | [[Ich]] | [[muss]] | [[heute mein Zimmer]] | [[aufräumen.]] |
| 3 | [[Wann]] | [[müsst]] | [[ihr das Referat]] | [[halten?]] |
| 4 | [[Warum]] | [[müssen]] | [[wir am Sonntag]] | [[arbeiten?]] |
| 5 | [[Du]] | [[musst]] | [[viele Klausuren]] | [[schreiben.]] |
| 6 | [[Die Studierenden]] | [[müssen]] | [[ein Formular]] | [[ausfüllen.]] |


---

 ## c) Ergänzen Sie die passenden Formen von **müssen** oder **können**.

1. Moritz [[muss]] heute nicht arbeiten. Er kann Freunde treffen.  

2. William [[kann]] heute nicht trainieren. Er muss lernen.  

3. Moritz [[kann]] heute nicht kochen. Er isst in der Mensa.  

4. William [[kann]] heute nicht ausschlafen. Er hat eine Prüfung.  

5. Chiara und William [[können]] heute nicht zusammen lernen. Chiara hält ein Referat.  


---

 ## d) **müssen, können oder wollen?** Ergänzen Sie die passenden Formen.

1. Am Mittwoch [[muss]] ich ein Referat halten. Aber wir [[können]] am Donnerstag Sport machen.  

2. Ich will nicht mehr lernen. Aber ich [[muss]] noch viele Klausuren schreiben.  

3. 😊 [[Wollen]] wir heute zusammen einen Film sehen? Ich muss nicht lernen.

4. Du [[musst]] nicht kommen. William und ich [[wollen]] das machen.  

5. Ich [[kann]] ausschlafen. Aber ich [[muss]] um 9:00 Uhr arbeiten. 

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Modalverb „müssen“</b></summary>

# 🟢 Modalverb: müssen

## Meaning

✅ müssen = “must / have to”

Examples:

- Ich muss lernen.  
- Wir müssen arbeiten.  
- Du musst ein Referat halten.

---

# 🟡 Part a) Formen von müssen

## Konjugation

| Person | müssen |
|---|---|
| ich | muss |
| du | musst |
| er / sie | muss |
| wir | müssen |
| ihr | müsst |
| sie / Sie | müssen |

---

## Helpful strategy

Look at the subject first:

- William → muss  
- William und Chiara → müssen  
- wir → müssen  
- ihr → müsst

---

# 🟢 Part b) Satzbau mit müssen

## Important rule

✅ Modalverb = Position 2  
✅ Main verb (Infinitiv) = Satzende

---

## Example

🗣️ William muss viel lernen.

| Position 1 | Position 2 | Mitte | Satzende |
|---|---|---|---|
| William | muss | viel | lernen |

---

## Question words

Questions start with:

- Wann  
- Warum

Examples:

🗣️ Wann müsst ihr das Referat halten?  
🗣️ Warum müssen wir am Sonntag arbeiten?

---

# 🟡 Part c) müssen oder können

## Difference

✅ müssen = obligation  
➡ have to

✅ können = possibility / ability  
➡ can

---

## Examples

🗣️ William muss lernen.  
(He has to study.)

🗣️ Moritz kann Freunde treffen.  
(He can meet friends.)

---

# 🟢 Part d) müssen, können oder wollen

## Meanings

| Verb | Meaning |
|---|---|
| müssen | must / have to |
| können | can |
| wollen | want to |

---

## Helpful examples

🗣️ Ich muss arbeiten.  
🗣️ Wir können Sport machen.  
🗣️ Wollen wir einen Film sehen?

---

# ⚠️ Grammar tip

With modal verbs:

✅ the second verb stays in infinitive form.

Examples:

- muss lernen  
- kann kochen  
- wollen arbeiten

</details>


# ⏰ Uhrzeiten

<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="330" viewBox="0 0 1200 330">
  <defs>
    <style>
      .label{font:700 18px Arial,sans-serif;fill:#243b3b}
      .num{font:700 18px Arial,sans-serif;fill:#6b7f1c}
      .clockFace{fill:#e8f4f3;stroke:#7ba7a3;stroke-width:8}
      .handHour{stroke:#333;stroke-width:6;stroke-linecap:round}
      .handMin{stroke:#333;stroke-width:5;stroke-linecap:round}
      .center{fill:#333}
      .tick{stroke:#466;stroke-width:3;stroke-linecap:round}
    </style>
  </defs>

  <rect width="1200" height="330" rx="24" fill="#f7fbef"/>
  <text x="40" y="45" font="700 28px Arial" fill="#6b7f1c">Uhrzeiten</text>
  <text x="40" y="78" font="500 18px Arial" fill="#59634f">Wie viel Uhr ist es? Notieren Sie die informelle Uhrzeit.</text>

  <!-- Function-like repeated ticks drawn per clock -->

  <!-- Clock 1: 02:15 -->
  <g transform="translate(70,105)">
    <text x="0" y="0" class="num">1</text>
    <circle cx="80" cy="80" r="62" class="clockFace"/>
    <g transform="translate(80,80)">
      <line x1="0" y1="-54" x2="0" y2="-46" class="tick"/>
      <line x1="54" y1="0" x2="46" y2="0" class="tick"/>
      <line x1="0" y1="54" x2="0" y2="46" class="tick"/>
      <line x1="-54" y1="0" x2="-46" y2="0" class="tick"/>
      <line x1="0" y1="0" x2="48" y2="0" class="handMin"/>
      <line x1="0" y1="0" x2="24" y2="-42" class="handHour"/>
      <circle r="5" class="center"/>
    </g>
    <text x="80" y="170" text-anchor="middle" class="label"></text>
  </g>

  <!-- Clock 2: 03:30 -->
  <g transform="translate(290,105)">
    <text x="0" y="0" class="num">2</text>
    <circle cx="80" cy="80" r="62" class="clockFace"/>
    <g transform="translate(80,80)">
      <line x1="0" y1="-54" x2="0" y2="-46" class="tick"/>
      <line x1="54" y1="0" x2="46" y2="0" class="tick"/>
      <line x1="0" y1="54" x2="0" y2="46" class="tick"/>
      <line x1="-54" y1="0" x2="-46" y2="0" class="tick"/>
      <line x1="0" y1="0" x2="0" y2="50" class="handMin"/>
      <line x1="0" y1="0" x2="31" y2="31" class="handHour"/>
      <circle r="5" class="center"/>
    </g>
    <text x="80" y="170" text-anchor="middle" class="label"></text>
  </g>

  <!-- Clock 3: 04:25 -->
  <g transform="translate(510,105)">
    <text x="0" y="0" class="num">3</text>
    <circle cx="80" cy="80" r="62" class="clockFace"/>
    <g transform="translate(80,80)">
      <line x1="0" y1="-54" x2="0" y2="-46" class="tick"/>
      <line x1="54" y1="0" x2="46" y2="0" class="tick"/>
      <line x1="0" y1="54" x2="0" y2="46" class="tick"/>
      <line x1="-54" y1="0" x2="-46" y2="0" class="tick"/>
      <line x1="0" y1="0" x2="25" y2="43" class="handMin"/>
      <line x1="0" y1="0" x2="-38" y2="-10" class="handHour"/>
      <circle r="5" class="center"/>
    </g>
    <text x="80" y="170" text-anchor="middle" class="label"></text>
  </g>

  <!-- Clock 4: 09:20 -->
  <g transform="translate(730,105)">
    <text x="0" y="0" class="num">4</text>
    <circle cx="80" cy="80" r="62" class="clockFace"/>
    <g transform="translate(80,80)">
      <line x1="0" y1="-54" x2="0" y2="-46" class="tick"/>
      <line x1="54" y1="0" x2="46" y2="0" class="tick"/>
      <line x1="0" y1="54" x2="0" y2="46" class="tick"/>
      <line x1="-54" y1="0" x2="-46" y2="0" class="tick"/>
      <line x1="0" y1="0" x2="43" y2="25" class="handMin"/>
      <line x1="0" y1="0" x2="-40" y2="-5" class="handHour"/>
      <circle r="5" class="center"/>
    </g>
    <text x="80" y="170" text-anchor="middle" class="label"></text>
  </g>

  <!-- Clock 5: 10:45 -->
  <g transform="translate(950,105)">
    <text x="0" y="0" class="num">5</text>
    <circle cx="80" cy="80" r="62" class="clockFace"/>
    <g transform="translate(80,80)">
      <line x1="0" y1="-54" x2="0" y2="-46" class="tick"/>
      <line x1="54" y1="0" x2="46" y2="0" class="tick"/>
      <line x1="0" y1="54" x2="0" y2="46" class="tick"/>
      <line x1="-54" y1="0" x2="-46" y2="0" class="tick"/>
      <line x1="0" y1="0" x2="-50" y2="0" class="handMin"/>
      <line x1="0" y1="0" x2="27" y2="-34" class="handHour"/>
      <circle r="5" class="center"/>
    </g>
    <text x="80" y="170" text-anchor="middle" class="label"></text>
  </g>
</svg>

 ## a) Wie viel Uhr ist es? Notieren Sie die informelle Uhrzeit.

1. [[Viertel nach zwei]]   

2. [[halb vier]]   

3. [[fünf vor halb fünf]]  

4. [[zwanzig nach neun]]   

5. [[Viertel vor elf]]  


---

 ## b) Wie spät ist es? Hören Sie und kreuzen Sie an.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_025.mp3?raw=true)

1.  
[[ ]] 15:30 Uhr  
[[x]] 16:30 Uhr  

2.  
[[x]] 10:15 Uhr  
[[ ]] 10:45 Uhr  

3.  
[[ ]] 09:25 Uhr  
[[x]] 09:55 Uhr  

4.  
[[x]] 11:10 Uhr  
[[ ]] 10:50 Uhr  

---

 ## c) Formelle und informelle Uhrzeiten. Was passt zusammen?

1. Viertel vor acht → [[07:45 Uhr]]  

2. zwanzig nach vier → [[16:20 Uhr]]  

3. fünf vor halb zwölf → [[11:25 Uhr]]   

4. zehn nach neun → [[09:10 Uhr]]   

5. halb sieben → [[06:30 Uhr]]   

6. Viertel nach drei → [[15:15 Uhr]]  
 
<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Uhrzeiten</b></summary>

# 🕒 Informelle Uhrzeiten

In German there are:

✅ formelle Uhrzeiten  
and  
✅ informelle Uhrzeiten

---

# 🟢 Important expressions

| Informell | Meaning |
|---|---|
| Viertel nach | :15 |
| halb | :30 |
| Viertel vor | :45 |
| fünf vor halb | 5 minutes before half |

---

# 🟡 Examples

🕒 02:15  
➡ Viertel nach zwei

🕒 03:30  
➡ halb vier

🕒 10:45  
➡ Viertel vor elf

---

# ⚠️ Important rule with „halb“

German uses the NEXT hour.

Example:

🕒 03:30  
✅ halb vier  
❌ halb drei

Because it is halfway TO four.

---

# 🟢 Part a) Clock strategy

Look at:

✅ minute hand  
✅ hour hand

Then ask:

- Is it :15? → Viertel nach  
- Is it :30? → halb  
- Is it :45? → Viertel vor

---

# 🟡 Part b) Listening strategy

Listen carefully for:

- Viertel nach
- halb
- vor
- nach

Examples:

🗣️ Viertel nach zehn  
➡ 10:15

🗣️ fünf vor zehn  
➡ 09:55

---

# 🟢 Part c) Formell ↔ informell

## Examples

| Informell | Formell |
|---|---|
| Viertel vor acht | 07:45 |
| halb sieben | 06:30 |
| Viertel nach drei | 15:15 |

---

# 🧠 Helpful tip

German informal time often uses:

- nach = after
- vor = before
- halb = half to next hour

</details>

# 📅 Sich verabreden

 ## Welche Antwort passt nicht? Streichen Sie durch.

1. Lernen wir heute zusammen?  
[[ ]] Das passt gut.  
[[ ]] Ja, das geht.  
[[x]] Bis dann!  

---

2. Wann?  
[[ ]] Kannst du um halb vier?  
[[x]] Morgen habe ich eine Vorlesung.  
[[ ]] Geht es um halb vier?  

---

3. Kannst du um halb vier?  
[[ ]] Ja, okay.  
[[ ]] Das geht leider nicht.  
[[x]] Das mache ich gern.  

---



---

# 1 Tageszeiten

 ## Ordnen Sie die Tageszeiten zu.

<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="360" viewBox="0 0 1375 375">
  <defs>
    <style>
      .txt{font:500 22px Arial;fill:#222}
      .blank{stroke:#999;stroke-width:2}
    </style>
  </defs>

  <rect width="1375" height="375" fill="#ffffff"/>

  <g transform="translate(0,0)">
    <rect width="170" height="95" rx="10" fill="#b8e2ef"/>
    <circle cx="35" cy="75" r="20" fill="#ffc94a"/>
    <path d="M0 82 C40 65 80 90 120 70 C145 58 160 70 170 60 L170 95 L0 95Z" fill="#5f8b63"/>
    <text x="210" y="42" class="txt">1. der Morgen / morgens</text>
    <line x1="210" y1="65" x2="600" y2="65" class="blank"/>
  </g>

  <g transform="translate(0,120)">
    <rect width="170" height="95" rx="10" fill="#98d9ee"/>
    <circle cx="45" cy="35" r="22" fill="#ffc94a"/>
    <path d="M0 80 C55 65 90 88 135 70 C150 65 160 70 170 64 L170 95 L0 95Z" fill="#5f8b63"/>
    <text x="210" y="42" class="txt">2.</text>
    <line x1="250" y1="42" x2="600" y2="42" class="blank"/>
    <line x1="250" y1="75" x2="600" y2="75" class="blank"/>
  </g>

  <g transform="translate(0,240)">
    <rect width="170" height="95" rx="10" fill="#89d7ea"/>
    <circle cx="85" cy="28" r="23" fill="#ffc94a"/>
    <path d="M0 82 C50 64 100 88 145 68 C158 62 165 68 170 64 L170 95 L0 95Z" fill="#5f8b63"/>
    <text x="210" y="42" class="txt">3.</text>
    <line x1="250" y1="42" x2="600" y2="42" class="blank"/>
    <line x1="250" y1="75" x2="600" y2="75" class="blank"/>
  </g>

  <g transform="translate(765,0)">
    <rect width="170" height="95" rx="10" fill="#7fd3e8"/>
    <circle cx="125" cy="25" r="24" fill="#ffc94a"/>
    <path d="M0 82 C60 66 105 88 150 68 C160 64 166 66 170 62 L170 95 L0 95Z" fill="#5f8b63"/>
    <text x="210" y="42" class="txt">4.</text>
    <line x1="250" y1="42" x2="610" y2="42" class="blank"/>
    <line x1="250" y1="75" x2="610" y2="75" class="blank"/>
  </g>

  <g transform="translate(765,120)">
    <rect width="170" height="95" rx="10" fill="#f2a36f"/>
    <circle cx="130" cy="70" r="28" fill="#ee6c45"/>
    <path d="M0 82 C60 66 105 88 150 68 C160 64 166 66 170 62 L170 95 L0 95Z" fill="#5f8b63"/>
    <text x="210" y="42" class="txt">5.</text>
    <line x1="250" y1="42" x2="610" y2="42" class="blank"/>
    <line x1="250" y1="75" x2="610" y2="75" class="blank"/>
  </g>

  <g transform="translate(765,240)">
    <rect width="170" height="95" rx="10" fill="#1f355d"/>
    <path d="M120 28 C105 30 100 18 110 8 C108 28 126 35 138 20 C135 28 130 32 120 28Z" fill="#ffe58a"/>
    <path d="M0 82 C60 66 105 88 150 68 C160 64 166 66 170 62 L170 95 L0 95Z" fill="#315d48"/>
    <text x="210" y="42" class="txt">6.</text>
    <line x1="250" y1="42" x2="610" y2="42" class="blank"/>
    <line x1="250" y1="75" x2="610" y2="75" class="blank"/>
  </g>
</svg>

>**Wörter:**  der Abend / abends · der Mittag / mittags · der Morgen / morgens · der Nachmittag / nachmittags · die Nacht / nachts · der Vormittag / vormittags

---

1. [[der Morgen / morgens]]  

2. [[der Vormittag / vormittags]]  

3. [[der Mittag / mittags]]  

4. [[der Nachmittag / nachmittags]]  

5. [[der Abend / abends]]  

6. [[die Nacht / nachts]]  

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Tageszeiten</b></summary>

# 🌅 Tageszeiten

In this exercise, you practice:
✅ parts of the day  
✅ time vocabulary  
✅ matching pictures with words

---

## Important words

| Deutsch | English |
|---|---|
| der Morgen / morgens | morning / in the morning |
| der Vormittag / vormittags | late morning / in the late morning |
| der Mittag / mittags | noon / at noon |
| der Nachmittag / nachmittags | afternoon / in the afternoon |
| der Abend / abends | evening / in the evening |
| die Nacht / nachts | night / at night |

---

## Helpful strategy

Look at the picture:

🌅 Sun is rising  
➡ der Morgen

☀️ Sun is high  
➡ der Mittag

🌇 Sun is going down  
➡ der Abend

🌙 Moon / dark sky  
➡ die Nacht

---

## Difference: noun and adverb

| Noun | Adverb |
|---|---|
| der Morgen | morgens |
| der Mittag | mittags |
| der Abend | abends |
| die Nacht | nachts |

---

## Examples

🗣️ Am Morgen lerne ich Deutsch.  
🗣️ Morgens trinke ich Kaffee.  

🗣️ Am Abend koche ich.  
🗣️ Abends sehe ich einen Film.

---

## Practice tip

Say the sequence aloud:

🗣️ morgens → vormittags → mittags → nachmittags → abends → nachts

This improves:
✅ vocabulary  
✅ pronunciation  
✅ daily routine speaking

</details>

# 2 Daten

 ## a) Wie heißen die Monate? Ordnen Sie die Monate den Jahreszeiten zu.

**Wörter:**  
BERTEMSEP · ARNUJA · GUSTAU · NIJU · PRILA · NOBERVEM · RUFEBAR · TOOKBER · DEBERZEM · LIJU · IMA · ZRMÄ

---

Frühling: [[März, April, Mai]]  

Sommer: [[Juni, Juli, August]]  

Herbst: [[September, Oktober, November]]  

Winter: [[Dezember, Januar, Februar]]  


---

 ## b) Heute ist der ... – Die Sprechstunde ist am ...

Schreiben Sie wie im Beispiel.

1. 12.3.  
[[der zwölfte März / der zwölfte Dritte; am zwölften März / am zwölften Dritten]]  

2. 8.9.  
[[der achte September / der achte Neunte; am achten September / am achten Neunten]]  

3. 6.5.  
[[der sechste Mai / der sechste Fünfte; am sechsten Mai / am sechsten Fünften]]  

4. 7.7.  
[[der siebte Juli / der siebte Siebte; am siebten Juli / am siebten Siebten]]  


---

 ## c) Lesen Sie die Daten. Hören Sie dann. Welche Daten hören Sie? Markieren Sie.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_026.mp3?raw=true)

[[x]] 07.09.  
[[x]] 03.04.  
[[ ]] 15.10.  
[[x]] 23.12.  
[[x]] 14.05.  
[[ ]] 11.02.  
[[x]] 27.07.  
[[x]] 30.03.  
[[x]] 27.06.  
[[x]] 06.08.  
[[ ]] 17.01.  
[[x]] 20.11.


---

 ## d) Was passt wo? Notieren Sie.

**Wörter:**  
15 Uhr · abends · Dienstag · Februar · Frühjahr · halb vier · Herbst · Juli · mittags · Mittwoch · morgens · Oktober · Samstag · Sommer · Viertel nach drei

| Uhrzeit | Tageszeit | Wochentag | Monat | Jahreszeit |
|--------|-----------|-----------|-------|------------|
| [[15 Uhr]] | [[abends]] | [[Dienstag]] | [[Februar]] | [[Frühjahr]] |
| [[halb vier]] | [[mittags]] | [[Mittwoch]] | [[Juli]] | [[Herbst]] |
| [[Viertel nach drei]] | [[morgens]] | [[Samstag]] | [[Oktober]] | [[Sommer]] |

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Daten, Monate und Jahreszeiten</b></summary>

# 📅 Monate und Jahreszeiten

In this exercise, you practice:

✅ months  
✅ seasons  
✅ dates  
✅ weekdays  
✅ time expressions

---

# 🟢 Part a) Monate ordnen

## Helpful strategy

Unscramble the words first.

Examples:

- ZRMÄ → März  
- PRILA → April  
- IMA → Mai

---

## Jahreszeiten

| Jahreszeit | Monate |
|---|---|
| Frühling | März, April, Mai |
| Sommer | Juni, Juli, August |
| Herbst | September, Oktober, November |
| Winter | Dezember, Januar, Februar |

---

# 🟡 Part b) Daten lesen

## Important rule

### Nominativ

✅ der + ordinal number

Example:

🗣️ der zwölfte März

---

### Dativ with „am“

✅ am + ordinal ending -en

Example:

🗣️ am zwölften März

---

## Helpful examples

| Datum | Example |
|---|---|
| 12.3. | der zwölfte März |
| 8.9. | der achte September |
| 6.5. | der sechste Mai |

---

# 🟢 Part c) Listening strategy

Listen carefully for:

✅ ordinal numbers  
✅ month names  
✅ dates

Examples:

🗣️ der dreiundzwanzigste Dezember  
➡ 23.12.

🗣️ der siebenundzwanzigste Juli  
➡ 27.07.

---

# 🟡 Part d) Categories

You must sort the words into:

| Category | Example |
|---|---|
| Uhrzeit | 15 Uhr |
| Tageszeit | morgens |
| Wochentag | Dienstag |
| Monat | Oktober |
| Jahreszeit | Sommer |

---

# 🧠 Helpful vocabulary

## Uhrzeiten

- 15 Uhr
- halb vier
- Viertel nach drei

## Tageszeiten

- morgens
- mittags
- abends

## Wochentage

- Dienstag
- Mittwoch
- Samstag

## Monate

- Februar
- Juli
- Oktober

## Jahreszeiten

- Frühjahr
- Sommer
- Herbst

---

# ⚠️ Grammar tip

Dates in German often use ordinal numbers:

- erste
- zweite
- dritte
- vierte
- fünfte

Examples:

🗣️ der siebte Juli  
🗣️ am achten September

</details>


# 4B Grammatik Kompakt – Temporale Präpositionen

 ## a) Welche Präposition hören Sie? Markieren Sie.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_027.mp3?raw=true)

1.  
[[x]] am  
[[ ]] im  
[[ ]] um  


---

2.  
[[ ]] am  
[[ ]] im  
[[x]] um  


---

3.  
[[ ]] am  
[[x]] im  
[[ ]] um  


---

4.  
[[ ]] am  
[[ ]] im  
[[x]] um  


---

5.  
[[ ]] am  
[[x]] im  
[[ ]] um  


---

6.  
[[x]] am  
[[ ]] im  
[[ ]] um  


---

 ## b) Frage und Antwort – Ordnen Sie zu.

1. Wann ist die Prüfung? → [[Am fünften Februar]]  

2. Wann hast du Semesterferien? → [[Im August und September]]  

3. Wann ist die Sprechstunde von Prof. Rabenstein? → [[Am Freitagnachmittag]]  

4. Wann essen wir? → [[Um halb acht]]  


---

 ## c) Was ist richtig? Ergänzen Sie die Präpositionen um,am,im,bis,von....bis/vom....bis.

 ### 1
Wann wollen wir zusammen für die Klausur lernen?  
Hast du [[am]] Mittwochnachmittag Zeit? Am Mittwoch muss ich [[um]] zwei in die Sprechstunde.  Aber [[von]] drei [[bis]] fünf habe ich Zeit.  


---

 ### 2.
Wann sind Sommerferien?  
[[Im]] Juli und August, also [[vom]] ersten Juli [[bis zum]] einunddreißigsten August.  


---

 ### 3.
Können wir [[am]] Abend in die Mensa?  [[Von]] Montag [[bis]] Freitag gibt es [[um]] 14 Uhr Mittagessen,  aber [[am]] Nachmittag und [[am]] Abend ist die Mensa geschlossen.  

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – 4B Grammatik Kompakt: Temporale Präpositionen</b></summary>

# 🕒 Temporale Präpositionen

In this section, you learn:

✅ am  
✅ im  
✅ um  
✅ von … bis  
✅ vom … bis zum

These prepositions describe:
📅 time  
📆 dates  
🕐 clock times  
🌤 seasons and months

---

# 🟢 Section A – Welche Präposition hören Sie?

## Important rules

| Präposition | Use |
|---|---|
| um | exact clock time |
| am | days / dates / parts of day |
| im | months / seasons |

---

## Examples

🗣️ um halb acht  
🗣️ am Freitag  
🗣️ am Nachmittag  
🗣️ im August  
🗣️ im Sommer

---

## Listening strategy

Listen for:

- Uhrzeiten → um
- Tage / Datum → am
- Monate / Jahreszeiten → im

---

# 🟡 Section B – Frage und Antwort

## Question word: Wann?

“Wann?” asks about time.

Examples:

🗣️ Wann ist die Prüfung?  
➡ Am fünften Februar.

🗣️ Wann essen wir?  
➡ Um halb acht.

---

## Helpful patterns

| Pattern | Example |
|---|---|
| am + Tag / Datum | am Freitag |
| im + Monat | im August |
| um + Uhrzeit | um halb acht |

---

# 🟢 Section C – Präpositionen ergänzen

## 1️⃣ am / um / von … bis

### Rules

✅ am → day / daytime  
✅ um → exact time  
✅ von … bis → time period

---

## Examples

🗣️ am Mittwochnachmittag  
🗣️ um zwei  
🗣️ von drei bis fünf

---

# 🟡 2️⃣ im / vom … bis zum

## Rules

✅ im → months / seasons  
✅ vom … bis zum → start and end dates

---

## Examples

🗣️ im Juli und August  
🗣️ vom ersten Juli bis zum einunddreißigsten August

---

# 🟢 3️⃣ Mensa example

## Important patterns

| Expression | Meaning |
|---|---|
| am Abend | in the evening |
| von Montag bis Freitag | Monday to Friday |
| um 14 Uhr | at 2 PM |

---

## Example sentences

🗣️ Am Abend ist die Mensa geschlossen.  
🗣️ Von Montag bis Freitag gibt es Mittagessen.  
🗣️ Um 14 Uhr essen wir.

---

# 🧠 Quick grammar summary

| Präposition | Use | Example |
|---|---|---|
| um | Uhrzeit | um 8 Uhr |
| am | Tage / Tageszeiten | am Montag |
| im | Monate / Jahreszeiten | im Sommer |
| von … bis | Zeitraum | von drei bis fünf |
| vom … bis zum | Datum-Zeitraum | vom ersten Juli bis zum fünften August |

</details>

---

# ✉️ Um einen Termin bitten: E-Mail an die Professorin 

 ## a) Was gehört zu einer formellen E-Mail? Kreuzen Sie an.

1.  
[[x]] Sehr geehrte Frau / Herr + Nachname  
[[ ]] Liebe(r) + Vorname  


---

2.  
[[x]] Sie  
[[ ]] du  


---

3.  
[[ ]] Liebe Grüße  
[[x]] Mit freundlichen Grüßen  


---

4.  
[[ ]] nur Vorname  
[[x]] Vorname + Familienname  


---

 ## b) Schreiben Sie eine E-Mail an den Assistenten Florian Maier. Nehmen Sie die E-Mail an Frau Rabenstein als Modell, aber schreiben Sie informell. Schicken Sie die E-Mail an Ihre Lehrerin / Ihren Lehrer.


💡 Beispiel:

[[Lieber Florian,  
ich habe eine Frage zu meiner Seminararbeit.  
Hast du am 18. September Sprechstunde?  
Ich möchte gern einen Termin.  

Viele Grüße  
Masub]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Um einen Termin bitten: E-Mail</b></summary>

# ✉️ Formelle und informelle E-Mails

In this section, you learn:

✅ formal email style  
✅ informal email style  
✅ greetings and endings  
✅ polite questions

---

# 🟢 Section A – Formelle E-Mail

## Important characteristics

### ✅ Formal greeting

Use:

🗣️ Sehr geehrte Frau + Nachname  
🗣️ Sehr geehrter Herr + Nachname

❌ NOT:
- Liebe Anna
- Hallo Tom

---

## ✅ Formal pronoun

Use:

🗣️ Sie

NOT:

❌ du

---

## ✅ Formal ending

Use:

🗣️ Mit freundlichen Grüßen

NOT:

❌ Liebe Grüße

---

## ✅ Full name

Write:

✅ Vorname + Familienname

Example:

🗣️ Masub Makhdoom

---

# 🟡 Section B – Informelle E-Mail

## Important difference

Now the email is:
✅ informal

So you use:

- Lieber / Liebe
- du
- Viele Grüße

---

## Structure of an informal email

| Part | Example |
|---|---|
| Greeting | Lieber Florian |
| Reason | ich habe eine Frage |
| Question | Hast du Sprechstunde? |
| Ending | Viele Grüße |

---

# 🟢 Helpful expressions

## Asking for an appointment

🗣️ Ich möchte gern einen Termin.  
🗣️ Hast du am 18. September Sprechstunde?  
🗣️ Ich habe eine Frage zu meiner Seminararbeit.

---

# 🟡 Formal vs. informal

| Formal | Informal |
|---|---|
| Sehr geehrte Frau Müller | Liebe Anna |
| Sie | du |
| Mit freundlichen Grüßen | Viele Grüße |

---

# 🧠 Writing tip

Formal email:
✅ polite  
✅ surname  
✅ Sie

Informal email:
✅ friendly  
✅ first name  
✅ du

</details>


# 4C Gemeinsam is(s)t man nicht allein



 ## 1 Was passt? Ordnen Sie die Wörter den Fotos zu.
![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_4/Bildschirmfoto2023-06-16um20.31.21.png?raw=true)

**Wörter:**  
abtrocknen · abwaschen · das Geschirr · die Spülmaschine · die Zutaten · einkaufen

---

1. [[die Spülmaschine]]  


2. [[die Zutaten]]  


3. [[das Geschirr]]  


4. [[abwaschen]]  


5. [[einkaufen]]  


6. [[abtrocknen]]  


---

 ## b) Schreiben Sie die Fragen.

1. Social Cooking · was · können · sein  
[[Was kann Social Cooking sein?]]  


---

2. funktionieren · Social Cooking · wie  
[[Wie funktioniert Social Cooking?]]  


---

3. wir · wie · teilnehmen · können  
[[Wie können wir teilnehmen?]]  


---

4. das Gericht · dürfen · wer · auswählen  
[[Wer darf das Gericht auswählen?]]  


---

5. kochen · alle · wo · das Essen  
[[Wo kochen alle das Essen?]]  


---

6. abwaschen · wer · das Geschirr · müssen  
[[Wer muss das Geschirr abwaschen?]]  

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Gemeinsam is(s)t man nicht allein</b></summary>

# 🍽️ Gemeinsam is(s)t man nicht allein

In this section, you practice:

✅ kitchen vocabulary  
✅ household activities  
✅ W-questions  
✅ modal verbs  
✅ sentence structure

---

# 🟢 Section A – Wörter und Fotos

## Helpful vocabulary

| Wort | Meaning |
|---|---|
| die Spülmaschine | dishwasher |
| die Zutaten | ingredients |
| das Geschirr | dishes |
| abwaschen | wash dishes |
| einkaufen | shopping |
| abtrocknen | dry dishes |

---

## Helpful strategy

Look at the picture:

🍽 plates and cups  
➡ das Geschirr

🛒 shopping  
➡ einkaufen

🥕 food ingredients  
➡ die Zutaten

---

# 🟡 Section B – Fragen schreiben

## Important grammar

German questions usually have:

✅ question word  
✅ verb  
✅ subject

---

# 🟢 W-Fragen

| Fragewort | Meaning |
|---|---|
| Was | what |
| Wie | how |
| Wer | who |
| Wo | where |

---

## Example structure

🗣️ Was kann Social Cooking sein?

| Position 1 | Position 2 | Rest |
|---|---|---|
| Was | kann | Social Cooking sein |

---

# 🟡 Modal verbs in questions

With modal verbs:

✅ modal verb = Position 2  
✅ second verb = infinitive at the end

---

## Examples

🗣️ Wie können wir teilnehmen?  
🗣️ Wer darf das Gericht auswählen?  
🗣️ Wer muss das Geschirr abwaschen?

---

# 🟢 Important verbs

| Verb | Meaning |
|---|---|
| können | can |
| dürfen | may / allowed to |
| müssen | must |

---

# 🟡 Sentence building tips

## Example

Words:

👉 alle · wo · das Essen · kochen

Think:

1. Question word first → Wo  
2. Verb second → kochen  
3. Subject after verb → alle

✅ Wo kochen alle das Essen?

---

# 🧠 Grammar summary

| Structure | Example |
|---|---|
| W-Frage + Verb + Subject | Wie funktioniert Social Cooking? |
| Modalverb + Subject + Infinitiv | Wer muss das Geschirr abwaschen? |

</details>

---

# 2 [ Wortbildung ] Verben mit trennbarer Vorsilbe

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_028.mp3?raw=true)

 ## a) Welche Silbe ist betont? Hören Sie und markieren Sie.

1. ~~teil~~nehmen  


2. er[[gän]]zen  


3. 😊[[aus]]füllen  


4. 😊[[mit]]bringen  


5. ver[[glei]]chen  


6. 😊[[ab]]waschen  


7. 😊[[ein]]kaufen  


8. be[[stell]]en  


---


 ## d) Sprechen

  ## 💡 Hören Sie und sprechen Sie nach.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_028.mp3?raw=true)

 

[[teilnehmen]]  
[[ausfüllen]]  
[[mitbringen]]
[[abwaschen]]
[[einkaufen]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Verben mit trennbarer Vorsilbe</b></summary>

# 🟢 Verben mit trennbarer Vorsilbe

In this section, you practice:

✅ separable verbs  
✅ pronunciation and stress  
✅ speaking and listening

---

# 🟡 What are separable verbs?

Some German verbs have:

✅ a prefix  
+  
✅ a main verb

Examples:

- aus + füllen → ausfüllen  
- mit + bringen → mitbringen  
- ein + kaufen → einkaufen

---

# 🟢 Important rule

In normal sentences:

✅ the prefix goes to the end.

---

## Examples

🗣️ Ich fülle das Formular aus.  
🗣️ Wir bringen die Zutaten mit.  
🗣️ Sie kaufen heute ein.

---

# 🟡 Part A – Which syllable is stressed?

## Important pronunciation rule

### Separable verbs

Stress is usually on:
✅ the prefix

Examples:

🗣️ AUSfüllen  
🗣️ MITbringen  
🗣️ ABwaschen  
🗣️ EINkaufen

---

### Non-separable verbs

Stress is usually on:
✅ the second part

Examples:

🗣️ ergänzen  
🗣️ vergleichen  
🗣️ bestellen

---

# 🟢 Separable vs. non-separable

| Verb | Type | Stress |
|---|---|---|
| ausfüllen | separable | AUS |
| mitbringen | separable | MIT |
| einkaufen | separable | EIN |
| ergänzen | non-separable | GÄN |
| vergleichen | non-separable | GLEI |
| bestellen | non-separable | STELL |

---

# 🟡 Part D – Speaking practice

## Listen and repeat

Practice these verbs aloud:

🗣️ teilnehmen  
🗣️ ausfüllen  
🗣️ mitbringen  
🗣️ abwaschen  
🗣️ einkaufen

---

# 🧠 Helpful speaking tip

Clap or stress the strong syllable:

👏 AUS-füllen  
👏 MIT-bringen  
👏 EIN-kaufen

This helps:
✅ pronunciation  
✅ listening  
✅ speaking fluency

---

# ⚠️ Grammar tip

## Sentence structure

| Verb | Sentence |
|---|---|
| ausfüllen | Ich fülle das Formular aus. |
| mitbringen | Wir bringen die Zutaten mit. |
| einkaufen | Er kauft heute ein. |

The prefix moves to:
✅ the end of the sentence.

</details>

# 3C Grammatik Kompakt – Verben mit trennbarer Vorsilbe


 ## a) Hören Sie die Sätze und ergänzen Sie die Verben.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_029.mp3?raw=true)

1. Am Social Cooking ~~nehmen~~ Gäste und Gastgeber ~~teil~~.  


2. Zuerst [[füllen]] alle ein Online-Formular [[aus]].  


3. Das Social-Cooking-Team [[lost]] die Gäste und die Gastgeber [[aus]].  


4. Das Kochteam [[bringt]] die Zutaten [[mit]].  


5. Die Gäste [[laden]] den Gastgeber [[ein]].  


---

 ## b) Schreiben Sie die Sätze in die Tabelle.

1. auswählen – das Kochteam – das Gericht
2. die Zutaten – die Gäste – einkaufen
3. abtrocknen – die Gäste – das Geschirr
4. die Küche – aufräumen – die Gäste

| Position 1 | Position 2 | Mitte | Satzende |
|------------|------------|-------|----------|
1. | Das Kochteam | wählt | das Gericht | aus |
2. | [[Die Gäste]] | [[kaufen]] | [[die Zutaten]] | [[ein]] |
3. | [[Die Gäste]] | [[trocknen]] | [[das Geschirr]] | [[ab]] |
4. | [[Die Gäste]] | [[räumen]] | [[die Küche]] | [[auf]] |


 ## e) Ergänzen Sie die Formen von ausschlafen und einladen.

| Person        | ausschlafen  | einladen  |
| ------------- | ------------ | --------- |
| ich           | schlafe aus  | lade ein  |
| du            | [[schläfst aus]] | lädst ein |
| er / sie / es | schläft aus  | [[lädt ein]]  |
| wir           | [[schlafen aus]] | laden ein |
| ihr           | schlaft aus  | ladet ein |
| sie / Sie     | schlafen aus | [[laden ein]] |

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Grammatik Kompakt: Verben mit trennbarer Vorsilbe</b></summary>

# 🟢 Verben mit trennbarer Vorsilbe

In this section, you practice:

✅ separable verbs  
✅ sentence structure  
✅ conjugation  
✅ speaking and listening

---

# 🟡 Section A – Verben ergänzen

## Important rule

A separable verb has:

✅ prefix  
+  
✅ main verb

Examples:

- teilnehmen  
- ausfüllen  
- mitbringen  
- einladen

---

## In a sentence:

The prefix moves to:
✅ the end

---

## Examples

🗣️ Gäste nehmen teil.  
🗣️ Alle füllen das Formular aus.  
🗣️ Die Gäste bringen Zutaten mit.

---

# 🟢 Common separable verbs

| Verb | Meaning |
|---|---|
| teilnehmen | participate |
| ausfüllen | fill out |
| auslosen | draw / select |
| mitbringen | bring along |
| einladen | invite |
| einkaufen | shop |
| aufräumen | clean up |
| abtrocknen | dry dishes |

---

# 🟡 Section B – Satzbau

## Important sentence structure

| Position 1 | Position 2 | Middle | Sentence end |
|---|---|---|---|
| Subject | Verb | Object | Prefix |

---

## Example

🗣️ Das Kochteam wählt das Gericht aus.

| Position 1 | Position 2 | Mitte | Satzende |
|---|---|---|---|
| Das Kochteam | wählt | das Gericht | aus |

---

## More examples

🗣️ Die Gäste kaufen die Zutaten ein.  
🗣️ Die Gäste trocknen das Geschirr ab.  
🗣️ Die Gäste räumen die Küche auf.

---

# 🟢 Section E – ausschlafen und einladen

## Conjugation patterns

### ausschlafen

| Person | Form |
|---|---|
| ich | schlafe aus |
| du | schläfst aus |
| er/sie | schläft aus |
| wir | schlafen aus |

---

### einladen

| Person | Form |
|---|---|
| ich | lade ein |
| du | lädst ein |
| er/sie | lädt ein |
| wir | laden ein |

---

# ⚠️ Important grammar tip

Some verbs change vowels:

| Infinitiv | du | er/sie |
|---|---|---|
| ausschlafen | schläfst | schläft |
| einladen | lädst | lädt |

---

# 🧠 Speaking tip

Stress the prefix:

👏 TEIL-nehmen  
👏 AUS-füllen  
👏 MIT-bringen  
👏 EIN-laden

This improves:
✅ pronunciation  
✅ fluency  
✅ listening comprehension

</details>


# 🧠 Seine Meinung äußern

 ## Wie finden Sie das? Ordnen Sie zu.


>eine tolle Idee · gefährlich · interessant · keine tolle Idee · komisch · lustig · spannend · stressig

👍 Positive:  
[[eine tolle Idee]]  
[[interessant]]  
[[lustig]]  
[[spannend]]  


---

👎 Negative:  
[[gefährlich]]  
[[komisch]]  
[[stressig]]  
[[keine tolle Idee]]  

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Seine Meinung äußern</b></summary>

# 🧠 Seine Meinung äußern

In this section, you learn how to:

✅ give your opinion  
✅ describe ideas and situations  
✅ use positive and negative adjectives

---

# 🟢 Positive Meinungen

These words express:
😊 good feelings  
😊 positive opinions

| Wort | Meaning |
|---|---|
| eine tolle Idee | a great idea |
| interessant | interesting |
| lustig | funny |
| spannend | exciting |

---

## Examples

🗣️ Social Cooking ist interessant.  
🗣️ Das Spiel ist lustig.  
🗣️ Die Idee ist spannend.

---

# 🟡 Negative Meinungen

These words express:
☹️ negative feelings  
☹️ criticism

| Wort | Meaning |
|---|---|
| gefährlich | dangerous |
| komisch | strange |
| stressig | stressful |
| keine tolle Idee | not a good idea |

---

## Examples

🗣️ Das ist gefährlich.  
🗣️ Die Situation ist stressig.  
🗣️ Das finde ich komisch.

---

# 🟢 Helpful sentence patterns

## Meinung sagen

🗣️ Ich finde das interessant.  
🗣️ Ich finde das lustig.  
🗣️ Ich finde das stressig.

---

# 🟡 Positive vs. negative

| Positive 👍 | Negative 👎 |
|---|---|
| spannend | stressig |
| lustig | gefährlich |
| interessant | komisch |

---

# 🧠 Speaking tip

Use:

🗣️ Ich finde …

Examples:

- Ich finde Social Cooking spannend.  
- Ich finde die Idee toll.  
- Ich finde das komisch.

This helps:
✅ speaking  
✅ discussions  
✅ expressing opinions

</details>


# Veranstaltungen


 ## 1 Einladung zum Semesterende

 ## a) Welche Veranstaltungen sehen Sie auf den Fotos? Ordnen Sie zu.

![](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_4/Bildschirmfoto2023-06-16um20.57.16..png?raw=true)

**Wörter:**  
das Beachvolleyballspiel · die Klausur · das Konzert · die Party

1. [[die Klausur]]  


2. [[die Party]]  


3. [[das Konzert]]  


4. [[das Beachvolleyballspiel]]  


---

 ## b) Lesen Sie die Einladung. Welches Foto passt?

> Das Semester ist bald zu Ende, die Klausuren kommen.  
> Aber wir wollen noch ein bisschen Spaß haben!  
>  
> Wir sind zehn Studierende aus den Fächern Mathematik und Physik  
> und bereiten wie jedes Jahr ein Beachvolleyball-Turnier vor.  
> Wir laden alle Studierenden ein.  
>  
> Der Termin ist wie immer am ersten Samstag im Juli.  
> Wir beginnen um 15 Uhr.  
>  
> Wie kannst du teilnehmen? Ganz einfach:  
> Schreibe bis zum 15. Juni eine Mail an kdjkf@xpu.de.  
> Am Samstag bringst du 10 Euro mit.  
>  
> Wo? Wir spielen auf den Beachplätzen bei der Mensa.  
>  
> Du kannst nicht perfekt Beachvolleyball spielen? Kein Problem.  
> Du musst kein Profi sein.  
> Wir wollen zusammen Spaß haben und gemeinsam Sport machen.

---


  ## c) Wie heißen die W-Fragen? Ordnen Sie zu.

* a. nimmt man teil?  
* b. organisiert die Veranstaltung?  
* c. findet die Veranstaltung statt?  
* d. findet die Veranstaltung statt?  
* e. kann ich teilnehmen?  
* f. passiert dort? 

1. Wann → [[c]]  


2. Was → [[f]]  


3. Wer → [[b]]  


4. Wer → [[a]]  


5. Wo → [[d]]  


6. Wie → [[e]]  




 ## d) Lesen Sie die Einladung noch einmal und beantworten Sie die W-Fragen aus 1c in Stichworten.

Wann?  
[[am ersten Samstag im Juli um 15 Uhr]]  


Was?  
[[ein Beachvolleyball-Turnier]]  


Wer?  
[[Studierende aus Mathematik und Physik]]  


Wo?  
[[auf den Beachplätzen bei der Mensa]]  


Wie?  
[[E-Mail schreiben und 10 Euro mitbringen]]  


---

 ## e) Ergänzen Sie die E-Mail an Azul mit den Informationen aus 1d.

Hi Azul,

am [[ersten Samstag im Juli]] (1) gibt es auf den Beachplätzen  
[[bei der Mensa]] (2) ein [[Beachvolleyball-Turnier]] (3).Das Turnier organisieren [[Studierende aus Mathematik und Physik]] (4).  Es können [[alle Studierenden]] (5) teilnehmen.Du musst nur [[eine Mail bis 15. Juni]] (6) schreiben an kdjkf@xpu.
 de und am Samstag[[10Euromitbringen]] (7).Kommst du?
Liebe Grüße  
Dominik 🙂

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-top:12px;">

<summary><b>💡 Hint – Veranstaltungen</b></summary>

# 🎉 Veranstaltungen

In this section, you practice:

✅ event vocabulary  
✅ invitations  
✅ W-questions  
✅ reading information  
✅ writing short emails

---

# 🟢 Section A – Veranstaltungen erkennen

## Helpful vocabulary

| Wort | Meaning |
|---|---|
| die Klausur | exam |
| die Party | party |
| das Konzert | concert |
| das Beachvolleyballspiel | beach volleyball game |

---

## Helpful strategy

Look at the picture carefully:

🎓 students writing → die Klausur  
🎵 music stage → das Konzert  
🏐 volleyball → das Beachvolleyballspiel

---

# 🟡 Section B – Einladung lesen

## Important information in the text

You should find:

✅ Was?  
✅ Wann?  
✅ Wo?  
✅ Wer?  
✅ Wie?

---

## Important vocabulary

| Expression | Meaning |
|---|---|
| das Turnier | tournament |
| teilnehmen | participate |
| die Beachplätze | beach courts |
| die Mensa | cafeteria |
| Spaß haben | have fun |

---

# 🟢 Section C – W-Fragen

## W-question words

| Fragewort | Meaning |
|---|---|
| Wann | when |
| Was | what |
| Wer | who |
| Wo | where |
| Wie | how |

---

## Examples

🗣️ Wann findet die Veranstaltung statt?  
🗣️ Wo findet die Veranstaltung statt?  
🗣️ Wer organisiert die Veranstaltung?

---

# 🟡 Section D – Antworten finden

## Reading strategy

Search the text for:

📅 time  
📍 place  
👥 people  
🏐 activity

---

## Example answers

| Frage | Information |
|---|---|
| Wann? | am ersten Samstag im Juli um 15 Uhr |
| Was? | ein Beachvolleyball-Turnier |
| Wo? | bei der Mensa |
| Wie? | Mail schreiben + 10 Euro mitbringen |

---

# 🟢 Section E – E-Mail ergänzen

## Helpful email expressions

🗣️ Es gibt ein Beachvolleyball-Turnier.  
🗣️ Alle Studierenden können teilnehmen.  
🗣️ Du musst eine Mail schreiben.  
🗣️ Bring bitte 10 Euro mit.

---

# 🟡 Important grammar

## Modal verbs

| Verb | Meaning |
|---|---|
| können | can |
| müssen | must / have to |

Examples:

🗣️ Du kannst teilnehmen.  
🗣️ Du musst 10 Euro mitbringen.

---

# 🧠 Writing tip

When you write about an event:

✅ say WHAT  
✅ say WHEN  
✅ say WHERE  
✅ say HOW to participate

---

# ⚠️ Useful sentence patterns

🗣️ Am Samstag gibt es ein Turnier.  
🗣️ Wir spielen bei der Mensa.  
🗣️ Alle Studierenden können teilnehmen.

</details>

# ✅ Lösungen – Kapitel 4

## 1 Uni und Haushalt

1. haben  
2. schreiben  
3. aufräumen  
4. halten

---

# 2 Grammatik Kompakt – müssen

 ## a)

1. muss  
2. müssen  
3. müssen  
4. muss  
5. muss  
6. müsst

---

 ## b)

1. William muss viel lernen.  
2. Ich muss heute mein Zimmer aufräumen.  
3. Wann müsst ihr das Referat halten?  
4. Warum müssen wir am Sonntag arbeiten?  
5. Du musst viele Klausuren schreiben.  
6. Die Studierenden müssen ein Formular ausfüllen.

---

 ## c)

1. muss  
2. kann  
3. kann  
4. kann  
5. können

---

 ## d)

1. muss / können  
2. muss  
3. Wollen  
4. musst / wollen  
5. kann / muss

---

# ⏰ Uhrzeiten

 ## a)

1. Viertel nach zwei  
2. halb vier  
3. fünf vor halb fünf  
4. zwanzig nach neun  
5. Viertel vor elf

---

 ## b)

1. 16:30 Uhr  
2. 10:15 Uhr  
3. 09:55 Uhr  
4. 11:10 Uhr

---

 ## c)

1. 07:45 Uhr  
2. 16:20 Uhr  
3. 11:25 Uhr  
4. 09:10 Uhr  
5. 06:30 Uhr  
6. 15:15 Uhr

---

# 📅 Sich verabreden

1. Bis dann!  
2. Morgen habe ich eine Vorlesung.  
3. Das mache ich gern.

---

 ## 🌅 Tageszeiten

1. der Morgen / morgens  
2. der Vormittag / vormittags  
3. der Mittag / mittags  
4. der Nachmittag / nachmittags  
5. der Abend / abends  
6. die Nacht / nachts

---

# 📆 Daten

 ## a)

* Frühling → März, April, Mai  
* Sommer → Juni, Juli, August  
* Herbst → September, Oktober, November  
* Winter → Dezember, Januar, Februar

---

 ## b)

1. der zwölfte März / am zwölften März  
2. der achte September / am achten September  
3. der sechste Mai / am sechsten Mai  
4. der siebte Juli / am siebten Juli

---

 ## c)

07.09.  
03.04.  
23.12.  
14.05.  
27.07.  
30.03.  
27.06.  
06.08.  
20.11.

---

 ## d)

| Uhrzeit | Tageszeit | Wochentag | Monat | Jahreszeit |
|---|---|---|---|---|
| 15 Uhr | abends | Dienstag | Februar | Frühjahr |
| halb vier | mittags | Mittwoch | Juli | Herbst |
| Viertel nach drei | morgens | Samstag | Oktober | Sommer |

---

# 🕒 Temporale Präpositionen

 ## a)

1. am  
2. um  
3. im  
4. um  
5. im  
6. am

---

 ## b)

1. Am fünften Februar  
2. Im August und September  
3. Am Freitagnachmittag  
4. Um halb acht

---

 ## c)

 ## 1
* am  
* um  
* von  
* bis

 ## 2
* Im  
* vom  
* bis zum

 ## 3
* am  
* Von  
* bis  
* um  
* am  
* am

---

# ✉️ E-Mail

 ## a)

1. Sehr geehrte Frau / Herr + Nachname  
2. Sie  
3. Mit freundlichen Grüßen  
4. Vorname + Familienname

---

 ## b)

Lieber Florian,  
ich habe eine Frage zu meiner Seminararbeit.  
Hast du am 18. September Sprechstunde?  
Ich möchte gern einen Termin.

Viele Grüße  
Masub

---

# 🍽️ Gemeinsam is(s)t man nicht allein

 ## a)

1. die Spülmaschine  
2. die Zutaten  
3. das Geschirr  
4. abwaschen  
5. einkaufen  
6. abtrocknen

---

 ## b)

1. Was kann Social Cooking sein?  
2. Wie funktioniert Social Cooking?  
3. Wie können wir teilnehmen?  
4. Wer darf das Gericht auswählen?  
5. Wo kochen alle das Essen?  
6. Wer muss das Geschirr abwaschen?

---

# 🧩 Verben mit trennbarer Vorsilbe

 ## a)

1. teilnehmen  
2. ergänzen  
3. ausfüllen  
4. mitbringen  
5. vergleichen  
6. abwaschen  
7. einkaufen  
8. bestellen

---

# 🟢 Grammatik Kompakt – Trennbare Verben

 ## a)

1. nehmen / teil  
2. füllen / aus  
3. lost / aus  
4. bringt / mit  
5. laden / ein

---

 ## b)

1. Das Kochteam wählt das Gericht aus.  
2. Die Gäste kaufen die Zutaten ein.  
3. Die Gäste trocknen das Geschirr ab.  
4. Die Gäste räumen die Küche auf.

---

 ## e)

| Person | ausschlafen | einladen |
|---|---|---|
| ich | schlafe aus | lade ein |
| du | schläfst aus | lädst ein |
| er/sie/es | schläft aus | lädt ein |
| wir | schlafen aus | laden ein |
| ihr | schlaft aus | ladet ein |
| sie/Sie | schlafen aus | laden ein |

---

# 🧠 Seine Meinung äußern

 ## Positive

- eine tolle Idee  
- interessant  
- lustig  
- spannend

 ## Negative

- gefährlich  
- komisch  
- stressig  
- keine tolle Idee

---

# 🎉 Veranstaltungen

 ## a)

1. die Klausur  
2. die Party  
3. das Konzert  
4. das Beachvolleyballspiel

---

 ## c)

1. c  
2. f  
3. b  
4. a  
5. d  
6. e

---

 ## d)

* Wann? → am ersten Samstag im Juli um 15 Uhr  
* Was? → ein Beachvolleyball-Turnier  
* Wer? → Studierende aus Mathematik und Physik  
* Wo? → auf den Beachplätzen bei der Mensa  
* Wie? → E-Mail schreiben und 10 Euro mitbringen

---

 ## e)

1. ersten Samstag im Juli  
2. bei der Mensa  
3. Beachvolleyball-Turnier  
4. Studierende aus Mathematik und Physik  
5. alle Studierenden  
6. eine Mail bis 15. Juni  
7. 10 Euro mitbringen