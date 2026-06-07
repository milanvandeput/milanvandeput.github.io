---
layout: default
title: Het nut van functies
---

# Het nut van functies

Waarom gebruiken we functies in een programma? Funties kunnen **structuur aanbrengen in een langer programma** waarin je bepaalde stukken code herhaaldelijk uitvoert.

We illustreren dit met een programma dat een reeks van 4 cijfers naar tekst omzet.

```python
cijfer1 = 4    
cijfer2 = 3
cijfer3 = 8
cijfer4 = 3

if cijfer1==0:
  print("nul")
elif cijfer1==1:
  print("een")
elif cijfer1==2:
  print("twee")
elif cijfer1==3:
  print("drie")
elif cijfer1==4:
  print("vier")
elif cijfer1==5:
  print("vijf")
elif cijfer1==6:
  print("zes")
elif cijfer1==7:
  print("zeven")
elif cijfer1==8:
  print("acht")
elif cijfer1==9:
  print("negen")


if cijfer2==0:
  print("nul")
elif cijfer2==1:
  print("een")
elif cijfer2==2:
  print("twee")
elif cijfer2==3:
  print("drie")
elif cijfer2==4:
  print("vier")
elif cijfer2==5:
  print("vijf")
elif cijfer2==6:
  print("zes")
elif cijfer2==7:
  print("zeven")
elif cijfer2==8:
  print("acht")
elif cijfer2==9:
  print("negen")


if cijfer3==0:
  print("nul")
elif cijfer3==1:
  print("een")
elif cijfer3==2:
  print("twee")
elif cijfer3==3:
  print("drie")
elif cijfer3==4:
  print("vier")
elif cijfer3==5:
  print("vijf")
elif cijfer3==6:
  print("zes")
elif cijfer3==7:
  print("zeven")
elif cijfer3==8:
  print("acht")
elif cijfer3==9:
  print("negen")

if cijfer4==0:
  print("nul")
elif cijfer4==1:
  print("een")
elif cijfer4==2:
  print("twee")
elif cijfer4==3:
  print("drie")
elif cijfer4==4:
  print("vier")
elif cijfer4==5:
  print("vijf")
elif cijfer4==6:
  print("zes")
elif cijfer4==7:
  print("zeven")
elif cijfer4==8:
  print("acht")
elif cijfer4==9:
  print("negen")
```
Het vorige programma werkt, maar is langdradig doordat we **dezelfde code vier keer moeten herhalen**.

We gaan deze code dus in een functie zetten.

```python
def cijfer_naar_tekst(x):
  if x==0:
    print("nul")
  elif x==1:
    print("een")
  elif x==2:
    print("twee")
  elif x==3:
    print("drie")
  elif x==4:
    print("vier")
  elif x==5:
    print("vijf")
  elif x==6:
    print("zes")
  elif x==7:
    print("zeven")
  elif x==8:
    print("acht")
  elif x==9:
    print("negen")
  return()  #geen return. Deze functie heeft dus geen output, maar er worden wel dingen geprint tijdens de uitvoer van de functie

cijfer1 = 4
cijfer2 = 3
cijfer3 = 8
cijfer4 = 3

cijfer_naar_tekst(cijfer1)    
cijfer_naar_tekst(cijfer2)
cijfer_naar_tekst(cijfer3)
cijfer_naar_tekst(cijfer4)

```
Een heel stuk eenvoudiger, toch?