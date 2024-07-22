# entregable-22-jul-2024
Ejercicios entregables con Django / Python

**Ejercicios elegidos:**

-    Adán
- 14 Alejandro
- 10 Cristian
- 20 Erik
- .  Irene
- 5  Fran
- . Glenn
- 6 Sergio
- 9 Josias
- . Yago
---

Lista de 20 ejercicios de Django que cubren diferentes aspectos del desarrollo web con este framework. Cada ejercicio incluye una breve descripción de los requisitos y los objetivos.

### Ejercicios de Django

#### 1. API Data Fetching
**Descripción**: Crear un endpoint que haga una petición a una API externa, obtenga datos y los devuelva formateados en una lista.
**Requisitos**:
- Usar `requests` para hacer la petición.
- Formatear los datos obtenidos.
- Devolverlos en formato JSON.

#### 2. JSON User List
**Descripción**: Crear un endpoint que devuelva una lista de usuarios en formato JSON.
**Requisitos**:
- Crear un modelo `User`.
- Poblar la base de datos con usuarios de prueba.
- Crear una vista que devuelva todos los usuarios en formato JSON.

#### 3. File List with Download Links
**Descripción**: Crear un endpoint que devuelva una lista de archivos en una carpeta específica con enlaces de descarga.
**Requisitos**:
- Leer el contenido de una carpeta.
- Generar enlaces de descarga para cada archivo.
- Devolver la lista en formato JSON.

#### 4. Profile Page with Login Requirement
**Descripción**: Crear una página de perfil que requiera autenticación para acceder.
**Requisitos**:
- Crear un sistema de autenticación.
- Crear una vista de perfil.
- Proteger la vista de perfil para que solo sea accesible a usuarios autenticados.

#### 5. CRUD Operations
**Descripción**: Implementar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para un modelo `Item`.
**Requisitos**:
- Crear el modelo `Item`.
- Implementar vistas para cada operación.
- Usar formularios de Django.

#### 6. Search Functionality
**Descripción**: Implementar una funcionalidad de búsqueda en una lista de artículos.
**Requisitos**:
- Crear un modelo `Article`.
- Crear una vista de búsqueda.
- Devolver resultados coincidentes.

#### 7. Pagination
**Descripción**: Implementar paginación en una lista de productos.
**Requisitos**:
- Crear un modelo `Product`.
- Crear una vista que soporte paginación.
- Mostrar un número limitado de productos por página.

#### 8. User Registration
**Descripción**: Crear un sistema de registro de usuarios.
**Requisitos**:
- Crear formularios de registro.
- Validar la información del usuario.
- Guardar nuevos usuarios en la base de datos.

#### 9. Email Sending
**Descripción**: Implementar una funcionalidad para enviar correos electrónicos.
**Requisitos**:
- Configurar un backend de email.
- Crear una vista para enviar correos.
- Enviar un correo de prueba.

#### 10. User Login and Logout
**Descripción**: Implementar vistas de inicio y cierre de sesión para usuarios.
**Requisitos**:
- Crear formularios de inicio de sesión.
- Manejar la sesión del usuario.
- Crear vistas para login y logout.

#### 11. File Upload
**Descripción**: Crear una funcionalidad para subir archivos.
**Requisitos**:
- Crear un formulario de subida de archivos.
- Manejar el almacenamiento de archivos subidos.
- Mostrar una lista de archivos subidos.

#### 12. User Profile Update
**Descripción**: Permitir a los usuarios actualizar su perfil.
**Requisitos**:
- Crear un formulario de actualización de perfil.
- Validar y guardar los cambios.
- Proteger la vista con autenticación.

#### 13. Dynamic Forms
**Descripción**: Crear formularios dinámicos que cambian según la entrada del usuario.
**Requisitos**:
- Usar formularios de Django.
- Implementar lógica para formularios dependientes.
- Actualizar el formulario dinámicamente con JavaScript.

#### 14. Social Login
**Descripción**: Implementar inicio de sesión con una red social (por ejemplo, Google o Facebook).
**Requisitos**:
- Configurar Django Allauth o similar.
- Integrar el login social.
- Manejar la autenticación y los perfiles sociales.

#### 15. Image Gallery
**Descripción**: Crear una galería de imágenes con subida y visualización.
**Requisitos**:
- Crear un modelo `Image`.
- Implementar la subida y almacenamiento de imágenes.
- Mostrar las imágenes en una galería.

#### 16. Data Export
**Descripción**: Implementar una funcionalidad para exportar datos a CSV.
**Requisitos**:
- Crear una vista para generar y descargar el archivo CSV.
- Formatear los datos en CSV.
- Manejar la descarga del archivo.

#### 17. Comment System
**Descripción**: Crear un sistema de comentarios para artículos.
**Requisitos**:
- Crear modelos `Article` y `Comment`.
- Implementar vistas para agregar y mostrar comentarios.
- Validar y guardar comentarios.

#### 18. Real-time Notifications
**Descripción**: Implementar notificaciones en tiempo real.
**Requisitos**:
- Usar Django Channels.
- Configurar WebSocket.
- Enviar y mostrar notificaciones en tiempo real.

#### 19. Like System
**Descripción**: Crear un sistema de "me gusta" para publicaciones.
**Requisitos**:
- Crear un modelo `Like`.
- Implementar lógica para agregar y quitar "me gusta".
- Mostrar el número de "me gusta" por publicación.

#### 20. Contact Form
**Descripción**: Crear un formulario de contacto que envíe mensajes por email.
**Requisitos**:
- Crear un formulario de contacto.
- Validar y procesar los datos.
- Enviar el mensaje por email.

### Entrega

- **Instrucciones**: Cada ejercicio debe completarse y subirse en una rama separada con el nombre del ejercicio (por ejemplo, `feature/exercise1`).
- **Repositorio**: Los alumnos recibirán la URL del repositorio donde deben hacer los pull requests.
- **Pull Requests**: Cada pull request debe incluir una descripción clara de los cambios y cómo probar la funcionalidad.

---

Estos ejercicios pueden completarse en aproximadamente una hora cada uno aproximadamente.
