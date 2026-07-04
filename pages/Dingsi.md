---
layout: default
title: Seite 2
---

# Seite 2

[Zurück](../readme.md)

## Microsoft's Markdown-Dingsi

**Microsoft bietet in Ondrive/Sharepoint (fast)  
einen richtigen Markdown-Editor an.**

Fast heißt: Er kann das meiste, was ein solcher können soll.  
Leider ist der theoretsch durch Html, Css und Javascript  
unbegrenzte Funktionsumfang unnötigerweise gedeckelt.  
(Javascript ist in Multiuser-Umgebungen nicht sicher.  
Aber lokal ist es sehr praktisch.)

> **Eingeschränkt heißt nicht:**  
dass man nicht überall, wo Texteingabe möglich ist,  
ein vollständiges Markdown mit allen Möglichkeiten  
schreiben könnte. Man muss es nur abspeichern,  
und sich irgendwo einen Renderer suchen.  
Dann ist wieder alles chic.  
>> **Wenn Markdown Routine ist:**  
dann braucht man diese visuelle Kontrolle auch nicht mehr.  
Nur für den letzten Schritt (Ausgabe als PDF) ist es noch nötig.

Das ist wohl dieselbe Denke wie z.B. in Word,  
wenn selten genutzte Funktionen versteckt werden.  
Unnötig deshalb, weil es nicht verwirren würde,  
da es einfach nicht zu sehen wäre.  
Stattdessen ist es nicht vorhanden.  
Das Dingsi hat noch nichtmal einen richtigen Namen.  
Notepad hat zwar einen Namen und kann auch Markdown,  
aber es ist leider sogar noch mehr kastriert.

Zum Beispiel:

### Fußnoten werden nicht unterstützt

```markdown
Text[^1]

[^1]: Fußnote
```

❌ keine Unterstützung  

---

Aber das Meiste geht dennoch:

### Tabellen mit Ausrichtung

rechts | links | mittig
-------|------:|:---:
101    | 2     | 3
1      | 201   | 3

---

### Codeblocks

```python
print("Goodbye, World!")
```

❌ keine Unterstützung für Highlighting

Codeblocks zeigen den Quelltext:

```md
'''python
print("Goodbye, World!")
'''
```

**Für dieses Beispiel:**  
Damit die Klammer sich nicht schließt  
stehen innen z.B. Hochkommas statt Backticks.

---

### Inline Code

Schreibe **im** Text `print("Goodbye, World!")` sowas.

Ein Codeblock zeigt den Quelltext:

```md
Schreibe **im** Text `print("Goodbye, World!")` sowas.
```

---

### Kommentare

> Kommentare sind etwas eingerückt  
und haben links einen senkrechten Strick.  
>> Für Zitate kann man auch weiter einrücken.

Ein Codeblock zeigt den Quelltext:

```md
> Kommentare sind etwas eingerückt  
und haben links einen senkrechten Strick.  
>> Für Zitate kann man auch weiter einrücken.
```

---






