---
layout: default
title:  Bestanden lezen (2)
---

# Bestanden lezen(2)

In de meeste tekstbestanden zullen de regels meerdere woorden bevatten.

```
hallo
dit is een voorbeeld
van een bestand

met meerdere woorden per regel

!!!
```

Het kan dan interessant zijn om in je code dit bestand woord per woord te lezen, in plaats van een hele regel in één keer. Hiervoor gebruiken we het **.split()** commando in python. Dit commando zal een string opdelen in meerdere stukken, gescheiden door een **spatie**, en deze achter elkaar in een **lijst** zetten. Daarna kan je de verschillende woorden uit deze lijst raadplegen via hun **index**.


Bestudeer de volgende code:
```python
zin = "hallo dit is een zin !"
zingesplitst = zin.split()

print(zingesplitst)
    # uitvoer: ['hallo', 'dit', 'is', 'een', 'zin', '!']

print(zingesplitst[1])
    # uitvoer: dit
```

**Opmerking:** je kan strings ook opsplitsen via een ander teken dan een spatie (bijvoorbeeld , ; -). Dan moet je dit teken als argument meegeven binnen de haakjes van *.split()*. Meer info: [split() method](https://www.w3schools.com/python/ref_string_split.asp) 


Voegen we het .split() commando toe aan onze vorige code, dan krijgen we nu volgende structuur:

```python
with open("test1.txt", "r") as bestand:
    for regel in bestand:
        regelgesplitst=regel.split()
        #....
```