# CLAUDE.md – Portfolio Moritz Frommelt

Stand: 07.10.2026. Diese Datei ist verbindlich. Aktuelle offene Punkte: `offene-punkte.md` (maßgeblich, nicht hier duplizieren).

## PROJEKT
Statische Portfolio-Website für Moritz Frommelt, UX-/UI- und Product Designer aus Kiel (B.Eng. Medieningenieur, Weiterbildung Product Design bei Digitale Leute). Hauptcase: Fueling Calculator; zweiter Case (Bachelorarbeit Second Brain) ist nur als Karte angedeutet. Zielgruppe: Recruiterinnen und Design Leads, die in rund zwei Minuten verstehen wollen, welches Problem er gelöst hat, was er gebaut hat und wie er denkt [PRÜFEN · Branche, Firmengröße]. Ziel: Einladung zum Gespräch für eine Festanstellung.

## STAND UND NÄCHSTE SCHRITTE
Moritz arbeitet mit einem 13-Schritte-Masterprogramm (siehe ARBEITSWEISE). Fertig: Schritte 1–9 (Ordner, Material, Konzept, Texte, Bau, Verbesserungsrunden). Danach:
- **Schritt 10 (Bilder nach WebP): bewusst vertagt**, solange er Bilder und Prototyp noch überarbeitet (offene-punkte B20). Kurz vor Schritt 13 nachholen; `media/webp/` enthält nur Testuploads, neu befüllen lassen. Auf diesem Rechner gibt es kein WebP-Werkzeug; Moritz exportiert per squoosh.app (WebP, Qualität 80). Alle echten Bilder sind unter 1600 px, nur umwandeln, nicht verkleinern.
- **Schritt 11 (Qualität prüfen): als Nächstes**, wartet auf sein „weiter". Prüft Kontrast, Semantik, Alt-Texte, Tastatur/Skip-Link, Meta (Title, Description unter 155 Zeichen, Vorschaubild 1200×630 mit absoluter URL), Responsive 320–1920 px, Kontextsätze, Platzhalter zählen. Probleme mit Zeilennummern, nach Schwere sortiert, dann einzeln reparieren.
- **Schritt 12: Impressum und Datenschutz.** `impressum.html` und `datenschutz.html` existieren noch nicht, die Footer verlinken sie bereits (404). Als gekennzeichnete Vorlagen mit Platzhaltern, keine Rechtssicherheit behaupten, Datenschutz für den einfachsten Fall (statisch, kein Formular, keine Statistik, keine Einbettungen). Die Anschrift liefert Moritz selbst (steht nicht mehr im Projekt, nie in diese Datei schreiben).
- **Schritt 13: Veröffentlichung, Plan hat sich geändert.** Das Repo liegt auf GitHub (`Moritz-F/portfolio`, Branch `main`), `CNAME` = `moritzfrommelt.de`. Stand 07.10.: Die Domain antwortet mit GitHub-404, GitHub Pages ist also vermutlich noch nicht aktiviert [PRÜFEN]. Damit entfallen `.htaccess`, FileZilla/Strato und das ZIP; stattdessen Pages-Einstellung (Branch/Root, HTTPS erzwingen). Neu zu klären: Alles im Repo wäre öffentlich (siehe Blocker 4). Dateinamen vor der Veröffentlichung klein, ohne Umlaute/Leerzeichen/Gedankenstriche umbenennen (Pages unterscheidet Groß-/Kleinschreibung). Am Ende `naechste-schritte.md` mit drei Punkten für die Woche danach.

**Blocker vor Veröffentlichung:**
1. `impressum.html`/`datenschutz.html` fehlen (Schritt 12).
2. `case-fueling-calculator.html` bindet `media/moodboard-v3-radius_zugeschnitten_teil2.jpg` ein, die Datei wurde gelöscht (kaputtes Bild; eine `.webp` liegt in `media/webp/`).
3. Sichtbare Platzhalter und Bildlücken (offene-punkte A5, A9, A14, B15–B19, C1).
4. Repo-Hygiene: Im Repo liegen u. a. `referenzen/` (Screenshots fremder Seiten), `media/persona.jpg` (kein Nutzungsrecht), `unterlagen/altes-Portfolio/`, `konzept.md`, `offene-punkte.md`, Werkzeug-Ordner `.agents/` und `skills-lock.json` (Skills, nicht Teil der Seite) sowie `media/webp/` (Testuploads). `media/webp/moodboard-v3-radius.webp` ist bewusst nicht committet (fremde Bilder). Vor Aktivierung von Pages mit Moritz klären (`.gitignore` oder eigener Veröffentlichungsordner). Der frühere Lebenslauf mit privaten Daten ist nie committed worden, so lassen.

