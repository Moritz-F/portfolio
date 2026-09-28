# Konzept – Portfolio Moritz Frommelt

Stand: 27.09.2026 · Grundlage: Lebenslauf (v1 + v2), altes Portfolio 04/2026, `referenzen/case-study-fueling-calculator.md`, Bilder in `media/`, Figma-Datei „DL-Bootcamp-Projekt“, 12 Referenz-Screenshots.

Markierungen: `[PLATZHALTER · …]` = Inhalt fehlt · `[BELEG FEHLT]` = Zahl ohne Quelle · `[PRÜFEN]` = unsicher, bitte bestätigen.

---

## 1 · Was aus deinem Material über dich hervorgeht

Du bist UX-/UI-Designer mit einem ungewöhnlich durchgängigen Weg durch Gestaltung und Technik: Gestaltungstechnischer Assistent, Mediengestalter Digital in einer Kieler Agentur, Medieningenieur mit Schwerpunkt UX/UI an der FH Kiel, dazu Praxis in einer Agentur und einem Softwareunternehmen. Deine Projekte folgen fast immer dem vollen Weg von Research über Personas und Wireframes bis zum getesteten Prototyp und oft bis zum Designsystem – im Studium, in der Bachelorarbeit und jetzt im Fueling Calculator. Du dokumentierst deine eigenen Schwächen offen: Die Case-Datei listet ungelöste Fragen (Monetarisierung) und Unstimmigkeiten im eigenen Design auf, statt sie zu verstecken.

**Die Stärke, die du unterverkaufst:** Du denkst in Systemen, nicht in Einzelscreens. In der Bachelorarbeit hast du ein Designsystem mit Komponenten gebaut, im GUI-Modul Design-Systeme und Guidelines vertieft, im Fueling Calculator Regeln mit Begründung aufgestellt (Radius nach Interaktivität, zwei getrennte Signale), und in der Green-Data-Challenge einen ganzen Prozess als Swimlane-Diagramm entworfen, bevor es Screens gab. In deinem Lebenslauf steht davon nichts – dort steht „Prototyping · Benutzerforschung“.

---

## 2 · Analyse der Referenzen

| Referenz | Was funktioniert | Was nicht | Prinzip, das ich übernehme |
|---|---|---|---|
| Sydney Rasmussen | Case-Titel sind Ergebnisse mit Zahl – in fünf Sekunden verstanden | Case Study sehr lang und textlastig | Case-Titel als Ergebnis-Satz, nicht als Projektname |
| Jacob Dilley | Extrem schnell zu überfliegen; Rolle, Firma, Zeitraum stehen immer an derselben Stelle | Case Study zeigt kaum Prozess und keine Belege | Feste Meta-Zeile an jeder Projektkarte |
| Johnyvino | Kleine Überzeilen in Mono geben ruhige Orientierung | Keine Case Studies, Karussells verstecken Inhalt | Überzeilen als Leitsystem über jedem Abschnitt |
| Nicole Roberts | Zwei harte Kennzahlen und ein Live-Link auf jeder Karte | Wirkt wie eine Vorlage, Headline sagt wenig Eigenes | Kennzahlen auf der Karte – aber nur belegte |
| Maryna Vasylenko | Tabs sprechen Recruiter, Designer, Entwickler getrennt an | Grauer Kleintext auf Schwarz schwer lesbar, Case sehr lang | Derselbe Inhalt in zwei Tiefen: Kurzfassung oben, Detail darunter |
| Noah Suppin | Ergebnis steht vorne, Case-Gliederung kurz und klar | Projektbilder teils nichtssagend, Case visuell monoton | Beleg vor Beschreibung |

**Was ich ausdrücklich nicht übernehme:** die Optik einer einzelnen Referenz, Testimonial-Karussells (du hast keine Testimonials, und wir erfinden keine), Kundenlogo-Leisten.

---

## 3 · Seitenstruktur

### Ebene 1 · Seiten

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite (S1–S8) |
| `case-fueling-calculator.html` | Hauptcase (C1, C1b, C2–C4, C6, C8, C7, C11) |
| `case-second-brain.html` | Zweiter Case – vorerst nur als Karte auf der Startseite angedeutet, Seite folgt |
| `impressum.html`, `datenschutz.html` | Schritt 12 |
| `lebenslauf-moritz-frommelt.pdf` | Download-Fassung ohne Geburtsdatum und Privatadresse |

### Ebene 2 · Startseite

| # | Abschnitt | Welche Frage er beantwortet | Was hineingehört | Warum an dieser Stelle |
|---|---|---|---|---|
| S1 | Kopfzeile | Wo finde ich was? | Name, Sprunglinks (Cases, Arbeiten, Über mich, Kontakt), Lebenslauf-PDF, Modus-Schalter hell/dunkel | Immer sichtbar (sticky, Glas) – Recruiter springen direkt |
| S2 | Einstieg | Wer ist das, und was macht er? | Ein Satz, Rolle, Ort, Button zum Hauptcase | Die ersten fünf Sekunden entscheiden, ob weitergelesen wird |
| S3 | Case Studies | Was hat er gebaut, und wie denkt er? | Karte Fueling Calculator (groß), Karte Second Brain (angedeutet) | Der beste Beleg kommt direkt nach der Behauptung |
| S4 | Weitere Arbeiten | Kann er mehr als ein Projekt? | 5 Kacheln mit Bild und je einem Satz | Zeigt Breite, ohne den Hauptcase zu verdrängen |
| S5 | Über mich | Wer steckt dahinter, und woher kommt er? | 3–4 Sätze, Porträt, kompakter Werdegang (5 Stationen), Werkzeuge und Methoden | Nach den Arbeiten: Wer überzeugt ist, will die Person kennenlernen |
| S7 | Kontakt | Wie erreiche ich ihn? | Mail, LinkedIn, Lebenslauf-PDF | Die Handlung am Ende der Seite |
| S8 | Fußzeile | Rechtliches | Impressum, Datenschutz | Pflicht, unauffällig |

