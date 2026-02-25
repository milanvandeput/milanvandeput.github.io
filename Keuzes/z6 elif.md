---
layout: default
title: elif
---

# elif
Wanneer je een groot aantal voorwaarden na elkaar wil nagaan, kan het gebruik van het *elif* statement de code eenvoudiger en leesbaarder maken. 

*elif* betekent hetzelfde als een nieuw *if* statement dat meteen na een *else* statement komt.


## Voorbeeld
We schrijven een programma om een getal (tussen 1 en 5) te raden. De onderstaande code werkt wel maar is heel onduidelijk om te lezen. 

```python
getal = int(input("Geef een getal"))

if getal==1:
  print("Het is een!")
else:
  if getal==2:
    print("Het is twee!")
  else:
    if getal==3:
      print("Het is drie!")
    else:
      if getal==4:
        print("Het is vier!")
      else:
        print("Het is vijf!")
```
Deze code kan veel eenvoudiger geschreven worden met het *elif* statement.

```python
getal = int(input("Geef een getal"))

if getal==1:
  print("Het is een!")
elif getal==2:
  print("Het is twee!")
elif getal==3:
  print("Het is drie!")
elif getal==4:
  print("Het is vier!")
else:
  print("Het is vijf!")
```