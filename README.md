# examensemillero
examensemillero
API REST en SpringBoot para ListarUsuarios, ObtenerUsuarioPorEmail.
Todo inicia en el controlador que es donde se recibe la petición web, inmediatamente manda
a llamar al servicio que es el que ejecuta la lógica y este utiliza el repositorio que es 
donde se hacen las conexiones realmente con la BD y el repositorio a su vez utiliza el modelo para 
saber que tipo de información va a traer.

