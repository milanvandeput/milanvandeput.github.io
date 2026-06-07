---
layout: default
title: For lus
---

# For lus

Lussen of loops zijn structuren die we gebruiken wanneer we code willen laten herhalen. Eerder zagen we al de **while loop**, deze gebruiken we meestal wanneer het aantal herhalingen **onbepaald** is.
 Daarnaast is er ook de **for loop**, deze gebruiken we meestal wanneer het aantal herhalingen **bepaald** is.

We gaan in totaal drie soorten for loops zien:
1. for loop op een **lijst** *<-- al gezien*
2. for loop op een **range** *<-- dit onderdeel*
3. for loop op een **string** *<--later* 

# For lus range
Bij deze *range loops* gebruik je ook een **lopende variabele x**. De *x* is een integer dat je laat variëren **tussen 0 en n-1**. 

```python
for x in range(10):
  print(x)
```
Je merkt dat x nooit de waarde 10 wordt.

Als je de loop wil laten beginnen bij een andere waarde dan 0, gebruik dan 2 parameters bij de range:

```python
for x in range(5,10):
  print(x)
```

## Opdracht

<div style="
    background-color: #b0cdff;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #ddd;
">
Test de bovenstaande codes uit zodat je de werking ervan begrijpt. Experimenteer gerust door dingen aan te passen.
</div>