
<!--

author:   Kanwal & Makhdoom
email:    masub.makhdoom@ovgu.de
date:     28/01/2026
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

# Kapitel 1 – Übungsbuchteil

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <pattern id="lines" width="10" height="10" patternUnits="userSpaceOnUse">
      <path d="M0,0 L10,10" stroke="#e4ece8" stroke-width="1"/>
    </pattern>

    <linearGradient id="green" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#8fa31f"/>
      <stop offset="100%" stop-color="#b9c94a"/>
    </linearGradient>

    <style>
      .title{font-family:Georgia,serif;font-size:76px;font-weight:700;fill:#7a8b00}
      .sub{font-family:Arial,sans-serif;font-size:38px;font-weight:600;fill:#607070}
      .small{font-family:Arial,sans-serif;font-size:24px;fill:#4f5f5f}
      .chip{font-family:Arial,sans-serif;font-size:22px;font-weight:700;fill:white}
      .boxtext{font-family:Arial,sans-serif;font-size:24px;font-weight:600;fill:#4b5c5c}
    </style>
  </defs>

  <rect width="1600" height="900" fill="url(#lines)"/>

  <rect x="250" y="120" width="1100" height="650" rx="28" fill="#ffffff" stroke="#b8d1cc" stroke-width="4"/>

  <rect x="250" y="120" width="34" height="650" fill="#9fbfbb"/>
  <rect x="310" y="165" width="230" height="56" rx="18" fill="url(#green)"/>
  <text x="425" y="201" text-anchor="middle" class="chip">KAPITEL 1</text>

  <text x="800" y="340" text-anchor="middle" class="title">Übungsbuchteil</text>
  <text x="800" y="405" text-anchor="middle" class="sub">Herzlich willkommen!</text>

  <g>
    <rect x="350" y="500" width="260" height="120" rx="22" fill="#f6f9ef" stroke="#dce8c8"/>
    <text x="480" y="548" text-anchor="middle" class="boxtext">👋 Begrüßen</text>
    <text x="480" y="585" text-anchor="middle" class="small">Hallo • Guten Tag</text>

    <rect x="670" y="500" width="260" height="120" rx="22" fill="#eef7ff" stroke="#cfe3ff"/>
    <text x="800" y="548" text-anchor="middle" class="boxtext">🗣 Vorstellen</text>
    <text x="800" y="585" text-anchor="middle" class="small">Ich heiße ...</text>

    <rect x="990" y="500" width="260" height="120" rx="22" fill="#fff8e8" stroke="#ead49b"/>
    <text x="1120" y="548" text-anchor="middle" class="boxtext">🔢 Zahlen</text>
    <text x="1120" y="585" text-anchor="middle" class="small">Telefonnummern</text>
  </g>

  <text x="800" y="705" text-anchor="middle" class="small">
    Lernen • Üben • Hören • Schreiben
  </text>
</svg>

---


    --{{0}}--

!?[](https://github.com/Masub27/A1-German-Tool/blob/main/chapter_1.mp4?raw=true)


# 🤖 Kapitel 1 Smart Lern-Bot

<section style="max-width:1200px;margin:auto;border-radius:24px;padding:20px;background:#eef3f9;font-family:Arial,sans-serif;">

<div style="background:white;border-radius:22px;padding:18px;border:1px solid #d0d9e6;box-shadow:0 8px 24px rgba(0,0,0,0.06);">

<h2 style="margin-top:0;color:#2f6fd1;">🤖 Kapitel 1 Deutsch Lern-Bot</h2>

<div id="k1-chat" style="min-height:260px;max-height:420px;overflow:auto;background:#f4f7fb;border-radius:18px;padding:16px;border:1px solid #d0d9e6;line-height:1.6;">
<b>Bot:</b> Hallo! Ask me about Kapitel 1: greetings, names, origin, W-questions, pronouns, verbs, numbers, and telephone numbers.
</div>

<div id="k1-buttons" style="margin-top:14px;display:flex;gap:8px;flex-wrap:wrap;"></div>

<div style="margin-top:16px;display:flex;gap:10px;flex-wrap:wrap;">
<input id="k1-input" type="text" placeholder="Ask your question..." style="flex:1;padding:14px;border-radius:14px;border:1px solid #b8c7db;font-size:15px;background:white;">
<button id="k1-send" style="padding:14px 18px;background:#2f6fd1;color:white;border:none;border-radius:14px;font-weight:bold;cursor:pointer;">Ask</button>
<button id="k1-clear" style="padding:14px 18px;background:white;color:#2f6fd1;border:1px solid #2f6fd1;border-radius:14px;font-weight:bold;cursor:pointer;">Clear</button>
</div>

</div>
</section>

<script>
(() => {
  const chat = document.getElementById("k1-chat");
  const input = document.getElementById("k1-input");
  const send = document.getElementById("k1-send");
  const clear = document.getElementById("k1-clear");
  const buttons = document.getElementById("k1-buttons");

  const quick = [
    "What can I learn in Kapitel 1?",
    "How do I introduce myself?",
    "What is du and Sie?",
    "What are W-questions?",
    "How do I ask where someone comes from?",
    "What is Vorname and Familienname?",
    "How do I say how I feel?",
    "What are German pronouns?",
    "How do I conjugate wohnen?",
    "How do I conjugate sprechen?",
    "How do I say phone numbers?",
    "Give me important answers"
  ];

  function norm(t){
    return String(t || "").toLowerCase()
      .replace(/ä/g,"ae").replace(/ö/g,"oe").replace(/ü/g,"ue").replace(/ß/g,"ss")
      .replace(/[^\w\s.-]/g," ").replace(/\s+/g," ").trim();
  }

  function msg(text,type){
    chat.innerHTML += `<div style="margin:10px 0;padding:12px;border-radius:14px;background:${type==="user"?"#2f6fd1":"white"};color:${type==="user"?"white":"#1a1a1a"};border:${type==="user"?"none":"1px solid #d0d9e6"};"><b>${type==="user"?"You":"Bot"}:</b> ${text}</div>`;
    chat.scrollTop = chat.scrollHeight;
  }

  function answer(q){
    q = norm(q);

    if(q.includes("learn") || q.includes("kapitel 1") || q.includes("chapter 1"))
      return "In Kapitel 1 you learn greetings, introductions, names, countries, languages, formal/informal speech, W-questions, verbs in Präsens, numbers, and telephone numbers.";

    if(q.includes("introduce") || q.includes("vorstellen") || q.includes("myself"))
      return "You can introduce yourself like this:<br><br><b>Ich heiße Masub Makhdoom.</b><br><b>Ich komme aus Pakistan.</b><br><b>Ich wohne in Magdeburg.</b><br><b>Ich spreche Urdu, Englisch und Deutsch.</b>";

    if(q.includes("du") && q.includes("sie"))
      return "<b>du</b> is informal. Use it with friends, classmates, and young people.<br><br><b>Sie</b> is formal. Use it with professors, teachers, strangers, and official situations.";

    if(q.includes("w-question") || q.includes("w fragen") || q.includes("w-fragen") || q.includes("frage"))
      return "Important W-questions:<br><br><b>Wie heißt du?</b> = What is your name?<br><b>Wie heißen Sie?</b> = What is your name? formal<br><b>Woher kommst du?</b> = Where are you from?<br><b>Was studierst du?</b> = What do you study?<br><b>Wo wohnst du?</b> = Where do you live?";

    if(q.includes("woher") || q.includes("come from") || q.includes("origin"))
      return "To ask origin:<br><br><b>Woher kommst du?</b> informal<br><b>Woher kommen Sie?</b> formal<br><br>Answer:<br><b>Ich komme aus Pakistan.</b>";

    if(q.includes("vorname") || q.includes("familienname"))
      return "<b>Vorname</b> means first name.<br><b>Familienname</b> means family name / surname.<br><br>Example:<br>Ferenc ist der Vorname.<br>Simon ist der Familienname.";

    if(q.includes("how i feel") || q.includes("wie geht") || q.includes("geht es"))
      return "Question:<br><b>Wie geht es dir?</b><br><br>Answers:<br><b>Mir geht es gut.</b><br><b>Mir geht es super.</b><br><b>Es geht so.</b><br><b>Mir geht es nicht so gut.</b>";

    if(q.includes("pronoun") || q.includes("pronomen") || q.includes("er sie"))
      return "German pronouns from this chapter:<br><br><b>er</b> = he / masculine singular<br><b>sie</b> = she / feminine singular<br><b>sie</b> = they / plural<br><br>Examples:<br>Gabriel → Er<br>Nicole → Sie<br>Sarah und Dana → Sie";

    if(q.includes("wohnen"))
      return "Conjugation of <b>wohnen</b>:<br><br>ich wohne<br>du wohnst<br>er/sie/es wohnt<br>wir wohnen<br>ihr wohnt<br>sie/Sie wohnen";

    if(q.includes("sprechen"))
      return "Conjugation of <b>sprechen</b>:<br><br>ich spreche<br>du sprichst<br>er/sie/es spricht<br>wir sprechen<br>ihr sprecht<br>sie/Sie sprechen<br><br>Important: e changes to i for du and er/sie/es.";

    if(q.includes("sein"))
      return "Conjugation of <b>sein</b>:<br><br>ich bin<br>du bist<br>er/sie/es ist<br>wir sind<br>ihr seid<br>sie/Sie sind";

    if(q.includes("number") || q.includes("zahlen") || q.includes("telephone") || q.includes("telefon"))
      return "In Kapitel 1 you practise numbers and telephone numbers.<br><br>Examples:<br>57 = siebenundfünfzig<br>92 = zweiundneunzig<br>374 = dreihundertvierundsiebzig<br><br>Telephone numbers are usually read digit by digit or in small groups.";

    if(q.includes("formal") || q.includes("formell"))
      return "Formal examples:<br><br><b>Wie heißen Sie?</b><br><b>Woher kommen Sie?</b><br><b>Wie ist Ihr Familienname?</b>";

    if(q.includes("informal") || q.includes("informell"))
      return "Informal examples:<br><br><b>Wie heißt du?</b><br><b>Woher kommst du?</b><br><b>Wie ist dein Vorname?</b>";

    if(q.includes("answer") || q.includes("key") || q.includes("loesung") || q.includes("lösung"))
      return "Important answers:<br><br>Begrüßung: Guten Morgen, Guten Tag, Hallo.<br>Verabschiedung: Auf Wiedersehen, Bis bald, Bis morgen, Tschüss.<br><br>W-Fragen: Wie heißt du? Woher kommst du? Was studierst du?<br><br>Verbs: ich wohne, du wohnst, er wohnt; ich spreche, du sprichst, er spricht.";

    return "Ask me about Kapitel 1: greetings, names, du/Sie, W-questions, origin, pronouns, verbs, numbers, or telephone numbers.";
  }

  function ask(text){
    const q = text || input.value.trim();
    if(!q) return;
    msg(q,"user");
    msg(answer(q),"bot");
    input.value = "";
  }

  send.onclick = () => ask();
  clear.onclick = () => {
    chat.innerHTML = "<b>Bot:</b> Hallo! Ask me about Kapitel 1 😊";
  };

  input.addEventListener("keydown", e => {
    e.stopPropagation();
    if(e.key === "Enter"){
      e.preventDefault();
      ask();
    }
  });

  quick.forEach(q => {
    const b = document.createElement("button");
    b.textContent = q;
    b.style.padding = "9px 12px";
    b.style.borderRadius = "12px";
    b.style.border = "1px solid #2f6fd1";
    b.style.background = "white";
    b.style.color = "#2f6fd1";
    b.style.cursor = "pointer";
    b.onclick = () => ask(q);
    buttons.appendChild(b);
  });
})();
</script>


# Guten Tag! Ich heiße …

 ## Welche Antwort passt? Ordnen Sie zu.

  ### Gespräch A:

1. Woher kommen Sie, Frau Larsson?  
2. Wie ist Ihr Familienname?  
3. Guten Tag, ich heiße Angelika Kessler.

1. 😊 [[3]]  Guten Tag, Frau Kessler. Ich heiße Emma. 


2. 😊[[2]]  Mein Familienname ist Larsson.  


3. 😊[[1]]  Ich komme aus Stockholm.


---

  ### Gespräch B:

1. Hallo! Ich heiße Bojan. Wie heißt du?  
2. Ich komme aus Warna. Und du?

1. 😊[[2]]  Ich komme aus Split.  


2. 😊[[1]]  Hallo Bojan! Ich bin Lea. Woher kommst du?

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must match questions and answers in a conversation.

To solve the task:

1️⃣ Read the question carefully 

2️⃣ Look for keywords:
- name
- country/city
- greeting

3️⃣ Find the logical answer

---

### Helpful question patterns

#### Wie heißen Sie?
= What is your name?

Possible answer:
- Ich heiße …
- Ich bin …

---

#### Wie ist Ihr Familienname?
= What is your family name?

Possible answer:
- Mein Familienname ist …

---

#### Woher kommen Sie?
= Where are you from?

Possible answer:
- Ich komme aus …

---

### Conversation strategy

A conversation usually follows this order:

1. Greeting  
2. Name  
3. Origin/place  

This helps you put the answers in the correct order.

---

### Important

Formal conversation uses:
- Sie
- Ihr

Informal conversation uses:
- du
- dein

Look carefully at the pronouns in the dialogue.

</details>

---

  ## Sortieren und schreiben Sie die Gespräche A und B aus 1a.  
>Hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_001.mp3?raw=true)

  ### Gespräch A:
* [[ Guten Tag, ich heiße Angelika Kessler]] 

* [[Guten Tag, Frau Kessler. Ich heiße Emma]] 

* [[Wie ist Ihr Familienname? ]]  

* [[Mein Familienname ist Larsson]] 

* [[ Woher kommen Sie, Frau Larsson? ]] 

* [[Ich komme aus Stockholm]] 


  ### Gespräch B:

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_002.mp3?raw=true)

* [[Hallo! Ich heiße Bojan. Wie heißt du?]] 

* [[Hallo Bojan! Ich bin Lea. Woher kommst du? ]]  

* [[Ich komme aus Warna. Und du?]]  

* [[Ich komme aus Split]]  

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must put the dialogue sentences into the correct conversation order.

To solve the task:

1️⃣ Start with the greeting  
A conversation usually begins with:
- Hallo!
- Guten Tag!

---

2️⃣ Continue with names

After a greeting, people usually say:
- Ich heiße …
- Ich bin …

---

3️⃣ Then come questions

Typical beginner questions:
- Wie heißt du?
- Wie ist Ihr Familienname?
- Woher kommst du?
- Woher kommen Sie?

---

4️⃣ Match the correct answers

Examples:
- Woher kommst du?
→ Ich komme aus …

- Wie ist Ihr Familienname?
→ Mein Familienname ist …

---

### Important

Look carefully at:
- formal language → Sie / Ihr
- informal language → du / dein

#### Gespräch A
= formal conversation

#### Gespräch B
= informal conversation

This helps you order the dialogue correctly.

---

### Listening strategy

Listen to:
- greeting order
- question-answer rhythm
- pauses between speakers

This helps you understand natural German conversation flow.

</details>

---

  ## Welches Gespräch ist formell, welches Gespräch ist informell?

Gespräch A: [[Formell]]


Gespräch B: [[Informell]]


---

  ## Wie schreibt man das?

   ## Buchstabieren Sie die Namen.  
>Hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_003.mp3?raw=true)

1. Anke  
2. Thorsten  
3. Xaver  
4. Wigald  
5. Mey  
6. Jöckel  
7. Dussmann  
8. Quandt  
9. Bäßler  
10. Pfützner  

---

   ## Hören Sie und ergänzen Sie die Namen.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_004.mp3?raw=true)


1)  [[J]]ochen    Schnei[[d]]er 
[[?]] Richtige Antwort: **J / d**. Diese Antwort passt zum Kontext der Aufgabe.

2) Va[[l]]en[[t]]in[[a]]   P[[a]]len[[z]] 
[[?]] Richtige Antwort: **l / t / a / a / z**. Diese Antwort passt zum Kontext der Aufgabe.

