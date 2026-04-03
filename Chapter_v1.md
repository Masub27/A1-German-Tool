
<!--

author:   Masub Makhdoom
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

#  Herzlich Willkommen
<!-- A1 German Course Cover -->
<svg xmlns='http://www.w3.org/2000/svg' width='800' height='450' viewBox='0 0 800 450'><rect width='800' height='450' fill='%23228B22'/><rect x='50' y='50' width='700' height='350' rx='20' fill='white'/><text x='400' y='150' font-family='Arial' font-size='60' font-weight='bold' text-anchor='middle' fill='%23228B22'>DEUTSCH</text><text x='400' y='240' font-family='Arial' font-size='100' font-weight='bold' text-anchor='middle' fill='green'>A1</text><text x='400' y='300' font-family='Arial' font-size='40' text-anchor='middle' fill='%23228B22'>Sprachkurs für Anfänger</text><text x='400' y='350' font-family='Arial' font-size='20' text-anchor='middle' fill='gray'>powered by LiaScript</text></svg>

<!-- data-no-scroll -->

# 🤖 Avatar Bot

<section style="
  max-width:1200px;
  margin:auto;
  border-radius:24px;
  padding:20px;
  background:#eef3f9;
  font-family:Arial,sans-serif;
">

  <div style="
    background:#ffffff;
    border-radius:22px;
    padding:18px;
    border:1px solid #d0d9e6;
    box-shadow:0 8px 24px rgba(0,0,0,0.06);
  ">

    <!-- Header -->
    <div style="display:flex;align-items:center;gap:14px;margin-bottom:18px;">
      <div style="
        width:72px;height:72px;border-radius:50%;
        background:linear-gradient(135deg,#2f6fd1,#5ea0ff);
        display:flex;align-items:center;justify-content:center;
        font-size:34px;color:white;
      ">🧑‍🏫</div>

      <div>
        <h2 style="margin:0;color:#2f6fd1;">German Learning Avatar</h2>
        <div style="color:#5a6b85;font-size:14px;">
          Ask questions, listen to German, and practise pronunciation.
        </div>
      </div>
    </div>

    <!-- Avatar message -->
    <div id="avatar-box" style="
      background:#f4f7fb;
      border:1px solid #d0d9e6;
      border-radius:18px;
      padding:16px;
      color:#1a1a1a;
      line-height:1.6;
      margin-bottom:18px;
    ">
      Hallo! Ich bin dein Lernassistent.  
      Du kannst mir Fragen zu Kapitel 1 stellen.  
      Du kannst auch deutsche Sätze anhören und nachsprechen.
    </div>

    <!-- Voice controls -->
    <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:18px;">
      <button id="speak-btn" style="
        padding:12px 16px;
        background:#2f6fd1;
        color:white;
        border:none;
        border-radius:14px;
        font-weight:bold;
        cursor:pointer;
      ">🔊 Speak German</button>

      <button id="stop-btn" style="
        padding:12px 16px;
        background:white;
        color:#2f6fd1;
        border:1px solid #2f6fd1;
        border-radius:14px;
        font-weight:bold;
        cursor:pointer;
      ">⏹ Stop Voice</button>
    </div>

    <!-- Pronunciation practice -->
    <div style="
      background:#f9fbff;
      border:1px solid #d0d9e6;
      border-radius:18px;
      padding:16px;
      margin-bottom:18px;
    ">
      <h3 style="margin-top:0;color:#2f6fd1;">Pronunciation Practice</h3>

      <div style="margin-bottom:10px;color:#1a1a1a;">
        Practice sentence:
      </div>

      <div id="practice-text" style="
        background:white;
        border:1px solid #d0d9e6;
        border-radius:12px;
        padding:12px;
        color:#1a1a1a;
        font-weight:bold;
        margin-bottom:12px;
      ">Guten Tag, ich heiße Anna.</div>

      <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:12px;">
        <button id="listen-practice-btn" style="
          padding:10px 14px;
          background:#2f6fd1;
          color:white;
          border:none;
          border-radius:12px;
          cursor:pointer;
          font-weight:bold;
        ">🔊 Listen</button>

        <button id="record-btn" style="
          padding:10px 14px;
          background:white;
          color:#2f6fd1;
          border:1px solid #2f6fd1;
          border-radius:12px;
          cursor:pointer;
          font-weight:bold;
        ">🎤 Start Speaking</button>
      </div>

      <div id="speech-result" style="
        background:white;
        border:1px solid #d0d9e6;
        border-radius:12px;
        padding:12px;
        color:#1a1a1a;
        min-height:60px;
      ">
        Your speech result will appear here.
      </div>
    </div>

    <!-- Chat -->
    <div id="chat-box" style="
      min-height:260px;
      max-height:420px;
      overflow:auto;
      background:#f4f7fb;
      border-radius:18px;
      padding:16px;
      border:1px solid #d0d9e6;
    "></div>

    <!-- Quick buttons -->
    <div id="quick-area" style="margin-top:12px;display:flex;gap:8px;flex-wrap:wrap;"></div>

    <!-- Input -->
    <div style="margin-top:16px;display:flex;gap:10px;flex-wrap:wrap;">
      <input id="user-input" type="text"
        placeholder="Ask your question..."
        style="
          flex:1;
          padding:14px;
          border-radius:14px;
          border:1px solid #b8c7db;
          font-size:15px;
          color:#1a1a1a;
          background:#ffffff;
        ">

      <button id="send-btn" style="
        padding:14px 18px;
        background:#2f6fd1;
        color:white;
        border:none;
        border-radius:14px;
        font-weight:bold;
        cursor:pointer;
      ">Ask</button>

      <button id="clear-btn" style="
        padding:14px 18px;
        background:white;
        color:#2f6fd1;
        border:1px solid #2f6fd1;
        border-radius:14px;
        font-weight:bold;
        cursor:pointer;
      ">Clear</button>
    </div>

  </div>
</section>

<style>
.msg{
  display:flex;
  margin:10px 0;
}
.msg.bot{justify-content:flex-start;}
.msg.user{justify-content:flex-end;}

.bubble{
  max-width:75%;
  padding:14px;
  border-radius:16px;
  font-size:14px;
  line-height:1.6;
  white-space:pre-wrap;
}

.msg.bot .bubble{
  background:#ffffff;
  color:#1a1a1a;
  border:1px solid #d0d9e6;
}

.msg.user .bubble{
  background:#2f6fd1;
  color:white;
}

.qbtn{
  padding:8px 12px;
  border-radius:12px;
  border:1px solid #2f6fd1;
  background:white;
  color:#2f6fd1;
  cursor:pointer;
  font-size:13px;
}
.qbtn:hover{
  background:#2f6fd1;
  color:white;
}
</style>

<script>
(() => {
  const chatBox = document.getElementById("chat-box");
  const input = document.getElementById("user-input");
  const sendBtn = document.getElementById("send-btn");
  const clearBtn = document.getElementById("clear-btn");
  const quickArea = document.getElementById("quick-area");

  const speakBtn = document.getElementById("speak-btn");
  const stopBtn = document.getElementById("stop-btn");
  const listenPracticeBtn = document.getElementById("listen-practice-btn");
  const recordBtn = document.getElementById("record-btn");
  const practiceText = document.getElementById("practice-text");
  const speechResult = document.getElementById("speech-result");
  const avatarBox = document.getElementById("avatar-box");

  const quickQuestions = [
    "What can I learn in this chapter?",
    "What is du and Sie?",
    "How do I introduce myself?",
    "What are W-questions?",
    "Where can I find numbers?"
  ];

  const knowledge = [
    {
      keys:["learn","chapter"],
      answer:"In this chapter you learn greetings, introductions, names, countries, languages, du and Sie, spelling, grammar, numbers, and telephone numbers."
    },
    {
      keys:["du","sie"],
      answer:"du is informal. Sie is formal. Use du with friends and Sie in polite situations."
    },
    {
      keys:["introduce"],
      answer:"Example: Ich heiße Ali. Ich komme aus Pakistan. Ich wohne in Magdeburg."
    },
    {
      keys:["w-questions","w fragen","w-fragen"],
      answer:"W-questions include: Wie, Woher, Was. Example: Wie heißt du?"
    },
    {
      keys:["numbers","zahl"],
      answer:"You can find numbers in the section 'Zahlen'. There you practise digits, words, and telephone numbers."
    },
    {
      keys:["name","familienname","vorname"],
      answer:"Vorname means first name. Familienname means last name."
    },
    {
      keys:["phone","telefon"],
      answer:"You practise listening to and writing telephone numbers in this chapter."
    }
  ];

  function addMessage(text, type){
    const row = document.createElement("div");
    row.className = "msg " + type;

    const bubble = document.createElement("div");
    bubble.className = "bubble";
    bubble.textContent = text;

    row.appendChild(bubble);
    chatBox.appendChild(row);
    chatBox.scrollTop = chatBox.scrollHeight;
  }

  function reply(question){
    const q = question.toLowerCase();
    for(const item of knowledge){
      for(const key of item.keys){
        if(q.includes(key)){
          return item.answer;
        }
      }
    }
    return "Please ask about grammar, names, du and Sie, introductions, or numbers.";
  }

  function askQuestion(text){
    const q = (text || input.value).trim();
    if(!q) return;
    addMessage(q, "user");
    addMessage(reply(q), "bot");
    input.value = "";
  }

  sendBtn.onclick = () => askQuestion();
  input.addEventListener("keydown", e => {
    e.stopPropagation();
    if(e.key === "Enter"){
      e.preventDefault();
      askQuestion();
    }
  });

  clearBtn.onclick = () => {
    chatBox.innerHTML = "";
    addMessage("Hallo! I am your Chapter 1 assistant. Ask me anything 😊", "bot");
  };

  quickQuestions.forEach(q => {
    const btn = document.createElement("button");
    btn.className = "qbtn";
    btn.textContent = q;
    btn.onclick = () => askQuestion(q);
    quickArea.appendChild(btn);
  });

  addMessage("Hallo! I am your Chapter 1 assistant. Ask me anything 😊", "bot");

  // Speech synthesis
  function speakGerman(text){
    if(!window.speechSynthesis) return;
    const utter = new SpeechSynthesisUtterance(text);
    utter.lang = "de-DE";
    utter.rate = 0.9;
    speechSynthesis.cancel();
    speechSynthesis.speak(utter);
  }

  speakBtn.onclick = () => {
    const text = "Hallo. In diesem Kapitel lernst du Begrüßungen, Namen, Herkunft, Sprachen, Grammatik, Zahlen und Telefonnummern.";
    avatarBox.textContent = "Speaking in German...";
    speakGerman(text);
    setTimeout(() => {
      avatarBox.textContent = "Hallo! Ich bin dein Lernassistent. Du kannst mir Fragen zu Kapitel 1 stellen. Du kannst auch deutsche Sätze anhören und nachsprechen.";
    }, 3000);
  };

  stopBtn.onclick = () => {
    if(window.speechSynthesis){
      speechSynthesis.cancel();
    }
  };

  listenPracticeBtn.onclick = () => {
    speakGerman(practiceText.textContent);
  };

  // Speech recognition
  let recognition = null;
  const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;

  if(SpeechRecognition){
    recognition = new SpeechRecognition();
    recognition.lang = "de-DE";
    recognition.interimResults = false;
    recognition.maxAlternatives = 1;

    recognition.onstart = () => {
      speechResult.textContent = "Listening... Please speak now.";
    };

    recognition.onresult = (event) => {
      const spoken = event.results[0][0].transcript;
      const target = practiceText.textContent.trim().toLowerCase();
      const student = spoken.trim().toLowerCase();

      let feedback = "You said: " + spoken + "\\n\\n";

      if(student === target){
        feedback += "Excellent! Your pronunciation matched the sentence very well.";
      } else if(student.includes("guten") || student.includes("heiße") || student.includes("anna")){
        feedback += "Good attempt! Some words were recognised correctly. Try again and speak a little more slowly.";
      } else {
        feedback += "Keep practising. Try to speak clearly and repeat the sentence again.";
      }

      speechResult.textContent = feedback;
    };

    recognition.onerror = () => {
      speechResult.textContent = "Speech recognition could not understand the audio. Please try again.";
    };

    recordBtn.onclick = () => {
      recognition.start();
    };
  } else {
    recordBtn.onclick = () => {
      speechResult.textContent = "Speech recognition is not supported in this browser. The voice listening feature may work better in Chrome.";
    };
  }
})();
</script>


# Hallo Deutschland!

 ## <span style="color:#006400;font-size:1.8em;font-weight:bold">
 Das Alphabet: Hören Sie die Buchstaben und sprechen Sie nach
</span>

?[](https://github.com/Masub27/Intro/blob/main/KursDaF_A1_KB_Track_001.mp3?raw=true)




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

# Horen Sie und schreiben Sie die Namen

?[](https://github.com/Masub27/Thesis-collection/blob/main/KursDaF_A1_KB_Track_003.mp3?raw=true)

1)Nelson [[M]][[u]][[l]][[l]][[e]][[r]]

2)Christen [[s]][[e]][[i]][[d]][[e]][[l]]

 ## Horen und Schreiben Sie die Telefonnummern.

 ?[](https://github.com/Masub27/Thesis-collection/blob/main/KursDaF_A1_KB_Track_005.mp3?raw=true)

1)Arek [[5]][[6]][[0]][[3]][[9]][[4]][[1]] 

2)Linus [[2]][[7]][[8]][[0]][[1]][[4]][[8]]    

