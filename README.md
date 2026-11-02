# 🍽️ Restaurante Poloché

Sistema de gestión de ventas e inventario para el Restaurante Poloche.

## 📌 Descripción
Este proyecto es un backend completo que permite administrar usuarios, categorías, productos y registrar ventas con detalle.

## 🛠️ Tecnologías utilizadas
- **Node.js** — Entorno de ejecución
- **Express** — Framework web
- **MySQL** — Base de datos
- **JWT** — Autenticación segura

## ✅ Funcionalidades
- 👤 Registro e inicio de sesión con token JWT
- 📂 Gestión de categorías (CRUD completo)
- 🛒 Gestión de productos con relación a categorías
- 🧾 Registro de ventas con múltiples productos y control de stock

## 📋 Endpoints principales

### Autenticación
| Método | Ruta | Descripción |
|--------|------|-------------|
| POST | `/api/auth/registro` | Registrar usuario |
| POST | `/api/auth/login` | Iniciar sesión |
| GET | `/api/auth/perfil` | Ver perfil de usuario |

### Categorías
| Método | Ruta | Descripción |
|--------|------|-------------|
| GET | `/api/categorias` | Listar todas |
| POST | `/api/categorias` | Crear categoría |
| GET | `/api/categorias/:id` | Ver una categoría |
| PUT | `/api/categorias/:id` | Editar categoría |
| DELETE | `/api/categorias/:id` | Eliminar categoría |

### Productos
| Método | Ruta | Descripción |
|--------|------|-------------|
| GET | `/api/productos` | Listar todos |
| POST | `/api/productos` | Crear producto |
| GET | `/api/productos/:id` | Ver un producto |
| PUT | `/api/productos/:id` | Editar producto |
| DELETE | `/api/productos/:id` | Eliminar producto |

### Ventas
| Método | Ruta | Descripción |
|--------|------|-------------|
| POST | `/api/ventas` | Registrar venta completa |
| GET | `/api/ventas` | Ver todas las ventas |
| GET | `/api/ventas/mis-ventas` | Ver mis ventas |
| GET | `/api/ventas/:id` | Ver detalle de venta |

## 👤 Autor
Juber Alexis Amador

## 📅 Fecha
Noviembre 2026