3) Chri[[s]][[t]]tian    Bü[[c]][[h]]el 
[[?]] Richtige Antwort: **s / t / c / h**. Diese Antwort passt zum Kontext der Aufgabe.

4) Ale[[x]]and[[r]]a    W[[a]]nn[[e]]r  
[[?]] Richtige Antwort: **r / a / e**. Diese Antwort passt zum Kontext der Aufgabe.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening exercise, you must complete German names by listening carefully to spelling and pronunciation.

To solve the task:

1️⃣ Listen carefully to each name  
2️⃣ Focus on:
- individual letters
- German pronunciation
- spelling patterns

---

### Helpful listening strategy

German names are often spelled letter by letter.

Pay attention to:
- consonants like:
  - d
  - t
  - z
  - h

- vowels like:
  - a
  - e
  - i

---

### Important pronunciation tips

#### d / t
These sounds can sound similar.
Listen carefully to the ending of the sound.

---

#### z
In German, “z” sounds like:
→ “ts”

Example:
- Palenz

---

#### ch
The German “ch” has a soft sound.

Example:
- Büchel

---

### Helpful trick

Read the incomplete name first:
- Jochen Schnei__er
- Valen__in__
- Chri__tian

Then listen and imagine the complete word.

This helps you predict the missing letters.