3)Ella [[3]][[0]][[7]][[4]][[9]][[2]][[8]]   


# 1
<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bg2" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0b2a66"/>
      <stop offset="0.55" stop-color="#3a7bd5"/>
      <stop offset="1" stop-color="#7fb7ff"/>
    </linearGradient>

    <linearGradient id="glass" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0.92"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0.82"/>
    </linearGradient>

    <filter id="shadow2" x="-25%" y="-25%" width="150%" height="150%">
      <feDropShadow dx="0" dy="14" stdDeviation="16" flood-color="#00112b" flood-opacity="0.35"/>
    </filter>

    <style>
      .kicker{font: 700 22px/1 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .title{font: 900 76px/1.05 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .subtitle{font: 550 30px/1.4 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .h2{font: 850 34px/1.1 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .txt{font: 520 24px/1.45 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .small{font: 520 18px/1.35 system-ui, -apple-system, Segoe UI, Roboto, Arial;}
      .mono{font: 650 18px/1.3 ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;}
    </style>
  </defs>

  <!-- Background -->
  <rect width="1600" height="900" fill="url(#bg2)"/>

  <!-- Decorative shapes -->
  <circle cx="1320" cy="180" r="220" fill="#ffffff" opacity="0.10"/>
  <circle cx="1450" cy="310" r="120" fill="#ffffff" opacity="0.10"/>
  <path d="M0,720 C280,640 520,820 800,740 C1060,665 1220,720 1600,640 L1600,900 L0,900 Z"
        fill="#ffffff" opacity="0.08"/>

  <!-- Main panel -->
  <g filter="url(#shadow2)">
    <rect x="110" y="110" rx="28" ry="28" width="1380" height="680" fill="url(#glass)"/>
  </g>

  <!-- Kicker / Chapter -->
  <g>
    <rect x="160" y="150" rx="22" ry="22" width="260" height="44" fill="#0b2a66" opacity="0.95"/>
    <text x="290" y="180" text-anchor="middle" fill="#ffffff" class="kicker">KAPITELSTART • A1</text>
  </g>

  <!-- Title -->
  <text x="160" y="320" fill="#0b2a66" class="title">Guten Tag! Ich heiße …</text>
  <text x="160" y="378" fill="#0b2a66" opacity="0.85" class="subtitle">
    Begrüßen • Sich vorstellen • Name • Herkunft • Formell/Informell
  </text>

  <!-- Feature cards -->
  <g>
    <!-- Card 1: Dialoge -->
    <g transform="translate(160, 440)">
      <rect rx="22" ry="22" width="420" height="290" fill="#ffffff" opacity="0.93"/>
      <rect rx="22" ry="22" width="420" height="290" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>

      <!-- Icon: speech bubbles -->
      <g transform="translate(26,26)">
        <rect x="0" y="22" width="92" height="92" rx="16" fill="#eaf2ff"/>
        <path d="M18 50h56M18 70h40" stroke="#0b2a66" stroke-width="5" opacity="0.35" stroke-linecap="round"/>
        <path d="M18 92l10-10h44" stroke="#0b2a66" stroke-width="5" opacity="0.35" stroke-linecap="round"/>
        <path d="M110 48h66a14 14 0 0 1 14 14v38a14 14 0 0 1-14 14h-40l-12 12v-12h-14a14 14 0 0 1-14-14V62a14 14 0 0 1 14-14z"
              fill="none" stroke="#0b2a66" stroke-width="5" opacity="0.75" stroke-linejoin="round"/>
      </g>

      <text x="140" y="70" fill="#0b2a66" class="h2">Dialoge &amp; Zuordnen</text>
      <text x="26" y="132" fill="#0b2a66" opacity="0.86" class="txt">Gespräch A &amp; B: Antworten</text>
      <text x="26" y="168" fill="#0b2a66" opacity="0.86" class="txt">passen + Sätze sortieren</text>
      <text x="26" y="204" fill="#0b2a66" opacity="0.86" class="txt">mit Audio-Kontrolle</text>
      <text x="26" y="260" fill="#0b2a66" opacity="0.70" class="small">Fokus: Hallo, Guten Tag, Wie heißt du/Sie?</text>
    </g>

    <!-- Card 2: Aussprache & Schreiben -->
    <g transform="translate(610, 440)">
      <rect rx="22" ry="22" width="420" height="290" fill="#ffffff" opacity="0.93"/>
      <rect rx="22" ry="22" width="420" height="290" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>

      <!-- Icon: letters / spelling -->
      <g transform="translate(26,26)">
        <rect x="0" y="22" width="92" height="92" rx="16" fill="#fff3e6"/>
        <path d="M18 104V42h56v62" fill="none" stroke="#0b2a66" stroke-width="5" opacity="0.75" stroke-linejoin="round"/>
        <path d="M18 58h56" stroke="#0b2a66" stroke-width="5" opacity="0.35" stroke-linecap="round"/>
        <path d="M18 78h40" stroke="#0b2a66" stroke-width="5" opacity="0.35" stroke-linecap="round"/>
        <text x="122" y="72" fill="#0b2a66" class="mono">T-H-O-M-A-S</text>
      </g>

      <text x="140" y="70" fill="#0b2a66" class="h2">Buchstabieren</text>
      <text x="26" y="132" fill="#0b2a66" opacity="0.86" class="txt">Namen hören &amp; schreiben</text>
      <text x="26" y="168" fill="#0b2a66" opacity="0.86" class="txt">Vokale ergänzen</text>
      <text x="26" y="204" fill="#0b2a66" opacity="0.86" class="txt">Nachsprechen (Aussprache)</text>
      <text x="26" y="260" fill="#0b2a66" opacity="0.70" class="small">Fokus: Alphabet • Vokale • Hörverstehen</text>
    </g>

    <!-- Card 3: Grammatik -->
    <g transform="translate(1060, 440)">
      <rect rx="22" ry="22" width="420" height="290" fill="#ffffff" opacity="0.93"/>
      <rect rx="22" ry="22" width="420" height="290" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>

      <!-- Icon: question mark -->
      <g transform="translate(26,26)">
        <rect x="0" y="22" width="92" height="92" rx="16" fill="#eafff4"/>
        <path d="M46 48c0-10 8-18 20-18s20 7 20 18c0 9-5 14-13 18-8 4-10 7-10 14"
              fill="none" stroke="#0b2a66" stroke-width="6" opacity="0.8" stroke-linecap="round"/>
        <circle cx="63" cy="104" r="5" fill="#0b2a66" opacity="0.65"/>
      </g>

      <text x="140" y="70" fill="#0b2a66" class="h2">W-Fragen</text>
      <text x="26" y="132" fill="#0b2a66" opacity="0.86" class="txt">Wie? Woher? – Antworten</text>
      <text x="26" y="168" fill="#0b2a66" opacity="0.86" class="txt">du / Sie (formell vs. informell)</text>
      <text x="26" y="204" fill="#0b2a66" opacity="0.86" class="txt">kommen, heißen, sein</text>
      <text x="26" y="260" fill="#0b2a66" opacity="0.70" class="small">Fokus: Ich heiße … / Ich komme aus …</text>
    </g>
  </g>

  <!-- Footer -->
  <text x="160" y="835" fill="#ffffff" opacity="0.92" class="small">
    A1 Deutsch • Kapitelstart • Begrüßen &amp; Vorstellen • Hörverstehen &amp; Grammatik
  </text>
  <text x="1490" y="835" text-anchor="end" fill="#ffffff" opacity="0.78" class="small">
    © Mahwixh & Maxub
  </text>
</svg>

    --{{0}}--

!?[](https://github.com/Masub27/A1-German-Tool/blob/main/chapter_1.mp4?raw=true)




# Guten Tag! Ich heiße …

 ## Welche Antwort passt? Ordnen Sie zu.

  ### Gespräch A:

1. Woher kommen Sie, Frau Larsson?  
2. Wie ist Ihr Familienname?  
3. Guten Tag, ich heiße Angelika Kessler.

[[3]]  Guten Tag, Frau Kessler. Ich heiße Emma.  
[[2]]  Mein Familienname ist Larsson.  
[[1]]  Ich komme aus Stockholm.

---

  ### Gespräch B:

1. Hallo! Ich heiße Bojan. Wie heißt du?  
2. Ich komme aus Warna. Und du?

[[2]]  Ich komme aus Split.  
[[1]]  Hallo Bojan! Ich bin Lea. Woher kommst du?

---

  ## Sortieren und schreiben Sie die Gespräche A und B aus 1a.  
>Hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/KursDaF_A1_UEB_Track_001.mp3?raw=true)

  ### Gespräch A:
* [[ Guten Tag, ich heiße Angelika Kessler]] 
* [[Guten Tag, Frau Kessler. Ich heiße Emma]] 
* [[Wie ist Ihr Familienname? ]]  
* [[Mein Familienname ist Larsson]] 
* [[ Woher kommen Sie, Frau Larsson? ]] 
* [[Ich komme aus Stockholm]] 

  ### Gespräch B:

  ?[](https://github.com/Masub27/A1-German-Tool/blob/main/KursDaF_A1_UEB_Track_002.mp3?raw=true)

* [[Hallo! Ich heiße Bojan. Wie heißt du?]] 
* [[Hallo Bojan! Ich bin Lea. Woher kommst du? ]]  
* [[Ich komme aus Warna. Und du?]]  
* [[Ich komme aus Split]]  

---

  ## Welches Gespräch ist formell, welches Gespräch ist informell?

Gespräch A: [[Formell]]

Gespräch B: [[Informell]]

---

  ## Wie schreibt man das?

   ### Buchstabieren Sie die Namen.  
>Hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/KursDaF_A1_UEB_Track_003.mp3?raw=true)

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

   ?[](https://github.com/Masub27/A1-German-Tool/blob/main/KursDaF_A1_UEB_Track_004.mp3?raw=true)


1)  [[J]]ochen    Schnei[[d]]er 

2) Va[[l]]en[[t]]in[[a]]   P[[a]]len[[z]] 

3) Chri[[s]][[t]]tian    Bü[[c]][[h]]el 

4) Ale[[x]]and[[r]]a    W[[a]]nn[[e]]r  

---

  ## Hören Sie und schreiben Sie die Namen.

  ?[](https://github.com/Masub27/A1-German-Tool/blob/main/KursDaF_A1_UEB_Track_005.mp3?raw=true)

1) [[Paula Koch]] 

2) [[Anna Hausmann]]

3) [[Leon Wagner]] 

