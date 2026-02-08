# 00 — Portada

- **Alumno/a:**  Miguel Raposo García
- **Grupo:**  1º ASIR
- **Reto:** Puesta a Punto Low-Cost y Competitiva (Centro de Mayores) — **FOCO EN HARDWARE**  
- **Fecha:**  08/02/2026

# 01 — Índice

1. [Contexto y requisitos](02-contexto_y_requisitos.md)
2. [Diagnóstico inicial del lote (HW)](10-diagnostico_inicial_lote.md)
3. [Búsqueda y selección de mejoras de hardware](30-busqueda_mejoras_hw.md)
4. [Análisis de mercado y PVP](65-analisis_mercado_y_pvp.md)
5. [Presupuesto HW y ROI](75-plan_presupuesto_hw_y_roi.md)
6. [ENTREGA ÚNICA](90-ENTREGA_UNICA.md)
7. [Glosario](95-glosario.md)
8. [Checklist](99-entrega_y_checklist.md)

# 02 — Contexto y requisitos

## Qué tienes que hacer
Redacta un **resumen breve** (6–10 líneas) con el **objetivo**, **restricciones** y **criterios de éxito**.

## Guía (cómo se hace y qué poner)
- **Objetivo:** PCs **usables** (web, correo, videollamada, ofimática online) para personas mayores **vía hardware mínimo**.
- **Restricciones:** compra **20 €**; escenario **S0/S1/S2**; **no se instala software** en este reto.
- **Criterios de éxito:** mejora perceptible con gasto bajo; compatibilidad garantizada; coste total competitivo.

El objetivo principal es reacondicionar una flota de ordenadores adquiridos a bajo coste para dotar a un centro de mayores de equipos funcionales aptos para navegación web, videollamadas y ofimática en la nube.
El alcance del proyecto se limita exclusivamente a la intervención hardware evaluando tres escenarios de inversión, sin incluir instalación de sistema operativo.
El éxito del proyecto depende de lograr una mejora de rendimiento, asegurar la compatibilidad estricta de los nuevos componentes y mantener un coste total inferior al precio de mercado de equipos equivalentes.

# 10 — Diagnóstico inicial del lote

- Modelo de CPU / RAM / almacenamiento por **5 unidades muestreadas**.(NOTA-PREGUNTA POR LOS DEMAS GRUPOS para obtener estos datos - podeis verlo en sus repositorios.)
- Estado térmico (temperaturas reposo/carga breve).
- Problemas detectados (discos con sectores reasignados, ruido, etc.).


| ID Equipo     | CPU / Socket                    | RAM Instalada / Máx | Almacenamiento       | Ranuras/Bahías Libres      | Observaciones (Estado físico y térmico)                   |
| :-------------- | :-------------------------------- | :--------------------- | :--------------------- | :---------------------------- | :------------------------------------------------------------ |
| **Equipo 01** | Intel Core 2 Duo E6750 / LGA775 | 4 GB DDR2 / 8 GB     | HDD 160 GB (Samsung) | 0 slots RAM / 1 bahía 3.5" | Polvo residual y cables que podrian estar mejor gestionados |
| **Equipo 02** | Intel Core 2 Duo E6750 / LGA775 | 4 GB DDR2 / 8 GB     | HDD 160 GB (Samsung) | 0 slots RAM / 1 bahía 3.5" | Polvo residual y mala gestion de los cables internos        |
| **Equipo 03** | Intel Core 2 Duo E6750 / LGA775 | 1 GB DDR2 / 8 GB     | HDD 160 GB (Seagate) | 3 slots RAM / 1 bahía 3.5" | Fallo en pila CMOS y chasis deformado o atascado            |
| **Equipo 04** | Intel Core 2 Duo E6750 / LGA775 | 1 GB DDR2 / 8 GB     | HDD 160 GB (Seagate) | 3 slots RAM / 1 bahía 3.5" | Pasta térmica muy degradada y suciedad interna             |
| **Equipo 05** | Intel Core 2 Duo E6750 / LGA775 | 1 GB DDR2 / 8 GB     | HDD 160 GB (Seagate) | 2 slots RAM / 1 bahía 3.5" | Mucho polvo acumulado y falta antena wifi                   |

**Capturas:**
![Foto1](../assets/img/10-diagnostico/foto3.jpg)
![Foto2](../assets/img/10-diagnostico/foto6.jpg)
![Foto3](../assets/img/10-diagnostico/foto7.jpg)
![Foto4](../assets/img/10-diagnostico/cpu.jpeg)


# 30 — Búsqueda y selección de mejoras de **hardware**

