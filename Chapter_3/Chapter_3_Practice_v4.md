
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

##     Welcome

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0b2a66"/>
      <stop offset="1" stop-color="#4fa3ff"/>
    </linearGradient>

    <linearGradient id="panel" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0.96"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0.86"/>
    </linearGradient>

    <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="14" stdDeviation="16" flood-color="#001736" flood-opacity="0.35"/>
    </filter>

    <style><![CDATA[
      .title{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:900; font-size:66px;}
      .subtitle{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:600; font-size:28px;}
      .chip{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:750; font-size:22px;}
      .h2{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:900; font-size:32px;}
      .txt{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:550; font-size:24px;}
      .small{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:550; font-size:18px;}
    ]]></style>
  </defs>

  <rect width="1600" height="900" fill="url(#bg)"/>
  <circle cx="1340" cy="150" r="220" fill="#fff" opacity="0.10"/>
  <circle cx="1460" cy="310" r="120" fill="#fff" opacity="0.10"/>
  <circle cx="260" cy="770" r="270" fill="#fff" opacity="0.08"/>

  <g filter="url(#shadow)">
    <rect x="110" y="110" rx="28" ry="28" width="1380" height="680" fill="url(#panel)"/>
  </g>

  <rect x="110" y="110" rx="28" ry="28" width="1380" height="130" fill="#fff" opacity="0.22"/>
  <rect x="110" y="240" width="1380" height="2" fill="#0b2a66" opacity="0.12"/>

  <rect x="160" y="150" rx="22" ry="22" width="230" height="44" fill="#0b2a66" opacity="0.95"/>
  <text x="275" y="180" text-anchor="middle" fill="#fff" class="chip">KAPITEL 3</text>

  <text x="160" y="330" fill="#0b2a66" class="title">Das essen Studierende in Deutschland</text>
  <text x="160" y="385" fill="#0b2a66" opacity="0.85" class="subtitle">Wortschatz • Grammatik • Hörverstehen • Übungen</text>

  <!-- Card 1 -->
  <g transform="translate(160, 450)">
    <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
    <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
    <text x="28" y="62" fill="#0b2a66" class="h2">Wortschatz</text>
    <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">Gerichte &amp; Zutaten</text>
    <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">Mensa, Essen, Getränke</text>
    <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">Nomen + Nomen</text>
    <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">Bratkartoffeln • Currywurst • Schnipo</text>
  </g>

  <!-- Card 2 -->
  <g transform="translate(595, 450)">
    <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
    <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
    <text x="28" y="62" fill="#0b2a66" class="h2">Grammatik</text>
    <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">können • wollen</text>
    <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">mögen • möchten</text>
    <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">Wortstellung • Satzbau</text>
    <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">nehme • nimmst • nimmt • nehmen</text>
  </g>

  <!-- Card 3 -->
  <g transform="translate(1030, 450)">
    <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
    <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
    <text x="28" y="62" fill="#0b2a66" class="h2">Hören &amp; Üben</text>
    <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">Fragen ergänzen</text>
    <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">Matching • Tabellen</text>
    <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">Lückentexte</text>
    <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">Audio </text>
  </g>

  <text x="160" y="815" fill="#0b2a66" opacity="0.60" class="small">LiaScript • Interaktive Übungen</text>
</svg>

# 🤖 Offline Chatbot – Kapitel 3 

<div id="c3bot" style="background:#f7fbff;border:2px solid #d8e8ff;border-radius:22px;padding:22px;max-width:1100px;margin:auto;font-family:Arial,sans-serif;">

<h2 style="color:#0b2a66;">🤖 Kapitel 3 Lernbot – Das essen Studierende in Deutschland</h2>

<div id="c3-output" style="background:white;border:1px solid #d8e8ff;border-radius:16px;padding:16px;min-height:220px;max-height:430px;overflow:auto;line-height:1.7;margin-bottom:14px;">
<b>Bot:</b> Hallo! Ask me about Kapitel 3: Essen, Mensa, Modalverben, Wortbildung, Satzbau, nehmen, mögen, möchten 😊
</div>

<input id="c3-input" placeholder="Example: mögen oder möchten answers" style="width:68%;padding:12px;border-radius:12px;border:1px solid #b9cde8;">
<button id="c3-ask" type="button" style="padding:12px 16px;border-radius:12px;border:none;background:#0b2a66;color:white;font-weight:bold;">Ask</button>
<button id="c3-clear" type="button" style="padding:12px 16px;border-radius:12px;border:1px solid #0b2a66;background:white;color:#0b2a66;font-weight:bold;">Clear</button>

<h3>💡 Quick Questions</h3>
<div id="c3-quick" style="display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:10px;margin-top:12px;"></div>

</div>

