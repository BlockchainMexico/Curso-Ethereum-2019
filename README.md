# Lotería

Este contrato debe poder:
- Recibir dos dígitos hexadecimales del usuario
- Determinar a los ganadores de los diferentes premios
    - Determinar todas las direcciones que ganaron el 1er premio
        - Guardar cada dirección cuyos dígitos hexadecimales seleccionados coincidan con los del primer byte de la dirección del minero que minó el bloque en que se determinaron los ganadores del sorteo
    - Determinar todas las direcciones que ganaron el 2o premio
        - Guardar cada dirección en cuyos dígitos hexadecimales seleccionados al menos 1 coincida con la dirección del minero que minó el bloque en que se determinaron los ganadores del sorteo

## Participantes del Sorteo
---

Mínimo: 2 <br>
Máximo: Ilimitado

### Necesidades

Cada **Participante del Sorteo** debe poder:

- Elegir 2 dígitos hexadecimales