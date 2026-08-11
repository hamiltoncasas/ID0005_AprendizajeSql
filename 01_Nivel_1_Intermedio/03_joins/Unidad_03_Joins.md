# Módulo 03 — JOINs (combinación de tablas)

> El módulo más importante del nivel: las tablas relacionadas se combinan con JOIN.

## 🎯 Objetivo

Combinar dos o más tablas correctamente y elegir el tipo de JOIN adecuado.

## 📖 Conceptos a aprender

- Concepto de clave foránea y por qué se combinan tablas.
- `INNER JOIN` (solo coincidencias).
- `LEFT JOIN` (todas las filas de la izquierda + coincidencias).
- `RIGHT JOIN` y `FULL OUTER JOIN` (soporte varía según motor).
- `CROSS JOIN` (producto cartesiano) y **cuándo evitarlo**.
- **Self-join** (unir una tabla consigo misma).
- Uso de **alias de tabla** (`FROM Clientes c JOIN Pedidos p ON ...`).
- La condición del JOIN va en `ON`; los filtros van en `WHERE`.

## ✅ Tareas

- [ ] Tarea 1: `01_inner_join.sql` — clientes con sus pedidos (solo quienes tienen pedidos).
- [ ] Tarea 2: `02_left_join.sql` — todos los clientes con sus pedidos
      (incluyendo quienes no tienen ninguno).
- [ ] Tarea 3: `03_join_tres_tablas.sql` — pedido + cliente + producto en una consulta.
- [ ] Tarea 4: `04_right_full.sql` — intenta `RIGHT JOIN` y `FULL JOIN`
      (si tu motor lo soporta) y documenta si falló y por qué.
- [ ] Tarea 5: `05_self_join.sql` — ejemplo de self-join
      (ej: empleados y su jefe en la misma tabla).
- [ ] Tarea 6: `06_cross_join.sql` — un `CROSS JOIN` con una tabla pequeña
      y explica en comentario qué produce.

## 📦 Entregables

- `01_inner_join.sql` … `06_cross_join.sql`

> ⚠️ **Regla de oro:** piensa "¿quiero TODAS las filas de la izquierda o solo las
> que coinciden?" → `LEFT JOIN` o `INNER JOIN`. Practica esta decisión en cada ejercicio.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — SQL JOIN](https://www.w3schools.com/sql/sql_join.asp) — tipos de JOIN con ejemplos.
- 🖥️ [SQLBolt](https://sqlbolt.com/) — lecciones de JOINs y OUTER JOINs.
- 🎮 [SQLZoo](https://sqlzoo.net/) — tutorial de JOIN.

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

