---
layout: default
title:  🧩 Gelukkige koninginnen
---

# 🧩 Gelukkige koninginnen

Het is mogelijk om op een schaakbord 8 koninginnen te plaatsen zonder dat ze elkaar kunnen *raken (via een geldige zet).*

We noemen de koninginnen dan **gelukkig**.

![koningin](/assets/images/koninging.png)

###Posities op een schaakbord
We kunnen elke positie op een schaakbord aanduiden met twee coördinaten zoals in een assenstelsel (met linksonderaan de oorsprong). Deze kunnen we in python weergeven in een lijst:
```python
[1,1] #het vakje linksbeneden a1
[8,1] #het vakje rechtsbeneden h1
[7,3] #het vakje g3
```
De posities van de 8 koninginnen kunnen dan samen in een lijst worden gezet, een lijst van lijsten:
```python
posities1 = [[1,6],[5,1],[8,8],[3,5],[7,2],[6,4],[2,3],[4,7]]
posities2 = [[7,6],[3,4],[2,2],[4,8],[8,7],[6,1],[5,5],[1,3]]
posities3 = [[2,7],[8,4],[4,5],[1,3],[2,5],[8,2],[2,3],[4,2]]
```

## Uitdaging
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Schrijf een programma dat van een gegeven lijst posities kan berekenen of de koninginnen gelukkig zijn of niet.
</div>


### Voorbeeldtesten

Oplossing: 1 ja, 2 nee, 3 nee