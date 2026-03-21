# Portada

- **Módulo:** Fundamentos de Hardware (FHW)  
- **Unidad:** UT4  
- **Reto:** 01 — Preparación de equipo  
- **Alumno/a:** Miguel Raposo García 
- **Curso:** 1º ASIR 
- **Fecha:** 21/03/2026

# Enunciado

## Objetivo Principal
Actuar como un **técnico informático** para preparar, desde cero, un ordenador de oficina virtualizado con **Windows**. El equipo debe quedar listo, seguro y optimizado para un entorno de trabajo basado principalmente en el ecosistema de **Google** (Drive, Docs, Gmail, etc.).

## Ejercicio 1: Máquina Virtual y SO (2 puntos)

- Crear una **máquina virtual** (VirtualBox, VMware, etc.).
- Asignar **hardware virtual** (RAM, CPU, disco) de forma coherente y justificada.
- Instalar Windows y crear al menos **dos usuarios**: un Administrador y uno Estándar.

## Ejercicio 2: Preparación y Software (3 puntos)

- Instalar **programas** para: navegación web, acceso a Google, visor PDF, descompresión de archivos y utilidades de oficina.
- Requisito clave: **No hay software impuesto**, pero debes justificar cada elección (nombre, función, motivo de elección y ventajas).

## Ejercicio 3: Seguridad y Pruebas (2,5 puntos)

- Instalar un **antivirus/antimalware** gratuito y actualizar Windows.
- Usar **herramientas de diagnóstico/monitorización** del sistema.
- Realizar **pruebas de funcionamiento**: Demostrar que se puede entrar a Gmail, abrir un PDF, descomprimir un archivo y que el antivirus funciona.
- **Registrar las incidencias** que surjan y explicar cómo las has solucionado.

## Ejercicio 4: Documentación en GitHub (2,5 puntos)

- Crear un **repositorio** público que documente todo el proceso como un técnico profesional.
- El **README.md** debe incluir: entorno virtual, instalación, lista de software justificada, pruebas, incidencias y una conclusión final sobre el estado del equipo y posibles mejoras.

### Qué debes entregar
**URL del repositorio de GitHub**: Debe ser público y se dejará en la caja de comentarios de la plataforma de entrega.

### Un único archivo PDF:
**Debe contener**: Portada con tus datos, breve introducción, el enlace al repositorio de GitHub, un resumen de las decisiones clave y capturas de pantalla.
**Nomenclatura estricta**: apellido1_apellido2_nombre_TareaXX

# Ejercicio 2: Preparación y Software

## Activación de Windows

Tengo este repositorio que te trae una forma de activar Windows de manera totalmente gratuita y facil. También viene con la opción de descargar y activar Microsoft 365.

Página web: https://massgrave.dev
Repositorio: https://github.com/massgravel/Microsoft-Activation-Scripts

Ejecutamos la PowerShell como administradores y copiamos el primer código que aparece

![Activar_Win](../assets/img/20-Preparacion/Act_win1.png)

Para activar Windows solo hay que clicar el en 1 de nuestro teclado y se ejecutará un codigo pra activarlo de manera gratuita.

![Activar_Win](../assets/img/20-Preparacion/Act_win2.png)
![Activar_Win](../assets/img/20-Preparacion/Act_win3.png)
![Activar_Win](../assets/img/20-Preparacion/Act_win4.png)

## Instalación de software

Para esto vamos a usar esta otra página la cual nos permite descargar todas los softwares que queramos de una unica vez, de manera muy sencilla. Además te da una explicación de cada software y está ordenado por categorías. También viene con una opción para quitar todas las opciones que vienen por defecto en Windows 11 que consumen mucha memoria para agilizar el ordenador.

Página web: https://christitus.com/windows-tool/

Ejecutamos la PowerShell como administrador y copiamos el primer código de la web y lko ejecutamos en la PowerShell. Esto nos abre una el servicio mencionado anteriormente.