4) [[Michael Schneider]] 

---

   ## Hören Sie und ergänzen Sie die Vokale.  
>Sprechen Sie dann nach.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_006.mp3?raw=true)

1)  Hall[[o]]! [[I]]ch h[[e]][[i]]ße Lin.  

2)  [[I]]ch b[[i]] neu hier [[i]]m Deutschk[[u]]rs.  
 
3)  [[I]]ch k[[o]]mme aus Ch[[i]]na.  

4) [[U]]nd d_[[u]], woh[[e]]r  k[[o]]mmst d[[u]]?

---

  ## Hören Sie und schreiben Sie.  Beantworten Sie dann die Fragen.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_007.mp3?raw=true)

1. [[Hallo]]
2. [[Ich heiße Luis]]
3. [[Ich komme aus Spanien]]
4. [[Wie heißt du?]]
5. [[Woher kommst du?]]



# 3 GRAMMATIK KOMPAKT  
  ### W-Fragen und Antworten

  ### Was passt? Ergänzen Sie.

**Wörter:** 

>Woher · Wie · Wie · Wie · ist · komme · heiße

1. Wie heißen Sie? ☐ Ich [[heiße]] Schulz.

2. ...  [[Wie]] ist Ihr Vorname? ☐ Mein Vorname [[ist]]Thomas.

