---
layout: default
title: 📝 Regula Falsi
---

De methode **Regula Falsi** is een numerieke methode om een **nulpunt** van een functie te berekenen.

De methode start met een gegeven functie, en twee **startwaarden** *A* en *B* waarvan de ene onder het nulpunt zit en de andere erboven. *We laten hier buiten beschouwing hoe je aan deze startwaarden zou moeten komen.*

**Voorbeeld:** de functie $f(x) =  x^2-2$ met het nulpunt $\sqrt{2}$ en de startwaarden $A=1$ en $B=2$. 

<img src="/assets/images/regulafalsi1.png" style="width: 20%; max-width: 100%; height: auto;">


We starten hier met het punt *A* onder de x-as en het punt *B* boven de x-as. We tekenen dan de rechte die door *A* en *B* loopt.

<img src="/assets/images/regulafalsi2.png" style="width: 20%; max-width: 100%; height: auto;">

We noemen *C* het snijpunt van deze rechte met de x-as.

<img src="/assets/images/regulafalsi3.png" style="width: 20%; max-width: 100%; height: auto;">

We bekijken of *f(C)* positief of negatief is en benoemen zo het nieuwe punt *A* of *B*.


<img src="/assets/images/regulafalsi4.png" style="width: 20%; max-width: 100%; height: auto;">

Dat betekent dat hoe langer we deze stappen blijven **herhalen**, hoe dichter we rond het nulpunt zullen zitten. 

## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Schrijf een programma dat de methode Regula Falsi kan uitvoeren. Je gebruikt de functie en startwaarden uit het voorbeeld hierboven. Laat de methode 100 keer herhalen.
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
">ℹ️Definiëer een functie regulafalsi(a,b) die vanuit een gegeven A en B de nieuwe A en B bepaalt en teruggeeft als tuple (A,B).
</div>

```python
def f(x):
    ...


def regulafalsi(a,b):
    ...
    return(anieuw,bnieuw)
```
*Je functie werkt als de waarden van a en b steeds dichter bij $\sqrt{2}=1.414213562373095...$ naderen*

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Voeg nog een tweede test toe aan je code met de funnctie $f(x)=\frac{x^3}{6}-3x$ en startpunten $A=2$ en $B=-3$. Je zou het nulpunt 0 moeten benaderen.

</div>

