
# Markdown – eine kurze Einführung

**Ziel:** Nach dieser Session kennst du die Grundsyntax von Markdown und kannst einfache Dokumente strukturieren.  
<small class="badge">Thema</small> Markdown · <small class="badge">Dauer</small> ~20 min

Note: Willkommen! Diese Vorlage nutzt reveal.js mit dem Markdown-Plugin. Drücke **S**, um die Referenten-Notizen zu sehen.

---

## Was ist Markdown?

- Eine **leichtgewichtige Auszeichnungssprache** zur Formatierung von Text
- Lesbar als Klartext, wandelbar in HTML/PDF/Slides
- Perfekt für **Readme-Dateien**, **Notizen**, **Blogs** und **Präsentationen**

Note: Hauptidee: Schreib fokussiert, formatiere minimal. Konvertierung mit z. B. Pandoc oder Static Site Generatoren.

--

### Beispiel: Markdown → HTML

```markdown
# Überschrift 1

**fett** und *kursiv*

- Liste A
- Liste B
```

➡ wird zu strukturiertem HTML.

---

## Überschriften

Verwende `#` bis `######` am Zeilenanfang:

```markdown
# H1
## H2
### H3
```

**Tipp:** Eine Folie ≈ ein Gedanke. Nutze H2/H3 sparsam.

---

## Zwischenstand

---

### Unterstand

---

## Textformatierung

- **Fett**: `**fett**`
- *Kursiv*: `*kursiv*`
- Durchgestrichen: `~~so~~`
- Code im Text: `` `inline code` ``

--

## Listen & Checklisten

**Unsorte Liste**
```markdown
- Punkt 1
- Punkt 2
```
**Nummeriert**
```markdown
1. Erster
2. Zweiter
```
**To‑Dos** (GitHub‑Flavour)
```markdown
- [x] erledigt
- [ ] offen
```

---

## Links & Bilder

Links: `[Titel](https://example.com)`  
Bilder: `![Alt-Text](assets/markdown.png)`

Note: Lege Dateien ins `assets/`‑Verzeichnis und verlinke relativ.

---

## Zitate & Codeblöcke

> Ein Zitat beginnt mit `>`.

Dreifache Backticks für Blöcke + Sprache:
```js
function hello(name){
  return `Hallo ${name}!`;
}
```

---

## Tabellen (erweiterte Syntax)

```markdown
| Spalte A | Spalte B |
|---------:|:---------|
| rechts   | links    |
```

Note: Tabellen sind Markdown‑Erweiterungen (CommonMark‑kompatible Dialekte wie GFM).

---

## Reveal.js‑Spezial: Fragments

Blende Inhalte Schritt für Schritt ein:

```html
<ul>
  <li class="fragment">Erster Punkt</li>
  <li class="fragment">Zweiter Punkt</li>
</ul>
```

Note: `fragment` ist eine CSS‑Klasse von reveal.js, funktioniert auch in Markdown via HTML‑Einbettung.

---

## Vertikale Slides

Trenne **vertikale** Unterfolien mit `--` (in dieser Vorlage bereits konfiguriert):

```markdown
## Oberthema
--
### Unterfolie 1
--
### Unterfolie 2
```

---

## Export & Teilen

- **PDF‑Export:** Druckdialog im Browser (oder `?print-pdf` bei älteren Versionen)
- **Teilen:** Auf einem Webserver hosten (z. B. GitHub Pages)

Note: Prüfe Schriftgrößen & Kontraste für Barrierefreiheit.

---

## Nächste Schritte

- Diese Vorlage klonen und eigene Inhalte in `slides.md` schreiben
- Themes wechseln (z. B. `moon.css`, `black.css`)
- Plugins: Notizen, Code‑Highlighting, ggf. MathJax

**Viel Erfolg!**