</details>

---

  ## Hören Sie und schreiben Sie die Namen.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_005.mp3?raw=true)

1) [[Paula Koch]] 


2) [[Anna Hausmann]]


3) [[Leon Wagner]] 


4) [[Michael Schneider]] 

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening exercise, you must write complete German first names and family names.

To solve the task:

1️⃣ Listen carefully to:
- first name
- surname (Familienname)

2️⃣ Pay attention to spelling and pronunciation.

---

### Helpful listening strategy

German names are often spoken slowly and clearly in beginner exercises.

Listen for:
- vowels
- double consonants
- common German surnames

Examples:
- Koch
- Wagner
- Schneider

---

### Important pronunciation tips

#### sch
In German:
- “sch” sounds like “sh”

Example:
- Schneider

---

#### ei
Usually sounds like:
→ “eye”

Example:
- Schneider

---

#### au
Usually sounds like:
→ “ow”

Example:
- Hausmann

---

### Writing strategy

Write:
- first name first
- surname second

Both names begin with a capital letter.

Examples:
- Paula Koch
- Leon Wagner

</details>

---

   ## Hören Sie und ergänzen Sie die Vokale.  
>Sprechen Sie dann nach.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_006.mp3?raw=true)

1)  Hall[[o]]! [[I]]ch h[[e]][[i]]ße Lin.  
[[?]] Richtige Antwort: **o / I / e / i**. Diese Antwort passt zum Kontext der Aufgabe.

2)  [[I]]ch b[[i]] neu hier [[i]]m Deutschk[[u]]rs.  
[[?]] Richtige Antwort: **I / i / i / u**. Diese Antwort passt zum Kontext der Aufgabe.
 
3)  [[I]]ch k[[o]]mme aus Ch[[i]]na.  
[[?]] Richtige Antwort: **I / o / i**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

4) [[U]]nd d_[[u]], woh[[e]]r  k[[o]]mmst d[[u]]?
[[?]] Richtige Antwort: **U / u / e / o / u**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening and pronunciation exercise, you must:
1️⃣ complete the missing vowels  

2️⃣ repeat the sentences aloud

---

### Step 1️⃣ Listen carefully to the vowels

German vowels are:
- a
- e
- i
- o
- u

Pay attention to:
- short sounds
- long sounds
- stressed syllables

---

### Helpful pronunciation strategy

#### ich
The vowel:
→ i

Example:
- Ich heiße …
- Ich komme …

---

#### komme
Listen carefully to:
→ o

Example:
- komme

---

#### Deutschkurs
The vowel sound in:
→ kurs
is:
→ u

---

### Step 2️⃣ Use sentence meaning

Even if you do not hear every sound clearly, the sentence meaning helps.

Examples:
- „Ich komme aus …“
- „Woher kommst du?“

These are common German beginner phrases.

---

### Step 3️⃣ Speak after listening

Repeat the sentences slowly:
- focus on vowels
- stress the correct syllables
- imitate pronunciation rhythm

This helps improve:
✅ listening  
✅ speaking  
✅ pronunciation

</details>

---

  ## Hören Sie und schreiben Sie.  Beantworten Sie dann die Fragen.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_007.mp3?raw=true)

1.~~ Hallo~~

2. [[Ich heiße Luis]]

3. [[Ich komme aus Spanien]]

4. [[Wie heißt du?]]

5. [[Woher kommst du?]]



# 3 GRAMMATIK KOMPAKT  
  ## W-Fragen und Antworten

  ## Was passt? Ergänzen Sie.

**Wörter:** 

>Woher · Wie · Wie · Wie · ist · komme · heiße

1. Wie heißen Sie? ☐ Ich [[ heiße ]] Schulz.


2. ...  [[ Wie ]] ist Ihr Vorname? ☐ Mein Vorname [[ ist ]]Thomas.


3. ... [[ Wie ]] schreibt man das? ☐ T-H-O-M-A-S.


4.  .[[ Woher ]]  kommen Sie? ☐ Ich [[ komme ]] aus Deutschland.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you complete:
- W-questions
- answers
- common introduction phrases

To solve the task:

1️⃣ Read the question carefully  
2️⃣ Look for the correct question word:
- Wie
- Woher

3️⃣ Then complete the answer with the correct verb.

---

### Important question words

#### Wie
Use for:
- names
- spelling
- personal information

Examples:
- Wie heißen Sie?
- Wie schreibt man das?
- Wie ist Ihr Vorname?

---

#### Woher
Use for:
- origin / country / city

Example:
- Woher kommen Sie?

Possible answer:
- Ich komme aus Deutschland.

---

### Helpful grammar strategy

#### heißen
Used for names:
- Ich heiße …

#### ist
Used with:
- Mein Vorname ist …

#### komme
Used with:
- Ich komme aus …

---

### Important

German nouns begin with a capital letter:
- Vorname
- Deutschland

Question words also begin with a capital letter at the beginning of the sentence.

</details>

---

  ##  Schreiben Sie sechs Fragen.

| W-Frage | Verb (du / Sie) | Ergänzung | ? |
|-------|----------------|-----------|---|
| Wie   | heißen / heißt | Ihr Vorname / dein Vorname | ? |
| Wie   | ist            | Ihr Familienname / dein Familienname | ? |
| Woher | kommen / kommst| Sie / du  | ? |



1)  Wie heißt du? 

2)  [[Wie heißen Sie? ]]


3)  [[Wie ist dein Vorname?]]


4)  [[Wie ist Ihr Familienname?]]


5)  [[Woher kommst du?]]