> **Objetivo:** Encontrar las **mejoras mínimas** que conviertan cada PC en **usable** para el centro de mayores, **respetando** S0/S1/S2.

## 1) Piezas candidatas (con enlaces y capturas)

Busca en **tiendas online españolas** (PcComponentes, Amazon ES, Coolmod, Wallapop/segunda mano con precaución) y documenta **al menos 2 opciones por categoría** (cuando aplique):

- **Almacenamiento:** SSD 2.5" (120–240 GB) o adaptadores 2.5"→3.5".
- **Memoria RAM:** módulos compatibles (capacidad y MHz soportados por tu placa).
- **Mantenimiento:** pasta térmica económica, filtros de polvo, tornillería o caddy(**adaptador/bandeja (caddy) para montar una unidad de almacenamiento** en un hueco del PC).
- **Otros (si procede):** adaptador Wi-Fi USB de bajo coste, altavoz barato si no hay sonido, etc.

### Almacenamiento (SSD 2.5" SATA)

| Categoría | Marca/Modelo | Capacidad | Precio (€) | Tienda | URL | Captura |
|---|---|---|---|---|---|---|
| SSD | Hikvision Digital | 120 GB | 22,55 | Amazon ES | https://www.amazon.es/Hikvision-Digital-Technology-HS-SSD-C100-120G/dp/B07F9PXTBG/ref=sr_1_4?adgrpid=52058013090&dib=eyJ2IjoiMSJ9.SpPkr6SgtSE4prOx3EPHqBzOhkIFxXvx8N6JiRGIhp9RokH2X8eec9cX3BbEPGBvukD1efU0RM8CCqpfmJWIA9uIzoG1YDmE8r_m0oEgmlNE4dSsWOo5Qs03b0FX7D9AaJrLooCF3Z5zP5n8ZJm9_MevDddenufRf7XNb3Xh0iDTT39omrFhDF0sCZUdanSiRiuAMpsfmI3cwzBCLrksNNucALJk5D4kaBUt16BR4N-Gs6I0D9khlzgVywAIy4Mv-RoCpHQEkrhe3PinAWMe3-6A2LLHZ7ewajv14FHT5MA.7H1D1fS4qnqt61lyfWopJmJmQ10CIvf7cqE4Pbzb56E&dib_tag=se&hvadid=601314682948&hvdev=c&hvexpln=0&hvlocphy=9208723&hvnetw=g&hvocijid=13356261423045380000--&hvqmt=b&hvrand=13356261423045380000&hvtargid=kwd-506959462530&hydadcr=23167_2231449&keywords=ssd%2Bsata%2B2.5%2B120gb&mcid=d7ae5352a32039af98060879ffe380f9&qid=1770576254&sr=8-4&th=1| ![SSD1](../assets/img/30-hw/SSD1.png) |
| SSD | Silicon Power | 128 GB | 29,99 | Amazon ES | https://www.amazon.es/Silicon-Power-GB-SSD-Performance-Interna/dp/B07KR25Q72/ref=sr_1_11?adgrpid=52058013090&dib=eyJ2IjoiMSJ9.SpPkr6SgtSE4prOx3EPHqBzOhkIFxXvx8N6JiRGIhp9RokH2X8eec9cX3BbEPGBvukD1efU0RM8CCqpfmJWIA9uIzoG1YDmE8r_m0oEgmlNE4dSsWOo5Qs03b0FX7D9AaJrLooCF3Z5zP5n8ZJm9_MevDddenufRf7XNb3Xh0iDTT39omrFhDF0sCZUdanSiRiuAMpsfmI3cwzBCLrksNNucALJk5D4kaBUt16BR4N-Gs6I0D9khlzgVywAIy4Mv-RoCpHQEkrhe3PinAWMe3-6A2LLHZ7ewajv14FHT5MA.7H1D1fS4qnqt61lyfWopJmJmQ10CIvf7cqE4Pbzb56E&dib_tag=se&hvadid=601314682948&hvdev=c&hvexpln=0&hvlocphy=9208723&hvnetw=g&hvocijid=13356261423045380000--&hvqmt=b&hvrand=13356261423045380000&hvtargid=kwd-506959462530&hydadcr=23167_2231449&keywords=ssd%2Bsata%2B2.5%2B120gb&mcid=d7ae5352a32039af98060879ffe380f9&qid=1770576426&sr=8-11&th=1 | ![SSD2](../assets/img/30-hw/SSD2.png) |

### Mantenimiento y pasta térmica