<script>
setTimeout(function(){

  const output = document.getElementById("c3-output");
  const input = document.getElementById("c3-input");
  const askBtn = document.getElementById("c3-ask");
  const clearBtn = document.getElementById("c3-clear");
  const quickBox = document.getElementById("c3-quick");

  const questions = [
    "Chapter 3 overview",
    "Food names answers",
    "Listening questions answers",
    "können exercise answers",
    "wollen exercise answers",
    "Modal verbs word order answers",
    "Compound nouns answers",
    "Weekdays answers",
    "Satzbau answers",
    "nehmen exercise answers",
    "möchten exercise answers",
    "mögen exercise answers",
    "mögen oder möchten answers",
    "Difference between mögen and möchten",
    "Mensa vocabulary",
    "Food vocabulary"
  ];

  function cleanText(text){
    return String(text || "")
      .replace(/4938/g, "")
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
           "<b style='color:#0b2a66;font-size:17px;'>" + title + "</b><br><br>" + body + "</div>";
  }

  function answer(question){
    const q = normalize(question);

    if(hasAny(q, ["chapter 3 overview", "kapitel 3 overview", "overview"])){
      return card("Kapitel 3 Overview",
        "Kapitel 3 heißt <b>Das essen Studierende in Deutschland</b>.<br><br>" +
        "Main topics:<br>• food and Mensa vocabulary<br>• Gerichte und Zutaten<br>• können / wollen<br>• Wortstellung mit Modalverben<br>• Nomen + Nomen<br>• Wochentage<br>• nehmen<br>• mögen / möchten.");
    }

    if(hasAny(q, ["food names answers", "gerichte answers", "wie heissen die gerichte", "dish answers"])){
      return card("Food Names – Correct Answers",
        "1. Bratkartoffeln<br>2. Currywurst<br>3. Gemüse-Reis-Pfanne<br>4. Hackfleischsoße<br>5. Jägerschnitzel<br>6. Paprikareis<br>7. Pommes frites<br>8. Studentenfutter");
    }

    if(hasAny(q, ["listening questions answers", "hoeren fragen", "audio questions", "track 021"])){
      return card("Listening Questions – Correct Answers",
        "1. <b>Esst</b> ihr gern <b>Gemüse</b>?<br>2. <b>Isst</b> du <b>Fleisch</b>?<br>3. <b>Ist</b> Mia <b>Vegetarierin</b>?<br>4. <b>Isst</b> Pia <b>vegan</b>?");
    }

    if(hasAny(q, ["koennen exercise", "können exercise", "koennen answers", "können answers"])){
      return card("können – Exercise Answers",
        "1. Ich <b>kann</b> sehr gut kochen.<br>2. Mia <b>kann</b> keine Milchprodukte essen.<br>3. Du <b>kannst</b> in der Mensa günstig essen.<br>4. Wir <b>können</b> sehr gut Keyboard spielen.<br>5. Studierende <b>können</b> das Essen mitnehmen.<br>6. <b>Könnt</b> ihr Spanisch sprechen?");
    }

    if(hasAny(q, ["wollen exercise", "wollen answers", "will willst wollt"])){
      return card("wollen – Exercise Answers",
        "1. Mia <b>will</b> kein Fleisch essen.<br>2. Heute <b>will</b> ich lieber zu Hause essen.<br>3. Wir <b>wollen</b> heute Fußball schauen.<br>4. Ihr <b>wollt</b> Physik studieren?<br>5. Pit und Peter <b>wollen</b> heute Schnipo essen.<br>6. <b>Willst</b> du heute Hähnchen essen?<br><br>Important correction: <b>wollt</b>, not wallt.");
    }

    if(hasAny(q, ["modal verbs word order", "wortstellung answers", "word order answers"])){
      return card("Modalverben – Wortstellung Answers",
        "1. Ich kann sehr gut französisch kochen.<br>2. Wir wollen heute in der Mensa essen.<br>3. Peter kann sehr gut Gitarre spielen.<br>4. Olga kann vier Sprachen sprechen.<br>5. Was will Susanne studieren?<br>6. Was wollen wir essen?<br><br>Rule: Modalverb = Position 2, infinitive verb = Satzende.");
    }

    if(hasAny(q, ["compound nouns answers", "nomen nomen answers", "wortbildung answers", "zusammengesetzte nomen"])){
      return card("Wortbildung – Correct Answers",
        "<b>Neue Wörter:</b><br>1. der Nudelsalat<br>2. der Obstsalat<br>3. die Kürbissuppe<br>4. die Gemüsesuppe<br>5. der Apfelkuchen<br>6. der Ananaskuchen<br><br>" +
        "<b>Zusammengesetzte Nomen:</b><br>1. die Hackfleischsoße<br>2. der Paprikareis<br>3. die Currywurst<br>4. <b>das Milchprodukt</b><br>5. die Gemüselasagne<br>6. der Kartoffelbrei<br>7. die Fischsuppe<br>8. das Ananaseis");
    }

    if(hasAny(q, ["weekdays answers", "welcher tag fehlt", "wochentage answers"])){
      return card("Wochentage – Answers",
        "1. Montag, <b>Dienstag</b>, Mittwoch<br>2. Donnerstag, <b>Freitag</b>, Samstag<br>3. Sonntag, <b>Montag</b>, Dienstag<br>4. Samstag, <b>Sonntag</b>, Montag<br>5. Dienstag, <b>Mittwoch</b>, Donnerstag<br>6. Freitag, <b>Samstag</b>, Sonntag");
    }

    if(hasAny(q, ["satzbau answers", "sentence building answers", "gibt es answers"])){
      return card("Satzbau – Answers",
        "1a. Am Montag ist Schnipottag.<br>1b. Schnipottag ist am Montag.<br><br>2a. Pizza gibt es am Donnerstag.<br>2b. Am Donnerstag gibt es Pizza.<br><br>3a. Am Sonntag wollen wir kochen.<br>3b. Wir wollen am Sonntag kochen.<br><br>4a. Am Freitag gibt es Fisch.<br>4b. Fisch gibt es am Freitag.");
    }

    if(hasAny(q, ["nehmen exercise", "nehmen answers", "nehme nimmst nimmt"])){
      return card("nehmen – Exercise Answers",
        "1. Was <b>nehmt</b> ihr?<br>2. Wir <b>nehmen</b> einen Butterkuchen und ein Franzbrötchen.<br>3. Ben <b>nimmt</b> ein Fischbrötchen.<br>4. <b>Nimmst</b> du auch ein Fischbrötchen?<br>5. Nein, ich <b>nehme</b> ein Rundstück.<br>6. Ariane und Olga <b>nehmen</b> das Hamburg-Frühstück.");
    }

    if(hasAny(q, ["moechten exercise", "möchten exercise", "moechten answers", "möchten answers"])){
      return card("möchten – Exercise Answers",
        "1. Wir <b>möchten</b> gern bezahlen.<br>2. <b>Möchtest</b> du heute Kuchen essen?<br>3. Mia <b>möchte</b> heute keinen Nachtisch essen.<br>4. Was <b>möchtet</b> ihr trinken?<br>5. Ich <b>möchte</b> auch etwas essen.<br>6. Anne und Mia <b>möchten</b> Französisch lernen.");
    }

    if(hasAny(q, ["moegen exercise", "mögen exercise", "moegen answers", "mögen answers"])){
      return card("mögen – Exercise Answers",
        "1. Ich <b>mag</b> keinen Fisch.<br>2. Wir <b>mögen</b> die Mensa.<br>3. Ben <b>mag</b> Schnipo.<br>4. <b>Magst</b> du Schnipo?<br>5. <b>Mögt</b> ihr kein Fleisch?<br>6. Anne und Mia <b>mögen</b> Gemüse.");
    }

    if(hasAny(q, ["moegen oder moechten answers", "mögen oder möchten answers"])){
      return card("mögen oder möchten – Answers",
        "1. Ben <b>mag</b> kein Gemüse, aber er isst sehr gern Fleisch.<br>2. Wir <b>möchten</b> heute in der Mensa essen: Es gibt Currywurst!<br>3. Ich <b>möchte</b> ein Stück Käsekuchen bestellen.<br>4. Olga <b>mag</b> Käsekuchen sehr.<br>5. <b>Möchtet</b> ihr den Labskaus probieren?<br>6. Ich <b>mag</b> kein Fleisch, aber ich esse sehr gern Fisch.<br>7. Ben <b>möchte</b> heute in der Mensa Schnipo essen, denn er <b>mag</b> Schnipo sehr.");
    }

    if(hasAny(q, ["difference between moegen and moechten", "difference between mögen and möchten", "moegen moechten difference"])){
      return card("Difference: mögen vs. möchten",
        "<b>mögen</b> = to like something.<br>Example: Ich mag Käsekuchen.<br><br><b>möchten</b> = would like / want politely.<br>Example: Ich möchte Käsekuchen bestellen.");
    }

    if(hasAny(q, ["mensa vocabulary", "mensa words", "speiseplan"])){
      return card("Mensa Vocabulary",
        "die Mensa, das Mensa-Essen, der Speiseplan, das Gericht, die Beilage, der Snack, die Speisekarte, bestellen, bezahlen, mitnehmen, Es gibt …");
    }

    if(hasAny(q, ["food vocabulary", "essen vocabulary", "gerichte vocabulary"])){
      return card("Food Vocabulary",
        "das Essen, das Gericht, die Pizza, das Fleisch, das Hähnchen, das Schnitzel, die Wurst, der Reis, die Pommes, die Spaghetti, die Soße, das Gemüse, die Kartoffel, die Nudel, das Ei, der Käse, der Fisch, das Brötchen.");
    }

    return card("Question not found",
      "Please ask about:<br>• food names answers<br>• können exercise answers<br>• wollen exercise answers<br>• word order answers<br>• compound nouns answers<br>• weekdays answers<br>• nehmen answers<br>• mögen / möchten answers");
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



## Das essen Studierende in Deutschland

 ## Wie heißen die Gerichte? Was passt zusammen? Schreiben Sie.

>~Brat ~· Curry · futter · Gemüse-Reis · Hackfleisch · jäger · ~kartoffeln~ · Pfanne · Pommes · reis · schnitzel · soße · Studenten · wurst · Paprika . Frites .

 *  ~~Bratkartoffeln ~~
*   [[ Currywurst ]]
*   [[Gemüse-Reis-Pfanne ]]
*   [[Hackfleischsoße]]
*   [[jägerschnitzel]]
*   [[Paprikareis]]
*   [[Pommesfrites  ]]
*   [[Studentenfutter]]

  ## Hören Sie und ergänzen Sie die Fragen.

  ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_021.mp3?raw=true)

1)    [[Esst]] ihr gern [[Gemüse]] ?  

2)  [[Isst]] du [[Fleisch]] ?

