# 🗄️ ID0005 — Aprendizaje de SQL (de cero a avanzado)

Repositorio diseñado para guardar el progreso de una persona que está aprendiendo
**SQL desde cero hasta nivel avanzado**. Aquí se almacenan las prácticas, ejercicios,
consultas, scripts y proyectos realizados durante el proceso de aprendizaje.

---

## 🎯 Objetivo del repositorio

- Guardar **todo el desarrollo** del aprendizaje de SQL en un solo lugar versionado.
- Mantener una **ruta de estudio clara y progresiva**: desde lo más básico hasta lo avanzado.
- Servir como **evidencia y portafolio** del avance (los entregables quedan registrados con `git`).
- Tener **ejercicios y proyectos reales** que demuestren cada habilidad adquirida.

---

## 🗺️ Estructura del repositorio

| Carpeta | Nivel | Qué se aprende |
|---|---|---|
| `00_Nivel_0_Fundamentos/` | Nivel 0 — Desde cero | Modelado relacional, `SELECT`, filtros y ordenamiento |
| `01_Nivel_1_Intermedio/` | Nivel 1 — Intermedio | Funciones, DML, agrupación, JOINs y subconsultas |
| `02_Nivel_2_Avanzado/` | Nivel 2 — Avanzado | Funciones de ventana, CTEs, índices, transacciones |
| `03_Nivel_3_Experto/` | Nivel 3 — Experto | Optimización, administración y SQL analítico |
| `04_Proyecto_Final/` | Proyecto integrador | Un proyecto completo que aplica todo lo aprendido |
| `data/` | Datos de ejemplo | Datos compartidos para practicar |
| `scripts/` | Scripts de apoyo | Utilidades para cargar datos y validar ejercicios |

---

## 🧭 Cómo usar este repositorio

1. **Empieza por el Nivel 0** (`00_Nivel_0_Fundamentos/`) y avanza en orden.
2. Lee la guía de cada carpeta (archivos `Guia_*.md` y `Unidad_*.md`): ahí está el **objetivo, los conceptos y las tareas**.
3. Resuelve cada tarea y guarda tu trabajo en la carpeta correspondiente.
4. Marca los checkboxes de las guías a medida que completes cada tarea.
5. **Haz commit después de cada práctica** para dejar registro del avance.
6. Cuando termines los niveles 0 al 3, desarrolla el `04_Proyecto_Final/`.

> 💡 **Tip:** intenta resolver primero sin ayuda. Cuando te quedes atascado, documenta
> en el propio código `-- Mi intento fallido:` y qué aprendiste. El proceso vale tanto
> como el resultado.

---

## 📂 Qué colocar en cada carpeta

Cada carpeta de práctica es el **lugar donde la persona guarda el trabajo que realizó**.
Puede colocar el resultado en cualquier formato:

- 🖼️ **Imágenes** (`.png`, `.jpg`): diagramas ER, capturas de pantalla de resultados.
- 📄 **Word** (`.docx`): resúmenes, informes o explicaciones de cada unidad.
- 📊 **Excel** (`.xlsx`): tablas de datos, cálculos o comparativas.
- 🗄️ **Archivos de base de datos** (`.db`, `.sqlite`): la base de datos trabajada en la unidad.
- 💾 **Consultas y scripts** (`.sql`): los ejercicios resueltos.

> Regla de nombres: un archivo por actividad con nombre descriptivo
> (ej: `diagrama_er_final.png`, `practica_joins.sql`, `resumen_unidad.docx`).

---

## 🧱 Reglas para quien estudia

- **Nunca borres** archivos de otras personas/carpetas sin avisar.
- Usa **un archivo por actividad** con nombre descriptivo (`.sql`, `.db`, imagen, Word o Excel).
- Comenta siempre tu código SQL con `--` explicando qué hace cada consulta.
- Los archivos de texto se guardan en formato UTF-8 para que `git` pueda versionarlos.
- Si usas una base de datos local (SQLite, SQL Server, PostgreSQL, MySQL…),
  indica cuál usaste en un comentario al inicio de cada archivo.

---

## ✅ Criterio de "nivel completado"

Un nivel se considera completado cuando:

- [ ] Todas las tareas de su guía (`Unidad_*.md`) están resueltas.
- [ ] Los archivos de trabajo (`.sql`, `.db`, imágenes, Word, Excel) están en el repo y tienen nombres descriptivos.
- [ ] Los checkboxes de la carpeta están marcados.
- [ ] Se hizo `git commit` con los avances.

---

## 🛠️ Herramientas sugeridas

| Herramienta | Uso |
|---|---|
| **SQLite** | La más sencilla para empezar (no requiere instalación de servidor) |
| **SQL Server / PostgreSQL** | Bases de datos profesionales para niveles 2 y 3 |
| **DBeaver / Azure Data Studio** | Editores visuales de consultas |
| **Git + GitHub** | Versionar y guardar el progreso |

---

## 📁 Estado del progreso

| Nivel | Estado |
|---|---|
| Nivel 0 — Fundamentos | ⬜ Pendiente |
| Nivel 1 — Intermedio | ⬜ Pendiente |
| Nivel 2 — Avanzado | ⬜ Pendiente |
| Nivel 3 — Experto | ⬜ Pendiente |
| Proyecto Final | ⬜ Pendiente |

_Actualizar este cuadro a medida que se avanza en cada nivel._

---

## 🔗 Recursos de apoyo (gratuitos, verificados)

**Páginas interactivas para practicar:**
- **SQLZoo**: https://sqlzoo.net — ejercicios interactivos en orden.
- **SQLBolt**: https://sqlbolt.com — curso interactivo desde cero.
- **PG Exercises** (PostgreSQL): https://pgexercises.com — nivel intermedio/avanzado.

**Referencias y documentación:**
- **W3Schools SQL**: https://www.w3schools.com/sql/ — referencia rápida de toda la sintaxis.
- **Documentación oficial** del motor que uses: [PostgreSQL](https://www.postgresql.org/docs/), [Microsoft Learn (SQL Server)](https://learn.microsoft.com/en-us/sql/), [SQLite](https://sqlite.org/docs.html).

**Videos (inglés):**
- **SQL Tutorial — Full Database Course for Beginners** (freeCodeCamp, 4h): https://www.youtube.com/watch?v=HXV3zeQKqGY
- **SQL Tutorial for Beginners** (Programming with Mosh, 1h): https://www.youtube.com/watch?v=7S_tz1z_5bA

> Cada guía de unidad incluye una sección **"🔗 Recursos y videos de apoyo"** con enlaces específicos del tema.
