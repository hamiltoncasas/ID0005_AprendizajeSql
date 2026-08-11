# Módulo 01 — Funciones de ventana (window functions)

> La herramienta más potente de SQL analítico: cálculos sobre "ventanas" de filas
> sin perder el detalle de cada fila.

## 🎯 Objetivo

Usar funciones de ventana para rankings, acumulados y comparaciones sin agrupar el resultado.

## 📖 Conceptos a aprender

- Diferencia entre `GROUP BY` (pierde detalle) y funciones de ventana (conservan filas).
- Sintaxis: `funcion() OVER (PARTITION BY ... ORDER BY ...)`.
- Ranking: `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()` (y sus diferencias).
- Desplazamiento: `LAG()`, `LEAD()` (fila anterior / siguiente).
- Agregadas como ventana: `SUM() OVER (...)`, `AVG() OVER (...)`, `COUNT() OVER (...)`.
- `FIRST_VALUE()`, `LAST_VALUE()`.
- Marco de ventana: `ROWS BETWEEN ... AND ...` (acumulados).

## ✅ Tareas

- [ ] Tarea 1: `01_row_number.sql` — numerar los pedidos de cada cliente
      por fecha (el 1 = más reciente).
- [ ] Tarea 2: `02_rank_dense.sql` — rankear clientes por total gastado con
      `RANK()` y `DENSE_RANK()` y explicar la diferencia en comentario.
- [ ] Tarea 3: `03_lag_lead.sql` — comparar la venta de cada mes con el mes anterior
      usando `LAG()`.
- [ ] Tarea 4: `04_sum_over.sql` — venta acumulada por día dentro de cada mes
      (`SUM(venta) OVER (PARTITION BY mes ORDER BY dia)`).
- [ ] Tarea 5: `05_top_por_grupo.sql` — reto clásico: los 2 productos más vendidos
      de cada categoría (subconsulta + `ROW_NUMBER`, sin CTE todavía).

## 📦 Entregables

- `01_row_number.sql` … `05_top_por_grupo.sql`

> 🎯 **Objetivo estrella del nivel:** el ejercicio 5 ("top N por grupo") es el más
> preguntado en entrevistas. Domínalo hasta poder explicarlo en voz alta.

---

## 🔗 Recursos y videos de apoyo

- 📘 [PostgreSQL Docs — Window Functions](https://www.postgresql.org/docs/current/tutorial-window.html) — documentación oficial con ejemplos.
- 📘 [Microsoft Learn — OVER Clause (T-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/queries/select-over-clause-transact-sql?view=sql-server-ver16) — cláusula OVER en SQL Server.
- 🏋️ [PostgreSQL Exercises](https://pgexercises.com/) — sección de window functions.

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

