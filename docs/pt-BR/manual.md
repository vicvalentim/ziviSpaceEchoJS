# Manual completo do ziviSpaceEcho

![Interface principal do ziviSpaceEcho](../assets/images/screenshot-main.png)

## 1. Conceito

**ziviSpaceEcho** é um instrumento musical de echo de fita e reverb de mola para REAPER.

Seu funcionamento segue o fluxo de uma unidade clássica de echo de fita com múltiplas cabeças:

1. o áudio entra em um estágio de pré-amplificação/gravação;
2. o sinal é escrito em uma fita virtual em movimento;
3. múltiplas cabeças de reprodução leem a fita em posições diferentes;
4. as cabeças selecionadas são mixadas pelo seletor de modo;
5. as repetições são modeladas por timbre, filtros, idade, saturação e feedback;
6. uma ramificação de reverb de mola pode operar em paralelo.

## 2. Modos de tempo

| Modo | Uso |
|---|---|
| RE-201 Motor | Gestos clássicos de velocidade de motor. |
| Manual ms | Controle preciso em milissegundos. |
| Tempo Sync | Divisões sincronizadas ao andamento do projeto. |
| Tap Tempo | Entrada performática por toque. |

## 3. Seletor de modo

| Posição | Rótulo | Significado |
|---:|---|---|
| 1 | H1 | Cabeça 1 |
| 2 | H2 | Cabeça 2 |
| 3 | H3 | Cabeça 3 |
| 4 | H2 + H3 | Cabeças 2 e 3 |
| 5 | H1 + Rev | Cabeça 1 com reverb |
| 6 | H2 + Rev | Cabeça 2 com reverb |
| 7 | H3 + Rev | Cabeça 3 com reverb |
| 8 | H1 + H2 + Rev | Cabeças 1 e 2 com reverb |
| 9 | H2 + H3 + Rev | Cabeças 2 e 3 com reverb |
| 10 | H1 + H3 + Rev | Cabeças 1 e 3 com reverb |
| 11 | H1 + H2 + H3 + Rev | Todas as cabeças com reverb |
| 12 | Reverb Only | Somente reverb de mola |

A posição 12 usa LED azul para separar visualmente o modo reverb-only dos modos de echo.

## 4. Fluxo de edição por mouse

1. Clique no valor numérico abaixo de um knob.
2. O editor modal abre.
3. Insira o valor com o teclado numérico na tela.
4. Clique em `APPLY`.

O editor evita o teclado físico porque o REAPER pode direcionar atalhos para o host.

## 5. Níveis iniciais sugeridos

```text
Intensity: 25–45%
Echo Volume: 35–55%
Reverb Volume: 15–35%
Drive: 5–20%
Noise: 0–12%
Condition: -10 a +20
Master: -6 a -3 dB
```

Aumente `Intensity` com cuidado, principalmente em tempos longos ou com múltiplas cabeças.

## 6. Citação

```text
Valentim, Victor Hugo Soares. ziviSpaceEcho. Version 7.6.4. Zenodo. https://doi.org/10.5281/zenodo.21196512
```

A assistência de IA generativa é declarada separadamente e não constitui autoria.
