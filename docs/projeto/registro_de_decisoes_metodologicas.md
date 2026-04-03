# Registro de Decisoes Metodologicas

## 1. Objetivo

Este documento registra decisoes metodologicas, de governanca e de conducao do
projeto que nao sao propriamente ADRs arquiteturais, mas que merecem trilha
historica explicita.

Ele existe para evitar que decisoes importantes sobre processo, backlog,
documentacao, cronograma e forma de trabalho fiquem apenas diluidas em issues,
commits ou memoria conversacional.

## 2. Quando registrar uma decisao aqui

Registrar quando a decisao:

- altera a forma oficial de trabalho
- redefine escopo metodologico ou estatuto de artefatos
- altera o cronograma macro ou a logica de iteracoes
- estabelece regra de governanca, rastreabilidade ou revisao
- nao se encaixa bem como ADR arquitetural

## 3. Estrutura sugerida para cada registro

### DM-XXX - Titulo da decisao

- data:
- status:
- contexto:
- decisao:
- justificativa:
- impactos esperados:
- artefatos impactados:
- observacoes posteriores:

## 4. Registros iniciais

### DM-001 - Adocao de processo iterativo e incremental orientado a riscos

- data: 2026-04-01
- status: aceita
- contexto: o projeto precisava de uma base metodologica mais profissional do
  que uma simples continuidade do trabalho anterior
- decisao: adotar processo iterativo e incremental, orientado a riscos,
  centrado em arquitetura, diagnostico e governanca de produto, inspirado no
  Unified Process e operacionalizado com Git e GitHub
- justificativa: essa abordagem preserva defensabilidade academica sem impor o
  peso excessivo de um RUP estrito para projeto individual
- impactos esperados:
  - fortalecimento da rastreabilidade
  - maior centralidade da arquitetura e da governanca
  - melhor articulacao entre processo, backlog e documentacao
- artefatos impactados:
  - `docs/projeto/processo_de_software.md`
  - `docs/projeto/fases_do_processo.md`
- observacoes posteriores:
  - nada registrado ate o momento

### DM-002 - Separacao entre documentos estruturais, operacionais e temporais

- data: 2026-04-02
- status: aceita
- contexto: o bloco metodologico passou a conter documentos com papeis muito
  diferentes, e havia risco de sobreposicao entre eles
- decisao: distinguir documentos estruturais, guias operacionais, cronograma
  macro e modelos reutilizaveis
- justificativa: a separacao melhora navegacao, reduz redundancia e esclarece o
  estatuto semantico de cada artefato
- impactos esperados:
  - mais clareza sobre o papel de cada documento
  - reducao de confusao entre planejamento temporal e guia operativo
- artefatos impactados:
  - `docs/projeto/processo_de_software.md`
  - `docs/projeto/plano_operacional_do_processo.md`
  - `docs/projeto/cronograma_macro_da_fundacao.md`
  - `docs/projeto/modelo_plano_de_iteracao.md`
- observacoes posteriores:
  - nada registrado ate o momento
