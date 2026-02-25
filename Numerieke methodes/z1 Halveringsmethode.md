---
layout: default
title: Halveringsmethode
---

# Halveringsmethode

De **halveringsmethode** is een numerieke methode om een **nulpunt** van een functie te berekenen.

De methode start met een gegeven functie, en twee **startwaarden** *A* en *B* waarvan de ene onder het nulpunt zit en de andere erboven. *We laten hier buiten beschouwing hoe je aan deze startwaarden zou moeten komen.*

**Voorbeeld:** de functie $f(x) =  x^2$ met het nulpunt $\sqrt{2}$. 

<img src="/assets/images/halvering1.png" style="width: 30%; max-width: 100%; height: auto;">


We starten hier met het punt *A* onder de x-as en het punt *B* boven de x-as. We berekenen dan het **midden** van de twee x-coördinaten en duiden het punt *M* aan op de grafiek.

<img src="/assets/images/halvering2.png" style="width: 30%; max-width: 100%; height: auto;">

Aangezien *M* boven de x-as ligt, wordt *M* de nieuwe *B*.

<img src="/assets/images/halvering3.png" style="width: 30%; max-width: 100%; height: auto;">

We zien nu dat we opnieuw in dezelfde situatie zitten met twee punten *A* en *B* met het nulpunt ertussen, maar de punten *A* en *B* liggen nu wel **dichter bij elkaar.**

Dat betekent dat hoe langer we deze stappen blijven **herhalen**, hoe dichter we rond het nulpunt zullen zitten. 

<img src="/assets/images/halvering4.png" style="width: 30%; max-width: 100%; height: auto;">

Deze methode zal echter **nooit exact** op $\sqrt{2}$ uitkomen. Maar dat is ook niet de bedoeling van een numerieke methode. We zullen na een tijd het resultaat **afronden** wanneer we een **nauwkeurigheid** bereiken die hoog genoeg ligt.

## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Schrijf een programma dat de halveringsmethode kan uitvoeren. Je gebruikt de functie en startwaarden uit het voorbeeld hierboven. Laat de methode 100 keer herhalen.
</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Definiëer een functie f(x) om de functiewaarden uit te rekenen.
</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Definiëer een functie halvering(a,b) die vanuit een gegeven A en B de nieuwe A en B bepaalt en teruggeeft als tuple (A,B).
</div>

```python
def halvering(a,b):
    ...
    return(anieuw,bnieuw)
```

## Afronden en nauwkeurigheid

... nog aanvullen




