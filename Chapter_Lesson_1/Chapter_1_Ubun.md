
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


# 🤖 German  Bot

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
        <h2 style="margin:0;color:#2f6fd1;">A1.1 Deutsch Lern-Bot</h2>
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


# Guten Tag! Ich heiße …

 ## Welche Antwort passt? Ordnen Sie zu.

  ### Gespräch A:

1. Woher kommen Sie, Frau Larsson?  
2. Wie ist Ihr Familienname?  
3. Guten Tag, ich heiße Angelika Kessler.

1. 😊 [[3]]  Guten Tag, Frau Kessler. Ich heiße Emma. 
[[?]] Richtige Antwort: **3**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

2. 😊[[2]]  Mein Familienname ist Larsson.  
[[?]] Richtige Antwort: **2**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

3. 😊[[1]]  Ich komme aus Stockholm.
[[?]] Richtige Antwort: **1**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

---

  ### Gespräch B:

1. Hallo! Ich heiße Bojan. Wie heißt du?  
2. Ich komme aus Warna. Und du?

1. 😊[[2]]  Ich komme aus Split.  
[[?]] Richtige Antwort: **2**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

2. 😊[[1]]  Hallo Bojan! Ich bin Lea. Woher kommst du?
[[?]] Richtige Antwort: **1**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

---

  ## Sortieren und schreiben Sie die Gespräche A und B aus 1a.  
>Hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_001.mp3?raw=true)

  ### Gespräch A:
* [[ Guten Tag, ich heiße Angelika Kessler]] 
[[?]] Richtige Antwort: **Guten Tag, ich heiße Angelika Kessler**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
* [[Guten Tag, Frau Kessler. Ich heiße Emma]] 
[[?]] Richtige Antwort: **Guten Tag, Frau Kessler. Ich heiße Emma**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
* [[Wie ist Ihr Familienname? ]]  
[[?]] Richtige Antwort: **Wie ist Ihr Familienname?**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
* [[Mein Familienname ist Larsson]] 
[[?]] Richtige Antwort: **Mein Familienname ist Larsson**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
* [[ Woher kommen Sie, Frau Larsson? ]] 
[[?]] Richtige Antwort: **Woher kommen Sie, Frau Larsson?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
* [[Ich komme aus Stockholm]] 
[[?]] Richtige Antwort: **Ich komme aus Stockholm**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

  ### Gespräch B:

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_002.mp3?raw=true)

* [[Hallo! Ich heiße Bojan. Wie heißt du?]] 
[[?]] Richtige Antwort: **Hallo! Ich heiße Bojan. Wie heißt du?**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
* [[Hallo Bojan! Ich bin Lea. Woher kommst du? ]]  
[[?]] Richtige Antwort: **Hallo Bojan! Ich bin Lea. Woher kommst du?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
* [[Ich komme aus Warna. Und du?]]  
[[?]] Richtige Antwort: **Ich komme aus Warna. Und du?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
* [[Ich komme aus Split]]  
[[?]] Richtige Antwort: **Ich komme aus Split**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

---

  ## Welches Gespräch ist formell, welches Gespräch ist informell?

Gespräch A: [[Formell]]
[[?]] Richtige Antwort: **Formell**. Gespräch A benutzt die höfliche Form, Gespräch B benutzt die informelle Form.

Gespräch B: [[Informell]]
[[?]] Richtige Antwort: **Informell**. Gespräch A benutzt die höfliche Form, Gespräch B benutzt die informelle Form.

---

  ## Wie schreibt man das?

   ### Buchstabieren Sie die Namen.  
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

---

  ## Hören Sie und schreiben Sie die Namen.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_005.mp3?raw=true)

1) [[Paula Koch]] 
[[?]] Richtige Antwort: **Paula Koch**. Diese Antwort passt zum Kontext der Aufgabe.

2) [[Anna Hausmann]]
[[?]] Richtige Antwort: **Anna Hausmann**. Diese Antwort passt zum Kontext der Aufgabe.

3) [[Leon Wagner]] 
[[?]] Richtige Antwort: **Leon Wagner**. Diese Antwort passt zum Kontext der Aufgabe.

4) [[Michael Schneider]] 
[[?]] Richtige Antwort: **Michael Schneider**. Diese Antwort passt zum Kontext der Aufgabe.

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

