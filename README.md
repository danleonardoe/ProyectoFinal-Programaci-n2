# ProyectoFinal-Programacion2

El objetivo de este proyecto es desarrollar un sistema de ventas en línea que permita a los usuarios realizar compras, gestionar inventarios y procesar pedidos. El sistema cuenta con 2 tipos de perfiles (cliente y administrador), en el perfil cliente el usuario se puede registrar con un correo electronico e ingresando una contraseña, dichas credenciales se almacenan en una base de datos en MongoDB, esta informacion nos sirve para poder ingresar a la tienda Online. El usuario pude ver en su pantalla los productos y las opciones que desee gestionar. Dentro de la pagina cuenta con un carrito de compras, donde el usuario puede almacenar y visualizar los articulos a comprar. Asi mismo el programa cuenta con un metodo de pago, siendo las mas practicas para que el usuario tenga opciones de poder cancelar lo que ha comprado por medio de tarjeta de credito, débito o transferencia bancaria. Además, se implementaron funciones de reportes para la administración del catálogo y de las ventas. Dichos reportes tambien se almacenan en nuestra base de datos en mongoDB.
 
El backend será implementado en Java 17

 utilizando Spring Framework
 
el frontend será desarrollado con React

y los datos se almacenarán en una base de datos NoSQL utilizando MongoDB.

 Este proyecto cuenta con Requerimientos Funcionales los cuales permitirán que el usuario pueda interactuar dentro de la aplicación de una manera sencilla, los cuales son los siguientes:
 
 La aplicacion cuenta con una opcion de Registro y Mantenimiento:
1.  	Usuarios y Perfiles:
a.      Registro de usuarios con diferentes perfiles: Cliente y Administrador.
Como bien se explica al principio de este manual usuario, para que el usuario pueda ingresar a la pagina principal dode se encuentran los productos y articulos.
2.  	Mantenimiento de Empresas:
b.      Registro y actualización de información de la empresa que ofrece los servicios o productos.
En este apartado se puede ingresar como un usuario administrador, el cual se encuentra el registro de cada entrada y salida que se haga dentro de la empresa.
3.  	Contactos:
c.       Registro y gestión de contactos relacionados con la empresa.
en este apartado se pueden visualizar todos aquellos contactos que tengan relacion con la empresa, esta información se almacena en la base de datos de mongoDB.
4.  	Catálogo de Artículos:
d.      Gestión de artículos clasificados en categorías y subcategorías.
En este apartado el usuario podrá tener una busqueda mas especifica, ejemplo si desea adquirir alguna lavadora lo puede encontrar en la familia de electrodomésticos, si desea una mesa la puede encontrar en la familia muebles, etc. 
5.  	Clientes y Proveedores:
e.      Gestión de clientes que compran en la tienda y proveedores que abastecen el inventario.
6.  	Tipos de Pago:
f.        Integración de pagos mediante depósitos y tarjetas de crédito/débito, PayPal (opcional).
7.  	Pedidos:
g.      Registro de pedidos con su respectivo Kardex.
8.  	Carrito de Compras:
h.      Funcionalidad de carrito de compras para los clientes, gestionando el stock y pedidos asociados.
9.  	Historial de Transacciones:
i.        Mantener un registro detallado de las transacciones (compras y ventas), accesible para consultas.
 
 
Reportes:
1.  	Existencia de Artículos:
-          Búsqueda de artículos por ID, mostrando detalles del inventario.
2.  	Pedidos y Ventas:
-          Reporte de pedidos y ventas, con opción de búsqueda por ID de transacción.
3.  	Histórico de Transacciones:
-          Reporte que permite filtrar las transacciones por ID de cliente.
 
 Requerimientos Técnicos:
 
 Backend:
-          Implementado en Java 17 utilizando el Spring Framework y Spring Boot.
-          Exposición de una API RESTful para manejar todas las operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre usuarios, artículos, pedidos, y transacciones.
-          Integración de métodos de pago mediante PayPal API (opcional)
-          Almacenamiento de datos en MongoDB para aprovechar su flexibilidad en la gestión de documentos.
 
 Frontend:
-          Desarrollado con React.
-          Diseño de una interfaz de usuario para que los usuarios puedan registrarse, iniciar sesión, gestionar sus perfiles, realizar compras y ver su historial de transacciones.
-          Implementación de componentes reutilizables para el manejo del carrito de compras, listado de productos, detalles de los productos y reportes.
 
 Base de Datos:
-          MongoDB será utilizada como la base de datos NoSQL, que almacenará todos los datos relacionados con los usuarios, productos, pedidos y transacciones.
-          Diseño eficiente de los documentos en MongoDB, permitiendo que la estructura del sistema de ventas pueda escalarse y ser flexible a futuros cambios.
 
 Despliegue:
-          Integración completa entre el frontend y backend utilizando la API REST. 
