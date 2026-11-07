# Case Study: Fueling Calculator

Sep 29, 2026 · @Moritz Frommelt

## Arbeitsweise

Die Case Study ist eine Master-Story für Präsentation und Webseite. Sie folgt der Struktur aus Modul 5, Übung 3 und erzählt eine Geschichte statt eines Aufgaben-Recaps.

- **Bestätigt:** Abschnitt ist abgenommen und wird nur auf ausdrückliche Anfrage geändert.
- **Offen:** Abschnitt ist in Arbeit oder enthält noch Entscheidungen.
- Hinweise zu Präsentation vs. Webseite stehen nur dort, wo sich Darstellung oder Umfang unterscheiden.

**Zeitbudget Präsentation (5 Minuten):**

| Abschnitt | Dauer | Slides |
| --- | --- | --- |
| Titel und erster Satz | 0:10 | 1 |
| Problem | 1:00 | 3 |
| Fokus | 0:40 | 2 |
| Lösung & MVP | 0:40 | 2 |
| Kern-Flow (Live-Demo) | 1:00 | Demo |
| Testing & Iteration | 0:50 | 2 |
| Impact & Abschluss | 0:40 | 2 |

## 1. Hero (bestätigt)

Titelfolie und Webseiten-Hero haben unterschiedliche Aufgaben: Die Folie soll in zwei Sekunden erfasst werden, der Webseiten-Hero ist der erste Satz, den jemand liest.

### Titelfolie (Präsentation)

**Fueling Calculator**

Verpflegungsplaner für lange Ausdauereinheiten

Unten klein: Moritz Frommelt · Product Design Bootcamp, Digitale Leute · Datum

*Visualisierung:* Optional rechts ein Phone-Mockup der Plan-Übersicht, aufgebaut wie in Zwischenpräsentation 4.

### Erster gesprochener Satz

„Ich habe eine App entwickelt, die Ausdauersportler:innen einfach und zuverlässig zeigt, was sie auf langen Einheiten essen und trinken sollten.“

### Hero der Webseite

**Fueling Calculator**

Eine App, die Ausdauersportler:innen einfach und zuverlässig zeigt, was sie für eine lange Einheit essen und trinken sollten.

Meta-Zeile (Vorschlag): Portfolio-Projekt · Product Design Bootcamp, Digitale Leute · \[Zeitraum\] · Solo

*Visualisierung:* Plan-Übersicht im Phone-Mockup mit sichtbaren ≈-Pills, alternativ die Ladeanimation mit Flaschenfüllung als kurzes Loop-Video.

## 2. Das Problem (bestätigt)

Der Abschnitt führt Laien in fünf Blöcken von der Fueling-Erklärung zu den beiden zentralen Erkenntnissen.

### Block 1: Was ist Fueling?

Bei langen Ausdauereinheiten verbraucht der Körper vor allem Kohlenhydrate. Seine eigenen Speicher reichen bei höherer Intensität nur etwa anderthalb Stunden. Wer länger unterwegs ist, muss unterwegs nachlegen: typischerweise 60 bis 90 Gramm Kohlenhydrate pro Stunde, über Getränke, Gels, Riegel oder ganz normale Lebensmittel wie Bananen. Dieses gezielte Nachtanken heißt Fueling. Wer zu wenig aufnimmt, bricht ein. Wer zu viel oder das Falsche aufnimmt, bekommt Magenprobleme.

*Visualisierung:* Baut Moritz selbst in einem anderen Programm. Ziel: Einstieg ins Thema mit Charakter und wenig Text. Kernbotschaft: Die eigenen Speicher sind nach ≈ 90 Minuten leer.

### Block 2: Warum es in der Praxis schwierig wird

Die Zielwerte kennen ambitionierte Hobby-Ausdauersportler:innen meist. Schwierig wird es, wenn daraus ein Plan für eine konkrete Einheit werden soll. Hitze, Intensität und Dauer verändern den Bedarf, und statt teurer Markenprodukte landen oft Supermarktartikel oder selbst gemischte Getränke im Gepäck, deren Kohlenhydratgehalt niemand im Kopf hat.

### Block 3: Erkenntnis (Typo-Break)

> **Das Problem ist nicht fehlendes Wissen. Sondern die Übersetzung in die Praxis.**

*Präsentation:* Optional gesprochener Halbsatz „Ich dachte anfangs, es fehlt an Wissen. Aber …“. Keine Gegenüberstellung auf der Slide.