3) [[Ist]] Mia [[Vegetarierin]] ?  

4) [[Isst]] Pia [[vegan]] ?



---

 ##  [GRAMMATIK KOMPAKT] Modalverben: können und wollen

  ##  Ergänzen Sie die passenden Formen von **können**.

1. Ich [[kann]] sehr gut kochen.  
2. Mia [[kann]] keine Milchprodukte essen.  
3. Du [[kannst]] in der Mensa günstig essen.  

4. Wir [[können]] sehr gut Keyboard spielen.  
5. Studierende [[können]] das Essen mitnehmen.  
6. .[[könnt]] ihr Spanisch sprechen?


---

  ##  Ergänzen Sie die passenden Formen von **wollen**.

1. Mia [[will]] kein Fleisch essen.  
2. Heute [[will]] ich lieber zu Hause essen.  
3. Wir [[Wollen]] heute Fußball schauen.  

4. Ihr [[wallt]] Physik studieren?  
5. Pit und Peter [[wollen]] heute Schnipo essen.  
6. .[[Willst]] du heute Hähnchen essen?

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Das essen Studierende in Deutschland</b></summary>

In this exercise, you practice:
🍽️ food vocabulary  
🧩 compound nouns in German  
🎧 listening comprehension

Your task:
✅ combine the correct word parts  
✅ build complete food names

---

## Helpful strategy

Look carefully at:
- food words
- noun endings
- familiar German dishes

Example:
🌭 Curry + wurst  
➡ Currywurst

---

## Important clue

German often combines:
✅ two or three nouns together

Examples:
- Gemüse + Reis + Pfanne
- Hackfleisch + soße
- Studenten + futter

---

## Helpful vocabulary

| German | English |
|---|---|
| die Wurst | sausage |
| der Reis | rice |
| die Soße | sauce |
| die Kartoffeln | potatoes |
| das Gemüse | vegetables |
| die Pfanne | pan |
| das Futter | snack/food |

---

## Listening Task

🎧 Listen carefully and complete the questions.

Pay attention to:
✅ verb forms  
✅ food vocabulary  
✅ yes/no questions

---

## Important grammar clue

| Subject | Verb |
|---|---|
| du | isst |
| ihr | esst |
| Mia | ist |
| Pia | isst |

