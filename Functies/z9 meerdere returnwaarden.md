---
layout: default
title: Meerdere returnwaarden
---

# Meerdere returnwaarden

We hebben al functies gezien met één of meerdere argumenten. Maar het is ook mogelijk om een functie meerdere variabelen te laten uitvoeren.

Voorbeeld: een functie die zowel de som en het product van drie getallen a, b en c berekent:

```python
def functie(a,b,c):
  som=a+b+c
  product=a*b*c
  return(som,product)
```
Hoe moet je deze functie dan **oproepen**?

De functie returnet beide waarden terug in een **tuple**. Op deze datastructuur gaan we niet verder in.

Maar hoe kan je dan een specifieke waarde raadplegen? We maken gebruik van **indexen** zoals we dat ook bij lijsten doen.

```python 
print(functie(1,3,3))

print(functie(1,3,3)[0])

print(functie(1,3,3)[1])


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