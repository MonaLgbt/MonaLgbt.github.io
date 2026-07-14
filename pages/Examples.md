---
title: Test 3
layout: default
---

[Zurück zu index.md](../index.md)

# Markdown-Funktionen

Das Dingsi unterstützt zum Beispiel nicht:

## Fußnoten

```markdown
Text[^1]

[^1]: Fußnote
```

❌ keine Unterstützung  

---

Aber das Meiste geht dennoch:

## Tabellen mit Ausrichtung

links  | rechts | mittig
-------|-------:|:---:
101    | 2      | 301
1      | 201    | 3

Codeblocks zeigen den Quelltext:

```md
links  | rechts | mittig
-------|-------:|:---:
101    | 2      | 301
1      | 201    | 3
```

---

## Codeblocks im Dingsi

```text
for i in range(10):
    print(i)
```

❌ keine Unterstützung für Highlighting

Codeblocks zeigen den Quelltext:

```md
'''python
for i in range(10):
    print(i)
'''
```

<br>

**Für dieses Beispiel:**  
Damit die Klammer sich nicht schließt  
stehen innen z.B. Hochkommas statt Backticks.

---

## Codeblocks hier im Wiki

```python
for i in range(10):
    print(i)
```
✔️ Unterstützung für Highlighting

---

## Inline Code

Schreibe **im** Text `print("Goodbye, World!")` sowas.

Ein Codeblock zeigt den Quelltext:

```md
Schreibe **im** Text `print("Goodbye, World!")` sowas.
```

---

## Kommentare

> Kommentare sind etwas eingerückt und haben links (meistens) einen senkrechten Strich. In diesem Fall nicht, es hängt ab vom verwendeten CSS-Stil.
>> Für Zitate kann man auch weiter einrücken.

Ein Codeblock zeigt den Quelltext:

```md
> Kommentare sind etwas eingerückt  
und haben links einen senkrechten Strich.  
>> Für Zitate kann man auch weiter einrücken.
```

[weiter](comparison.md)
