---
layout: default
title: Spelen met variabelen
---

# Spelen met variabelen

De waarde van een variabele aanpassen of kopiëren naar een nieuwe variabele kan je allemaal eenvoudig doen met het **=** teken. Maar je moet wel goed in gedachten houden welke variabele op welk moment welke waarde bevat.

## Opdracht
<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Probeer van de onderstaande code te voorspellen wat de uitvoer zal zijn. Controleer daarna je antwoord door ze te runnen.
</div>

**Opgave a)**

```python
a=7
b=a
a=10
print(b)
```

**Opgave b)**

```python
a=7
b=10
b=a
a=b
c=a+b
print(c)
```

**Opgave c)**
```python
a=7
b=10
a=a+b
b="a"
print(b)
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