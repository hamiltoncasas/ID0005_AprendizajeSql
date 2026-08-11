# Módulo 02 — SELECT básico

> Tu primera consulta: leer datos de una tabla.

## 🎯 Objetivo

Escribir consultas `SELECT` básicas y entender el orden lógico en el que se ejecuta una consulta.

## 📖 Conceptos a aprender

- Estructura base: `SELECT columnas FROM tabla;`
- Seleccionar **todas** las columnas (`SELECT *`) vs. columnas específicas.
- **Alias de columna** (`AS`) para renombrar resultados.
- **Literales** y expresiones aritméticas dentro de `SELECT`.
- **DISTINCT** para eliminar duplicados.
- **Comentarios** en SQL (`--` y `/* */`).
- Orden lógico de ejecución: `FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY`.

## ✅ Tareas

- [ ] Tarea 1: Crea `01_select_todos.sql` que consulte todas las columnas de la tabla `Clientes`.
- [ ] Tarea 2: Crea `02_select_columnas.sql` que consulte solo `nombre` y `email` de `Clientes`.
- [ ] Tarea 3: Crea `03_alias.sql` que use alias y una columna calculada
      (ej: `precio * cantidad AS total`).
- [ ] Tarea 4: Crea `04_distinct.sql` que liste los valores únicos de una columna
      (ej: `SELECT DISTINCT ciudad FROM Clientes;`).
- [ ] Tarea 5: Escribe un comentario al inicio de cada archivo con la base de datos
      que usaste (SQLite, SQL Server, etc.) y la sintaxis que requiere.

## 📦 Entregables

- `01_select_todos.sql`
- `02_select_columnas.sql`
- `03_alias.sql`
- `04_distinct.sql`

> 💡 Si aún no tienes datos, crea una base temporal con SQLite y las tablas
> del módulo anterior. Los scripts de `../data/` te pueden ayudar.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — SELECT Statement](https://www.w3schools.com/sql/sql_select.asp) — sintaxis básica.
- 🎮 [SQLZoo](https://sqlzoo.net/) — ejercicios interactivos de SELECT básico.
- 🖥️ [SQLBolt](https://sqlbolt.com/) — lecciones de SELECT y consultas con constraints.

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