![Software](../assets/img/20-Preparacion/Software1.png)
![Software](../assets/img/20-Preparacion/Software2.png)
![Software](../assets/img/20-Preparacion/Software3.png)

### Debloat Windows
Lo primero que voy a realizar es un debloat de Windows, para quitar muchas de las opciones que hacen que el sistemas vaya más lento y que no se utilizan. Como es el caso de la telemetría o los widgets. Solo selecciono esas casillas porque son las que no comprometen al sistemas, en "Advance Tweaks" hay opciones que comprometen al SO. Para ejecutarlo solo hay que darle a "Run Tweaks" abajo a la izquierda. En "Cuustomize Preference" he dejado seleccionadas esas ya que para un oficinista va a ser lo más comodo y visual.

![Software](../assets/img/20-Preparacion/Software4.png)

### Instalación de software

#### Navegador:

- **Nombre:** Chrome
- **Función:** Navegador web
- **Motivo:** Es un buen navegador web y te da facil acceso a las herramientas de Google con las que se va a trabajar.
- **Ventajas:** Buena velociada, simple para el trabajador e integración con los servicios de Google
- **Evidencia:** ![Chrome](../assets/img/20-Preparacion/Chrome.png)

#### Utilidades básicas

- **Nombre:** Zoom
- **Función:** Video conferencias
- **Motivo:** Permite hacer video conferencias y presentar pantalla para explicar proyectos. Es una aplicación muy utilizada en oficina.
- **Ventajas:** Permite presentar pantalla para conferencias o proyectos colaborativos.
- **Evidencia:** ![Zoom](../assets/img/20-Preparacion/Zoom.png)

- **Nombre:** Telegram
- **Función:** App de mensajería
- **Motivo:** Para consultar los mensajes desde el ordenador, esta aplicación es muy utilizada.
- **Ventajas:** Buena seguridad, velocidad y simplicidad
- **Evidencia:** ![Telegram](../assets/img/20-Preparacion/Telegram.png)

- **Nombre:** Adobe Acrobat Reader
- **Función:** Visualizador de PDF
- **Motivo:** Es un buen visualizador de PDF, los cuales son muy usados en la documentación de las empresas.
- **Ventajas:** Buen visualizador e impresor de PDF, además de permitir anotación en estos mismos.
- **Evidencia:** ![Adobe_Acrobat](../assets/img/20-Preparacion/Adobe_acrobat.png)

- **Nombre:** 7-Zip
- **Función:** Compresor de archivos open-source y gratuito
- **Motivo:** Es uno de los compresores de archivos más populares debido a su posibilidad de compresión en multiples formatos, con un alto ratio de compresión.
- **Ventajas:** Open-source y gratuito, alto ratio de compresión, cifrado empresarial, compresión en practicamente todos los formatos.
- **Evidencia:** ![7-ZIP](../assets/img/20-Preparacion/7-ZIP.png)

- **Nombre:** Google Drive
- **Función:** Guardado en la nube
- **Motivo:** Como se van a utilizar las herramientas de Google, lo mejor es tener Drive para guardar los archivos.
- **Ventajas:** Perfecta integración con las herramientas que se van a utilizar.
- **Evidencia:** ![Drive](../assets/img/20-Preparacion/Drive.png)

Por último, he añadido las Gmail, Docs, Sheets y Slides como aplicaciones para tener un acceso más comodo a ellas.

![Google_apps](../assets/img/20-Preparacion/Google_apps.png)

Esta es la vista final del escritorio. He puesto un fondo básico que no molesta a la vista y el tema en oscuro para que no canse tanto la vista.

![Vista_final](../assets/img/20-Preparacion/Vista_final.png)

# Ejercicio 3: Seguridad y Pruebas

## Aplicaciones instaladas

Aplicaciones instaladas para comprobar la seguridad, mantenimiento y diagnóstico.

