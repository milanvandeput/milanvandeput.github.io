---
layout: default
title: 🧩 Tijd meten
---

# 🧩 Tijd meten

Hoe kan je experimenteel aantonen dat de ene zoekmethode snelle werkt dan de andere? **Tijdsmetingen** kunnen hiervoor helpen. Je meet hoe lang het duurt om je code uit te voeren met de module  **time**

```python
#dit is een externe module die eerst bovenaan je code geïmporteerd moet worden.
from time import time

begintijd = time()

#...
#voer je code uit
#...

eindtijd=time()

tijdsduur = eindtijd - begintijd
print(tijdsduur)
```

## Opdracht


<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Meet de tijdsduur van de verschillende zoekmethodes en vergelijk ze met elkaar. Gebruik dezelfde lengtes van lijsten om de test eerlijk te maken.
</div> 
<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Vooral bij zeer lange lijsten zal een snellere methode een merkbaar verschil hebben met een tragere methode. Maak gebruik van AI om extreem lange lijsten te genereren om je tijdsmetingen op uit te testen.
</div>