## ARBEITSWEISE
- Deutsch, kurz, keine Einleitungen wie „Gerne!", keine Zusammenfassung von Dingen, die er gerade gelesen hat.
- Masterprogramm: Schritte strikt in Reihenfolge, ein Schritt pro Nachricht, danach auf „weiter" warten. Format: `SCHRITT n · Name`, Arbeit, `FERTIG, WENN: …` (am echten Zustand geprüft), `Sag „weiter", wenn …`. Reihenfolge: 1 Ordner prüfen · 2 Material auswerten · 3 Verbindung · 4 CLAUDE.md · 5 Abschnitte und Konzept · 6 Konzept prüfen · 7 Inhalte erfragen · 8 Bauen · 9 Verbessern und Lücken füllen · 10 Bilder · 11 Qualität · 12 Impressum/Datenschutz · 13 Paket und Veröffentlichen.
- Nichts erfinden: keine Projekte, Zahlen, Kunden, Zitate, Auszeichnungen, kein Lorem Ipsum, keine Zahl ohne Quelle, die Moritz genannt hat. Fehlendes wird als sichtbarer Platzhalter markiert und in `offene-punkte.md` geführt.
- Widersprüche ansprechen statt still auflösen (Beispiele aus der Praxis: Datumsangaben zwischen CV und Case, Pfadkonventionen). Vor größeren Änderungen kurz sagen, was kommt; danach in einem Satz, was sich geändert hat.
- Moritz nutzt kein Terminal und öffnet Dateien per Doppelklick. Nichts installieren; fehlt ein Werkzeug, in einem Satz sagen, was er tun muss. Für Browser-Tests darf ein lokaler Server (`python -m http.server`) kurz laufen und wird danach gestoppt, weil das Vorschaufenster `file://` ohne CSS und Bilder lädt.
- Löschen nur nach Rückfrage; Bilddateien nie löschen, wenn nur die Einbindung entfällt.
- Git: Commit/Push nur auf Wunsch, direkt auf `main`. Autor-Adresse repo-lokal die GitHub-noreply-Adresse (`73314151+Moritz-F@users.noreply.github.com`); die globale Git-Adresse ist eine Isogon-Adresse und darf hier nicht verwendet werden. Commits enden mit der Co-Authored-By-Zeile.
- Quellen der Wahrheit: Inhalte der Case in `referenzen/case-study-fueling-calculator.md` (Zahlen, Entscheidungen), Lebenslauf in `unterlagen/Lebenslauf_Moritz-Frommelt_final.pdf` (bereinigt, öffentlich), Konzept in `konzept.md` (teils überholt, im Zweifel gewinnt der HTML-Stand).

## AUFBAU
- `index.html`: Kopfzeile + Einstieg im Wrapper `.hero-zone` (trägt den Farbverlauf), dann `<main>`: Case Studies `#cases` (Karte Fueling Calculator mit Ziel-KPIs, Karte Second Brain als Teaser), Weitere Projekte `#weitere-projekte` (5 Kacheln mit `tile-*.png`), Über-mich-Teaser `#ueber-mich`, Kontakt `#kontakt`, Footer.
- `case-fueling-calculator.html`: Hero, „Auf einen Blick", Kapitel `#problem` `#prozess` `#loesung` `#ki` `#designsystem` `#learnings`, Kontakt `#kontakt`. Prozess = Persona, 4 Wendepunkte (Entscheidung / Verworfen / Befund / Warum). Lösung = 3 Screens. Auf rund 7 echte Bilder gekürzt, 4 Platzhalter `[BILD FOLGT: …]`.
- `ueber-mich.html`: h1, Profiltext, Platzhalter „So arbeite ich" und „Abseits vom Design", Werdegang-Liste, 5 Werkzeuge, Lebenslauf-Download.
- `style.css` (alles), `CNAME`, `media/` (`MF2 – …` App-Screens, `tile-*.png` 800×500 mit weißem Rand, `profil/`, `grafiken/` SVG, `fonts/` Manrope TTF, `webp/`), `unterlagen/`, `referenzen/` (Vorbilder, nur intern).
- Nicht vorhanden: `impressum.html`, `datenschutz.html`, `case-second-brain.html`.

