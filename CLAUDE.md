# CLAUDE.md – Portfolio Moritz Frommelt

## PROJEKT
Gebaut wird eine statische Portfolio-Website für Moritz Frommelt, UX-/UI-Designer aus Kiel (B.Eng. Medieningenieur, Weiterbildung Product Design bei Digitale Leute), mit dem Fueling Calculator als Hauptcase. Sie richtet sich an Recruiterinnen und Design Leads, die in rund zwei Minuten verstehen wollen, welches Problem er gelöst hat, was er gebaut hat und wie er denkt [PRÜFEN · Zielgruppe genauer: Branche, Firmengröße]. Ziel ist eine Einladung zum Gespräch für eine Festanstellung als UX-/UI- bzw. Product Designer.

## TECHNIK
- Statische Seite, keine Frameworks, kein Build-Schritt.
- Dateien: `index.html`, `case-*.html` je Case, eine gemeinsame `style.css`, `impressum.html`, `datenschutz.html`.
- Nichts von fremden Servern: keine Skripte, keine Schriften, keine Einbettungen.
- Systemschriften oder Schriftdateien lokal aus `media/fonts/`. Die Schrift steht als eine Variable in `style.css`, damit sie mit einer Zeile tauschbar ist (gewählt: Manrope).
- Bilder als WebP mit `width` und `height` im HTML; unterhalb des ersten Bildschirms `loading="lazy"` und `decoding="async"`.

## DESIGN
- Farben, Schriftgrößen und Abstände als benannte CSS-Variablen ganz oben in `style.css`. Im restlichen CSS danach keine rohen Werte mehr.
- Farben mit Rollennamen, nicht mit Farbnamen: `--color-primary`, `--color-accent`, `--color-success` statt `--blau`.
- Zwei Modi: Light und Dark, beide vollständig. Jede Farbrolle hat einen Wert pro Modus, jedes Paar besteht den Kontrast in beiden Modi.
- Runde Ecken, Buttons und Tags als Pills. Glaseffekt (Blur, Transparenz) nur für Kopfzeile und Pills, nie hinter Fließtext; bei `prefers-reduced-transparency` undurchsichtige Ersatzfläche.
- Die Portfolio-Palette ist unabhängig von den Farben der gezeigten Projekte. Case-Farben (z. B. Gelb, Papier-Weiß des Fueling Calculators) tauchen nur in den Screens auf, nie im Portfolio-Design.
- Screens stehen auf einer eigenen Bühnenfläche aus der Portfolio-Palette, mit je einem Wert für Light und Dark.

## QUALITÄT
- Semantisches HTML, eine `h1` pro Seite, Überschriften ohne Sprung.
- Kontrast mindestens WCAG AA: 4,5:1 für normalen, 3:1 für großen Text.
- Sichtbarer Fokusring auf allen interaktiven Elementen.
- Jeder Zustand über mindestens zwei Merkmale, nie nur über Farbe.
- `prefers-reduced-motion` respektieren.
- Mobile first, ab 320 px nutzbar.

## INHALTSREGELN
- Jeder Screenshot braucht einen Satz Kontext: Was kann man hier tun, und warum sieht es so aus?
- Kurze Absätze, klare Überschriften, keine Textwände. Jede Sektion folgt Aussage → Beleg → Ergebnis.
- Zahlen immer mit Bedeutung, nie als Dekoration. Stichproben nennen (z. B. Umfrage n = 11).
- Zitate nur verwenden, wenn klar ist, woher sie stammen (Interview, Umfrage, Test). Verdichtete Stimmen aus Persona oder Journey Map als solche kennzeichnen, nicht als wörtliches Zitat einer Person.

## PLATZHALTER
Fehlende Inhalte werden nie erfunden, sondern markiert:
- Text: `[PLATZHALTER · Was hier hingehört, in einem Satz]`
- Zahl: `[BELEG FEHLT]` hinter jeder Zahl, die Moritz nicht selbst genannt oder belegt hat
- Unsicher: `[PRÜFEN]`
- Bild: grauer Rahmen im richtigen Seitenverhältnis mit Beschriftung „Platzhalter · Breite × Höhe px · was hier hingehört“

Alle offenen Punkte stehen in `offene-punkte.md`.

## VERBOTE
- Keine erfundenen Projekte, Zahlen, Kunden, Testimonials oder Auszeichnungen.
- Kein Lorem Ipsum.
- Keine Zahl ohne Quelle, die Moritz genannt hat.
- Keine Cookie-Banner, keine Besucherstatistik, keine eingebetteten Fremdinhalte.
- Keine Bilder ohne Nutzungsrecht (z. B. Persona-Foto, fremde Bilder im Moodboard `moodboard-v3-radius.jpg`).

## ARBEITSWEISE
- Vor größeren Änderungen kurz sagen, was kommt.
- Nach Änderungen in einem Satz zusammenfassen, was sich geändert hat.
- Widersprüche ansprechen statt stillschweigend auflösen.
- Moritz arbeitet nicht mit dem Terminal: nichts installieren oder starten; wenn ein Werkzeug fehlt, in einem Satz sagen, was er tun muss.
