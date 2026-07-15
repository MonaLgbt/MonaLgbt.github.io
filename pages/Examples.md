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

````text
```python
for i in range(10):
    print(i)
```
````

---

## Codeblocks hier im Wiki

```python
for i in range(10):
    print(i)
```
✔️ Unterstützung für Highlighting

---

## Inline Code

Schreibe `print("Hallo")` **im** Text.

Ein Codeblock zeigt den Quelltext:

```text
Schreibe `print("Hallo")` **im** Text.
```

---

## Kommentare

> Kommentare sind etwas eingerückt  
und haben meistens links einen  
senkrechten Strich. Es hängt aber  
vom verwendeten CSS-Stil ab.  
>> Für Zitate kann man auch weiter  
einrücken.

Ein Codeblock zeigt den Quelltext:

```md
> Kommentare sind etwas eingerückt  
> und haben meistens links einen  
> senkrechten Strich. Es hängt aber  
> vom verwendeten CSS-Stil ab.  
>> Für Zitate kann man auch weiter  
>> einrücken.
```

[weiter](comparison.md)

<!-- Dies ist ein mehrzeiliger Kommentar.
<script>
document.body.insertAdjacentHTML(
  'beforeend',
  '<p>innerWidth=' + window.innerWidth +
  ' scrollWidth=' + document.body.scrollWidth + '</p>'
);
</script>
-->