---

  ## Hören Sie und schreiben Sie.  Beantworten Sie dann die Fragen.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_007.mp3?raw=true)

1. [[Hallo]]
[[?]] Richtige Antwort: **Hallo**. Diese Antwort passt zum Kontext der Aufgabe.
2. [[Ich heiße Luis]]
[[?]] Richtige Antwort: **Ich heiße Luis**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
3. [[Ich komme aus Spanien]]
[[?]] Richtige Antwort: **Ich komme aus Spanien**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
4. [[Wie heißt du?]]
[[?]] Richtige Antwort: **Wie heißt du?**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
5. [[Woher kommst du?]]
[[?]] Richtige Antwort: **Woher kommst du?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.



# 3 GRAMMATIK KOMPAKT  
  ### W-Fragen und Antworten

  ### Was passt? Ergänzen Sie.

**Wörter:** 

>Woher · Wie · Wie · Wie · ist · komme · heiße

1. Wie heißen Sie? ☐ Ich [[heiße]] Schulz.
[[?]] Richtige Antwort: **heiße**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

2. ...  [[Wie]] ist Ihr Vorname? ☐ Mein Vorname [[ist]]Thomas.
[[?]] Richtige Antwort: **Wie / ist**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

3. ... [[Wie]] schreibt man das? ☐ T-H-O-M-A-S.
[[?]] Richtige Antwort: **Wie**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.

4.  .[[Woher]]  kommen Sie? ☐ Ich [[komme]] aus Deutschland.
[[?]] Richtige Antwort: **Woher / komme**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

---

  ##  Schreiben Sie sechs Fragen.

| W-Frage | Verb (du / Sie) | Ergänzung | ? |
|-------|----------------|-----------|---|
| Wie   | heißen / heißt | Ihr Vorname / dein Vorname | ? |
| Wie   | ist            | Ihr Familienname / dein Familienname | ? |
| Woher | kommen / kommst| Sie / du  | ? |



1)  Wie heißt du? 

2)  [[Wie heißen Sie? ]]
[[?]] Richtige Antwort: **Wie heißen Sie?**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

3)  [[Wie ist dein Vorname?]]
[[?]] Richtige Antwort: **Wie ist dein Vorname?**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

4)  [[Wie ist Ihr Familienname?]]
[[?]] Richtige Antwort: **Wie ist Ihr Familienname?**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

5)  [[Woher kommst du?]]
[[?]] Richtige Antwort: **Woher kommst du?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

6)  [[Woher kommen Sie?]]
[[?]] Richtige Antwort: **Woher kommen Sie?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

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
[[?]] Richtige Antwort: **heiße**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
   Und wie [[heißen]] Sie?
[[?]] Richtige Antwort: **heißen**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

2. Ich [[heiße]] Ferenc Simon. Ferenc [[ist]]  
[[?]] Richtige Antwort: **heiße / ist**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
   mein Vorname und Simon mein [[Familienname]].
[[?]] Richtige Antwort: **Familienname**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

3. Wie [[buchstabiert]] man das?  
[[?]] Richtige Antwort: **buchstabiert**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.
   ° F-E-R-E-N-C S-I-M-O-N.

4. Woher [[kommen]] Sie, Herr Simon?
[[?]] Richtige Antwort: **kommen**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

5. Ich komme [[aus]][[Ungarn]]. Und Sie?
[[?]] Richtige Antwort: **aus / Ungarn**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

6. Ich [[komme]] aus Portugal.
[[?]] Richtige Antwort: **komme**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.




# Informationen

 ## Ergänzen Sie **er** oder **sie** (Singular oder Plural).

