# YouTube-Thumbnail: Ideen und fertige Bilder mit Claude Code

Ein Claude-Code-Skill, der für dein Video drei Thumbnail-Ideen entwickelt, daraus fertige Bilder in 1280 × 720 baut und sie auf Handygröße und Fernseher prüft. Kostenlos: Claude setzt das Bild aus deinem Foto oder einem Hintergrund und Text selbst zusammen. Dazu bekommst du die Anleitung für den A/B-Test in YouTube Studio.

## Was du bekommst

- Drei Ideen, mit und ohne Gesicht, jede mit höchstens drei Elementen und einem Text, der deinen Titel ergänzt statt ihn zu wiederholen.
- Fertige Thumbnails als Bild, Text immer in der oberen Hälfte (am Fernseher sieht man zuerst nur die), die Ecke mit der Zeitangabe bleibt frei.
- Eine Prüfansicht und eine Mini-Vorschau in 320 Pixel Breite, damit du siehst, ob alles lesbar ist.
- Notizen mit Frage, Gefühl, Vorbildern und Testempfehlung.

## Installieren

1. Oben rechts auf **Code** und dann **Download ZIP** klicken. ZIP entpacken.
2. Im entpackten Ordner liegt der Ordner `youtube-thumbnail`. Kopiere genau diesen Ordner in deinen Skills-Ordner:
   - Windows: `C:\Users\<dein-name>\.claude\skills\`
   - Mac: `~/.claude/skills/`

   Gibt es den Ordner `skills` noch nicht, leg ihn an. Danach liegt die Datei unter `.claude/skills/youtube-thumbnail/SKILL.md`.
3. Claude Code neu starten.

## So benutzt du ihn

Tippe `/youtube-thumbnail` oder sag es in deinen Worten, zum Beispiel:

> Mach mir ein Thumbnail. Titel: "Ich habe meine Buchhaltung mit KI automatisiert". Mein Foto liegt unter C:\Users\ich\Bilder\ich.png

## Tipp: zuerst dein Profil

Mit [mein-profil](https://github.com/eugen-ki/claude-skill-mein-profil) kennt der Skill deine Zielgruppe und Farben. Ohne Profil funktioniert er auch. Titel und Intro für dasselbe Video schreibt [youtube-skript](https://github.com/eugen-ki/claude-skill-youtube-skript).

## Was du brauchst

- [Claude Code](https://claude.com/claude-code).
- Google Chrome oder Microsoft Edge (unter Windows ist Edge immer da).
- Internet beim Bauen (für die Schriften).
- Optional: ein Foto von dir (freigestellt geht in der Windows Fotos-App, in der Mac Vorschau oder in Canva) und ein Bild-Programm aus deinem Abo (ChatGPT oder Gemini) für Hintergründe. Der Skill schreibt dir die Prompts.

## Gut zu wissen

- Die Skills erfinden nichts: Das Video muss liefern, was Bild und Titel versprechen.
- Der Skill lädt nichts hoch. Den A/B-Test startest du selbst in YouTube Studio mit "Testen und vergleichen".

## Lizenz

MIT, frei nutzbar und veränderbar. Siehe [LICENSE](LICENSE).