---

## Helpful examples

🗣️ Isst du Fleisch?  
🗣️ Esst ihr gern Gemüse?

---

## Practice tip

Read the food names aloud:

🗣️ Currywurst  
🗣️ Gemüse-Reis-Pfanne  
🗣️ Studentenfutter

This improves:
✅ pronunciation  
✅ vocabulary memory  
✅ speaking confidence

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Modalverben: können</b></summary>

In this exercise, you practice:
🧠 the modal verb <b>können</b>

"können" means:
✅ can / to be able to

---

## Present tense forms

| Person | können |
|---|---|
| ich | kann |
| du | kannst |
| er/sie/es | kann |
| wir | können |
| ihr | könnt |
| sie/Sie | können |

---

## Helpful strategy

First find:
👉 the subject

Then choose:
✅ the correct verb form

---

## Examples

🗣️ Ich kann kochen.  
🗣️ Du kannst Spanisch sprechen.  
🗣️ Wir können Keyboard spielen.

---

## Important grammar rule

With modal verbs:
✅ the second verb stays in infinitive form at the end.

Example:
🗣️ Ich kann gut kochen.  
🗣️ Wir können Spanisch sprechen.

---

## Practice tip

Read aloud:

🗣️ ich kann  
🗣️ du kannst  
🗣️ ihr könnt

This improves:
✅ verb memorization  
✅ pronunciation  
✅ sentence structure

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;">
<summary><b>💡 Hint – Modalverben: wollen</b></summary>

In this exercise, you practice:
🧠 the modal verb <b>wollen</b>

"wollen" means:
✅ want to

---

## Present tense forms

| Person | wollen |
|---|---|
| ich | will |
| du | willst |
| er/sie/es | will |
| wir | wollen |
| ihr | wollt |
| sie/Sie | wollen |

---

## Helpful strategy

Find:
👉 the subject

Then match:
✅ the correct form of "wollen"

---

## Important clue

⚠️ Common mistake:

❌ wallt  
✅ wollt

---

## Examples

🗣️ Ich will Pizza essen.  
🗣️ Wir wollen Fußball schauen.  
🗣️ Willst du Hähnchen essen?

---

## Important grammar rule

With modal verbs:
✅ the second verb stays at the end in infinitive form.

Examples:
- essen
- schauen
- studieren

---

## Practice tip

Say the forms aloud:

🗣️ ich will  
🗣️ du willst  
🗣️ ihr wollt  
🗣️ wir wollen

This improves:
✅ speaking  
✅ grammar memory  
✅ fluency

</details>

---


##  [GRAMMATIK KOMPAKT]  
 ## Modalverb **können** und **wollen** – Wortstellung

 ## Wo stehen die Verben? Schreiben Sie die Sätze in die Tabelle.

---

1. sehr gut • französisch • kann • ich • kochen  
2. wollen • wir • heute • in der Mensa • essen  
3. spielen • kann • sehr gut • Gitarre • Peter  

4. Olga • vier Sprachen • sprechen • kann  
5. will • studieren • was • Susanne • ?  
6. wir • was • essen • wollen • ?



---

| Nr. | Position 1 | Position 2 | Mittelfeld | Satzende |
|----|------------|------------|------------|----------|
| 1  | Ich         | kann        | sehr gut französisch | kochen |
| 2  |   [[Wir]]         |    [[wollen]]        |       [[heute in der Mensa]]     |     [[essen.]]     |
| 3  |     [[Peter]]       |      [[kann]]      |       [[sehr gut Gitarre]]     |       [[spielen.]]   |
| 4  |     [[Olga]]       |       [[kann]]     |        [[vier Sprachen]]    |      [[sprechen.]]    |
| 5  |      [[Was]]      |      [[will]]      |       [[Susanne]]     |       [[studieren?]]   |
| 6  |      [[Was]]      |       [[wollen]]     |      [[wir]]      |      [[essen?]]    |


<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Modalverb können und wollen: Wortstellung</b></summary>

In this exercise, you practice:
🧠 German sentence structure  
🧩 modal verbs  
📚 word order

Your task:
✅ put the words in the correct order  
✅ complete the table

---

## Important grammar rule

With modal verbs:
✅ the conjugated modal verb is in Position 2  
✅ the second verb goes to the end

---

## Sentence structure

| Position 1 | Position 2 | Mittelfeld | Satzende |
|---|---|---|---|
| Subject / Question word | Modalverb | extra information | infinitive verb |

---

## Examples

🗣️ Ich kann sehr gut kochen.  

| Position 1 | Position 2 | Mittelfeld | Satzende |
|---|---|---|---|
| Ich | kann | sehr gut | kochen |

---

🗣️ Wir wollen heute in der Mensa essen.

| Position 1 | Position 2 | Mittelfeld | Satzende |
|---|---|---|---|
| Wir | wollen | heute in der Mensa | essen |

---

## Helpful clue

The infinitive verb:
✅ always stays at the end

Examples:
- kochen
- essen
- spielen
- sprechen
- studieren

---

## Important question rule

For W-questions:

✅ Question word comes first

Example:
🗣️ Was will Susanne studieren?

| Position 1 | Position 2 | Mittelfeld | Satzende |
|---|---|---|---|
| Was | will | Susanne | studieren |

---

## Helpful strategy

### Step 1
Find:
👉 the modal verb
(kann / wollen / will)

### Step 2
Put it in:
✅ Position 2

### Step 3
Put the infinitive:
✅ at the end

---

## Modalverb forms

| können | wollen |
|---|---|
| ich kann | ich will |
| du kannst | du willst |
| er/sie kann | er/sie will |
| wir können | wir wollen |
| ihr könnt | ihr wollt |
| sie können | sie wollen |

---

## Practice tip

Read aloud:

🗣️ Peter kann sehr gut Gitarre spielen.  
🗣️ Olga kann vier Sprachen sprechen.  
🗣️ Was wollen wir essen?