1. Nicole kommt aus Kamerun. [[sie]] wohnt jetzt in Leipzig.  
[[?]] Richtige Antwort: **sie**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
2. Gabriel wohnt in Berlin. [[Er]] arbeitet schon.  
[[?]] Richtige Antwort: **Er**. Das ist die richtige Form von „wohnen“ für das Subjekt.
3. Eivor und Fynn sind aus Schweden. [[Sie]] wohnen in Potsdam.  
[[?]] Richtige Antwort: **Sie**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
4. Sarah und Dana sind neu im Deutschkurs. [[Sie]] lernen Deutsch.  
[[?]] Richtige Antwort: **Sie**. Das ist die richtige Form von „sein“ für das Subjekt.
5. Sarah kommt aus Frankreich. [[Sie]] wohnt jetzt in Deutschland.  
[[?]] Richtige Antwort: **Sie**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
6. Frau Klein ist Deutschlehrerin. [[Sie]] kommt aus Deutschland.  
[[?]] Richtige Antwort: **Sie**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
7. Herr Klein ist Architekt. [[Er]] wohnt in Berlin.  
[[?]] Richtige Antwort: **Er**. Das ist die richtige Form von „sein“ für das Subjekt.
8. Tina studiert Germanistik. [[Sie]] spricht Englisch, Französisch und Deutsch.
[[?]] Richtige Antwort: **Sie**. Das ist die richtige Form von „sein“ für das Subjekt.

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
[[?]] Richtige Antwort: **4**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

b. [[6]] Wir studieren Medizin. 
[[?]] Richtige Antwort: **6**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

c. [[3]] Ich spreche Französisch und Englisch. 
[[?]] Richtige Antwort: **3**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

d. [[8]] Wir wohnen in Potsdam. 
[[?]] Richtige Antwort: **8**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

e. [[7]] Wir sprechen Schwedisch und Dänisch. 
[[?]] Richtige Antwort: **7**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

f. [[2]] Ich studiere Informatik. 
[[?]] Richtige Antwort: **2**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

g. [[1]] Ich komme aus Kamerun. 
[[?]] Richtige Antwort: **1**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

h. [[5]] Wir kommen aus Schweden.
[[?]] Richtige Antwort: **5**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

---

 ## GRAMMATIK KOMPAKT  
 ### Verben im Präsens

 ### a Ergänzen Sie die Pronomen und Verbformen.

|        | sein | wohnen | heißen | arbeiten | sprechen |
|------|------|--------|--------|----------|----------|
| ich  | bin  | wohne  |    [[heiße]]    |     [[arbeite]]       | spreche  |
[[?]] Richtige Antwort: **heiße / arbeite**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
| du   |    [[bist]]    |     [[wohnst]]     |    [[heißt]]      | arbeitest| sprichst |
[[?]] Richtige Antwort: **bist / wohnst / heißt**. Das ist die richtige Form von „sein“ für das Subjekt.
| er / sie / es | ist | wohnt | heißt | arbeitet |     [[spricht]]       |
[[?]] Richtige Antwort: **spricht**. Das ist die richtige Form von „sein“ für das Subjekt.
| wir  | sind |    [[wohnen]]      |     [[heißen]]     |      [[arbeiten]]      |    [[sprechen]]        |
[[?]] Richtige Antwort: **wohnen / heißen / arbeiten / sprechen**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.
| ihr  | seid |     [[wohnt]]     | heißt  |     [[arbeitet]]       |     sprecht     |
[[?]] Richtige Antwort: **wohnt / arbeitet**. Das ist die richtige Form von „sein“ für das Subjekt.
| sie / Sie |    [[sind]]    |    [[wohnen]]      |     [[heißen]]    | arbeiten |   [[sprechen]]     |
[[?]] Richtige Antwort: **sind / wohnen / heißen / sprechen**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

---

  ##  Ergänzen Sie die passenden Verbformen.

1. Wer [[ist]] Frau Klein?  
[[?]] Richtige Antwort: **ist**. Das ist die richtige Form von „sein“ für das Subjekt.
   ○ Sie [[ist]] meine Deutschlehrerin. *(sein)*
[[?]] Richtige Antwort: **ist**. Das ist die richtige Form von „sein“ für das Subjekt.

2. Woher [[kommt]] Nicole?  
[[?]] Richtige Antwort: **kommt**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
   ○ Sie [[kommt]] aus Kamerun. *(kommen)*
[[?]] Richtige Antwort: **kommt**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

3. Was [[studieren]] Fynn und Eivor?  
[[?]] Richtige Antwort: **studieren**. Diese Antwort passt zum Studienfach oder Beruf im Text.
   ○ Sie [[studieren]] Medizin. *(studieren)*
