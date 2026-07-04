# Conceito

## Um modelo tocável de máquina de fita

ziviSpaceEcho é concebido como um **instrumento musical de delay de fita**, não como uma cópia circuito-a-circuito de um equipamento histórico.

O plugin parte do fluxo de sistemas clássicos de echo de fita com múltiplas cabeças: o áudio é registrado em um caminho virtual de fita em movimento, múltiplas cabeças de reprodução leem a fita em posições diferentes, as cabeças selecionadas retornam pelo circuito de feedback e uma ramificação de reverb de mola pode ser combinada ao echo.

O resultado é um ambiente de delay performático para dub, eletrônica viva, produção experimental, desenho sonoro e coloração de mixagem.

## Uma fita, um motor, três cabeças

O princípio central é:

```text
um caminho virtual de fita
um motor virtual
uma cabeça de gravação
três cabeças de reprodução
uma ramificação paralela de reverb de mola
```

As cabeças não são tratadas como delays independentes. Seus tempos derivam de uma geometria compartilhada de fita virtual. Isso mantém o instrumento coerente ao mudar velocidade de motor, tempo manual, sincronismo por andamento ou tap tempo.

## Tempo como comportamento

ziviSpaceEcho oferece quatro modos de temporização:

| Modo | Finalidade |
|---|---|
| RE-201 Motor | Trata Repeat Rate como controle de velocidade de motor. |
| Manual ms | Faz a cabeça principal seguir um tempo explícito em milissegundos. |
| Tempo Sync | Converte divisões do andamento do host em comportamento de fita. |
| Tap Tempo | Converte gestos de performance em comportamento de fita. |

## Reverb de mola como ramificação paralela

O reverb de mola não é apenas ambiência decorativa. Ele funciona como uma ramificação paralela que pode ser combinada com cabeças de echo ou usada sozinha na posição 12.

Os controles `Dwell`, `Decay`, `Drip`, `Bounce` e `Grain` foram pensados para modelagem musical, não para simulação física estrita.

## Filosofia de interface

A interface é um painel performático estilo gabinete. Ela prioriza:

- leitura visual imediata das cabeças e do roteamento de reverb;
- controles circulares grandes;
- chaves discretas de modo e caráter;
- informação dinâmica de tempo;
- edição numérica somente com mouse.

O editor por mouse é uma decisão específica para REAPER, evitando conflitos com atalhos de teclado do host.

## O que o plugin não é

ziviSpaceEcho não é produto oficial, não é emulação licenciada e não reivindica reconstrução eletrônica circuito-a-circuito.

Nomes de produtos, marcas e referências históricas são usados apenas para contextualização musical e técnica.
