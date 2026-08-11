# Módulo 04 — Subconsultas

> Consultas dentro de consultas: cuando necesitas un valor o un conjunto que aún no tienes.

## 🎯 Objetivo

Escribir subconsultas en las tres posiciones (`SELECT`, `FROM`, `WHERE`) y distinguir
cuándo conviene una subconsulta vs. un JOIN.

## 📖 Conceptos a aprender

- Subconsulta **escalar** (devuelve 1 valor) en `SELECT` y `WHERE`.
- Subconsulta **de columna** (devuelve una lista) con `IN` / `NOT IN`.
- Subconsulta **de tabla** (devuelve varias filas/columnas) en `FROM`.
- Subconsultas **correlacionadas** (referencian la consulta externa).
- Operadores `EXISTS` / `NOT EXISTS`.
- Comparación: subconsulta vs. `JOIN` (cuándo usar cada una).

## ✅ Tareas

- [ ] Tarea 1: `01_escalar.sql` — cliente cuyo pedido tiene el precio máximo
      (subconsulta en `WHERE`).
- [ ] Tarea 2: `02_in.sql` — productos que pertenecen a una lista de categorías
      mediante `IN` con subconsulta.
- [ ] Tarea 3: `03_from.sql` — usar una subconsulta en `FROM` y darle alias
      (ej: contar pedidos por cliente a partir de un subconjunto).
- [ ] Tarea 4: `04_correlacionada.sql` — por cada cliente, su último pedido
      (subconsulta correlacionada con `MAX(fecha)`).
- [ ] Tarea 5: `05_exists.sql` — clientes que tienen al menos un pedido con `EXISTS`.
- [ ] Tarea 6: `06_subconsulta_vs_join.sql` — resolver el mismo problema con subconsulta
      y con JOIN, y comparar en comentario cuál prefieres.

## 📦 Entregables

- `01_escalar.sql` … `06_subconsulta_vs_join.sql`

> 💡 **Tip:** si la subconsulta va en `WHERE` y no está correlacionada, muchas veces
> un `JOIN` es más legible. Si va en `SELECT`, verifica que devuelva exactamente 1 valor.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — EXISTS Operator](https://www.w3schools.com/sql/sql_exists.asp) — subconsultas con EXISTS.
- 📘 [W3Schools — IN Operator](https://www.w3schools.com/sql/sql_in.asp) — IN con subconsulta.
- 🖥️ [SQLBolt](https://sqlbolt.com/) — tema de subconsultas.

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

