# Módulo 01 — Funciones escalares y DML

> Aprende a transformar datos en `SELECT` y a modificar los datos de las tablas.

## 🎯 Objetivo

Dominar las funciones más usadas del motor y las tres operaciones básicas de escritura:
insertar, actualizar y borrar.

## 📖 Conceptos a aprender

**Funciones escalares (tema 1):**
- Texto: `UPPER`, `LOWER`, `LENGTH`, `SUBSTRING`/`SUBSTR`, `REPLACE`, `CONCAT`.
- Números: `ROUND`, `CEIL`/`CEILING`, `FLOOR`, `ABS`, `MOD`.
- Fechas: `CURRENT_DATE`, `DATEADD`/`DATE_ADD`, `DATEDIFF`, `EXTRACT`/`YEAR()`.
- `NULL`: `COALESCE`, `ISNULL`, `NULLIF`.

**DML (tema 2):**
- `INSERT INTO` (una fila y múltiples filas).
- `UPDATE` con `WHERE` (¡nunca sin `WHERE` salvo que sea intencional!).
- `DELETE` con `WHERE`.
- `TRUNCATE` vs `DELETE`.

## ✅ Tareas

- [ ] Tarea 1: `01_funciones_texto.sql` — 3 ejemplos de funciones de texto
      (mayúsculas, subcadena, reemplazo).
- [ ] Tarea 2: `02_funciones_numeros.sql` — 2 ejemplos de redondeo y 1 de valor absoluto.
- [ ] Tarea 3: `03_funciones_fechas.sql` — calcular la edad de una persona a partir
      de su fecha de nacimiento.
- [ ] Tarea 4: `04_null_functions.sql` — usar `COALESCE` para reemplazar `NULL` por un valor.
- [ ] Tarea 5: `05_insert.sql` — insertar 3 clientes nuevos (uno con `NULL` en email).
- [ ] Tarea 6: `06_update.sql` — actualizar el email de un cliente por su `id`.
- [ ] Tarea 7: `07_delete.sql` — borrar un registro por `id` (y verificar con `SELECT`).

## 📦 Entregables

- `01_funciones_texto.sql` … `07_delete.sql`

> ⚠️ Práctica de seguridad: antes de cada `UPDATE`/`DELETE`, ejecuta un `SELECT`
> con el mismo `WHERE` para ver qué filas se verán afectadas.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — INSERT INTO](https://www.w3schools.com/sql/sql_insert.asp) — insertar datos.
- 📘 [W3Schools — UPDATE Statement](https://www.w3schools.com/sql/sql_update.asp) — actualizar datos.
- 📘 [W3Schools — DELETE Statement](https://www.w3schools.com/sql/sql_delete.asp) — borrar datos.
- 📘 [W3Schools — NULL Values](https://www.w3schools.com/sql/sql_null_values.asp) — manejo de NULL.

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

