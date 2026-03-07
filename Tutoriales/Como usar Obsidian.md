---
tutorial: formato
---
```dataview
TABLE WITHOUT ID file.link AS "Tutorial", tutorial AS "Tipo"
WHERE tutorial = "formato"
```
---

## Índice
- [[#Agregar Links a otras notas:|Agregar Links a otras notas:]]
- [[#Fondos para canvas:|Fondos para canvas:]]

### Agregar Links a otras notas

	"[[Facultad-Xmena/Materias/Autómatas y Gramática/Índice|Autómatas y Gramática ]]"
- Entre corchetes
- Lo que viene despues del "|" es para que se muestre con un nombre custom

### Fondos para canvas


````css title="Cuadrícula"
.canvas-background {
  background-image: 
    linear-gradient(rgba(255,255,255,0.05) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.05) 1px, transparent 1px);
  background-size: 50px 50px;
}
````
<div style="
  width: 100%;
  height: 150px;
  border-radius: 8px;
  background-image: linear-gradient(rgba(255,255,255,0.05) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.05) 1px, transparent 1px);
  background-size: 50px 50px;
  background-color: #1e1e1e;
">
</div>

````css title="Punteado"
.canvas-background {
  background-image: radial-gradient(circle, rgba(255,255,255,0.15) 1px, transparent 1px);
  background-size: 30px 30px;
}
````
<div style="
  width: 100%;
  height: 150px;
  border-radius: 8px;
  background-image: radial-gradient(circle, rgba(255,255,255,0.15) 1px, transparent 1px);
  background-size: 30px 30px;
  background-color: #1e1e1e;
">
</div>

````css title="Lineas Diagonales"
.canvas-background {
  background-image: repeating-linear-gradient(
    45deg,
    rgba(255,255,255,0.05) 0px,
    rgba(255,255,255,0.05) 1px,
    transparent 1px,
    transparent 50px
  );
}
````
<div style="
  width: 100%;
  height: 150px;
  border-radius: 8px;
  background-image: repeating-linear-gradient(
    45deg,
    rgba(255,255,255,0.05) 0px,
    rgba(255,255,255,0.05) 1px,
    transparent 1px,
    transparent 50px
  );
  background-color: #1e1e1e;
">
</div>

````css title="Patrón geométrico"
.canvas-background {
  background-image: repeating-linear-gradient(
    60deg,
    rgba(255,255,255,0.05) 0px,
    rgba(255,255,255,0.05) 1px,
    transparent 1px,
    transparent 30px
  ),
  repeating-linear-gradient(
    -60deg,
    rgba(255,255,255,0.05) 0px,
    rgba(255,255,255,0.05) 1px,
    transparent 1px,
    transparent 30px
  );
}
````
<div style="
  width: 100%;
  height: 150px;
  border-radius: 8px;
  background-image: repeating-linear-gradient(
    60deg,
    rgba(255,255,255,0.05) 0px,
    rgba(255,255,255,0.05) 1px,
    transparent 1px,
    transparent 30px
  ),
  repeating-linear-gradient(
    -60deg,
    rgba(255,255,255,0.05) 0px,
    rgba(255,255,255,0.05) 1px,
    transparent 1px,
    transparent 30px
  );
  background-color: #1e1e1e;
">
</div>

````css title="Cuadrícula con punto en la intersección"
.canvas-background {
  background-image: 
    radial-gradient(circle, rgba(255,255,255,0.2) 1px, transparent 1px),
    linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
  background-size: 30px 30px;
}
````
<div style="
  width: 100%;
  height: 150px;
  border-radius: 8px;
  background-image:
    radial-gradient(circle, rgba(255,255,255,0.2) 1px, transparent 1px),
    linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
  background-size: 30px 30px;
  background-color: #1e1e1e;
">
</div>

````css title="Color de fondo sólido distinto al negro"
.canvas-background {
  background-color: #1a1a2e;
}
````
<div style="
  width: 100%;
  height: 150px;
  border-radius: 8px;
  background-color: #1a1a2e;
">
</div>
