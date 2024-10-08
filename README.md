# Implementaci-n-CRUD.-Construir-Layout-
# Proyecto de Gestión de Estudiantes

Este proyecto consiste en una aplicación que gestiona estudiantes, materias y sus respectivas notas, tanto en el backend como en el frontend. El backend está desarrollado en Node.js con una base de datos MySQL, y el frontend está creado con Android Studio.

## Contenidos

- [Requisitos](#requisitos)
- [Configuración del Backend](#configuración-del-backend)
- [Configuración del Frontend](#configuración-del-frontend)
- [Integración del Backend y Frontend](#integración-del-backend-y-frontend)
- [Demostración en Video](#demostración-en-video)
- [Cómo ejecutar el proyecto](#cómo-ejecutar-el-proyecto)
- [Contribuciones](#contribuciones)

## Requisitos

Para ejecutar el proyecto correctamente, necesitarás:

- Node.js v14 o superior
- Android Studio (última versión recomendada)
- MySQL 8.0 o un contenedor MySQL
- Postman o cualquier herramienta para probar APIs

## Configuración del Backend

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/sparyock/Implementaci-n-CRUD.-Construir-Layout-.git
   cd proyecto-estudiantes/backend



 ## Instalar las dependencias:

bash
Copiar código
npm install
Configurar la base de datos:

Sube el contenedor de MySQL siguiendo el manual de serve-mysql.
Crea la base de datos estudiante con las siguientes entidades:
estudiante: id, nombre, apellido, documento.
materia: id, nombre, créditos.
nota: id, corte, valor.
matricula: id, estudiante_id, materia_id, nota_definitiva.
Usa snake_case para los nombres de las tablas y atributos.
Configurar el archivo .env:

## Crea un archivo .env en la raíz del proyecto con las siguientes variables de entorno:

makefile
Copiar código
DB_HOST=localhost
DB_USER=root
DB_PASS=password
DB_NAME=estudiante
Iniciar el servidor backend:

bash
Copiar código
npm run start
Probar el backend:

## Usa Postman para probar las rutas del backend y asegurarte de que las APIs funcionan correctamente (por ejemplo, para crear estudiantes, registrar notas, etc.).

Configuración del Frontend
Sigue estos pasos para configurar el frontend:

Abrir el proyecto en Android Studio:

Navega al directorio frontend y abre el proyecto en Android Studio.
Configurar las pantallas interactivas:

Desarrolla las pantallas para estudiantes, materias y notas, asegurándote de que se conecten a las APIs del backend.
Prueba la navegación:

Verifica que la navegación entre las pantallas sea fluida y que la comunicación con el backend funcione correctamente.
Integración del Backend y Frontend
El frontend de Android se comunica con el backend mediante llamadas API. Asegúrate de que las URL del backend estén correctamente configuradas en el código del frontend.

Para una integración completa:

Ejecuta el backend con npm run start.
Ejecuta la aplicación en Android Studio.
Asegúrate de que ambas partes estén conectadas y funcionando correctamente.
Demostración en Video
Puedes ver una demostración del funcionamiento del proyecto en el siguiente enlace:

## Video de Demostración

Cómo ejecutar el proyecto
Backend:
Clona el repositorio.
Configura la base de datos MySQL.
Instala las dependencias con npm install.
Configura las variables de entorno en el archivo .env.
Inicia el servidor con npm run start.
Frontend:
Abre el proyecto en Android Studio.
Asegúrate de que el backend esté corriendo antes de ejecutar la app.
Ejecuta la aplicación en un emulador o dispositivo físico.
Pruebas:
Usa Postman para realizar peticiones a las APIs del backend.
Navega entre las pantallas en la aplicación de Android y asegúrate de que el sistema funcione correctamente.
Contribuciones
Si deseas contribuir a este proyecto, sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature-nueva-funcionalidad).
Realiza tus cambios y haz commit (git commit -m 'Descripción del cambio').
Sube tus cambios (git push origin feature-nueva-funcionalidad).
Abre un Pull Request.
