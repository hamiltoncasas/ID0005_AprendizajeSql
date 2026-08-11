# Módulo 04 — SQL analítico avanzado

> SQL como herramienta de business intelligence y data science.

## 🎯 Objetivo

Usar funciones de pivote, totales parciales y análisis de series de tiempo para
responder preguntas de negocio.

## 📖 Conceptos a aprender

- **Pivoteo**: `PIVOT` (SQL Server) / `CASE WHEN` + agregación (todos los motores).
- Subtotales: `ROLLUP` y `CUBE` (grupos y jerarquías de totales).
- `GROUPING SETS` (agrupaciones personalizadas).
- Series de tiempo: calendario, `generate_series` (PostgreSQL) o tabla de fechas.
- Ventanas temporales: comparaciones YoY (año contra año), MoM, YTD (año a la fecha).
- Frecuencias y distribución: `NTILE()` para crear percentiles/cuartiles.
- (Opcional) funciones geográficas y JSON básico según motor.

## ✅ Tareas

- [ ] Tarea 1: `01_pivot.sql` — tabla de ventas (filas = meses, columnas = años)
      usando `CASE WHEN` y luego (si tu motor lo permite) `PIVOT`.
- [ ] Tarea 2: `02_rollup_cube.sql` — ventas por (región, categoría) con `ROLLUP`
      y `CUBE`; identificar qué filas son subtotales.
- [ ] Tarea 3: `03_grouping_sets.sql` — mismo análisis pero con `GROUPING SETS`
      para controlar exactamente qué totales quieres.
- [ ] Tarea 4: `04_serie_tiempo.sql` — generar un calendario diario de los últimos
      30 días y rellenar días sin ventas con 0 (LEFT JOIN + `COALESCE`).
- [ ] Tarea 5: `05_yoy.sql` — comparar ventas del mes actual vs. el mismo mes del
      año anterior usando `LAG()` con 12 de desplazamiento.
- [ ] Tarea 6: `06_ntile.sql` — clasificar clientes en 4 cuartiles según su gasto
      y reportar el gasto total por cuartil.

## 📦 Entregables

- `01_pivot.sql` … `06_ntile.sql`

> 💡 **Nota:** `ROLLUP`, `CUBE` y `GROUPING SETS` no existen en SQLite.
> Usa PostgreSQL, SQL Server o MySQL 8+ para este módulo.

---

## 🔗 Recursos y videos de apoyo

- 📘 [PostgreSQL Docs — GROUPING SETS, CUBE y ROLLUP](https://www.postgresql.org/docs/current/queries-table-expressions.html) — subtotales y totales.
- 📘 [Microsoft Learn — OVER Clause (T-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/queries/select-over-clause-transact-sql?view=sql-server-ver16) — ventanas para análisis.
- 📘 [W3Schools — GROUP BY](https://www.w3schools.com/sql/sql_groupby.asp) — base de la agregación.

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

