# Módulo 06 — Ejercicios integradores del Nivel 2

> Retos que combinan ventanas, CTEs, vistas, transacciones y objetos programables.

## 🎯 Objetivo

Demostrar dominio del nivel avanzado resolviendo problemas complejos.

## ✅ Ejercicios (un archivo .sql por ejercicio)

- [ ] `ejercicio_01.sql` — Por cada categoría, listar sus productos con el ranking de
      precio dentro de la categoría (`RANK() OVER (PARTITION BY ...)`).
- [ ] `ejercicio_02.sql` — Variación mes a mes de las ventas totales usando
      CTE + `LAG()`.
- [ ] `ejercicio_03.sql` — CTE recursiva que genere la jerarquía de categorías
      (categoría padre → subcategorías) en un árbol.
- [ ] `ejercicio_04.sql` — Vista que muestre el top 3 de productos más vendidos
      por mes (vista + ventana + filtro de ranking).
- [ ] `ejercicio_05.sql` — Procedimiento que "procese un pedido": en una transacción
      inserte el pedido, descuente el stock y haga `COMMIT` (o `ROLLBACK` si falta stock).
- [ ] `ejercicio_06.sql` — Reto: con una tabla de 100k filas (generada con un script),
      encuentra la consulta más lenta que puedas y optimízala con índice.
      Documenta tiempos antes/después en comentarios.

## 📦 Entregables

- `ejercicio_01.sql` … `ejercicio_06.sql` (con comentarios explicando cada paso)

## 🏁 Autoevaluación

- [ ] Resuelvo "top N por grupo" con ventanas y CTE sin ayuda.
- [ ] Entiendo por qué una consulta con índice es más rápida (lo vi en `EXPLAIN`).
- [ ] Puedo explicar ACID y los 4 niveles de aislamiento.

> Cuando completes esto, marca el nivel en `../Guia_Nivel_2_Avanzado.md` y pasa al Nivel 3. 🚀

---

## 🔗 Recursos y videos de apoyo

- 🏋️ [PostgreSQL Exercises](https://pgexercises.com/) — retos de window functions y recursivos.
- 📘 [PostgreSQL Docs — Window Functions](https://www.postgresql.org/docs/current/tutorial-window.html) — referencia de ventanas.
- 📘 [PostgreSQL Docs — WITH (CTEs)](https://www.postgresql.org/docs/current/queries-with.html) — referencia de CTEs.

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