### Ebene 3 · Case Study Fueling Calculator

| # | Kapitel | Welche Frage es beantwortet | Was hineingehört | Warum an dieser Stelle |
|---|---|---|---|---|
| C1 | Hero | Worum geht es, und was war meine Rolle? | Ergebnis-Titel, ein Satz zum Problem, Meta-Zeile (Rolle, Zeitraum, Kontext, Tools), finaler Screen | Das Wichtigste für Leser mit zwei Minuten |
| C1b | Auf einen Blick | Was muss ich wissen, wenn ich nur zwei Minuten habe? | Drei Zeilen: Problem, Lösung, wichtigste Entscheidung | Direkt unter dem Hero – wer hier aufhört, hat trotzdem das Wichtigste |
| C2 | Das Problem | Warum lohnt sich das? | Übersetzungsproblem, Umfrage (n = 11), Studie, Zielgruppe | Ohne Problem keine Bewertung der Lösung |
| C3 | Prozess | Wie habe ich entschieden? | 4 Wendepunkte mit verworfener Alternative, Persona, Journey Map, Zitat, Lo-Fi neben Final | Das Denken vor dem Ergebnis – der eigentliche Beleg |
| C4 | Die Lösung | Was ist herausgekommen? | 5 Key Screens mit Kontextsatz in Flow-Reihenfolge, dazu der Ladescreen (kein klickbarer Flow) | Folgt aus den Entscheidungen in C3 |
| C6 | KI im Prozess | Wie nutze ich KI – und wo nicht? | Haltung (Sparring, alles hinterfragt), Werkzeuge mit Zweck | Wird im Gespräch fast immer gefragt |
| C8 | Designsystem der App | Wie konsequent gestalte ich? | Farblogik, Radius-Regel, zwei unabhängige Signale, Moodboard | Vertiefung für Designer:innen – nach dem Kern, vor der Reflexion |
| C7 | Learnings | Was nehme ich mit? | 2–3 Erkenntnisse, Ausblick, ungelöste Frage | Kurz vor dem Ende: wirkt reflektiert, beantwortet „Was würdest du anders machen?“ |
| C11 | Abschluss | Wer ist das, wie erreiche ich ihn? | Kurzvorstellung, Kontakt, Link zum nächsten Case | Handlung am Ende; niemand muss zurückscrollen |

**Hinweis zu Testing:** Du hast C5 Testing gestrichen. Der Usability-Test ist aber der Auslöser für deinen wichtigsten Wendepunkt („Transparenz dosieren“). Ich baue den Test deshalb als Wendepunkt 4 in C3 ein – mit Befund und Änderungen –, statt ihn ganz wegzulassen. C9 Erfolgsmessung und C10 Markt fallen weg; die Maurten-Analyse steht als ein Satz in Wendepunkt 2.

---

## 4 · Designkonzept

### Farben – woher sie kommen

Die Portfolio-Palette stammt aus **deinen Bewerbungsunterlagen, nicht aus der Case**. Lebenslauf und altes Portfolio nutzen beide ein tiefes Indigo für Namen und Überschriften und helle Lavendel-Flächen für Karten (Lebenslauf v2). Das wird die Grundfarbe. So bilden Lebenslauf-PDF und Website eine erkennbare Einheit.

Das Gelb-Orange aus deinem alten Portfolio übernehme ich **nicht** als Fläche, weil es zu nah am Gelb der Fueling-App liegt und Portfolio und Case sonst verschwimmen. Übrig bleibt davon eine warme **Aprikose** als zweiter, sparsamer Akzent – für Markierungen und Kennzahlen.

Die Werte habe ich aus deinen PDFs nach Augenmaß abgeleitet und so angepasst, dass sie den Kontrast bestehen [PRÜFEN · wenn du die genauen Hex-Werte aus Lebenslauf oder altem Portfolio hast, gleiche ich sie an].

| Rolle | Light | Dark | Verwendung |
|---|---|---|---|
| `--color-bg` | `#F6F6FB` | `#0E0F22` | Seitenhintergrund (Dark ist Indigo-Nacht, kein Schwarz) |
| `--color-surface` | `#FFFFFF` | `#181A33` | Karten |
| `--color-surface-tint` | `#ECEEFB` | `#222549` | Hervorgehobene Karten (Lavendel aus dem Lebenslauf) |
| `--color-stage` | `#E3E5F3` | `#2A2D55` | Bühne hinter App-Screens |
| `--color-text` | `#17173A` | `#EEEFFA` | Fließtext, Überschriften |
| `--color-text-muted` | `#4D4E6E` | `#AEB0CC` | Meta-Zeilen, Bildunterschriften |
| `--color-primary` | `#3D3C8C` | `#AFAEFF` | Links, Buttons, Fokusring |
| `--color-on-primary` | `#FFFFFF` | `#0E0F22` | Text auf Buttons |
| `--color-accent` | `#FFB45E` | `#FFB45E` | Aprikose: nur Fläche hinter dunklem Text (Light), auch Text (Dark) |
| `--color-border` | `#D4D7EA` | `#34375E` | Dekorative Trennlinien |
| `--color-placeholder` | `#E6E6E9` | `#2C2C33` | Platzhalter-Flächen (grau, bewusst ohne Farbe) |
| `--color-placeholder-text` | `#4A4A55` | `#C9C9D2` | Beschriftung der Platzhalter |

