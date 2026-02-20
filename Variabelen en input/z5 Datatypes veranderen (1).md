---
layout: default
title: Datatypes veranderen (1)
---

# Datatypes veranderen (1)

Je kan variabele van datatype veranderen met de volgende functies:

* **int(**x**)**   Maakt een integer van de variabele *x*.
* **float(**x**)** Maakt een float van de variabele *x*.
* **str(**x**)** Maakt een string van de variabele *x*.

## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Voer de volgende code uit. Verander daarna *var4* naar het juiste datatype zodat je geen error meer krijgt.
</div>

```python
var1="vier"
var2=4
var3=4.0
var4="4"


uitkomst = var2 + var4
print(uitkomst)
```

<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️
*var1* veranderen naar een float of integer zal trouwens niet lukken. Python is niet zo slim dat hij het getal 4 kan herkennen in het woord "vier". Toch kan het nuttig zijn om ook bij strings op het datatype te letten (zie verder).
</div>