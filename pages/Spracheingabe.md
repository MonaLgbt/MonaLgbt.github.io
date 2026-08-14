---
title: Test 3
layout: default
---

[Zurück zu index.md](../index.md)

# Ein "Word" für die Hosentasche

### Alles passend machen

- Unterschiedliche Tastaturen nutzen.  
- Bequeme Eingabe per Speech to Text.  
- Eigene Dokumente auf das gegebene Hochformat anpassen,  
damit PDF besser in das Handyformat passen.  
Zum Beispiel: Chou3 (120 x 235 mm) statt A4.  
- In beliebige Zielformate konvertieren.  
Das heißt:  
Zum Beispiel Markdown in Word umwandeln.  
(Ja, das geht! Mit Pandoc)

> **Wie geht die Eingabe per Speech to Text in Android?**

## So funktioniert es

1. Öffne eine App mit Texteingabe, zum Beispiel **Nachrichten, WhatsApp, Notizen oder Gmail**.
2. Tippe in das Textfeld, damit die Tastatur erscheint.
3. Tippe auf das **Mikrofon-Symbol** auf der Tastatur.
4. Warte auf „Jetzt sprechen“ und diktiere deinen Text.
5. Sage Satzzeichen mit an, zum Beispiel **„Komma“**, **„Punkt“** oder **„Fragezeichen“**. Google beschreibt diesen Ablauf ebenfalls für Gboard. [support.google](https://support.google.com/messages/answer/2781851?hl=de&co=GENIE.Platform=Android)
6. Prüfe den erkannten Text und korrigiere ihn bei Bedarf.

> **Tipp:** Sprich in normalem Tempo und möglichst in ruhiger Umgebung. Für Deutsch sollte in den Tastatur- oder Spracheinstellungen **Deutsch** als Eingabesprache ausgewählt sein.

## Falls das Mikrofon fehlt

Bei **Gboard**:

**Einstellungen → System → Sprachen & Eingabe → Bildschirmtastatur → Gboard → Spracheingabe**

Dort die Spracheingabe einschalten. Auf Samsung-Geräten heißt der Weg häufig **Einstellungen → Allgemeine Verwaltung → Samsung-Tastatur-Einstellungen → Spracheingabe**. Die genaue Bezeichnung kann je nach Hersteller und Android-Version leicht abweichen. [sky-scribe](https://www.sky-scribe.com/de/blog/android-voice-to-text-setup)

Prüfe außerdem unter **Einstellungen → Apps → Gboard beziehungsweise Tastatur → Berechtigungen**, ob der **Mikrofonzugriff** erlaubt ist. [sky-scribe](https://www.sky-scribe.com/de/blog/how-do-i-turn-on-talk-to-text-on-android-guides-step-by-step)


> **Hm, ist die Funktion in die jeweilige Tastatur eingebaut?**

Ja, **meistens steckt Speech-to-Text in der verwendeten Tastatur beziehungsweise ist dort direkt erreichbar**.

- **Gboard:** Das Mikrofon-Symbol befindet sich meist oben rechts in der Tastaturleiste. Die eigentliche Erkennung wird durch Googles Spracheingabe bereitgestellt.
- **Samsung-Tastatur:** Die Spracheingabe ist normalerweise in die Tastatur integriert; das Mikrofon kann neben der Leertaste oder in der Tastatur-Symbolleiste erscheinen.
- **SwiftKey und andere Tastaturen:** Auch dort kann es ein Mikrofon-Symbol geben, je nach App und Einstellungen.

Wichtig ist: Die Tastatur liefert die Schaltfläche und fügt den Text ein; die Spracherkennung kann im Hintergrund von einem separaten Systemdienst wie **Google Spracheingabe** bereitgestellt werden. Deshalb müssen manchmal sowohl die Spracheingabe in den Tastatureinstellungen als auch die **Mikrofonberechtigung der Tastatur** aktiviert sein. [sky-scribe](https://www.sky-scribe.com/de/blog/how-do-i-turn-on-talk-to-text-on-android-guides-step-by-step)

Kurz gesagt: **In der jeweiligen Tastatur nach dem Mikrofon suchen.** Wenn es fehlt, in den Tastatureinstellungen die Spracheingabe oder die Tastatur-Symbolleiste aktivieren.


> **In HeliBoard sehe ich kein Mikro.**

Ja, das ist bei **HeliBoard** normal: Die Spracheingabe ist nicht unbedingt standardmäßig als Mikrofon sichtbar.
## Mikrofon einblenden
1. Öffne **HeliBoard-Einstellungen**.
2. Gehe zu **Symbolleiste** beziehungsweise **Toolbar**.
3. Öffne **Angeheftete Symbolleistenschaltflächen auswählen**.
4. Aktiviere **Spracheingabe** beziehungsweise **Voice input**.
5. Öffne anschließend eine Texteingabe erneut.

Falls das Symbol nicht direkt sichtbar ist, tippe in der HeliBoard-Symbolleiste auf den **Pfeil zum Aufklappen**. Dort sollte sich die Schaltfläche **Spracheingabe** befinden. Du kannst sie meist länger gedrückt halten, um sie dauerhaft oben anzuheften. [github](https://github.com/HeliBorg/HeliBoard/discussions/1044)
## Wenn „Spracheingabe“ fehlt
HeliBoard erkennt nicht selbst automatisch Sprache. Es braucht einen aktivierten Spracheingabedienst, beispielsweise **Google Spracheingabe**, **FUTO Voice Input**, **Sayboard** oder einen anderen kompatiblen Dienst. Unter Android findest du die aktivierten Eingabedienste meist hier:

**Einstellungen → System → Tastatur → Bildschirmtastatur → Eingabemethoden verwalten**

Danach in HeliBoard nochmals **Spracheingabe** in der Symbolleiste aktivieren. [github](https://github.com/GrapheneOS/os-issue-tracker/issues/4976)

Wenn du eine möglichst datenschutzfreundliche Lösung möchtest, ist **FUTO Voice Input** eine mögliche Ergänzung zu HeliBoard; danach lässt sich die Spracheingabe-Schaltfläche in HeliBoard aktivieren. [community.e](https://community.e.foundation/t/speech-2-text-privacy-friendly/58061)

[weiter](Dingsi.md)
