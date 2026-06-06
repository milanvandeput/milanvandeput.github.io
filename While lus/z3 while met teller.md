---
layout: default
title: while met teller
---

# while met teller

Een andere methode om while loops op tijd te doen stoppen is door een variabele te gebruiken die iets telt. Vanaf dat deze variabele een bepaalde waarde overschrijdt, stopt het programma met de lus te doorlopen.

```python
t = 0   #dit is de teller variabele, voer deze in voor de loop!

while t<10:
  print(t)
  t=t+1
```
  
Opgelet: de plaats in de code waar je de teller verhoogt, kan een andere uitvoer geven.

```python
t = 0   #dit is de teller variabele, voer deze in voor de loop!

while t<10:
  t=t+1
  print(t)
```

## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Test de bovenstaande codes uit zodat je de werking ervan begrijpt. Verklaar het verschil in uitvoer tussen de twee programma's.
</div>