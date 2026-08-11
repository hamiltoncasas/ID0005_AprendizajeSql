# 🟠 Nivel 2 — Avanzado

> **Duración estimada:** 4 a 5 semanas.

Aquí empieza lo que separa a un usuario de SQL de un **desarrollador de datos**:
funciones de ventana, consultas recursivas, rendimiento, transacciones y código
reutilizable (procedimientos, funciones y triggers).

---

## 🎯 Objetivos del nivel

Al terminar este nivel serás capaz de:

- [ ] Calcular rankings, acumulados y comparaciones con **funciones de ventana**.
- [ ] Escribir **CTEs** y **CTEs recursivas** para consultas complejas.
- [ ] Crear **vistas** y entender **índices** para mejorar el rendimiento.
- [ ] Explicar **transacciones**, `COMMIT`, `ROLLBACK` y aislamiento de lecturas.
- [ ] Crear **stored procedures**, **funciones** y **triggers** básicos.

---

## 📚 Módulos de este nivel

| Carpeta | Tema | Estado |
|---|---|---|
| `01_funciones_ventana/` | `ROW_NUMBER`, `RANK`, `LAG`/`LEAD`, `SUM() OVER(...)` | ⬜ |
| `02_ctes/` | `WITH`, CTEs y consultas recursivas | ⬜ |
| `03_vistas_indices_rendimiento/` | Vistas, índices, `EXPLAIN` y buen rendimiento | ⬜ |
| `04_transacciones/` | `BEGIN`, `COMMIT`, `ROLLBACK`, aislamiento | ⬜ |
| `05_procedimientos_y_triggers/` | Procedimientos, funciones y triggers | ⬜ |
| `06_ejercicios/` | Ejercicios integradores del nivel | ⬜ |

---

## 📝 Cómo trabajar

1. Lee la guía de cada módulo en orden (archivos `Unidad_*.md`).
2. Las **funciones de ventana** son el módulo estrella: práctica obligatoria.
3. Usa el motor de base de datos que tengas (SQL Server, PostgreSQL, MySQL…)
   e indica cuál usas en cada archivo.
4. Guarda tus consultas como archivos `.sql` comentados.
5. Resuelve los retos de `06_ejercicios/` sin mirar soluciones.

---

## 🏁 Criterios para pasar al Nivel 3

- [ ] Resolviste todos los ejercicios de `06_ejercicios/`.
- [ ] Sabes resolver "el ranking por categoría" con funciones de ventana.
- [ ] Explicas qué es un índice, cuándo ayuda y cuándo estorba.
- [ ] Escribiste al menos un procedimiento y un trigger funcionando.
- [ ] Tus archivos `.sql` están comentados y guardados en el repo.
- [ ] Hiciste `git commit` del nivel completo.

> ⚠️ **Importante:** si usas SQLite, ten en cuenta que no soporta procedimientos
> ni triggers completos; para este nivel se recomienda SQL Server o PostgreSQL.

---

## 🔗 Recursos y videos de apoyo

- 🏋️ [PostgreSQL Exercises](https://pgexercises.com/) — secciones avanzadas (window functions, recursivos).
- 📘 [PostgreSQL Docs — Window Functions](https://www.postgresql.org/docs/current/tutorial-window.html) — documentación oficial.
- 📘 [PostgreSQL Docs — WITH (CTEs)](https://www.postgresql.org/docs/current/queries-with.html) — documentación oficial.
- 📘 [Microsoft Learn — Transactions (T-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/language-elements/transactions-transact-sql) — transacciones en SQL Server.

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

