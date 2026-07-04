# Manual completo de ziviSpaceEcho

![Interfaz principal de ziviSpaceEcho](assets/images/screenshot-main.png)

## 1. Concepto

**ziviSpaceEcho** es un instrumento musical de echo de cinta y reverberación de muelles para REAPER.

Sigue el flujo de una unidad clásica de echo de cinta con múltiples cabezales:

1. el audio entra en una etapa de preamplificación/grabación;
2. la señal se escribe en una cinta virtual en movimiento;
3. múltiples cabezales leen la cinta en posiciones diferentes;
4. los cabezales seleccionados se mezclan según el selector de modo;
5. las repeticiones se modelan por tono, filtros, edad, saturación y feedback;
6. una rama de reverb de muelles puede operar en paralelo.

## 2. Flujo de señal

```text
Entrada
  → preamplificación / drive
  → escritura en cinta virtual
  → cabezales H1 / H2 / H3
  → tono y filtros del echo
  → feedback / intensity
  → salida de echo

Entrada
  → rama de reverb de muelles
  → tono de reverb
  → salida de reverb

Echo + Reverb
  → comportamiento estéreo / salida
  → master
```

## 3. Regiones de la interfaz

![Selector de modo](assets/images/screenshot-mode-selector.png)

![Editor con mouse](assets/images/screenshot-editor.png)

## 4. Modos de tiempo

| Modo | Uso |
|---|---|
| RE-201 Motor | Gestos clásicos de velocidad de motor y ecos fuera de grilla. |
| Manual ms | Control preciso en milisegundos. |
| Tempo Sync | Divisiones sincronizadas al tempo del proyecto. |
| Tap Tempo | Entrada performática mediante toques. |

## 5. Selector de modo

| Posición | Etiqueta | Significado |
|---:|---|---|
| 1 | H1 | Cabezal 1 |
| 2 | H2 | Cabezal 2 |
| 3 | H3 | Cabezal 3 |
| 4 | H2 + H3 | Cabezales 2 y 3 |
| 5 | H1 + Rev | Cabezal 1 con reverb |
| 6 | H2 + Rev | Cabezal 2 con reverb |
| 7 | H3 + Rev | Cabezal 3 con reverb |
| 8 | H1 + H2 + Rev | Cabezales 1 y 2 con reverb |
| 9 | H2 + H3 + Rev | Cabezales 2 y 3 con reverb |
| 10 | H1 + H3 + Rev | Cabezales 1 y 3 con reverb |
| 11 | H1 + H2 + H3 + Rev | Todos los cabezales con reverb |
| 12 | Reverb Only | Solo reverb de muelles |

## 6. Cita

```text
Valentim, Victor Hugo Soares. ziviSpaceEcho. Version 7.6.4. Zenodo. https://doi.org/10.5281/zenodo.21196512
```
