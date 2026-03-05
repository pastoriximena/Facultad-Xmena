---
tipo: home
tags:
  - dashboard
---

# 🏠 Mi Vault

---

## 📚 Materias
```dataview
TABLE profesor AS "Profesor", cuatrimestre AS "Cuatrimestre", estado AS "Estado", nota_final AS "Nota Final"
FROM "Materias"
WHERE tipo = "materia"
SORT cuatrimestre ASC
```

---

## 📆 Próximas entregas
```dataview
TABLE file.link AS "Tarea", materia AS "Materia", fecha_entrega AS "Fecha"
FROM "Materias"
WHERE (tipo = "practico" OR tipo = "examen") AND fecha_entrega >= date(today) AND estado != "entregado" AND estado != "aprobado"
SORT fecha_entrega ASC
```

---

## 🔴 Temas pendientes
```dataview
TABLE materia AS "Materia"
FROM "Materias"
WHERE tipo = "tema" AND estado = "incompleto"
SORT materia ASC
```

---

## 📝 Últimas notas modificadas
```dataview
TABLE file.mtime AS "Última modificación"
FROM "Materias"
SORT file.mtime DESC
LIMIT 10
```

---

