# Problemas encontrados y soluciones aplicadas

En esta sección se recopilan los fallos o dificultades del proceso.  
No importa que hayan sido pequeños o grandes: lo importante es que queden bien explicados.

## Incidencia 1

- Descripción: No arranca el dispositivo y se reproducen cinco pitidos.
- Cuándo apareció: Al principio de la práctica.
- Posible causa: Problemas con la RAM, varios módulos estaban defectuosos.
- Solución aplicada: Los comprobamos uno a uno para ver cuales iban correctamente, al final solo quedó un módulo.
- Resultado: El dispositivo arranca.

## Incidencia 2

- Descripción: No se detecta el USB, por lo que no se ejecuta el Ventoy
- Cuándo apareció: En el primer arranque
- Posible causa: El Ventoy estaba mal configurado con un estilo de partición GPT en vez de MBR.
- Solución aplicada: Reconfiguramos el Ventoy.
- Resultado: Lee el USB y se ejecuta el Ventoy.

## Aprendizaje técnico

Hemos aprendido que los cinco pitidos de error junto a que no arranque el equipo significa que hay problemas con la memoria RAM. también hemos aprendido ha identificar los módulos que dan problemas para poder descartarlos.

También hemos aprendido que es muy importante la configuración del Ventoy para que el PC lo detecte.