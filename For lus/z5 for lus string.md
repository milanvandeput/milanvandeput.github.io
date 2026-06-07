---
layout: default
title: For lus string
---

We komen nu aan het derde en laatste type van een for loop.

- for loop op een lijst *<-- al gezien*
- for loop op een range *<-- al gezien*
- **for loop op een string** 

### For loop string
Deze for loop werkt opnieuw met een **lopende variabele x**, die nu elk **karakter*** van de string aanneemt.

**Karakters zijn niet enkel letters maar ook cijfers, leestekens en zelfs spaties.*

```python
for x in "Hallo, dit is mijn eerste for loop op een string!":
  print(x)
```

### Werken met strings
De volgende oefeningen zullen gaan over het bewerken van strings. Hier is nog eens een samenvatting van de commando's op strings.

```python 
var = "string voorbeeld"

print(var[2])     #Geeft het 2de teken terug
print(var[2:10])   #Geeft het 2de t.e.m. 9de teken terug
print(var[:2])    #Geeft de eerste 2 tekens terug
print("a" in var) #Checkt of een karakter voorkomt in de string (Boolean)

```