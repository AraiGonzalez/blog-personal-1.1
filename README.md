# Blog Personal

## Descripción
Este proyecto es una aplicación de blog personal construida con Node.js, Express y MongoDB Atlas. Se desarrolló como parte de la materia de Backend de la Tecnicatura en Desarrollo de Software en el IFTS N° 29. La aplicación permite a los usuarios registrarse, iniciar sesión, crear publicaciones, comentar en publicaciones y gestionar usuarios. Utiliza `express-session` para la gestión de sesiones y `jsonwebtoken` para la autenticación basada en tokens.

### Funcionalidades Principales

1. **Autenticación de Usuarios**:
   - Registro de nuevos usuarios.
   - Inicio de sesión con verificación de credenciales.
   - Cierre de sesión para finalizar la sesión del usuario.
   - Creación de usuarios administradores con permisos especiales.

2. **Gestión de Publicaciones**:
   - Creación de nuevas publicaciones con título, contenido y categoría.
   - Edición de publicaciones existentes.
   - Eliminación de publicaciones.
   - Listado de todas las publicaciones.
   - Filtrado de publicaciones por autor y categoría.
   - Comentarios en publicaciones por parte de los usuarios.

3. **Gestión de Usuarios**:
   - Listado de todos los usuarios registrados en la aplicación.
   - Cambio de roles de usuario (de `user` a `admin` y viceversa).
   - Eliminación de usuarios.

4. **Mensajes Flash**:
   - Notificaciones de éxito y error para las acciones realizadas por los usuarios, como registro, inicio de sesión, creación de publicaciones, etc.

### Arquitectura del Proyecto

El proyecto sigue la arquitectura MVC (Modelo-Vista-Controlador):

- **Modelos**: Definen la estructura de los datos y las relaciones entre ellos. Utilizamos Mongoose para definir los esquemas y modelos de datos.
- **Vistas**: Utilizamos Pug como motor de plantillas para renderizar las vistas HTML.
- **Controladores**: Contienen la lógica de negocio y manejan las solicitudes HTTP. Los controladores se encargan de interactuar con los modelos y renderizar las vistas correspondientes.

### Tecnologías Utilizadas

- **Node.js**: Entorno de ejecución para JavaScript.
- **Express**: Framework para construir aplicaciones web y APIs.
- **MongoDB Atlas**: Base de datos NoSQL en la nube.
- **Mongoose**: ODM para MongoDB.
- **express-session**: Middleware para la gestión de sesiones.
- **connect-mongo**: Almacén de sesiones para MongoDB.
- **jsonwebtoken**: Biblioteca para la gestión de tokens JWT.
- **bcrypt**: Biblioteca para encriptar contraseñas.
- **dotenv**: Carga variables de entorno desde un archivo `.env`.
- **pug**: Motor de plantillas para renderizar vistas HTML.
- **supertest**: Biblioteca para realizar solicitudes HTTP y probar aplicaciones Express.
- **jest**: Framework de pruebas para JavaScript.
- **mongodb-memory-server**: Servidor MongoDB en memoria para pruebas.


### Instalación y configuración
Clonar el repositorio :
intento

### Copiar
git clone https://github.com/AraiGonzalez/blog-personal-1.1.git
cd blog-personal
Instalar las dependencias :
intento

### Copiar
npm install

### Copiar
npm start
La aplicación se ejecutará en http://localhost:3000.

### Uso
Acceda a la aplicación en el navegador.
Regístrate como nuevo usuario para comenzar a crear publicaciones y comentar.
Si eres administrador, podrás gestionar usuarios y sus roles.

### proyecto deployado ( en railway)
https://blog-personal-production.up.railway.app/