6)  [[Woher kommen Sie?]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you build correct German W-questions.

To solve the task:

1️⃣ Start with the question word:
- Wie
- Woher

2️⃣ Put the verb in Position 2.

3️⃣ Add:
- du (informal)
or
- Sie / Ihr (formal)

---

### Important difference

#### Informal
Use with friends or classmates:
- du
- dein

Examples:
- Wie heißt du?
- Wie ist dein Vorname?

---

#### Formal
Use with strangers or official situations:
- Sie
- Ihr

Examples:
- Wie heißen Sie?
- Wie ist Ihr Familienname?

---

### Helpful grammar patterns

#### Name questions
- Wie heißt du?
- Wie heißen Sie?

#### First name
- Wie ist dein Vorname?
- Wie ist Ihr Vorname?

#### Origin
- Woher kommst du?
- Woher kommen Sie?

---

### Important

At the beginning of a sentence:
- Wie
- Woher

begin with a capital letter.

German nouns also begin with capital letters:
- Vorname
- Familienname

</details>

---



  ## Woher kommt …?

Erkennen Sie die europäischen Flaggen?  
Schreiben Sie wie im Beispiel.

1. 🇩🇪 Simone
2. 🇦🇹 Alina
3. 🇨🇭 Niklas
4. 🇫🇷 Noah
5. 🇱🇺 Jean
6. 🇧🇪 Wout
7. 🇳🇱 Anouk
8. 🇩🇰 Mette
9. 🇵🇱 Arek
10. 🇨🇿 Jaromir
11. 🇵🇹 Luisa
12. 🇭🇺 Enikö 

**Beispiel:**  
1) Simone kommt aus Deutschland.

2) [[Alina kommt aus Österreich]] 
[[?]] Richtige Antwort: **Alina kommt aus Österreich**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

3) [[Niklas kommt aus der Schweiz]]
[[?]] Richtige Antwort: **Niklas kommt aus der Schweiz**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

4)  [[Noah kommt aus Frankreich]]
[[?]] Richtige Antwort: **Noah kommt aus Frankreich**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

5)  [[Jean kommt aus Luxemburg]]
[[?]] Richtige Antwort: **Jean kommt aus Luxemburg**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

6)  [[Wout kommt aus Belgien]]
[[?]] Richtige Antwort: **Wout kommt aus Belgien**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

7)  [[Anouk kommt aus den Niederlanden]]
[[?]] Richtige Antwort: **Anouk kommt aus den Niederlanden**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

8)  [[Mette kommt aus Dänemark]]
[[?]] Richtige Antwort: **Mette kommt aus Dänemark**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

9)  [[Arek kommt aus Polen]]
[[?]] Richtige Antwort: **Arek kommt aus Polen**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

10)  [[Jaromír kommt aus Tschechien]]
[[?]] Richtige Antwort: **Jaromír kommt aus Tschechien**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

11)  [[Luisa kommt aus Portugal]]
[[?]] Richtige Antwort: **Luisa kommt aus Portugal**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

12)  [[Enikö kommt aus Ungarn]]
[[?]] Richtige Antwort: **Enikö kommt aus Ungarn**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.


---

  ## Woher kommen Sie?

  ### Ergänzen Sie das Gespräch.  Hören Sie dann zur Kontrolle.

  ![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um09.36.28.png?raw=true)

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_008.mp3?raw=true)

1. Guten Tag, ich [[heiße]] Fabiola Pessoa.  

   Und wie [[heißen]] Sie?


2. Ich [[heiße]] Ferenc Simon. Ferenc [[ist]]  

   mein Vorname und Simon mein [[Familienname]].


3. Wie [[buchstabiert]] man das?  

   ° F-E-R-E-N-C S-I-M-O-N.

4. Woher [[kommen]] Sie, Herr Simon?


5. Ich komme [[aus]][[Ungarn]]. Und Sie?


6. Ich [[komme]] aus Portugal.


<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you complete a formal introduction conversation in German.

To solve the task:

1️⃣ Look for common conversation patterns:
- greeting
- name
- spelling
- country/origin

---

### Important phrases

#### Name introduction
- Ich heiße …
- Und wie heißen Sie?

Use:
👉 heißen for names

---

### Vorname and Familienname

- Vorname = first name
- Familienname = surname/family name

Example:
- Ferenc ist mein Vorname.
- Simon ist mein Familienname.

---

### buchstabieren

When somebody asks:
- Wie buchstabiert man das?

you spell the name letter by letter.

---

### Herkunft / origin

Question:
- Woher kommen Sie?

Answer:
- Ich komme aus …

Examples:
- aus Ungarn
- aus Portugal

---

### Grammar tip

Formal conversation uses:
- Sie
- Ihr

The verb must match:
- Sie heißen
- Sie kommen

---

### Capital letters

German nouns always begin with a capital letter:
- Vorname
- Familienname
- Ungarn
- Portugal

</details>





# Informationen

 ## Ergänzen Sie **er** oder **sie** (Singular oder Plural).

1. Nicole kommt aus Kamerun. [[sie]] wohnt jetzt in Leipzig.  

2. Gabriel wohnt in Berlin. [[Er]] arbeitet schon.  

3. Eivor und Fynn sind aus Schweden. [[Sie]] wohnen in Potsdam.  

4. Sarah und Dana sind neu im Deutschkurs. [[Sie]] lernen Deutsch.  

5. Sarah kommt aus Frankreich. [[Sie]] wohnt jetzt in Deutschland.  

6. Frau Klein ist Deutschlehrerin. [[Sie]] kommt aus Deutschland.  

7. Herr Klein ist Architekt. [[Er]] wohnt in Berlin.  

8. Tina studiert Germanistik. [[Sie]] spricht Englisch, Französisch und Deutsch.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you choose the correct personal pronoun:
- <b>er</b>
- <b>sie</b>

To solve the task:

1️⃣ Identify:
- male person
- female person
- plural (more than one person)

---

### Personal pronouns in German

| Subject | Pronoun |
|---|---|
| masculine singular | er |
| feminine singular | sie |
| plural | sie |

---

### Helpful strategy

#### One male person
Use:
→ <b>er</b>

Examples:
- Gabriel
- Herr Klein

---

#### One female person
Use:
→ <b>sie</b>

Examples:
- Nicole
- Sarah
- Frau Klein
- Tina

---

#### Two or more people
Use:
→ <b>sie</b>

Examples:
- Eivor und Fynn
- Sarah und Dana

Even if the group includes:
- male + female
or
- two females
or
- two males

German plural still uses:
→ sie

---

### Important

At the beginning of a sentence:
- Er
- Sie

begin with a capital letter.

</details>

---

  ## **du und ich – ihr und wir**  
Welche Antwort passt? Ordnen Sie zu.

1. Woher kommst du?  
2. Was studierst du?  
3. Welche Sprachen sprichst du?  
4. Wo wohnst du?  
5. Woher kommt ihr?  
6. Was studiert ihr?  
7. Welche Sprachen sprecht ihr?  
8. Wo wohnt ihr?

a. [[4]]  Ich wohne in Leipzig.


b. [[6]] Wir studieren Medizin. 


c. [[3]] Ich spreche Französisch und Englisch. 


d. [[8]] Wir wohnen in Potsdam. 


e. [[7]] Wir sprechen Schwedisch und Dänisch. 


f. [[2]] Ich studiere Informatik. 


g. [[1]] Ich komme aus Kamerun. 


h. [[5]] Wir kommen aus Schweden.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you match questions with the correct answers.

To solve the task:

1️⃣ Look carefully at the pronouns:
- du
- ihr

2️⃣ Match them with:
- ich
- wir

---

### Important grammar pattern

#### Questions with <b>du</b>
usually answer with:
→ <b>ich</b>

