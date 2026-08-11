# Módulo 05 — Procedimientos, funciones y triggers

> Código reutilizable y automatización dentro de la propia base de datos.

## 🎯 Objetivo

Crear objetos programables en el motor y automatizar acciones con triggers.

## 📖 Conceptos a aprender

**Procedimientos y funciones:**
- Diferencia entre procedimiento almacenado y función.
- `CREATE PROCEDURE` / `CREATE FUNCTION` (sintaxis según motor).
- Parámetros de entrada y salida.
- Llamar un procedimiento: `EXEC` (SQL Server) / `CALL` (MySQL/PostgreSQL).

**Triggers:**
- Qué es un trigger y cuándo se dispara (`BEFORE/AFTER INSERT/UPDATE/DELETE`).
- Tablas especiales: `INSERTED`/`DELETED` (SQL Server), `NEW`/`OLD` (MySQL/PostgreSQL).
- Casos de uso reales (auditoría, validaciones, actualización de totales).
- `DROP PROCEDURE/FUNCTION/TRIGGER`.

> ⚠️ **Nota:** SQLite soporta triggers pero **no** procedimientos ni funciones
> almacenadas. Para este módulo usa SQL Server Express o PostgreSQL.

## ✅ Tareas

- [ ] Tarea 1: `01_procedimiento.sql` — procedimiento que reciba un `id_cliente`
      y devuelva sus pedidos.
- [ ] Tarea 2: `02_procedimiento_insert.sql` — procedimiento que inserte un cliente
      validando que el email no exista.
- [ ] Tarea 3: `03_funcion.sql` — función escalar que calcule el IVA de un importe.
- [ ] Tarea 4: `04_trigger_auditoria.sql` — trigger que guarde en una tabla de
      auditoría cada `UPDATE` de la tabla clientes (usuario, fecha, datos).
- [ ] Tarea 5: `05_trigger_total.sql` — trigger que actualice el total de un pedido
      automáticamente al insertar un detalle.
- [ ] Tarea 6: `06_limpiar.sql` — script que elimine los objetos creados
      (`DROP` de procedimiento, función y triggers) para dejar todo limpio.

## 📦 Entregables

- `01_procedimiento.sql` … `06_limpiar.sql`

> 💡 **Importante:** respeta las convenciones de nombres de tu motor
> (ej: prefijos `usp_`, `fn_`, `trg_`) y comenta cada objeto.

---

## 🔗 Recursos y videos de apoyo

- 📘 [Microsoft Learn — CREATE PROCEDURE](https://learn.microsoft.com/en-us/sql/t-sql/statements/create-procedure-transact-sql) — procedimientos almacenados.
- 📘 [Microsoft Learn — CREATE TRIGGER](https://learn.microsoft.com/en-us/sql/t-sql/statements/create-trigger-transact-sql) — triggers en SQL Server.
- 📘 [PostgreSQL Docs — PL/pgSQL](https://www.postgresql.org/docs/current/plpgsql.html) — funciones y procedimientos en PostgreSQL.

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

