# temario
temario 

1.-Introducción al desarrollo web
Historia y evolución del desarrollo web
Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)

- Historia y evolución del desarrollo web
- Tipos de aplicaciones web: 
  - Estáticas
  - Dinámicas
  - SPA (Single Page Application)
  - PWA (Progressive Web Application)

<img width="192" height="176" alt="image" src="https://github.com/user-attachments/assets/0e29cd93-b4b3-49c2-96eb-25081806399b" />


2.Arquitectura de aplicaciones web
Cliente-Servidor
Arquitectura de tres capas (presentación, lógica, datos)
REST y API-first design

 Modelo Cliente-Servidor
- Arquitectura de tres capas:
  - Presentación
  - Lógica
  - Datos
- REST y API-first design

<img width="492" height="236" alt="image" src="https://github.com/user-attachments/assets/29b38d62-383d-45d9-9f9d-b3bac96c6624" />


3. -Lenguajes y tecnologías fundamentales
HTML, CSS, JavaScript, PHP, MySQL

El desarrollo web utiliza diversos lenguajes y tecnologías que permiten construir sitios y aplicaciones funcionales, interactivas y seguras. Los principales son:

#### **HTML (HyperText Markup Language)**
- Es el lenguaje de marcado estándar para crear páginas web.
- Define la estructura del contenido (títulos, párrafos, listas, tablas, formularios).
- Ejemplo: `<h1>Bienvenido</h1>`, `<p>Este es un párrafo.</p>`

#### **CSS (Cascading Style Sheets)**
- Es el lenguaje de estilos utilizado para definir la apariencia visual de las páginas web.
- Permite controlar colores, fuentes, tamaños, márgenes y disposición de los elementos.
- Ejemplo: `body { background-color: #f0f0f0; }`

#### **JavaScript**
- Es el lenguaje de programación que añade interactividad a las páginas web.
- Permite validar formularios, crear animaciones, manejar eventos y comunicarse con servidores.
- Se ejecuta en el navegador (frontend) y también puede usarse en el servidor (backend) con tecnologías como Node.js.
- Ejemplo: `document.getElementById('boton').onclick = function() { alert('Hola!'); }`

#### **PHP**
- Es un lenguaje de programación del lado del servidor.
- Permite crear páginas web dinámicas, procesar formularios, gestionar sesiones y conectar con bases de datos.
- Se integra fácilmente con HTML y es ampliamente utilizado en sistemas de gestión de contenidos como WordPress.
- Ejemplo: `<?php echo "Hola, mundo!"; ?>`

#### **MySQL**
- Es un sistema de gestión de bases de datos relacional.
- Se utiliza para almacenar, organizar y consultar datos de la aplicación web (usuarios, productos, registros).
- Funciona junto con lenguajes de backend como PHP para acceder y modificar la información.
- Ejemplo de consulta: `SELECT * FROM usuarios WHERE activo = 1;`

4.-Control de versiones
Git y GitHub
Flujo de trabajo con ramas (branching, merge, pull requests)

### 4. Control de Versiones

El control de versiones es una práctica fundamental en el desarrollo web moderno, permitiendo gestionar y rastrear los cambios realizados en el código fuente de un proyecto. Las herramientas más utilizadas son **Git** y **GitHub**.
 **Git**
- Sistema de control de versiones distribuido.
- Permite guardar historiales de cambios, revertir versiones, crear ramas para desarrollo paralelo.
- Se utiliza localmente en tu computadora y también puede sincronizarse con servidores remotos.

**GitHub**
- Plataforma basada en la web que aloja repositorios Git.
- Facilita la colaboración entre desarrolladores, la revisión de código y la gestión de proyectos.
- Permite compartir código, administrar incidencias (issues) y gestionar solicitudes de cambio (pull requests).
**Flujo de trabajo con ramas**
- **Branching (Ramas):**  
  Se crean ramas para desarrollar nuevas funcionalidades, corregir errores o experimentar sin afectar la rama principal.
  Ejemplo: `main`, `develop`, `feature/login`, `bugfix/header`

