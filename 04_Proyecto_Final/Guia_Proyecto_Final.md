# 🏆 Proyecto Final — Integración de todo lo aprendido

> **Duración estimada:** 2 a 3 semanas.

Este es el **proyecto integrador**: diseñarás y construirás una base de datos completa
para un caso real (por ejemplo, un sistema de ventas o una biblioteca). Aquí demuestras
**todo lo aprendido** en los niveles 0 a 3 en un solo entregable.

---

## 🎯 Objetivo del proyecto

Construir una base de datos funcional de principio a fin:

1. Analizar un **caso real** y levantar sus requerimientos.
2. Diseñar el **modelo de datos** (diagrama ER + script `CREATE TABLE`).
3. Poblar la base con **datos de ejemplo** (`INSERT` o carga desde CSV).
4. Escribir un **set de consultas** que respondan preguntas de negocio
   (de básicas a avanzadas, incluyendo ventanas y CTEs).
5. Agregar **mejoras de rendimiento** (índices) y **seguridad** (roles/vistas).
6. Documentar todo en `04_documentacion/`.

---

## 📚 Módulos del proyecto

| Carpeta | Contenido | Estado |
|---|---|---|
| `01_requerimientos/` | Descripción del caso, alcance y preguntas de negocio | ⬜ |
| `02_modelo_datos/` | Diagrama ER y script de `CREATE TABLE` | ⬜ |
| `03_scripts/` | Scripts de carga de datos y consultas finales | ⬜ |
| `04_documentacion/` | Manual de uso, decisiones y lecciones aprendidas | ⬜ |

---

## 💡 Ideas de proyectos (elige uno o propon otro)

| Proyecto | Descripción breve |
|---|---|
| **Sistema de ventas** | Clientes, productos, pedidos y detalle de pedidos |
| **Biblioteca** | Libros, socios, préstamos y devoluciones |
| **Gimnasio** | Socios, planes, asistencias y pagos |
| **E-commerce** | Productos, categorías, carritos y órdenes |
| **Hospital / clínica** | Pacientes, médicos, citas y recetas |

---

## ✅ Criterios de aprobación

- [ ] Esquema normalizado (mínimo 3FN) con claves primarias y foráneas bien definidas.
- [ ] Datos de ejemplo cargados (más de 100 registros en la tabla principal).
- [ ] Al menos **10 consultas de negocio** documentadas, incluyendo:
  - JOINs de 3+ tablas.
  - Una agregación con `GROUP BY` y `HAVING`.
  - Una función de ventana (ranking o acumulado).
  - Una CTE (con o sin recursión).
- [ ] Índices creados sobre columnas usadas en `WHERE`/`JOIN`.
- [ ] Documentación completa en `04_documentacion/`.
- [ ] `git commit` del proyecto completo con mensajes claros.

---

## 🚀 Al terminar

Actualiza el `README.md` general (tabla de "Estado del progreso") marcando todo como
completado. ¡Ya eres una persona que puede trabajar con SQL a nivel profesional!

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — SQL Tutorial](https://www.w3schools.com/sql/) — repaso de toda la sintaxis.
- 🏋️ [PostgreSQL Exercises](https://pgexercises.com/) — práctica integral para el proyecto.
- 🖥️ [SQLBolt](https://sqlbolt.com/) — repaso rápido de los fundamentos.

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