## ENTSCHEIDUNGEN (nicht ohne Rückfrage ändern)
- Schrift Manrope (lokal, Variable `--font-sans`). Palette Indigo, Lavendel, Aprikose aus dem Lebenslauf; Light und Dark. Dark = fast Schwarz mit neutralen Grautönen, helles Indigo als Primärfarbe mit Leuchtschatten. Case-Farben (Gelb, Papier-Weiß) nie im Portfolio-Design.
- Kopfzeile: Glas-Pill, ab 60 em `position: fixed` (nicht sticky, die Hero-Zone ist zu kurz), mobil im Fluss. Nav: Case Studies, Weitere Projekte, Über mich (`ueber-mich.html`, `aria-current="page"` auf der eigenen Seite), Kontakt. Kein Lebenslauf in der Nav, dafür in allen Footern.
- Links relativ (`index.html#cases`, `ueber-mich.html`), keine root-absoluten Pfade (Doppelklick-Test und Pages).
- Herkunfts-Etiketten (Beleg, Befund, Entscheidung, Verworfen) nur in der Case Study. Auf der Startseite stehen Ziel-KPIs (≥ 85 % / ≥ 50 % / ≥ 70 %), klar als „Ziel-KPI, nicht gemessen" gekennzeichnet.
- Kein klickbarer Kern-Flow in der Case Study (Wunsch). Intensität per Auswahl statt Watt war von Anfang an Moritz' Entscheidung.
- Fakten: Fueling Calculator Einzelprojekt, 06.–10.2026; Umfrage n = 11, 3 Interviews, 4 Testpersonen; Persona ohne Foto (Illustration `grafiken/bike.svg`). Die „rund 30 %" im Problem-Kapitel haben keine Quelle (A5).
- Über-mich-Fließtext: bewusst die ausführlichere frühere Fassung. Dort keine Gedankenstriche im Fließtext (Datumsbereiche mit Halbgeviertstrich sind ok).
- Kontakt: „Aktuell suche ich eine Festanstellung …", keine Zusage zur Antwortzeit.

## KONVENTIONEN (Code)
- Keine Frameworks, kein Build, nichts von fremden Servern (keine Skripte, Schriften, Einbettungen, Cookie-Banner, Statistik).
- Farben, Größen, Abstände nur als Variablen in `:root` von `style.css`; im restlichen CSS keine rohen Werte. Farbrollen statt Farbnamen (`--color-primary`). Neue Werte zuerst als Variable anlegen. Breakpoints 30 / 40 / 60 em.
- Vorhandene Komponenten wiederverwenden: `.section`, `.container`, `.stack(-lg)`, `.grid--2/--3`, `.card`, `.tag` (`--decision`, `--rejected`, `--finding`, `--kpi`, `--status`), `.stage` + `.screen`, `.ph` / `.ph-img`, `.case-card` (`__content`, `__media`, `--reverse`), `.case-stats`, `.turn`, `.persona`, `.screens`, `.timeline`, `.inline-list`, `.button--primary/--secondary`, `.eyebrow`. Neue Seite = Kopfzeile, Footer und Theme-Skript von einer bestehenden Seite kopieren.
- Qualität: semantisches HTML, eine `h1` pro Seite, keine Überschriftensprünge, Kontrast AA (4,5:1 / 3:1) in beiden Modi, sichtbarer Fokusring, Zustände nie nur über Farbe, `prefers-reduced-motion` und `prefers-reduced-transparency` beachten, mobil ab 320 px. Glas nur an Kopfzeile und Pills.
- Bilder: `width` und `height` immer; `loading="lazy" decoding="async"` unterhalb des ersten Bildschirms, Hero-Bilder ohne `lazy`. Ziel-Format WebP (Schritt 10). Jeder Screen braucht einen Kontextsatz: Was kann man tun, warum sieht es so aus.
- Platzhalter: `[PLATZHALTER · …]` Text, `[BILD FOLGT: …]` Bild in der Case Study (`.ph-img`), `[BELEG FEHLT]` Zahl ohne Quelle, `[PRÜFEN · …]` unsicher. TODOs zusätzlich als HTML-Kommentar im Code.
- Verboten: Bilder ohne Nutzungsrecht (Persona-Foto, fremde Bilder im Moodboard), fremde Marken als Gestaltungsmittel.