Examples:
- Woher kommst du?
→ Ich komme aus …

- Was studierst du?
→ Ich studiere …

---

#### Questions with <b>ihr</b>
usually answer with:
→ <b>wir</b>

Examples:
- Woher kommt ihr?
→ Wir kommen aus …

- Wo wohnt ihr?
→ Wir wohnen in …

---

### Helpful vocabulary clues

#### Languages
Question:
- Welche Sprachen sprichst du?

Answer:
- Ich spreche Französisch und Englisch.

---

#### Study subjects
Question:
- Was studiert ihr?

Answer:
- Wir studieren Medizin.

---

### Important

At the beginning of sentences:
- Ich
- Wir

begin with a capital letter.

German nouns also begin with capital letters:
- Medizin
- Informatik
- Französisch
- Englisch

</details>


---

 ## GRAMMATIK KOMPAKT  
 ### Verben im Präsens

 ### a Ergänzen Sie die Pronomen und Verbformen.

|        | sein | wohnen | heißen | arbeiten | sprechen |
|------|------|--------|--------|----------|----------|
| ich  | bin  | wohne  |    [[heiße]]    |     [[arbeite]]       | spreche  |

| du   |    [[bist]]    |     [[wohnst]]     |    [[heißt]]      | arbeitest| sprichst |

| er / sie / es | ist | wohnt | heißt | arbeitet |     [[spricht]]       |

| wir  | sind |    [[wohnen]]      |     [[heißen]]     |      [[arbeiten]]      |    [[sprechen]]        |

| ihr  | seid |     [[wohnt]]     | heißt  |     [[arbeitet]]       |     sprecht     |

| sie / Sie |    [[sind]]    |    [[wohnen]]      |     [[heißen]]    | arbeiten |   [[sprechen]]     |

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you complete present tense verb forms (Präsens).

To solve the task:

1️⃣ Identify the pronoun:
- ich
- du
- er/sie/es
- wir
- ihr
- sie/Sie

2️⃣ Choose the correct verb ending.

---

### Regular verb endings

| Pronoun | Ending |
|---|---|
| ich | -e |
| du | -st |
| er/sie/es | -t |
| wir | -en |
| ihr | -t |
| sie/Sie | -en |

Examples:
- wohnen → wohnst
- arbeiten → arbeitet
- sprechen → sprechen

---

### Important irregular verbs

#### sein
This verb is irregular:
- ich bin
- du bist
- wir sind

You must memorize these forms.

---

#### sprechen
This verb changes vowel in:
- du
- er/sie/es

Example:
- sprechen → sprichst
- sprechen → spricht

---

### Helpful strategy

Look carefully at:
- the pronoun
- singular or plural
- regular or irregular verb

This helps you find the correct form.

</details>

---

  ##  Ergänzen Sie die passenden Verbformen.

1. Wer [[ist]] Frau Klein?  

   ○ Sie [[ist]] meine Deutschlehrerin. *(sein)*


2. Woher [[kommt]] Nicole?  

   ○ Sie [[kommt]] aus Kamerun. *(kommen)*


3. Was [[studieren]] Fynn und Eivor?  

   ○ Sie [[studieren]] Medizin. *(studieren)*


4. Wie [[heißt]] du?  

   ○ Ich [[heiße]] Gabriel. *(heißen)*


5. Welche Sprache [[lernst]] du?  

   ○ Ich [[lerne]] Deutsch. *(lernen)*

6. Wo [[wohnt]] ihr?  

   ○ Wir [[wohnen]] in Potsdam. *(wohnen)*


7. Welche Sprachen [[sprichst]] du?  

   ○ Ich [[spreche]] Englisch und Polnisch. *(sprechen)*


8. Welche Sprache [[lernt]] ihr?  

   ○ Wir [[lernen]] Deutsch. *(lernen)*


9. Was [[studiert]] Laura?  

   ○ Laura [[studiert]] Germanistik. *(studieren)*


10. Was [[lernt]] Laura?  

    ○ Laura [[lernt]] Englisch. *(lernen)*

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you complete the correct present tense verb forms.

To solve the task:

1️⃣ Find the subject:
- ich
- du
- sie
- wir
- Laura
- Fynn und Eivor

2️⃣ Conjugate the verb correctly.

---

### Helpful verb endings

| Pronoun | Typical Ending |
|---|---|
| ich | -e |
| du | -st |
| er/sie/es | -t |
| wir | -en |
| ihr | -t |
| sie/Sie | -en |

---

### Important singular and plural clues

#### Singular
- Nicole kommt
- Laura studiert
- du lernst

#### Plural
- wir wohnen
- Fynn und Eivor studieren

---

### Important irregular verbs

#### sein
- ich bin
- du bist
- sie ist

#### sprechen
Changes vowel in:
- du sprichst

---

### Helpful strategy

Before writing the verb:
1️⃣ identify the subject  
2️⃣ check singular or plural  
3️⃣ choose the correct verb ending

</details>


---

  ## 3 Wer ist das?

 ##  Schreiben Sie die Sätze.  Achten Sie auf Groß- und Kleinschreibung.

1. dasistsandrahofer.
2. siekommtausdeutschland.
3. siewohntinmünchenundstudiertmedizin.
4. sandrasprichtdeutsch,französischundenglisch

1) Das ist Sandra Hofer.

2) [[Sie kommt aus Deutschland]]


3) [[Sie wohnt in München und studiert Medizin]]


