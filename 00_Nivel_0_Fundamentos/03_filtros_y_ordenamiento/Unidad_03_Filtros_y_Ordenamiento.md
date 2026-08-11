# Módulo 03 — Filtros y ordenamiento

> Aquí tus consultas dejan de devolver todo: aprendes a pedir solo lo que necesitas.

## 🎯 Objetivo

Filtrar filas con precisión y controlar el orden y la cantidad de resultados.

## 📖 Conceptos a aprender

- `WHERE` con operadores: `=`, `<>`, `>`, `<`, `>=`, `<=`.
- Operadores lógicos: `AND`, `OR`, `NOT` (y precedencia con paréntesis).
- `BETWEEN` (rangos) e `IN` (listas).
- `LIKE` y comodines `%` y `_` (búsqueda por patrones).
- Manejo de `NULL` con `IS NULL` / `IS NOT NULL`.
- `ORDER BY` ascendente/descendente y por varias columnas.
- Límite de resultados: `LIMIT` (MySQL/SQLite/PostgreSQL) y `TOP` (SQL Server).
- `OFFSET` para paginación.

## ✅ Tareas

- [ ] Tarea 1: `01_filtros_basicos.sql` — 3 consultas con `WHERE`, `AND`, `OR`.
- [ ] Tarea 2: `02_between_in.sql` — consultas con `BETWEEN` y `IN`.
- [ ] Tarea 3: `03_like.sql` — buscar clientes cuyo nombre empiece por "A" y
      emails con dominio específico usando `%`.
- [ ] Tarea 4: `04_null.sql` — consultar registros con `NULL` y sin `NULL` en una columna.
- [ ] Tarea 5: `05_order_limit.sql` — ordenar por una columna descendente y
      limitar a los 5 primeros resultados.

## 📦 Entregables

- `01_filtros_basicos.sql`
- `02_between_in.sql`
- `03_like.sql`
- `04_null.sql`
- `05_order_limit.sql`

> ⚠️ Recuerda: el filtro ocurre en `WHERE` (antes de `SELECT`), por lo que
> **no puedes usar alias de `SELECT` dentro de `WHERE`**. Compruébalo tú mismo.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — WHERE Clause](https://www.w3schools.com/sql/sql_where.asp) — filtros con operadores.
- 📘 [W3Schools — LIKE Operator](https://www.w3schools.com/sql/sql_like.asp) — búsquedas con patrones.
- 📘 [W3Schools — ORDER BY](https://www.w3schools.com/sql/sql_orderby.asp) — ordenar resultados.
- 🖥️ [SQLBolt](https://sqlbolt.com/) — lecciones de constraints, filtros y orden.

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

