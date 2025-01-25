# BD-II
Proyecto Final
# Sistema de Gestión de Productos

Un sistema moderno de gestión de productos construido con Node.js, Express y MongoDB. Permite gestionar productos con imágenes, categorías y seguimiento de inventario en tiempo real.

![Node.js](https://img.shields.io/badge/Node.js-v14+-green.svg)
![Express](https://img.shields.io/badge/Express-v4.17+-blue.svg)
![MongoDB](https://img.shields.io/badge/MongoDB-v4.4+-green.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Características

- 📦 Gestión completa de productos (CRUD)
- 🖼️ Subida y gestión de imágenes de productos
- 📊 Control de inventario en tiempo real
- 🏷️ Categorización de productos
- 📝 Sistema de auditoría para seguimiento de cambios
- 💅 Interfaz moderna y responsiva

## 🚀 Tecnologías

- **Backend**: Node.js + Express.js
- **Base de Datos**: MongoDB + pgAdmin
- **Frontend**: EJS + Bootstrap 5
- **Gestión de Archivos**: Multer
- **Estilos**: CSS personalizado

## 📋 Requisitos Previos

- Node.js (v14 o superior)
- MongoDB (v4.4 o superior)
- npm o yarn

## 🛠️ Instalación

1. Clona el repositorio:
```

2. Instala las dependencias:
```bash
npm install
```

3. Configura las variables de entorno:
```bash
cp .env.example .env
# Edita .env con tus configuraciones
```

4. Inicia MongoDB:
```bash
mongod
```

5. Inicia la aplicación:
```bash
npm start
```

La aplicación estará disponible en `http://localhost:3001`

## 🗂️ Estructura del Proyecto

```
NODE-MGDB/
├── config/           # Configuración de la aplicación
├── controllers/      # Controladores
├── models/          # Modelos de datos
├── public/          # Archivos estáticos
│   ├── css/         # Estilos
│   ├── js/          # Scripts
│   └── uploads/     # Imágenes subidas
├── routes/          # Rutas
├── views/           # Plantillas EJS
└── app.js           # Punto de entrada
```

## 📱 Características Principales

### Gestión de Productos
- Crear, editar y eliminar productos
- Subir y gestionar imágenes de productos
- Control de stock y precios
- Categorización

### Sistema de Auditoría
- Registro de todas las operaciones
- Seguimiento de cambios
- Historial completo

### Interfaz de Usuario
- Diseño responsivo
- Temas claros y oscuros
- Formularios intuitivos
- Previsualización de imágenes

## 🔧 Configuración

### Variables de Entorno
```env
PORT=3001
MONGODB_URI=mongodb://localhost:27017/gestion_producto
```

### Base de Datos
La aplicación utiliza MongoDB. Asegúrate de tener MongoDB instalado y ejecutándose.

## 📖 API Endpoints

### Productos
- `GET /products` - Listar productos
- `POST /products/store` - Crear producto
- `GET /products/edit/:id` - Obtener producto para editar
- `POST /products/update/:id` - Actualizar producto
- `GET /products/delete/:id` - Eliminar producto

## 🤝 Contribuir

1. Fork el proyecto
2. Crea tu rama de características (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

## 👥 Autores

- **Jean Phillipe** - *Desarrollo Inicial* - (https://github.com/Pasquelinho)

## 🙏 Agradecimientos

- A la profesora por su guía y apoyo
- A la comunidad de Node.js y MongoDB
- A todos los contribuidores que ayudaron a mejorar este proyecto

---
⌨️ con ❤️ por [Jean Phillipe]https://github.com/Pasquelinho
