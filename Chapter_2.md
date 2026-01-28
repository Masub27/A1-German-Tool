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
    © Mahwixh & Maxub
  </text>
</svg>

   --{{0}}--
In this chapter, you will learn important university vocabulary and basic grammar.
You will practice pronunciation and listening with short dialogues and messages.
You will learn how to use articles, plurals, and simple pronouns.
Let’s get started and learn German step by step.


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
