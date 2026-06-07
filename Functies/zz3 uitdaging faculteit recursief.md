---
layout: default
title:  🧩 Faculteit recursief
---

# 🧩 Faculteit recursief

Recursieve functies zijn functies die zichzelf oproepen.

We nemen als voorbeeld de functie *som(n)* die de som 1+2+3+4+…+n berekent. Wanneer je dan bijvoorbeeld *som(7)* moet uitrekenen, kan je ook verwijzen naar het resultaat van *som(6)* en daar nog 7 bij optellen. Maar om op zijn beurt *som(6)* te berekenen, ga je kijken naar *som(5)* om daar 6 bij op te tellen.

Dit gaat zo door tot je uiteindelijk bij *som(0)* aankomt, wat gewoon 0 is. Dit basisgeval moet je apart onderscheiden bij een recursieve functie.

Hier is de code voor een recursieve functie som(n):
```python
def som(n):
    if n == 0:  #basisgeval (altijd nodig bij recursie)
        return 0
    else:
        return n + som(n - 1) #de eigen functie oproepen
```


## Uitdaging
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Definiëer opnieuw de functie faculteit(n) uit de vorige oefening, maar schrijf deze als een recursieve functie.
</div>


### Voorbeeldtesten

###Voorbeeldtesten

| Oproepen functie  | Uitvoer |
| ------------- | ------------- |
|faculteit(10) | 3628800 |

| Oproepen functie  | Uitvoer |
| ------------- | ------------- |
|faculteit(0) | 1 |
