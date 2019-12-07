Instrucciones para la creación de la aplicacion web
 
Se creó back-end usando Node js, Express, Mongo DB

nombre de la carpeta: back-end-nodejs
url:localhost:3700/
=====================================================================================================================
se creó Frond-end usando angular 6
nombre de la carpeta: portafolio
url:http://localhost:4200/
=====================================================================================================================

contenido back-end

routes => para  crear la ruta get,put,post,delete

models => para crear las propiedades que se trae de la base de datos mongo DB
     name : string,
    description : string,
    category : string,
    year : number,
    langs :string,
    image : string

controller => crear las funciones CRUD para enviarlo al Front-end
1.- se crearon los metodos para crear, leer,actualizar y eliminar el contenido de la web
2.- se agregó codigo para subir archivo al servidor.
=====================================================================================================================
contenido Frond-end

1.- se crearon modelos,servicios y componentes
usando html para la vista y typescript para el llamado y la creacion del CRUD.

2.- se creo un script la cual hace la grabacion del audio en el browser, usando el api getUserMedia().


=====================================================================================================================
1.-la aplicacion se basa en la creacion de un proyecto Personal con su respectivo CRUD, agregandole una funcion para grabar audio y guardarlo 
a la base de datos, la cual se puede borrar y editar.

2.- cuando se crea un nuevo proyecto en el formulario se encuentra la opcion para grabar el audio, le damos play empieza a grabar y le damos clic en stop 
se para el audio y  descarga automaticamente con la extencion audios.mp3 a la carpeta Download o Descargas depende de la configuracion de la computadora.

3. seleccionamos archivo y buscamos el audio.mp3 guardado en Download, lo subimos, y nos muestra una alerta de "el proyeto se ha creado correctamente".

4.- nos dirigimos a proyectos, alli nos muestra los proyectos agregados.

5.- podemos editar o eliminar el proyecto.

6.-  Termina el manual

GRACIAS..............





