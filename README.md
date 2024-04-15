
# Aplicación CRUD de PHP

Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario. CRUD es un concepto básico en el desarrollo web. Si recién comienzas a programar, aquí aprenderás cuáles son los procesos esenciales que debes tener en cuenta al desarrollar software y gestionar bases de datos relacionales.Para ejemplificar la implementación del CRUD, vamos a considerar un gestor de pagos. 

##Create (crear)
Esta fase se utiliza para crear un nuevo registro en la base. Para implementar la operación «Crear», es necesario proporcionar un formulario o una interfaz donde el usuario pueda ingresar los datos para el nuevo registro. Después de que el usuario envía los datos, se debe realizar una validación de los mismos y luego insertarlos en la base o en el sistema de almacenamiento.

En un gestor de pagos, esto se podría utilizar para agregar un nuevo cliente o para crear un registro de pago.

## Desventajas y ventajas
Algunas ventajas son que facilita la creación y gestión de datos.
Proporciona una estructura coherente y fácil de entender para su manipulación.
Ayuda a minimizar los errores y garantiza la integridad de los datos.
Proporciona una base sólida para el desarrollo de aplicaciones.
Ahora algunas desventajas es que  puede ser demasiado simplista para aplicaciones complejas.
En ocasiones, es menos eficiente para aplicaciones de alta velocidad o de gran escala.
A veces, requiere una gran cantidad de código y configuración para implementarlo completamente.



## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.


---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