### Kontrastwerte (WCAG, berechnet)

| Paar | Light | Dark | Ergebnis |
|---|---|---|---|
| text auf bg | 15,98 : 1 | 16,54 : 1 | AA ✓ |
| text auf surface | 17,21 : 1 | 14,88 : 1 | AA ✓ |
| text auf surface-tint | 14,91 : 1 | 12,85 : 1 | AA ✓ |
| text auf stage | 13,74 : 1 | 11,44 : 1 | AA ✓ |
| text-muted auf bg | 7,41 : 1 | 8,90 : 1 | AA ✓ |
| text-muted auf stage (schwächstes Paar) | 6,37 : 1 | 6,16 : 1 | AA ✓ |
| primary auf bg | 8,77 : 1 | 9,30 : 1 | AA ✓ |
| primary auf stage | 7,54 : 1 | 6,43 : 1 | AA ✓ |
| on-primary auf primary (Button) | 9,44 : 1 | 9,30 : 1 | AA ✓ |
| Tinte `#17173A` auf accent | 9,79 : 1 | 9,79 : 1 | AA ✓ |
| accent auf bg (als Text) | **1,63 : 1** | 10,76 : 1 | Light ✗ → Aprikose im Light Mode nie als Text |
| placeholder-text auf placeholder | 7,02 : 1 | 8,43 : 1 | AA ✓ |
| border auf surface | 1,43 : 1 | 1,50 : 1 | nur dekorativ, nie als einziges Merkmal |

### Schrift

Eine Variable `--font-sans` in `style.css`, austauschbar mit einer Zeile. Gewählt: **Manrope** (liegt in `media/fonts/`, 7 Schnitte als TTF; genutzt werden Regular, Medium, SemiBold, Bold, ExtraBold – Umwandlung in WOFF2 in Schritt 10). Rückfall: `system-ui, -apple-system, "Segoe UI", Roboto, sans-serif`. Überzeilen und Meta-Zeilen in gesperrten Versalien derselben Schrift – keine zweite Schrift nötig.

Lange deutsche Wörter („Flüssigkeitsbedarf“): `hyphens: auto` mit `lang="de"`, Überschriften bei 320 px nie größer als 2,125 rem.

### Schriftgrößen-Skala (Verhältnis 1,25, Basis 17 px)

| Variable | Größe | Verwendung |
|---|---|---|
| `--text-xs` | 0,8125 rem (13 px) | Überzeilen, Etiketten |
| `--text-sm` | 0,9375 rem (15 px) | Meta-Zeilen, Bildunterschriften |
| `--text-base` | 1,0625 rem (17 px) | Fließtext, Zeilenhöhe 1,6 |
| `--text-lg` | 1,3125 rem (21 px) | Einleitungen, h4 |
| `--text-xl` | 1,625 rem (26 px) | h3 |
| `--text-2xl` | clamp(1,75 rem, 4vw, 2,0625 rem) | h2 |
| `--text-3xl` | clamp(2,125 rem, 6vw, 3,25 rem) | h1 |

### Abstandsskala (4er-Raster)

`--space-1` 4 px · `--space-2` 8 · `--space-3` 12 · `--space-4` 16 · `--space-5` 24 · `--space-6` 32 · `--space-7` 48 · `--space-8` 64 · `--space-9` 96 · `--space-10` 128

Seitenrand mobil 16 px, Textspalte maximal 68 Zeichen (~ 40 rem), Inhaltsbreite maximal 72 rem.

### Radien

`--radius-sm` 8 px (Etiketten innen, kleine Bilder) · `--radius-md` 16 px (Bilder, Bühnen) · `--radius-lg` 24 px (Karten) · `--radius-pill` 999 px (Buttons, Tags, Kopfzeile).

Bewusster Unterschied zur App: Die App nutzt Radius 0 für Inhalte. Das Portfolio ist durchgehend weich – auch das trennt Rahmen und Case.

### Glas

Nur Kopfzeile und Pills: halbtransparente Fläche mit `backdrop-filter: blur()`, feiner Rand. Bei `prefers-reduced-transparency` und in Browsern ohne Blur: volle Fläche `--color-surface`. Nie hinter Fließtext.

### Visuelles Leitmotiv: Herkunfts-Etiketten

Dein wiederkehrendes Thema ist Ehrlichkeit darüber, woher ein Wert kommt – in der App („Geschätzt“), in Green Data (KI-Konfidenz). Das Portfolio macht dasselbe mit seinen eigenen Aussagen: **Jede Behauptung trägt ein kleines Etikett, woher sie kommt.**

- `BELEG · Umfrage n = 11` – Zahl aus Daten
- `ENTSCHEIDUNG` – was ich gewählt habe
- `VERWORFEN` – die Alternative, durchgestrichen
- `BEFUND · Usability-Test` – was der Test zeigte
- `ANNAHME` – noch nicht belegt

Gestaltet als Pill mit Symbol **und** Wort (nie nur Farbe). Das Leitmotiv trägt die Wendepunkte in C3 und die Kennzahlen auf den Karten und macht die Seite unverwechselbar, ohne eine Referenz nachzubauen. Die vorhandenen Platzhalter-Markierungen fügen sich in dieses System ein.

---

## 5 · Erste Textentwürfe

### Startseite