[[?]] Richtige Antwort: **studieren**. Diese Antwort passt zum Studienfach oder Beruf im Text.

4. Wie [[heißt]] du?  
[[?]] Richtige Antwort: **heißt**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.
   ○ Ich [[heiße]] Gabriel. *(heißen)*
[[?]] Richtige Antwort: **heiße**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

5. Welche Sprache [[lernst]] du?  
[[?]] Richtige Antwort: **lernst**. Das ist die richtige Form von „lernen“ für das Subjekt.
   ○ Ich [[lerne]] Deutsch. *(lernen)*
[[?]] Richtige Antwort: **lerne**. Das ist die richtige Form von „lernen“ für das Subjekt.

6. Wo [[wohnt]] ihr?  
[[?]] Richtige Antwort: **wohnt**. Das ist die richtige Form von „wohnen“ für das Subjekt.
   ○ Wir [[wohnen]] in Potsdam. *(wohnen)*
[[?]] Richtige Antwort: **wohnen**. Das ist die richtige Form von „wohnen“ für das Subjekt.

7. Welche Sprachen [[sprichst]] du?  
[[?]] Richtige Antwort: **sprichst**. Das ist die richtige Form von „sprechen“ für das Subjekt.
   ○ Ich [[spreche]] Englisch und Polnisch. *(sprechen)*
[[?]] Richtige Antwort: **spreche**. Das ist die richtige Form von „sprechen“ für das Subjekt.

8. Welche Sprache [[lernt]] ihr?  
[[?]] Richtige Antwort: **lernt**. Das ist die richtige Form von „lernen“ für das Subjekt.
   ○ Wir [[lernen]] Deutsch. *(lernen)*
[[?]] Richtige Antwort: **lernen**. Das ist die richtige Form von „lernen“ für das Subjekt.

9. Was [[studiert]] Laura?  
[[?]] Richtige Antwort: **studiert**. Diese Antwort passt zum Studienfach oder Beruf im Text.
   ○ Laura [[studiert]] Germanistik. *(studieren)*
[[?]] Richtige Antwort: **studiert**. Das ist die richtige Form von „sein“ für das Subjekt.

10. Was [[lernt]] Laura?  
[[?]] Richtige Antwort: **lernt**. Das ist die richtige Form von „lernen“ für das Subjekt.
    ○ Laura [[lernt]] Englisch. *(lernen)*
[[?]] Richtige Antwort: **lernt**. Das ist die richtige Form von „lernen“ für das Subjekt.

---

  ## 3 Wer ist das?

 ###  Schreiben Sie die Sätze.  Achten Sie auf Groß- und Kleinschreibung.

1. dasistsandrahofer.
2. siekommtausdeutschland.
3. siewohntinmünchenundstudiertmedizin.
4. sandrasprichtdeutsch,französischundenglisch

1) Das ist Sandra Hofer.

2) [[Sie kommt aus Deutschland]]
[[?]] Richtige Antwort: **Sie kommt aus Deutschland**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

3) [[Sie wohnt in München und studiert Medizin]]
[[?]] Richtige Antwort: **Sie wohnt in München und studiert Medizin**. Das ist die richtige Form von „wohnen“ für das Subjekt.

4) [[Sandra spricht Deutsch, Französisch und Englisch]]
[[?]] Richtige Antwort: **Sandra spricht Deutsch, Französisch und Englisch**. Das ist die richtige Form von „sprechen“ für das Subjekt.






# Ergänzen Sie die passenden Verbformen.

**Verben:**  

>arbeiten · kommen · lernen · sein · sein · sprechen · wohnen

* Das [[ist]] (1) Ana Laura Ramirez.
[[?]] Richtige Antwort: **ist**. Das ist die richtige Form von „sein“ für das Subjekt.
*  Sie [[kommt]](2) aus Peru.  
[[?]] Richtige Antwort: **kommt**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
* Sie [[wohnt]] (3) in Lima.
[[?]] Richtige Antwort: **wohnt**. Das ist die richtige Form von „wohnen“ für das Subjekt.
*  Ana Laura [[arbeitet]] (4) schon.  
[[?]] Richtige Antwort: **arbeitet**. Diese Antwort passt zum Kontext der Aufgabe.
* Sie [[ist]] (5) Architektin.
[[?]] Richtige Antwort: **ist**. Das ist die richtige Form von „sein“ für das Subjekt.
*  Ana Laura [[spricht]] (6) Spanisch und Englisch.  
[[?]] Richtige Antwort: **spricht**. Das ist die richtige Form von „sprechen“ für das Subjekt.
* Sie [[lernt]] (7) jetzt Deutsch.
[[?]] Richtige Antwort: **lernt**. Das ist die richtige Form von „lernen“ für das Subjekt.