### Block 4: Beleg

6 von 11 Befragten verfolgen ein festes Gramm-Ziel pro Stunde. Nur 1 von 11 fühlt sich sicher, diese Menge in den eigenen Snacks zu bestimmen.

> „Das Wissen hab ich eigentlich. Aber das Übertragen auf den ganz konkreten Tag mit Hitze und Intensität ist das Wackelige, da rät man dann oft nur noch.“

*Visualisierung:* Kontrastgrafik 6/11 vs. 1/11 im Design-System, die Lücke dazwischen in Signal Yellow. Absolute Zahlen statt Prozent, weil die Stichprobe klein ist.

*Übergang zu Block 5, gesprochen:* „Naheliegend wäre, einfach einen der bestehenden Rechner zu nutzen. Aber die haben ein anderes Problem.“

### Block 5: Warum bestehende Tools das nicht lösen

Fueling-Rechner gibt es bereits, doch fast alle stammen von Herstellern von Sportnahrung. Sie planen überwiegend mit eigenen Produkten, und aus groben Selbsteinschätzungen werden exakte Werte, die im Ergebnis nicht mehr als Schätzung erkennbar sind. Nutzer:innen bleibt die Frage, ob die Empfehlung ihnen dient oder dem Verkauf.

> **Ein Plan hilft nur, wenn man ihm vertraut. Und Vertrauen entsteht durch Nachvollziehbarkeit.**

*Visualisierung:* Keine eigene Grafik. Die hervorgehobene Aussage trägt den Block allein.

### Präsentation vs. Webseite

- **Präsentation:** Block 1 und 2 mündlich mit Speicher-Grafik, dann eine Slide mit Erkenntnis und Beleg, dann eine Slide zu Block 5.
- **Webseite:** Alle fünf Blöcke untereinander, Erkenntnisse als große Typo-Breaks zwischen den Textblöcken.

## Top Insights (bestätigt)

Zwei frühe Insights begründen die Lösung, ein drittes Learning entsteht erst im Usability-Test.

| Insight | Quelle | Führt zu | Abschnitt |
| --- | --- | --- | --- |
| **Übersetzungsproblem:** Die Theorie gibt Richtwerte vor, aber Dauer, Intensität, Hitze und verfügbare Produkte verändern den Bedarf so stark, dass sie sich kaum auf den konkreten Tag anwenden lässt. | Research Modul 1 | Plan, der die Bedingungen des konkreten Tages berücksichtigt; die Packanweisung pro Flasche und Trikottasche ist das Ergebnis dieser Übersetzung. | Problem |
| **Vertrauen durch Nachvollziehbarkeit:** Bestehende Tools stammen von Herstellern und lassen Schätzungen wie Messwerte aussehen. | Wettbewerbsanalyse Modul 2 | Markenneutralität und transparente Herleitung | Problem |
| **Transparenz muss dosiert sein:** Zu viele Kennzeichnungen überfordern. | Usability-Test Modul 4 | ≈-Pill als passives Signal, Details im Bottom Sheet | Testing & Iteration |

## 3a. Fokus (bestätigt)

Der Abschnitt beantwortet die Frage, mit der das Problem endet: Für wen ist die Lücke am größten?

*Übergang vom Problem, gesprochen:* „Wenn das Problem nicht das Wissen ist, sondern die Übersetzung, dann war meine erste Frage: Für wen ist diese Lücke am größten?“

### Segment-Wahl

In der Research zeigten sich zwei Gruppen. Die eine kennt ihre Zielwerte, scheitert aber daran, sie an wechselnde Bedingungen wie Hitze oder hohe Intensität anzupassen. Die andere will teure Markenprodukte durch Supermarktartikel ersetzen, findet dafür aber keine verlässlichen Angaben. Ich habe mich auf die erste Gruppe konzentriert, weil dort die Unsicherheit am größten war: 6 von 11 Befragten fühlen sich vor langen Einheiten gestresst oder verunsichert, und selbst erfahrene Interviewpartner:innen gaben zu, bei Hitze oft nur zu raten. Das Bedürfnis der zweiten Gruppe verschwindet dabei nicht, es fließt in die Lösung ein: Die App rechnet auch mit Produkten aus dem Supermarkt.

### Persona

