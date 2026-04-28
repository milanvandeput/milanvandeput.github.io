---
layout: default
title:  Bestanden schrijven
---

# Bestanden schrijven

Om bestanden te schrijven, gebruiken we de modus **w** (write).

```python
with open("testschrijf.txt", "w") as bestand:
    #...
```

- Deze code zal in dezelfde map een nieuw tekstbestand aanmaken met de gegeven naam.
- Als er al een tekstbestand bestaat met die naam, zal deze code **dat bestand volledig overschijven**.


## Schrijfmodus ("w")
In de schrijmodus kan je eender welke tekst toevoegen aan je bestand met het commando *.write*.

Meestal zal je aan het einde van elke regel een **\n** willen toevoegen. Deze n staat voor *newline* en zorgt ervoor dat je op de volgende regel verder schrijft.

```python
with open("testschrijf.txt", "w") as bestand:
    bestand.write("Hallo!\n")
    bestand.write("Dit is een bestand dat ik met python code heb geschreven\n")
    bestand.write("Dit begint stilaan meer op een schrijopdracht Nederlands te lijken...")

```

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Test de schrijfmodus uit door een tekst naar keuze te schrijven in een tekstbestand via python code.
</div> 