- **Nombre:** Recoverit
- **Función:** Recuperación de archivos borrados
- **Motivo:** Es una de las herramientas más conocidas y utilizadas  para recuperar archivos borrados en sistemas Windows.
- **Ventajas:** Se puede escanear discos duros, USB, SSD y SD o microSD. También tiene una versión portable.
- **Evidencia:** ![Recoverit](../assets/img/30-Seguridad_mantenimiento/Recoverit.png)

- **Nombre:** CPU-Z
- **Función:** Herramienta de diagnóstico, auditoría y monitorización de hardware.
- **Motivo:** Es un software gratuito y reconocido en el sector informático.
- **Ventajas:** Permite conocer las especificaciones físicas exactas del equipo sin necesidad de abrir la carcasa del ordenador. Permite diagnosticar cuellos de botella en el rendimiento.
- **Evidencia:** ![CPU-Z](../assets/img/30-Seguridad_mantenimiento/CPU-Z.png)

- **Nombre:** CCleaner (Versión gratis)
- **Función:** Herramienta de mantenimiento, limpieza de archivos temporales y optimización del sistema
- **Motivo:** Es una herramienta famosa y consolidada que permite la limpiar el cachés, historiales de todos los navegadores instalados y archivos residuales del sistema operativo.
- **Ventajas:** Ayuda a liberar espacio en el disco duro de forma rápida. Además, incluye herramientas muy prácticas para un técnico, como un gestor rápido de los programas que se inician con el sistema para mejorar los tiempos de arranque.
- **Evidencia:** ![CCleaner](../assets/img/30-Seguridad_mantenimiento/CCleaner.png)

- **Nombre:** Malwarebytes
- **Función:** Software antimalware
- **Motivo:** Es muy buena por su alta eficacia detectando amenazas modernas, especialmente ransomware, spyware y PUPs.
- **Ventajas:** Está diseñado para coexistir sin conflictos con Microsoft Defender. También, aporta una capa de seguridad extra mediante análisis exhaustivos bajo demanda, sin ralentizar el equipo.
- **Evidencia:** ![Malwarebytes](../assets/img/30-Seguridad_mantenimiento/Malwarebytes.png)

- **Nombre:** Speccy
- **Función:** Herramienta de auditoría de hardware y monitorización del sistema
- **Motivo:** Es un software de lectura rápida que muestra un resumen detallado de las especificaciones del equipo y su estado operativo en tiempo real.
- **Ventajas:** Permite al técnico revisar de un solo vistazo todos los componentes instalados en la máquina y monitorizar sensores como la temperatura. Es ideal para documentar el estado físico del equipo.
- **Evidencia:** ![Speccy](../assets/img/30-Seguridad_mantenimiento/Speccy.png)

## Comprobaciones

- Comprobación de seguridad
![Analisis_seguridad](../assets/img/30-Seguridad_mantenimiento/anlisis_seguridad.png)

- Diagnostico de hardware: pdf del diagnostico entero en doc
![Diagnostico_hardware](../assets/img/30-Seguridad_mantenimiento/diagnostico_hardware.png)

- Windows actualizado
![Windows_actualizado](../assets/img/30-Seguridad_mantenimiento/Win_act.png)

- Compresión de archivos
![Archivos_comprimidos](../assets/img/30-Seguridad_mantenimiento/compresion.png)

# Ejercicio 4: Conclusión final

El equipo ha quedado perfecto con todo el software necesario para el oficinista y para el técnico. No he tenido ningún problema durante el proceso. He dejado el sistema debloated para que vaya a la mayor velocidad posible. Además lo he modificado para que se vea agradable a la vista y que no confunda al usuario con demasiadas opciones.
Para mejorarlo se podría mirar alguna suscripción para malwarebytes si queremos aumentar la seguridad o mirar algun otro sofware de pago, pero en general ha quedado en perfectas condiciones.