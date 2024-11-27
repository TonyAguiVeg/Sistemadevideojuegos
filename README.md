# Sistema de gestion de Videojuegos

Este proyecto es un sistema de gestión de videojuegos desarrollado para permitir a los usuarios gestionar su biblioteca de juegos, 
realizar registros, actualizar información y eliminar videojuegos de su inventario. La plataforma incluye un sistema de autenticación para que los usuarios puedan crear cuentas,
iniciar sesión y personalizar su experiencia.

El sistema proporciona una interfaz fácil de usar donde los usuarios pueden ver una lista de sus videojuegos, agregar nuevos juegos a su colección, 
editar detalles como el título, la descripción y la plataforma, y eliminar juegos que ya no desean mantener. Además, cada usuario tiene su propio espacio de gestión de juegos, 
lo que permite una administración personalizada y segura.

## Caracteristicas

* Registro de usuarios y autenticación con inicio de sesión.
* CRUD (Crear, Leer, Actualizar, Eliminar) completo para gestionar videojuegos.
* Gestión personalizada de juegos por usuario.
* Interfaz de usuario intuitiva y fácil de navegar.
* Función de búsqueda para encontrar juegos rápidamente.

## Para ejecutar este proyecto, asegúrate de tener instalados los siguientes programas y herramientas:

- Java JDK 17+: Necesario para ejecutar el proyecto en Java.
- Maven: Usado para manejar dependencias y construir el proyecto.
- Base de Datos: Puedes usar MySQL, PostgreSQL o cualquier base de datos compatible con JPA.
- MySQL
- IDE (Recomendado: IntelliJ IDEA): Para editar y ejecutar el código fácilmente.


## Registro e inicio de sesión de usuario:
Los usuarios deben registrarse en el sistema antes de poder acceder a las funcionalidades. Para ello, 
accede a la página de registro e ingresa los datos necesarios como nombre de usuario y contraseña.

Gestión de videojuegos:
Una vez registrado y logueado, los usuarios podrán gestionar su colección de videojuegos, clientes, reservas, prestamos a través de las siguientes opciones:

Funcionalidades de CRUD
Crear (Create):
Permite a los usuarios agregar nuevas instancias de una entidad a la base de datos. Esto implica llenar un formulario con los datos correspondientes a los atributos de la entidad, como:

Entidad de ejemplo: Videojuego, Usuario, Reserva, Producto, etc.
Campos típicos: Título, nombre, descripción, fecha, estado, etc.
Leer (Read):
Permite consultar y visualizar la información de las entidades almacenadas. Dependiendo del sistema, los usuarios pueden:

Visualizar detalles completos de una entidad específica.
Buscar entidades usando filtros o palabras clave (por ejemplo, buscar un producto por nombre o un usuario por correo).
Mostrar una lista de todas las instancias de una entidad.
Actualizar (Update):
Los usuarios pueden modificar la información existente de una entidad en la base de datos. Esto puede incluir cambios en cualquier atributo, como:

Cambiar el nombre, descripción, o cualquier otra propiedad de la entidad.
Actualizar el estado de la entidad (por ejemplo, cambiar el estado de una reserva o producto).
Eliminar (Delete):
Permite eliminar una entidad de la base de datos. Una vez eliminada, la instancia ya no estará disponible en el sistema.

Los usuarios pueden eliminar elementos de la lista, como registros de productos, usuarios o pedidos.
Listado
Visualización de Entidades:
Los usuarios pueden ver un listado de todas las instancias de una entidad. El listado puede incluir información relevante como el nombre, fecha de creación, estado, entre otros.

Filtros y Búsquedas:
Los usuarios pueden buscar y filtrar las entidades por ciertos atributos o criterios, como:

Fecha
Nombre o título
Estado (activo, inactivo, reservado, etc.)
Categoría, género o tipo
Paginación y Ordenamiento:
Si el número de registros es grande, se puede implementar paginación para mostrar los elementos de forma más organizada. Además, se puede permitir ordenar el listado por criterios como:

Nombre
Fecha de creación
Estado
Acciones sobre el Listado:
Los usuarios pueden realizar acciones desde el listado, como:

Editar: Modificar los registros directamente desde la lista.
Eliminar: Eliminar registros desde la vista de lista.
Ver detalles: Acceder a más información de cada entidad.