Stellvertretend für diese Gruppe steht Joshua. Er fährt ambitioniert Rennrad und Gravel, trainiert 7 bis 12 Stunden pro Woche und kennt seinen Zielwert. Trotzdem bleibt er vor langen Ausfahrten bei seiner Standard-Routine, weil ihm ein System fehlt, das sie an den Tag anpasst. Er will vor der Fahrt keine Rechnungen im Kopf machen, sondern sich darauf verlassen können, dass seine Verpflegung reicht.

*Visualisierung:* Kompakte Persona-Karte statt Miro-Template: Foto, Name, eine Zeile Kontext, zwei Bedürfnisse. Platz für eine Illustration. Kein Zitat, das steht schon im Problem-Abschnitt.

### Fokusmoment

Der Fokusmoment ist die Planung vor einer langen Radausfahrt. Rad steht stellvertretend für den Ausdauersport: Hier hatte ich den besten Zugang zu Testpersonen, und die Planung vereint viele Variablen auf einmal, nämlich lange Dauer, mehrere Flaschen und begrenzten Platz in den Trikottaschen.

### HMW (Typo-Break)

> **Wie können wir Joshua bei der Planung vor langen Einheiten unterstützen, sein Wissen in die Praxis umzusetzen und Unsicherheit zu reduzieren?**

*Hinweis:* Gegenüber Modul 1 leicht gekürzt, damit sie auf eine Slide passt und gesprochen funktioniert.

### Präsentation vs. Webseite

- **Präsentation:** Zwei Slides. Slide 1: Persona-Karte mit Illustration; Segment-Wahl und Fokusmoment werden gesprochen. Slide 2: nur die HMW.
- **Webseite:** Segment-Wahl, Persona-Karte, Fokusmoment, HMW als großer Typo-Break.

*Übergang zum nächsten Abschnitt, gesprochen:* „Mit dieser Frage bin ich in die Ideation gegangen. Und die erste wichtige Entscheidung war, was die App nicht sein soll: ein weiterer Hersteller-Rechner.“

*Lesefassung:* „Mit der HMW als Anker begann die Ideation. Die erste Entscheidung ergab sich direkt aus dem Vertrauens-Insight: Die App muss markenneutral sein.“

## 3b. Lösung & MVP (bestätigt)

Die drei Schlüsselentscheidungen erklären, warum die Lösung so aussieht, wie sie aussieht. Jede leitet sich aus einem Insight ab.

### Lösungsidee (Typo-Break)

> **Aus einer offenen Rechenaufgabe wird eine fertige Ansage.**

### Die drei Schlüsselentscheidungen

**1. Ein Plan für genau diesen Tag.** Das Übersetzungsproblem entsteht, weil jede Einheit anders ist. Die App fragt deshalb nur ab, was sich von Fahrt zu Fahrt ändert: Dauer, Intensität und Wetter. Körperdaten, Verträglichkeit und der eigene Produktvorrat sind im Profil hinterlegt, so dauert die Planung nur wenige Minuten. Das Ergebnis ist keine abstrakte Gramm-Zahl, sondern eine konkrete Ansage, was in welche Flasche und welche Trikottasche kommt.

**2. Markenneutral.** Weil bestehende Rechner von Herstellern stammen, rechnet die App ausschließlich mit dem, was Nutzer:innen selbst besitzen, vom Gel bis zur Supermarkt-Banane.

**3. Nachvollziehbar statt scheingenau.** Jede Zahl im Plan lässt sich herleiten. Geschätzte Werte sind als Schätzung erkennbar und sehen nicht aus wie Messwerte.

*Visualisierung:* Drei Entscheidungskarten nebeneinander, jeweils Insight klein oben, Entscheidung groß darunter. Bewusst ohne Screens; die folgen im Kern-Flow.

### MVP-Abgrenzung (nur Webseite)

Features wie ein Logbuch oder gespeicherte Pläne sind denkbar, habe ich fürs MVP aber bewusst zurückgestellt, um mich auf den Moment vor der Fahrt zu konzentrieren.

### Outcome

Nutzer:innen verlassen das Haus mit einer begründeten statt geratenen Menge und packen einfach nach Liste.

### Präsentation vs. Webseite

- **Präsentation:** Slide 1 nur die Lösungsidee. Slide 2 die drei Entscheidungskarten. MVP-Abgrenzung entfällt.
- **Webseite:** Lösungsidee als Typo-Break, die drei Entscheidungen, MVP-Abgrenzung, Outcome.

