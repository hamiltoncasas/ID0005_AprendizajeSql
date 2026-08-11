# 📦 data/ejemplos — Datasets de práctica

> Guarda aquí los datasets ficticios que usarás para practicar.

## Qué poner en esta carpeta

- Archivos **CSV** con datos ficticios (ej: `clientes.csv`, `productos.csv`, `pedidos.csv`).
- Scripts **SQL** de creación de tablas de práctica.
- Una pequeña guía `.md` por dataset explicando su contenido.

## Dataset base sugerido (esquema de ventas)

| Tabla | Columnas clave |
|---|---|
| `Clientes` | id_cliente, nombre, email, ciudad, fecha_alta |
| `Productos` | id_producto, nombre, categoria, precio |
| `Pedidos` | id_pedido, id_cliente, fecha, total |
| `Detalle_Pedido` | id_detalle, id_pedido, id_producto, cantidad, precio_unitario |
| `Categorias` | id_categoria, nombre, id_categoria_padre (para recursividad) |

> ⚠️ **Importante:** todos los datos deben ser **ficticios**. Nunca subas
> datos reales de personas o empresas.

---

## 🔗 Recursos y videos de apoyo

- 📘 [W3Schools — SQL Tutorial](https://www.w3schools.com/sql/) — consultas para explorar los datasets.
- 🎮 [SQLZoo](https://sqlzoo.net/) — más tablas de práctica.
- 📘 [SQLite — Documentación](https://sqlite.org/docs.html) — cargar los CSV en una base local.

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

