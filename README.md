<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/744/744465.png" />

# 🚗 Car Rental Management System MVC

### Plataforma web de renta de vehículos desarrollada con PHP MVC 🚀

<p align="center">
  <b>Car Rental Management System MVC</b> es una plataforma web diseñada para automatizar la administración de renta de automóviles, reservas, clientes y operaciones administrativas utilizando arquitectura MVC en PHP.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CarRental-MVCSystem-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-MVCFramework-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-WebApp-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Car Rental Management System MVC** es un sistema web orientado a la gestión inteligente de renta de vehículos, desarrollado bajo el patrón de arquitectura MVC (Model - View - Controller) para garantizar escalabilidad, mantenimiento y organización del código.

La plataforma permite administrar automóviles, clientes, reservas y pagos desde un panel administrativo moderno y centralizado.

El sistema fue diseñado para:

- 🚗 Gestionar vehículos
- 👥 Administrar clientes
- 📅 Controlar reservas
- 💳 Gestionar pagos
- 📋 Supervisar contratos
- 📊 Administrar operaciones
- 🔐 Gestionar accesos
- 🌐 Automatizar alquileres

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Registro de automóviles
- 📍 Gestión de disponibilidad
- 🖼️ Subida de imágenes
- 💰 Configuración de tarifas
- 📋 Información detallada

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- ⚡ Administración centralizada
- 📊 Historial de reservas

---

## 📅 Sistema de reservas

- 📆 Reservas en línea
- 📋 Gestión de contratos
- 💳 Administración de pagos
- ⚡ Confirmaciones rápidas
- 📄 Historial de alquileres

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🚗 Gestión de flota
- 👥 Administración de usuarios
- 📅 Supervisión de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🚗 Vehicle Module

Este módulo administra todos los vehículos registrados dentro del sistema.

### Funcionalidades:

- ➕ Registro de automóviles
- 📍 Gestión de disponibilidad
- 💰 Configuración de precios
- 🖼️ Administración de imágenes
- 📋 Información detallada

---

## 👤 Customer Module

Este módulo es utilizado por los clientes de la plataforma.

### Funcionalidades:

- 🔍 Buscar automóviles
- 📋 Consultar detalles
- 📅 Realizar reservas
- 💳 Gestionar pagos
- 📄 Historial de alquileres

---

## 📅 Reservation Module

Este módulo administra las reservas de vehículos.

### Funcionalidades:

- 📆 Reservas en tiempo real
- 📋 Gestión de contratos
- ⚡ Confirmaciones automáticas
- 💳 Seguimiento de pagos
- 📊 Historial de operaciones

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🚗 Supervisión de vehículos
- 📊 Dashboard administrativo
- 📅 Administración de reservas
- 🔐 Gestión general

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript
- AJAX

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- Arquitectura MVC
- Programación orientada a objetos
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión vehicular

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
PlataformaWebRentaVehiculos/
│
├── app/
│   ├── controllers/          # Controladores MVC
│   ├── models/               # Modelos de datos
│   ├── views/                # Vistas del sistema
│   └── core/                 # Núcleo del framework
│
├── public/                   # Archivos públicos
├── assets/                   # Recursos frontend
├── uploads/                  # Imágenes de vehículos
├── database/                 # Scripts SQL
├── config/                   # Configuración general
├── index.php                 # Entrada principal
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- XAMPP / WAMP
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaWebRentaVehiculos.git
```

---

## 2️⃣ Mover archivos

Copiar proyecto hacia:

```bash
xampp/htdocs/PlataformaWebRentaVehiculos/
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
car_rental_mvc
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/car_rental_mvc.sql
```

---

## 5️⃣ Configurar conexión

Editar:

```bash
config/database.php
```

Agregar:

```php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'car_rental_mvc');
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/PlataformaWebRentaVehiculos/
```

---

# 📊 Funcionalidades principales

## 🚗 Gestión vehicular

- Administración de automóviles
- Gestión de disponibilidad
- Configuración de tarifas
- Control de reservas

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Roles administrativos
- Historial de operaciones

---

## 📅 Gestión de reservas

- Reservas en línea
- Contratos automáticos
- Gestión de pagos
- Confirmaciones rápidas

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🚗 Página principal
![Home](https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1200&auto=format&fit=crop)

### 🔐 Inicio de sesión
![Login](https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop)

### 🚘 Catálogo de vehículos
![Cars](https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1200&auto=format&fit=crop)

### 📋 Detalles del automóvil
![Details](https://images.unsplash.com/photo-1549924231-f129b911e442?q=80&w=1200&auto=format&fit=crop)

### 📅 Gestión de reservas
![Reservation](https://images.unsplash.com/photo-1550355291-bbee04a92027?q=80&w=1200&auto=format&fit=crop)

### 👥 Administración de clientes
![Users](https://images.unsplash.com/photo-1521737604893-d14cc237f11d?q=80&w=1200&auto=format&fit=crop)

### 📊 Dashboard administrativo
![Admin](https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=1200&auto=format&fit=crop)

### ⚙️ Configuración del sistema
![Settings](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1200&auto=format&fit=crop)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web MVC
- Gestión vehicular
- Bases de datos relacionales
- CRUD administrativos
- Arquitectura MVC
- Sistemas de autenticación
- Automatización de reservas

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Integración de pagos
- 🤖 Recomendaciones inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real
- 📍 Geolocalización GPS

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas vehiculares, sistemas administrativos y arquitectura MVC 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje y desarrollo de sistemas de renta de vehículos utilizando arquitectura MVC con PHP.

---

<div align="center">

### 🚗 Car Rental Management System MVC — administración inteligente de renta vehicular 🚀

</div>
