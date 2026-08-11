# 📊 data/ — Datos de ejemplo

> Datos compartidos para practicar las consultas de todos los niveles.

## Contenido

- `ejemplos/` — datasets de ejemplo en formato CSV y scripts SQL
  para crear tablas de práctica (clientes, productos, pedidos…).

## Cómo usar

1. Carga las tablas de ejemplo en tu motor de base de datos
   (hay scripts de creación en `../scripts/`).
2. Úsalo para resolver los ejercicios de los niveles 0 al 3.
3. Cuando llegues al Nivel 2, genera tu propia base "grande"
   con el script de generación de datos de `../scripts/`.

## Reglas

- No subas datos personales ni confidenciales (solo datos ficticios).
- Si agregas un dataset, incluye una guía `.md` en su carpeta explicando
  las tablas y columnas.

## Ejemplo de creación de tablas

```sql
-- Ejemplo de tabla de clientes (SQLite / compatible con muchos motores)
CREATE TABLE Clientes (
    id_cliente   INTEGER PRIMARY KEY,
    nombre       TEXT NOT NULL,
    email        TEXT,
    ciudad       TEXT,
    fecha_alta   DATE
);
```

---

## 🔗 Recursos y videos de apoyo

- 📘 [SQLite — Documentación](https://sqlite.org/docs.html) — crear y consultar bases de práctica.
- 📘 [W3Schools — CREATE TABLE](https://www.w3schools.com/sql/sql_create_table.asp) — definir tablas de ejemplo.
- 🎮 [SQLZoo](https://sqlzoo.net/) — datasets de práctica adicionales.

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

