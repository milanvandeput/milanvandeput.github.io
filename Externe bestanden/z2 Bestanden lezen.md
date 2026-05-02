---
layout: default
title:  Bestanden lezen
---

# Bestanden lezen

De lijnen code die je in de vorige oefening hebt uitgevoerd, geven de basisstructuur van hoe je bestanden kan inlezen.

```python
with open("test1.txt", "r") as bestand:
    #...
```

- Het eerste argument *(hier: "test1.txt")* is de **naam** van het bestand. Deze moet exact overeenkomen.
- Het tweede argument is de **modus**, m.a.w. de manier waarop je het bestand wil openen:
    - **"r"** is de leesmodus (*read*)
    - **"w"** is de schrijfmodus (*write*)
    - **"a"** is de aanvulmodus (*append*)

Het bestand openen in een verschillende modus, geeft je code andere rechten tot wat het wel en niet mag doen met het bestand. In dit eerste deel beperken we ons tot de leesmodus.

## Leesmodus ("r")
Wanneer je een tekstbestand opent in de **leesmodus ("r")**, kan je code alle regels tekst lezen maar het bestand zelf kan niet gewijzigd worden.

Een tekstbestand bestaat uit meerdere regels. Je code zal daarom vrijwel altijd beginnen met een for-loop om de verschillende regels tekst om de beurt in te lezen. De regels worden regel per regel ingelezen als **string**.

```python
with open("test1.txt", "r") as bestand:
    for regel in bestand:
        #hier komt je code...
        print(regel)
```
**Binnen de for-loop** kan je met deze regels doen wat je wil: printen, opslaan in een variabele, bewerkingen uitvoeren, toevoegen aan een lijst, etc.