---

  ## Schreiben Sie die Sätze.  
Achten Sie auf Groß- und Kleinschreibung.

1. Austin · sind · und · das · Shannon ·  
[[Das sind Austin und Shannon.]]
[[?]] Richtige Antwort: **Das sind Austin und Shannon.**. Das ist die richtige Form von „sein“ für das Subjekt.

2. den · aus · kommen · sie · USA ·  
[[Sie kommen aus den USA.]]
[[?]] Richtige Antwort: **Sie kommen aus den USA.**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

3. neu · sind · Deutschkurs · im · sie ·  

[[Sie sind neu im Deutschkurs.]]
[[?]] Richtige Antwort: **Sie sind neu im Deutschkurs.**. Das ist die richtige Form von „sein“ für das Subjekt.
4. Elektrotechnik · Informatik · studieren · und · sie ·  
[[Sie studieren Elektrotechnik und Informatik.]]
[[?]] Richtige Antwort: **Sie studieren Elektrotechnik und Informatik.**. Diese Antwort passt zum Studienfach oder Beruf im Text.

---

 

  


  ## WORTBILDUNG  
Ergänzen Sie die Sprachen mit der Endung **-isch**.

1. Ungarn →  [[Ungarisch]]
[[?]] Richtige Antwort: **Ungarisch**. Diese Antwort passt zum Kontext der Aufgabe.
2. Spanien → [[Spanisch]] 
[[?]] Richtige Antwort: **Spanisch**. Diese Antwort passt zum Kontext der Aufgabe.
3. Schweden → [[Schwedisch]] 
[[?]] Richtige Antwort: **Schwedisch**. Diese Antwort passt zum Kontext der Aufgabe.
4. Dänemark → [[Dänisch]] 
[[?]] Richtige Antwort: **Dänisch**. Diese Antwort passt zum Kontext der Aufgabe.
5. Portugal → [[Portugiesisch]] 
[[?]] Richtige Antwort: **Portugiesisch**. Diese Antwort passt zum Kontext der Aufgabe.
6. Frankreich → [[Französisch]] 
[[?]] Richtige Antwort: **Französisch**. Diese Antwort passt zum Kontext der Aufgabe.



# 1 Hallo! Wie geht es dir?

   ###  Welche Wörter passen? Ergänzen Sie.

**Wörter:**  
Auf Wiedersehen · Bis bald · Bis morgen · Guten Morgen · Guten Tag · Hallo · Tschüss

**Begrüßung:** [[Guten Morgen, Guten Tag, Hallo!]]
[[?]] Richtige Antwort: **Guten Morgen, Guten Tag, Hallo!**. Diese Antwort passt zum Kontext der Aufgabe.

**Verabschiedung:** [[Auf Wiedersehen, Bis bald.Bis morgen,Tschüss]]
[[?]] Richtige Antwort: **Auf Wiedersehen, Bis bald.Bis morgen,Tschüss**. Diese Antwort passt zum Kontext der Aufgabe.


---

  ## Ergänzen Sie das Gespräch und hören Sie dann zur Kontrolle.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_009.mp3?raw=true)

**Sätze:**  
Bis morgen. Tschüss! · Es geht so. Ich arbeite viel. · Hallo, Wie geht es dir? · Ja, ich komme zum Kurs.

1. •  [[Hallo, Wie geht es dir?]]
[[?]] Richtige Antwort: **Hallo, Wie geht es dir?**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.
   ○ Mir geht es super. Und dir?

2. • [[Es geht so. Ich arbeite viel.]] 
[[?]] Richtige Antwort: **Es geht so. Ich arbeite viel.**. Diese Antwort passt zum Kontext der Aufgabe.
   ○ Kommst du morgen Abend zum Deutschkurs?

