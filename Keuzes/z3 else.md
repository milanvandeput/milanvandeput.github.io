---
layout: default
title: else
---

# else

De *partner-in-crime* van de **if** bij het programmeren is de **else**. Deze kan je toevoegen als je wilt dat het programma ook iets doet indien de voorwaarde bij de if **niet voldaan** was.

**Voorbeeld: terug naar het pretpark**
```python
print("Welkom in het pretpark!")

lengte = int(input("Wat is je lengte?"))

if lengte < 160:
    print("oei je bent te klein voor deze attractie :( ")
else:
    print("je bent groot genoeg, geniet ervan!")

print("Tot de volgende keer!")
```

Heb je de bovenstaande code begrepen?
* Achter *else* moet ook een **:** volgen zoals bij *if*.
* De code op lijn 8 wordt uitgevoerd indien de voorwaarde bij *if* niet voldaan was.
* **Opmerking:** Je mag dus geen (andere) voorwaarde toevoegen achter *else*. 
* **Opmerking2:** je kan geen *else* gebruiken zonder *if*.

**Een figuur om het voorgaande samen te vatten:**
![ifelse](/assets/images/ifelseschema.png)