- **Merge (Fusión):**  
  Una vez que los cambios en una rama están listos, se fusionan con la rama principal o con otra rama. Esto integra los cambios y resuelve posibles conflictos de código.

- **Pull Requests (Solicitudes de extracción):**  
  Proceso para solicitar la integración de los cambios realizados en una rama hacia otra rama (generalmente la principal). Permite revisión de código, discusión y aprobación antes de fusionar.


Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web




1.-Diseño e implementación del frontend
Maquetación/Wireframe/Mockup
API

El frontend es la parte de la aplicación web que interactúa directamente con el usuario. Involucra el diseño visual, la experiencia de usuario y la lógica que se ejecuta en el navegador.

#### **Maquetación / Wireframe / Mockup**
- **Maquetación:**  
  Proceso de estructurar los elementos visuales de una página web (cabecera, menú, contenido, pie de página) usando HTML y CSS.
- **Wireframe:**  
  Esquema básico (boceto) que muestra la disposición de los elementos en la página, sin detalles visuales. Ayuda a planificar la navegación y la organización.
- **Mockup:**  
  Representación visual más detallada, incluyendo colores, tipografías e imágenes. Sirve para mostrar cómo se verá el diseño final antes de desarrollarlo.

#### **API en el Frontend**
- El frontend puede comunicarse con el backend o servicios externos mediante APIs (Application Programming Interface).
- Usar APIs permite mostrar datos dinámicos, enviar información de formularios, autenticar usuarios, etc.
- Ejemplo: Utilizar `fetch` en JavaScript para obtener datos de un servidor y mostrarlos en la página.


2.-Diseño e implementación del backend
Servidor
Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
2. Diseño e Implementación del Backend

El backend es la parte de la aplicación web que se ejecuta en el servidor y se encarga de procesar la lógica, almacenar datos y responder a las solicitudes del frontend.

#### **Servidor**
- El servidor es el software/hardware que recibe las solicitudes de los usuarios y responde con los recursos adecuados (páginas, datos, archivos).
- Ejemplos de servidores: Apache, Nginx, Node.js con Express, PHP, Python con Flask/Django.

#### **Manejo de Peticiones y Respuestas HTTP**
- El backend gestiona las **peticiones HTTP** (GET, POST, PUT, DELETE) que llegan desde el frontend o clientes externos.
- Procesa la información recibida, realiza operaciones necesarias (consultas de datos, cálculos, validaciones) y envía una **respuesta HTTP** que puede ser HTML, JSON, archivos, etc.
- Ejemplo básico en JavaScript (Node.js con Express):
  ```js
  app.get('/usuarios', (req, res) => {
    res.json({ usuarios: [] });
  });
  ```

