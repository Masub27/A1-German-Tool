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

# Übungsbuchteil

    --{{0}}--
!?[](https://github.com/Masub27/A1-German-Tool/blob/main/Chapter_2/Chapter%202%20work%20Introduction_1080p.mp4?raw=true)

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">

<defs>

<linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
  <stop offset="0%" stop-color="#f7faf3"/>
  <stop offset="100%" stop-color="#ffffff"/>
</linearGradient>

<linearGradient id="green" x1="0" y1="0" x2="1" y2="0">
  <stop offset="0%" stop-color="#93a82b"/>
  <stop offset="100%" stop-color="#bfd157"/>
</linearGradient>

<filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
  <feDropShadow dx="0" dy="10" stdDeviation="18"
                flood-color="#9aac46"
                flood-opacity="0.25"/>
</filter>

<style><![CDATA[

.title{
  font-family:Georgia, serif;
  font-size:88px;
  fill:#7d9129;
  font-weight:700;
}

.subtitle{
  font-family:Georgia, serif;
  font-size:52px;
  fill:#97a9b1;
}

.chapter{
  font-family:Georgia, serif;
  font-size:190px;
  fill:#dbe7bf;
  font-weight:700;
}

.small{
  font-family:Arial,sans-serif;
  font-size:28px;
  fill:#5c6759;
}

.cardTitle{
  font-family:Georgia, serif;
  font-size:34px;
  fill:#7f8e2d;
  font-weight:700;
}

.cardText{
  font-family:Arial,sans-serif;
  font-size:24px;
  fill:#4f584a;
}

.footer{
  font-family:Arial,sans-serif;
  font-size:20px;
  fill:#6e7668;
}

]]></style>

</defs>

<rect width="1600" height="900" fill="url(#bg)"/>

<circle cx="1320" cy="180" r="180" fill="#edf4de"/>
<circle cx="250" cy="770" r="170" fill="#eff5e1"/>
<circle cx="1480" cy="760" r="120" fill="#f3f7ea"/>

<g filter="url(#shadow)">
  <rect x="90" y="90" width="1420" height="720"
        rx="34"
        fill="#ffffff"
        stroke="#dce6cb"
        stroke-width="2"/>
</g>

<!-- CHAPTER TAG -->
<rect x="120" y="120" width="250" height="60"
      rx="18"
      fill="url(#green)"/>

<text x="245" y="158"
      text-anchor="middle"
      style="font-family:Arial,sans-serif;
             font-size:24px;
             font-weight:700;
             fill:white;">
KAPITEL
</text>

<!-- BIG NUMBER -->
<text x="140" y="330" class="chapter">2</text>

<!-- TITLE -->
<text x="360" y="310" class="title">
Übungsbuchteil
</text>

<text x="360" y="390" class="subtitle">
Studium und Freizeit
</text>

<text x="360" y="455" class="small">
Freizeitaktivitäten • Universität • Hobbys • Kommunikation
</text>

<!-- LEFT CARD -->
<rect x="150" y="545" width="410" height="170"
      rx="24"
      fill="#f8fbf3"
      stroke="#dfe8cb"/>

<text x="185" y="595" class="cardTitle">
📘 Wortfelder
</text>

<text x="185" y="640" class="cardText">
• Freizeitaktivitäten
</text>

<text x="185" y="675" class="cardText">
• Sport und Hobbys
</text>

<!-- CENTER CARD -->
<rect x="610" y="545" width="430" height="170"
      rx="24"
      fill="#f8fbf3"
      stroke="#dfe8cb"/>

<text x="645" y="595" class="cardTitle">
💬 Kommunikation
</text>

<text x="645" y="640" class="cardText">
• über Freizeit sprechen
</text>

<text x="645" y="675" class="cardText">
• Vorlieben ausdrücken
</text>

<!-- RIGHT CARD -->
<rect x="1090" y="545" width="320" height="170"
      rx="24"
      fill="#f8fbf3"
      stroke="#dfe8cb"/>

<text x="1125" y="595" class="cardTitle">
✏️ Grammatik
</text>

<text x="1125" y="640" class="cardText">
• Artikel
</text>

<text x="1125" y="675" class="cardText">
• Negation
</text>

<!-- FOOTER -->
<line x1="140" y1="770"
      x2="1460" y2="770"
      stroke="#dbe4c5"
      stroke-width="2"/>

<text x="140" y="808" class="footer">
Deutsch A1.1 • Kapitel 2 • Übungsbuchteil
</text>

<text x="1460" y="808"
      text-anchor="end"
      class="footer">
Studium • Freizeit • Sprache
</text>

</svg>



# 🤖 Chapter 2 Smart Help Bot

<section style="max-width:1100px;margin:auto;border:1px solid #dbe7ff;border-radius:20px;padding:18px;background:linear-gradient(135deg,#f8fbff,#eef4ff);box-shadow:0 8px 24px rgba(11,42,102,0.08);font-family:Arial,sans-serif">

  <div style="display:flex;align-items:center;gap:12px;margin-bottom:14px">
    <div style="width:52px;height:52px;border-radius:50%;background:linear-gradient(135deg,#0b2a66,#3a7bd5);display:flex;align-items:center;justify-content:center;color:white;font-size:24px">
      🤖
    </div>
    <div>
      <h2 style="margin:0;color:#0b2a66">Chapter 2 Smart Help Bot</h2>
      <div style="color:#4b5b7a;font-size:15px">Ask about university vocabulary, grammar, hobbies, messages, articles, pronouns, and negation.</div>
    </div>
  </div>

  <div id="smartbot-box"
       style="min-height:260px;max-height:420px;overflow:auto;white-space:pre-wrap;background:white;border:1px solid #dfe8f8;border-radius:16px;padding:14px;line-height:1.6;color:#1f2d3d">
Hello! I am your Chapter 2 Smart Help Bot.

You can:
• Type your own question
• Click a quick topic button
• Ask about grammar, vocabulary, university life, hobbies, mailbox messages, or chapter sections

Try one of these:
- What can I learn in this chapter?
- What is a Buddy?
- What is the difference between nicht and kein?
- What are the articles der, die, das?
- What does Erstsemester mean?
  </div>

  <div style="margin-top:14px;display:flex;gap:8px;flex-wrap:wrap">
    <button class="quick-btn" data-q="What can I learn in this chapter?">📚 Chapter overview</button>
    <button class="quick-btn" data-q="What is a Buddy?">🧑 Buddy</button>
    <button class="quick-btn" data-q="What is the difference between nicht and kein?">🚫 nicht / kein</button>
    <button class="quick-btn" data-q="What are the articles der die das?">📘 Articles</button>
    <button class="quick-btn" data-q="What are the personal pronouns in this chapter?">👤 Pronouns</button>
    <button class="quick-btn" data-q="What vocabulary do I learn about university?">🏫 University vocabulary</button>
    <button class="quick-btn" data-q="What hobbies are in this chapter?">🎸 Hobbies</button>
    <button class="quick-btn" data-q="What is Anmeldung?">📝 Anmeldung</button>
  </div>

  <div style="margin-top:14px;display:flex;gap:10px;flex-wrap:wrap">
    <input id="smartbot-input" type="text" placeholder="Type your question here..."
           style="flex:1;min-width:260px;padding:12px 14px;border:1px solid #cfdcf2;border-radius:14px;font-size:15px;outline:none" />
    <button id="smartbot-ask" style="padding:12px 18px;border:none;border-radius:14px;background:#0b2a66;color:white;cursor:pointer;font-weight:bold">
      Ask
    </button>
    <button id="smartbot-clear" style="padding:12px 18px;border:1px solid #cfdcf2;border-radius:14px;background:white;color:#0b2a66;cursor:pointer;font-weight:bold">
      Clear
    </button>
  </div>

  <div style="margin-top:16px;padding:12px 14px;border-radius:14px;background:#ffffff;border:1px dashed #cfdcf2;color:#51617f;font-size:14px">
    <b>Tip:</b> Ask short questions like:
    “What does Universität mean?”
    “How do I use kein?”
    “What is a mailbox message?”
    “Where can I find hobbies in this chapter?”
  </div>
</section>

<style>
.quick-btn{
  padding:10px 14px;
  border-radius:14px;
  border:1px solid #cfdcf2;
  background:white;
  color:#0b2a66;
  cursor:pointer;
  font-weight:600;
}
.quick-btn:hover{
  background:#eef4ff;
}
</style>

<script>
(() => {
  const box = document.getElementById("smartbot-box");
  const input = document.getElementById("smartbot-input");
  const askBtn = document.getElementById("smartbot-ask");
  const clearBtn = document.getElementById("smartbot-clear");
  const quickBtns = document.querySelectorAll(".quick-btn");

  const knowledge = [

    {
      keys: ["what can i learn in this chapter", "chapter overview", "what do i learn"],
      answer: "In this chapter, you learn university vocabulary, important nouns such as Universität, Studium, Studentin, Job and Professor, grammar with der, die, das, ein, eine, plural forms, personal pronouns, negation with nicht and kein, hobbies and courses, mailbox messages, and short university-related communication."
    },

    {
      keys: ["what is a buddy", "buddy"],
      answer: "A Buddy is a student who already studies at the university and helps new students. In this chapter, a Buddy knows the university, gives tips, shows the university, and accompanies first-semester students."
    },

    {
      keys: ["erstsemester", "what does erstsemester mean"],
      answer: "Erstsemester means a first-semester student, someone who is new at the university."
    },

    {
      keys: ["universität", "uni", "what does universität mean"],
      answer: "Universität means university. Uni is the short form of Universität."
    },

    {
      keys: ["studium", "what does studium mean"],
      answer: "Studium means studies or university study program."
    },

    {
      keys: ["studentin", "student", "what does studentin mean"],
      answer: "Student means male student. Studentin means female student."
    },

    {
      keys: ["professor", "professorin"],
      answer: "Professor is masculine. Professorin is feminine. The plural forms are Professoren and Professorinnen."
    },

    {
      keys: ["job", "what does job mean"],
      answer: "Job means job. In this chapter, Daniel says the job as Buddy is super."
    },

    {
      keys: ["what vocabulary do i learn about university", "university vocabulary", "wortschatz"],
      answer: "You learn words such as der Buddy, der Erstsemester, die Universität, das Studium, der Student, die Studentin, der Professor, das Team, der Tipp, die Frage, die Sprache, das Programm, die Mitarbeiterin, and many more."
    },

    {
      keys: ["what verbs do i learn", "verbs", "verben"],
      answer: "Important verbs in this chapter include arbeiten, studieren, begleiten, zeigen, geben, üben, organisieren, kennen, machen, haben, finden, treffen, lesen, hören, tanzen, schwimmen, kaufen, brauchen, fragen, antworten, surfen, scannen, and mailen."
    },

    {
      keys: ["what does begleiten mean", "begleiten"],
      answer: "begleiten means to accompany. A Buddy begleitet Erstsemester."
    },

    {
      keys: ["what does zeigen mean", "zeigen"],
      answer: "zeigen means to show. Daniel zeigt die Uni."
    },

    {
      keys: ["what does geben mean", "tipps geben", "geben"],
      answer: "geben means to give. In this chapter, a Buddy gives tips: Tipps geben."
    },

    {
      keys: ["what does üben mean", "üben"],
      answer: "üben means to practise. Daniel übt Russisch with Katja."
    },

    {
      keys: ["what does finden mean", "finden"],
      answer: "finden means to find or think something is good or interesting. Example: Er findet den Job super."
    },

    {
      keys: ["what are the articles der die das", "articles", "der die das"],
      answer: "German nouns have articles: der for masculine, die for feminine, and das for neuter. Plural nouns usually take die."
    },

    {
      keys: ["what is the difference between ein and eine", "ein eine"],
      answer: "ein is the indefinite article for masculine and neuter nouns in the nominative, and eine is for feminine nouns. Example: ein Buddy, ein Studium, eine Studentin."
    },

    {
      keys: ["plural", "plural forms", "plural forms in this chapter"],
      answer: "This chapter practises plural forms such as Studentin → Studentinnen, Professorin → Professorinnen, Universität → Universitäten, Sprache → Sprachen, Team → Teams, Tipp → Tipps."
    },

    {
      keys: ["what are the personal pronouns in this chapter", "personal pronouns", "pronouns"],
      answer: "Important personal pronouns are er, sie, es, and Sie. In the chapter: Der Stift? Ja, er schreibt gut. Das Buch? Es ist interessant. Die Laptops? Sie sind neu. The teacher? Sie kommt aus Rostock."
    },

    {
      keys: ["what is the difference between nicht and kein", "nicht kein", "kein", "keine", "nicht"],
      answer: "nicht negates verbs, adjectives, places, or complete statements. kein and keine negate nouns. Example: Ich studiere nicht in Wolfsburg. Das ist kein Laptop. Das sind keine Fußbälle."
    },

    {
      keys: ["how do i use nicht", "use nicht"],
      answer: "Use nicht with verbs, adjectives, and places. Example: Ich spreche nicht gut Deutsch. Der Kurs ist nicht in Köln. Düsseldorf ist nicht schön. Deutsch ist nicht einfach."
    },

    {
      keys: ["how do i use kein", "use kein"],
      answer: "Use kein or keine before nouns. Example: kein Englischbuch, keine Geige, kein Laptop, keine Probleme."
    },

    {
      keys: ["what hobbies are in this chapter", "hobbies", "hobby"],
      answer: "Hobbies and leisure activities in this chapter include Schwimmen, Gitarre spielen, Schach spielen, Filme schauen, Musik hören, Lesen, Tanzen, Surfen, Yoga, Volleyball, Basketball, and Kaffee trinken."
    },

    {
      keys: ["what does hobby mean", "hobby"],
      answer: "Hobby means hobby. Example: Mein Hobby ist Schwimmen."
    },

    {
      keys: ["what does anmeldung mean", "anmeldung"],
      answer: "Anmeldung means registration. In the chapter, Jonas asks if the registration is online."
    },

    {
      keys: ["what does surfboard mean", "surfboard"],
      answer: "Surfboard means Surfboard. In the mailbox message, Hannah says she has three Surfboards."
    },

    {
      keys: ["what does tasche mean", "tasche"],
      answer: "Tasche means bag."
    },

    {
      keys: ["what does gitarre mean", "gitarre"],
      answer: "Gitarre means guitar."
    },

    {
      keys: ["what does kurs mean", "kurs", "deutschkurs"],
      answer: "Kurs means course. Deutschkurs means German course."
    },

    {
      keys: ["what is a mailbox message", "mailbox", "mailbox messages"],
      answer: "Mailbox messages are short spoken messages left on the phone. In this chapter, students listen to short messages about hobbies, courses, surfboards, registration, and questions."
    },

    {
      keys: ["what does online mean", "online"],
      answer: "online means online. In the chapter, students ask: Ist die Anmeldung online?"
    },

    {
      keys: ["what does gratis mean", "gratis"],
      answer: "gratis means free."
    },

    {
      keys: ["what does formular mean", "formular"],
      answer: "Formular means form."
    },

    {
      keys: ["what does anhang mean", "anhang"],
      answer: "Anhang means attachment."
    },

    {
      keys: ["what does unterschrift mean", "unterschrift"],
      answer: "Unterschrift means signature."
    },

    {
      keys: ["what does buddy team mean", "team"],
      answer: "A Buddy team is a team that gives tips and organizes activities for new students."
    },

    {
      keys: ["what does mit freundlichen grüßen mean", "mit freundlichen grüßen"],
      answer: "Mit freundlichen Grüßen is a formal way to end an email. It means Kind regards."
    },

    {
      keys: ["what does viele grüße mean", "viele grüße"],
      answer: "Viele Grüße is a friendly way to end a message. It means Best wishes or Greetings."
    },

    {
      keys: ["where can i find university vocabulary in this chapter", "where can i find vocabulary"],
      answer: "You can find university vocabulary at the beginning of the chapter in the section 'An der Uni' and also in the vocabulary list at the end under 'Studium und Freizeit'."
    },

    {
      keys: ["where can i find grammar in this chapter", "where can i find articles", "where can i find negation"],
      answer: "You can find grammar in the sections 'Grammatik Kompakt'. There you practise articles, plural forms, pronouns, and negation with nicht and kein."
    },

    {
      keys: ["where can i find hobbies in this chapter", "where can i find hobby vocabulary"],
      answer: "You can find hobbies in the section 'Mein Hobby ist …' and also in the final vocabulary list 'Studium und Freizeit'."
    },

    {
      keys: ["where can i find pronunciation in this chapter", "where can i find aussprache", "word stress"],
      answer: "You can find pronunciation in the section 'Aussprache – Wortakzent'. There you practise stress in words like Sprachkurs, Bücher, Musik, Gitarre, Professorin and Freizeitaktivität."
    },

    {
      keys: ["where can i find listening in this chapter", "where can i find hören", "listening tasks"],
      answer: "Listening appears in several parts of the chapter, especially with articles, pronouns, word stress, and mailbox messages."
    },

    {
      keys: ["what is sakura's story", "sakura"],
      answer: "Sakura is new in Germany. She speaks Japanese and English, but not good German. She first has a course in Düsseldorf, not Köln. Later she meets Stefan, does a language tandem, studies art in Köln, and has no problems anymore."
    },

    {
      keys: ["what is jonas asking", "jonas"],
      answer: "Jonas says his hobby is swimming and he is looking for a course. He asks if the swimming course is free for one week and if the registration is online."
    },

    {
      keys: ["what is daniel doing", "daniel"],
      answer: "Daniel works as a Buddy. He already studies at the university, accompanies first-semester students, shows the university, gives tips, and practises Russian with Katja."
    },

    {
      keys: ["who is katja", "katja"],
      answer: "Katja is a first-semester student. She comes from Russia. Daniel practises Russian with her."
    },

    {
      keys: ["what is greifswald", "greifswald"],
      answer: "Greifswald is the university city mentioned in the chapter. In the message to Mischa, someone studies physics in Greifswald."
    },

    {
      keys: ["what message is written to mischa", "mischa"],
      answer: "The text message to Mischa says that the student is studying physics in Greifswald, the study program is interesting but not easy, the university is old and beautiful, and there are already international friends."
    },

    {
      keys: ["what is accusative in this chapter", "akkusativ"],
      answer: "The chapter introduces article forms in nominative and accusative with examples like: Der Student trifft den Professor und die Professorin. The teacher sucht das Wörterbuch und die Stifte."
    },

    {
      keys: ["what nouns are in mein hobby ist", "mein hobby ist"],
      answer: "In 'Mein Hobby ist …' you work with nouns such as der Laptop, die Informationen, die Tasche, das Hobby, die Surfboards, die Gitarre, die Kurse, and die Anmeldung."
    },

    {
      keys: ["give me an example email", "example email", "short email"],
      answer: "Example: Hallo, ich heiße Ali. Ich suche einen Deutschkurs. Ist die Anmeldung online? Vielen Dank. Viele Grüße, Ali."
    },

    {
      keys: ["give me an example university introduction", "example introduction", "introduce myself chapter 2"],
      answer: "Example: Hallo! Ich heiße Ali. Ich studiere Informatik an der Uni. Mein Hobby ist Musik. Ich lerne Deutsch und suche einen Sprachkurs."
    },

    {
      keys: ["what can i say about my hobby", "talk about hobby"],
      answer: "You can say: Mein Hobby ist Schwimmen. / Ich spiele Gitarre. / Ich höre Musik. / Ich lese Bücher. / Ich schaue Filme."
    },

    {
      keys: ["how do i say i do not like", "i do not like", "nicht gern"],
      answer: "Use nicht gern. Example: Ich lese nicht gern. / Ich spiele nicht gern Schach."
    },

    {
      keys: ["how do i say i need", "brauchen"],
      answer: "Use brauchen. Example: Ich brauche eine Tasche. / Die Studenten brauchen Laptops."
    },

    {
      keys: ["how do i say i am looking for", "suche", "looking for"],
      answer: "Use suchen. Example: Ich suche einen Kurs. / Ich suche ein Surfboard."
    },

    {
      keys: ["what is the difference between student and studentin", "student studentin"],
      answer: "Student is masculine. Studentin is feminine. Their plural forms are Studenten and Studentinnen."
    },

    {
      keys: ["what can i ask in a course email", "course email questions"],
      answer: "You can ask: Ist der Kurs online? Ist die Anmeldung online? Ist der Kurs gratis? Wann beginnt der Kurs?"
    },

    {
      keys: ["what does sprachkurs mean", "sprachkurs"],
      answer: "Sprachkurs means language course."
    },

    {
      keys: ["what does sprachtandem mean", "sprachtandem"],
      answer: "Sprachtandem means a language exchange where two people practise languages together."
    },

    {
      keys: ["what does semesterbeginn mean", "semesterbeginn"],
      answer: "Semesterbeginn means the beginning of the semester."
    },

    {
      keys: ["what sports are in this chapter", "sport"],
      answer: "Sports and activities in this chapter include Schwimmen, Schach, Badminton, Volleyball, Basketball, Beachvolleyball, Yoga, and Surfen."
    },

    {
      keys: ["what instruments are in this chapter", "instruments", "guitar", "keyboard", "bass"],
      answer: "Instruments in this chapter include Gitarre, Keyboard, and Bass."
    },

    {
      keys: ["what can i say about university life", "university life"],
      answer: "You can say: Ich studiere an der Uni. / Die Uni ist sehr schön. / Ich habe schon Freunde hier. / Das Studium ist interessant, aber nicht einfach."
    }
  ];

  function appendMessage(sender, text) {
    box.textContent += "\n\n" + sender + ": " + text;
    box.scrollTop = box.scrollHeight;
  }

  function normalize(text) {
    return text.toLowerCase().trim();
  }

  function findAnswer(question) {
    const q = normalize(question);

    for (const item of knowledge) {
      for (const key of item.keys) {
        if (q.includes(key.toLowerCase())) {
          return item.answer;
        }
      }
    }

    return "I am not sure about that exact question yet. Please ask about university vocabulary, Buddy, articles, plural, pronouns, hobbies, mailbox messages, negation with nicht and kein, or where to find these topics in the chapter.";
  }

  function askQuestion(q) {
    if (!q || !q.trim()) return;
    appendMessage("Student", q.trim());
    appendMessage("Bot", findAnswer(q));
    input.value = "";
  }

  askBtn.addEventListener("click", () => askQuestion(input.value));

  input.addEventListener("keydown", (e) => {
    e.stopPropagation();
    if (e.key === "Enter") {
      e.preventDefault();
      askQuestion(input.value);
    }
  });

  quickBtns.forEach(btn => {
    btn.addEventListener("click", () => {
      askQuestion(btn.dataset.q);
    });
  });

  clearBtn.addEventListener("click", () => {
    box.textContent = `Hello! I am your Chapter 2 Smart Help Bot.

You can:
• Type your own question
• Click a quick topic button
• Ask about grammar, university life, hobbies, mailbox messages, or chapter sections

Try one of these:
- What can I learn in this chapter?
- What is a Buddy?
- What is the difference between nicht and kein?
- What are the articles der, die, das?
- What does Erstsemester mean?`;
    input.value = "";
  });
})();
</script>

##  An der Uni

 ##  Wie heißen die Nomen? Schreiben Sie.

1. TTREIÄSUINV  

  die  [[Universität]] 

2. UDMUITS  

   das [[Studium]] 

3. DUISTTNEN  

   die [[Studentin]] 

4. BJO  

   der [[Job]] 

5. POFROSSER 

   der [[Professor]] 

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must rebuild German nouns from mixed letters.

To solve the task:

1️⃣ Read all letters carefully  
2️⃣ Look for familiar German university words  
3️⃣ Think about:
- Study
- University
- Jobs
- Students
- Professors

Pay attention to:
- Capital letters → German nouns always begin with a capital letter
- articles:
  - der
  - die
  - das

These articles help you identify the correct noun.

Example:
- “die” often matches feminine nouns like:
  → die Studentin  
  → die Universität

Try to arrange the letters slowly until the word becomes meaningful.

</details>


---

 ##  Ergänzen Sie.

**Verben:** 

>arbeitet · begleitet · gibt · haben · ist · studiert · übt · zeigt

1. Daniel [[arbeitet]]  (1) als Buddy.

2.  Ein Buddy [[studiert]] (2) schon und kennt die Uni.  

3. Daniel [[begleitet]]  (3) als Buddy Erstsemester.

4.  Warum? Erstsemester [[haben]]  (4) Fragen.  

5. Und Daniel [[zeigt]]  (5) die Uni und [[gibt]]  (6) Tipps.  

6. Er findet, der Job als Buddy ist super. 
7. Katja [[ist]]  (7) Erstsemester und kommt aus Russland.  

8. Daniel lernt Russisch und [[übt]]  (8) die Sprache mit Katja.


<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must choose the correct verb from the list and complete the sentences.

To solve the task:

* 1️⃣ Read the sentence carefully  
* 2️⃣ Think about the meaning  
* 3️⃣ Choose the verb that logically fits the situation

The topic is:
👉 university life  
👉 buddies  
👉 first-semester students

---

### Helpful vocabulary meanings

- <b>arbeitet</b> = works  
- <b>studiert</b> = studies at university  
- <b>begleitet</b> = accompanies / helps someone  
- <b>haben</b> = have  
- <b>zeigt</b> = shows  
- <b>gibt</b> = gives  
- <b>ist</b> = is  
- <b>übt</b> = practices

---

### Grammar strategy

Look at the subject first:

- Daniel → singular verb
- Erstsemester → plural verb

Example:
- Erstsemester <b>haben</b> Fragen.
  → plural subject = plural verb

---

### Meaning strategy

Ask yourself:
- Is the person working?
- Studying?
- Helping?
- Showing something?
- Giving tips?
- Practicing a language?

Choose the verb that best matches the sentence meaning.

</details>

---

 ##  Was passt? Kreuzen Sie an.  Manchmal passen zwei Antworten.

1. als Buddy 
 
   [[ ]] finden 
   [[x]]arbeiten 
   [[ ]]heißen

2. die Uni  

   [[ ]]studieren 
   [[x]]zeigen 
   [[x]] kennen

3. Erstsemester 

   [[x]] begleiten 
   [[x]]sein 
   [[ ]]machen

4. Fragen 

   [[ ]] geben 
   [[ ]] spielen 
   [[x]]haben

5. Tipps 

   [[x]]geben 
   [[ ]]sprechen 
   [[ ]]organisieren

6. eine Sprache 

   [[x]] lernen 
   [[ ]]fragen 
   [[x]]üben


<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you match verbs with the correct noun expressions.

To solve the task:

1️⃣ Read the noun carefully 

2️⃣ Think:
👉 Which verb is normally used with this word in German?

This is called a:
<b>verb + noun combination</b>

---

### Important strategy

Some combinations are fixed expressions in German.

Examples:
- als Buddy <b>arbeiten</b>
- die Uni <b>zeigen</b>
- Fragen <b>haben</b>
- Tipps <b>geben</b>
- eine Sprache <b>lernen</b>

---

### Pay attention to capital letters

German nouns always begin with a capital letter:

- Buddy
- Uni
- Erstsemester
- Fragen
- Tipps
- Sprache

Verbs normally begin with a small letter:

- arbeiten
- zeigen
- kennen
- lernen

This helps you identify:
- Nouns
- Verbs
- Sentence structure

---

### Important

Sometimes:
✅ More than one answer is correct.

Read every option carefully before choosing.

</details>

---

 ## Wer sind die Personen? Ergänzen Sie.

>**Wörter:**  Buddy · Mitarbeiterin · Professorinnen · Student · Team

1. Das ist ein [[Student]].  

   Er studiert Musik und arbeitet als Buddy.

2. Das sind [[Professorinnen]].  

   Sie kommen aus Bonn und kennen die Uni Greifswald nicht.

3. Das ist ein [[Buddy]].  

   Er begleitet Erstsemester und zeigt die Uni.

4. Das ist ein Buddy-[[Team]].  

   Es gibt Tipps und organisiert Partys.

5. Das ist eine [[Mitarbeiterin]]vom Unijournal.  

   Sie ist neu und hat viele Fragen.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must choose the correct noun for each description.

To solve the task:

1️⃣ Read the sentence carefully  

2️⃣ Look for clues about:
- Profession
- University role
- Gender
- Singular or plural

---

### Important grammar clues

#### Articles help you a lot:

- <b>ein</b> → usually masculine singular  
- <b>eine</b> → feminine singular  
- <b>das sind</b> → plural

Examples:
- ein Student
- eine Mitarbeiterin
- das sind Professorinnen

---

### Meaning clues

Think about what the person does:

- Studies music → Student
- Helps first-semester students → Buddy
- Organizes together → Team
- Works for a journal → Mitarbeiterin
- Teaches at university → Professorinnen

---

### Capital letters

All German nouns begin with a capital letter:

- Student
- Buddy
- Team
- Mitarbeiterin
- Professorinnen

This helps you identify the correct answer.

</details>

---

## GRAMMATIK KOMPAKT  
 ## Bestimmter, unbestimmter und Negativartikel im Nominativ

 ##  Was passt wo? Schreiben Sie mit dem bestimmten Artikel.

**Wörter:** 

>Film · Job · Sprache · Studenten · Studium · Team · Tipps · Universität

1. Maskulinum (der):  
der [[ Job]]


2. Neutrum (das):  
das [[Studium]]

3. das [[Team]] 


4. Femininum (die):  
die [[Sprache]]

5. die [[Universität]]


6. Plural (die):  
die [[Studenten]]

7. die [[Tipps]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must match nouns with the correct definite article:

- <b>der</b> → masculine  
- <b>das</b> → neuter  
- <b>die</b> → feminine or plural

To solve the task:

1️⃣ Look at the noun carefully  
2️⃣ Identify:
- Singular or plural
- Masculine, feminine, or neuter gender

---

### Helpful grammar strategy

#### Masculine nouns
usually use:
→ <b>der</b>

Example:
- der Job

---

#### Neuter nouns
usually use:
→ <b>das</b>

Examples:
- das Studium
- das Team

---

#### Feminine nouns
usually use:
→ <b>die</b>

Examples:
- die Sprache
- die Universität

---

#### Plural nouns
always use:
→ <b>die</b>

Examples:
- die Studenten
- die Tipps

---

### Important

German nouns always begin with a capital letter:
- Job
- Sprache
- Universität

Articles are written in small letters:
- der
- das
- die

</details>


---

 ##  Ergänzen Sie Singular oder Plural.

1. die Studentin → die [[Studentinnen]] 

2. der [[Professor]]→ die Professoren  

3. die Professorin → die [[Professorinnen]] 

4. das [[Team]]→ die Teams  

5. die Universität → die [[Universitäten]] 

6. der [[Computer]] → die Computer  

7. die Sprache → die [[Sprachen]] 

8. das [[Programm]]→ die Programme  

9. der Tipp → die [[Tipps]] 

10. die [[Frage]] → die Fragen

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you change nouns from:
- singular → plural
or
- plural → singular

To solve the task:

1️⃣ Look carefully at the article:
- der
- die
- das

2️⃣ Check if the noun is:
- One person/object → singular
- More than one → plural

---

### Important plural patterns in German

German plural forms change in different ways.

#### Some nouns add:
- <b>-en</b>
Examples:
- Studentin → Studentinnen
- Professorin → Professorinnen

---

#### Some nouns add:
- <b>-e</b>
Examples:
- Programm → Programme

---

#### Some nouns add:
- <b>-s</b>
Examples:
- Tipp → Tipps
- Team → Teams

---

#### Some nouns change vowels:
Examples:
- Universität → Universitäten
- Sprache → Sprachen

---

### Important grammar clue

Plural nouns usually use:
→ <b>die</b>

Examples:
- die Studentinnen
- die Fragen
- die Computer

---

### Capital letters

German nouns always begin with a capital letter:
- Professor
- Computer
- Programm
- Frage

</details>

---

 ##  Was hören Sie? Ergänzen Sie die unbestimmten Artikel.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_013.mp3?raw=true)

1. das Studium → [[ein]] Studium  

2. die Tipps → [[solution]] Tipps  

3. die Frage → [[eine]]Frage  

4. der Buddy → [[ein]] Buddy  

5. die Erstsemester → [[solution]] Erstsemester  

6. die Studentin → [[eine]]Studentin

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening exercise, you must choose the correct indefinite article.

German indefinite articles are:

- <b>ein</b> → masculine or neuter singular
- <b>eine</b> → feminine singular

Plural nouns normally have:
→ no indefinite article

---

### Step 1️⃣ Identify the noun gender

Look at the definite article:

- der → usually takes <b>ein</b>
- das → usually takes <b>ein</b>
- die → can be:
  - feminine singular
  - plural

---

### Step 2️⃣ Check singular or plural

Examples:

#### Singular
- das Studium → ein Studium
- der Buddy → ein Buddy
- die Studentin → eine Studentin

---

#### Plural
- die Tipps
- die Erstsemester

Plural nouns do not use:
- ein
- eine

So the answer is:
→ no article

That is why the placeholder uses:
→ [[solution]]

---

### Helpful trick

Before answering, ask:

👉 Is it singular or plural? 

👉 Is the noun masculine, feminine, or neuter?

This helps you choose:
- ein
- eine
- or no article

</details>




#  Das ist kein Englischbuch, das ist ein Deutschbuch!

 ### Was ist das? Ergänzen Sie die Sätze wie im Beispiel.

 ![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um11.17.22.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um11.17.26.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um11.17.31.png?raw=true)
![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um11.17.34.png?raw=true)
1.   
Ich glaube, das ist ein Englischbuch.  
Nein, das ist kein Englischbuch, das ist ein Deutschbuch.

2.   
Ich denke, das ist eine Geige.  
Nein, das ist [[keine]] Geige, das ist [[eine Gitarre]].


3.   
Ich glaube, das sind Fußbälle.  
Nein, das sind [[keine]]Fußbälle, das sind [[Basketbälle]].


4.   
Ich denke, das ist ein Laptop.  
Nein, das ist [[kein]] Laptop, das ist [[ein Computer]].

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you correct false guesses using:

- <b>kein / keine</b> for negation
- and the correct noun with the correct article

You follow this pattern:

👉 “Das ist kein …, das ist ein …”

---

### Step 1️⃣ Identify the noun gender

Use:
- <b>kein</b> → masculine or neuter nouns
- <b>keine</b> → feminine nouns or plural nouns

Examples:
- kein Laptop
- keine Geige
- keine Fußbälle

---

### Step 2️⃣ Look at the real object in the picture

The first sentence gives a wrong guess.

You must:
1️⃣ Negate the wrong noun 

2️⃣ Write the correct noun

Example:
- Not a violin → a guitar
- Not footballs → basketballs

---

### Step 3️⃣ Check singular or plural

Examples:

#### Singular feminine
- die Geige
→ keine Geige

#### Plural
- die Fußbälle
→ keine Fußbälle

#### Singular masculine/neuter
- der Laptop
→ kein Laptop

---

### Important grammar rule

- <b>kein / keine</b> negates nouns
- German nouns always start with a capital letter

</details>

---



 ##  Im Sprachkurs

 ##  Ergänzen Sie die Personalpronomen und hören Sie zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_014.mp3?raw=true)

1. Der Stift? Ja, [[er]] schreibt sehr gut.  

2. Das ist ein Buch. [[Es]] ist sehr interessant.  

3. Hier sind Laptops. [[Sie]] sind neu!  

4. Das ist mein Kollege. [[Er]] ist sehr nett.  

5. Und da ist die Lehrerin. [[Sie]] kommt aus Rostock.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you replace nouns with the correct personal pronouns.

To solve the task:

1️⃣ Look at the noun carefully  
2️⃣ Identify:
- Masculine
- Feminine
- Neuter
- Plural

Then choose the correct pronoun.

---

### German personal pronouns

| Noun Type | Pronoun |
|---|---|
| der (masculine) | er |
| die (feminine) | sie |
| das (neuter) | es |
| plural | sie |

---

### Examples from the exercise

#### der Stift
→ masculine
→ <b>er</b>

#### das Buch
→ neuter
→ <b>es</b>

#### die Laptops
→ plural
→ <b>sie</b>

#### die Lehrerin
→ feminine
→ <b>sie</b>

---

### Important

German nouns begin with a capital letter:
- Stift
- Buch
- Lehrerin

Pronouns are written in small letters:
- er
- sie
- es

---

### Listening strategy

Listen carefully to:
- Pronunciation of er / es / sie
- Singular or plural meaning

</details>


---



 ## AUSSPRACHE  
 ## Wortakzent

 ##  Wo ist die Betonung?  Hören Sie und markieren Sie.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_015.mp3?raw=true)

1. Sprachkurs  _____Sprach_____
2. Bücher      [[Bü]]

3. Stift       [[Stift ]]

4. Filme       [[Fil]]

5. Computer    [[pu]]

6. Musik       [[sik]]

7. Gitarre     [[tar]]

8. Wörter      [[ Wör]]

9. Deutschlehrer [[Deutsch]] 

10. Englischbuch  [[ Eng]]

11. Professorin  [[so]]

12. Freizeitaktivität [[Frei]]


<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this pronunciation exercise, you must identify:
👉 which syllable has the stress (Betonung).

German words usually have one strong syllable.

---

### How to solve the task

1️⃣ Listen carefully to the word

2️⃣ Pay attention to the louder or stronger part

3️⃣ Mark the stressed syllable   

The stressed syllable is:
- louder
- clearer
- stronger

---

### Helpful pronunciation strategy

#### Two-syllable words
Often the first syllable is stressed.

Examples:
- Bücher
- Filme
- Wörter

---

#### Longer words
Listen carefully because the stress can move.

Examples:
- Computer
- Professorin
- Freizeitaktivität

---

### Important

Compound words often stress the first main word.

Example:
- Deutschlehrer
→ stress on <b>Deutsch</b>

---

### Listening tip

Clap or tap while listening:
👏 weak — STRONG — weak

This helps you hear the stressed syllable more easily.

</details>

---

  ## Ich studiere jetzt in Greifswald!

   ## Sortieren Sie die Sätze und schreiben Sie die Textnachricht an Mischa.

* a.  spreche Deutsch und Englisch. Und du?  
* b.  Interessant, aber es ist nicht einfach. Es ist  
* c.  hier! Sie sind sehr international und wir  
* d.  Hallo Mischa, wie geht es dir?  
* e. ein Job! Die Uni ist sehr alt und  

* f.  es dir? Mir geht es gut. Ich studiere jetzt  
* g.  Grüße.  
* h.  sie ist sehr schön! Ich habe schon Freunde  
* i.  bist du, was machst du? Viele  
* j.  Physik in Greifswald! Das Studium ist

1. [[Hallo Mischa, wie geht es dir? ]]
2. [[hier! Sie sind sehr international und wir ]]
3. [[Interessant, aber es ist nicht einfach. Es ist ]]
4. [[ es dir? Mir geht es gut. Ich studiere jetzt]]
5. [[Physik in Greifswald! Das Studium ist]]
6. [[ein Job! Die Uni ist sehr alt und ]]
7. [[bist du, was machst du? Viele ]]
8. [[Grüße. ]]
9. [[sie ist sehr schön! Ich habe schon Freunde  ]]
10. [[spreche Deutsch und Englisch. Und du? ]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must put the text message into the correct logical order.

To solve the task:

1️⃣ Start with the greeting  
A message usually begins with:
- Hallo …
- Wie geht es dir?

---

2️⃣ Find the answer to the greeting

After:
- „Wie geht es dir?“

you normally answer:
- „Mir geht es gut.“

---

3️⃣ Look for connected ideas

Some sentences belong together because they talk about the same topic.

Example:
- „Ich studiere jetzt …“
- „Das Studium ist interessant …“

These sentences continue the same idea.

---

4️⃣ Watch for linking words

Words like:
- aber
- und

Connect ideas and help you continue the message logically.

---

5️⃣ Finish with closing phrases

Messages often end with:
- Und du?
- Viele Grüße.

These are usually near the end.

---

### Important writing strategy

Read the text like a real WhatsApp or chat message:
- Greeting
- Personal information
- University/study details
- Questions to the friend
- Closing

This helps you find the correct order naturally.

</details>

## GRAMMATIK KOMPAKT  
 ## Negation

 ###  Wo steht nicht?  
Antworten Sie wie im Beispiel.

1. Sprichst du gut Koreanisch?  
   ~~_Nein, ich spreche nicht gut Koreanisch._~~

2. Studierst du in Wolfsburg?  
   Nein, [[ich studiere nicht in Wolfsburg]]


3. Liest du gern?  
   [[ich lese nicht gern]]


4. Findest du Schach interessant?  
   [[ich finde Schach nicht interessant]]


5. Arbeitest du?  
  [[ich arbeite nicht]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you answer questions with:
👉 <b>nicht</b> (negation).

You must build negative sentences.

---

### Important grammar rule

<b>nicht</b> usually comes:
- Before adjectives
- Before places
- Before adverbs
- Or at the end of the sentence

---

### Examples

#### not good
- nicht gut Koreanisch

#### not in Wolfsburg
- nicht in Wolfsburg

#### not interesting
- nicht interessant

#### not gladly
- nicht gern

---

### How to solve the task

1️⃣ Start with:
- Nein, ich …

2️⃣ Use the correct verb form

3️⃣ Put <b>nicht</b> in the correct position

---

### Helpful trick

Ask yourself:

👉 What exactly is negated?

- The place?
- The adjective?
- The activity?
- The opinion?

Then place <b>nicht</b> before that part.

</details>


  ##  Schreiben Sie Sätze.

1. und • nicht • Eva • im Sprachkurs • sind • Tom
[[Tom und Eva sind nicht im Sprachkurs]]


2. Keyboard • gut • spielt • Amanda • nicht
[[Amanda spielt nicht gut Keyboard.]]


3. interessant • Bijan • nicht • findet • Fußball
[[Bijan findet Fußball nicht interessant]]


4. nicht • Laura • studiert
[[Laura studiert nicht]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must build correct German sentences from mixed words.

To solve the task:

1️⃣ Find the subject first  
Examples:
- Tom und Eva
- Amanda
- Bijan
- Laura

The subject usually comes at the beginning.

---

2️⃣ Find the verb

German main sentences need:
👉 The verb in Position 2.

Examples:
- sind
- spielt
- findet
- studiert

---

3️⃣ Place <b>nicht</b> correctly

Use <b>nicht</b> to negate:
- A place
- An adjective
- An activity
- The whole sentence

Examples:
- nicht im Sprachkurs
- nicht gut
- nicht interessant

---

4️⃣ Build the sentence logically

German sentence order is usually:

Subject + Verb + Other Information

Example:
- Amanda spielt nicht gut Keyboard.

---

### Important

German nouns begin with a capital letter:
- Sprachkurs
- Keyboard
- Fußball

Verbs are written in small letters:
- spielt
- findet
- studiert

</details>


  ## Sakura ist neu in Deutschland. Ergänzen Sie nicht oder kein(e).

* Sakuras Plan: ein Studium in Köln. Sie spricht Japanisch und Englisch, aber sie spricht [[nicht]] gut Deutsch. Sakura macht einen Deutschkurs. Aber der Kurs ist [[nicht]] in Köln, er ist in Düsseldorf! Sakura findet Düsseldorf [[nicht]] schön. Und Deutsch ist [[nicht]] einfach.


* Dann trifft Sakura Stefan. Stefan studiert Japanisch in Köln. Er sagt: [[kein]] Problem! Wir machen ein Sprachtandem.“ Sie lernen oft zusammen und sind jetzt Freunde. Sakura studiert jetzt Kunst in Köln und hat [[keine]] Probleme mehr.

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must decide:
👉 use <b>nicht</b> or <b>kein / keine</b>.

To solve the task, first ask:

### Is the sentence negating:
- a noun?
OR
- an adjective / place / whole sentence?

---

### Use <b>kein / keine</b>
when you negate a noun.

Examples:
- kein Problem
- keine Probleme

You use:
- kein → masculine or neuter singular
- keine → feminine or plural nouns

---

### Use <b>nicht</b>
when you negate:
- adjectives
- places
- languages
- the whole sentence

Examples:
- nicht gut
- nicht schön
- nicht einfach

---

### Helpful strategy

Look at the word after the blank:

#### noun?
→ use kein / keine

#### adjective or description?
→ use nicht

Examples:
- ___ Problem → noun
- ___ schön → adjective

This helps you choose correctly.

</details>
## Mein Hobby ist …

  ## Markieren Sie die Nomen. Notieren Sie die Nomen dann mit Artikel.

BHNLAPTOPUGINFORMATIONENSDPTASCHETTUHOBBYGMANSURFBOARDSZENGITARREHVWKURSETROANMELDUNGIFVM

1. ~~der Laptop~~
2. .[[die Informationen]]

3. .[[die Tasche]]

4. .[[das Hobby]]

5. .[[die Surfboards]]

6. .[[die Gitarre]]

7. .[[die Kurse]]

8. .[[die Anmeldung]]

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must find hidden German nouns inside a long group of letters.

To solve the task:

1️⃣ Look for familiar German words

2️⃣ Separate the letters into meaningful nouns

3️⃣ Add the correct article:
- der
- die
- das

---

### Helpful strategy

Search for:
- University vocabulary
- Hobby vocabulary
- Objects and activities

Examples:
- Laptop
- Hobby
- Gitarre
- Anmeldung

---

### Grammar clue

German nouns always begin with a capital letter.

You must also remember the correct article:

- der Laptop
- die Tasche
- das Hobby

---

### Important

Plural nouns also use:
→ die

Examples:
- die Informationen
- die Kurse
- die Surfboards

Read slowly and try to divide the long word chain into smaller known words.

</details>



 ##  Mailbox-Nachrichten: Ergänzen Sie die Wörter aus 1a. Hören Sie dann zur Kontrolle.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_017.mp3?raw=true)

1. Guten Tag, Herr Bauer. Hier ist Jonas Frey. Ich habe eine Frage. Mein [[Hobby]] ist Schwimmen und ich suche einen Kurs. Ist der Schwimmkurs auch eine Woche gratis? Und ist die [[Anmeldung]] online? Bitte rufen Sie mich zurück unter 0151-64870254. Vielen Dank und auf Wiederhören!


2. Hallo Adriana, hier ist Hannah! Du suchst [[Surfboards]]? Ich habe drei, aber sie sind schon zehn Jahre alt. Kaufst du sie für 90 Euro? Meine Nummer ist 0178-76187903.


3. Hallo Jonas! Ein Freund und ich spielen [[Gitarre]] für 2 Personen? Ich heiße Ben, Telefon [[Kurse]].


4. Hey Fati, hier ist Annette. Du [[Laptop]] hast einen [[Informationen]]. Aber ich brauche noch mehr  und ich suche einen, super! Ich rufe später noch einmal an. Ach, die [[Tasche]] brauche ich nicht. Bis später!

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this listening exercise, you must complete the mailbox messages with the correct nouns from Exercise 1a.

To solve the task:

1️⃣ Listen for keywords about:
- Hobbies
- University courses
- Music
- Technology
- Registration

---

### Helpful vocabulary meanings

- Hobby → free-time activity
- Anmeldung → registration
- Surfboards → boards for surfing
- Gitarre → musical instrument
- Kurse → classes/courses
- Laptop → computer
- Informationen → information
- Tasche → bag

---

### Strategy for solving

Read the sentence first and ask:

👉 What word logically fits here?

Examples:

- „Mein ___ ist Schwimmen.“
→ hobby/activity
→ Hobby

- „Ist die ___ online?“
→ registration process
→ Anmeldung

- „Wir spielen ___.“
→ musical instrument
→ Gitarre

- „Ich brauche noch mehr ___.“
→ information/details
→ Informationen

---

### Listening tip

Listen carefully for:
- Singular or plural forms
- Familiar university vocabulary
- Pronunciation of long German nouns

</details>



## [GRAMMATIK KOMPAKT]  
 ## Bestimmter, unbestimmter Artikel und Negativartikel  im Nominativ und Akkusativ

 ### Ergänzen Sie den bestimmten Artikel im Nominativ und im Akkusativ.

1.~~ Der ~~ Student trifft ~~den ~~ Professor und ~~die ~~ Professorin. 
2. Der Lehrer sucht [[das]]Wörterbuch und [[die]] Stifte.  

3. Die Studentin kauft [[das]] Surfboard und [[die]] Gitarre.  

4. Die Studenten brauchen [[die]] Laptops und [[die]] Taschen. 

<details style="background:#eef7ff;border:1px solid #cfe3ff;border-radius:14px;padding:14px;margin-bottom:18px;">
<summary><b>💡 Hint</b></summary>

In this exercise, you must choose the correct definite article:
- der
- das
- die
- den

You also need to understand:
👉 Nominativ
👉 Akkusativ

---

### Step 1️⃣ Find the subject

The subject is in:
👉 Nominativ

Ask:
- Who does the action?

Examples:
- Der Student trifft …
- Die Studentin kauft …
- Die Studenten brauchen …

The subject keeps the normal article:
- der
- die
- das

---

### Step 2️⃣ Find the object

The object is usually in:
👉 Akkusativ

Ask:
- Whom?
- What?

---

### Important Akkusativ rule

Only:
👉 masculine articles change

| Nominativ | Akkusativ |
|---|---|
| der | den |

Examples:
- der Professor → den Professor

---

### Neuter and plural stay the same

| Nominativ | Akkusativ |
|---|---|
| das | das |
| die | die |

Examples:
- das Wörterbuch → das Wörterbuch
- die Stifte → die Stifte

---

### Helpful strategy

1️⃣ Find the verb

2️⃣ Find the subject

3️⃣ Find the object

4️⃣ Choose the correct article

</details>


## Studium und Freizeit

| Kategorie | Wort / Ausdruck |
|----------|-----------------|
| Nomen | der Buddy, -s |
| Nomen | der Erstsemester, - |
| Nomen | das Programm, -e |
| Nomen | die Universität, -en (Abk.: Uni) |
| Nomen | das Unijournal, -e |
| Nomen | der Mitarbeiter, - / die Mitarbeiterin, -nen |
| Nomen | der Unimitarbeiter, - / die Unimitarbeiterin, -nen |
| Nomen | das Studium (nur Sg.) |
| Nomen | das Hobby, -s |
| Nomen | der Job, -s |
| Nomen | die Musik (nur Sg.) |
| Nomen | der Spaß, -e |
| Nomen | der Student, -en / die Studentin, -nen |
| Nomen | das Team, -s |
| Nomen | der Tipp, -s |
| Nomen | das Problem, -e |
| Verb | üben |
| Verb | organisieren |
| Verb | machen |
| Verb | arbeiten als … |
| Verb | der Job als … |
| Verb | kennen |
| Verb | begleiten |
| Verb | haben (hat) |
| Verb | Fragen haben |
| Verb | zeigen |
| Verb | geben (gibt) |
| Verb | finden |
| Ausdruck | interessant |
| Ausdruck | etwas super finden |
| Nomen | das Sprachtandem, -s |
| Nomen | die Freizeit (nur Sg.) |
| Nomen | die Zeitschrift, -en |
| Nomen | der Sport (nur Sg.) |
| Nomen | das Schach (nur Sg.) |
| Nomen | das Badminton (nur Sg.) |
| Verb | spielen |
| Verb | Gitarre spielen |
| Verb | Schach spielen |
| Verb | Fußball / Volleyball / Basketball spielen |
| Verb | Sport machen |
| Verb | Sport treiben |
| Verb | treffen (trifft) |
| Verb | Freunde treffen |
| Verb | schauen |
| Verb | Filme / Serien schauen |
| Verb | tanzen |
| Verb | Salsa tanzen |
| Verb | schwimmen |
| Verb | unternehmen (unternimmt) |
| Verb | hören |
| Verb | Musik hören |
| Verb | lesen (liest) |
| Verb | Bücher lesen |
| Verb | Zeitschriften lesen |
| Ausdruck | gern / gerne |
| Ausdruck | sehr / super gern |
| Ausdruck | nicht so / nicht / überhaupt nicht gern |
| Ausdruck | gern – lieber – am liebsten |
| Nomen | der Beginn (nur Sg.) |
| Nomen | der Semesterbeginn (nur Sg.) |
| Nomen | der Kaffee, -s |
| Verb | trinken |
| Ausdruck | Kaffee trinken |
| Nomen | die Idee, -n |
| Ausdruck | Das ist eine sehr gute Idee! |
| Land | Portugal |
| Nomen | der Park, -s |
| Nomen | das Stadion, Stadien |
| Nomen | der Bass, -e |
| Nomen | das Keyboard, -s |
| Nomen | die Gruppe, -n |
| Nomen | die Tasche, -n |
| Verb | brauchen |
| Verb | funktionieren |
| Ausdruck | gratis |
| Verb | testen |
| Nomen | das Sportprogramm, -e |
| Nomen | die Woche, -n |
| Nomen | die Sportart, -en |
| Nomen | das Surfen (nur Sg.) |
| Nomen | der Beachvolleyball (nur Sg.) |
| Nomen | das / der Yoga (nur Sg.) |
| Nomen | die Anmeldung, -en |
| Verb | fragen / antworten |
| Verb | surfen |
| Nomen | das Board, -s |
| Nomen | das Surfboard, -s |
| Ausdruck | nicht mehr |
| Satz | Du surfst nicht mehr. |
| Verb | kaufen |
| Ausdruck | Sehr geehrter Herr … / Sehr geehrte Frau … |
| Ausdruck | Mit freundlichen Grüßen |
| Ausdruck | Viele Grüße |
| Ausdruck | online |
| Nomen | das Formular, -e |
| Verb | ausfüllen |
| Nomen | der Anhang, -e |
| Verb | scannen |
| Verb | mailen |
| Nomen | das Datum, Daten |
| Nomen | die Unterschrift, -en |

# Lösungen / Answer Key – Kapitel 2 Übungsbuchteil

## An der Uni

 ## Wie heißen die Nomen?
1. die Universität  
2. das Studium  
3. die Studentin  
4. der Job  
5. der Professor  

 ## Ergänzen Sie
1. arbeitet  
2. studiert  
3. begleitet  
4. haben  
5. zeigt / gibt  
7. ist  
8. übt  

 ## Was passt?
1. als Buddy → arbeiten  
2. die Uni → zeigen, kennen  
3. Erstsemester → begleiten, sein  
4. Fragen → haben  
5. Tipps → geben  
6. eine Sprache → lernen, üben  

 ## Wer sind die Personen?
1. Student  
2. Professorinnen  
3. Buddy  
4. Team  
5. Mitarbeiterin  

---

## Grammatik Kompakt – Artikel

 ## Bestimmter Artikel
1. der Job  
2. das Studium  
3. das Team  
4. die Sprache  
5. die Universität  
6. die Studenten  
7. die Tipps  

 ## Singular / Plural
1. Studentinnen  
2. Professor  
3. Professorinnen  
4. Team  
5. Universitäten  
6. Computer  
7. Sprachen  
8. Programm  
9. Tipps  
10. Frage  

 ## Unbestimmte Artikel
1. ein Studium  
2. — Tipps  
3. eine Frage  
4. ein Buddy  
5. — Erstsemester  
6. eine Studentin  

---

 ## Das ist kein Englischbuch …

1. kein Englischbuch / ein Deutschbuch  
2. keine Geige / eine Gitarre  
3. keine Fußbälle / Basketbälle  
4. kein Laptop / ein Computer  

---

 ## Im Sprachkurs – Personalpronomen

1. er  
2. Es  
3. Sie  
4. Er  
5. Sie  

---

## Aussprache – Wortakzent

1. Sprachkurs → Sprach  
2. Bücher → Bü  
3. Stift → Stift  
4. Filme → Fil  
5. Computer → pu  
6. Musik → sik  
7. Gitarre → tar  
8. Wörter → Wör  
9. Deutschlehrer → Deutsch  
10. Englischbuch → Eng  
11. Professorin → so  
12. Freizeitaktivität → Frei  

---

 ## Ich studiere jetzt in Greifswald!

Correct order:

1. Hallo Mischa, wie geht es dir?  
2. Mir geht es gut. Ich studiere jetzt  
3. Physik in Greifswald! Das Studium ist  
4. interessant, aber es ist nicht einfach. Es ist  
5. ein Job! Die Uni ist sehr alt und  
6. sie ist sehr schön! Ich habe schon Freunde  
7. hier! Sie sind sehr international und wir  
8. sprechen Deutsch und Englisch. Und du?  
9. Wo bist du, was machst du? Viele  
10. Grüße.  

---

## Negation

 ## Wo steht nicht?
1. Nein, ich spreche nicht gut Koreanisch.  
2. Nein, ich studiere nicht in Wolfsburg.  
3. Ich lese nicht gern.  
4. Ich finde Schach nicht interessant.  
5. Ich arbeite nicht.  

 ## Schreiben Sie Sätze
1. Tom und Eva sind nicht im Sprachkurs.  
2. Amanda spielt nicht gut Keyboard.  
3. Bijan findet Fußball nicht interessant.  
4. Laura studiert nicht.  

 ## Sakura ist neu in Deutschland
1. nicht  
2. nicht  
3. nicht  
4. nicht  
5. kein  
6. keine  

---

## Mein Hobby ist …

 ## Nomen mit Artikel
1. der Laptop  
2. die Informationen  
3. die Tasche  
4. das Hobby  
5. die Surfboards  
6. die Gitarre  
7. die Kurse  
8. die Anmeldung  

 ## Mailbox-Nachrichten
1. Hobby / Anmeldung  
2. Surfboards  
3. Gitarre / Kurse  
4. Laptop / Informationen / Tasche  

---

 ## Grammatik Kompakt – Nominativ und Akkusativ

1. Der Student trifft den Professor und die Professorin.  
2. Der Lehrer sucht das Wörterbuch und die Stifte.  
3. Die Studentin kauft das Surfboard und die Gitarre.  
4. Die Studenten brauchen die Laptops und die Taschen.  

