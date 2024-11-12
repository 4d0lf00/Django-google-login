# 🚀 Testing Project - Django Google Authentication

Un proyecto de demostración que implementa autenticación con Google usando Django y django-allauth. Permite a los usuarios iniciar sesión de forma segura utilizando sus cuentas de Google.

## 📋 Tabla de Contenidos
- [Características](#características)
- [Requisitos Previos](#requisitos-previos)
- [Tecnologías](#tecnologías)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Contribución](#contribución)
- [Licencia](#licencia)

## ✨ Características

- **🔐 Autenticación con Google**: Integración segura con Google OAuth2
- **👥 Gestión de Usuarios**: Sistema completo de gestión de usuarios
- **📱 Diseño Responsivo**: Interfaz adaptable a diferentes dispositivos
- **🔄 Sesiones Persistentes**: Manejo seguro de sesiones de usuario
- **📊 Panel de Administración**: Interfaz de administración Django integrada
- **🛡️ Seguridad**: Implementación de mejores prácticas de seguridad

## 🔧 Requisitos Previos

- Python 3.12+
- pip (gestor de paquetes de Python)
- Cuenta de Google Cloud Platform con OAuth2 configurado
- Git

## 🛠️ Tecnologías

- **Framework**: Django 5.1.3
- **Autenticación**: django-allauth 65.2.0
- **Base de Datos**: SQLite3
- **Frontend**: HTML, CSS, JavaScript
- **Seguridad**: PyJWT, cryptography

## ⚙️ Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/4d0lf00/Testing.git
cd Testing
```

2. **Crear y activar entorno virtual**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/MacOS
python3 -m venv venv
source venv/bin/activate
```

3. **Instalar dependencias**
```bash
pip install -r requirements.txt
```

4. **Aplicar migraciones**
```bash
python manage.py migrate
```

## 🔩 Configuración

1. **Configurar variables de entorno**
   - Crea un archivo `.env` en la raíz del proyecto
   - Añade las siguientes variables:
```env
SECRET_KEY=tu_clave_secreta
DEBUG=True
GOOGLE_CLIENT_ID=tu_client_id
GOOGLE_CLIENT_SECRET=tu_client_secret
```

2. **Configurar Google OAuth2**
   - Ve a [Google Cloud Console](https://console.cloud.google.com)
   - Crea un nuevo proyecto
   - Habilita la API de Google+ 
   - Configura las URLs de redirección OAuth2:
     - `http://localhost:8000/accounts/google/login/callback/`
     - `http://localhost:8000/accounts/google/login/callback/`

## 📦 Estructura del Proyecto
```
Testing/
├── googlelogin/             # Configuración principal del proyecto
│   ├── settings.py         # Configuraciones de Django
│   ├── urls.py            # URLs principales
│   └── wsgi.py            # Configuración WSGI
├── users/                  # Aplicación de usuarios
├── templates/             # Plantillas HTML
├── static/                # Archivos estáticos
├── manage.py              # Script de gestión de Django
├── requirements.txt       # Dependencias del proyecto
└── README.md             # Este archivo
```

## 🚀 Uso

1. **Iniciar el servidor de desarrollo**
```bash
python manage.py runserver
```

2. **Acceder a la aplicación**
   - Abre tu navegador y visita: `http://localhost:8000`
   - Haz clic en "Iniciar sesión con Google"
   - Selecciona tu cuenta de Google

3. **Panel de administración**
   - Crea un superusuario: `python manage.py createsuperuser`
   - Accede a: `http://localhost:8000/admin`

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

1. Fork el repositorio
2. Crea una nueva rama (`git checkout -b feature/mejora`)
3. Realiza tus cambios
4. Commit tus cambios (`git commit -am 'Añade nueva característica'`)
5. Push a la rama (`git push origin feature/mejora`)
6. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

## 📧 Contacto

Adolfo - [email](adolfoignacio.vg@gmail.com)

Link del proyecto: [https://github.com/4d0lf00/Testing](https://github.com/4d0lf00/Testing)
