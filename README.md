# Chatty
Chatty es un software de chat hecho específicamente para Twitch, en el espíritu de un cliente IRC clásico. Se ejecuta en Windows y cualquier otro sistema operativo que soporte Java 8 o posterior.


Instalación 
------------ 
No es necesario realizar ninguna instalación, simplemente extraiga el archivo Chatty_*.zip en una carpeta e inicie Chatty.jar con Java. 

Iniciando Chatty 
--------------- 
Es posible que puedas simplemente hacer doble clic en Chatty.jar. Si le pide que seleccione un programa para abrirlo, elija Java. 
También puede crear un acceso directo para iniciar Chatty. Al crear el acceso directo, utilice: javaw -jar "<Ruta a Chatty.jar>" 
Por ejemplo: 
javaw -jar "C:\Program Files (x86)\Chatty\Chatty.jar" 

Esto también le permite agregar opciones de inicio, por ejemplo, definir el canal al que unirse: 
javaw -jar "C:\Program Files (x86)\Chatty\Chatty.jar" -channel twitch 

Si crea un acceso directo como este, asegúrese de configure el directorio de trabajo correctamente (especificado en un campo denominado "Ejecutar" o similar). 
Esto puede ser importante para algunas funciones. 

Es posible que también necesites especificar la ruta completa a Java si simplemente "javaw -jar" no funciona: C:\Windows\System32\javaw.exe -jar "C:\Program Files (x86)\Chatty\Chatty.jar " O para usar un JRE específico: 
C:\Program Files\Java\jre1.8.0_261\bin\javaw.exe -jar "<Ruta a Chatty.jar>" 

Configuración
-------------- 

La configuración se guarda en una subcarpeta ".chatty" de su directorio de usuario de forma predeterminada. 
Puede averiguar dónde se guardan las configuraciones ingresando "/dir" en Chatty. 
Puede cambiar esta ubicación a su directorio de trabajo actual usando la opción de inicio "-cd", a un directorio específico usando la opción de inicio "-d <dir>" (el directorio ya debe existir) o a un directorio ubicado al lado a Chatty.jar utilizando la opción de inicio "-portable". 

Archivo de registro 
------------------- 

Hay un subdirectorio /debuglogs en el directorio de configuración que contiene varios registros de depuración diferentes. Hay más información sobre ellos en la ayuda. 

Más ayuda 
--------- 
Hay más ayuda disponible en Chatty en <Ayuda - Acerca de/Ayuda> y en línea en el sitio web de Chatty como se menciona al principio de este archivo. 

Licencia 
-------- 

Chatty se publica bajo GPLv3. Consulte la ayuda en la aplicación y el repositorio de GitHub para obtener información más detallada.
