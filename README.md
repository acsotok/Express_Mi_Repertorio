Descripción

La escuela de música “E-Sueño” está motivando a sus estudiantes de canto a presentarse en vivo y se puso en contacto con el restaurante del sector para utilizar su tarima e iniciar un calendario de presentaciones. Para conocer y gestionar las canciones que cantarán sus estudiantes, la escuela contrató a un desarrollador freelance para la reación de una aplicación tipo CRUD. En este desafío deberás desarrollar un servidor con Express que utilice el módulo File System para agregar, modificar y eliminar canciones almacenadas en un JSON local llamado repertorio.json.

Funcionalidades

El servidor deberá disponibilizar las siguientes rutas:

POST /canciones : Recibe los datos correspondientes a una canción y la agrega al repertorio.

GET /canciones : Devuelve un JSON con las canciones registradas en el repertorio.

PUT /canciones/:id : Recibe los datos de una canción que se desea editar y la actualiza manipulando el JSON local.

DELETE /canciones/:id : Recibe por queryString el id de una canción y la elimina del repertorio.

Requerimientos

Levantar un servidor local usando Express Js.

Devolver una página web como respuesta a una consulta GET.

Ofrecer diferentes rutas con diferentes métodos HTTP que permitan las operaciones CRUD de datos alojados en un archivo JSON local.

Manipular los parámetros obtenidos en la URL.

Manipular el payload de una consulta HTTP al servidor.
