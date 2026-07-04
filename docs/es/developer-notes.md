# Notas de desarrollo

## Formato

ziviSpaceEcho está escrito como efecto JSFX para REAPER, usando sintaxis EEL2.

Archivo principal:

```text
src/ziviSpaceEcho.jsfx
```

Archivo versionado actual:

```text
src/ziviSpaceEcho_v7_6_4.jsfx
```

## Organización

El plugin se organiza en:

- `@init`;
- `@slider`;
- `@block`;
- `@sample`;
- `@gfx`.

## Ideas centrales de DSP

- una cinta virtual;
- un motor virtual;
- múltiples cabezales de lectura;
- rama paralela de reverberación de muelles;
- filtros y tonos separados para echo y reverb;
- protección de memoria y tiempo;
- control final de salida.
