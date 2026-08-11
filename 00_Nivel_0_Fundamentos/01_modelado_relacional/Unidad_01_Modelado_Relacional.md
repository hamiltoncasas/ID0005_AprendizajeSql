# Módulo 01 — Modelado relacional

> Primer paso: entender qué es una base de datos antes de escribir la primera consulta.

## 🎯 Objetivo

Comprender los conceptos fundamentales de las bases de datos relacionales y ser capaz
de dibujar el modelo de una base sencilla.

## 📖 Conceptos a aprender

- Qué es una base de datos y un **DBMS** (SQLite, SQL Server, PostgreSQL, MySQL…).
- **Tablas, filas (registros) y columnas (campos)**.
- Tipos de datos comunes: `INTEGER`, `TEXT/VARCHAR`, `DECIMAL`, `DATE`, `BOOLEAN`.
- **Clave primaria (PK)** y **clave foránea (FK)**.
- Tipos de relaciones: **1 a 1, 1 a muchos, muchos a muchos**.
- Qué es un **diagrama entidad-relación (ER)**.

## ✅ Tareas

- [ ] Tarea 1: Investiga y escribe un resumen (5 a 10 líneas) de qué es un DBMS
      y nombra 3 ejemplos. Guárdalo como `resumen_dbms.md`.
- [ ] Tarea 2: Explica con tus palabras qué es una PK y una FK.
      Ejemplo en `01_pk_fk.sql` como comentarios.
- [ ] Tarea 3: Dibuja a mano (o con herramienta libre como draw.io) el diagrama ER de:
      **Clientes → Pedidos → Productos** (relación muchos a muchos por tabla puente).
      Guarda la imagen en esta carpeta como `diagrama_er.png`.
- [ ] Tarea 4: Escribe en `02_tipos_datos.sql` un comentario con la tabla
      `CREATE TABLE Clientes` básica que usarás en los siguientes módulos.

## 📦 Entregables

- `resumen_dbms.md`
- `01_pk_fk.sql`
- `02_tipos_datos.sql`
- `diagrama_er.png`

> 💡 Puedes apoyarte en https://sqlzoo.net y https://www.w3schools.com/sql/

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — FOREIGN KEY Constraint](https://www.w3schools.com/sql/sql_foreignkey.asp) — claves primarias y foráneas.
- 📘 [SQLite — Documentación](https://sqlite.org/docs.html) — guía de SQLite para empezar sin servidor.
- 🖥️ [SQLBolt — Introducción a bases de datos relacionales](https://sqlbolt.com/) — lección introductoria.

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

