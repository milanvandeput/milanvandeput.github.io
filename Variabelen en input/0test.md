---
layout: default
title: test
---

# Python Demo
<textarea id="code" rows="10" cols="60">
print("Hallo wereld")
</textarea>
<button onclick="runPython()">Uitvoeren</button>
<pre id="output"></pre>
<script type="module">
import { loadPyodide } from "https://cdn.jsdelivr.net/pyodide/v0.28.2/full/pyodide.mjs";
 
let pyodide = await loadPyodide();
window.runPython = async function() {
const code = document.getElementById("code").value;
try {
const result = await pyodide.runPythonAsync(code);
document.getElementById("output").textContent =
result ?? "Code uitgevoerd";
} catch (err) {
document.getElementById("output").textContent = err;
}
}
</script>

# oef a
oef a van les 1

```python
leeftijd = 16
naam = "Robbe"
temperatuur = 23.24
for i in range(10):
  print(i+1)
  if i==2:
    i=3
```
<details>
  <summary>voorbeeldtesten</summary>
  ehehehe
</details>

## Voorbeeldtesten

| Oproepen functie          | Uitvoer |
|---------------------------|---------|
| oppervlakte_rechthoek(2,3) | 6      |

| Oproepen functie          | Uitvoer |
|---------------------------|---------|
| omtrek_rechthoek(2,3)     | 10     |

| Oproepen functie          | Uitvoer |
|---------------------------|---------|
| som_rechthoek(2,3)        | 16     |


