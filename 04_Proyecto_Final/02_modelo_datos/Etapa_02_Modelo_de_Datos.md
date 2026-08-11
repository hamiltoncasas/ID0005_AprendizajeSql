# Proyecto Final — 02 Modelo de datos

> El corazón del proyecto: el diseño de la base de datos.

## 🎯 Objetivo

Diseñar el esquema completo del proyecto (diagrama + scripts de creación).

## 📖 Qué hacer aquí

1. Dibujar el **diagrama entidad-relación** con todas las tablas y relaciones.
2. Normalizar el esquema (mínimo 3FN).
3. Escribir el script `CREATE TABLE` con:
   - Claves primarias y foráneas.
   - Tipos de datos adecuados.
   - `NOT NULL`, `UNIQUE`, `CHECK` y valores por defecto.
4. Crear los **índices** sobre columnas de `WHERE`/`JOIN`.
5. (Opcional) vistas y roles desde el diseño.

## ✅ Tareas

- [ ] `diagrama_er.png` (o `.drawio`) — diagrama completo del modelo.
- [ ] `01_create_tables.sql` — script de creación de todas las tablas
      (listo para ejecutar de una sola vez).
- [ ] `02_indices.sql` — índices creados y comentados (por qué cada uno).
- [ ] `03_vistas.sql` — 2 o 3 vistas de negocio útiles
      (ej: resumen de ventas por mes, clientes morosos).
- [ ] `04_roles.sql` — roles y permisos básicos (lectura vs. escritura).

## 📦 Entregables

- `diagrama_er.png` / `diagrama_er.drawio`
- `01_create_tables.sql` … `04_roles.sql`

> ✅ **Prueba de calidad:** tu script debe ejecutarse **sin errores** en un motor
> limpio. Ejecútalo de inicio a fin para verificarlo antes de continuar.

---

## 🔗 Recursos y videos de apoyo

- 📘 [Wikipedia — Database Normalization](https://en.wikipedia.org/wiki/Database_normalization) — normalizar el esquema.
- 📘 [W3Schools — CREATE TABLE](https://www.w3schools.com/sql/sql_create_table.asp) — sintaxis de tablas.
- 📘 [W3Schools — FOREIGN KEY Constraint](https://www.w3schools.com/sql/sql_foreignkey.asp) — relaciones entre tablas.

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