**S1 · Kopfzeile**
Moritz Frommelt · Cases · Arbeiten · Über mich · Kontakt · [Lebenslauf (PDF)] · [hell/dunkel]

**S2 · Einstieg**
Überzeile: UX/UI & Product Designer · Kiel
> Ich bin UX/UI- und Product Designer und gestalte digitale Produkte vom ersten Research bis zum Designsystem.

Button: Case Study ansehen: Fueling Calculator →

*(Gewählt, 27.09.2026.)*

Kompass-Satz (nicht auf der Seite, nur zur Prüfung): Nach zwei Minuten soll eine Recruiterin denken: „Moritz denkt ein Produkt vom ersten Research bis zum Designsystem durch – und zeigt ehrlich, was belegt ist und was nicht.“

**S3 · Case Studies**

Karte 1 – groß
- Überzeile: Product Design · Einzelprojekt · Weiterbildung Digitale Leute (Datum entfernt, 27.09.2026 – wirkte auf der Karte wie ein Ablaufdatum)
- Titel: **Fueling Calculator für Ausdauersportler** (verständlicher als Ergebnis-Titel; „Aus 60–90 g …“ blieb als erklärender Satz)
- Satz: Aus 60–90 g Kohlenhydrate pro Stunde wird eine Packliste: ein markenneutraler Planer, der für eine konkrete Radtour berechnet, was in welche Flasche und welche Trikottasche kommt.
- Ablauf: Research · Konzept · Struktur · Test & Hi-Fi · Story (die fünf Module aus der Case-Datei)
- Tools: Figma · Miro · KI (Claude, Gemini, NotebookLM, Perplexity)
- Bild: `MF2 – Plan – Übersicht.jpg` auf Bühne
- Button: Case Study lesen →

Karte 2 – angedeutet
- Überzeile: Bachelorarbeit · FH Kiel · 2025
- Titel: **Second Brain** [PLATZHALTER · Ergebnis-Titel, sobald Material vorliegt]
- Satz: Ein Anwendungskonzept, das die Second-Brain-Methode durch nutzerzentriertes UX- und UI-Design im Alltag nutzbar machen soll.
- Status-Pill: `CASE STUDY FOLGT`
- Bild: [Platzhalter · 1600 × 1000 px · Startbildschirm der Second-Brain-Anwendung, Desktop]

**S4 · Weitere Arbeiten**
Einleitung: Kleinere Projekte aus dem Studium und einer Challenge – ohne ganze Case Study, aber mit je einer Entscheidung, die man sehen kann.

| Kachel | Kontext | Ein Satz |
|---|---|---|
| Smart Home Energie Control | GUI Design · Einzelprojekt | Ein Tablet-Dashboard, das Erzeugung, Eigenverbrauch und Netzeinspeisung auf einen Blick zeigt. |
| App für nachhaltiges Reisen | Innovative Konzepte · Team | Eine App, die den CO₂-Ausstoß einer Reise je Transportmittel vergleichbar macht. |
| SHHB Digitale Jahrbücher | Projektarbeit 2 · Team | Ein Webauftritt-Konzept, das die Jahrbücher des Schleswig-Holsteinischen Heimatbunds über eine Karte der Kreise erschließt. |
| Bewässerungs-App | Human Computer Interaction · Einzelarbeit in einem modulübergreifenden Projekt | Eine Steuerungs-App für eine Zimmerpflanzen-Bewässerungsanlage, die ich in einem anderen Modul mitgebaut habe – entwickelt vom Papierprototyp bis zum Wireframe. |
| Green Data Inbound-Tool | UI/UX Challenge | Ein Upload-Wizard, in dem KI Dokumente ausliest und unsichere Werte zur Bestätigung markiert. |

Bei Teamprojekten (Reise-App, SHHB): [PLATZHALTER · deine Rolle im Team, ein Halbsatz je Projekt]
Bilder: [Platzhalter · 800 × 500 px · je ein Screen aus dem alten Portfolio]

**S5 · Über mich**
> Ich bin UX-/UI-Designer aus Kiel. Angefangen habe ich mit Gestaltung – als Gestaltungstechnischer Assistent und Mediengestalter Digital –, dann kam mit dem Studium zum Medieningenieur das Verständnis dafür, wie digitale Produkte entstehen. Praxis habe ich in einer Agentur und einem Softwareunternehmen gesammelt. Mich interessiert der ganze Weg: von der ersten Nutzerfrage über Konzept und Prototyp bis zum Interface, das im Test besteht.

Werkzeuge: Figma · FigJam · Miro · Photoshop · Illustrator · Premiere Pro · Blender · HTML/CSS · KI-Werkzeuge (Claude, Gemini, NotebookLM, Perplexity, Figma-KI)
Methoden: Interviews · Umfragen · Personas · Customer Journey · User Story Mapping · User Flows · Wireframes · Prototyping · Usability-Tests · Designsysteme
Werdegang (kompakt, Teil von S5):
- seit 06.2026 · Weiterbildung Product Design · Digitale Leute School
- 02.2024–04.2025 · Isogon Informationssysteme, Kiel · Praktikum UX-Design, danach projektbezogen Webdesign
- 09.2019–08.2025 · B.Eng. Medieningenieur, Schwerpunkt UX/UI · FH Kiel · Bachelorarbeit: Second Brain
- 09.2017–06.2019 · Ausbildung Mediengestalter Digital und Print · ideenwerft GmbH, Kiel
- 08.2015–07.2017 · Fachabitur, Gestaltungstechnischer Assistent · Walther-Lehmkuhl-Schule, Neumünster

