# Markdown Template & Referenz Guide

Eine komplette Übersicht aller Markdown-Formatierungsmöglichkeiten zum Nachschlagen.

---

## 📋 Inhaltsverzeichnis

1. [Überschriften](#überschriften)
2. [Text-Formatierung](#text-formatierung)
3. [Listen](#listen)
4. [Links & Bilder](#links--bilder)
5. [Code & Syntax-Highlighting](#code--syntax-highlighting)
6. [Tabellen](#tabellen)
7. [Zitate](#zitate)
8. [Horizontale Linien](#horizontale-linien)
9. [Abgesetzte Elemente](#abgesetzte-elemente)
10. [Sonderzeichen & Escaping](#sonderzeichen--escaping)

---

## Überschriften

```markdown
# Überschrift 1 (H1)
## Überschrift 2 (H2)
### Überschrift 3 (H3)
#### Überschrift 4 (H4)
##### Überschrift 5 (H5)
###### Überschrift 6 (H6)
```

### Anzeige:

# Überschrift 1 (H1)

## Überschrift 2 (H2)

### Überschrift 3 (H3)

#### Überschrift 4 (H4)

##### Überschrift 5 (H5)

###### Überschrift 6 (H6)

---

## Text-Formatierung

### Normale Formatierung

```markdown
**Fetter Text** oder __Fetter Text__
*Kursiver Text* oder _Kursiver Text_
***Fett und kursiv*** oder ___Fett und kursiv___
~~Durchgestrichener Text~~
`Inline Code`
```

### Anzeige:

**Fetter Text** oder __Fetter Text__

*Kursiver Text* oder _Kursiver Text_

***Fett und kursiv*** oder ___Fett und kursiv___

~~Durchgestrichener Text~~

`Inline Code`

### Erweiterte Textformatierung

```markdown
<u>Unterstrichener Text</u> (HTML)
<mark>Hervorgehobener Text</mark> (Gelb)
H<sub>2</sub>O (Subscript)
E=mc<sup>2</sup> (Superscript)
```

### Anzeige:

<u>Unterstrichener Text</u>

<mark>Hervorgehobener Text</mark>

H<sub>2</sub>O

E=mc<sup>2</sup>

---

## Listen

### Ungeordnete Listen

```markdown
- Punkt 1
- Punkt 2
  - Unterpoint 2.1
  - Unterpoint 2.2
- Punkt 3

* Alternative mit Asterisk
+ Alternative mit Plus
```

### Anzeige:

- Punkt 1
- Punkt 2
  - Unterpoint 2.1
  - Unterpoint 2.2
- Punkt 3

### Geordnete Listen

```markdown
1. Erster Punkt
2. Zweiter Punkt
   1. Unterpoint 2.1
   2. Unterpoint 2.2
3. Dritter Punkt
```

### Anzeige:

1. Erster Punkt
2. Zweiter Punkt
   1. Unterpoint 2.1
   2. Unterpoint 2.2
3. Dritter Punkt

### Checklisten

```markdown
- [x] Abgeschlossene Aufgabe
- [ ] Offene Aufgabe
- [x] Weitere abgeschlossene Aufgabe
```

### Anzeige:

- [x] Abgeschlossene Aufgabe
- [ ] Offene Aufgabe
- [x] Weitere abgeschlossene Aufgabe

---

## Links & Bilder

### Links

```markdown
[Linktext](https://www.example.com)
[Linktext mit Titel](https://www.example.com "Hover-Text")
<https://www.example.com>
[Referenzlink][1]

[1]: https://www.example.com
```

### Bilder

```markdown
![Alternativer Text](https://via.placeholder.com/200)
![Alternativer Text mit Titel](https://via.placeholder.com/200 "Bild Titel")
[![Klickbares Bild](https://via.placeholder.com/200)](https://www.example.com)
```

### Anzeige:

[Linktext](https://www.example.com)

[Linktext mit Titel](https://www.example.com "Hover-Text")

---

## Code & Syntax-Highlighting

### Inline Code

```markdown
Dies ist `inline code`.
```

### Code-Blöcke

```markdown
```javascript
function helloWorld() {
  console.log("Hallo Welt!");
}
```

```python
def hello_world():
    print("Hallo Welt!")
```

```bash
echo "Hallo Welt!"
```

```
### Anzeige:

```javascript
function helloWorld() {
  console.log("Hallo Welt!");
}
```

```python
def hello_world():
    print("Hallo Welt!")
```

```bash
echo "Hallo Welt!"
```

### Eingerückte Code-Blöcke

```markdown
    Das ist ein Code-Block
    mit Einrückung (4 Leerzeichen)
    oder 1 Tab
```

---

## Tabellen

### Einfache Tabelle

```markdown
| Spalte 1 | Spalte 2 | Spalte 3 |
|----------|----------|----------|
| Wert 1   | Wert 2   | Wert 3   |
| Wert 4   | Wert 5   | Wert 6   |
```

### Anzeige:

| Spalte 1 | Spalte 2 | Spalte 3 |
| -------- | -------- | -------- |
| Wert 1   | Wert 2   | Wert 3   |
| Wert 4   | Wert 5   | Wert 6   |

### Tabelle mit Ausrichtung

```markdown
| Links | Mitte | Rechts |
|:------|:-----:|-------:|
| L1    |  M1   |     R1 |
| L2    |  M2   |     R2 |
```

### Anzeige:

| Links | Mitte | Rechts |
| :---- | :---: | -----: |
| L1    |  M1   |     R1 |
| L2    |  M2   |     R2 |

---

## Zitate

### Einfache Zitate

```markdown
> Dies ist ein Zitat.
> Es kann mehrere Zeilen lang sein.
```

### Anzeige:

> Dies ist ein Zitat.
> Es kann mehrere Zeilen lang sein.

### Verschachtelte Zitate

```markdown
> Äußeres Zitat
> > Inneres Zitat
> > > Noch tieferes Zitat
```

### Anzeige:

> Äußeres Zitat
>
> > Inneres Zitat
> >
> > > Noch tieferes Zitat

### Zitate mit Formatierung

```markdown
> **Wichtig:** Dies ist ein Zitat mit **Fettdruck** und *Kursiv*.
> - Liste im Zitat
> - Zweiter Punkt
```

### Anzeige:

> **Wichtig:** Dies ist ein Zitat mit **Fettdruck** und *Kursiv*.
>
> - Liste im Zitat
> - Zweiter Punkt

---

## Horizontale Linien

```markdown
---
***
___
```

### Anzeige:

---

---

## Abgesetzte Elemente

### Absätze

```markdown
Dies ist ein Absatz.

Dies ist ein neuer Absatz nach einer Leerzeile.

Zeilenumbruch mit zwei Leerzeichen am Ende    
führt zu einem Zeilenumbruch.
```

### Blockquotes mit Code

```markdown
> ```javascript
> function example() {
>   return "Code im Zitat";
> }
> ```
```

### Listen mit mehreren Absätzen

```markdown
- Punkt mit mehreren Absätzen

  Dies ist der zweite Absatz im gleichen Punkt.

- Zweiter Hauptpunkt
```

---

## Sonderzeichen & Escaping

### Escaping

```markdown
\*Dieser Text wird nicht zu Kursiv*\
\[Kein Link\]
\# Keine Überschrift
```

### Spezielle Symbole

```markdown
© ® ™ € £ ¥ § ¶ † ‡
← ↑ → ↓ ↔ ↕
∑ ∏ √ ∞ ≈ ≠ ≤ ≥
```

### Anzeige:

© ® ™ € £ ¥ § ¶ † ‡

← ↑ → ↓ ↔ ↕

∑ ∏ √ ∞ ≈ ≠ ≤ ≥

---

## 🎨 Zusätzliche Tipps & Tricks

### Emoji verwenden

```markdown
😀 😃 😄 😁 😆 😅 🤣 😂
🎉 🎊 🎈 🎁 🎀
✅ ❌ ⚠️ ℹ️
👍 👎 👏 🙌
```

### Kommentare (werden nicht angezeigt)

```markdown
<!-- Dies ist ein Kommentar und wird nicht angezeigt -->
```

### Fußnoten

```markdown
Dies ist Text mit einer Fußnote[^1].

[^1]: Dies ist der Inhalt der Fußnote.
```

### Definitionslisten

```markdown
Begriffserklärung
:   Dies ist die Definition des Begriffs.

Anderer Begriff
:   Und hier die Erklärung dafür.
```

### Inhaltsverzeichnis Anker

```markdown
# [Überschrift](#anchor)

...später im Dokument...

<a id="anchor"></a>
## Zielüberschrift
```

---

## 📝 Template für neue Dateien

```markdown
# Titel des Dokuments

**Autor:** Dein Name  
**Datum:** DD.MM.YYYY  
**Version:** 1.0

---

## Zusammenfassung

Kurze Zusammenfassung des Inhalts.

---

## Inhalt

### Abschnitt 1

Dein Inhalt hier...

### Abschnitt 2

Mehr Inhalt...

---

## Zusammenfassung

Abschließende Bemerkungen.

---

*Zuletzt aktualisiert: DD.MM.YYYY*
```

---

## 🔗 Weitere Ressourcen

- [CommonMark Spezifikation](https://spec.commonmark.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

---

**Viel Erfolg beim Erstellen von Markdown-Dokumenten!** 🚀
