# API-REST-Firebase
Esta aplicacion nos permite generar una api para crear, consultar, actualizar y eliminar tareas
esto a traves de controladores diseñados para ayudarnos con estas funcionalidades.

El medio de conexion es a traves de Firebase, para ello, se requirió crear un proyecto, usar Firestore Database, crear una coleccion y luego generar la conexion desde la aplicion.

La forma para llevar a cabo esta conexion, es mediante una "secret key" que nos genera Firebase, entonces lo que sigue es importar el modulo "firebase-admin", el cual nos ayudara a realizar la conexion con la bd.

Y finalmente poner la url de nuestro proyecto firebase junto con la ruta de la bd

En cuanto al modelo y al controlador, tuvieron que ser modificados para poder mandar llamar promesas de Firebase