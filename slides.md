# Eine kurze Einführung in **Markdown**

Markdown ist eine leichtgewichtige Markupsprache, mit der du schnell **formatierte** Texte schreiben kannst – lesbar als Klartext, renderbar als HTML.

**Ziel heute:** Grundlagen verstehen & sofort anwenden.

*2009* beschloss der Senat von Illinois, dem Heimatbundesstaat des Pluto-Entdeckers **Clyde Tombaugh**, Pluto weiterhin **als Planeten** zu betrachten.

*2009* beschloss der Senat von Illinois, dem Heimatbundesstaat des Pluto-Entdeckers **Clyde Tombaugh**, Pluto weiterhin **als Planeten** zu betrachten.

*2009* beschloss der Senat von Illinois, dem Heimatbundesstaat des Pluto-Entdeckers **Clyde Tombaugh**, Pluto weiterhin **als Planeten** zu betrachten.

> Tipp: Diese Präsentation ist selbst in Markdown geschrieben.

Note: Begrüßung, Zielsetzung, kurzer Überblick.


---

<!-- .slide: class="two-col left" -->
## Grundsyntax – Überschriften & Text

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

### Absätze & Zeilenumbrüche

Leere Zeile = neuer Absatz.  \
Zwei Leerstellen am Zeilenende = manueller Zeilenumbruch.

### Listen
```
- Punkt 1
- Punkt 2
  - Unterpunkt
1. Erster
2. Zweiter
```

---

<!-- .slide: class="two-col left" -->
## Links, Bilder & Zitate

### Links
```
[Link-Text](https://beispiel.de)
```

### Bilder
```
![Alt-Text](pfad/zum/bild.png)
```

### Zitate
```
> Ein eingerücktes Zitat
```

### Trennlinien
```
---
```

### Inline-Code & Blöcke

```
`inline`

```js
console.log('Codeblock mit Sprache');
```
```

---

<!-- .slide: class="two-col left" -->
## Tabellen & Aufgabenlisten

### Tabellen
```
| Spalte A | Spalte B |
|---------:|:---------|
| rechts   | links    |
```

### Aufgabenlisten (GFM)
```
- [x] erledigt
- [ ] offen
```

### Escaping & Sonderzeichen
Backslash `\` vor Sonderzeichen nutzen, z. B. `\*` für Stern.

### Emojis (optional)
Einige Renderer unterstützen :tada: :rocket:

---

## Best Practices

- **Lesbarkeit vor Perfektion**: Klarer, einfacher Markdown schlägt komplexes HTML.
- **Konsistente Überschriften-Hierarchie** nutzen.
- **Kurze Zeilen** (z. B. 80–100 Zeichen) erleichtern Diffs.
- **Alt‑Texte** für Bilder – Barrierefreiheit und SEO.
- **Sprache im Codeblock** für Syntax‑Highlighting angeben (z. B. ` ```js `).

Note: Hinweise zur Teamkonvention, Code Reviews, Dokumentation.

---

## Nützliche Ressourcen

- Daring Fireball – Original Markdown-Spezifikation: <https://daringfireball.net/projects/markdown/>
- CommonMark – eine standardisierte Spezifikation: <https://commonmark.org/>
- GitHub-Flavored Markdown (GFM) Guide: <https://github.github.com/gfm/>
- Reveal.js Doku (Markdown-Plugin & Folien-Attribute): <https://revealjs.com/markdown/>

--

## Danke!

Fragen?

*(Drücke **S** für Referentennotizen, **Esc** für Überblick)*