3. ... [[Wie]] schreibt man das? ☐ T-H-O-M-A-S.

4.  .[[Woher]]  kommen Sie? ☐ Ich [[komme]] aus Deutschland.

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

3) [[Niklas kommt aus der Schweiz]]

4)  [[Noah kommt aus Frankreich]]

5)  [[Jean kommt aus Luxemburg]]

6)  [[Wout kommt aus Belgien]]

7)  [[Anouk kommt aus den Niederlanden]]

8)  [[Mette kommt aus Dänemark]]

9)  [[Arek kommt aus Polen]]

10)  [[Jaromír kommt aus Tschechien]]

11)  [[Luisa kommt aus Portugal]]

12)  [[Enikö kommt aus Ungarn]]


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

---

  ## 3 Wer ist das?

 ###  Schreiben Sie die Sätze.  Achten Sie auf Groß- und Kleinschreibung.

1. dasistsandrahofer.
2. siekommtausdeutschland.
3. siewohntinmünchenundstudiertmedizin.
4. sandrasprichtdeutsch,französischundenglisch

1) Das ist Sandra Hofer.

2) [[Sie kommt aus Deutschland]]

3) [[Sie wohnt in München und studiert Medizin]]

4) [[Sandra spricht Deutsch, Französisch und Englisch]]






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