| Categoría     | Marca/Modelo                  | Contenido | Precio (€) | Tienda        | URL                                             | Captura             |
|---------------|-------------------------------|-----------:|-----------:|---------------|-------------------------------------------------|---------------------|
| Pasta térmica | Temperst Zero II              | 1 g        | 1,98       | PcComponentes | https://www.pccomponentes.com/tempest-zero-ii-pasta-termica-1g-62w-mk     |  ![Tempest](../assets/img/30-hw/pasta1.png)|
| Pasta térmica | Arctic MX-4 4 g               | 4 g        | 7,09       | PcComponentes | https://www.pccomponentes.com/arctic-mx-4-pasta-termica-4-gramos     |  ![Artic](../assets/img/30-hw/pasta2.png)|


## 2) Compatibilidad técnica

Para **cada pieza** elegida, justifica la **compatibilidad** con tu lote:

- **SSD:**  Están en formato 2.5" y utilizan **interfaz SATA III retrocompatible con SATA II**, por lo que se pueden utilizar en bahías libres o con adaptador de 2.5" a 3.5". Las placas estándar de sobremesa con puertos SATA admiten sin problema estos SSD.
- **Pasta térmica:** Es compatible con **cualquier disipador y CPU de sobremesa estándar**, aplicándose entre el procesador y su disipador para mejorar transferencia de calor y disminuir temperaturas.

## 3) Mini‑estimación de impacto (sentido común + referencias)

- **SSD 120 GB:** Cambiar el HDD por un SSD es como asfaltar una carretera de tierra: los datos viajan mucho más rápido. El PC no tendrá más "potencia bruta", pero todo el tráfico de información (abrir Chrome, arrancar Windows) volará.

- **Mantenimiento:** Funciona como el cambio de aceite en un coche. No hace que el motor corra más, pero evita que se queme y asegura que el viaje sea suave y sin ruidos molestos.

## 4) Escenario elegido y desglose de gasto

Se elige el Escenario S2 (Upgrade ligero). Aunque el objetivo ideal era el S1, el precio de mercado actual de los SSDs nuevos disponibles (aprox. 22 €) y la necesidad de mantenimiento térmico sitúan la inversión por encima de los 15 €, pero cumpliendo holgadamente el tope de 30 €.


| Escenario    | Pieza                      | Precio (€) | Unidades | Subtotal (€) | Nota                            |
| :------------- | :--------------------------- | :-----------: | :--------: | :-------------: | :-------------------------------- |
| **S2**       | SSD Hikvision Digital 120GB       |    22,55    |    1    |     22,55     | Opción más económica listada           |
| **S2**       | Pasta térmica Tempest (1g) |    1,98    |    1    |     1,98     | Monodosis (coste completo)      |
|              |                            |             |         |               |                                 |
| **Total HW** | **Coste por Unidad**       |             |         | **24,53 €** | **Objetivo cumplido (≤ 30€)** |

# 30 — Instalación y post‑instalación

- Pasos de instalación (resumen).
- Paquetes esenciales (navegador, ofimática online, codecs).
- Usuarios/contraseñas y políticas de actualización.

**Capturas:** `../assets/img/30-postinstalacion/`

# 30 — Instalación y post‑instalación

## 1. Resumen de Pasos de Instalación

Se ha procedido a realizar una instalación limpia ("Clean Install") para aprovechar el rendimiento del nuevo SSD, eliminando cualquier rastro de datos anteriores.

1. **Creación del medio:** Se utilizó la herramienta **Rufus** para crear un USB booteable con la imagen ISO del sistema operativo (Linux Mint XFCE).
2. **BIOS/Boot:** Se configuró la BIOS para arrancar desde USB (Legacy/CSM habilitado).
3. **Particionado:** Se eliminaron todas las particiones existentes en el disco para asegurar una instalación limpia en el espacio no asignado del nuevo SSD.
4. **OOBE (Configuración inicial):** Se realizó la configuración sin conexión a internet inicial para crear una cuenta local y evitar la vinculación obligatoria con cuentas de correo, simplificando el acceso.

## 2. Paquetes y Software Esencial

Dado que el uso será **navegación y ofimática online**, se ha instalado un set de aplicaciones ligero y funcional.

* **Navegador Web:** **Firefox**.
* **Ofimática Online:** Accesos directos en el escritorio a **Google Docs** y **Google Sheets** (o Office Online). No se instala suite pesada localmente para ahorrar espacio y recursos.
* **Multimedia:** **VLC Media Player**.
* **Comunicación:** **Zoom** y **Skype** para las videollamadas con familiares.
* **Visor PDF:** Adobe Acrobat Reader.

## 3. Usuarios, Contraseñas y Políticas

### Gestión de Usuarios

