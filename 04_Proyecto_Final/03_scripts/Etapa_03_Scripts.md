# Proyecto Final — 03 Scripts

> Los datos y las consultas que demuestran que el modelo funciona.

## 🎯 Objetivo

Poblar la base con datos realistas y escribir las consultas que responden
las preguntas de negocio definidas en `01_requerimientos/`.

## 📖 Qué hacer aquí

1. **Poblar la base:**
   - Opción A: script `INSERT` con datos manuales.
   - Opción B: cargar datos desde CSV (usa `../data/` del repo).
   - La tabla principal debe tener **100+ registros**.
2. **Escribir las consultas de negocio:**
   - Mínimo 10 consultas (una por cada pregunta de `02_preguntas_negocio.md`).
   - Deben incluir: JOINs de 3+ tablas, `GROUP BY` + `HAVING`,
     una función de ventana y una CTE (con o sin recursión).
3. (Opcional) procedimientos y triggers de apoyo.

## ✅ Tareas

- [ ] `01_carga_datos.sql` — script de carga de datos de ejemplo.
- [ ] `02_consultas_basicas.sql` — consultas 1 a 4 (básicas/intermedias).
- [ ] `03_consultas_avanzadas.sql` — consultas 5 a 8
      (agregaciones y JOINs complejos).
- [ ] `04_consultas_analiticas.sql` — consultas 9 y 10
      (ventanas y CTEs).
- [ ] `05_procedimientos.sql` — (opcional) 1 procedimiento útil para el negocio.
- [ ] `LEEME_SCRIPTS.md` — instrucciones de cómo ejecutar todo en orden.

## 📦 Entregables

- `01_carga_datos.sql` … `05_procedimientos.sql`
- `LEEME_SCRIPTS.md`

> 💡 Cada consulta debe llevar un comentario con la **pregunta de negocio**
> que responde y el resultado esperado.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — SQL Tutorial](https://www.w3schools.com/sql/) — referencia de consultas.
- 🎮 [SQLZoo](https://sqlzoo.net/) — práctica previa de cada consulta.
- 📘 [SQLite — Documentación](https://sqlite.org/docs.html) — si usas SQLite para el proyecto.

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