3. • [[ Ja, ich komme zum Kurs.]]
[[?]] Richtige Antwort: **Ja, ich komme zum Kurs.**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
   ○ Schön. Bis morgen!

4. • [[Bis morgen. Tschüss!]]
[[?]] Richtige Antwort: **Bis morgen. Tschüss!**. Diese Antwort passt zum Kontext der Aufgabe.

---

   ## Wie geht es dir? Ordnen Sie zu.

* Es geht mir (sehr) gut. / Mir geht es (sehr) gut.  
* Es geht mir nicht so gut. / Mir geht es nicht so gut.  
* Es geht (so).  
* Es geht mir super. / Mir geht es super.

1. 🙂  [[Es geht mir (sehr) gut. / Mir geht es (sehr) gut.  ]]
[[?]] Richtige Antwort: **Es geht mir (sehr) gut. / Mir geht es (sehr) gut.**. Diese Antwort passt zum Kontext der Aufgabe.
2.  🤩  [[Es geht mir super. / Mir geht es super.]]
[[?]] Richtige Antwort: **Es geht mir super. / Mir geht es super.**. Diese Antwort passt zum Kontext der Aufgabe.
3. 😐  [[Es geht (so). ]] 
[[?]] Richtige Antwort: **Es geht (so).**. Diese Antwort passt zum Kontext der Aufgabe.
4. ☹️  [[Es geht mir nicht so gut. / Mir geht es nicht so gut. ]]
[[?]] Richtige Antwort: **Es geht mir nicht so gut. / Mir geht es nicht so gut.**. Diese Antwort passt zum Kontext der Aufgabe.

---

  ## 2 AUSSPRACHE   Satzmelodie

   ### Hören Sie eine Frage (Question) oder eine Antwort (.)?  Ergänzen Sie die Satzzeichen.

 ?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_010.mp3?raw=true)

1. Wie geht es dir [[Question]] 
[[?]] Richtige Antwort: **Question**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.
2. Mir geht es super[[.]]  
[[?]] Richtige Antwort: **.**. Diese Antwort passt zum Kontext der Aufgabe.
3. Wo wohnst du[[Question]] 
[[?]] Richtige Antwort: **Question**. Das ist die richtige Form von „wohnen“ für das Subjekt.
4. Ich wohne in Berlin[[.]] 
[[?]] Richtige Antwort: **.**. Das ist die richtige Form von „wohnen“ für das Subjekt.
5. Wohnst du in Berlin[[Question]] 
[[?]] Richtige Antwort: **Question**. Das ist die richtige Form von „wohnen“ für das Subjekt.
6. Sprechen Sie Deutsch[[Question]]  
[[?]] Richtige Antwort: **Question**. Das ist die richtige Form von „sprechen“ für das Subjekt.


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
[[?]] Richtige Antwort: **Wie geht es Ihnen?**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.

   ○ geht · gut · mir · es ·  
   [[Mir geht es gut.]]
[[?]] Richtige Antwort: **Mir geht es gut.**. Diese Antwort passt zum Kontext der Aufgabe.

2. • heißen · Sie · wie · ?  
   [[Wie heißen Sie? ]] 
[[?]] Richtige Antwort: **Wie heißen Sie?**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

   ○ heiße · Sarah Girard · ich · .  
   [[Ich heiße Sarah Girard.]]
[[?]] Richtige Antwort: **Ich heiße Sarah Girard.**. Diese Antwort passt zur Frage nach Name, Vorname oder Familienname.

3. • im Sprachenzentrum · was · ihr · macht · ?  
   [[Was macht ihr im Sprachenzentrum?]]
[[?]] Richtige Antwort: **Was macht ihr im Sprachenzentrum?**. Achten Sie auf Fragewort, Verbposition und Fragezeichen.

   ○ zusammen · Polnisch · lernen · wir · 
   [[Wir lernen zusammen Polnisch.]]
[[?]] Richtige Antwort: **Wir lernen zusammen Polnisch.**. Das ist die richtige Form von „lernen“ für das Subjekt.




## Schreiben Sie Ja/Nein-Fragen und Antworten.

1. • Sie · Stuttgart · wohnen · in · ?  
   [[Wohnen Sie in Stuttgart?]]
