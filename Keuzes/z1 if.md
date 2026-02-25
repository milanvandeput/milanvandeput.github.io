---
layout: default
title: if
---

# if

**if** kan gebruikt worden om **voorwaardelijke code** te schrijven. Dat betekent dat een stukje code enkel uitgevoerd zal worden indien er aan een bepaalde voorwaarde is voldaan. Deze voorwaarde is altijd een booleaanse variabele.

**Voorbeeld: voer deze code uit**

```python
print("Welkom in het pretpark!")

lengte = int(input("Wat is je lengte?"))

if lengte < 160:
    print("oei je bent te klein voor deze attractie :( ")
    
print("Tot de volgende keer!")
```

Begrijp je de werking van de code hierboven? 
* Achter *if* komt de voorwaarde (in dit geval een ongelijkheid). 
* Daarna komt altijd een **:**. 
* De code op lijn 6 staat een tab naar rechts. Deze code wordt enkel uitgevoerd indien er aan de voorwaarde voldaan is.
* De code vanaf lijn 8 staat weer op de oorspronkelijke inspringing. Deze wordt dus altijd uitgevoerd.