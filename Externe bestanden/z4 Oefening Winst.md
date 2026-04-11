---
layout: default
title: 📝 Winst
---

# 📝 Winst

## Opdracht

<a href="/assets/files/test.txt" download="test1">Download hier het voorbeeld van een tekstbestand voor deze oefening.</a>

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Download het tekstbestand en plaats het in dezelfde map als je python code. Voer dan de volgende code uit:
</div> 

```python
with open("test1.txt", "r") as bestand:
    for lijn in bestand:
        print(lijn)
```

### Voorbeeldtesten
Je hebt dit correct gedaan als het tekstbestand regel per regel via je python code wordt geprint.
