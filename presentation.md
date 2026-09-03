---
marp: true
# theme: gaia
# theme: uncover
theme: dracula
author: _GreyWolf, KellyGreeny
title: Bondage for Cosplay
_class: lead
paginate: true
inlineSVG: false
# backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.svg')
style: |
    .column {
        float: left;
        width: 50%;
    }

    ol.sources {
        li {
            a {
                overflow: hidden;
                font-size: smaller;
                break: break-all;
                hyphenate-character: "_";
            }
        }
    }

    .qrcode {
        height: 100px;
        width: 100px;
        border-radius: 8px;
        align-self: center;
        justify-self: end;
    }

    .social {
        /* border: 2px solid rgba(96, 139, 168, 0.3); */
        width: 95%;
        margin: 0 auto;
        justify-self: stretch;
        height: 100px;
        display: inline-grid;
        /* inline to prevent splitting */
        align-content: space-between;
        align-items: center;
        justify-items: start;
        grid-template:
            "title qr" 50%
            "name qr" 50%;
        /*
            grid-template:
                "title name qr";
            */
        border-radius: 5px 5px 5px 5px;
        /* box-shadow: 0px 2px 5px rgba(255, 0, 0, 0.3); */

    }

    .social>a:has(img),
    img.social-qr {
        align-self: center;
        justify-self: end;
        grid-area: qr;



    }

    .social-name {
        grid-area: name;
        font-size: smaller;
    }

    .social-title {
        text-decoration: none;
        text-wrap: nowrap;
        text-overflow: clip;
        justify-self: start;
        font-size: smaller;
        grid-area: title;

    }

    .two-balanced-columns {
        /* border: 2px solid rgba(255, 127, 7, 0.3); */
        columns: 2;
        column-fill: balance;
        margin: 0 auto;
        padding: 0;
        justify-items: stretch;
    }

    ul.social-list {


        /* border: 2px solid rgba(255, 127, 7, 0.3); */

        break-before: avoid;

        &.standalone {
            height: 360px;
            columns: 2;
            column-rule-color: #ff0000;
            column-fill: auto;
            column-gap: 10%;
            list-style-position: outside;


            /* this is important addition */
            & li {
                /* border: 4px dashed rgba(7, 255, 61, 0.3); */
                align-items: start;
                padding: 20px;
                width: 50%;

                &:before {
                    content: "";
                    padding-left: 10px;

                }
            }
        }

    }



    /* Clear floats after the columns */
    /*.row:after {
    content: "";
    display: table;
    clear: both;
    }*/

    .warning-block {
        border: 10px solid rgba(201, 52, 14, 0.3);
        margin: 10px auto;
        font-size: bigger;
        &::before {
            /* content: "!"; */
        }

        prefix: ">";
    }

---
<!-- markdownlint-disable MD004 -->

# Bondage for Cosplay

Das wird ein schneller Crash-Kurs für euch und ihr bekommt etliche Ressourcen als QR-Codes, die dürft ihr gerne mit den Handys abscannen und wir versuchen auch ein PDF der Präsentation zur Verfügung zu stellen, aber wir bitten euch keine Fotos von uns zu machen!

---

## Vorstellung

---

### \_GreyWolf

<div class="two-balanced-columns">
<ul>
<li>Knotet seit Jahrzehnten</li>
<!-- Segeln, Feuerwehr, ... -->
<li>Fesselt seit einige Jahren</li>
<li> Socials:
<ul class="social-list">
    <li>
    <address class="social">
        <div class="social-title twitter">Twitter:</div>
            <div class="social-name">@German_GreyWolf</div>
        <a href="https://twitter.com/german_greywolf">
                <img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/twitter_gw.png" class="social-qr qrcode" alt="Link to Twitter"/>
        </a>
    </address>
    </li>
    <li>
    <address class="social">
        <div class="social-title">BlueSky:</div>
            <div class="social-name">@UnderscoreGreyWolf</div>
        <a href="https://bsky.app/profile/underscoregreywolf.bsky.social">
            <img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/bsky_gw.png" class="social-qr qrcode" alt="Link to BlueSky"/>
        </a>
    </address>
    </li>
        <li>
    <address class="social">
        <div class="social-title">Fedi (@KinkyCats.org):</div>
            <div class="social-name">@_GreyWolf</div>
        <a href="https://kinkycats.org/@_GreyWolf">
            <img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/fedi_gw.png" class="social-qr qrcode" alt="Link to Mastodon"/>
        </a>
    </address>
    </li>
   <li>
    <address class="social">
        <div class="social-title">Fetlife:</div>
            <div class="social-name">_GreyWolf</div>
    <a href="https://fetlife.com/_GreyWolf">
            <img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/fl_gw.png" class="social-qr qrcode" alt="Link to Fetlife"/>
        </a>
    </address>
    </li>
       <li>
    <address class="social">
        <div class="social-title">GitHub:</div>
            <div class="social-name">UnderscoreGreyWolf</div>
            <a href="https://github.com/UnderscoreGreyWolf">
            <img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/gh_gw.png" class="social-qr qrcode" alt="Link to GitHub"/>
        </a>
    </address>
    </li>
