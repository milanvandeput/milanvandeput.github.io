---
layout: default
title:  Lineair zoeken
---

# Lineair zoeken

We willen de positie van het getal 34 vinden in een lijst getallen.

```python
getallenlijst=[38,3,6,50,11,13,15,34,21,36,2,42,49,8]
```

We kunnen dit doen door de getallen in de lijst een voor een af te gaan, dit heet **lineair zoeken**.
<img src="/assets/images/lineairzoeken.png" style="width: 40%; max-width: 100%; height: auto;">

Dit is een vrij trage methode maar voor een **ongesorteerde lijst** is er geen andere methode die sneller zal werken.

## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">

Implementeer de methode van het lineair zoeken en voor ze uit op onderstaande voorbeelden.</div>

### Voorbeeldtest

```python
lijst1= [7, 12, 3, 45, 22, 98, 14, 67, 1, 39,56, 81, 23, 90, 5, 34, 76, 2, 88, 19,41, 60,11, 72, 29, 84, 6, 53, 100, 16,27, 58, 4, 92, 36, 75, 8, 66, 21, 49,10, 31, 63, 18, 95, 24, 70, 13, 54, 37]
```
Zoek 90, dit heeft index 13.

### Voorbeeldtest

```python
lijst2= [100, 16,27, 58, 4, 92, 36, 75, 8, 66, 21, 49, 7, 12, 3, 45, 22, 98, 14, 67, 1, 39,56, 81, 23, 90, 5, 34, 76, 2, 88, 19,41, 60,11, 72, 29, 84, 6, 53,10, 31, 63, 18, 95, 24, 70, 13, 54, 37]
```
Zoek 58, dit heeft index 3.