# 1 Hallo! Wie geht es dir?

   ###  Welche Wörter passen? Ergänzen Sie.

**Wörter:**  
Auf Wiedersehen · Bis bald · Bis morgen · Guten Morgen · Guten Tag · Hallo · Tschüss

**Begrüßung:** [[Guten Morgen, Guten Tag, Hallo!]]

**Verabschiedung:** [[Auf Wiedersehen, Bis bald.Bis morgen,Tschüss]]


---

  ## Ergänzen Sie das Gespräch und hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_009.mp3?raw=true)

**Sätze:**  
Bis morgen. Tschüss! · Es geht so. Ich arbeite viel. · Hallo, Wie geht es dir? · Ja, ich komme zum Kurs.

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

---

  ## 2 AUSSPRACHE   Satzmelodie

   ### Hören Sie eine Frage (Question) oder eine Antwort (.)?  Ergänzen Sie die Satzzeichen.

   ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_010.mp3?raw=true)

1. Wie geht es dir [[Question]] 
2. Mir geht es super[[.]]  
3. Wo wohnst du[[Question]] 
4. Ich wohne in Berlin[[.]] 
5. Wohnst du in Berlin[[Question]] 
6. Sprechen Sie Deutsch[[Question]]  


---

   ###  Wo ist die Satzmelodie besonders? Kreuzen Sie an.

  [[ ]]  W-Frage  
 [[x]] Ja/Nein-Frage  