</ul>
</li>
</ul>

---

### KellyGreeny

<div class="two-balanced-columns">
<ul>
<li>macht seit 13 Jahren Cosplay</li>
<li> Socials:
<ul class="social-list">
<li>
    <address class="social">
        <div class="social-title">Instagram:</div>
            <div class="social-name">@Kellygreenycosplay</div>
        <a href="https://www.instagram.com/kellygreenycosplay">
            <img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/ig_kg.png" class="social-qr qrcode" height=200px alt="Link to Instagram"/>
        </a>
    </address>
    </li>
</ul>
</li>
</ul>

---

### Seil ist cool und vielseitig

* Von Selbstverteidigung über Kink bis hin zum Alltag hilft es überall!

<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/hojo_cover.jpg" alt="Cover eines Buchs mit einem roten Seil zum Thema 'Hojo Jutsu: Haya Nawa' mit dem Untertitel 'Das schnelle Seil in Budo und Bujutsu' von Norbert Mahl & Walter Baier" height="50%">

---

## Consent

<!--Schneller Walk-trough und verlinken auf Ressourcen-->

---

### Consent Modelle

* Negativer Consent [¹](#wikipedia-sexual-consent)
<!--
"Nein heisst Nein"
Solange kein Widerspruch kommt, ist es OK
!! In diesem Bereich schwierig !!
-->
* Positiver Consent [¹](#wikipedia-sexual-consent)
<!--
Mach das (mit mir)
-->
* Affirmativer Consent [¹](#wikipedia-sexual-consent)
<!--
"Only yes means yes"
-->
* Enthusiastischer Consent [¹](#wikipedia-sexual-consent)
* FRIES [¹](#wikipedia-sexual-consent)
<!--
Freely Given
Reversible
Informed
Enthusiastic
Specific
-->
* Meta-Consent
<!--
Mach mit mir was **du** willst (ausser ich benutze ein Safeword)
-->

<!--Quelle: https://en.wikipedia.org/w/index.php?title=Sexual_consent&oldid=1300147158 -->

---

## Risiko

<!--Seil ist NIE *un*gefährlich! -->

---

### Risiko Modelle

* SSC [³](#reddit-consent-models)
<!--
Safe
Sane
Consentual
-->
* RACK [³](#reddit-consent-models)
<!--
Risk
Aware
Consentual
Kink
 -->
* PRICK [³](#reddit-consent-models)
<!--
personal
responsibility
informed
consensual
kink
-->
* CCCC [³](#reddit-consent-models) / "4Cs" [⁴](#researchgate-4cs)
<!--
caring
communication
consent
caution
-->

--- 
### Risiko Arten

* Physische Risiken
* Medizinische Risiken
* Psychologische Risiken

---

### Risiko Vermeidung

* Information
<!--
Nur informierter Konsent ist Konsent!
-->
* Vetting: <a href="https://www.theduchy.com/vetting-a-potential-rope-partner/">www.theduchy.com/vetting-a-potential-rope-partner/<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/duchy_vetting.png" alt="QR Code" class="qrcode"></a>
<!--
Vetting: Evaluieren von Bondage-"Partnern"
- Nach Leuten fragen, die bereits mit der Person gefesselt haben
- In der Szene / Freundeskreis fragen
- Allgemein nach Erfahrungen der Person fragen
-->
* Klare Absprachen

---

#### Absprache Strategien und Hilfsmittel

---

##### Absprache > Risiko Einschätzung [²](#duchy-negotiation-starter-2.1)

* Wichtige medizinische Punkte?
* Aktueller Zustand (Drogen? Alkohol? Medikamente?)
* Persönliche Risiken (Trigger?)

---

##### Absprache > Grenzen [²](#duchy-negotiation-starter-2.1)

* Wo sind Berührungen OK?
* Wo sind Berührungen **NICHT** OK?

---

##### Absprache > Ziel

* Play? (=> Welche Art von Spiel?)
* Fotos? (Dauer?)
* Performance? (Dauer???)

---

##### Absprache > Checklists

<!--
Allgemein helfen Checklists dabei Punkte nicht zu vergessen
-->
Beispiele:
<ul>
<li>
<a href="https://www.theduchy.com/general-negotiation-and-planning/">www.theduchy.com/general-negotiation-and-planning/<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/duchy_negotiation.png" alt="QR Code" class="qrcode"></a>
</li>
<li>
<a href="https://www.theduchy.com/negotiation-forms/">www.theduchy.com/negotiation-forms/<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/duchy_negotiation_forms.png" alt="QR Code" class="qrcode"></a>
</li>
</ul>

---

## Safety

<a href="https://www.theduchy.com/risks-when-using-rope/">www.theduchy.com/risks-when-using-rope/<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/duchy_risks.png" alt="QR Code" class="qrcode"></a>

Siehe auch <a href="https://www.selfsuspend.com/safety">www.selfsuspend.com/safety<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/selfsuspend_safety.png" class="qrcode" alt="QR Code"></a>
<!--
Self-Bondage nie alleine machen, immer einen Spotter haben
-->


---

### Anatomiekenntnisse und Nerven
<!--
Insbesondere oberflächliche Nerven sind bei Bondage gefährdet
Auch geringer Druck kann bei längerer Auswirkung Schäden verursachen
-->

Tests:
* "Funktionstest" durch Anregen und Nachfragen
    <div class="warning-block">
    Auch bei leichtem Druck können Nervenschäden entstehen
    </div>

---

Mehr dazu findet ihr zum Beispiel hier:

* Anatomy for Rope Bondage  <a href="https://www.youtube.com/watch?v=u9-VzX9_pzg">
www.youtube.com/watch?v=u9-VzX9_pzg  <img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/yt_anatomy.png" alt="QR Code" class="qrcode"/></a>
* <a href="https://www.theduchy.com/nerves-and-circulation/">www.theduchy.com/nerves-and-circulation/<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/duchy_nerves.png" alt="QR Code" class="qrcode"></a>

---

### die leicht übersehenen Risiken

* Was passiert wenn jemand gefesselt stolpert
<!--
Unterschiede in der Postion der Fesselung
    "Vorführung"
    Hände frei
    Hände vor dem Körper
    Hände hinter dem Körper
-->
* Was passiert bei Notfällen, Feuer, epileptischem Anfall...
<!--
Notfälle können sowohl Bunny als auch Rigger treffen!
-->
* Was passiert, wenn der Kreislauf der gefesselten Person versagt?
<!--
Dextrose/Zucker und Flüssigkeit zum aufpeppeln
Wie wirkt sich das auf die Fesselung aus?
-->
<!--
Nochmal Hinweis auf Nervenschäden
-->


---


### Sicherheitsausrüstung

* Dinge zum Seil zerstören, wenn es schnell gehen muss
    <!--
    Scheren
    Seilschneider
    Messer
    -->
    <div class="warning-block">Wenn andere Leute fesselnde Person keine Schere hat, überschätzt sie sich grundsätzlich</div>
<!--
Show and Tell
-->

* Bonus: Material für Aftercare
    - Dextrose
    - Decke
    - Trinken

---

## Kurze Einführung von Begriffen

* restriktive vs dekorative Bondage
<!--
Was ist die Kategorie von Bondage die ihr anstrebt
Cosplay eher Dekorativ
-->
* Funktionalität von Bondage: ihr braucht für ein Outfit in der Regel keine Suspension-fähigen Dinge
<!--
Funktionale Anforderungen verändern massiv die Art zu fesseln ebenso wie Anforderungen an die Zeit 
Deshalb auch die Absprache zu dem Thema
-->
* Selfbondage
<!--
Bondage an sich selbst (Wow wie unerwartet)
Zusätzliche Herausforderungen gegenüber Fesseln alleine
(Mehr auf Nachfrage)
-->

---

## Einführung von Knoten

* Überraschung: Ihr braucht fast keine Knoten!
<!--
Wette, dass alle schon einen Bondage-Knoten können
-->
* Overhandknot oder einfach: ein (Standard-)Knoten
  * Karada mit overhand knots
    <!-- 
    Vorführung 1 
    Bewusste Fehler einbauen!
        Verdrehtes Seil
        Asymmetrie, Seil nicht ausrichten
    -->

---

## Tipp und Tricks

### oder "Warum sieht mein Knoten komisch aus?"

<!--

Einführung von Seil Management
Die kleinen Tricks (Seile parallel führen und mit den Fingern die Seile von der Haut abheben)

-->
* Seile parallel führen
<!--
Sorgt auch für besser Druckverteilung, da Seil-"Kreuzungen" den Druck erhöhen
-->
* Seile unter gleicher Spannung führen
<!--
Macht die Seile und den Druck berechenbarer
Trick dafür: Seile mit Fingern von der Haut abheben und sich neu "setzen" lassen
-->

---

## Überlegungen für Fotos

* Bondage Fotos alleine machen ist Hard-Mode!
<!--
Seilführung hinter dem Rücken ist bei Self-Bondage tricky!
-->
* Auch zu zweit ist eine Person sowohl für die Fotos als auch für die gefesselte Person verantwortlich
  <!-- Eine dedizierter Rigger macht die Verantwortlichkeiten klarer und kann sich besser auf die gefesselte Person konzentrieren -->
  * Außer es ist Self-Bondage

---

### Suspensions für beeindruckende Bilder

* Suspensions sehen beeindruckend aus, aber sind auch sehr riskant
    * Shay Tiziano
        - <a href="https://www.selfsuspend.com">www.selfsuspend.com<img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/selfsuspend.png" alt="QR Code" class="qrcode"/></a>
        - Tying and Flying: Bondage for self-suspension, ISBN: 978-0578566405
    <!--
    Self-Suspension + Kamera/Spotter ist aber eine legitime Kombination
    Referenz auf Shay Tiziano
    -->
    * TheDuchy(R) <a href="https://www.theduchy.com/"><img src="https://raw.githubusercontent.com/UnderscoreGreyWolf/2025_Vortrag_Connichi/refs/heads/main/img/theduchy.png" class="qrcode" alt="QR Code"/></a>


---
## Habt ihr Fragen?

<!--
Platz für Fragen aus dem Publikum
-->

---

## Show (and Tell?)
<!--
Improvisation oder Interaktiver Workshop
-->

---


## Sources

<ol class="sources">
<li id="wikipedia-sexual-consent"> <a href="https://en.wikipedia.org/w/index.php?title=Sexual_consent&oldid=1300147158">en.wikipedia.org/w/index.php?title=Sexual_consent&oldid=1300147158</a></li>
<li id="duchy-negotiation-starter-2.1"><a href="https://www.theduchy.com/wp-content/uploads/2022/10/Negotiation-Starter-v2.1-General-Rope-TheDuchy.pdf">www.theduchy.com/wp-content/uploads/2022/10/Negotiation-Starter-v2.1-General-Rope-TheDuchy.pdf</a></li>
<li id="reddit-consent-models"><a href="https://old.reddit.com/r/paypigsupportgroup/comments/1bat9br/finsubs_please_learn_about_rack_prick_ssc_and_cccc/">reddit.com/r/paypigsupportgroup/comments/1bat9br/<wbr>finsubs_please_learn_about_rack_prick_ssc_and_cccc/</a></li>
<li id="researchgate-4cs"><a href="https://www.researchgate.net/publication/271854517_From_SSC_and_RACK_to_the_4Cs_Introducing_a_New_Framework_for_Negotiating_BDSM_Participation">www.researchgate.net/publication/271854517_<wbr>From_SSC_and_RACK_to_the_4Cs_Introducing_a_New_Framework_for_<wbr>Negotiating_BDSM_Participation</a></li>
</ol>

---

### draculatheme

GitHub: <https://github.com/dracula/marp>
Website: <https://draculatheme.com/marp>
Author: Daniel Nicolas Gisolfi

Found via <https://yoanbernabeu.github.io/MARP-Template-Library/docs/themes/dracula>
