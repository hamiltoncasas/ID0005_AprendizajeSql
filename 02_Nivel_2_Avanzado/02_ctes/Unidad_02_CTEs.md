# Módulo 02 — CTEs (Common Table Expressions)

> Consultas nombradas y reutilizables que hacen legible lo complejo.

## 🎯 Objetivo

Escribir consultas modulares con `WITH` y resolver problemas recursivos (árboles, jerarquías).

## 📖 Conceptos a aprender

- Sintaxis: `WITH nombre AS (consulta) SELECT ... FROM nombre;`.
- Múltiples CTEs separadas por coma (y CTE que usa otra CTE).
- CTEs **recursivas**: `WITH RECURSIVE` (PostgreSQL/MySQL/SQLite)
  o `WITH ... AS (... UNION ALL ...)` (SQL Server).
- Componentes de una recursión: parte base (ancla) + parte recursiva.
- Cuándo una CTE **no** aporta vs. cuándo hace la consulta mucho más clara.

## ✅ Tareas

- [ ] Tarea 1: `01_cte_basica.sql` — escribir una consulta con CTE para calcular
      el total gastado por cliente y luego filtrarla con `WHERE`.
- [ ] Tarea 2: `02_cte_multiples.sql` — 2 CTEs donde la segunda use la primera
      (ej: primero clientes activos, luego sus pedidos).
- [ ] Tarea 3: `03_recursiva_numeros.sql` — CTE recursiva que genere los números del 1 al 10.
- [ ] Tarea 4: `04_recursiva_arbol.sql` — CTE recursiva sobre una tabla de empleados
      (id, id_jefe) para listar la jerarquía completa.
- [ ] Tarea 5: `05_cte_top_por_grupo.sql` — rehacer el "top 2 por categoría" del
      módulo anterior, pero ahora con CTE + `ROW_NUMBER`.
- [ ] Tarea 6: `06_vs_subconsulta.sql` — misma consulta con subconsultas anidadas
      y con CTE; compara legibilidad en comentario.

## 📦 Entregables

- `01_cte_basica.sql` … `06_vs_subconsulta.sql`

> 💡 **Tip:** si tu consulta tiene más de 3 niveles de subconsultas anidadas,
> casi siempre una CTE la hará más clara.

---

## 🔗 Recursos y videos de apoyo

- 📘 [PostgreSQL Docs — WITH (CTEs)](https://www.postgresql.org/docs/current/queries-with.html) — CTEs y recursión.
- 📘 [Microsoft Learn — WITH common_table_expression](https://learn.microsoft.com/en-us/sql/t-sql/queries/with-common-table-expression-transact-sql) — CTEs en T-SQL.
- 🏋️ [PostgreSQL Exercises](https://pgexercises.com/) — ejercicios con consultas recursivas.

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