#### **Conexión a Bases de Datos**
- El backend se conecta a bases de datos para almacenar, consultar y modificar información de la aplicación.
- **MySQL:** Base de datos relacional, muy utilizada en aplicaciones web.
- **PostgreSQL:** Base de datos relacional avanzada con soporte para operaciones complejas.
- **MongoDB:** Base de datos NoSQL orientada a documentos, ideal para estructuras flexibles y escalables.
- Ejemplo básico de conexión en PHP (MySQL):
  ```php
  $conexion = new mysqli('localhost', 'usuario', 'contraseña', 'basedatos');
  if ($conexion->connect_error) {
      die('Error de conexión: ' . $conexion->connect_error);
  }

3.-Bases de datos
 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend

3. Bases de Datos

Las bases de datos son fundamentales en el desarrollo web, ya que permiten almacenar, organizar y consultar información de manera eficiente y segura. En esta sección se abordan los siguientes conceptos clave:

#### **Modelado de datos y relaciones**
- **Modelado de datos:**  
  Proceso de definir cómo se estructurará la información en la base de datos, identificando entidades (por ejemplo, usuarios, productos) y sus atributos (nombre, correo, precio).
- **Relaciones:**  
  Se establecen conexiones entre diferentes tablas para reflejar cómo se vinculan los datos. Ejemplos:
  - **Uno a uno:** Un usuario tiene una sola dirección.
  - **Uno a muchos:** Un usuario puede tener varios pedidos.
  - **Muchos a muchos:** Los estudiantes pueden estar en varios cursos y cada curso tiene varios estudiantes.

#### **ORM (Object Relational Mapping)**
- Herramienta que permite interactuar con la base de datos usando objetos y clases en el código, en lugar de escribir consultas SQL directamente.
- Facilita el acceso, la manipulación y la gestión de datos, haciendo el código más organizado y seguro.
- Ejemplos de ORMs: **SQLAlchemy** (Python), **Eloquent** (Laravel/PHP), **Sequelize** (Node.js).

#### **CRUD desde el backend**
- **CRUD:**  
  Acrónimo de las principales operaciones sobre los datos:
  - **Create:** Crear nuevos registros.
  - **Read:** Leer o consultar datos existentes.
  - **Update:** Actualizar información.
  - **Delete:** Eliminar registros.
- Desde el backend se implementan las funciones para realizar estas operaciones, normalmente a través de rutas o endpoints que reciben peticiones HTTP.

```js
// Ejemplo básico de CRUD en Node.js con Express
app.post('/usuarios', (req, res) => { /* Crear usuario */ });
app.get('/usuarios', (req, res) => { /* Leer usuarios */ });
app.put('/usuarios/:id', (req, res) => { /* Actualizar usuario */ });
app.delete('/usuarios/:id', (req, res) => { /* Eliminar usuario */ });

4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización 

### 4. Seguridad Básica en Aplicaciones Web

La seguridad es esencial en el desarrollo web para proteger la información de los usuarios y el funcionamiento correcto de la aplicación. Esta sección cubre dos aspectos fundamentales:

#### **Validación de formularios**
- **Propósito:** Evitar que los usuarios envíen datos incorrectos, incompletos o maliciosos (como inyecciones de código).
- **Tipos de validación:**
  - **Validación en el frontend:** Se realiza en el navegador usando JavaScript y/o HTML5 (por ejemplo, campos obligatorios, formatos de correo, rangos de valores).
  - **Validación en el backend:** Se realiza en el servidor para garantizar que los datos recibidos sean correctos y seguros antes de guardarlos en la base de datos.
- **Buenas prácticas:** Validar siempre en ambos lados (nunca confiar solo en el frontend).

#### **Autenticación y autorización**
- **Autenticación:**  
  Proceso de verificar la identidad de un usuario (por ejemplo, mediante usuario y contraseña).
  - Ejemplo: Formularios de inicio de sesión.
  - Métodos avanzados: autenticación por token, OAuth, autenticación en dos pasos (2FA).
- **Autorización:**  
  Proceso de controlar el acceso del usuario a recursos o acciones específicas, según sus permisos o roles.
  - Ejemplo: Solo los administradores pueden eliminar usuarios.
  - Se implementa mediante reglas en el backend, asignación de roles y permisos.


Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional



1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend

1. Integración de Frontend y Backend

La integración entre frontend y backend es clave para crear aplicaciones web funcionales y dinámicas. Permite que la interfaz del usuario (frontend) se comunique con el servidor y la base de datos (backend) a través de APIs, intercambiando datos y operaciones.

#### **Interfaz de usuario Frontend**
- Es la parte visual con la que interactúa el usuario (HTML, CSS, JavaScript).
- Recoge datos del usuario (formularios, botones), muestra información proveniente del backend y responde a acciones.

#### **Manejo de API**
- El frontend utiliza APIs (Application Programming Interface) para enviar solicitudes al backend y recibir respuestas.
- Las APIs suelen comunicar datos en formato JSON o XML.
- Ejemplo: Registrar un usuario, consultar productos, actualizar información.

```js
// Ejemplo de llamada a una API desde el frontend usando fetch
fetch('https://api.ejemplo.com/productos')
  .then(response => response.json())
  .then(data => {
    // Mostrar productos en la interfaz
    mostrarProductos(data);
  });
```

