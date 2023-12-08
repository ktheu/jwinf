## Muster für Blockly-Programme

Muster für Blockly-Programme und ihre Entsprechung in Python

---

#### Text

Den letzten Buchstaben in eine Variable speichern:

<img src='erster.png' width='500'>

```
letzter = text[-1]
```

----

Den letzten Buchstaben in einem Text entfernen

<img src='ohneLetzten.png' width='600'>

```
text = text[:-1]
```

----

Die letzten k Buchstaben des Texts ```wort``` in eine Variable ```endung``` speichern.

<img src='endung.png' width='650'>

```
endung = wort[-k:]

```

---

Die Variable ```anfang``` auf  ```wort``` ohne die letzten k Zeichen setzen.

<img src='endung1.png' width='750'>

```
anfang = wort[:-k]

```

----

#### Bedingte Anweisungen

Durch Click auf das blaue Bearbeitungsrädchen können wir die bedingte Anweisungen mit mehreren
```sonst falls``` und mit oder ohne ```sonst``` erstellen.


<img src='elif2else.png' width='300'>

```
if ... 
elif ....
elif ...
else 
```
----

<img src='elif3.png' width='300'>

```
if ....
elif ....
elif ...
elif ...
```

-----

#### Listen

Am Ende einer Liste etwas hinzufügen

<img src='append.png' width='400'>

```
endungen.append(zeile)

```

---- 

Eine typische Schleife zum Einlesen von Daten in eine Liste ```zeilen```.

<img src='einlesen1.png' width='500'>

---


Die Liste ```endungen``` durchlaufen und den Inhalt zeilenweise ausgeben

<img src='liste_durchlaufen.png' width='500'>

---


