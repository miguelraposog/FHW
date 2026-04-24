# Ficha · Preparación del USB con Ventoy

## 1. Datos básicos del pendrive

- Marca y modelo: PHILIPS FM32FD165B
- Capacidad: 32GB
- Sistema desde el que se preparó: Win11

## 2. Preparación de Ventoy

- Programa utilizado: ventoy
- Versión de Ventoy: 1.1.11
- Pasos seguidos para instalar Ventoy en el USB:
  1. Abrir el archivo Ventoy2Disk.exe
  2. Seleccionar el USB que vas a formatear para instalarle el Ventoy
  3. Configurar el particionado a MBR, hay que meterse en Opcion -> Partition Style -> MBR
  4. Configuarar la configurarción del particionad, hay que meterse en Opción -> Partition Configuration -> File System (exFAT), Cluster Size (System Default Value), Align partition with 4KB
  5. Clickas en Install, para instalar el ventoy en el USB. Hay que tener cuidado ya que este rpoceso formatea el USB por lo que hay que guardar los datos en caso de qwue contenga alguno importante.
  6. Meter las ISOs dentro del fichero del USB que ahora se llama Ventoy.

## 3. Precauciones tomadas

- ¿Se comprobó que el USB correcto era el seleccionado? Sí
- ¿Se hizo copia de seguridad de los datos del pendrive antes de formatearlo? Sí
- ¿Se verificó que Ventoy quedó instalado correctamente? Sí

## 4. Evidencias

- Captura o foto del proceso de instalación de Ventoy: 
![Instalación](../../../assets/img/10-ventoy_preparado/Instalación_ventoy.png)
![Estilo de partición](../../../assets/img/10-ventoy_preparado/Partition_Style.png)
![Configuración de partición](../../../assets/img/10-ventoy_preparado/Partition_Configuration.png)
- Captura o foto del contenido del USB ya preparado:
![Contenido](../../../assets/img/10-ventoy_preparado/Contenido.png)
- Observaciones:

## 5. Valoración

Explica brevemente si la preparación del USB fue sencilla o si surgió alguna dificultad.

Es bastante sencillo, solo tienes que fijarte bien en todo y tener muy en cuenta el equipo en el que lo vas a usar.