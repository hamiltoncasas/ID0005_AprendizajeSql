# Módulo 03 — Administración de bases de datos

> El rol de quien cuida que los datos estén seguros, disponibles y accesibles.

## 🎯 Objetivo

Gestionar usuarios, permisos, backups y tareas de mantenimiento de una base de datos.

## 📖 Conceptos a aprender

**Seguridad y permisos:**
- Usuarios y roles: `CREATE USER`, `CREATE ROLE`, `GRANT`, `REVOKE`.
- Principio de **mínimo privilegio**.
- Esquemas como contenedores de objetos (SQL Server/PostgreSQL).
- Enmascaramiento de datos sensibles (concepto).

**Backups y recuperación:**
- Tipos de backup: completo, diferencial, de registros (*log*).
- Estrategia 3-2-1 (3 copias, 2 medios, 1 fuera del sitio).
- `RESTORE` y pruebas de restauración.

**Mantenimiento:**
- `VACUUM`/`ANALYZE` (PostgreSQL/SQLite) o mantenimiento de índices (SQL Server).
- Recompilación de estadísticas.
- Monitoreo de espacio y de consultas lentas.
- `LOCK` y gestión de conexiones activas.

## ✅ Tareas

- [ ] Tarea 1: `01_usuarios.sql` — crear 2 usuarios y asignarles permisos
      (`SELECT` a uno, lectura/escritura a otro).
- [ ] Tarea 2: `02_roles.sql` — crear un rol `analista` con permisos de lectura
      y asignarlo a un usuario. Verificar que un usuario sin permiso no pueda leer.
- [ ] Tarea 3: `03_revocar.sql` — revocar un permiso y demostrar el efecto
      con una consulta que falle.
- [ ] Tarea 4: `04_backup_restore.sql` — documentar y ejecutar un backup completo
      y una restauración en otra base (si tu motor lo permite).
- [ ] Tarea 5: `05_mantenimiento.sql` — ejecutar análisis de índices/estadísticas
      y limpieza de espacio en tu motor.
- [ ] Tarea 6: `06_plan_estrategia.md` — escribir una estrategia 3-2-1 de backup
      para una base "de producción" ficticia.

## 📦 Entregables

- `01_usuarios.sql` … `05_mantenimiento.sql`
- `06_plan_estrategia.md`

> ⚠️ **Seguridad primero:** usa nombres de usuarios de prueba y contraseñas simples
> SOLO en esta base local. Nunca subas contraseñas reales al repositorio.

---

## 🔗 Recursos y videos de apoyo

- 📘 [PostgreSQL Docs — Database Roles](https://www.postgresql.org/docs/current/user-manag.html) — usuarios, roles y permisos.
- 📘 [Microsoft Learn — Back up and Restore](https://learn.microsoft.com/en-us/sql/relational-databases/backup-restore/back-up-and-restore-of-sql-server-databases) — backups y restauración.

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