#### **Proceso de Solicitud y Respuesta de Backend**
- **Solicitud:**  
  El frontend realiza una petición HTTP (GET, POST, PUT, DELETE) a una ruta específica del backend.
- **Procesamiento:**  
  El backend recibe la solicitud, la procesa (validaciones, lógica, consulta de datos) y prepara una respuesta.
- **Respuesta:**  
  El backend devuelve la información solicitada (o confirma una operación) al frontend, generalmente en formato JSON.

```js
// Ejemplo de endpoint en backend (Node.js con Express)
app.get('/productos', (req, res) => {
  res.json(productos);
});
```


2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento

2. Almacenamiento en Servidor

El almacenamiento en servidor es esencial para alojar aplicaciones web, manejar archivos, bases de datos y asegurar el acceso remoto a los recursos de la aplicación. En esta sección se abordan los conceptos clave:

#### **Tipos de servidores**
- **Servidor físico:**  
  Máquina dedicada que se encuentra en un centro de datos o en las instalaciones de la empresa.
- **Servidor virtual (VPS):**  
  Servidor simulado dentro de una máquina física, permite mayor flexibilidad y escalabilidad.
- **Servidor en la nube:**  
  Recursos disponibles bajo demanda a través de proveedores como AWS, Azure o Google Cloud, que permiten pagar solo por lo que se utiliza.

#### **Servidores y servicios de hosting**
- **Hosting compartido:**  
  Varios sitios web comparten los recursos de un mismo servidor. Es económico pero con limitaciones de rendimiento.
- **Hosting dedicado:**  
  El cliente dispone de un servidor completo para su uso exclusivo, mayor control y rendimiento.
- **Hosting VPS:**  
  Combina ventajas de hosting compartido y dedicado, recursos asignados virtualmente.
- **Hosting en la nube:**  
  Máxima flexibilidad y escalabilidad, ideal para aplicaciones que requieren alta disponibilidad.

#### **Proveedores de Servicios de Almacenamiento**
- **Amazon Web Services (AWS):** Ofrece almacenamiento con S3, bases de datos, servidores EC2, entre otros servicios.
- **Google Cloud Platform (GCP):** Soluciones como Cloud Storage, Cloud SQL, Compute Engine.
- **Microsoft Azure:** Almacenamiento en Blob, máquinas virtuales, bases de datos administradas.
- **Otras opciones populares:** DigitalOcean, Heroku, Hostinger, GoDaddy.


3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto
2. Almacenamiento en Servidor
El almacenamiento en servidor es esencial para alojar aplicaciones web, manejar archivos, bases de datos y asegurar el acceso remoto a los recursos de la aplicación. En esta sección se abordan los conceptos clave:

Tipos de servidores
Servidor físico:
Máquina dedicada que se encuentra en un centro de datos o en las instalaciones de la empresa.
Servidor virtual (VPS):
Servidor simulado dentro de una máquina física, permite mayor flexibilidad y escalabilidad.
Servidor en la nube:
Recursos disponibles bajo demanda a través de proveedores como AWS, Azure o Google Cloud, que permiten pagar solo por lo que se utiliza.
Servidores y servicios de hosting
Hosting compartido:
Varios sitios web comparten los recursos de un mismo servidor. Es económico pero con limitaciones de rendimiento.
Hosting dedicado:
El cliente dispone de un servidor completo para su uso exclusivo, mayor control y rendimiento.
Hosting VPS:
Combina ventajas de hosting compartido y dedicado, recursos asignados virtualmente.
Hosting en la nube:
Máxima flexibilidad y escalabilidad, ideal para aplicaciones que requieren alta disponibilidad.
Proveedores de Servicios de Almacenamiento
Amazon Web Services (AWS): Ofrece almacenamiento con S3, bases de datos, servidores EC2, entre otros servicios.
Google Cloud Platform (GCP): Soluciones como Cloud Storage, Cloud SQL, Compute Engine.
Microsoft Azure: Almacenamiento en Blob, máquinas virtuales, bases de datos administradas.
Otras opciones populares: DigitalOcean, Heroku, Hostinger, GoDaddy.
