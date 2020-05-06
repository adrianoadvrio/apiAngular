# apiAngular ##
El Sistema fue desarrollado en la IDE Eclipse EE y está compuesto de:
•	API desarrollada en JAVA con tecnología JPA (Hibernate) e interface de testeo Swagger
•	Front End con tecnología AngularJS
•	Base de Datos PostgreSQL

Front  API Restfull Base de Datos



Configuración de la API:
1)	Importar el Proyecto compactado en el archivo “turno.jar” https://github.com/adrianoadvrio/apiAngular
2)	Verificar si las dependencias del archivo “pom.xml” están cargadas
3)	Aplicar las configuraciones de conexión del archivo “application.properties” conforme su base de datos 

Configuración del Front End:
1)	Descargar el archivo https://github.com/adrianoadvrio/apiAngular
2)	Instalar el servidor para el Front End
•	Un servidor local (instalado vía MPN) para hospedar la página web del Proyecto. 
(en caso de no tener MPN, descargar nodejs desde este link https://nodejs.org/en/download/)
3)	Abrir ventana CMD o Windows Power Shell.
4)	Instalar el servidor con el siguiente comando: npm install - g http-server
5)	Descompactar el archivo front.rar en la carpeta que desee.
6)	Abrir el CMD o Windows Power Shell y entrar en la carpeta donde se encuentra el archivo “index.html”
7)	Ejecutar el comando http-server - o (el servidor va a buscar automáticamente el archivo index.html)




Secuencia de inicialización del SISTEMA
1)	Se debe iniciar la aplicación JAVA API Rest. desde el paquete con.turnos.api (la aplicación se va a iniciar con su propio servidor en el puerto 8080).
2)	Desde la primera inicialización de la API JAVA y teniendo el Pograma Postgre SQL instalado una tabla se va a crear automáticamente como se indica en el archivo “application.properties”
3)	Ejecutar el servidor web con el comando http-server – o (el servidor web se va a iniciar en el puerto 8081) y se va a cargar los campos de la tabla que fue creada automáticamente pero que no posee registros.

Registro de datos:
1)	Pulsar el Botón “Alta del turno” de la página web
2)	Ingresar manualmente datos para crear 2 o 3 registros
3)	Recargar la página para obtener el listado de registros ingresados en la base de datos


Seagger (testeo de envío y recepición)
 http://localhost:8080/swagger-ui.html#/turno45resource   la aplicación de testeo funciona independientemente del front end, es justamente para verificar las requisiciones HTPP  en  JSON.  (pulsar en    produto-resource



OBSERVACIONES:
Las consignas totales del Proyecto no se cumplieron en su totalidad debido al contexto actual de contingencia que me impuso ciertas compromisos laborales, impidiéndome por ende, dedicar 100%  de mi jornada a este desarrollo.
