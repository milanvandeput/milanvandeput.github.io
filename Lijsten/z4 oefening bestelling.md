---
layout: default
title: 📝 Bestelling
---

# 📝 Bestelling

Een koppel passeert in de drive-through van een fastfoodketen. Ze geven een bestelling door:
* Ze geven beiden een item door uit het menu (*strings*).
* Ze geven een aantal door van hoeveel keer ze dit item willen (*integers*).
* Ze geven nog door of ze een kortingskaart hebben (*Boolean*)

## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">Schrijf een programma dat een bestelling opneemt van twee personen en deze gegevens bundelt in een lijst. De lijst wordt op het einde geprint.
</div>



### Voorbeeldtesten

|Boodschap | Invoer  | Uitvoer |
|----------| ------------- | ------------- |
|Welk item wil u bestellen?| chickenfingers|   |
|Hoeveel porties wil u bestellen?| 2|   |
|Welk item wil u bestellen?| cheeseburger|   |
|Hoeveel porties wil u bestellen?| 3|   |
|Heeft u een kortingskaart?| Nee|  ["chickenfingers",2,"cheeseburger",3,False]|

|Boodschap | Invoer  | Uitvoer |
|----------| ------------- | ------------- |
|Welk item wil u bestellen?| bickyburger|   |
|Hoeveel porties wil u bestellen?| 4|   |
|Welk item wil u bestellen?| cheeseburger|   |
|Hoeveel porties wil u bestellen?| 1|   |
|Heeft u een kortingskaart?| Ja|  ["bickyburger",4,"cheeseburger",1,True]|