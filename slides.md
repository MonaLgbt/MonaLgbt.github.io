# Markdown-Kurzanleitung

**Quelle: Markdown Quick Reference auf der Gihub-Seite von: [markedjs/marked](https://github.com/markedjs/marked?tab=readme-ov-file).  
Übersetzung mit Hilfe von DeepL.**


Ein Markdown-Parser und -Compiler, auf Geschwindigkeit ausgelegt. Auf der [Demoseite](https://marked.js.org/demo/) können Sie Marked in Aktion sehen.


---


Markdown-Kurzanleitung
====================

Dieser Leitfaden bietet einen kurzen Überblick mit Beispielen zur Syntax, die [Markdown] unterstützt. Er ist selbst in Markdown geschrieben, und Sie können die Beispiele zum Ausprobieren in den linken Bereich kopieren. Sie werden als *Text* und nicht als *gerendertes HTML* angezeigt.

Markdown-Quelltext:

```md
Markdown-Kurzanleitung
======================
```

[Markdown]: http://daringfireball.net/projects/markdown/


---


Einfache Textformatierung
======================

Das Wichtigste zuerst: Sie können *Sternchen* oder _Unterstriche_ für Kursivschrift verwenden. **Doppelte Sternchen** und __doppelte Unterstriche__ für Fettschrift. ***Drei zusammen*** für ___beides___.

```md
Einfache Textformatierung
======================

Das Wichtigste zuerst: Sie können *Sternchen* oder _Unterstriche_ für Kursivschrift verwenden. **Doppelte Sternchen** und __doppelte Unterstriche__ für Fettschrift. ***Drei zusammen*** für ___beides___.
```


---


Absätze sind auch ziemlich einfach. Fügen Sie einfach eine Leerzeile zwischen Textblöcken ein.

> Dieser Textblock befindet sich in einem Blockzitat. Seine mehreren Zeilen werden alle
> gegenüber dem Rest des Textes etwas eingerückt.
>
> > Mehrere Ebenen von Blockzitaten funktionieren ebenfalls.

```md
Absätze sind auch ziemlich einfach. Fügen Sie einfach eine Leerzeile zwischen Textblöcken ein.

> Dieser Textblock befindet sich in einem Blockzitat. Seine mehreren Zeilen werden alle
> gegenüber dem Rest des Textes etwas eingerückt.
>
> > Mehrere Ebenen von Blockzitaten funktionieren ebenfalls.
```


---


Manchmal möchten Sie Code einfügen, beispielsweise wenn Sie erklären, wie `<h1>` HTML-Tags funktionieren, oder wenn Sie als Programmierer über `eineMethode()` sprechen. Dann klammern Sie diese Teile mit einem Backtick ( ` ) ein.

```md
Manchmal möchten Sie Code einfügen, beispielsweise wenn Sie erklären, wie `<h1>` HTML-Tags funktionieren, oder wenn Sie als Programmierer über `eineMethode()` sprechen. Dann klammern Sie diese Teile mit einem Backtick ( ` ) ein.
```

---


Wenn Sie Code einfügen und neue
Zeilen beibehalten möchten, rücken Sie die Zeile mit einem Tabulator
oder mindestens **vier** Leerzeichen ein:

    Auch hier funktionieren zusätzliche Leerzeichen.
    Dies wird auch als vorformatierter Text bezeichnet und ist nützlich, um Beispiele anzuzeigen.
    Der Text bleibt als Text erhalten, sodass alle von Ihnen hinzugefügten *Markdown*- oder <u>HTML</u>-Elemente
    nicht formatiert angezeigt werden. Auf diese Weise können Sie Markdown-Beispiele in einem
    Markdown-Dokument anzeigen.

```md
    Auch hier funktionieren zusätzliche Leerzeichen.
    Dies wird auch als vorformatierter Text bezeichnet und ist nützlich, um Beispiele anzuzeigen.
    Der Text bleibt als Text erhalten, sodass alle von Ihnen hinzugefügten *Markdown*- oder <u>HTML</u>-Elemente
    nicht formatiert angezeigt werden. Auf diese Weise können Sie Markdown-Beispiele in einem
    Markdown-Dokument anzeigen.
```

---


>     Sie können auch vorformatierten Text mit Ihren Blockzitaten verwenden,
>     solange Sie mindestens **fünf"" Leerzeichen hinzufügen.

```md
>     Sie können auch vorformatierten Text mit Ihren Blockzitaten verwenden,
>     solange Sie mindestens **fünf** Leerzeichen hinzufügen.
```


---


Überschriften
===========

Es gibt mehrere Möglichkeiten, Überschriften zu erstellen. Durch die Verwendung von drei oder mehr Gleichheitszeichen in einer Zeile unter einer Überschrift wird diese zum Stil „h1”. Drei oder mehr Bindestriche unter einer Zeile machen sie zu „h2” (etwas kleiner).

Sie können auch mehrere Rautezeichen (`#`) vor und nach einer Überschrift verwenden. Rautezeichen nach dem Titel werden ignoriert, aber sie verdeutlichen möglicherweise eine Überschrift im Quelltext, genauso wie es die Unterstreichungen tun.


---


Hier sind einige Beispiele:

Dies ist eine H1 Überschrift
============================

Dies ist eine H2 Überschrift
---

# Dies ist H1

## Dies ist H2

### Dies ist H3 mit einigen zusätzlichen Rautezeichen ###

#### Sie verstehen, worauf ich hinaus will ####

##### Ich brauche am Ende keine zusätzlichen Rautezeichen

###### H6 ist das Maximum


---


```md
Dies ist eine H1 Überschrift
============================

Dies ist eine H2 Überschrift
---

# Dies ist H1

## Dies ist H2

### Dies ist H3 mit einigen zusätzlichen Rautezeichen ###

#### Sie verstehen, worauf ich hinaus will ####

##### Ich brauche am Ende keine zusätzlichen Rautezeichen

###### H6 ist das Maximum
```


---


Links
=====

Verlinken wir ein paar Websites.  
Zunächst verwenden wir die reine URL,  
wie   <https://www.github.com>.  
Das ist gut für Text,  
aber unschön für HTML.

Als Nächstes kommt ein Inline-Link  
zu [Google](https://www.google.com).  
Das sieht schon etwas besser aus.


---


Dies ist ein Link im Referenzstil  
zu [Wikipedia] [1].  
Zuletzt noch ein hübscher Link  
zu [Yahoo].  
Der Link im Referenzstil und der hübsche Link verwenden beide automatisch die unten definierten Links, aber sie könnten *überall* im Markdown definiert werden und werden aus dem HTML entfernt. Bei den Namen wird auch nicht zwischen Groß- und Kleinschreibung unterschieden, sodass Sie [YaHoO] verwenden können und der Link trotzdem richtig funktioniert.


[1]: https://www.wikipedia.org
[Yahoo]: https://www.yahoo.com


---


Titelattribute können zu Links hinzugefügt werden, indem Text nach einem Link eingefügt wird.

Dies ist der [Inline-Link](https://www.bing.com „Bing”) mit dem Titel „Bing”.

Sie können auch zu „W3C” [2] gehen und vielleicht einen [Freund] besuchen.


[2]: https://w3.org (The W3C puts out specs for web-based things)
[Freund]: https://facebook.com "Facebook!"


---


E-Mail-Adressen im Klartext sind nicht verlinkt: test@example.com.  
E-Mail-Adressen in spitzen Klammern sind verlinkt: <test@example.com>.  
Sie sind außerdem verschleiert, damit Spam-Roboter sie hoffentlich nicht finden können.


---


Listen
=====

* Dies ist eine Aufzählungsliste.
* Ideal für Einkaufslisten.
- Sie können auch Bindestriche verwenden.
+ Oder Pluszeichen.
+ Nochmal Pluszeichen. (Interessant: keine eingefügte Leerzeile)

Das oben Genannte ist eine „ungeordnete” Liste. Nun zu etwas Ordnung.

1. Nummerierte Listen sind ebenfalls einfach
2. Beginnen Sie einfach mit einer Zahl
3. Die tatsächliche Zahl spielt jedoch keine Rolle, wenn sie in HTML konvertiert wird.
4. Dies wird weiterhin als 4 angezeigt.


---


Möglicherweise benötigen Sie einige erweiterte Listen:

- Diese Liste der obersten Ebene ist in Absatz-Tags eingeschlossen
- Dadurch wird zwischen jedem Element der obersten Ebene ein zusätzlicher Abstand erzeugt.

- Dies erreichen Sie durch Hinzufügen einer Leerzeile

- Diese verschachtelte Liste enthält ebenfalls Leerzeilen zwischen den Listenelementen.


---


- So erstellen Sie verschachtelte Listen:
  - Beginnen Sie mit Ihrer regulären Liste.
  - Verschachtelte Listen werden um zwei Leerzeichen eingerückt.
  - Bei weiteren Verschachtelungen sollten Sie um zwei weitere Leerzeichen einrücken.
    - Diese Zeile ist um vier Leerzeichen eingerückt.


---


- Listenelemente können recht lang sein. Sie können einfach weiter tippen und sie entweder
ohne Einrückung in der nächsten Zeile fortsetzen.

- Alternativ können Sie, wenn Ihnen das nicht gefällt,
  die nächste Zeile etwas einrücken, um ein schöneres Erscheinungsbild zu erzielen.

- Sie können große Textblöcke in Ihre Liste einfügen, indem Sie sie einfach um zwei Leerzeichen einrücken.

  Dies wird genauso formatiert wie Code, aber wenn Sie den HTML-Code überprüfen,
 werden Sie feststellen, dass er lediglich in einen `<p>`-Tag eingeschlossen ist und *nicht*
  als vorformatierter Text angezeigt wird.

  Sie können einem einzelnen Listenelement immer mehr Absätze hinzufügen, indem Sie die herkömmliche Leerzeile einfügen und dann die Absätze weiterhin um zwei Leerzeichen einrücken.

Sie müssen eigentlich nur die erste Zeile einrücken, aber das sieht unschön aus.


---


- Listen unterstützen Blockzitate

> Genau wie in diesem Beispiel hier. Übrigens können Sie
> Listen innerhalb von Blockzitaten verschachteln!
  > - Fantastisch!

- Listen unterstützen vorformatierten Text

      Sie müssen lediglich **vier** zusätzliche Leerzeichen einrücken.


---


# Noch mehr

Horizontale Linie
- - -

Wenn Sie eine horizontale Linie benötigen, müssen Sie lediglich mindestens drei Bindestriche, Sternchen oder Unterstriche in einer Zeile allein stehen lassen. Sie können sogar Leerzeichen zwischen die Zeichen setzen.

```md
Horizontale Linie
- - -
---
****************************
_ _ _ _ _ _
```
Alle erzeugen horizontale Linien.

Beachten Sie, dass drei Bindestriche unter einem Text diesen Text in eine Überschrift umwandeln.

Fügen Sie daher ein Leerzeichen ein, wenn Sie Bindestriche verwenden ( - - - ) oder nehmen Sie den Unterstrich ( ___ ) oder lassen Sie eine Leerzeile dazwischen.


---


## Bilder

Bilder funktionieren genau wie Links, haben jedoch ein Ausrufezeichen vorangestellt. Sie funktionieren auch mit Referenzen und Titeln.

![Google Logo](https://www.google.com/images/errors/logo_sm.gif) and ![Happy]

[Happy]: https://img.icons8.com/color/48/linux--v1.png ("Linux)

[icons8.de](https://icons8.de/icons/set/tux)

icons8-linux-48.png

:blush: ("Smiley face")


---


## Inline-HTML

Wenn Markdown zu einschränkend ist, können Sie einfach Ihr eigenes <strike>verrücktes</strike> HTML einfügen. 

**3 Varianten für das Durchstreichen:**

```md
~~durchgestrichen~~ (Markdown)

<s> durchgestrichen </s> (Html)

<strike>durchgestrichen</strike> (auch Html)
```

**Für dasselbe Ergebnis:**

~~durchgestrichen~~


---


Span-Level-HTML <u>kann *weiterhin* Markdown verwenden</u>.

```md
Span-Level-HTML <u>kann *weiterhin* Markdown verwenden</u>. 
```


---


Block-Level-Elemente müssen durch eine Leerzeile vom Text getrennt werden und dürfen keine Leerzeichen vor dem öffnenden und schließenden HTML-Tag enthalten.

<div style='font-family: "Comic Sans MS", "Comic Sans", cursive;'>

Es ist schade, aber Markdown funktioniert hier für die meisten Markdown-Parser **nicht**.

**Marked** kommt damit recht gut zurecht.
</div>

```html
<div style='font-family: "Comic Sans MS", "Comic Sans", cursive;'>

Es ist schade, aber Markdown funktioniert hier für die meisten Markdown-Parser **nicht**.

**Marked** kommt damit recht gut zurecht.
</div>
```

**Markor kann es auch!**  
Das ist ein Editor für Android.


---


### Tabellen

**In Markdown werden Tabellen aus Textzeichen quasi "gemalt".**

|  🔆    |    A |   B |   C |
|---------:|------:|------:|-----:|
| **1** |    7  | 31 |  33 |
| **2** |  95  | 17 |    2 |
| **3** |    5  | 10 |  50 |

- Der Spaltentrenner ist ( | )
- Unter der oberen Tabellenbeschriftung ist immer mindestens: ( ---|---|--- )
- Die Ausrichtung der Spalten bestimmt ein Doppelpunkt " : "
- Links: ( :---|:---|:--- ) oder  ( ---|---|--- )
- Rechts: ( ---:|---:|---: )
- Mittig:  ( :---:|:---:|:---: )
- Gemischt:  ( :---|:---:|---: )

---


In reinem Markdown gibt es keinen offiziellen Befehl, um die Spaltenbreite direkt zu setzen. Viele Renderer erlauben aber eingebettetes HTML oder CSS, mit dem sich die Breite steuern lässt.

|  🔆  | <div style="width:60px">A</div> | <div style="width:60px">B</div> | <div style="width:60px">C</div> |
|----:|-----:|-----:|-----:|
| **1** |   7 |  31 |  33 |
| **2** |  95 |  17 |   2 |
| **3** |   5 |  10 |  50 |

```html

| 🔆    | <div style="width:60px">A</div> | <div style="width:60px">B</div> | <div style="width:60px">C</div> |
|------:|----:|----:|----:|
| **1** |   7 |  31 |  33 |
| **2** |  95 |  17 |   2 |
| **3** |   5 |  10 |  50 |
```


