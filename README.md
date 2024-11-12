# 🛠️ **Testing Project**

Este es un proyecto de prueba que incluye un sistema de autenticación con Google Login y una base de datos en SQLite. El proyecto está diseñado para manejar usuarios y sus datos de manera sencilla.

## 🚀 **Características**

- **Autenticación con Google Login**: Los usuarios pueden iniciar sesión utilizando su cuenta de Google.
- **Gestión de usuarios**: La aplicación permite la gestión de usuarios almacenados en una base de datos SQLite.
- **Base de datos SQLite**: Los datos de los usuarios se almacenan de manera local utilizando SQLite.

## 📦 **Estructura del proyecto**

La estructura básica del proyecto es la siguiente:
/googlelogin # Funcionalidad para login con Google
/users # Gestión de usuarios
/db.sqlite3 # Base de datos SQLite
/manage.py # Script para ejecutar el proyecto

## 🛠️ **Tecnologías utilizadas**

- **Django**: Framework de desarrollo web.
- **SQLite**: Sistema de gestión de bases de datos.
- **Google Login**: Autenticación de usuarios con cuentas de Google.

## 📥 **Instalación**

Sigue estos pasos para instalar y configurar el proyecto en tu máquina local:

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/4d0lf00/Testing.git

2. Configura las credenciales de Google Login: Asegúrate de tener las credenciales de la API de Google configuradas en el proyecto y actualiza los archivos correspondientes.

3. Inicia el servidor de desarrollo:
    ```bash
    python manage.py runserver

🌐 Uso
Accede a la aplicación en tu navegador en la dirección: http://127.0.0.1:8000/

**Autenticación de Google**
Los usuarios pueden iniciar sesión utilizando su cuenta de Google a través del sistema de autenticación integrado.

📑 Base de datos
La base de datos utilizada es SQLite, y todos los datos de los usuarios se almacenan en el archivo db.sqlite3.

📝 Notas
Si necesitas modificar la base de datos o agregar nuevos usuarios, puedes hacerlo a través del panel de administración de Django o directamente 
editando el archivo db.sqlite3.

🛠️ Contribuciones
Si deseas contribuir a este proyecto, por favor crea un pull request y asegúrate de que el código esté bien documentado y probado.

¡Gracias por usar el proyecto! 🙌
