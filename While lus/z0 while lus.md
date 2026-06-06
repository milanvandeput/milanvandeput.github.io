---
layout: default
title: While lus
---

# While lussen
Lussen (*loops*) worden gebruikt om code te schrijven die zichzelf een aantal keer herhaalt. Een **while lus** bestaat uit een **voorwaarde** (Boolean) en zolang deze voorwaarde voldaan (True) is, blijft de code in de loop zichzelf herhalen.

**Voorbeeld 1:**

```python
doorgaan = True   #Dit is een Booleaanse variabele

while doorgaan:
  print("hallo")
```

Deze lus blijft eindeloos herhalen omdat de waarde van de variabele *doorgaan* op True blijft staan. Dit willen we natuurlijk niet. We moeten er daarom voor zorgen dat de variabele *doorgaan* ergens de kans krijgt om te veranderen naar False, bijvoorbeeld door een nieuwe input.

**Voorbeeld 2:**

```python
doorgaan = True   #Dit is een Booleaanse variabele

while doorgaan:
  print("hallo")
  vraag=input("Moet ik doorgaan? Ja/Nee")
  if vraag=="Ja":
    doorgaan=True
  else:
    doorgaan=False
```
## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Test de bovenstaande codes uit zodat je de werking ervan begrijpt. Experimenteer gerust door dingen aan te passen.
</div>