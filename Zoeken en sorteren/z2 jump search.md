---
layout: default
title:  Jump search
---

# Jump search

*Jump search* is **sneller** dan lineair zoeken, maar werkt enkel op een **gesorteerde lijst**.


Bijvoorbeeld: we zoeken het getal 34 in onderstaande lijst.
```python
getallenlijst=[2,3,6,8,11,13,15,21,34,36,38,42,49,50]
```
We gaan doorheen de lijst zoeken naar 34 maar we nemen **sprongen met grootte k**. Op die manier hoeven we niet elk element te controleren. Wanneer we een element tegenkomen dat groter is dan 34, gaan we **achterwaards**  (lineair) terugzoeken in de lijst. 

Een voorbeeld met k=3:

<img src="/assets/images/jumpzoeken.png" style="width: 40%; max-width: 100%; height: auto;">



## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Implementeer de methode van jump search en voor ze uit op onderstaande voorbeelden.</div>
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Implementeer eerst een methode die de sprongen kan maken. Daarna pas begint het achterwaards zoeken.
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