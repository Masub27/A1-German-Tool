
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

   --{{0}}--
Welcome to Chapter Three, In this chapter, you will learn food and dining vocabulary used at the university.
You will practice grammar with modal verbs like can, want, like, and would like.
You will improve listening skills through matching tasks and short exercises.
Let’s begin and explore everyday German step by step.

## Das essen Studierende in Deutschland

 ### Wie heißen die Gerichte? Was passt zusammen? Schreiben Sie.

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

 ###  Ergänzen Sie die passenden Formen von **können**.

1. Ich [[kann]] sehr gut kochen.  
2. Mia [[kann]] keine Milchprodukte essen.  
3. Du [[kannst]] in der Mensa günstig essen.  

4. Wir [[können]] sehr gut Keyboard spielen.  
5. Studierende [[können]] das Essen mitnehmen.  
6. .[[könnt]] ihr Spanisch sprechen?


---

 ###  Ergänzen Sie die passenden Formen von **wollen**.

1. Mia [[will]] kein Fleisch essen.  
2. Heute [[will]] ich lieber zu Hause essen.  
3. Wir [[Wollen]] heute Fußball schauen.  

4. Ihr [[wallt]] Physik studieren?  
5. Pit und Peter [[wollen]] heute Schnipo essen.  
6. .[[Willst]] du heute Hähnchen essen?

---


##  [GRAMMATIK KOMPAKT]  
 ### Modalverb **können** und **wollen** – Wortstellung

 ### Wo stehen die Verben? Schreiben Sie die Sätze in die Tabelle.

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





##  [WORTBILDUNG]  
 ## Nomen + Nomen = Nomen

---

 ###  Neue Wörter zusammensetzen. Ordnen Sie zu.

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


##  Was gibt es am Samstag?

 ### Welcher Tag fehlt? Ergänzen Sie.

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
  ### Achten Sie auf Groß- und Kleinschreibung.

**Wortliste:**  
*nehme · nimmst · nimmt · nehmen · nehmt · nehmen*



1. Was [[nehmt]] ihr?

2. Wir [[nehmen]] einen Butterkuchen und ein Franzbrötchen.

3. Ben [[nimmt]] ein Fischbrötchen.

4. .[[Nimmst]] du auch ein Fischbrötchen?

5. Nein, ich [[nehme]] ein Rundstück.

6. Ariane und Olga [[nehmen]] das Hamburg-Frühstück.

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

## END

<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="900" viewBox="0 0 1600 900">
  <defs>
    <linearGradient id="bgEnd" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0b2a66"/>
      <stop offset="0.55" stop-color="#3a7bd5"/>
      <stop offset="1" stop-color="#7fb7ff"/>
    </linearGradient>

    <linearGradient id="panelEnd" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0.96"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0.86"/>
    </linearGradient>

    <filter id="shadowEnd" x="-20%" y="-20%" width="140%" height="140%">
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

  <!-- Background -->
  <rect width="1600" height="900" fill="url(#bgEnd)"/>

  <!-- Decorative -->
  <circle cx="1320" cy="180" r="220" fill="#fff" opacity="0.10"/>
  <circle cx="1450" cy="310" r="120" fill="#fff" opacity="0.10"/>
  <path d="M0,720 C280,640 520,820 800,740 C1060,665 1220,720 1600,640 L1600,900 L0,900 Z" fill="#fff" opacity="0.08"/>

  <!-- Main panel -->
  <g filter="url(#shadowEnd)">
    <rect x="110" y="110" rx="28" ry="28" width="1380" height="680" fill="url(#panelEnd)"/>
  </g>

  <!-- Header -->
  <rect x="110" y="110" rx="28" ry="28" width="1380" height="130" fill="#fff" opacity="0.20"/>
  <rect x="110" y="240" width="1380" height="2" fill="#0b2a66" opacity="0.12"/>

  <!-- Chip -->
  <rect x="160" y="150" rx="22" ry="22" width="260" height="44" fill="#0b2a66" opacity="0.95"/>
  <text x="290" y="180" text-anchor="middle" fill="#fff" class="chip">KAPITEL 3 • ENDE</text>

  <!-- Title -->
  <text x="160" y="330" fill="#0b2a66" class="title">Danke!</text>
  <text x="160" y="385" fill="#0b2a66" opacity="0.85" class="subtitle">Kapitel abgeschlossen • Gute Arbeit</text>

  <!-- Summary cards -->
  <g>
    <!-- Card 1 -->
    <g transform="translate(160, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <text x="28" y="62" fill="#0b2a66" class="h2">Du kannst jetzt…</text>
      <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">Gerichte nennen</text>
      <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">in der Mensa bestellen</text>
      <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">über Essen sprechen</text>
      <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">Wortschatz: Bratkartoffeln • Currywurst • …</text>
    </g>

    <!-- Card 2 -->
    <g transform="translate(595, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <text x="28" y="62" fill="#0b2a66" class="h2">Grammatik</text>
      <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">können • wollen</text>
      <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">mögen • möchten</text>
      <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">Satzbau üben</text>
      <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">nicht / kein(e) • Wortstellung</text>
    </g>

    <!-- Card 3 -->
    <g transform="translate(1030, 450)">
      <rect rx="22" ry="22" width="410" height="270" fill="#fff" opacity="0.92"/>
      <rect rx="22" ry="22" width="410" height="270" fill="none" stroke="#0b2a66" opacity="0.10" stroke-width="2"/>
      <text x="28" y="62" fill="#0b2a66" class="h2">Nächster Schritt</text>
      <text x="28" y="110" fill="#0b2a66" opacity="0.85" class="txt">Wiederholen</text>
      <text x="28" y="146" fill="#0b2a66" opacity="0.85" class="txt">Audio noch einmal hören</text>
      <text x="28" y="182" fill="#0b2a66" opacity="0.85" class="txt">Übungen machen</text>
      <text x="28" y="238" fill="#0b2a66" opacity="0.70" class="small">Weiter zu Kapitel 4</text>
    </g>
  </g>

  <!-- Footer -->
  <text x="160" y="835" fill="#ffffff" opacity="0.92" class="small">A1 Deutsch • Kapitelende • LiaScript</text>
  <text x="1490" y="835" text-anchor="end" fill="#ffffff" opacity="0.78" class="small">© Mahwixh &amp; Maxub</text>
</svg>