4) [[Sandra spricht Deutsch, Französisch und Englisch]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In these exercises, you practice:
- sentence building
- present tense verbs
- capital letters in German
- countries and languages

Important:
German nouns and languages begin with a capital letter:
- Deutschland
- Medizin
- Englisch

At the beginning of every sentence, the first word also begins with a capital letter.

</details>




# Ergänzen Sie die passenden Verbformen.

**Verben:**  

>arbeiten · kommen · lernen · sein · sein · sprechen · wohnen

* Das [[ist]] (1) Ana Laura Ramirez.

*  Sie [[kommt]](2) aus Peru.  

* Sie [[wohnt]] (3) in Lima.

*  Ana Laura [[arbeitet]] (4) schon.  

* Sie [[ist]] (5) Architektin.

*  Ana Laura [[spricht]] (6) Spanisch und Englisch.  

* Sie [[lernt]] (7) jetzt Deutsch.



---

  ## Schreiben Sie die Sätze.  
Achten Sie auf Groß- und Kleinschreibung.

1. Austin · sind · und · das · Shannon ·  
[[Das sind Austin und Shannon.]]


2. den · aus · kommen · sie · USA ·  
[[Sie kommen aus den USA.]]


3. neu · sind · Deutschkurs · im · sie ·  

[[Sie sind neu im Deutschkurs.]]

4. Elektrotechnik · Informatik · studieren · und · sie ·  
[[Sie studieren Elektrotechnik und Informatik.]]


---

 

  


  ## WORTBILDUNG  
Ergänzen Sie die Sprachen mit der Endung **-isch**.

1. Ungarn →  [[Ungarisch]]

2. Spanien → [[Spanisch]] 

3. Schweden → [[Schwedisch]] 

4. Dänemark → [[Dänisch]] 

5. Portugal → [[Portugiesisch]] 

6. Frankreich → [[Französisch]] 

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In these exercises, you practice:
- Present tense verbs
- Sentence building
- Capital letters
- Country and language names

To solve the verb exercise:

1️⃣ Find the subject 

2️⃣ Choose the correct verb form 

3️⃣ Check singular or plural

Examples:
- Sie kommt …
- Sie wohnt …
- Sie lernt …

German nouns and languages begin with a capital letter:
- Peru
- Deutsch
- Spanisch
- Elektrotechnik

</details>



# 1 Hallo! Wie geht es dir?

   ##  Welche Wörter passen? Ergänzen Sie.

>**Wörter:**  Auf Wiedersehen · Bis bald · Bis morgen · Guten Morgen · Guten Tag · Hallo · Tschüss

**Begrüßung:** [[Guten Morgen, Guten Tag, Hallo!]]


**Verabschiedung:** [[Auf Wiedersehen, Bis bald.Bis morgen,Tschüss]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you sort German expressions into:
- greetings (Begrüßung)
- farewells (Verabschiedung)

To solve the task:

1️⃣ Think about:
👉 Do people say this at the beginning?
or
👉 at the end of a conversation?

---

### Begrüßung = Greeting

Used when meeting someone.

Examples:
- Guten Morgen
- Guten Tag
- Hallo

---

### Verabschiedung = Saying goodbye

Used when leaving or ending a conversation.

Examples:
- Tschüss
- Bis morgen
- Auf Wiedersehen

---

### Helpful strategy

Ask yourself:

👉 “Do I use this when I arrive?”
→ Begrüßung

👉 “Do I use this when I leave?”
→ Verabschiedung

</details>

---

  ## Ergänzen Sie das Gespräch und hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_009.mp3?raw=true)

>**Sätze:**  Bis morgen. Tschüss! · Es geht so. Ich arbeite viel. · Hallo, Wie geht es dir? · Ja, ich komme zum Kurs.

1. •  [[Hallo, Wie geht es dir?]]
   ○ Mir geht es super. Und dir?

2. • [[Es geht so. Ich arbeite viel.]] 
   ○ Kommst du morgen Abend zum Deutschkurs?

3. • [[ Ja, ich komme zum Kurs.]]
   ○ Schön. Bis morgen!

4. • [[Bis morgen. Tschüss!]]


---

   ## Wie geht es dir? Ordnen Sie zu.

* Es geht mir (sehr) gut. / Mir geht es (sehr) gut.  
* Es geht mir nicht so gut. / Mir geht es nicht so gut.  
* Es geht (so).  
* Es geht mir super. / Mir geht es super.

1. 🙂  [[Es geht mir (sehr) gut. / Mir geht es (sehr) gut.  ]]

2.  🤩  [[Es geht mir super. / Mir geht es super.]]

3. 😐  [[Es geht (so). ]] 

4. ☹️  [[Es geht mir nicht so gut. / Mir geht es nicht so gut. ]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you match emotions with the correct German expressions.

To solve the task:

1️⃣ Look carefully at the emoji:
- happy
- very excited
- neutral
- sad

2️⃣ Match the feeling with the correct sentence.

---

### Helpful meanings

#### 🙂 happy
→ good / fine

Example:
- Mir geht es gut.

---

#### 🤩 very excited
→ super / excellent

Example:
- Mir geht es super.

---

#### 😐 neutral
→ okay / so-so

Example:
- Es geht so.

---

#### ☹️ sad or tired
→ not so good

Example:
- Mir geht es nicht so gut.

---

### Important phrase

German often uses:
👉 „Wie geht es dir?“  
= “How are you?”

Possible answers:
- Mir geht es gut.
- Mir geht es super.
- Es geht so.

</details>

---

  ## 2 AUSSPRACHE   Satzmelodie

   ## Hören Sie eine Frage (Question) oder eine Antwort (.)?  Ergänzen Sie die Satzzeichen.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_010.mp3?raw=true)

1. Wie geht es dir [[Question]] 

2. Mir geht es super[[.]]  

3. Wo wohnst du[[Question]] 

4. Ich wohne in Berlin[[.]] 

5. Wohnst du in Berlin[[Question]] 

6. Sprechen Sie Deutsch[[Question]]  



---

   ##  Wo ist die Satzmelodie besonders? Kreuzen Sie an.

  [[ ]]  W-Frage  
 [[x]] Ja/Nein-Frage  
[[ ]]  Aussage  

---

   ## 3 GRAMMATIK KOMPAKT  
   ## W-Fragen, Ja/Nein-Fragen, Antworten / Aussagen

   ## a. Schreiben Sie W-Fragen und Antworten.

1. • geht · Ihnen · es · wie · ?  
   [[Wie geht es Ihnen?]]

   ○ geht · gut · mir · es ·  
   [[Mir geht es gut.]]

2. • heißen · Sie · wie · ?  
   [[Wie heißen Sie? ]] 

   ○ heiße · Sarah Girard · ich · .  
   [[Ich heiße Sarah Girard.]

3. • im Sprachenzentrum · was · ihr · macht · ?  
   [[Was macht ihr im Sprachenzentrum?]]

   ○ zusammen · Polnisch · lernen · wir · 
   [[Wir lernen zusammen Polnisch.]]





## Schreiben Sie Ja/Nein-Fragen und Antworten.

1. • Sie · Stuttgart · wohnen · in · ?  
   [[Wohnen Sie in Stuttgart?]]

   ○ nein · Tübingen · wohne · in · ich · .  
   [[Nein, ich wohne in Tübingen.]]


2. • Tübingen · Sie · arbeiten · in · ?  
   [[Arbeiten Sie in Tübingen?]] 

   ○ nein · Biologie · studiere · ich · .  
   [[Nein, ich studiere Biologie.]]


3. • ihr · heute Abend · zum Kurs · kommt · ?  
   [[Kommt ihr heute Abend zum Kurs?]]

   ○ ja · wir · kommen ·  
  [[Ja, wir kommen.]]


---

   ## Ergänzen Sie jeweils die informelle und die formelle Frage.

1. • Wie heißt du? / Wie heißen Sie?  
   ○ Ich heiße Igor Smirnow.

2. • [[Studierst du Informatik?]]  [[Studieren Sie Informatik?]]  
   ○ Ja. Ich studiere Informatik.

3. • [[Wo wohnst du?]]  [[Wo wohnen Sie?]]  
   ○ Ich wohne in Hamburg.

4. • [[Woher kommst du?]]  [[Woher kommen Sie?]]   
   ○ Ich komme aus Russland.

5. • [[Wohnst du in Berlin?]]  [[Wohnen Sie in Berlin?]]  
   ○ Nein. Wir wohnen in Potsdam.

6. • [[Kommst du morgen zum Kurs?]]  [[Kommen Sie morgen zum Kurs?]]   
   ○ Ja. Ich komme morgen zum Kurs.
 

---

   ##  Zahlen

   ##  Schreiben Sie als Wort und als Zahl.

1. und · ßig · drei · drei  
    ~~dreiunddreißig~~ ~~57~~


2. sie · fünf · zig · und · ben  
   [[siebenundfünfzig]]  [[57]]


3. zwan · sie · zig · und · ben  
    [[siebenundzwanzig]] [[27]] 


4. zig · und · neun · zwei  
   [[zweiundneunzig]]  [[92]]


5. und · zig · acht · sech  
   [[achtundsechzig]] [[68]]


---

   ##  Was hören Sie? Kreuzen Sie an.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_011.mp3?raw=true)

1. A

   [[ ]]  17
   [[x]]  70
   [[ ]]  77
   

2.  B 

    [[x]]  548
    [[ ]]  584
    [[ ]]  854
   

3.  C

    [[x]]  1015
    [[ ]]  1050
    [[ ]]  1055
   

4.  D

   [[ ]]  1823
    [[x]]  1832
   [[ ]]  1833
   

5.  E

    [[ ]]  68437
    [[x]]  68734
    [[ ]]  86734
   

6.  F

    [[ ]]  27456
    [[ ]]  72456
    [[x]]  72465
   

---

  ## Schreiben Sie Zahlen.

1. sechsundfünfzig ~~56~~

2. dreiundsechzig [[63]] 

3. sechsundachtzig [[86]] 


4. dreihundertvierundsiebzig [[374]] 

5. eintausendsiebenundzwanzig [[1027]] 

6. viertausenddreihundertneunzehn [[4319]]


---

  ## Was hören Sie?  Notieren Sie die Telefonnummern.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_012.mp3?raw=true)

1) ~~082481999~~


2) [[03515482380]]


3) [[03017741228]] 

4) [[01736934876]]


