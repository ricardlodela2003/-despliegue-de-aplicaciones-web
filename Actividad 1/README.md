**3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
datos sensibles que se envían.**

accept-ranges: es un marcador usado por el servidor para notificar que soporta solicitudes parciales. 
cache-control: contiene directivas tanto en peticiones como en respuestas para controlar el almacenamiento temporal. 
content-encoding: es usada para comprimir el media-type. 
content-language: es usada para describir el idioma que está destinado a la audiencia. 
content-length: indica el tamaño de la entidad cuerpo, en bytes, enviado al destinatario. 
content-script-type: especifica el lenguaje de secuencias de comandos predeterminado para el fragmento de documento dado en el elemento. 
content-style-type: especifica el idioma de la hoja de estilo para el fragmento de documento dado en el elemento. 
content-type: sirve para indicar el tipo de medio original del recurso. 
date: sirve para identificar el dia y la hora. 
pragma: puede tener varios efectos a lo largo de la cadena solicitud respuesta. 
server: el servidor
strict-transport-security: informa a los navegadores que solo se debe acceder al sitio mediante HTTPS, y que cualquier intento futuro de acceder mediante HTTP se debe convertir automáticamente a HTTPS.
vary: determina como hacer coincidir los encabezados de las solicitudes futuras para decidir si se puede utilizar una respuesta oculta en caché en lugar de solicitar una nueva desde el servidor de origen.  
x-content-type-options: es un marcador utilizado por el servidor para indicar que los tipos MIME anunciados en los content-type encabezados deben seguirse y no cambiarse. 
x-frame-options: se puede usar para indicar si un navegador debe permitir o no mostrar una página en un, 0. 
x-ua-compatible: permite a los autores de la web elegir la versión de Internet Explorer con la que se debe mostrar la página. 
x-xss-protection: es una característica de internet explorer, chrome y safari que impide la carga de una página cuando detecta ataques del tipo Cross-site. 

token: cuando el cliente se ha podido validar como un usuario de la aplicación, recibe una cadena encriptada como respuesta. Esa cadena es el token y sirve para que en los siguientes accesos, el usuario pueda informar al servidor que ya ha pasado por el proceso de autenticación. 


**4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP,
UDP, e IP?**

Normalmente el puerto que se utiliza es el 80 que se usa para la comunicación del sistema de cliente a sitio. 
El HTTP se encuentra en la capa 4 o también llamada capa de aplicación. 
El protocolo TCP se encuentra en la capa 1 o capa de acceso al medio. 
El protocolo UDP se encuentra en la capa 3 o capa de transporte. 
Y por último el protocolo IP se encuentra en la capa 1 o capa de acceso al medio y también se encuentra en la capa 2 o capa de internet. 


**5. ¿Cuál es el significado de la siguiente respuesta de un servidor?
HTTP/1.1 302 Found
Location: http://www.example.com/test/index2.php**

Significa que el recurso solicitado ha sido movido temporalmente a la URL dada por las cabeceras Location. También significa que la 
página ha sido movida temporalmente. 


**6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.**






