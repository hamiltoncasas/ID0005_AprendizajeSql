# Módulo 03 — Vistas, índices y rendimiento

> Aquí pasas de "que funcione" a "que funcione rápido".

## 🎯 Objetivo

Crear vistas reutilizables y entender cómo los índices aceleran (o frenan) las consultas.

## 📖 Conceptos a aprender

**Vistas:**
- Qué es una vista y para qué sirve (abstraer consultas, seguridad, simplicidad).
- `CREATE VIEW`, `ALTER VIEW`, `DROP VIEW`.
- Vistas actualizables vs. de solo lectura (según motor).

**Índices y rendimiento:**
- Qué es un índice (como el índice de un libro).
- `CREATE INDEX`, índices únicos, compuestos.
- Cuándo un índice **ayuda** (columnas de `WHERE`, `JOIN`, `ORDER BY`)
  y cuándo **estorba** (muchas escrituras, baja cardinalidad).
- Lectura de planes: `EXPLAIN` / `EXPLAIN QUERY PLAN` / `SET SHOWPLAN`.
- Detectar `SELECT *` innecesario y evitar funciones sobre columnas indexadas.

## ✅ Tareas

- [ ] Tarea 1: `01_vista_cliente_total.sql` — crear una vista con el total gastado
      por cliente y consultarla.
- [ ] Tarea 2: `02_indices.sql` — crear índices sobre columnas usadas en `WHERE`
      y `JOIN` de tus tablas (con comentarios de por qué).
- [ ] Tarea 3: `03_explain.sql` — ejecutar la misma consulta **antes y después**
      de crear el índice y guardar ambos `EXPLAIN` como comentarios.
- [ ] Tarea 4: `04_mejores_practicas.sql` — reescribir una consulta lenta
      aplicando 3 mejoras (evitar `SELECT *`, evitar función en `WHERE`, etc.).
- [ ] Tarea 5: `05_indice_unque.sql` — crear un índice único en una columna
      que deba ser única (ej: email de cliente).

## 📦 Entregables

- `01_vista_cliente_total.sql` … `05_indice_unque.sql`

> ⚠️ Los motores tienen sintaxis distinta para `EXPLAIN`:
> - SQLite: `EXPLAIN QUERY PLAN`
> - PostgreSQL/MySQL: `EXPLAIN`
> - SQL Server: `SET SHOWPLAN_ALL ON`
> Indica en cada archivo qué motor usaste.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — CREATE INDEX](https://www.w3schools.com/sql/sql_create_index.asp) — índices para acelerar consultas.
- 📘 [W3Schools — CREATE VIEW](https://www.w3schools.com/sql/sql_view.asp) — vistas reutilizables.
- 📘 [SQLite — EXPLAIN](https://www.sqlite.org/lang_explain.html) — cómo leer el plan de una consulta.

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

