### Von Blockly nach Python

#### Bedingte Anweisungen (falls)
---

<img src='./bild2.png' width='200'>

```
if hindernisRechts():
    oben()
```

---
<img src='./bild1.png' width='200'>

```
if hindernisOben():
    unten()
else:
    oben()
```

---
<img src='./bild7.png' width='250'>

```
if hindernisRechts():
    if hindernisOben():
        unten()
    else:
        oben()
else:
    rechts()
```

---
<img src='./bild6.png' width='300'>

```
if not plattformOben():
    bauePlattformOben()
```

#### Schleifen (wiederhole, zähle)
---

<img src='./bild0.png' width='200'>

```
for i in range(6):
    oben()
```

---
<img src='./bild3.png' width='300'>

```
while aufPfeilNachRechts():
    rechts()
```

---
<img src='./bild4.png' width='300'>

```
for i in range(1,18):
    geheSchritte(i)
    links()
```

---
<img src='./bild5.png' width='300'>

```
for i in range(17,0,-1):
    geheSchritte(i)
    rechts()
```
---