This improves:
✅ sentence structure  
✅ speaking fluency  
✅ grammar understanding

</details>


##  [WORTBILDUNG]  
 ## Nomen + Nomen = Nomen

---

  ##  Neue Wörter zusammensetzen. Ordnen Sie zu.

>**Ananas • Apfel • Gemüse • Kürbis • Nudel • Obst**

1. der [[Nudel]] salat  
2. der [[Obst]] salat  

3. die [[Kürbis]] suppe  
4. die [[Gemüse]] suppe  

5. der [[Apfel]] kuchen  
6. der [[Ananas]] kuchen  




---

 ##  Bilden Sie zusammengesetzte Nomen und notieren Sie sie mit dem Artikel.

1. das Hackfleisch + die Soße =  ~~die Hackfleischsoße ~~
2. die Paprika + der Reis = [[ der Paprikareis]] 
3. der Curry + die Wurst = [[die Currywurst]] 
4. die Milch + das Produkt = [[die Currywurst]] 
5. das Gemüse + die Lasagne = [[die Gemüselasagne]] 
6. die Kartoffel + der Brei = [[der Kartoffelbrei]] 
7. der Fisch + die Suppe = [[die Fischsuppe]]
8. die Ananas + das Eis = [[das Ananaseis]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Nomen + Nomen = Nomen</b></summary>

In this exercise, you practice:
🧠 German compound nouns  
🍲 food vocabulary  
📚 word formation

Your task:
✅ combine two nouns  
✅ build one new noun

---

## Important grammar rule

In German:
✅ two nouns can become one word

Example:
🗣️ die Paprika + der Reis  
➡ der Paprikareis

---

## Important clue

The LAST noun decides:
✅ the article  
✅ the gender

---

## Examples

| Word 1 | Word 2 | New noun |
|---|---|---|
| die Curry | die Wurst | die Currywurst |
| das Gemüse | die Lasagne | die Gemüselasagne |
| die Kartoffel | der Brei | der Kartoffelbrei |

---

## Helpful strategy

### Step 1
Find:
👉 noun 1

### Step 2
Find:
👉 noun 2

### Step 3
Write:
✅ one long noun

---

## Important article rule

The article comes from:
✅ the second noun

Example:

🗣️ die Fischsuppe

because:
- die Suppe → feminine

---

🗣️ der Kartoffelbrei

because:
- der Brei → masculine

---

🗣️ das Ananaseis

because:
- das Eis → neuter

---

## Helpful vocabulary

| German | English |
|---|---|
| der Salat | salad |
| die Suppe | soup |
| der Kuchen | cake |
| das Eis | ice cream |
| die Soße | sauce |
| der Reis | rice |

---

## Important correction

⚠️ Watch carefully:

❌ die Currywurst  
for:
Milch + Produkt

✅ Correct:
<b>das Milchprodukt</b>

because:
- das Produkt → neuter

---

## Practice tip

Read the compound nouns aloud:

🗣️ die Hackfleischsoße  
🗣️ der Paprikareis  
🗣️ die Gemüselasagne  
🗣️ das Ananaseis

This improves:
✅ pronunciation  
✅ vocabulary memory  
✅ understanding of German word formation

</details>


##  Was gibt es am Samstag?

 ## Welcher Tag fehlt? Ergänzen Sie.

1. Montag, ~~Dienstag~~, Mittwoch  
2. Donnerstag, [[Freitag]], Samstag  
3. Sonntag, [[Montag]], Dienstag  

4. Samstag, [[Sonntag]], Montag  
5. Dienstag, [[Mittwoch]], Donnerstag  
6. Freitag, [[Samstag]], Sonntag  

---

 ## [GRAMMATIK KOMPAKT] Satzbau

 ### Schreiben Sie Sätze wie im Beispiel.



---

1.  
a) ~~Am Montag~~ ist Schnipottag.  
b) ~~Schnipottag ~~ ist am Montag.

2.  
a) [[Pizza]] gibt es am Donnerstag.  
b) [[Am Donnerstag]] gibt es Pizza.

3.  
a) [[Am Sonntag]] wollen wir kochen.  
b) [[Wir]] wollen am Sonntag kochen.

4.  
a) [[Am Freitag]] gibt es Fisch.  
b) [[Fisch]] gibt es am Freitag.

---
 ## Ergänzen Sie die passenden Formen von nehmen
  ## Achten Sie auf Groß- und Kleinschreibung.

**Wortliste:**  
*nehme · nimmst · nimmt · nehmen · nehmt · nehmen*



1. Was [[nehmt]] ihr?

2. Wir [[nehmen]] einen Butterkuchen und ein Franzbrötchen.

3. Ben [[nimmt]] ein Fischbrötchen.

4. .[[Nimmst]] du auch ein Fischbrötchen?

5. Nein, ich [[nehme]] ein Rundstück.

6. Ariane und Olga [[nehmen]] das Hamburg-Frühstück.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Welcher Tag fehlt?</b></summary>

In this exercise, you practice:
📅 weekdays in German

Your task:
✅ find the missing day

---

## Reihenfolge der Wochentage

| Deutsch | English |
|---|---|
| Montag | Monday |
| Dienstag | Tuesday |
| Mittwoch | Wednesday |
| Donnerstag | Thursday |
| Freitag | Friday |
| Samstag | Saturday |
| Sonntag | Sunday |

---

## Helpful strategy

Look carefully:
👉 Which day comes before?
👉 Which day comes after?

Example:

Montag → ? → Mittwoch

✅ Dienstag

---

## Practice tip

Say the weekdays aloud:

🗣️ Montag, Dienstag, Mittwoch  
🗣️ Donnerstag, Freitag, Samstag

This improves:
✅ vocabulary  
✅ pronunciation  
✅ memory

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Satzbau</b></summary>

In this exercise, you practice:
🧠 German sentence structure

Your task:
✅ build correct sentences  
✅ change Position 1

---

## Important grammar rule

