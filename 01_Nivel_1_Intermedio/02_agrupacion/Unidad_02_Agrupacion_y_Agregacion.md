# Módulo 02 — Agrupación y agregación

> De listas a resúmenes: la base del análisis de datos con SQL.

## 🎯 Objetivo

Resumir muchas filas en una sola por grupo usando funciones agregadas.

## 📖 Conceptos a aprender

- Funciones agregadas: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`.
- `COUNT(*)` vs `COUNT(columna)` (diferencia con `NULL`).
- `GROUP BY` para agrupar por una o varias columnas.
- `HAVING` para filtrar grupos (a diferencia de `WHERE`, que filtra filas).
- Orden de ejecución: `WHERE` filtra **antes** de agrupar; `HAVING` **después**.
- Agrupar por más de una columna.

## ✅ Tareas

- [ ] Tarea 1: `01_agregadas.sql` — contar clientes totales, suma de precios, promedio,
      mínimo y máximo de una columna.
- [ ] Tarea 2: `02_group_by.sql` — contar clientes **por ciudad**.
- [ ] Tarea 3: `03_group_by_varias.sql` — agrupar por 2 columnas
      (ej: ventas por ciudad y mes).
- [ ] Tarea 4: `04_having.sql` — ciudades con más de 5 clientes (usar `HAVING COUNT(*) > 5`).
- [ ] Tarea 5: `05_where_vs_having.sql` — misma consulta aplicando filtro con `WHERE`
      y con `HAVING`, y explica en un comentario la diferencia.

## 📦 Entregables

- `01_agregadas.sql` … `05_where_vs_having.sql`

> 💡 **Pregunta para investigar:** ¿qué devuelve `AVG` si una columna tiene `NULL`?
> Escríbelo en un comentario de `01_agregadas.sql`.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — GROUP BY Statement](https://www.w3schools.com/sql/sql_groupby.asp) — agrupar y resumir.
- 📘 [W3Schools — HAVING Clause](https://www.w3schools.com/sql/sql_having.asp) — filtrar grupos.
- 🎮 [SQLZoo](https://sqlzoo.net/) — tutorial de SUM y COUNT.

---

## 📂 ¿Qué debe colocar la persona en esta carpeta?

Todo el **trabajo realizado**, en cualquier formato:

- 🖼️ **Imágenes** (`.png`, `.jpg`): diagramas, capturas de pantalla de resultados.
- 📄 **Word** (`.docx`): resúmenes, informes o explicaciones.
- 📊 **Excel** (`.xlsx`): tablas de datos, cálculos o comparativas.
- 🗄️ **Base de datos** (`.db`, `.sqlite`): la base de datos trabajada.
- 💾 **Consultas y scripts** (`.sql`): ejercicios resueltos y scripts creados.

> Regla de nombres: un archivo por actividad, con nombre descriptivo
> (ej: `diagrama_er_final.png`, `practica_joins.sql`, `resumen_actividad.docx`).