[[ ]]  Aussage  

---

   ## 3 GRAMMATIK KOMPAKT  
   ### W-Fragen, Ja/Nein-Fragen, Antworten / Aussagen

   ### a Schreiben Sie W-Fragen und Antworten.

1. • geht · Ihnen · es · wie · ?  
   [[Wie geht es Ihnen?]]

   ○ geht · gut · mir · es ·  
   [[Mir geht es gut.]]

2. • heißen · Sie · wie · ?  
   [[Wie heißen Sie? ]] 

   ○ heiße · Sarah Girard · ich · .  
   [[Ich heiße Sarah Girard.]]

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

   ###  Schreiben Sie als Wort und als Zahl.

1. und · ßig · drei · drei  
    [[dreiunddreißig]]
    [[57]]

2. sie · fünf · zig · und · ben  
   [[siebenundfünfzig]]  [[57]]

3. zwan · sie · zig · und · ben  
    [[siebenundzwanzig]] 
    [[27]] 

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

1. sechsundfünfzig [[56]]
2. dreiundsechzig [[63]] 
3. sechsundachtzig [[86]] 

4. dreihundertvierundsiebzig [[374]] 
5. eintausendsiebenundzwanzig [[1027]] 
6. viertausenddreihundertneunzehn [[4319]]