*Übergang zum Kern-Flow, gesprochen:* „Wie sich diese drei Entscheidungen anfühlen, zeigt am besten der Weg vom Start bis zum fertigen Plan.“

*Lesefassung:* „Die drei Entscheidungen prägen jeden Schritt der App. Am deutlichsten werden sie im Kern-Flow, vom Start bis zum fertigen Plan.“

## 4. Kern-Flow (bestätigt)

Der Abschnitt zeigt den finalen Hi-Fi-Stand, in den die Änderungen aus dem Test bereits eingeflossen sind. Er wird als Live-Demo präsentiert und auf der Webseite über Key Screens erklärt.

### Sprechspur für die Live-Demo (ca. 1,5 min)

1. **Start:** „Joshua will gleich eine Runde von dreieinhalb Stunden fahren. Er tippt auf ‚Neue Tour planen‘.“
2. **Profil und Tour:** „Seine Körperdaten sind hinterlegt, er bestätigt sie nur. Dann Dauer, Distanz und Höhenmeter.“
3. **Bedingungen und Intensität:** „Das Wetter kommt automatisch, er wählt nur noch, wie hart er fährt. Mehr fragt die App nicht, weil sich nur das von Fahrt zu Fahrt ändert.“ (Entscheidung 1)
4. **Vorrat:** „Er wählt aus, was er zu Hause hat. Das Gel steht direkt neben der Banane aus dem Supermarkt.“ (Entscheidung 2)
5. **Plan und Packliste:** „Das Ergebnis: seine Zielmenge und eine Liste, was in die Trikottaschen und was in die Flaschen kommt.“
6. **Herleitung:** „Und wenn er wissen will, woher die Zahl kommt, sieht er genau, wie gerechnet wurde und was davon geschätzt ist.“ (Entscheidung 3)

### Key Screens für die Webseite

| Screen | Kontext-Satz |
| --- | --- |
| Bedingungen | Die App fragt nur ab, was sich von Fahrt zu Fahrt ändert. Das Wetter wird automatisch übernommen. |
| Vorrat wählen | Sportprodukte und Supermarktartikel stehen gleichberechtigt nebeneinander. Geplant wird nur mit dem, was da ist. |
| Plan-Übersicht | Die fertige Ansage: Zielmenge pro Stunde, Gesamtmenge und ein Rhythmus für unterwegs. |
| Packliste | Aus Gramm werden Handgriffe. Jede Position lässt sich beim Packen abhaken. |
| Herleitung | Jede Zahl ist nachvollziehbar. Geschätzte Werte sind als solche markiert. |

Darunter der eingebettete klickbare Prototyp, alternativ ein kurzes Video des kompletten Flows.

*Visualisierung:* Nur finale Hi-Fi-Screens, keine MF2-Versionen. Auf der Webseite als Reihe von Phone-Mockups, der Kontext-Satz jeweils darunter. Mix-Tab kein eigener Key Screen, darf im Video vorkommen.

*Übergang zum Testing, gesprochen:* „Eine Frage hat diesen Flow besonders geprägt: Wird der Plan verstanden oder nur angezeigt?“

*Lesefassung:* „Maßgeblich geprägt hat diesen Flow ein Usability-Test. Seine Leitfrage: Wird der Plan verstanden oder nur angezeigt?“

## 5. Testing & Iteration (bestätigt)

Der Abschnitt zeigt den zentralen Wendepunkt: Transparenz schafft Vertrauen, kostet aber Übersicht. Gezeigt werden nur veränderte Ausschnitte, nicht der ganze Flow erneut.

### Der Test

Getestet habe ich den Mid-Fidelity-Prototyp mit drei Personen und einem realistischen Szenario: eine Rennradrunde von gut dreieinhalb Stunden, Profil und Vorrat bereits angelegt, das Getränk diesmal selbst gemischt. Die Testpersonen sollten einen Plan erstellen, erklären, was sie einpacken, und herausfinden, wie die App auf ihren Wert kommt.

### Was funktionierte

Der Wizard wurde ohne Hilfe abgeschlossen, und die Packliste wurde sofort als Handlungsanweisung gelesen. Das Grundkonzept trägt also.

### Der Wendepunkt

