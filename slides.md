# Eine kurze Einführung in **Markdown**

Ziel: Die wichtigsten Markdown-Bausteine kurz & praxisnah.

> Hinweis: Diese Slides werden aus `slides.md` geladen und mit CSS zweispaltig per **getrennten Blöcken** gelayoutet.

Note: Vorstellung, Zielsetzung, Ablauf.

---

<!-- .slide: class="left grid-2" -->
## Grundsyntax – Überschriften & Text

<div class="col">

### Überschriften
```
# H1
## H2
### H3
```

### Textformatierung
```
**fett**  *kursiv*  ~~durchgestrichen~~  `Code`
```

### Absätze & Zeilenumbruch
Leere Zeile = neuer Absatz.  \\
Zwei Leerstellen am Zeilenende = manueller Zeilenumbruch.

</div>
<div class="col">

### Listen
```
- Punkt 1
- Punkt 2
  - Unterpunkt
1. Erster
2. Zweiter
```

### Zitate
```
> Ein eingerücktes Zitat
```

### Trennlinien
```
---
```

</div>

---

<!-- .slide: class="left grid-2" -->
## Links, Bilder & Code

<div class="col">

### Links
```
[Link-Text](https://beispiel.de)
```

### Bilder
```
![Alt-Text](pfad/zum/bild.png)
```

### Inline-Code
```
`inline`
```

</div>
<div class="col">

### Codeblöcke (mit Sprache)
```js
console.log('Hallo Markdown');
```

### Tabellen
```
| A | B |
|--:|:--|
| 1 | x |
```

### Aufgabenlisten (GFM)
```
- [x] erledigt
- [ ] offen
```

</div>

---

<!-- .slide: class="left grid-2" -->
## Praxis-Tipps & Ressourcen

<div class="col">

### Best Practices
- Lesbarkeit > Komplexität
- Konsistente Überschriften-Hierarchie
- Kurze Zeilen (80–100 Zeichen) für bessere Diffs
- Alt-Texte bei Bildern
- Sprache im Codeblock angeben (z. B. ```js)

</div>
<div class="col">

### Ressourcen
- Daring Fireball: <https://daringfireball.net/projects/markdown/>
- CommonMark: <https://commonmark.org/>
- GitHub-Flavored Markdown: <https://github.github.com/gfm/>
- Reveal.js (Markdown): <https://revealjs.com/markdown/>

</div>

---

## Danke!

Fragen?

*(S = Referentennotizen, Esc = Überblick)*