[[?]] Richtige Antwort: **Wohnen Sie in Stuttgart?**. Das ist die richtige Form von „wohnen“ für das Subjekt.
   ○ nein · Tübingen · wohne · in · ich · .  
   [[Nein, ich wohne in Tübingen.]]
[[?]] Richtige Antwort: **Nein, ich wohne in Tübingen.**. Das ist die richtige Form von „sein“ für das Subjekt.

2. • Tübingen · Sie · arbeiten · in · ?  
   [[Arbeiten Sie in Tübingen?]] 
[[?]] Richtige Antwort: **Arbeiten Sie in Tübingen?**. Das ist die richtige Form von „sein“ für das Subjekt.
   ○ nein · Biologie · studiere · ich · .  
   [[Nein, ich studiere Biologie.]]
[[?]] Richtige Antwort: **Nein, ich studiere Biologie.**. Diese Antwort passt zum Studienfach oder Beruf im Text.

3. • ihr · heute Abend · zum Kurs · kommt · ?  
   [[Kommt ihr heute Abend zum Kurs?]]
[[?]] Richtige Antwort: **Kommt ihr heute Abend zum Kurs?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
   ○ ja · wir · kommen ·  
  [[Ja, wir kommen.]]
[[?]] Richtige Antwort: **Ja, wir kommen.**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.

---

   ## Ergänzen Sie jeweils die informelle und die formelle Frage.

1. • Wie heißt du? / Wie heißen Sie?  
   ○ Ich heiße Igor Smirnow.

2. • [[Studierst du Informatik?]]  [[Studieren Sie Informatik?]]  
[[?]] Richtige Antwort: **Studierst du Informatik? / Studieren Sie Informatik?**. Diese Antwort passt zum Studienfach oder Beruf im Text.
   ○ Ja. Ich studiere Informatik.

3. • [[Wo wohnst du?]]  [[Wo wohnen Sie?]]  
[[?]] Richtige Antwort: **Wo wohnst du? / Wo wohnen Sie?**. Das ist die richtige Form von „wohnen“ für das Subjekt.
   ○ Ich wohne in Hamburg.

4. • [[Woher kommst du?]]  [[Woher kommen Sie?]]   
[[?]] Richtige Antwort: **Woher kommst du? / Woher kommen Sie?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
   ○ Ich komme aus Russland.

5. • [[Wohnst du in Berlin?]]  [[Wohnen Sie in Berlin?]]  
[[?]] Richtige Antwort: **Wohnst du in Berlin? / Wohnen Sie in Berlin?**. Das ist die richtige Form von „wohnen“ für das Subjekt.
   ○ Nein. Wir wohnen in Potsdam.

6. • [[Kommst du morgen zum Kurs?]]  [[Kommen Sie morgen zum Kurs?]]   
[[?]] Richtige Antwort: **Kommst du morgen zum Kurs? / Kommen Sie morgen zum Kurs?**. Bei Herkunft benutzt man oft die Frage „Woher?“ und die Antwort mit „aus“.
   ○ Ja. Ich komme morgen zum Kurs.
 

---

   ##  Zahlen

   ###  Schreiben Sie als Wort und als Zahl.

1. und · ßig · drei · drei  
    [[dreiunddreißig]]
[[?]] Richtige Antwort: **dreiunddreißig**. Diese Antwort passt zum Kontext der Aufgabe.
    [[57]]
[[?]] Richtige Antwort: **57**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

2. sie · fünf · zig · und · ben  
   [[siebenundfünfzig]]  [[57]]
[[?]] Richtige Antwort: **siebenundfünfzig / 57**. Diese Antwort passt zum Kontext der Aufgabe.

3. zwan · sie · zig · und · ben  
    [[siebenundzwanzig]] 
[[?]] Richtige Antwort: **siebenundzwanzig**. Diese Antwort passt zum Kontext der Aufgabe.
    [[27]] 
[[?]] Richtige Antwort: **27**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

4. zig · und · neun · zwei  
   [[zweiundneunzig]]  [[92]]
[[?]] Richtige Antwort: **zweiundneunzig / 92**. Diese Antwort passt zum Kontext der Aufgabe.

5. und · zig · acht · sech  
   [[achtundsechzig]] [[68]]
