# Concepto

<figure class="zivi-figure">
  <img src="../../assets/images/screenshot-main.png" alt="Interfaz principal de ziviSpaceEcho">
  <figcaption>El plugin se organiza como un gabinete de performance: selección de modo, temporización, comportamiento de cinta, reverb de muelles y salida permanecen visibles en conjunto.</figcaption>
</figure>

## Un modelo tocable de máquina de cinta

ziviSpaceEcho está diseñado como un **instrumento musical de delay de cinta**, no como una copia circuito por circuito de un equipo histórico.

El plugin toma como referencia el flujo de sistemas clásicos de echo de cinta con múltiples cabezales: el audio se registra en una cinta virtual en movimiento, varios cabezales de reproducción leen la cinta en distintas posiciones, los cabezales seleccionados vuelven por feedback y una rama de reverberación de muelles puede combinarse con el echo.

## Una cinta, un motor, tres cabezales

El principio central es:

```text
una ruta virtual de cinta
un motor virtual
un cabezal de grabación
tres cabezales de reproducción
una rama paralela de reverberación de muelles
```

Los cabezales no son delays independientes. Sus tiempos derivan de una geometría compartida de cinta virtual.

## Tiempo como comportamiento

| Modo | Finalidad | Resultado musical |
|---|---|---|
| RE-201 Motor | Trata Repeat Rate como control de velocidad de motor. | Gestual y cercano a una lógica de hardware. |
| Manual ms | Hace que el cabezal principal siga un tiempo explícito en ms. | Preciso y repetible. |
| Tempo Sync | Convierte divisiones del tempo del host en comportamiento de cinta. | Compatible con producción en grilla. |
| Tap Tempo | Convierte gestos de performance en comportamiento de cinta. | Tiempo corporal y performático. |

## Reverb de muelles

La reverberación de muelles funciona como una rama paralela. Puede combinarse con los cabezales o usarse sola en la posición 12.

## Lo que no es

ziviSpaceEcho no es un producto oficial, no es una emulación licenciada y no afirma reconstrucción electrónica circuito por circuito.
