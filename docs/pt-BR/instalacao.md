# Instalação

## Requisitos

- REAPER com suporte a JSFX.
- REAPER para macOS, Windows ou Linux.
- O arquivo `ziviSpaceEcho.jsfx`.

Não é necessário instalador, gerenciador de pacotes, formato externo de plugin ou execução online.

## Instalar

1. Baixe:

```text
src/ziviSpaceEcho.jsfx
```

2. Abra o REAPER.

3. Escolha:

```text
Options → Show REAPER resource path in explorer/finder
```

4. Abra a pasta `Effects`.

5. Copie `ziviSpaceEcho.jsfx` para a pasta `Effects`.

6. Reinicie o REAPER ou atualize o navegador de efeitos.

7. Busque por:

```text
ziviSpaceEcho
```

## Atualização

Substitua o arquivo `ziviSpaceEcho.jsfx` antigo pelo novo.

Para projetos ativos, mantenha arquivos versionados quando um projeto depender de uma versão específica:

```text
src/ziviSpaceEcho_v7_6_4.jsfx
```

## Verificação

Após carregar o plugin, confirme:

- o áudio passa pelo plugin;
- a interface gráfica aparece;
- o seletor de modo muda o roteamento de cabeças/reverb;
- `Echo Cancel` cancela o ramo de efeito;
- a posição 12 funciona como reverb-only;
- o editor por mouse abre ao clicar nos valores numéricos.
