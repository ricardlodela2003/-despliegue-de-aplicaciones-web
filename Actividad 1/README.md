**3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
datos sensibles que se envían.**


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






