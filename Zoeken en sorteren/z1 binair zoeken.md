---
layout: default
title:  Binair zoeken
---

# Binair zoeken

Binair zoeken is **sneller** dan lineair zoeken, maar werkt enkel op een **gesorteerde lijst**.


Bijvoorbeeld: we zoeken het getal 34 in onderstaande lijst.
```python
getallenlijst=[2,3,6,8,11,13,15,21,34,36,38,42,49,50]
```
We kunnen het getal 34 zoeken door eerst naar het middelste getal van de lijst te kijken. Dit is 15 en dit is kleiner dan 34 dus we kunnen alle getallen links van 15 al schrappen. Dan bekijken we opnieuw het midden van de overgebleven getallen enzovoort...

<img src="/assets/images/binairzoeken.png" style="width: 40%; max-width: 100%; height: auto;">



## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Implementeer de methode van het binair zoeken en voor ze uit op onderstaande voorbeelden.</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Schrijf een aparte functie die het midden m kan bepalen van de ondergrens a en bovengrens b.
</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Gebruik //2 om het midden van de lijst te bepalen. Zo wordt de index afgerond indien er geen exact midden bestaat.  
</div>

### Voorbeeldtest

```python
lijst1= [2,3,6,8,11,13,15,21,34,36,38,42,49,50]
```
Zoek 34, dit heeft index 8.

### Voorbeeldtest

```python
lijst2= 
[1, 2, 3, 4, 5, 6, 7, 8, 10, 11,12, 13, 14, 16, 18, 19, 21, 22, 23, 24,27, 29, 31, 34, 36, 37, 39, 41, 45, 49,53, 54, 56, 58, 60, 63, 66, 67, 70, 72,75, 76, 81, 84, 88, 90, 92, 95, 98, 100]
```
Zoek 90, dit heeft index 45.