* **Creación de usuario:** Se ha creado un usuario con una contraseña recordable para el usuario.
* **Sistema Operativo:** Actualizaciones automáticas activadas pero programadas para horas nocturnas para no interrumpir las actividades del centro.
* **Navegador:** Actualización automática en segundo plano.


# 65 — Análisis de mercado y PVP

## Comparables (3 mínimos)
| Plataforma | Enlace | Captura | Precio (€) | Especificación | Fecha/Hora |
|---|---|---|---:|---|---|
| Wallapop  |https://es.wallapop.com/item/ordenador-1228020580   |![Foto1](../assets/img/65-mercado/PC1.png)   | 30  |Ordenador de sobremesa para oficina. Sus especificaciones son: Intel Core 2 Duo E7300 2 cores x 2.6Ghz Memoria RAM 2048MB DDR2 667MHz 160 GB SATA Regrabadora DVD±RW Interna Tarjeta de red Broadcom 5787 Gigabit 100/1000MB   | 2026‑02‑08 20:30  |
| Wallapop  | https://es.wallapop.com/item/ordenador-hp-negro-oficina-1221586149  |![Foto2](../assets/img/65-mercado/PC2.png)   | 36  |Ordenador de sobremesa sencillo HP en color negro, ideal para tareas de ofimática. -Lectora de discos DVD -Mantenimiento realizado recientemente -Windows 10 recién instalado -Desperfectos estéticos visibles en las dos últimas imágenes | 2026‑02‑08 20:30  |
| Wallapop  | https://es.wallapop.com/item/pc-da-ufficio-kraun-grigio-1225512519  |![Foto3](../assets/img/65-mercado/PC3.png)   | 40  |Un ordenador de escritorio para la oficina. - Alimentador Kraun. - Tarjeta madre. - Disco duro. - Caja gris| 2026‑02‑08 20:30  |

## PVP objetivo
- Media precios comparables: 35 €  
- Margen de competitividad: 15 %  
- **PVP objetivo:** 60 €

# 75 — Plan de presupuesto (HW) y ROI

> Tras decidir **S0/S1/S2** en `30-busqueda_mejoras_hw.md`, completa costes y ROI.

- **Tarifa interna (€/h):** 10,00 €/h (Técnico Junior)
- **Horas por equipo:** 45 min: montaje, limpieza y testeo


| Escenario         | Gasto HW (€) | Horas | Tarifa (€/h) | **Coste total (€)** | **PVP objetivo (€)** | **ROI (%)** | ¿Competitivo?                                            |
| :------------------ | :-------------: | :-----: | :-------------: | :--------------------: | :---------------------: | :-----------: | :---------------------------------------------------------- |
| **S0** (Limpieza) |     0,00     | 0,50 |     10,00     |     **25,00 €**     |       35,00 €       |     40%     | **No.** ROI alto pero producto obsoleto (lento).          |
| **S1** (Micro)    |    ~15,00    | 0,75 |     10,00     |     **42,50 €**     |       50,00 €       |     17%     | **Difícil.** No se encontraron piezas fiables por <15€. |
| **S2** (Elegido)  |   **24,53**   | 0,75 |     10,00     |     **52,03 €**     |     **60,00 €**     |  **15,3%**  | **SÍ.** Producto "Premium" con SSD nuevo.                |

## Fórmulas y Cálculos

### 1. Coste Total

El coste unitario real de producción incluye la compra del equipo, las piezas nuevas y el tiempo de trabajo (45 minutos a 10 €/hora)
Coste = 20 € (Base PC) + 24,53 € (SSD + Pasta) + 7,50 € (Mano de obra)
Coste Final = 52,03 €

### 2. ROI (Retorno de Inversión)

Calculamos la rentabilidad vendiendo el equipo a 60 €. Se justifica este PVP frente a los 35 € de la competencia porque nuestro equipo incluye un SSD nuevo, lo que garantiza velocidad.
ROI = ((PVP - Coste Total) / Coste Total) * 100
ROI = ((60,00 - 52,03) / 52,03) * 100
ROI = 15,3 %

**Elección final y motivos:**

**Se elige el Escenario S2 (Upgrade Ligero).**

* **Viabilidad Técnica:** Es la única opción que cumple con el requisito de "usabilidad" para un centro de mayores. Mantener el disco mecánico habría resultado en quejas por lentitud, incumpliendo el objetivo del proyecto.
* **Viabilidad Económica:** Aunque el coste total sube a **52 €**, el valor percibido del equipo aumenta drásticamente gracias al SSD. Esto nos permite fijar un PVP de **60 €**, obteniendo un beneficio del **15%** y entregando un producto superior al que se vende en Wallapop.