[[?]] Richtige Antwort: **achtundsechzig / 68**. Diese Antwort passt zum Kontext der Aufgabe.

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
[[?]] Richtige Antwort: **56**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.
2. dreiundsechzig [[63]] 
[[?]] Richtige Antwort: **63**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.
3. sechsundachtzig [[86]] 
[[?]] Richtige Antwort: **86**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

4. dreihundertvierundsiebzig [[374]] 
[[?]] Richtige Antwort: **374**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.
5. eintausendsiebenundzwanzig [[1027]] 
[[?]] Richtige Antwort: **1027**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.
6. viertausenddreihundertneunzehn [[4319]]
[[?]] Richtige Antwort: **4319**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

---

  ## Was hören Sie?  Notieren Sie die Telefonnummern.

?[](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/KursDaF_A1_UEB_Track_012.mp3?raw=true)

1) [[082481999]]
[[?]] Richtige Antwort: **082481999**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

2) [[03515482380]]
[[?]] Richtige Antwort: **03515482380**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

3) [[03017741228]] 
[[?]] Richtige Antwort: **03017741228**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

4) [[01736934876]]
[[?]] Richtige Antwort: **01736934876**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

5) [[0158514023]]
[[?]] Richtige Antwort: **0158514023**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

6) [[0941351861]] 
[[?]] Richtige Antwort: **0941351861**. Das ist die richtige Zahl / Zuordnung in dieser Aufgabe.

---

# Studium international

 ##  Studierende aus Deutschland in der Welt

 ###  Lesen Sie die Porträts schnell.  Wo sind die Personen?  Schreiben Sie in die Weltkarte.

![](https://github.com/Masub27/A1-German-Tool/blob/main/Audio-UEB/Bildschirmfoto2023-06-15um10.50.12.png?raw=true)

1. [[Merle]]
[[?]] Richtige Antwort: **Merle**. Diese Antwort passt zum Kontext der Aufgabe.
2. [[Timo]]
[[?]] Richtige Antwort: **Timo**. Diese Antwort passt zum Kontext der Aufgabe.
3. [[Zeynep]]
[[?]] Richtige Antwort: **Zeynep**. Diese Antwort passt zum Kontext der Aufgabe.
4. [[Piotr und Stefan]]
[[?]] Richtige Antwort: **Piotr und Stefan**. Diese Antwort passt zum Kontext der Aufgabe.

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
[[?]] Richtige Antwort: **Shanghai / Barcelona / Kapstadt / Manaus**. Diese Form passt zur Tabelle und zur jeweiligen Person / Kategorie.

| **Sprachen**           | [[Deutsch]]       |  [[Deutsch]]     | [[Deutsch]]        | [[Deutsch]] |
[[?]] Richtige Antwort: **Deutsch / Deutsch / Deutsch / Deutsch**. Diese Form passt zur Tabelle und zur jeweiligen Person / Kategorie.
|                    | [[Chinesisch]]    | [[Spanisch]]     | [[Englisch]]       | [[Portugiesisch]] |
[[?]] Richtige Antwort: **Chinesisch / Spanisch / Englisch / Portugiesisch**. Diese Form passt zur Tabelle und zur jeweiligen Person / Kategorie.
|                    | [[Türkisch ]]     | [[Französisch]]  | [[Polnisch]]       | [[Spanisch]] |
[[?]] Richtige Antwort: **Türkisch / Französisch / Polnisch / Spanisch**. Diese Form passt zur Tabelle und zur jeweiligen Person / Kategorie.
|                    | [[Englisch]]      |              | [[Afrikaans]]      |        |
[[?]] Richtige Antwort: **Englisch / Afrikaans**. Diese Form passt zur Tabelle und zur jeweiligen Person / Kategorie.
|                    |               |              | [[Zulu ]]          |        |
[[?]] Richtige Antwort: **Zulu**. Diese Form passt zur Tabelle und zur jeweiligen Person / Kategorie.

| **Studienfach / Beruf**| [[Medizininformatik]] | [[Chemikerin]] |  [[Design]]        | [[Biologe]] |
[[?]] Richtige Antwort: **Medizininformatik / Chemikerin / Design / Biologe**. Diese Antwort passt zum Studienfach oder Beruf im Text.


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