5) [[0158514023]]


6) [[0941351861]] 


---

# Studium international

 ##  Studierende aus Deutschland in der Welt

![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um10.50.57.png?raw=true)

 ### Das ist Zeynep Gül.
Sie kommt aus Stuttgart.  
Sie wohnt jetzt in Shanghai.

» Zeynep, was studierst du?  
Ich studiere Medizininformatik in Stuttgart und jetzt bin ich in Shanghai und lerne Chinesisch.

» Welche Sprachen sprichst du?  
Ich spreche Deutsch, Türkisch und Englisch und ein bisschen Chinesisch.

---

 ### Das sind Piotr Nowak und Stefan Wróbel.
Sie kommen aus Berlin.  
Sie studieren in Kapstadt.

» Piotr und Stefan, was studiert ihr?  
Wir studieren Design.

» Welche Sprachen sprecht ihr?  
Wir sprechen Deutsch, Polnisch und Englisch.  
Wir lernen Afrikaans und Zulu.

---

 ### Das ist Merle Brinkmann.
Sie kommt aus Bremen.  
Sie wohnt in Barcelona.

» Merle, was studierst du?  
Ich arbeite schon. Ich bin Chemikerin.  
Ich arbeite an der Universität Barcelona.

» Welche Sprachen sprichst du?  
Ich spreche Deutsch, Spanisch und Französisch.

---

 ### Das ist Timo Schmidt.
Er kommt aus Tübingen.

Er spricht Deutsch, Portugiesisch und Spanisch.

» Timo, wo wohnst du?  
Ich wohne jetzt in Brasilien, in Manaus.

» Was studierst du?  
Ich arbeite schon. Ich bin Biologe.  
Ich arbeite an der Universität.

---

 ###  Lesen Sie die Porträts noch einmal und ergänzen Sie die Tabelle.

|                    | Zeynep        | Merle        | Piotr + Stefan | Timo   |
|--------------------|---------------|--------------|----------------|--------|
| **Wohnort**            |  [[Shanghai]]     | [[Barcelona]]    | [[Kapstadt]]       | [[Manaus]] |


| **Sprachen**           | [[Deutsch]]       |  [[Deutsch]]     | [[Deutsch]]        | [[Deutsch]] |

|                    | [[Chinesisch]]    | [[Spanisch]]     | [[Englisch]]       | [[Portugiesisch]] |

|                    | [[Türkisch ]]     | [[Französisch]]  | [[Polnisch]]       | [[Spanisch]] |

|                    | [[Englisch]]      |              | [[Afrikaans]]      |        |

|                    |               |              | [[Zulu ]]          |        |


| **Studienfach / Beruf**| [[Medizininformatik]] | [[Chemikerin]] |  [[Design]]        | [[Biologe]] |

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you read short portraits and complete the table with:
- place of residence
- languages
- study subject or profession

To solve the task:

1️⃣ Read each portrait carefully  
2️⃣ Look for important information:
- „wohnt in …“
- „spricht …“
- „studiert …“
- „ist …“

3️⃣ Put the information into the correct table row.

---

### Helpful vocabulary

#### Wohnort
= place of residence

Examples:
- Shanghai
- Barcelona
- Kapstadt
- Manaus

---

#### Sprachen
= languages

Examples:
- Deutsch
- Englisch
- Chinesisch
- Spanisch

---

#### Studienfach / Beruf
= subject or profession

Examples:
- Medizininformatik
- Design
- Biologe
- Chemikerin

---

### Helpful reading strategy

Ask yourself:
👉 Who is the person?  
👉 Where does the person live?  
👉 Which languages does the person speak?  
👉 What does the person study or work as?

This helps you complete the table correctly.

</details>

---



# 1A – Lektionswortschatz

| 1A |
|----|
| Hallo! |
| Guten Tag! |
| das Gespräch, -e |
| das Foto, -s |
| der Kurs, -e |
| der Deutschkurs, -e |
| sein |
| neu |
| hier |
| kommen |
| kommen aus … |
| der Lehrer, - |
| die Lehrerin, -nen |
| der Deutschlehrer, - |
| die Deutschlehrerin, -nen |
| heißen |
| der Name, -n* |
| der Familienname, -n |
| der Vorname, -n |
| Entschuldigung! |
| schreiben |
| der Buchstabe, -n* |
| buchstabieren |
| man |
| Wie schreibt man das? |
| bitte |
| Danke sehr! |
| Vielen Dank! |
| die Anrede, -n |
| formell / informell |
| der / die Studierende, -n |
| der Freund, -e |
| die Freundin, -nen |
| die Familie, -n |

 

| 1B |
|----|
| studieren |
| das Porträt, -s |
| der Professor, -en |
| die Professorin, -nen |
| der / die Fremde, -n |
| die Frage, -n |
| die Antwort, -en |
| die Stadt, -e |
| das Land, -er |
| China |
| Dänemark |
| Deutschland |
| Frankreich |
| Ghana |
| Großbritannien |
| Japan |
| Kanada |
| Kasachstan |
| Österreich |
| Peru |
| Tansania |
| die Niederlande |
| die Schweiz |
| die Türkei |
| die USA |
| der Iran |
| die Chemie (nur Sg.) |
| der Frieden (nur Sg.) |
| die Literatur (nur Sg.) |
| die Medizin (nur Sg.) |
| die Physik (nur Sg.) |
| die Wirtschaft (nur Sg.) |
| die Architektur (nur Sg.) |
| das Interview, -s |
| das Kurzinterview, -s |
| die Information, -en |
| international |
| Brasilien |
| Kamerun |
| Kolumbien |
| Schweden |
| wohnen |
| wohnen in … |
| der Wohnort, -e |
| das Studienfach, -er |
| die Informatik (nur Sg.) |
| die Elektrotechnik (nur Sg.) |
| lernen |
| sprechen (spricht) |
| die Sprache, -n |
| Welche Sprachen sprichst du? |
| Dänisch |
| Deutsch |
| Englisch |
| Französisch |
| Portugiesisch |
| Schwedisch |
| Spanisch |
| ein bisschen |
| arbeiten |
| der Beruf, -e |
| der Architekt, -en |
| die Architektin, -nen |
| der Koch, -e |
| die Köchin, -nen |
| der Musiker, - |
| die Musikerin, -nen |
| der Schauspieler, - |
| die Schauspielerin, -nen |
| schon |

  
| 1C |
|----|
| gehen |
| Wie geht es dir / Ihnen? |
| gut / sehr gut |
| super |
| nicht so gut |
| Es geht so. |
| Es geht mir gut / sehr gut / super / nicht so gut. |
| Mir geht es gut / sehr gut / super / nicht so gut. |
| auch |
| danke |
| viel |
| die Biologie (nur Sg.) |
| die Party, -s |
| schön / sehr schön |
| natürlich |
| morgen |
| Bis morgen! |
| Tschüss! |
| Auf Wiedersehen! |
| Guten Morgen! |
| der Abend, -e |
| die Zahl, -en* |
| das Telefon, -e |
| die Nummer, -n |
| die Telefonnummer, -n* |
| die Vorwahl, -en |
| die E-Mail, -s |
| die Adresse, -n |
| die E-Mail-Adresse, -n |
| wiederholen |


# Lösungen / Answer Key

