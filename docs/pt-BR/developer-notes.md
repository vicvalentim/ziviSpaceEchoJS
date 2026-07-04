# Notas de desenvolvimento

## Formato

ziviSpaceEcho é escrito como efeito JSFX para REAPER, usando sintaxe EEL2.

Arquivo principal:

```text
src/ziviSpaceEcho.jsfx
```

Arquivo versionado da versão arquivada atual:

```text
src/ziviSpaceEcho_v7_6_4.jsfx
```

## Organização

O plugin se organiza em:

- `@init`;
- `@slider`;
- `@block`;
- `@sample`;
- `@gfx`.

## Ideias centrais de DSP

- uma fita virtual;
- um motor virtual;
- múltiplas cabeças de leitura;
- ramificação paralela de reverb de mola;
- filtros e timbres separados para echo e reverb;
- proteção de memória e tempo;
- controle final de saída.

## Checklist de release

- [ ] Plugin carrega no REAPER.
- [ ] Áudio passa pelo plugin.
- [ ] Modos de echo funcionam.
- [ ] Reverb-only funciona.
- [ ] Editor por mouse aplica valores.
- [ ] Controles nativos seguem disponíveis.
- [ ] Versão do JSFX principal atualizada.
- [ ] Arquivo JSFX versionado atualizado.
- [ ] README atualizado.
- [ ] Documentação atualizada.
- [ ] CITATION.cff atualizado.
- [ ] Metadados Zenodo atualizados.
- [ ] Declaração de IA permanece correta.
