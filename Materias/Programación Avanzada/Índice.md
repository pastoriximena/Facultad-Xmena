---
tipo: materia
nombre: Programación Avanzada
profesor: Verónica Aubin
cuatrimestre: 1C 2026
estado: cursando
nota_parcial_1:
nota_parcial_2:
nota_final:
tags:
  - materia
  - programacion
---
# 📚 Programación Avanzada

> [!info] Info rápida
> **Profesor:** `$= dv.current().profesor`
> **Cuatrimestre:** `$= dv.current().cuatrimestre`
> **Estado:** `$= dv.current().estado`
## 📅 Clases
```dataview
TABLE fecha AS "Fecha", tema AS "Tema", presente AS "Asistí"
FROM "Materias/Programacion Avanzada/Clases"
WHERE tipo = "clase"
SORT fecha ASC
```

## 📖 Temas pendientes
```dataview
LIST
FROM "Materias/Programacion Avanzada/Temas"
WHERE tipo = "tema" AND estado = "incompleto"
```

## 📝 Prácticos
```dataview
TABLE fecha_entrega AS "Entrega", estado AS "Estado", nota AS "Nota"
FROM "Materias/Programacion Avanzada/Practicos"
SORT fecha_entrega ASC
```

## 📆 Próximas fechas
```dataview
TABLE fecha_entrega AS "Fecha", estado AS "Estado"
FROM "Materias/Programación Avanzada"
WHERE fecha_entrega >= date(today)
SORT fecha_entrega ASC
```