In German:
✅ the verb stays in Position 2

---

## Example

🗣️ Am Montag ist Schnipottag.

| Position 1 | Position 2 | Rest |
|---|---|---|
| Am Montag | ist | Schnipottag |

---

🗣️ Schnipottag ist am Montag.

| Position 1 | Position 2 | Rest |
|---|---|---|
| Schnipottag | ist | am Montag |

---

## Helpful strategy

You can change:
✅ Position 1

BUT:
⚠️ the verb stays in Position 2

---

## Examples

🗣️ Pizza gibt es am Donnerstag.  
🗣️ Am Donnerstag gibt es Pizza.

🗣️ Wir wollen am Sonntag kochen.  
🗣️ Am Sonntag wollen wir kochen.

---

## Important clue

When:
📅 time expression comes first

then:
✅ verb comes second
✅ subject comes after the verb

Example:
🗣️ Am Freitag gibt es Fisch.

---

## Practice tip

Read both sentence versions aloud.

This improves:
✅ sentence structure  
✅ speaking fluency  
✅ grammar understanding

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;">
<summary><b>💡 Hint – Verb „nehmen“</b></summary>

In this exercise, you practice:
🧠 the verb <b>nehmen</b>

"nehmen" means:
✅ to take

---

## Present tense forms

| Person | nehmen |
|---|---|
| ich | nehme |
| du | nimmst |
| er/sie/es | nimmt |
| wir | nehmen |
| ihr | nehmt |
| sie/Sie | nehmen |

---

## Helpful strategy

First find:
👉 the subject

Then choose:
✅ the correct verb form

---

## Examples

🗣️ Ich nehme ein Brötchen.  
🗣️ Du nimmst einen Kuchen.  
🗣️ Ben nimmt ein Fischbrötchen.

---

## Important clue

⚠️ du and er/sie/es change:

- nehmen → nimmst
- nehmen → nimmt

---

## Helpful grammar

Remember:
✅ nouns are capitalized in German

Examples:
- Fischbrötchen
- Rundstück
- Hamburg-Frühstück

---

## Practice tip

Read aloud:

🗣️ ich nehme  
🗣️ du nimmst  
🗣️ er nimmt  
🗣️ wir nehmen

This improves:
✅ pronunciation  
✅ verb memorization  
✅ speaking confidence

</details>

## [GRAMMATIK KOMPAKT] Modalverben möcht- und mögen
 ## Ergänzen Sie die Formen von **möchten**  
*Achten Sie auf Groß- und Kleinschreibung.*

---

1. Wir ~~möchten~~ gern bezahlen.

2. .[[Möchtest]] du heute Kuchen essen?

3. Mia [[möchte]] heute keinen Nachtisch essen.

4. Was [[möchtet]] ihr trinken?

5. Ich [[möchte]] auch etwas essen.

6. Anne und Mia [[möchten]] Französisch lernen.

 ## Ergänzen Sie die Formen von **mögen**  
*Achten Sie auf Groß- und Kleinschreibung.*

---

1. Ich~~ mag~~ keinen Fisch.

2. Wir [[mögen]] die Mensa.

3. Ben [[mag]] Schnipo.

4. .[[Magst]] du Schnipo?

5. .[[Mögt]] ihr kein Fleisch?

6. Anne und Mia [[mögen]] Gemüse.

  ## mögen oder möchte?  
**Ergänzen Sie. Achten Sie auf Groß- und Kleinschreibung.**



1. Ben ~~mag~~ kein Gemüse, aber er isst sehr gern Fleisch.

2. Wir [[möchten]] heute in der Mensa essen: Es gibt Currywurst!

3. Ich [[möchte]] ein Stück Käsekuchen bestellen.

4. Olga [[mag]] Käsekuchen sehr.

5. .[[Möchtet]] ihr den Labskaus probieren?

6. Ich [[mag]] kein Fleisch, aber ich esse sehr gern Fisch.

7. Ben [[möchte]] heute in der Mensa Schnipo essen, denn er [[mag]] Schnipo sehr.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Modalverben: möchten</b></summary>

In this exercise, you practice:
🧠 the modal verb <b>möchten</b>

"möchten" means:
✅ would like

---

## Present tense forms

| Person | möchten |
|---|---|
| ich | möchte |
| du | möchtest |
| er/sie/es | möchte |
| wir | möchten |
| ihr | möchtet |
| sie/Sie | möchten |

---

## Helpful strategy

First find:
👉 the subject

Then choose:
✅ the correct form of "möchten"

---

## Examples

🗣️ Ich möchte Kaffee trinken.  
🗣️ Möchtest du Kuchen essen?  
🗣️ Wir möchten bezahlen.

---

## Important clue

⚠️ Watch capitalization carefully:

✅ Möchtest  
✅ Möchtet  
❌ möchtest at sentence beginning

---

## Helpful grammar rule

With modal verbs:
✅ the second verb stays at the end in infinitive form.

Examples:
- essen
- trinken
- lernen

---

## Practice tip

Read aloud:

🗣️ ich möchte  
🗣️ du möchtest  
🗣️ ihr möchtet  
🗣️ wir möchten

This improves:
✅ speaking  
✅ pronunciation  
✅ grammar memory

</details>

---

<details style="background:#eefbea;border:1px solid #cfe7bf;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint – Modalverb: mögen</b></summary>

In this exercise, you practice:
🧠 the verb <b>mögen</b>

"mögen" means:
✅ to like

---

## Present tense forms

| Person | mögen |
|---|---|
| ich | mag |
| du | magst |
| er/sie/es | mag |
| wir | mögen |
| ihr | mögt |
| sie/Sie | mögen |

---

## Helpful strategy

Find:
👉 the subject

Then choose:
✅ the correct verb form

---

## Examples

🗣️ Ich mag Fisch.  
🗣️ Ben mag Schnipo.  
🗣️ Mögt ihr Fleisch?

---

## Important clue

⚠️ du and ihr forms are different:

