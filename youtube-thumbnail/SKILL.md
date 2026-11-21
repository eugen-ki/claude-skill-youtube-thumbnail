---
name: youtube-thumbnail
description: Use when the member wants a YouTube thumbnail (Thumbnail, Vorschaubild, "mach mir ein Thumbnail", Thumbnail-Text, Thumbnail-Ideen, A/B-Test für Thumbnails), has a video title and needs the image for it, or says their videos get too few clicks.
---

# YouTube-Thumbnail

Plant und baut Thumbnails für **ein** Video: drei Ideen, fertige Bilder in 1280 × 720, Prüfung auf Handygröße und Fernseher, dazu die Anleitung für den A/B-Test. Kostenlos: Das Bild setzt Claude aus einem Foto und Text selbst zusammen. Eine Bild-KI ist nur für den Hintergrund nötig, und auch der geht ohne.

## Wie ein Klick entsteht

Im Feed passiert in ein bis zwei Sekunden:
1. **Blick:** Das Bild fällt auf (Farbe, Kontrast, ein großes Gesicht, eine große Zahl).
2. **Titel:** Der Zuschauer liest den Titel, um zu verstehen, was er bekommt.
3. **Bestätigung:** Er schaut zurück aufs Bild. Passt es zum Versprechen, klickt er.

Ein Thumbnail muss alle drei Schritte tragen. Bild und Titel sind ein Paket: Das Bild sagt nie dasselbe wie der Titel, es ergänzt ihn.

Neu dazu: Viele schauen YouTube am Fernseher. Dort ist zuerst nur die **obere Hälfte** des Thumbnails zu sehen. Und die Titel werden kleiner, das Bild muss also auch allein neugierig machen.

## Schritt 1: Eingaben (eine Nachricht)

Lies `~/.claude/mein-profil.md` (Zielgruppe, Farben, Stimme). Frag dann nur, was fehlt:
- Titel des Videos (Pflicht) und in einem Satz, was der Zuschauer bekommt.
- Ein Foto von dir als Dateipfad (optional, nötig für Ideen mit Gesicht). Am besten mehrere: freudig, überrascht, nachdenklich, zeigend.
- Ist dein Kanal neu oder kennen dich die Leute schon?
- Markenfarben (optional).

Kommt keine Antwort, arbeite mit dem, was da ist: ohne Foto keine Gesicht-Variante (siehe Schritt 4), ohne Vorbilder weiter mit Hinweis, Farben aus der Vorlage.

## Schritt 2: Frage und Gefühl festlegen

Bevor es um Bilder geht, beantworte für dieses Video:
- **Wunsch:** Geld, Zeit, Ruhe oder Ansehen? Welcher **Schmerz** steht dem Wunsch im Weg, welche **Lösung** bietet das Video?
- **Frage:** Was soll sich der Zuschauer fragen, wenn er nur das Bild sieht?
- **Gefühl:** Was soll er fühlen? Dieses Gefühl zeigt später das Gesicht. Es ist das Gefühl, das er **nach** dem Video haben soll.

Schreib diese drei Zeilen auf. Fragen und Gefühle bringen mehr Klicks als ein Bild, das nur zum Thema passt.

## Schritt 3: Vorbilder sammeln

Bitte das Mitglied um 3 bis 5 Vorbilder (Screenshots oder Links), oder nenne ihm die fünf Quellen:
1. eigene Videos, die besser liefen als der Durchschnitt,
2. Videos aus der Nische, die viel besser liefen als der Rest ihres Kanals,
3. Kanäle mit gleichem Format, aber anderem Thema,
4. Thumbnails, die beim Surfen aufgefallen sind (privat in einer Playlist sammeln),
5. Vorbilder außerhalb von YouTube: Filmplakate, Werbung, Albumcover.

Benenne je Vorbild den **Mechanismus**: Warum entsteht dort eine Frage oder ein Gefühl? (Beispiel: "riesige Geldsumme plus erschrockenes Gesicht = Wie viel steht auf dem Spiel?"). Übernimm den Mechanismus, nie das Motiv. Ohne Vorbilder weitermachen und sagen, dass das Ergebnis schwächer ist.

## Schritt 4: Drei Ideen

