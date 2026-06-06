---
layout: default
title: For lus op een lijst
---

# For lus

Lussen of loops zijn structuren die we gebruiken wanneer we code willen laten herhalen. Eerder zagen we al de **while loop**, deze gebruiken we meestal wanneer het aantal herhalingen **onbepaald** is.

Daarnaast is er ook de **for loop**, deze gebruiken we meestal wanneer het aantal herhalingen **bepaald** is.

We gaan in totaal drie soorten for loops zien:
1. for loop op een **lijst** *<-- dit onderdeel*
2. for loop op een **string** *<--later*
3. for loop op een **range** *<--later*


# For lus op een lijst

We gebruiken een for loop op een lijst wanneer we **alle elementen** van deze lijst willen doorlopen, *en dus iets mee doen*.

Voorbeeld 1: alle elementen printen
```python
lijst = [1,2,3,4,5,"hond","kat"]
for x in lijst:
    print(x)
```

Voorbeeld 2: alle elementen uit een lijst verdubbelen*
```python
lijst = [1,2,3,4,5,"hond","kat"]
for x in lijst:
    print(2*x)
```
*Je merkt dat 'verdubbelen' een ander effect heeft naargelang het datatype.*

## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Voeg code toe aan het bovenstaande voorbeeld om uit te testen wat er met de lijst zelf is gebeurd.
</div>