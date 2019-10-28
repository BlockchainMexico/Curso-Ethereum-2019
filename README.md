# Lotería

Este contrato debe poder:
- Recibir dos dígitos hexadecimales del usuario
- Enviar el premio de ether acumulado a los ganadores de los diferentes premios
    - Determinar todas las direcciones que ganaron el 1er premio
        - Guardar cada dirección cuyos dígitos hexadecimales seleccionados coincidan con los del primer byte de la dirección del minero que mine el bloque en que se vayan a determinar los ganadores del sorteo
            - Determinar el número del bloque en que se realizará el sorteo  
            - Comparar dígitos hexadecimales seleccionados coincidan con los del primer byte de la dirección del minero que minó el bloque de número ya determinado. Mientras no se haya minado dicho bloque
    - Enviar a todas las direcciones que ganaron el 1er premio el equivalente a dividir el 60% del premio entre el número de direcciones que ganaron el 1er premio
    - Determinar todas las direcciones que ganaron el 2o premio
        - Guardar cada dirección en cuyos dígitos hexadecimales seleccionados al menos 1 coincida con la dirección del minero que minó el bloque en que se determinaron los ganadores del sorteo

## Participantes del Sorteo
---

Mínimo: 2 <br>
Máximo: Ilimitado

### Necesidades

Cada **Participante del Sorteo** debe poder:

- Elegir 2 dígitos hexadecimales