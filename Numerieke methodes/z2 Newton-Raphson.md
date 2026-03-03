---
layout: default
title: 📝 Newton-Raphson
---

# 📝 Newton-Raphson

De **halveringsmethode** is een numerieke methode om een **nulpunt** van een functie te berekenen.

De methode start met een gegeven functie en een startwaarde $X_{0}$ *We laten hier buiten beschouwing hoe je aan deze startwaarde zou moeten komen.*

**Voorbeeld:** de functie $f(x) =  x^2-2$ met het nulpunt $\sqrt{2}$ en de startwaarde $X_{0}=2$. 

<img src="/assets/images/newton1.png" style="width: 20%; max-width: 100%; height: auto;">


We tekenen de raaklijn aan de grafiek in $x=X_{0}$. Het nulpunt van deze raaklijn noemen we $X_{1}$.

<img src="/assets/images/newton2.png" style="width: 20%; max-width: 100%; height: auto;">

We merken dat deze nieuwe waarde $X_{1}$ al dichter bij de nulwaarde ligt. We kunnen op dezelfde manier deze methode herhalen door de raaklijn in $X_{1}$ te tekenen, enzovoort...

## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Schrijf een programma dat de methode van Newton-Raphson kan uitvoeren. Je gebruikt de functie en startwaarden uit het voorbeeld hierboven. Laat de methode 100 keer herhalen.
</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Definiëer $f(x)$ en $f'(x)$ apart.  
</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Reken op papier uit hoe je de raaklijn en het nulpunt van de raaklijn kan berekenen, voordat je begint met programmeren.
</div>

```python
def f(x):
    ...

def f'(x):
    ...



def newtonraphson(x):
    ...
    return(xnieuw)
```
*Je functie werkt als de waarden x steeds dichter bij $\sqrt{2}=1.414213562373095...$ nadert.*

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Test je code ook eens uit op andere functies, nulpunten en startwaarden.
</div>

## 🧩Afgeleide
In de vorige opdracht heb je de afgeleide functie zelf gedefiniëerd door de formule via de rekenregels uit te rekenen. Je kan ook de afgeleide in een punt zelf berekenen via een numerieke methode, door gebruik te maken van het **differentiequotiënt**.

De limietdefinitie is de volgende:

$f'(a) = \lim_{\Delta x \to 0} \frac{f(a + \Delta x) - f(a)}{\Delta x}$

Deze limiet zou je dus zelf kunnen benaderen via een numerieke methode waarbij je het quotiënt voor steeds kleinere waarden voor $\Delta x$ berekent.

## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Schrijf een functie die de afgeleide kan berekenen via een numerieke methode. Implementeer daarna deze functie in de Newton-Raphson methode van de vorige oefening
</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Het laten naderen van $\Delta x$ naar 0 kan bijvoorbeeld door een macht van $(\frac{1}{2})^n$ te laten oplopen.

</div>