## Guten Tag! Ich heiße …

 ## Welche Antwort passt? Ordnen Sie zu.

Gespräch A:

* 1 → 3  
* 2 → 2  
* 3 → 1  

Gespräch B:

* 1 → 2  
* 2 → 1  

---

 ## Sortieren und schreiben Sie die Gespräche

 ## Gespräch A
1. Guten Tag, ich heiße Angelika Kessler.  
2. Guten Tag, Frau Kessler. Ich heiße Emma.  
3. Wie ist Ihr Familienname?  
4. Mein Familienname ist Larsson.  
5. Woher kommen Sie, Frau Larsson?  
6. Ich komme aus Stockholm.  

 ## Gespräch B
1. Hallo! Ich heiße Bojan. Wie heißt du?  
2. Hallo Bojan! Ich bin Lea. Woher kommst du?  
3. Ich komme aus Warna. Und du?  
4. Ich komme aus Split.  
 
 ## Welches Gespräch ist
Gespräch A: Formell


Gespräch B: Informell

---

 ## Hören Sie und ergänzen Sie die Namen

1. Jochen Schneider  
2. Valentina Palenz  
3. Christian Büchel  
4. Alexandra Wanner  

---

 ## Hören Sie und schreiben Sie die Namen

1. Paula Koch  
2. Anna Hausmann  
3. Leon Wagner  
4. Michael Schneider  

---

 ## Hören Sie und ergänzen Sie die Vokale

1. Hallo! Ich heiße Lin.  
2. Ich bin neu hier im Deutschkurs.  
3. Ich komme aus China.  
4. Und du, woher kommst du?  

---

# GRAMMATIK KOMPAKT – W-Fragen

 ## Was passt? Ergänzen Sie.

1. heiße  
2. Wie / ist  
3. Wie  
4. Woher / komme  

---

 ## Schreiben Sie sechs Fragen

1. Wie heißt du?  
2. Wie heißen Sie?  
3. Wie ist dein Vorname?  
4. Wie ist Ihr Familienname?  
5. Woher kommst du?  
6. Woher kommen Sie?  

---

 ## Woher kommt …?

2. Alina kommt aus Österreich.  
3. Niklas kommt aus der Schweiz.  
4. Noah kommt aus Frankreich.  
5. Jean kommt aus Luxemburg.  
6. Wout kommt aus Belgien.  
7. Anouk kommt aus den Niederlanden.  
8. Mette kommt aus Dänemark.  
9. Arek kommt aus Polen.  
10. Jaromír kommt aus Tschechien.  
11. Luisa kommt aus Portugal.  
12. Enikö kommt aus Ungarn.  

---

 ## Woher kommen Sie?

1. heiße / heißen  
2. heiße / ist / Familienname  
3. buchstabiert  
4. kommen  
5. aus Ungarn  
6. komme  

---

# Informationen

 ## Ergänzen Sie er oder sie

1. sie  
2. Er  
3. Sie  
4. Sie  
5. Sie  
6. Sie  
7. Er  
8. Sie  

---

 ## du und ich – ihr und wir

* a → 4  
* b → 6  
* c → 3  
* d → 8  
* e → 7  
* f → 2  
* g → 1  
* h → 5  

---

# Verben im Präsens

 ## Tabelle

* ich → heiße / arbeite  
* du → bist / wohnst / heißt  
* er/sie/es → spricht  
* wir → wohnen / heißen / arbeiten / sprechen  
* ihr → wohnt / arbeitet  
* sie/Sie → sind / wohnen / heißen / sprechen  

---

 ## Ergänzen Sie die passenden Verbformen

1. ist / ist  
2. kommt / kommt  
3. studieren / studieren  
4. heißt / heiße  
5. lernst / lerne  
6. wohnt / wohnen  
7. sprichst / spreche  
8. lernt / lernen  
9. studiert / studiert  
10. lernt / lernt  

---

 ## Wer ist das?

1. Das ist Sandra Hofer.  
2. Sie kommt aus Deutschland.  
3. Sie wohnt in München und studiert Medizin.  
4. Sandra spricht Deutsch, Französisch und Englisch.  

---

 ## Ergänzen Sie die passenden Verbformen

1. ist  
2. kommt  
3. wohnt  
4. arbeitet  
5. ist  
6. spricht  
7. lernt  

---

 ## Schreiben Sie die Sätze

1. Das sind Austin und Shannon.  
2. Sie kommen aus den USA.  
3. Sie sind neu im Deutschkurs.  
4. Sie studieren Elektrotechnik und Informatik.  

---

 ## Wortbildung

1. Ungarisch  
2. Spanisch  
3. Schwedisch  
4. Dänisch  
5. Portugiesisch  
6. Französisch  

---

# Hallo! Wie geht es dir?

 ## Begrüßung
Guten Morgen, Guten Tag, Hallo!

 ## Verabschiedung
Auf Wiedersehen, Bis bald, Bis morgen, Tschüss

---

 ## Ergänzen Sie das Gespräch

1. Hallo, wie geht es dir?  
2. Es geht so. Ich arbeite viel.  
3. Ja, ich komme zum Kurs.  
4. Bis morgen. Tschüss!  

---

 ## Wie geht es dir?

1. Es geht mir gut.  
2. Es geht mir super.  
3. Es geht so.  
4. Es geht mir nicht so gut.  

---

 ## Satzmelodie

1. ?  
2. .  
3. ?  
4. .  
5. ?  
6. ?  

Besonders: Ja/Nein-Frage

---

 ## W-Fragen und Antworten

1. Wie geht es Ihnen? → Mir geht es gut.  
2. Wie heißen Sie? → Ich heiße Sarah Girard.  
3. Was macht ihr im Sprachenzentrum? → Wir lernen zusammen Polnisch.  

---

 ## Ja/Nein-Fragen

1. Wohnen Sie in Stuttgart? → Nein, ich wohne in Tübingen.  
2. Arbeiten Sie in Tübingen? → Nein, ich studiere Biologie.  
3. Kommt ihr heute Abend zum Kurs? → Ja, wir kommen.  

---

 ## Informelle und formelle Fragen

2. Studierst du Informatik? / Studieren Sie Informatik?  
3. Wo wohnst du? / Wo wohnen Sie?  
4. Woher kommst du? / Woher kommen Sie?  
5. Wohnst du in Berlin? / Wohnen Sie in Berlin?  
6. Kommst du morgen zum Kurs? / Kommen Sie morgen zum Kurs?  

---

# Zahlen

2. siebenundfünfzig – 57  
3. siebenundzwanzig – 27  
4. zweiundneunzig – 92  
5. achtundsechzig – 68  

---

 ## Was hören Sie?

1. 70  
2. 548  
3. 1015  
4. 1832  
5. 68734  
6. 72465  

---

 ## Schreiben Sie Zahlen

2. 63  
3. 86  
4. 374  
5. 1027  
6. 4319  

---

 ## Telefonnummern

1. 082481999  
2. 03515482380  
3. 03017741228  
4. 01736934876  
5. 0158514023  
6. 0941351861  

---

# Studium international

 ## Tabelle

 ## Wohnort
- Zeynep → Shanghai  
- Merle → Barcelona  
- Piotr + Stefan → Kapstadt  
- Timo → Manaus  

 ## Sprachen
- Zeynep → Deutsch, Chinesisch, Türkisch, Englisch  
- Merle → Deutsch, Spanisch, Französisch  
- Piotr + Stefan → Deutsch, Englisch, Polnisch, Afrikaans, Zulu  
- Timo → Deutsch, Portugiesisch, Spanisch  

 ## Studienfach / Beruf
- Zeynep → Medizininformatik  
- Merle → Chemikerin  
- Piotr + Stefan → Design  
- Timo → Biologe  
