carpeta routes
Aquí tendremos un archivo por cada entidad. Cada ruteador contendrá un objeto literal y cada método, por lo general, corresponderá a una ruta. Los middlewares de rutas se aplican en estos archivos.

main js
Ruteador por defecto. Contendrá todas las rutas que no pertenecen a una entidad, como el inicio, contacto, acerca de, etc.
product js


product js
Nuestro ruteador de productos. Contendrá rutas como creación, edición, detalle, listados, etc.

user js
Nuestro ruteador de usuarios.
Contendrá rutas como el registro, el login, el perfil, etc.