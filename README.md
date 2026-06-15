\# Reveal.js Vorlage: \*Markdown – Einführung\*



Diese minimalistische Vorlage liefert eine sofort lauffähige Reveal‑Präsentation, deren Inhalte vollständig in \*\*Markdown\*\* (`slides.md`) gepflegt werden.



\## Schnellstart



1\. \*\*Download entpacken\*\* und Ordner öffnen.

2\. `index.html` im Browser öffnen – fertig.



> 💡 Die Vorlage lädt reveal.js \\\& Plugins bequem über \\\*\\\*CDN\\\*\\\*. Für Offline‑Nutzung siehe Abschnitt \\\*Offline verwenden\\\*.



\## Struktur



```

reveal\\\_markdown\\\_intro\\\_template/

├─ index.html      # Präsentations-Host (lädt slides.md)

├─ slides.md       # Deine Folien in Markdown

└─ assets/         # Bilder \\\& weitere Dateien

```



\## Nützliche Einstellungen



\* \*\*Theme wechseln:\*\* In `index.html` den Theme‑Pfad anpassen, z. B. `dist/theme/moon.css`.

\* \*\*Übergänge:\*\* In `index.html` bei `transition` (`fade`, `slide`, `convex`, `concave`, `zoom`).

\* \*\*Fragmente:\*\* HTML‑Klasse `fragment` nutzen, um Inhalte schrittweise einzublenden.



\## Offline verwenden



1\. Repository `reveal.js` klonen: `git clone https://github.com/hakimel/reveal.js.git`

2\. In `index.html` die CDN‑Links durch lokale Pfade ersetzen (z. B. `./reveal.js/dist/reveal.css`).



\## Hinweise



\* PDF‑Export über den Browser‑Druckdialog. Für fortgeschrittene Optionen siehe die offizielle Doku.



Viel Spaß beim Präsentieren!



\---



\## Lizenz \& Namensnennung



Diese Präsentation ist ausschließlich für private und pädagogische Zwecke bestimmt.

Sie stellt kein kommerzielles Angebot dar und wird nicht gewerblich betrieben.



Dieses Repository basiert auf einem Fork von reveal.js von Hakim El Hattab.

Das ursprüngliche Framework steht unter der \*\*MIT-Lizenz\*\*.



Die Präsentationsinhalte (Texte, Slides) werden unter der \*\*CC0‑Lizenz\*\* veröffentlicht.

Sie sind so weit wie rechtlich möglich gemeinfrei gestellt und dürfen frei verwendet, verändert und weitergegeben werden, ohne dass eine Namensnennung erforderlich ist.



Einige Präsentationsbilder stammen von Unsplash (https://unsplash.com)

und dürfen frei verwendet werden.



Teile dieser Präsentation wurden mit Hilfe von Modellen erstellt,

die Intelligenz nachahmen. Sie dienen ausschließlich Bildungszwecken.

