---
layout: default
title: 🧩 Draaiknop
---

# 🧩 Draaiknop

Een draaiknop bevat de cijfers van 0 tot en met 99. Momenteel staat de draaiknop op 50. 

Via een aantal instructies wordt er verteld welke bewegingen de draaiknop maakt.

- **L 8** betekent dat het cijfer met 8 afneemt, bijvoorbeeld van 50 naar 42.
- **R 10** betekent dat het cijfer met 10 toeneemt, bijvoorbeeld van 50 naar 60.
- Indien het cijfer de 0 passeert, draait hij gewoon verder in dezelfde richting. Bijvoorbeeld: **L68** laat de draaiknop van 50 naar 82 gaan.
<img src="/assets/images/draaiknop.png" style="width: 20%; max-width: 100%; height: auto;">

## Opdracht

We willen tellen **hoe vaak de draaiknop op 0 terecht komt**. Dit is de score.

Een voorbeeldje: L 68  L 30  R 48  L 5  R 60  L 55  L 1  L 99  R 14  L 82

- De knop start op 50.
- De knoop draait via L 68 naar 82.
- De knoop draait via L 30 naar 52.
- De knoop draait via R 48 naar **0**.
- De knoop draait via L 5 naar 95.
- De knoop draait via R 60 naar 55.
- De knoop draait via L 55 naar **0**.
- De knoop draait via L 1 naar 99.
- De knoop draait via L 99 naar **0**.
- De knoop draait via R 14 naar 14.
- De knoop draait via L 82 naar 32.

Deze bewegingen hebben dus een **score van 3**.

<a href="/assets/files/draaiknop.txt" download="draaiknop">Download hier het tekstbestand met de bewegingen van de draaiknop.</a>

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Schrijf een programma dat de score berekent van de draaibewegingen uit het bijgevoegde bestand.
</div> 



### Voorbeeldtesten
Het antwoord van het bijgevoegde bestand is **1105**. Het is aangeraden om eerst zelf een kleiner testbestand te maken.

Heb je het juist? Proficiat, je hebt zonet de eerste opgave opgelost van de **Advent of code 2025**. Bekijk zeker eens de website voor meer van deze gevorderde vragen  [adventofcode.com](https://adventofcode.com/2025/about) 