---

  ## Was hören Sie?  Notieren Sie die Telefonnummern.

  ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_012.mp3?raw=true)

1) [[082481999]]

2) [[03515482380]]

3) [[03017741228]] 

4) [[01736934876]]

5) [[0158514023]]

6) [[0941351861]] 

---

# Studium international

 ##  Studierende aus Deutschland in der Welt

 ###  Lesen Sie die Porträts schnell.  Wo sind die Personen?  Schreiben Sie in die Weltkarte.

![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um10.50.12.png?raw=true)

1. [[Merle]]
2. [[Timo]]
3. [[Zeynep]]
4. [[Piotr und Stefan]]

---
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

## END

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bgEndCh1" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0b2a66"/>
      <stop offset="1" stop-color="#4fa3ff"/>
    </linearGradient>

    <linearGradient id="panelEndCh1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0.96"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0.86"/>
    </linearGradient>

    <filter id="shadowEndCh1" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="14" stdDeviation="16" flood-color="#001736" flood-opacity="0.35"/>
    </filter>

    <style><![CDATA[
      .title{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:900; font-size:76px;}
      .subtitle{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:600; font-size:30px;}
      .chip{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:750; font-size:22px;}
      .small{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; font-weight:550; font-size:18px;}
    ]]></style>
  </defs>

  <rect width="1600" height="900" fill="url(#bgEndCh1)"/>
  <circle cx="1350" cy="180" r="220" fill="#ffffff" opacity="0.10"/>
  <circle cx="260" cy="760" r="260" fill="#ffffff" opacity="0.08"/>

  <g filter="url(#shadowEndCh1)">
    <rect x="110" y="110" rx="28" ry="28" width="1380" height="680" fill="url(#panelEndCh1)"/>
  </g>

  <rect x="110" y="110" rx="28" ry="28" width="1380" height="130" fill="#ffffff" opacity="0.22"/>
  <rect x="110" y="240" width="1380" height="2" fill="#0b2a66" opacity="0.12"/>

  <rect x="160" y="150" rx="22" ry="22" width="260" height="44" fill="#0b2a66" opacity="0.95"/>
  <text x="290" y="180" text-anchor="middle" fill="#ffffff" class="chip">KAPITEL 1 • ENDE</text>

  <text x="160" y="360" fill="#0b2a66" class="title">Danke!</text>
  <text x="160" y="415" fill="#0b2a66" opacity="0.85" class="subtitle">Kapitel 1 abgeschlossen</text>

  <text x="160" y="835" fill="#0b2a66" opacity="0.60" class="small">A1 Deutsch • LiaScript</text>
</svg>

