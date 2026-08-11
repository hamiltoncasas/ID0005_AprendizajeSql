# Módulo 02 — Modelado avanzado de datos

> Diseñar bases de datos como se hace en producción: con criterio y previsión.

## 🎯 Objetivo

Diseñar esquemas normalizados, saber cuándo desnormalizar y aplicar técnicas de
escalado de datos.

## 📖 Conceptos a aprender

**Normalización:**
- Primera (1FN), segunda (2FN) y tercera forma normal (3FN).
- **BCNF** (Boyce-Codd) y cuándo aplica.
- Dependencias funcionales.

**Desnormalización:**
- Cuándo es **válido** desnormalizar (rendimiento de lectura vs. integridad).
- Columnas calculadas y tablas de resumen (reporting).

**Escalado y almacenamiento:**
- **Particionado** de tablas (rangos, listas, hash).
- **Sharding** (concepto).
- Tipos de almacenamiento: columnar vs. filas (para analytics).
- `TRUNCATE`, archivo de datos históricos (*data retention*).

## ✅ Tareas

- [ ] Tarea 1: `01_normalizacion.md` — partir de una tabla "planilla" mal diseñada,
      detectar sus problemas y normalizarla hasta 3FN (documentar paso a paso).
- [ ] Tarea 2: `02_bcnf.md` — ejemplo práctico de una tabla en 3FN pero no BCNF,
      y su solución.
- [ ] Tarea 3: `03_desnormalizar.md` — caso donde conviene desnormalizar:
      explicar la situación, el costo y el beneficio.
- [ ] Tarea 4: `04_particionado.sql` — crear una tabla particionada por rango
      de fechas (si tu motor lo soporta) y explicar en comentarios.
- [ ] Tarea 5: `05_esquema_produccion.sql` — diseñar el esquema completo de una
      base de ventas con: normalización, índices, claves, tipos adecuados
      y tabla de auditoría.

## 📦 Entregables

- `01_normalizacion.md`, `02_bcnf.md`, `03_desnormalizar.md`
- `04_particionado.sql`, `05_esquema_produccion.sql`

> 💡 **Consejo:** no existe "el esquema perfecto", existe "el esquema correcto para
> el problema". Justifica siempre tus decisiones en comentarios.

---

## 🔗 Recursos y videos de apoyo

- 📘 [Wikipedia — Database Normalization](https://en.wikipedia.org/wiki/Database_normalization) — 1FN, 2FN, 3FN y más.
- 📘 [Wikipedia — Boyce–Codd Normal Form (BCNF)](https://en.wikipedia.org/wiki/Boyce%E2%80%93Codd_normal_form) — BCNF explicado.
- 📘 [W3Schools — CREATE TABLE](https://www.w3schools.com/sql/sql_create_table.asp) — crear tablas con constraints.

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

