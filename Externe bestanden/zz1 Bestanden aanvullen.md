---
layout: default
title:  Bestanden aanvullen
---

# Bestanden aanvullen

Om bestanden aan te vullen, gebruiken we de modus **a** (append).

```python
with open("testaanvul.txt", "a") as bestand:
    bestand.write("\nDeze tekst voeg ik toe op een nieuwe regel")
```

- Het schrijven van nieuwe regels tekst gebeurt op dezelfde manier als in de *write*-modus. Het verschil is nu dat de bestaande tekst ook behouden blijft. 
- De regels worden automatisch achter de laatste bestaande regel tekst in het bestand geschreven. Daarom begin je meestal met een *\n* om een nieuwe regel te starten.


<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Test de aanvulmodus uit door een tekst naar keuze toe te voegen aan een reeds bestaand tekstbestand via python code.
</div> 

## Verschillende modussen gebruiken
Soms wil je in eenzelfde tekstebestand regels lezen en ook regels toevoegen. Het is belangrijk om te onthouden dat dit **niet tegelijk in één modus kan.** Je moet het bestand dan bijvoorbeeld eerst openen in de leesmodus en daarna in de aanvulmodus.

```python
with open("testaanvul.txt", "r") as bestand:
    for regel in bestand:
        ... #regels lezen

#Daarna op nieuw het bestand openen in de andere modus
with open("testaanvul.txt", "a") as bestand:
    bestand.write("\nDeze tekst voeg ik toe op een nieuwe regel")
```


