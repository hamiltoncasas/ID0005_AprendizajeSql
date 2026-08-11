# 🔴 Nivel 3 — Experto

> **Duración estimada:** 4 a 6 semanas.

En este nivel dejas de "escribir consultas" y empiezas a **diseñar, optimizar y
administrar** bases de datos. Es el nivel de quienes resuelven problemas de
rendimiento y diseñan esquemas para miles de usuarios.

---

## 🎯 Objetivos del nivel

Al terminar este nivel serás capaz de:

- [ ] Leer e interpretar un **plan de ejecución** (`EXPLAIN`) y optimizar consultas lentas.
- [ ] Diseñar esquemas en **3FN / BCNF** y decidir cuándo desnormalizar.
- [ ] Administrar usuarios, roles, permisos y **backups** de una base de datos.
- [ ] Usar SQL analítico avanzado: `PIVOT`, `ROLLUP`, `CUBE`, ranking y series de tiempo.
- [ ] Conocer particionado de tablas, índices avanzados y buenas prácticas de producción.

---

## 📚 Módulos de este nivel

| Carpeta | Tema | Estado |
|---|---|---|
| `01_optimizacion/` | `EXPLAIN`, planes de ejecución, refactor de consultas | ⬜ |
| `02_modelado_avanzado/` | Normalización, desnormalización, particionado | ⬜ |
| `03_administracion/` | Usuarios, permisos, backups y mantenimiento | ⬜ |
| `04_sql_analitico/` | `PIVOT`, `ROLLUP`, `CUBE`, series temporales | ⬜ |
| `05_ejercicios/` | Ejercicios integradores del nivel | ⬜ |

---

## 📝 Cómo trabajar

1. Lee la guía de cada módulo en orden (archivos `Unidad_*.md`).
2. Para `01_optimizacion/` necesitas una base "grande": genera datos con un script
   (puedes usar los generadores de `../scripts/`).
3. Para `03_administracion/` usa SQL Server Express o PostgreSQL (instalación local).
4. Documenta cada optimización: **consulta antes → problema detectado → solución → tiempo medido**.
5. Guarda tus archivos `.sql` comentados en el repo.

---

## 🏁 Criterios para pasar al Proyecto Final

- [ ] Resolviste todos los ejercicios de `05_ejercicios/`.
- [ ] Optimizaste al menos 3 consultas y guardaste el antes/después documentado.
- [ ] Implementaste roles y permisos en una base de datos real.
- [ ] Tus archivos `.sql` están comentados y guardados en el repo.
- [ ] Hiciste `git commit` del nivel completo.

> 💡 **Tip:** a este nivel conviene tener una base de datos propia instalada
> (SQL Server Express es gratis y compatible con Windows).

---

## 🔗 Recursos y videos de apoyo

- 📘 [PostgreSQL Docs — Using EXPLAIN](https://www.postgresql.org/docs/current/using-explain.html) — lectura de planes de ejecución.
- 📘 [Microsoft Learn — Execution Plans](https://learn.microsoft.com/en-us/sql/relational-databases/performance/execution-plans) — planes de ejecución en SQL Server.
- 📘 [Wikipedia — Database Normalization](https://en.wikipedia.org/wiki/Database_normalization) — normalización 1FN a 6FN.
- 🏋️ [PostgreSQL Exercises](https://pgexercises.com/) — retos avanzados para practicar.

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

