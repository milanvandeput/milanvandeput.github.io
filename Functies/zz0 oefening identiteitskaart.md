---
layout: default
title: 📝 Identiteitskaart
---

# 📝 Identiteitskaart

Dit is een oefening op een functie met meerdere returnwaarden.

## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">Definiëer een functie identiteitskaart(naam,leeftijd) die allerlei gegevens genereert over een persoon van wie de naam en leeftijd wordt gegeven.
</div>

Deze functie moet vier returnwaarden hebben.
- Een begroeting *'Hallo, [naam]!'*
- Meerderjarig of Minderjarig
- Het geboortejaar (we gaan er van uit dat de persoon op 1 januari geboren is).
- Een controle of de naam normaal is. In deze oefening beschouwen we alle namen met een x als vreemd, en ook alle namen zonder de letter a. De functie returned '*Vreemde naam*' of '*Naam OK*'

<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️Splits deze opdracht op in 4 aparte opdrachten. Test een deelopdracht uit voor je naar de volgende overgaat.
</div>


### Voorbeeldtesten

| Oproepen functie  | Uitvoer |
| ------------- | ------------- |
|identiteitskaart("Milan",27) | ("Hallo, Milan!", "Meerderjarig", 1999, "Naam OK") |

| Oproepen functie  | Uitvoer |
| ------------- | ------------- |
|identiteitskaart("Robert",13)[0] | Hallo, Robert!|
|identiteitskaart("Robert",13)[1] | Minderjarig|
|identiteitskaart("Robert",13)[2] | 2013|
|identiteitskaart("Robert",13)[3] | Vreemde naam|