Bild: `profil/pb_komprimiert_v3.jpg` – Alt-Text: „Moritz Frommelt, lächelnd, mit verschränkten Armen vor dunklem Hintergrund“

**S7 · Kontakt**
> Aktuell suche ich eine Festanstellung als UX/UI- oder Product Designer. Schreib mir.

mail@moritzfrommelt.de · LinkedIn [linkedin.com/in/moritzfrommelt](https://www.linkedin.com/in/moritzfrommelt) · Lebenslauf (PDF) – `unterlagen/Lebenslauf_Moritz-Frommelt_final.pdf` (bereinigte Fassung, 28.09.2026 geliefert)

**S8 · Fußzeile**
© 2026 Moritz Frommelt · Impressum · Datenschutz

---

### Case Study Fueling Calculator

**C1 · Hero**
Überzeile: Case Study · Product Design
Titel (h1): **Aus 60–90 g pro Stunde wird eine Packliste**
Untertitel: Fueling Calculator – ein Planer, der für eine konkrete Radtour berechnet, wie viel Kohlenhydrate und Flüssigkeit nötig sind, und daraus eine Packliste und eine Mix-Anleitung pro Flasche macht.

Meta-Zeile:
- Rolle: Einzelprojekt – Research, Konzept, UX/UI-Design, Prototyp und Usability-Test
- Zeitraum: 06.–10.2026, rund vier Monate
- Kontext: Weiterbildung Product Design, Digitale Leute School, Module 1–5
- Tools: Figma, Figma Slides, Miro · KI: Perplexity, NotebookLM, Claude, Gemini, Figma-KI

Bild: `MF2 – Plan – Übersicht.jpg` auf Bühne, daneben `MF2 – Plan – Packliste.jpg`
Alt: „Plan-Übersicht der App: 210 g Kohlenhydrate, 1,5 l Flüssigkeit, 60 g pro Stunde, Genauigkeit mittel“

**C1b · Auf einen Blick**
- **Problem:** 10 von 11 Befragten hatten im letzten Jahr trotz Vorbereitung einen Hungerast oder Magenprobleme. Das Wissen ist da – die Übersetzung auf den konkreten Tag fehlt.
- **Lösung:** Ein markenneutraler Planer, der in fünf Schritten eine Packliste erstellt: was in welche Flasche und welche Trikottasche kommt.
- **Wichtigste Entscheidung:** Transparenz dosieren statt jede Zahl zu erklären – weil die Testpersonen (4) sonst lange brauchten, bis sie das Ergebnis erfasst hatten.

**C2 · Das Problem**
Aussage: Das Wissen ist da. Die Übersetzung auf den konkreten Tag fehlt.

> Viele ambitionierte Hobby-Radfahrer:innen kennen die Empfehlung: 60 bis 90 Gramm Kohlenhydrate pro Stunde. Trotzdem erreichen bei Fahrten über zweieinhalb Stunden nur rund 30 % diese Menge [BELEG FEHLT · Quelle; ohne Quelle streichen]. Eine Studie zeigt sogar, dass das Wissen um die Empfehlung nicht vorhersagt, wie viel tatsächlich gegessen wird (Sampson et al., European Journal of Sport Science, 2024).
>
> Meine eigene Umfrage unter 11 Ausdauersportler:innen (10 davon fahren Rennrad oder Gravel) zeigt dasselbe Muster: Das Wissen ist da – 6 von 11 planen schon mit einem Gramm-Ziel pro Stunde. Angepasst wird trotzdem kaum: 8 von 11 ändern ihre Verpflegung selten oder nie, wenn es heiß wird oder die Fahrt hart. Und es geht schief: 10 von 11 hatten im letzten Jahr mindestens einmal einen Hungerast oder Magenprobleme, obwohl sie sich vorbereitet hatten.
>
> Strecke, Temperatur, Intensität und die Produkte, die gerade zu Hause liegen, machen die Rechnung schwer. Am Ende wird geraten.

Etikett: `BELEG · Umfrage n = 11`
Bild: `Screenshot 2026-09-27 at 16-26-29 Planung der Kohlenhydrataufnahme während des Ausdauersports.png` (Ausschnitt: die drei Fragen zu Planung, Anpassung und Fehlschlägen) – Kontextsatz: „Drei Fragen aus meiner Umfrage nebeneinander: Die meisten planen mit einem Ziel, passen es aber nicht an – und fast alle hatten im letzten Jahr Probleme.“

Korrektur gegenüber der Case-Datei: „54 % fühlen sich sehr unsicher“ gibt die Umfrage nicht her – auf der Skala 1–5 liegen 6 von 11 bei 3 oder 4, niemand bei 5. „36,4 % verlieren Spaß“ passt ebenfalls nicht: 5 von 11 stimmen der Aussage mit 4 oder 5 zu. Ich verwende nur die drei Werte oben.

Zielgruppe: Ich habe mich auf ambitionierte Hobby- und Amateurfahrer:innen ohne Betreuerteam konzentriert. Profis haben Betreuer, die genau diese Rechnung übernehmen – Hobbyfahrer:innen stehen damit allein.

**C3 · Prozess**
Einleitung: Vier Entscheidungen haben den Fueling Calculator geformt. Bei jeder stand eine naheliegende Alternative im Raum.

*Wendepunkt 1 · Welche Idee?*
`ENTSCHEIDUNG` Der Tour-Übersetzer: ein situativer Rechner, der für genau eine Fahrt eine Packliste erstellt.
`VERWORFEN` Strategie-Baukasten mit gespeicherten Presets · Erfahrungs-Logbuch zur Auswertung nach der Fahrt
Warum: Das war das Ergebnis meiner MVP-Erarbeitung. Der Übersetzer löst den Kern-Moment – den Plan vor einer konkreten Tour –, und Baukasten und Logbuch bauen auf ihm auf [PRÜFEN · stimmt diese Begründung?]. Die beiden anderen Ideen sind als spätere Ausbaustufen vorgesehen.

*Wendepunkt 2 · Mit welchen Produkten wird gerechnet?*
`ENTSCHEIDUNG` Mit dem, was Nutzer:innen besitzen – auch Banane, Feigen und Cola aus dem Supermarkt.
`VERWORFEN` Ein Produktkatalog einer Marke.
Warum: Der Maurten Fuel Planner plant nur mit eigenen Produkten und verwandelt eine grobe Selbsteinschätzung in exakte Werte, denen man die Schätzung nicht mehr ansieht. Für eine Zielgruppe, der Profi-Produkte oft zu teuer sind, ist das keine Hilfe.

*Wendepunkt 3 · Wo endet das Ergebnis?*
`ENTSCHEIDUNG` Bei einer Packliste: was in welche Flasche und welche Trikottasche kommt.
`VERWORFEN` Eine Gesamtmenge in Gramm pro Stunde.
Warum: Eine Zahl muss man wieder selbst übersetzen – genau das Problem, das gelöst werden soll. In der Journey Map ist das Ziel der Moment „Ich packe einfach“.
Bilder: `WF_zwischenstand_03_teil2.jpg` neben `MF2 – Plan – Packliste.jpg` (Lo-Fi neben Final)

*Wendepunkt 4 · Wie viel Transparenz?*
`VERWORFEN` Volle Transparenz überall: bei jedem Wert zeigen, ob er geschätzt ist und wie er zustande kommt. Das war mein ursprünglicher Anspruch.
`BEFUND · Usability-Test, 4 Personen` Es hat eine Weile gedauert, bis die Testpersonen das Ergebnis vollständig und korrekt erfasst hatten. Gleichzeitig erzeugten vorbelegte Werte wie Ort und Startzeit Misstrauen, weil ihre Herkunft nicht sichtbar war.
`ENTSCHEIDUNG` Transparenz dosieren: sichtbar, wo ein Wert das Ergebnis stark beeinflusst, im Detail erst auf Nachfrage im Tab „Herleitung“.
Warum: Schon beim Gestalten und dann im Test habe ich gemerkt, dass Transparenz und schnelles Erfassen gegeneinander arbeiten. Ich musste einen Mittelweg finden.
Änderungen nach dem Test: Ort und Startzeit sind als änderbar gekennzeichnet · die Wahl zwischen Fertigpulver und Eigenmischung ist ergänzt.
Testpersonen: 4 · Interviews vorab: 3
Bild: `MF2 – Plan – Herleitung.jpg` – Kontextsatz: „Im Tab Herleitung sieht man, wie gerechnet wurde; geschätzte Werte tragen ein Etikett, und eine kleine Tabelle zeigt, wie sich der Flüssigkeitsbedarf bei anderen Temperaturen ändert.“

*Artefakte*
- Persona Joshua als HTML-Karte, verdichtet aus 3 Interviews und der Umfrage (n = 11), Etikett `BELEG · 3 Interviews · Umfrage n = 11`. Bild: `grafiken/bike.svg` statt Foto. Zitat: „Das Wissen hab ich eigentlich. Aber das Übertragen auf den ganz konkreten Tag mit Hitze und Intensität ist das Wackelige, da rät man dann oft nur noch.“ – Etikett `BELEG · Interview`
- `Customer Journey.png` – Kontextsatz: „Die Journey Map zeigt, wo Zweifel entstehen: nicht bei der Eingabe, sondern beim Blick auf das Ergebnis – ‚Kann ich einem Rechner mehr trauen als mir selbst?‘“
- `User-Flow_v3.jpg` – Kontextsatz: „Der Flow geht von der Zweitnutzung aus: Profil und Vorrat sind gespeichert, neu eingegeben wird nur, was die Tour betrifft.“
- `User-Story-Mapping-Zweite-Nutzung_teil-1.jpg` / `_teil-2.jpg` – Kontextsatz: „In der User Story Map habe ich den MVP geschnitten: Die markierten Aufgaben braucht man für einen Plan; Vorlagen, Nachschub unterwegs und Export kommen später.“

**C4 · Die Lösung**
Aussage: Ein Plan in 2–3 Minuten, nach dem man direkt packen kann.
Einleitung: Der Wizard fragt in fünf Schritten nur, was sich pro Tour ändert. Danach zeigt der Plan in vier Tabs, was zu tun ist – und auf Wunsch, warum.

Key Screens mit Kontextsatz:
1. `MF2 – Wizard – Profildaten.jpg` – „Beim zweiten Plan ist das Profil schon gespeichert und wird nur bestätigt. FTP und Schweißrate tragen das Etikett ‚Geschätzt‘, weil sie aus dem Fitnesslevel abgeleitet sind und das Ergebnis stark beeinflussen.“
2. `MF2 – Wizard – Intensität (vor Auswahl).jpg` – „Statt Watt einzugeben, wählt man, wie sich die Fahrt anfühlen wird – beschrieben über das Sprechen. Das war von Anfang an meine Entscheidung – in der Journey Map steht beim Einstieg der Satz „meine FTP weiß ich gerade nicht“ [PRÜFEN · passt das als Begründung?]. Wer Daten hat, kann Herzfrequenz oder Leistung genauer angeben.“
3. `MF2 – Wizard – Produkte wählen.jpg` – „Hier wählt man aus dem eigenen Vorrat. Profi-Produkte und Supermarktprodukte stehen gleichberechtigt nebeneinander, weil die App an keine Marke gebunden ist.“
4. `MF2 – Plan – Übersicht.jpg` – „Die Übersicht zeigt zuerst die zwei Zahlen, die zählen, und direkt darunter, wie genau sie sind: Zwei Werte sind geschätzt, deshalb steht die Genauigkeit auf ‚mittel‘.“
5. `MF2 – Plan – Packliste.jpg` – „Die Packliste trennt nach Trikottaschen und Flaschen und lässt sich abhaken. Im Test wurde sie sofort als Handlungsanweisung gelesen.“

Ladescreen als sechstes Bild: `Berechnung_03.jpg` – „Während gerechnet wird, füllt sich eine Flasche, und eine Liste zeigt, welcher Schritt gerade läuft – so ist die Wartezeit nachvollziehbar statt leer.“

Bewusste Abweichung vom Gerüst: Kein klickbarer oder animierter Kern-Flow – auf Moritz' Wunsch (27.09.2026). Die Key Screens stehen in der Reihenfolge des Flows und ersetzen ihn.

**C6 · KI im Prozess**
Aussage: KI war durchgehend mein Sparringspartner, um schneller zu werden – jedes Ergebnis habe ich selbst hinterfragt, bevor ich es übernommen habe.

| Werkzeug | Wofür |
|---|---|
| Perplexity [PRÜFEN · Schreibweise, im Gespräch „Complexity“] | Desk Research |
| NotebookLM | Interviews und Umfrage auswerten |
| Claude, Gemini | Sparring über den ganzen Prozess |
| KI-Agents in Figma | Unterstützung beim Gestalten |
| Google Stitch | kurz ausprobiert, kaum genutzt |

**C8 · Designsystem der App**
Aussage: Drei Farben, zwei Radien, zwei Signale – jede Regel hat einen Grund.
- Tinte gibt Struktur, Gelb zeigt das Ergebnis, Grau zeigt Unsicherheit. Gelb ist nie Textfarbe, nur Markerfläche hinter dunklem Text.
- Radius 0 für alles, was man liest; Radius 999 für alles, was man antippt. So erkennt man ohne Nachdenken, was interaktiv ist.
- Zwei unabhängige Signale: Eine graue Fläche heißt „geschätzt“, ein Rahmen in Tinte heißt „editierbar“. Beide bleiben getrennt, weil ein Wert geschätzt und trotzdem nicht änderbar sein kann – oder umgekehrt.
- Schrift: Archivo Expanded Bold für Zahlen und Überschriften, Archivo für Text.

Bilder: `moodboard-v3-radius_zugeschnitten.jpg` – Kontextsatz: „Das Moodboard legt Farben, Typografie und Tonalität fest: ‚Zahl zuerst. Unsicherheit benennen.‘“ · `moodboard-v3-radius_zugeschnitten_teil2.jpg` – Kontextsatz: „Die Komponenten zeigen die Radius-Regel: eckige Datenzeilen, runde Buttons und Tabs.“
Farbwerte: [PRÜFEN · Gelb im Moodboard `#FCDB32`, in der Case-Datei `#FFE01B` – welcher gilt?]

**C7 · Learnings**
1. **Transparenz braucht eine Dosis.** Wer jeden Wert erklärt, macht das Ergebnis schwerer lesbar. Entscheidend ist, wo die Erklärung steht – und dass sie auf Nachfrage da ist.
2. [PLATZHALTER · Was du beim nächsten Mal anders machen würdest – in einem Satz]

Ausblick: Geschätzte Werte werden selbst zur antippbaren Pille; ein Bottom Sheet erklärt, woher der Wert kommt, wie stark er wirkt und wie man ihn anpasst. Die Ideen Strategie-Baukasten und Erfahrungs-Logbuch sind die nächsten Ausbaustufen.

Ungelöst: Monetarisierung. Affiliate- oder Partnermodelle würden die Markenneutralität untergraben – eine gute Antwort habe ich noch nicht.

**C11 · Abschluss**
> Ich bin Moritz, UX-/UI-Designer aus Kiel. Wenn du über den Fueling Calculator oder eine offene Stelle sprechen möchtest, schreib mir.

mail@moritzfrommelt.de · LinkedIn · Lebenslauf (PDF)
Nächster Case: Second Brain – Case Study folgt →

---

## 5b · Bildverzeichnis mit Kontextsätzen

Jedes Bild in `media/`, mit Einsatzort und Kontextsatz (Was kann man hier tun, warum sieht es so aus?). Dekorative Grafiken bekommen `alt=""`.

| Datei | Einsatz | Kontextsatz |
|---|---|---|
| `MF2 – Wizard – Profildaten.jpg` | C4 Key Screen 1 | Beim zweiten Plan ist das Profil gespeichert und wird nur bestätigt. FTP und Schweißrate tragen das Etikett „Geschätzt“, weil sie aus dem Fitnesslevel abgeleitet sind und das Ergebnis stark beeinflussen. |
| `MF2 – Wizard – Tourdaten.jpg` | C4 (Galerie) | Hier gibt man Dauer, Distanz und Höhenmeter ein. Die Dauer steht allein oben, weil sie der wichtigste Wert für die Berechnung ist; alles andere erhöht nur die Genauigkeit. |
| `MF2 – Wizard – Bedingungen.jpg` | C4 (Galerie) | Das Wetter wird für Ort und Startzeit vorgeschlagen und lässt sich anpassen. Nach dem Test steht die Herkunft der Werte sichtbar dabei, weil vorbelegte Werte ohne Herkunft Misstrauen erzeugt hatten. |
| `MF2 – Wizard – Intensität (vor Auswahl).jpg` | C4 Key Screen 2 | Statt Watt einzugeben, wählt man, wie sich die Fahrt anfühlen wird – beschrieben über das Sprechen. Wer Daten hat, kann Herzfrequenz oder Leistung genauer angeben. |
| `MF2 – Wizard – Produkte wählen.jpg` | C4 Key Screen 3 | Hier wählt man aus dem eigenen Vorrat. Profi- und Supermarktprodukte stehen gleichberechtigt nebeneinander, weil die App an keine Marke gebunden ist. |
| `Berechnung_03.jpg` | C4 Ladescreen | Während gerechnet wird, füllt sich eine Flasche, und eine Liste zeigt, welcher Schritt gerade läuft – so ist die Wartezeit nachvollziehbar statt leer. |
| `MF2 – Plan – Übersicht.jpg` | C1 Hero, S3 Karte, C4 Key Screen 4 | Die Übersicht zeigt zuerst die zwei Zahlen, die zählen, und direkt darunter, wie genau sie sind: Zwei Werte sind geschätzt, deshalb steht die Genauigkeit auf „mittel“. |
| `MF2 – Plan – Packliste.jpg` | C1 Hero, C3 WP 3, C4 Key Screen 5 | Die Packliste trennt nach Trikottaschen und Flaschen und lässt sich abhaken. Im Test wurde sie sofort als Handlungsanweisung gelesen. |
| `MF2 – Plan – Mix.jpg` | C4 (Galerie) | Für jede Flasche steht, wie viel Maltodextrin, Fruktose und Natrium hineinkommen. Passt nicht alles in die Flaschen, sagt die App oben, wie viel auf feste Produkte verlagert wurde. |
| `MF2 – Plan – Herleitung.jpg` | C3 WP 4 | Im Tab Herleitung sieht man, wie gerechnet wurde. Geschätzte Werte tragen ein Etikett, und eine kleine Tabelle zeigt, wie sich der Flüssigkeitsbedarf bei anderen Temperaturen ändert. |
| `WF_zwischenstand_03_teil1_wizard.jpg` | C3 WP 3 (Lo-Fi) | Die Wireframes des Wizards: Schon hier fragt jeder Schritt nur eine Sache, und geschätzte Werte sind grau hinterlegt. |
| `WF_zwischenstand_03_teil2.jpg` | C3 WP 3 (Lo-Fi neben Final) | Die Wireframes des Plans mit vier Tabs. Neben dem finalen Screen sieht man, dass die Struktur blieb und sich vor allem die Gewichtung der Zahlen geändert hat. [PRÜFEN] |
| `User-Flow_v3.jpg` | C3 Artefakte | Der Flow geht von der Zweitnutzung aus: Profil und Vorrat sind gespeichert, neu eingegeben wird nur, was die Tour betrifft. |
| `User-Story-Mapping-Zweite-Nutzung_teil-1.jpg` / `_teil-2.jpg` | C3 Artefakte | In der User Story Map habe ich den MVP geschnitten: Die markierten Aufgaben braucht man für einen Plan; Vorlagen, Nachschub unterwegs und Export kommen später. |
| `Customer Journey.png` | C3 Artefakte | Die Journey Map zeigt, wo Zweifel entstehen: nicht bei der Eingabe, sondern beim Blick auf das Ergebnis – „Kann ich einem Rechner mehr trauen als mir selbst?“ |
| `Screenshot 2026-09-27 at 16-26-29 Planung der Kohlenhydrataufnahme während des Ausdauersports.png` | C2 (Ausschnitt) | Drei Fragen aus meiner Umfrage: Die meisten planen mit einem Ziel, passen es aber nicht an – und fast alle hatten im letzten Jahr Probleme. |
| `umfragen.png` | nicht verwendet | ersetzt durch den vollständigen Umfrage-Screenshot |
| `persona.jpg` | nicht verwendet | Foto ohne Nutzungsrecht; Persona wird als HTML-Karte nachgebaut |
| `moodboard-v3-radius_zugeschnitten.jpg` | C8 | Das Moodboard legt Farben, Typografie und Tonalität fest: „Zahl zuerst. Unsicherheit benennen.“ |
| `moodboard-v3-radius_zugeschnitten_teil2.jpg` | C8 | Die Komponenten zeigen die Radius-Regel: eckige Datenzeilen, runde Buttons und Tabs. |
| `moodboard-v3-radius.jpg` | nicht verwenden | enthält fremde Bilder |
| `profil/pb_komprimiert_v3.jpg` | S5 | (Porträt, kein Kontextsatz nötig) Alt: „Moritz Frommelt, lächelnd, mit verschränkten Armen vor dunklem Hintergrund“ |
| `profil/2f448be7.jpg`, `a6ec9305.jpg`, `c7d60bb3.jpg`, `pb_komprimiert.jpg`, `_v2.jpg` | Reserve | Originale für den WebP-Export in Schritt 10 |
| `grafiken/bike.svg` | C3 Persona-Karte | Illustration statt Foto, `alt=""` (dekorativ) |
| übrige `grafiken/*.svg` | ggf. Abschnitts-Icons | dekorativ, `alt=""` |

## 6 · Offene Punkte

Siehe `offene-punkte.md`.
