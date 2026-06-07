---
layout: default
title: Functies definiëren
---

# Functies
Functies kennen we uit de wiskundeles. Voor een bepaalde input x, berekent de functie een output, bijvoorbeeld x²+x-1.

Ook in Python bestaan er functies, maar deze kunnen veel meer dan enkel berekeningen doen. Een aantal functies kennen we al uit de voorbije lessen:

```python
print(x)  #deze functie print een variabele

int(x)  #deze functie verandert het datatype van x naar integer

round(x,y) #deze functie rondt het getal x af op y cijfers na de komma
```

Een functie bestaat uit een **naam**, bijvoorbeeld *print* en heeft geen/een/meerdere *parameters* als input tussen de haakjes, gescheiden door een komma.

Soms moet een parameter van een bepaald **datatype** zijn. Bijvoorbeeld: de variabele *y* bij *round(x,y)* moet een natuurlijk getal zijn.

# Functies definiëren
Python beschikt dus al over heel wat functies. Maar je kan ook zelf een functie definiëren.

Bijvoorbeeld: je wil zelf een functie maken die telkens 10 van een getal aftrekt.
```python
def tien_aftrekken(x):  #achter def geef je de naam van je functie. Tussen de haakjes staan de eventuele argumenten.
  y = x-10
  return(y)             #return is de output die de functie teruggeeft.
```

In de bovenstaande code wordt de functie gedefiniëerd. Deze code heeft zelf geen uitvoer. Om een uitvoer te krijgen, moet je de functie ook **oproepen**.

```python 
def tien_aftrekken(x):  
  y = x-10
  return(y) 

a = tien_aftrekken(65)
print(a)

b = tien_aftrekken(100) + tien_aftrekken(4)
print(b)

c = tien_aftrekken(tien_aftrekken(21))
print(c)
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
