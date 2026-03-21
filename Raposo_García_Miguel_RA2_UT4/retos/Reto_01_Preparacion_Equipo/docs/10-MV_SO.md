# Ejercicio 1: Máquina Virtual y SO

## Hipervisor utilizado y versión de Windows

En este caso, he utilizado **VirtualBox** ya que es el hipervisor el cual más controlo y me permite realizar todo el trabajo sin problemas.
Como sistemas operativo me he decantado por Windows 11 ya que, Windows es el SO por excelencia para oficina, he elegido la versión 11 porque al ser la última que ha salido, va a seguir teniendo actualizaciones de seguridad mientras que en Windows 10 ya finalizo su soporte. Además, al ser la última versión, te aseguras que el equipo será compatible con todas la nuevas versiones de los sofwares de oficina, navegadores o incluso los servicios de Google. Por último, Windows 11 viene con un gestión de ventanas más optima y cómoda para multitarea en oficina.

![Hipervisor_Win11](../assets/img/10-MV_SO/Win11.png)

## Recursos asignados a la máquina virtual

Para el he decidido poner las mismas especificaciones que el PC por piezas creado en mi tarea anterior, por eso he elegido 8GB de RAM y 4 núcleos de la CPU. Esto permite una rápida navegación y multitarea con varios documentos abiertos a la vez, sin que se vea comprometida la velocidad. De almacenamiento, ahora en la maquina virtual he seleccionado 80GB ya que para la práctica me es suficiente, pero el ordenador real tendría 240GB. En cuanto a la red, en la realidad estaría conectado a partir de RJ45 Cat5e, para VirtualBox lo he configurado para que utilice la red de mi propio ordenador.

![RAM_CPU](../assets/img/10-MV_SO/RAM_CPU.png)
![Almacenamiento](../assets/img/10-MV_SO/Almacenamiento.png)
![Red](../assets/img/10-MV_SO/Red.png)

## Proceso básico de instalación

El primer paso es seleccionar el idioma y formato de hora y moneda, en mi caso selecciono Español, España.
![Paso1](../assets/img/10-MV_SO/Paso1.png)

Para el teclado también lo ponemos en Español.
![Paso2](../assets/img/10-MV_SO/Paso2.png)

En nuestro caso hay que seleccionar "instalar Windows 11" y aceptar que se eliminen todos los archivos para continuar al siguiente paso.
![Paso3](../assets/img/10-MV_SO/Paso3.png)

Para este paso habría que introducir una clave de producto, yo he seleccionado la opción de que no tengo clave de producto, ya que te deja continuar igual. La clave se pude introduccir más tarde en configuración o utilizar otro metodo para activar el windows de manera gratuita.
![Paso4](../assets/img/10-MV_SO/Paso4.png)

De versión de Windows 11 he seleccionado la Pro ya que es la que luego nos permite configurara de mejor manera el ordenador, además de tener configuración que la versión Home no posee, como la unión a dominios muy utilizada en empresas para conectar todos los ordenadores la un nube común, también posee configuración para hacer el dispositivo más seguro como el BitLocker (cifrado de disco).
![Paso5](../assets/img/10-MV_SO/Paso5.png)

Acepatamos la licencia y avisos.
![Paso6](../assets/img/10-MV_SO/Paso6.png)

Seleccionamos el disco utilizado previamente y si quisieramos se podrían crear particiones, aunque lo más comodo es que Windows se encargue automáticamente.
![Paso7](../assets/img/10-MV_SO/Paso7.png)

Instalamos Windows
![Paso8](../assets/img/10-MV_SO/Paso8.png)

![Paso9](../assets/img/10-MV_SO/Paso9.png)

Tras instalarse, seleccionamos Español en los siguientes pasos.
![Paso10](../assets/img/10-MV_SO/Paso10.png)

![Paso11](../assets/img/10-MV_SO/Paso11.png)

Le ponemos nombre al dispositivo.
![Paso12](../assets/img/10-MV_SO/Paso12.png)

Seleccionaremos la opcion de "Configurar para uso profesional" para habilitar la creación de cuentas locales de administración, evitando vincular el equipo de la oficina a cuentas personales de Microsoft.
![Paso13](../assets/img/10-MV_SO/Paso13.png)

Clicamos en "Opciones de inicio de sesión".
![Paso14](../assets/img/10-MV_SO/Paso14.png)

Clicamos en "Unirse a un dominio".
![Paso15](../assets/img/10-MV_SO/Paso15.png)

Creamos el usuario Admin.
![Paso16](../assets/img/10-MV_SO/Paso16.png)

Le ponemos una contraseña.
![Paso17](../assets/img/10-MV_SO/Paso17.png)

Nos piden tres peguntas de seguridad. Se rellenan con respuestas que vayamos a recordar.
![Paso18](../assets/img/10-MV_SO/Paso18.png)

Empezarán a pedirnos permisos los cuales vamos a rechazar ya que son totalmente opcionales e innecesarios. Estos solo harán que el equipo vaya más lento por culpa de que Windows esté recopilando información continuamente.
![Paso19](../assets/img/10-MV_SO/Paso19.png)

En esta opción, ponemos solo los obligatorios.
![Paso20](../assets/img/10-MV_SO/Paso20.png)

## Creación de, al menos, un usuario administrador y un usuario estándar.

El usuario admin, lo hemos creado ya mienrtas instalábamos Winsdows. Gracias a los pasos realizados este se crea automaticamente como administrador, por lo que vamos a crear el usuario estándar.
![Admin](../assets/img/10-MV_SO/Admin.png)

Comenzamos yendo a la configuración, seleccionamos cuentas y nos vamoas a la opción de "Otros usuarios". Luego clicamos en agregar cuenta.
![User1](../assets/img/10-MV_SO/User1.png)

Le damos a que no tenemos los datos de inicio de sesión de esta persona.
![User2](../assets/img/10-MV_SO/User2.png)

Agregamos un usuario sin cuenta de Microsoft.
![User3](../assets/img/10-MV_SO/User3.png)

Metemos el nombre de usuario con su contraseña, además nos pide completar tres preguntas de seguridad.
![User4](../assets/img/10-MV_SO/User4.png)

Y ya estaría creado el usuario estándar.
![User5](../assets/img/10-MV_SO/User5.png)

## Pruebas
Capturas de pantalla que demuestren la configuración de la máquina virtual, el proceso de instalación y el sistema ya operativo.

![Justificacion](../assets/img/10-MV_SO/Justificación1.png)
![Justificacion](../assets/img/10-MV_SO/Justificación2.png)