Beim Vertrauen zeigte sich etwas anderes. Vorbelegte Werte ohne sichtbare Herkunft erzeugten Misstrauen, und geschätzte Werte waren im Wizard nicht als solche erkennbar. Die naheliegende Antwort wäre gewesen, noch mehr zu kennzeichnen. Aber schon im Plan zeigte sich, dass die vielen Labels die Übersicht kosten.

> **Transparenz schafft Vertrauen, aber nur, solange sie die Übersicht nicht frisst.**

### Die Änderung

Statt jeden Wert zu kommentieren, trägt ein geschätzter Wert sein Signal jetzt selbst: ein ≈ und eine graue Pill. Eine Legende steht einmal oben. Wer mehr wissen will, tippt auf den Wert und sieht im Bottom Sheet, woher er kommt, was er am Plan verändert und wie man ihn anpassen kann. Die Gramm-Angaben bleiben immer sichtbar.

*Visualisierung:* Vorher/Nachher an einem einzigen Wert statt an ganzen Screens: links ein Wert aus dem MF2-Stand mit „GESCHÄTZT“-Badge, rechts derselbe Wert als ≈-Pill im Hi-Fi, daneben das aufgeklappte Bottom Sheet. Die Testauswertung aus Miro wird nicht gezeigt.

### Weitere Änderungen (nur Webseite)

Außerdem wurden Ort und Startzeit als änderbar gekennzeichnet, die Wahl zwischen Fertigpulver und Eigenmischung ergänzt und der GPX-Upload als eigene Karte vor die Eingabefelder gezogen.

### Präsentation vs. Webseite

- **Präsentation:** Slide 1 nur die Leitfrage, das Szenario wird kurz erzählt. Slide 2 das Vorher/Nachher, darüber die Kernaussage.
- **Webseite:** alle Teile in dieser Reihenfolge, Kernaussage als großer Typo-Break.

*Übergang zu Learnings & Ausblick, gesprochen:* „Ob Nutzer:innen dem Plan dadurch wirklich mehr vertrauen, muss sich messen lassen.“

*Lesefassung:* „Ob die dosierte Transparenz das Vertrauen tatsächlich stärkt, lässt sich messen. Genau daran setzt der nächste Schritt an.“

## 6. Impact, Next Step & Learnings (bestätigt)

Signal und nächster Schritt folgen direkt aus dem Kernproblem Vertrauen; so wird Product Thinking sichtbar.

### Impact

> **Der Plan funktioniert, wenn Nutzer:innen ihm mehr vertrauen als ihrer eigenen Schätzung.**

Das lässt sich messen. Der Trust Score beobachtet, ob Nutzer:innen die Herleitung öffnen und den Plan danach übernehmen, statt ihn anzupassen oder zu verwerfen. Wer nachschaut und trotzdem übernimmt, hat die Rechnung geprüft und für plausibel befunden. Genau dieses Verhalten soll die App erzeugen.

### Next Step: Aus Schätzungen werden Erfahrungswerte

Viele Werte im Plan sind heute noch Schätzungen, etwa Schweißrate oder Leistung. Der nächste Schritt ist deshalb ein kurzes Feedback nach der Fahrt: Hat die Verpflegung gereicht, gab es Magenprobleme? Mit jeder Fahrt kann die App ihre Schätzungen an die echte Person anpassen. Was heute noch mit ≈ markiert ist, wird mit der Zeit zum Erfahrungswert.

Vor einer echten Umsetzung würde ich die Berechnungslogik außerdem von ernährungswissenschaftlichen Fachleuten prüfen lassen. Für ein hypothetisches Projekt war das nicht nötig, für ein Produkt, dem Menschen vertrauen sollen, schon.

*Visualisierung:* Dieselbe ≈-Pill zweimal nebeneinander, einmal grau mit ≈, einmal als normaler Wert ohne Pill, dazwischen ein Pfeil „nach 5 Fahrten“.

### Offene Produktfrage (nur Webseite)

Offen bleibt, wie sich ein neutrales Tool finanziert. Affiliate-Links oder Partnerschaften mit Herstellern lägen nahe, würden aber genau die Neutralität untergraben, auf der das Vertrauen aufbaut.

### Learnings

**Transparenz braucht Dosierung.** Mehr Information erzeugt nicht automatisch mehr Vertrauen. Entscheidend ist, was sofort sichtbar ist und was erst auf Nachfrage erscheint.

**Fokus auf einen Moment.** Die Beschränkung auf die Planung vor der Fahrt hat das MVP erst möglich gemacht.

### Abschluss (Typo-Break)