- du → magst  
- ihr → mögt

---

## Helpful vocabulary

| German | English |
|---|---|
| der Fisch | fish |
| das Gemüse | vegetables |
| das Fleisch | meat |
| die Mensa | cafeteria |
| der Nachtisch | dessert |

---

## Practice tip

Read aloud:

🗣️ ich mag  
🗣️ du magst  
🗣️ ihr mögt  
🗣️ wir mögen

This improves:
✅ pronunciation  
✅ fluency  
✅ verb memorization

</details>

---

<details style="background:#fff8e8;border:1px solid #edd8a6;border-radius:14px;padding:14px;">
<summary><b>💡 Hint – mögen oder möchten?</b></summary>

In this exercise, you practice:
🧠 the difference between <b>mögen</b> and <b>möchten</b>

---

## Important difference

### mögen
= to like something

🗣️ Ich mag Pizza.  
🗣️ Ben mag Schnipo.

---

### möchten
= would like / want politely

🗣️ Ich möchte Pizza essen.  
🗣️ Wir möchten bezahlen.

---

## Helpful strategy

Ask yourself:

👉 Does the person LIKE something?
✅ Use <b>mögen</b>

👉 Does the person WANT something now?
✅ Use <b>möchten</b>

---

## Examples

🗣️ Olga mag Käsekuchen sehr.  
➡ She likes cheesecake.

🗣️ Ich möchte ein Stück Käsekuchen bestellen.  
➡ I would like to order cheesecake.

---

## Important clue

⚠️ "möchten" often comes with:
- essen
- trinken
- bestellen
- lernen

because:
✅ another verb stays at the end

---

## Helpful comparison

| mögen | möchten |
|---|---|
| Ich mag Fisch. | Ich möchte Fisch essen. |
| Wir mögen Pizza. | Wir möchten Pizza bestellen. |

---

## Practice tip

Read aloud:

🗣️ Ich mag Schnipo.  
🗣️ Ich möchte Schnipo essen.

This helps you understand:
✅ liking vs wanting  
✅ modal verbs  
✅ sentence meaning

</details>


## Ein leerer Bauch studiert nicht gern  
  ## Wortschatz

| 3A |  |  |  |
|---|---|---|---|
| die Mensa, -n | kochen | das Steak, -s | das Fast Food (nur Sg.) |
| essen (isst) | abends | der Fisch, -e* | der Hering, -e* |
| das Essen (nur Sg.) | mitnehmen | der Lachs, -e* | der Heringssalat, -e |
| das Mensa-Essen (nur Sg.) | können (kann) | die Lasagne, -n | das Brötchen, - |
| die Schokolade, -n | wollen (will) | die Gemüselasagne, -n | das Fischbrötchen, - |
| das Tier, -e | lieben | die Beilage, -n* | das Franzbrötchen, - |
| die Milch (nur Sg.) | Ungarisch | die Kartoffel, -n* | der Toast, - |
| das Produkt, -e | toll | der Kartoffelbrei, -e | der Speck (nur Sg.) |
| das Milchprodukt, -e* | der Stress (nur Sg.) | der Knödel, - | die Bohne, -n |
| die Laktoseintoleranz (nur Sg.) | der Service (nur Sg.) | die Nudel, -n | die rote Bete (nur Sg.) |
| vegan (essen) | das Seminar, -e | das Rührei, -er* | das Spiegelei, -er |
| der Veganer, - / die Veganerin, -nen | okay / o.k. | der Käse, - | die Butter (nur Sg.) |
| Ich bin Veganer/in. | der Snack, -s | der Ziegenkäse, - | der Butterkuchen, - |
| der Vegetarier, - / die Vegetarierin, -nen | finden | die Salami, -s | der Käsekuchen, - |
| Ich bin Vegetarier/in. | Ich finde das okay / unhöflich / … | der Schinken, - | die Torte, -n |
| geben (gibt) | das Ei, -er* | der Champignon, -s* | die Schokoladentorte, -n |
| Es gibt … | der Knoblauch (nur Sg.) | die Suppe, -n | die rote Grütze (nur Sg.) |
| das Gericht, -e* | riechen | die Gemüsesuppe, -n | die Kirsche, -n |
| der Döner Kebab, -s | gehen | die Kürbissuppe, -n | die Vanille (nur Sg.) |
| die Pizza, -s / Pizzen | Das geht (nicht). | der Salat, -e* | die Vanillesoße, -n |
| das Fleisch (nur Sg.)* | stören | der Nudelsalat, -e | der Zimt (nur Sg.) |
| das Hackfleisch (nur Sg.) | total | der Obstsalat, -e | der Zucker (nur Sg.) |
| das Hähnchen, - | unhöflich | der Teller, - | das Getränk, -e |
| das Schnitzel, -* | die Kybernetik (nur Sg.) | der Salatteller, - | der Tee, -s |
| das Jägerschnitzel, - | die Philosophie (nur Sg.) | das Obst (nur Sg.)* | der Espresso, -s |
| die Wurst, -e* | Jura (kein Artikel) | der Apfel, -* | die Orange, -n |
| die Currywurst, -e | sozial | die Ananas, -/-se | der Saft, -e |
| der Reis (nur Sg.)* | der Dozent, -en / die Dozentin, -nen | die Birne, -n | der Orangensaft, -e |
| der Paprikareis (nur Sg.) | manchmal | die Erdbeere, -n | die Cola, -s |
| die Pommes (frites) (nur Pl.) | der Hunger (nur Sg.) | der Nachtisch, -* | das Wasser (hier nur Sg.) |
| die Spaghetti, -s | der Artikel, - | das Eis | das Glas, -er |
| die Soße, -n | das Forum, Foren | das / der Joghurt, -s | die Tasse, -n |
| die Hackfleischsoße, -n | der Beitrag, -e | der Kuchen, -* | das Kännchen, - |
| das Gemüse (nur Sg.)* | der Forumsbeitrag, -e | der Apfelkuchen, - | die Flasche, -n |
| der Brokkoli, -* | das Kino, -s | der Milchreis (nur Sg.)* | die Bedienung (nur Sg.) |
| die Karotte, -n* |  | der Quark (nur Sg.)* | schmecken |
| der / die Paprika, -s* |  | der Erdbeerquark, -s | bestellen |
| die Tomate, -n* |  | der Gast, -* | nehmen (nimmt) |
| die Pfanne, -n |  | das Personal (nur Sg.) | dann |
| täglich |  | geschlossen | lecker |
| das Café, -s |  | vegetarisch (essen) | möchte |
| dort |  |  | mögen (mag) |
|  |  |  | die Rechnung, -en |
|  |  |  | bezahlen |
|  |  |  | zusammen + getrennt |
|  |  |  | Stimmt so. |
|  |  |  | spät |
|  |  |  | zu spät sein |