Schreib drei Ideen, mindestens eine **ohne Gesicht** (Ergebnis, Bildschirm, Gegenstand) und eine **mit Gesicht**. Ohne eigenes Foto ersetzt eine Variante mit **Frage** oder **großer Zahl** die Gesicht-Variante. Sag dann, dass für die Gesicht-Variante ein Foto nötig ist. Kennt noch niemand den Kanal, wirkt ein klares Ergebnis oft stärker als ein fremdes Gesicht. Deshalb beides testen.

Jede Idee hat genau diese Teile:
- **Die eine Idee:** ein Satz.
- **Elemente (höchstens drei):** aus Gesicht mit Emotion, Gegenstand oder Grafik, großer Text oder große Zahl, Pfeil oder Kreis, ästhetisches Bild, geordnete Sammlung. Farbkontrast kommt immer dazu.
- **Aufbau:** mittig, im Drittel (Person rechts, Text links oder umgekehrt) oder geteilt in Vorher (links) und Nachher (rechts).
- **Text:** 0 bis 4 Wörter in Großbuchstaben, ein Wort davon in Akzentfarbe.
- **Warum es den Titel ergänzt:** ein Satz.

Regeln für jede Idee:
- Der Text wiederholt den Titel nie. Er liefert Gefühl, Ergebnis, Zahl oder Frage. Beispiel: Titel "So schreibst du Skripte, die fesseln", Text "FAST SCHUMMELN".
- Eine Grafik zeigt eins von vier: das Ergebnis, den Weg, Vorher und Nachher oder den Schmerz.
- Ein klarer Blickpunkt. Alles, was nicht hilft, fliegt raus.
- Text und Wichtigstes in die **obere Hälfte**. Die Ecke **unten rechts** bleibt frei (dort liegt die Zeitangabe).
- Grün heißt gut, Rot heißt schlecht.
- Köder ja, Täuschung nein: Das Video muss liefern, was das Bild verspricht.

Empfiehl ein Paar für den A/B-Test (eine Idee mit, eine ohne Gesicht) und frag, welche gebaut werden sollen. Hat das Mitglied schon alles in einer Nachricht gesagt oder antwortet nicht: alle drei bauen.

## Schritt 5: Bilder besorgen

| Quelle | Was zu tun ist |
|---|---|
| **Eigenes Foto** | Pfad nutzen. Für eine Person vor anderem Hintergrund das Foto freistellen: Windows Fotos-App (Hintergrund entfernen), Mac Vorschau (Hintergrund entfernen) oder Canva. Als PNG mit durchsichtigem Hintergrund speichern. |
| **Bildschirm oder Ergebnis** | Screenshot in voller Größe, nie abgeschnitten. |
| **KI-Bild aus dem Abo** | Schreib einen Prompt für ChatGPT oder Gemini (Zusatz unten). Das Mitglied erzeugt das Bild dort und speichert es in `bilder/`. |
| **Gratis-Foto** | Suchbegriffe für Pexels oder Unsplash nennen, nur freie Lizenz. |

Zusatz für jeden KI-Prompt: "YouTube-Thumbnail-Hintergrund im Format 16:9, hell, kräftige Farben, starker Kontrast, ein klares Motiv, obere linke (oder rechte) Hälfte ruhig für Text, keine Schrift, keine Buchstaben, keine Logos, keine echten bekannten Personen." Den Text setzt die Vorlage, KI-Programme schreiben Text oft falsch.

## Schritt 6: Bauen

1. Ordner `thumbnail-<titel-in-kurz>/` in dem Ordner anlegen, in dem Claude Code gestartet wurde, darin `bilder/`.
2. `assets/vorlage.html` aus diesem Skill-Ordner nach `thumbnail-<...>/thumbnail.html` kopieren. Farben in `:root` aus dem Profil, sonst Vorlage lassen.
3. Je Idee eine `section` (`#v1`, `#v2`, `#v3`) füllen: Hintergrund, freigestellte Person (`figur links|rechts`), Text (`text links|rechts|mitte`, Akzentwort in `<em>`), bei Bedarf Pfeil oder Kreis. Sitzt das Motiv falsch, `background-position` anpassen (zum Beispiel `center 70%`). Hat das Bild schon eigenen Text, einen anderen Ausschnitt wählen oder ein anderes Bild nehmen. Geteilte Variante: Text je Hälfte mit `text halb links` und `text halb rechts`.
4. Bilder speichern, im Kopfmodus mit Chrome oder Edge (Pfade mit `/`):

