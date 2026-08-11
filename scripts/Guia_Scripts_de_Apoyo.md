# 🛠️ scripts/ — Scripts de apoyo

> Utilidades para facilitar el estudio: cargar datos, generar bases y validar ejercicios.

## Qué scripts se esperan aquí

- `crear_base_ejemplo.sql` — crea las tablas base (clientes, productos, pedidos).
- `cargar_datos.sql` — carga datos de ejemplo desde `../data/ejemplos/`.
- `generar_datos_grandes.sql` — genera una base "grande" (100k+ filas)
  para practicar rendimiento (Nivel 2 y 3).
- `resetear_db.sql` — borra y recrea la base de práctica desde cero
  (para empezar un módulo con datos limpios).

## Convenciones

- Cada script indica al inicio: **motor** (SQLite / SQL Server / PostgreSQL / MySQL)
  y cómo ejecutarlo.
- Un script **no debe borrar** datos de otros proyectos.
- Comenta cada sección para que sirva de estudio.

## Cómo ejecutar (ejemplo con SQLite)

```bash
# Crear la base de práctica
sqlite3 practica.db < scripts/crear_base_ejemplo.sql
```

---

## 🔗 Recursos y videos de apoyo

- 📘 [SQLite — Documentación](https://sqlite.org/docs.html) — comandos para crear y cargar bases.
- 📘 [SQLite — EXPLAIN](https://www.sqlite.org/lang_explain.html) — validar el rendimiento de los scripts.
- 📘 [W3Schools — SQL Tutorial](https://www.w3schools.com/sql/) — referencia de sintaxis.

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

