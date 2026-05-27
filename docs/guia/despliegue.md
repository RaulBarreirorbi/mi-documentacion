# 🚀 Despliegue de la Aplicación

Este documento describe los pasos necesarios para desplegar la aplicación en un entorno de producción (o staging).

## 📋 Requisitos previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en el servidor o máquina de despliegue:

- **Node.js** (versión 18 o superior)
- **npm** (versión 9 o superior) o **yarn**
- **Git**
- **Servidor web** (Nginx, Apache) o **Docker** (si se utiliza contenerización)
- **Base de datos** (MySQL, PostgreSQL, MongoDB, etc.) con las credenciales preparadas
- **Variables de entorno** necesarias (ver sección de configuración)

## ⚙️ Configuración del entorno

1. Clona el repositorio del proyecto:
   ```bash
   git clone https://github.com/usuario/proyecto.git
   cd proyecto