```
"<BROWSER>" --headless=new --disable-gpu --hide-scrollbars --allow-file-access-from-files --force-device-scale-factor=1 --virtual-time-budget=8000 --window-size=1280,720 --screenshot="<PFAD>/thumbnail-v1.png" "file:///<PFAD>/thumbnail.html#v1"
```

`<BROWSER>`: Windows `C:\Program Files\Google\Chrome\Application\chrome.exe` oder `C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe`, Mac `/Applications/Google Chrome.app/Contents/MacOS/Google Chrome`. `<PFAD>` ist der volle Ordnerpfad mit `/`, unter Windows mit Laufwerk (`C:/Users/...`). Die Meldung "bytes written" ist kein Fehler. Die Schriften brauchen Internet.

5. YouTube erlaubt höchstens 2 MB. Ist eine PNG-Datei größer, als JPG speichern (`ffmpeg -i thumbnail-v1.png -q:v 3 thumbnail-v1.jpg`) oder im Bildprogramm verkleinern.

## Schritt 7: Prüfen, bevor es fertig ist

1. **Prüfansicht** speichern: gleiche Adresse mit `thumbnail.html?pruefen#v1` als `pruefen-v1.png`. Sie zeigt die Zeitangabe unten rechts und eine Linie in der Mitte.
2. **Klein ansehen:** Für jede Variante eine Hilfsdatei `klein-v1.html` mit `<body style="margin:0"><img src="thumbnail-v1.png" width="320"></body>` anlegen und mit demselben Befehl wie oben, aber `--window-size=320,180`, als `klein-v1.png` speichern. Dann ansehen.
3. Fragen, ehrlich beantworten:
   - Ist auf 320 Pixel jedes Wort lesbar? Gibt es einen klaren Blickpunkt?
   - Versteht man das Video mit der oberen Hälfte allein (Fernseher)?
   - Verdeckt die Zeitangabe etwas Wichtiges?
   - Macht das Bild ohne Titel neugierig oder löst es ein Gefühl aus?
   - Wiederholt der Text den Titel? Ist ein Wort falsch geschrieben?
   - Passt die Emotion zum Versprechen?
4. Sag dem Mitglied in zwei bis drei Zeilen, was gut ist und was nicht. Biete **eine** Überarbeitung an, dann fertig.

## Schritt 8: A/B-Test und Notizen

Erklär den Test: In YouTube Studio das Video öffnen, auf das Thumbnail klicken, "Testen und vergleichen" wählen, zwei oder drei Varianten hochladen. YouTube zeigt nach einigen Tagen, welche mehr Zuschauzeit bringt. Große Kanäle testen bei jedem Video mehrere Varianten.

Speichere `thumbnail-<...>/notizen.md`: Titel, Wunsch, Frage, Gefühl, Vorbilder mit Mechanismus, die drei Ideen, Dateinamen, Prüfergebnis, Testempfehlung. Lade nichts selbst hoch.

## Was große Kanäle gemeinsam haben

- Ein Gesicht mit klarer Emotion im Drittel, daneben **ein** starker Gegenstand (Wecker, Grabstein, Ball).
- Große Zahlen oder Geldsummen in der oberen Hälfte.
- Gegensätze als geteiltes Bild ("ECHT" gegen "FALSCH").
- Kräftige, gesättigte Farben, Licht von hinten trennt die Person vom Hintergrund.
- Wiederkehrende Etiketten für Serien ("HINTER DEN KULISSEN"), damit man sie sofort erkennt.
- Sehr wenig Text, oft nur eine Zahl oder zwei Wörter.

## Häufige Fehler

| Fehler | Besser |
|---|---|
| Text wiederholt den Titel | Gefühl, Ergebnis, Zahl oder Frage |
| Fünf Elemente, alles klein | Höchstens drei, groß |
| Text unten | Obere Hälfte, unten rechts frei |
| Unbekanntes Gesicht ohne Emotion | Ergebnis zeigen oder starke Emotion |
| Ein Thumbnail, kein Test | Zwei bis drei Varianten testen |
| Thumbnail kurz vor dem Hochladen | Idee vor dem Dreh festlegen |
