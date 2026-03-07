---
tipo: materia
nombre: Autómatas y Gramática
profesor:
cuatrimestre: 1C 2026
estado: cursando
nota_parcial_1:
nota_parcial_2:
nota_final:
tags:
  - materia
---
# 📚 Autómatas y Gramática

> [!info] Info rápida
> **Profesor:** `$= dv.current().profesor`
> **Cuatrimestre:** `$= dv.current().cuatrimestre`
> **Estado:** `$= dv.current().estado`

---

## 📅 Clases
```dataview
TABLE fecha AS "Fecha", tema AS "Tema", presente AS "Asistí"
FROM "Materias/Autómatas y Gramática/Clases"
WHERE tipo = "clase"
SORT fecha ASC
```

---

## 📖 Temas pendientes
```dataview
LIST
FROM "Materias/Autómatas y Gramática/Temas"
WHERE tipo = "tema" AND estado = "incompleto"
```

---

## 📝 Prácticos
```dataview
TABLE fecha_entrega AS "Entrega", estado AS "Estado", nota AS "Nota"
FROM "Materias/Autómatas y Gramática/Practicos"
WHERE tipo = "practico"
SORT fecha_entrega ASC
```


---

## 📆 Próximas fechas
```dataview
TABLE fecha_entrega AS "Fecha", estado AS "Estado"
FROM "Materias/Autómatas y Gramática"
WHERE fecha_entrega >= date(today)
SORT fecha_entrega ASC
```

---

## 📚 Bibliografía

![[Bibliografía]]
