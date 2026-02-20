---
layout: default
title: Datatypes veranderen (2)
---

Voer de volgende code uit:
```python
var1 = "vier"
var2= "acht"

print(var1+var2)
```

Had je deze uitvoer verwacht? Of dacht je misschien dat er "twaalf" zou geprint worden?

<details>
  <summary>Verklaring</summary>
  De bewerking + reageert hier anders omdat het datatype van *var1* en *var2* een string is. En strings worden achter elkaar geplakt in plaats van opgeteld zoals bij integers of floats.
</details>


## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Wat zal de uitvoer van deze code zijn? Denk aan de datatypes.
</div>

```python
schooljaar1 = "2024-2025"
schooljaar2 = 2024 - 2025

print(schooljaar1)
print(schooljaar2)
```

<details>
  <summary>Verklaring</summary>
  Schooljaar1 is een string en zal dus zo geprint worden. Schooljaar2 is een integer en dus zal hier de bewerking uitgevoerd worden.
</details>