---

  ## 3B
* der Plan, -e  
* der Speiseplan, -e  
* der Tag, -e  
* der Montag, -e  
* der Dienstag, -e  
* der Mittwoch, -e  
* der Donnerstag, -e  
* der Freitag, -e  
* der Samstag, -e  
* der Sonntag, -e  
* am Montag / Dienstag / …

---

 ## 3C
* die Karte, -n  
* die Speisekarte, -n  
* der Campus, -/-se  
* herzhaft ≠ süß  
* das Frühstück, -e  
* das Mittagessen, -  
* warm – heiß  
* das Stück, -e  
* der Hamburger, -


---

# ✅ Lösungen – Kapitel 3

## Das essen Studierende in Deutschland

 ## Wie heißen die Gerichte?

1. Bratkartoffeln  
2. Currywurst  
3. Gemüse-Reis-Pfanne  
4. Hackfleischsoße  
5. Jägerschnitzel  
6. Paprikareis  
7. Pommes frites  
8. Studentenfutter  

---

 ## Hören Sie und ergänzen Sie die Fragen

1. Esst ihr gern Gemüse?  
2. Isst du Fleisch?  
3. Ist Mia Vegetarierin?  
4. Isst Pia vegan?  

---

 ## Modalverben: können

1. Ich kann sehr gut kochen.  
2. Mia kann keine Milchprodukte essen.  
3. Du kannst in der Mensa günstig essen.  
4. Wir können sehr gut Keyboard spielen.  
5. Studierende können das Essen mitnehmen.  
6. Könnt ihr Spanisch sprechen?

---

 ## Modalverben: wollen

1. Mia will kein Fleisch essen.  
2. Heute will ich lieber zu Hause essen.  
3. Wir wollen heute Fußball schauen.  
4. Ihr wollt Physik studieren?  
5. Pit und Peter wollen heute Schnipo essen.  
6. Willst du heute Hähnchen essen?

---

## Modalverb können und wollen – Wortstellung

| Nr. | Lösung |
|---|---|
| 1 | Ich kann sehr gut französisch kochen. |
| 2 | Wir wollen heute in der Mensa essen. |
| 3 | Peter kann sehr gut Gitarre spielen. |
| 4 | Olga kann vier Sprachen sprechen. |
| 5 | Was will Susanne studieren? |
| 6 | Was wollen wir essen? |

---

## Wortbildung – Neue Wörter

1. der Nudelsalat  
2. der Obstsalat  
3. die Kürbissuppe  
4. die Gemüsesuppe  
5. der Apfelkuchen  
6. der Ananaskuchen  

---

 ## Zusammengesetzte Nomen

1. die Hackfleischsoße  
2. der Paprikareis  
3. die Currywurst  
4. das Milchprodukt  
5. die Gemüselasagne  
6. der Kartoffelbrei  
7. die Fischsuppe  
8. das Ananaseis  

---

## Was gibt es am Samstag?

 ## Welcher Tag fehlt?

1. Dienstag  
2. Freitag  
3. Montag  
4. Sonntag  
5. Mittwoch  
6. Samstag  

---

 ## Satzbau

1.  
a) Am Montag ist Schnipottag.  
b) Schnipottag ist am Montag.  

2.  
a) Pizza gibt es am Donnerstag.  
b) Am Donnerstag gibt es Pizza.  

3.  
a) Am Sonntag wollen wir kochen.  
b) Wir wollen am Sonntag kochen.  

4.  
a) Am Freitag gibt es Fisch.  
b) Fisch gibt es am Freitag.  

---

## Verb nehmen

1. Was nehmt ihr?  
2. Wir nehmen einen Butterkuchen und ein Franzbrötchen.  
3. Ben nimmt ein Fischbrötchen.  
4. Nimmst du auch ein Fischbrötchen?  
5. Nein, ich nehme ein Rundstück.  
6. Ariane und Olga nehmen das Hamburg-Frühstück.  

---

## Modalverben: möchten

1. Wir möchten gern bezahlen.  
2. Möchtest du heute Kuchen essen?  
3. Mia möchte heute keinen Nachtisch essen.  
4. Was möchtet ihr trinken?  
5. Ich möchte auch etwas essen.  
6. Anne und Mia möchten Französisch lernen.  

---

 ## Verb mögen

1. Ich mag keinen Fisch.  
2. Wir mögen die Mensa.  
3. Ben mag Schnipo.  
4. Magst du Schnipo?  
5. Mögt ihr kein Fleisch?  
6. Anne und Mia mögen Gemüse.  

---

 ## mögen oder möchten

1. Ben mag kein Gemüse, aber er isst sehr gern Fleisch.  
2. Wir möchten heute in der Mensa essen: Es gibt Currywurst!  
3. Ich möchte ein Stück Käsekuchen bestellen.  
4. Olga mag Käsekuchen sehr.  
5. Möchtet ihr den Labskaus probieren?  
6. Ich mag kein Fleisch, aber ich esse sehr gern Fisch.  
7. Ben möchte heute in der Mensa Schnipo essen, denn er mag Schnipo sehr.

---