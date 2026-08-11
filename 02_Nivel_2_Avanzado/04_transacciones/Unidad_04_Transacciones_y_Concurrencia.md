# Módulo 04 — Transacciones y concurrencia

> Los datos de una empresa no pueden quedar a medias: por eso existen las transacciones.

## 🎯 Objetivo

Garantizar que un conjunto de operaciones se ejecute **completo o no se ejecute**,
y entender los niveles de aislamiento.

## 📖 Conceptos a aprender

- Propiedades **ACID** (Atomicidad, Consistencia, Aislamiento, Durabilidad).
- `BEGIN TRANSACTION`, `COMMIT`, `ROLLBACK`.
- `SAVEPOINT` (puntos de guardado).
- Niveles de aislamiento: `READ UNCOMMITTED`, `READ COMMITTED`,
  `REPEATABLE READ`, `SERIALIZABLE`.
- Problemas de concurrencia: **lecturas sucias**, **no repetibles** y **fantasmas**.
- Qué son los *locks* (bloqueos) y los *deadlocks* (interbloqueos).

## ✅ Tareas

- [ ] Tarea 1: `01_transaccion.sql` — una transacción que inserte un pedido y su detalle,
      con `COMMIT`, y verificar después que ambos quedaron.
- [ ] Tarea 2: `02_rollback.sql` — la misma transacción pero con `ROLLBACK` al final,
      y verificar que **nada** se guardó.
- [ ] Tarea 3: `03_savepoint.sql` — transacción con `SAVEPOINT`: hacer 3 operaciones,
      deshacer solo la segunda con `ROLLBACK TO SAVEPOINT`, y commitear el resto.
- [ ] Tarea 4: `04_niveles_aislamiento.sql` — documentar en comentarios cada nivel de
      aislamiento y qué problema resuelve (si tu motor lo permite, configura uno).
- [ ] Tarea 5: `05_deadlock.sql` — investigar y explicar en comentarios qué es un
      *deadlock* y cómo se previene (orden consistente de operaciones).

## 📦 Entregables

- `01_transaccion.sql` … `05_deadlock.sql`

> 💡 **Ejercicio práctico extra:** abre dos ventanas de consulta en tu motor,
> inicia una transacción en cada una y comprueba cuándo una bloquea a la otra.

---

## 🔗 Recursos y videos de apoyo

- 📘 [PostgreSQL Docs — Transactions](https://www.postgresql.org/docs/current/tutorial-transactions.html) — transacciones y SAVEPOINT.
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