> **Das Wissen war immer da. Jetzt kommt es auch unterwegs an.**

### Präsentation vs. Webseite

- **Präsentation:** Slide 1 Impact-Kernaussage mit Trust Score in einem Satz. Slide 2 Next Step als eine Zeile, z. B. „Aus ≈ wird Erfahrung“. Slide 3 der Abschluss-Satz. Gesprochen wird nur ein Learning, je nach Zeit das erste oder das zweite.
- **Webseite:** Impact, Next Step inklusive fachlicher Prüfung, offene Produktfrage, beide Learnings, Abschluss als letzter Typo-Break.

## 7. KI im Designprozess, nur Webseite (bestätigt)

Kommt in der Präsentation nicht vor. Roter Faden: Auch bei der Toolwahl zählte Nachvollziehbarkeit.

| Tool | Einsatz | Ergebnis |
| --- | --- | --- |
| Perplexity | Desk Research | Studien mit prüfbaren Quellen |
| NotebookLM | Interviews & Umfrage auswerten | Jede Erkenntnis bis zur Quelle rückverfolgbar |
| Claude | Sparring im gesamten Projekt | Geschärfte Hypothesen und Entscheidungen |
| Claude, Google Stitch, Figma Make, Figma Agent | Frühe Screen-Ideen | Mehrere Richtungen in kurzer Zeit |

KI hat mich durch das ganze Projekt begleitet, aber mit einer klaren Rolle: Sie hat Arbeit beschleunigt, die Entscheidungen blieben bei mir.

In der Research habe ich Perplexity genutzt, um schnell auf belastbare Studien zur Kohlenhydratzufuhr zu stoßen, jeweils mit Quellenangabe, die ich selbst geprüft habe. Für die Auswertung von Interviews und Umfrage habe ich NotebookLM eingesetzt. Der entscheidende Vorteil: Jede Erkenntnis ließ sich direkt bis zur Originalaussage zurückverfolgen. Die Interpretation und Clusterung habe ich danach selbst vorgenommen.

Claude war durchgehend mein Sparringspartner. Damit habe ich Hypothesen hinterfragt, Argumente geschärft und Entscheidungen auf blinde Flecken abgeklopft.

In der frühen Konzeptphase habe ich mit Claude, Google Stitch, Figma Make und dem Figma Agent erste Screen-Ideen erzeugt, um mehrere Richtungen schnell nebeneinander zu sehen. Das finale Design ist in Figma entstanden.

> **Ich habe KI so eingesetzt, wie die App funktionieren soll: nachvollziehbar.**

*Visualisierung:* Tabelle oben, darunter der Text stark gekürzt auf zwei bis drei Sätze.

*Alternative für die Webseite (Entscheidung beim Umsetzen):* KI-Nutzung nicht gebündelt, sondern an Ort und Stelle erwähnen. Perplexity und NotebookLM beim Problem, Claude als Sparring bei Fokus und Lösung & MVP, die UI-Tools beim Kern-Flow. Die Kernaussage stünde dann einmal am Ende als Zusammenfassung.

## Offene Punkte

- [x] Hero neu formulieren
- [x] Meta-Zeile der Webseite: wird beim Bau der Webseite entschieden
- [x] Präsentationsdauer: 5 Minuten
- [x] Umfragewerte bestätigt: 1 von 11 „sehr sicher“, 6 von 11 bei Stress und Anpassung
- [x] Anzahl der Interviews: 3
- [x] Zielwert: 60–90 g/h für Hobbysportler:innen, bis 120 g/h ist ein Profiwert. App und alte Folien (z. B. ZP4 „60–120 g“) daraufhin prüfen
- [x] Nutzer:innen-Aussage zu Vertrauen und Herstellerbindung: nicht dokumentiert, Block 5 stützt sich auf die Wettbewerbsanalyse
- [ ] Quelle für „70 % liegen außerhalb des Zielbereichs“ nachreichen, nur für die Webseite relevant
- [ ] Nur falls die Probeläufe über 5 Minuten liegen: Impact und Next Step auf eine Slide, Demo-Schritt „Profil und Tour“ ohne Kommentar
- [ ] Prüfen, ob Wizard-Reihenfolge und Plan-Tabs im finalen Hi-Fi noch der Sprechspur entsprechen
- [ ] Webseite: KI-Nutzung gebündelt in Abschnitt 7 oder verteilt über die Abschnitte?