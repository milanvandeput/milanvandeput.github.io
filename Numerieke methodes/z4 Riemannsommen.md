---
layout: default
title:  📝 Riemannsommen
---

# 📝 Riemannsommen

**Riemannsommen** geven een benadering van de integraal van een functie $f(x)$ met ondergrens $a$ en bovengrens $b$. Het interval wordt in $n$ gelijke stroken verdeeld. In elke strook wordt een rechthoek getekend. De som van deze rechthoeken benadert de werkelijke oppervlakte.

<img src="/assets/images/riemann.png" style="width: 30%; max-width: 100%; height: auto;">

*Het is in de eerste opdracht nog niet belangrijk of je met de middensom, ondersom of bovensom werkt.* 



## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Definiëer een functie *rieman(a,b,n)* die de oppervlakte kan benaderen via een som van *n* rechthoeken.
</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Definiëer $f(x)$ apart.  
</div>


```python
def f(x):
    ...

def rieman(a,b,n):

    return(oppervlakte)
```
*Je kan je programma testen op de functie $f(x)=-x^2+4$ in $[1,2]$ met een oppervlakte van 9. 

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Test je code ook eens uit op andere functies en intervallen.
</div>


