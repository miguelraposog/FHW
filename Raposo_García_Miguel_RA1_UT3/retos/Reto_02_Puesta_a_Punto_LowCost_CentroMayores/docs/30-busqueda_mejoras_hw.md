# 30 — Búsqueda y selección de mejoras de **hardware**

> **Objetivo:** Encontrar las **mejoras mínimas** que conviertan cada PC en **usable** para el centro de mayores, **respetando** S0/S1/S2.

## 1) Piezas candidatas (con enlaces y capturas)

Busca en **tiendas online españolas** (PcComponentes, Amazon ES, Coolmod, Wallapop/segunda mano con precaución) y documenta **al menos 2 opciones por categoría** (cuando aplique):

- **Almacenamiento:** SSD 2.5" (120–240 GB) o adaptadores 2.5"→3.5".
- **Memoria RAM:** módulos compatibles (capacidad y MHz soportados por tu placa).
- **Mantenimiento:** pasta térmica económica, filtros de polvo, tornillería o caddy(**adaptador/bandeja (caddy) para montar una unidad de almacenamiento** en un hueco del PC).
- **Otros (si procede):** adaptador Wi-Fi USB de bajo coste, altavoz barato si no hay sonido, etc.

**Tabla por categoría (ejemplo SSD):**

| Categoría | Marca/Modelo | Capacidad | Precio (€) | Tienda | URL | Captura |
|---|---|---:|---|---|---|
| SSD | KingDian S280 | 120 GB | 14,99 | Amazon ES | https://... | img/ssd01.png |
| SSD | Goodram CX400 | 128 GB | 16,90 | PcComponentes | https://... | img/ssd02.png |

> Guarda capturas en `../assets/img/30-hw/` con **URL completa** visible y **fecha/hora**.

## 2) Compatibilidad técnica (justifica con datos)

Para **cada pieza** elegida, justifica la **compatibilidad** con tu lote:

- **RAM:** tipo (DDR2/DDR3), voltaje (1.5 V/1.35 V), frecuencia soportada por la placa/CPU, **slots libres**.
- **SSD:** interfaz **SATA**, formato **2.5"**, bahías/adaptadores disponibles.
- **Otros:** puertos USB necesarios, espacio físico en chasis.

> Incluye captura de **fuente oficial** (manual/hoja técnica de la placa o del fabricante de la pieza) donde se vea el dato clave (ej.: “hasta 8 GB DDR2-1600”).

## 3) Mini‑estimación de impacto (sentido común + referencias)

En 3–5 líneas por categoría, explica el **impacto esperado**:

- **De HDD a SSD:** arranques/aperturas más rápidas (órdenes de magnitud).
- **De 4 GB a 8 GB RAM:** menos paginación, mejor multitarea ligera.
- **Pasta térmica/limpieza:** menos temperatura/ruido → estabilidad.

> **No** se piden benchmarks. Usa criterio y referencias de fuentes fiables.

## 4) Escenario elegido y desglose de gasto (S0/S1/S2)

Completa la tabla con tu **propuesta final** y calcula el **gasto HW** total (sin mano de obra):


| Escenario    | Pieza          | Precio (€) | Unidades | Subtotal (€) | Nota                         |
| -------------- | ---------------- | ------------: | ---------: | --------------: | ------------------------------ |
| S1           | SSD 120 GB     |       15,00 |        1 |         15,00 | 2ª mano o oferta            |
| S1           | Pasta térmica |        2,00 |        1 |          2,00 | tubo compartido entre varios |
|              |                |             |          |               |                              |
| **Total HW** |                |             |          |        **…** |                              |

Luego traslada el **Total HW** a `75-plan_presupuesto_hw_y_roi.md` para calcular costes y ROI.
