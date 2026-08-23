---
layout: default
title: 📝 Temperatuur
---

# 📝 Temperatuur

De formule voor het verband tussen een temperatuur *C* in graden Celsius en een temperatuur *F* in graden Fahrenheit is:

$$F=\frac{9}{5}C+32$$

## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">Schrijf een programma dat een temperatuur (in Celsius) vraagt en deze omzet naar Fahrenheit.
</div>

<div style="
    background-color: #daabff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">ℹ️ De input die je hier opvraagt is een decimaal getal (=float). Je moet dus ook meteen bij het vragen van de input het datatype naar float veranderen. Dit doe je met de functie float() die we hiervoor geleerd hebben.
</div>

```python
temperatuur = float(input())
```

<details>
<summary><span style="color: #daabff"><b>Python code uitvoeren 🐍</b></span></summary>
<iframe
src="https://www.onlineide.pro/playground/python"
width="100%"
height="500"
frameborder="10">
</iframe>
</details>


### Voorbeeldtesten

| Invoer  | Uitvoer |
| ------------- | ------------- |
| 10  | 50.0  |
| 20  | 68.0 |
| 23 | 73.4 |