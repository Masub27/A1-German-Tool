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
# Welcome
<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0b2a66"/>
      <stop offset="1" stop-color="#4fa3ff"/>
    </linearGradient>

    <linearGradient id="panel" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0.95"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0.85"/>
    </linearGradient>

    <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="12" stdDeviation="14" flood-color="#001736" flood-opacity="0.35"/>
    </filter>

    <style>
      .title{font: 800 74px/1.05 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .subtitle{font: 500 30px/1.35 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .chip{font: 650 22px/1 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .h2{font: 800 34px/1.1 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .txt{font: 500 24px/1.4 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .small{font: 500 18px/1.3 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
    </style>
  </defs>

  <!-- Background -->
  <rect width="1600" height="900" fill="url(#bg)"/>

  <!-- Decorative circles -->
  <circle cx="1320" cy="150" r="210" fill="#ffffff" opacity="0.10"/>
  <circle cx="1440" cy="290" r="110" fill="#ffffff" opacity="0.10"/>
  <circle cx="250" cy="770" r="260" fill="#ffffff" opacity="0.08"/>

  <!-- Main panel -->
  <g filter="url(#shadow)">
    <rect x="110" y="110" rx="28" ry="28" width="1380" height="680" fill="url(#panel)"/>
  </g>

  <!-- Header bar -->
  <rect x="110" y="110" rx="28" ry="28" width="1380" height="130" fill="#ffffff" opacity="0.25"/>
  <rect x="110" y="240" width="1380" height="2" fill="#0b2a66" opacity="0.12"/>

  <!-- Chapter chip -->
  <g>
    <rect x="160" y="150" rx="22" ry="22" width="190" height="44" fill="#0b2a66" opacity="0.95"/>
    <text x="255" y="180" text-anchor="middle" fill="#ffffff" class="chip">KAPITEL 2</text>
  </g>

  <!-- Title -->
  <text x="160" y="330" fill="#0b2a66" class="title">An der Uni</text>
  <text x="160" y="385" fill="#0b2a66" opacity="0.85" class="subtitle">
    Wortschatz • Grammatik • Aussprache • Hörverstehen
  </text>

  <!-- Cards row -->
  <g>
    <!-- Card 1: Wortschatz -->
    <g transform="translate(160, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#ffffff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <!-- icon: building -->
      <g transform="translate(24,24)" opacity="0.95">
        <rect x="0" y="36" width="86" height="86" rx="14" fill="#eaf2ff"/>
        <path d="M14 54h58M14 72h58M14 90h58" stroke="#0b2a66" stroke-width="4" opacity="0.35"/>
        <path d="M18 120V58l25-14 25 14v62" fill="none" stroke="#0b2a66" stroke-width="5" stroke-linejoin="round"/>
        <path d="M34 120V86h18v34" fill="none" stroke="#0b2a66" stroke-width="5" stroke-linejoin="round"/>
        <path d="M18 58l25-14 25 14" fill="none" stroke="#0b2a66" stroke-width="5" stroke-linejoin="round"/>
      </g>
      <text x="140" y="58" fill="#0b2a66" class="h2">Wortschatz</text>
      <text x="140" y="104" fill="#0b2a66" opacity="0.85" class="txt">Universität, Studium,</text>
      <text x="140" y="140" fill="#0b2a66" opacity="0.85" class="txt">Student/in, Job,</text>
      <text x="140" y="176" fill="#0b2a66" opacity="0.85" class="txt">Professor, Buddy</text>

      <text x="10" y="240" fill="#0b2a66" opacity="0.70" class="small">+ Verben kombinieren: Tipps geben, Sprache üben</text>
    </g>

    <!-- Card 2: Grammatik -->
    <g transform="translate(595, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#ffffff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <!-- icon: grammar / blocks -->
      <g transform="translate(24,24)" opacity="0.95">
        <rect x="0" y="36" width="86" height="86" rx="14" fill="#fff3e6"/>
        <rect x="10" y="52" width="66" height="14" rx="7" fill="#0b2a66" opacity="0.25"/>
        <rect x="10" y="76" width="46" height="14" rx="7" fill="#0b2a66" opacity="0.25"/>
        <rect x="10" y="100" width="58" height="14" rx="7" fill="#0b2a66" opacity="0.25"/>
        <path d="M104 54h44" stroke="#0b2a66" stroke-width="6" opacity="0.35" stroke-linecap="round"/>
      </g>
      <text x="140" y="58" fill="#0b2a66" class="h2">Grammatik</text>
      <text x="140" y="104" fill="#0b2a66" opacity="0.85" class="txt">Artikel: der / die / das</text>
      <text x="140" y="140" fill="#0b2a66" opacity="0.85" class="txt">ein / eine (unbestimmt)</text>
      <text x="140" y="176" fill="#0b2a66" opacity="0.85" class="txt">Plural &amp; Pronomen</text>

      <text x="24" y="240" fill="#0b2a66" opacity="0.70" class="small">+ Negation: nicht / kein(e)</text>
    </g>

    <!-- Card 3: Hören & Aussprache -->
    <g transform="translate(1030, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#ffffff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <!-- icon: headphones -->
      <g transform="translate(24,24)" opacity="0.95">
        <rect x="0" y="36" width="86" height="86" rx="14" fill="#eafff4"/>
        <path d="M18 88c0-20 10-34 25-34s25 14 25 34" fill="none" stroke="#0b2a66" stroke-width="6" opacity="0.9" stroke-linecap="round"/>
        <path d="M18 88v16c0 8 6 14 14 14" fill="none" stroke="#0b2a66" stroke-width="6" opacity="0.9" stroke-linecap="round"/>
        <path d="M68 88v16c0 8-6 14-14 14" fill="none" stroke="#0b2a66" stroke-width="6" opacity="0.9" stroke-linecap="round"/>
        <rect x="8" y="86" width="16" height="34" rx="8" fill="#0b2a66" opacity="0.25"/>
        <rect x="62" y="86" width="16" height="34" rx="8" fill="#0b2a66" opacity="0.25"/>
      </g>
      <text x="120" y="58" fill="#0b2a66" class="h2">Hören &amp; Aussprache</text>
      <text x="140" y="104" fill="#0b2a66" opacity="0.85" class="txt">Dialoge &amp; Mailbox</text>
      <text x="140" y="140" fill="#0b2a66" opacity="0.85" class="txt">Wortakzent</text>
      <text x="140" y="176" fill="#0b2a66" opacity="0.85" class="txt">Sätze sortieren</text>

      <text x="24" y="240" fill="#0b2a66" opacity="0.70" class="small">+ Schreiben: kurze Nachricht (Greifswald)</text>
    </g>
  </g>

  <!-- Footer -->
  <text x="160" y="835" fill="#ffffff" opacity="0.92" class="small">
    A1 Deutsch • Kapitelstart • Interaktive Übungen in LiaScript
  </text>
  <text x="1490" y="835" text-anchor="end" fill="#ffffff" opacity="0.75" class="small">
    
  </text>
</svg>

   --{{0}}--
In this chapter, you will learn important university vocabulary and basic grammar.
You will practice pronunciation and listening with short dialogues and messages.
You will learn how to use articles, plurals, and simple pronouns.
Let’s get started and learn German step by step.

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
• type your own question
• click a quick topic button
• ask about grammar, vocabulary, university life, hobbies, mailbox messages, or chapter sections

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
• type your own question
• click a quick topic button
• ask about grammar, university life, hobbies, mailbox messages, or chapter sections

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

 ###  Wie heißen die Nomen? Schreiben Sie.

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

---

 ###  Was passt? Kreuzen Sie an.  Manchmal passen zwei Antworten.

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

---

 ### Wer sind die Personen? Ergänzen Sie.

**Wörter:**  
Buddy · Mitarbeiterin · Professorinnen · Student · Team

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

---

## GRAMMATIK KOMPAKT  
 ### Bestimmter, unbestimmter und Negativartikel im Nominativ

 ###  Was passt wo? Schreiben Sie mit dem bestimmten Artikel.

**Wörter:** 

>Film · Job · Sprache · Studenten · Studium · Team · Tipps · Universität

Maskulinum (der):  
der [[ Job]]

Neutrum (das):  
das [[Studium]]
das [[Team]] 

Femininum (die):  
die [[Sprache]]
die [[Universität]]

Plural (die):  
die [[Studenten]]
die [[Tipps]]

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

---

 ##  Was hören Sie? Ergänzen Sie die unbestimmten Artikel.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_013.mp3?raw=true)

1. das Studium → [[ein]] Studium  
2. die Tipps → [[solution]] Tipps  
3. die Frage → [[eine]]Frage  
4. der Buddy → [[ein]] Buddy  
5. die Erstsemester → [[solution]] Erstsemester  
6. die Studentin → [[eine]]Studentin




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

---



 ##  Im Sprachkurs

 ##  Ergänzen Sie die Personalpronomen und hören Sie zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_014.mp3?raw=true)

1. Der Stift? Ja, [[er]] schreibt sehr gut.  
2. Das ist ein Buch. [[Es]] ist sehr interessant.  
3. Hier sind Laptops. [[Sie]] sind neu!  
4. Das ist mein Kollege. [[Er]] ist sehr nett.  
5. Und da ist die Lehrerin. [[Sie]] kommt aus Rostock.



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



---

  ## Ich studiere jetzt in Greifswald!

   ### Sortieren Sie die Sätze und schreiben Sie die Textnachricht an Mischa.

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

[[Hallo Mischa, wie geht es dir? ]]
[[hier! Sie sind sehr international und wir ]]
[[Interessant, aber es ist nicht einfach. Es ist ]]
[[ es dir? Mir geht es gut. Ich studiere jetzt]]
[[Physik in Greifswald! Das Studium ist]]
[[ein Job! Die Uni ist sehr alt und ]]
[[bist du, was machst du? Viele ]]
[[Grüße. ]]
[[sie ist sehr schön! Ich habe schon Freunde  ]]
[[spreche Deutsch und Englisch. Und du? ]]


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

  ##  Schreiben Sie Sätze.

1. und • nicht • Eva • im Sprachkurs • sind • Tom
[[Tom und Eva sind nicht im Sprachkurs]]

2. Keyboard • gut • spielt • Amanda • nicht
[[Amanda spielt nicht gut Keyboard.]]

3. interessant • Bijan • nicht • findet • Fußball
[[Bijan findet Fußball nicht interessant]]

4. nicht • Laura • studiert
[[Laura studiert nicht]]


  ## Sakura ist neu in Deutschland. Ergänzen Sie nicht oder kein(e).

* Sakuras Plan: ein Studium in Köln. Sie spricht Japanisch und Englisch, aber sie spricht [[nicht]] gut Deutsch. Sakura macht einen Deutschkurs. Aber der Kurs ist [[nicht]] in Köln, er ist in Düsseldorf! Sakura findet Düsseldorf [[nicht]] schön. Und Deutsch ist [[nicht]] einfach.

* Dann trifft Sakura Stefan. Stefan studiert Japanisch in Köln. Er sagt: [[kein]] Problem! Wir machen ein Sprachtandem.“ Sie lernen oft zusammen und sind jetzt Freunde. Sakura studiert jetzt Kunst in Köln und hat [[keine]] Probleme mehr.

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


 ##  Mailbox-Nachrichten: Ergänzen Sie die Wörter aus 1a. Hören Sie dann zur Kontrolle.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_017.mp3?raw=true)

1. Guten Tag, Herr Bauer. Hier ist Jonas Frey. Ich habe eine Frage. Mein [[Hobby]] ist Schwimmen und ich suche einen Kurs. Ist der Schwimmkurs auch eine Woche gratis? Und ist die [[Anmeldung]] online? Bitte rufen Sie mich zurück unter 0151-64870254. Vielen Dank und auf Wiederhören!

2. Hallo Adriana, hier ist Hannah! Du suchst [[Surfboards]]? Ich habe drei, aber sie sind schon zehn Jahre alt. Kaufst du sie für 90 Euro? Meine Nummer ist 0178-76187903.

3. Hallo Jonas! Ein Freund und ich spielen [[Gitarre]] für 2 Personen? Ich heiße Ben, Telefon [[Kurse]].

4. Hey Fati, hier ist Annette. Du [[Laptop]] hast einen [[Informationen]]. Aber ich brauche noch mehr  und ich suche einen, super! Ich rufe später noch einmal an. Ach, die [[Tasche]] brauche ich nicht. Bis später!


## [GRAMMATIK KOMPAKT]  
 ## Bestimmter, unbestimmter Artikel und Negativartikel  im Nominativ und Akkusativ

 ### Ergänzen Sie den bestimmten Artikel im Nominativ und im Akkusativ.

1.~~ Der ~~ Student trifft ~~den ~~ Professor und ~~die ~~ Professorin. 
2. Der Lehrer sucht [[das]]Wörterbuch und [[die]] Stifte.  
3. Die Studentin kauft [[das]] Surfboard und [[die]] Gitarre.  
4. Die Studenten brauchen [[die]] Laptops und [[die]] Taschen. 

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

## END

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bgEnd2" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0b2a66"/>
      <stop offset="0.55" stop-color="#3a7bd5"/>
      <stop offset="1" stop-color="#7fb7ff"/>
    </linearGradient>

    <linearGradient id="panelEnd2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0.96"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0.86"/>
    </linearGradient>

    <filter id="shadowEnd2" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="14" stdDeviation="16" flood-color="#001736" flood-opacity="0.35"/>
    </filter>

    <style><![CDATA[
      .title{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:900; font-size:76px;}
      .subtitle{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:600; font-size:30px;}
      .chip{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:750; font-size:22px;}
      .h2{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:900; font-size:34px;}
      .txt{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:550; font-size:24px;}
      .small{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:550; font-size:18px;}
    ]]></style>
  </defs>

  <rect width="1600" height="900" fill="url(#bgEnd2)"/>

  <circle cx="1320" cy="180" r="220" fill="#fff" opacity="0.10"/>
  <circle cx="1450" cy="310" r="120" fill="#fff" opacity="0.10"/>
  <path d="M0,720 C280,640 520,820 800,740 C1060,665 1220,720 1600,640 L1600,900 L0,900 Z" fill="#fff" opacity="0.08"/>

  <g filter="url(#shadowEnd2)">
    <rect x="110" y="110" rx="28" ry="28" width="1380" height="680" fill="url(#panelEnd2)"/>
  </g>

  <rect x="110" y="110" rx="28" ry="28" width="1380" height="130" fill="#fff" opacity="0.20"/>
  <rect x="110" y="240" width="1380" height="2" fill="#0b2a66" opacity="0.12"/>

  <rect x="160" y="150" rx="22" ry="22" width="260" height="44" fill="#0b2a66" opacity="0.95"/>
  <text x="290" y="180" text-anchor="middle" fill="#fff" class="chip">KAPITEL 2 • ENDE</text>

  <text x="160" y="330" fill="#0b2a66" class="title">Danke!</text>
  <text x="160" y="385" fill="#0b2a66" opacity="0.85" class="subtitle">Kapitel 2 abgeschlossen • Gute Arbeit</text>

  <g>
    <g transform="translate(160, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <text x="28" y="62" fill="#0b2a66" class="h2">Du kannst jetzt…</text>
      <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">über Hobbys sprechen</text>
      <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">Kurse suchen</text>
      <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">Nachrichten verstehen</text>
      <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">Wortschatz: Hobby • Kurs • Anmeldung • …</text>
    </g>

    <g transform="translate(595, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <text x="28" y="62" fill="#0b2a66" class="h2">Grammatik</text>
      <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">Akkusativ-Verben</text>
      <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">Artikel im Akkusativ</text>
      <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">nicht / kein(e)</text>
      <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">kaufen • brauchen • suchen • …</text>
    </g>

    <g transform="translate(1030, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <text x="28" y="62" fill="#0b2a66" class="h2">Nächster Schritt</text>
      <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">Wiederholen</text>
      <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">Audio noch einmal hören</text>
      <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">Weiter zu Kapitel 3</text>
      <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">Tipp: 5 Minuten täglich üben</text>
    </g>
  </g>

  <text x="160" y="835" fill="#ffffff" opacity="0.92" class="small">A1 Deutsch • Kapitelende • LiaScript</text>
  <text x="1490" y="835" text-anchor="end" fill="#ffffff" opacity="0.78" class="small">© Mahwixh &amp; Maxub</text>
</svg>