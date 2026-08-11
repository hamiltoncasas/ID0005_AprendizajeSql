# Módulo 01 — Optimización de consultas

> El arte de hacer que una consulta pase de minutos a milisegundos.

## 🎯 Objetivo

Leer planes de ejecución, detectar cuellos de botella y optimizar consultas reales.

## 📖 Conceptos a aprender

- Lectura de planes de ejecución: `EXPLAIN`/`EXPLAIN QUERY PLAN`.
- Métodos de acceso: *scan* (recorrido completo) vs. *seek* (búsqueda por índice).
- Operadores comunes en el plan: `Nested Loop`, `Hash Join`, `Merge Join`, `Sort`.
- Estadísticas de coste y cómo interpretarlas.
- Anti-patrones de rendimiento:
  - `SELECT *` innecesario.
  - Funciones sobre columnas indexadas en `WHERE`.
  - `LIKE '%algo'` (no usa índice).
  - `OR` que rompe el índice (y cómo reescribirlo con `UNION ALL`).
  - Falta de `WHERE` sargable.
  - Joins sin índices en la columna de unión.
- Comparar tiempos reales (`SET STATISTICS TIME ON` en SQL Server, `\timing` en psql).

## ✅ Tareas

- [ ] Tarea 1: `01_plan_lectura.sql` — ejecutar `EXPLAIN` de una consulta simple
      y **explicar en comentario** cada parte del plan.
- [ ] Tarea 2: `02_scan_vs_seek.sql` — comparar el plan de una consulta sin índice
      (scan) y con índice (seek). Guardar ambos planes como comentarios.
- [ ] Tarea 3: `03_funcion_en_where.sql` — reescribir un `WHERE` con función sobre
      columna indexada para que use el índice (ej: `UPPER(columna) = ...` → arreglar).
- [ ] Tarea 4: `04_like_mejorado.sql` — comparar `LIKE '%x'` vs `LIKE 'x%'`
      y documentar la diferencia de rendimiento.
- [ ] Tarea 5: `05_optimizacion_documentada.md` — elegir 1 consulta lenta real,
      documentar: consulta original → plan → problema → solución → tiempo antes/después.

## 📦 Entregables

- `01_plan_lectura.sql` … `04_like_mejorado.sql`
- `05_optimizacion_documentada.md`

> 🎯 **Objetivo del módulo:** ser capaz de justificar **con datos** (plan + tiempos)
> por qué una versión de la consulta es mejor que otra.

---

## 🔗 Recursos y videos de apoyo

- 📘 [PostgreSQL Docs — Using EXPLAIN](https://www.postgresql.org/docs/current/using-explain.html) — cómo leer planes de ejecución.
- 📘 [Microsoft Learn — Execution Plans](https://learn.microsoft.com/en-us/sql/relational-databases/performance/execution-plans) — planes de ejecución en SQL Server.
- 📘 [SQLite — EXPLAIN](https://www.sqlite.org/lang_explain.html) — planes de consulta en SQLite.

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

