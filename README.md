# RouterESP
El proyecto contiene la herramienta para flashear el Nodemcu-espX2 y los binarios con su dirección de inicio (address ofset)

Instrucciones
---------------
- El ejecutable de la herramienta de flasheo está en la ruta \nodemcu-flasher-master\nodemcu-flasher-master\Win64\Release (Win32 para 32 bits)
- Ya dentro vamos a la pestaña bins y seteamos los bin de la carpeta bins con su dirección de inicio correspondiente

![Binarios](Recursos/1CargaBins.png)

- configuramos los parametros del flaseo, esos son los que recomiendo pero los defalut también están bien (la velocidad del flasheo la determina el baudrate)

![Settings](Recursos/2Config.png);

-iniciamos el flaseo y esperamos que termine

![Flacheo](Recursos/3flash.png)

- Una vez terminado vamos a configurar el nodemcu, nos conectamos al wifi "MYAP" y entrando a cualquier navegador e ingresando la dirección 192.168.4.1 accederemos a la configuración del router, que es bastante intuitiva

![ConfigRuter](Recursos/4ConfigRouter.png)

- STA setting: la dirección y contraseña del router al que se va a conectar el nodemcu
- AP settings: la dirección y contraseña para conectarse al nodemcu


# Linux
---------------
-los Binarios esán disponibles para que los puedan programar, luego pondé una herramienta de flasheo para Linux
