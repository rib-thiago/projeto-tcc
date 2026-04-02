# Cronograma Macro da Fundacao

## 1. Objetivo

Este documento organiza a milestone `M1 - Fundacao do Produto e Processo` em
janelas de trabalho com foco dominante. Seu papel nao e impor uma cascata
rigida, mas oferecer orientacao temporal para a execucao da fundacao
metodologica do projeto.

O cronograma deve ser lido como planejamento por predominancia de fase. Isso
significa que uma janela pode exigir retornos pontuais a fases anteriores,
desde que o foco dominante da rodada permaneca claro.

A ordem logica de producao dos artefatos permanece documentada em
`docs/projeto/sequencia_de_producao_por_fase.md`. Este cronograma acrescenta a
camada temporal da milestone atual, sem substituir a logica estrutural do
processo.

## 2. Horizonte da milestone

- inicio considerado: 2026-04-01
- horizonte inicial da milestone: 2026-04-15
- principio de organizacao: janelas curtas com foco dominante e revisitas
  controladas quando houver descoberta relevante
- natureza do cronograma: hipotese inicial de distribuicao temporal, sujeita a
  redistribuicao conforme a densidade real de cada frente revisada

## 3. Janelas de trabalho propostas

### 3.1 Janela 1 - Estruturacao do processo

Periodo sugerido:

- 2026-04-01 a 2026-04-03

Fase predominante:

- governanca minima de fundacao
- consolidacao do bloco estrutural do processo

Issue principal associada:

- issue `#1` - revisar criticamente as fases do processo de software

Artefatos dominantes:

- `fases_do_processo.md`
- `processo_de_software.md`
- `sequencia_de_producao_por_fase.md`
- `plano_operacional_do_processo.md`

Entregas esperadas da janela:

- revisao de `fases_do_processo.md`
- revisao de `processo_de_software.md`
- revisao de `sequencia_de_producao_por_fase.md`
- criacao de `plano_operacional_do_processo.md`
- checagem final da coerencia do bloco metodologico inicial

Riscos da janela:

- encerrar a issue `#1` cedo demais
- manter contradicoes sutis entre documentos estruturais
- fechar a janela sem criterio claro de aceite

Sinais de replanejamento:

- necessidade de reabrir escopo central das fases
- contradicoes relevantes entre processo, sequencia e plano operacional
- falta de base para decidir o encerramento responsavel da issue `#1`

### 3.2 Janela 2 - Artefatos e estrutura documental

Periodo sugerido:

- 2026-04-04 a 2026-04-09

Fase predominante:

- consolidacao do corpo de artefatos do processo
- revisao da estrutura documental do repositorio

Issues principais associadas:

- issue `#2` - revisar criticamente a matriz de selecao de artefatos
- issue `#5` - revisar a estrutura documental inicial do repositorio

Artefatos dominantes:

- `catalogo_de_artefatos.md`
- `matriz_de_selecao_de_artefatos.md`
- estrutura documental inicial do repositorio

Entregas esperadas da janela:

- revisao de `catalogo_de_artefatos.md`
- revisao de `matriz_de_selecao_de_artefatos.md`
- revisao da arvore documental e do estatuto dos documentos
- alinhamento entre artefatos selecionados e sequencia de producao por fase

Riscos da janela:

- subestimar a densidade da selecao de artefatos
- criar redundancia documental sem perceber
- perder coerencia entre artefatos selecionados e fases do processo

Sinais de replanejamento:

- ampliacao relevante da lista de artefatos obrigatorios
- necessidade de redesenhar parte importante da arvore documental
- identificacao de sobreposicoes fortes entre artefatos inicialmente aceitos

### 3.3 Janela 3 - Politicas fundacionais

Periodo sugerido:

- 2026-04-10 a 2026-04-12

Fase predominante:

- politicas fundacionais e governanca evoluida

Issue principal associada:

- issue `#3` - definir conjunto inicial de politicas fundacionais

Artefatos dominantes:

- lista priorizada de politicas fundacionais
- estrutura inicial do bloco normativo do projeto

Entregas esperadas da janela:

- lista priorizada de politicas
- ordem sugerida de escrita
- relacao entre politicas minimas, politicas amadurecidas e dependencias
  arquiteturais

Riscos da janela:

- tentar escrever politicas demais cedo demais
- confundir politica provisoria com politica amadurecida
- perder a ligacao entre politica e decisao arquitetural real

Sinais de replanejamento:

- dependencia forte de decisoes operacionais ainda nao tomadas
- necessidade de antecipar ou adiar politicas por falta de base tecnica
- identificacao de lacunas graves no nucleo normativo esperado

### 3.4 Janela 4 - Bloco operacional inicial

Periodo sugerido:

- 2026-04-13 a 2026-04-15

Fase predominante:

- descoberta de produto e contexto operacional
- consolidacao da estrategia operacional minima do MVP

Issues principais associadas:

- issue `#4` - definir estrategia operacional minima do MVP
- issue `#6` - definir papel da Web minima e da CLI na fundacao do projeto

Artefatos dominantes:

- direcao inicial de ambientes, deploy e distribuicao
- definicao do papel da CLI e da Web minima
- criterios de MVP operacionalmente aceitavel
- requisitos minimos de operacao, segredos, logs, backup e tratamento de
  falhas externas

Entregas esperadas da janela:

- direcao inicial sobre ambientes, deploy e distribuicao
- definicao do papel da CLI e da Web minima
- criterios de MVP operacionalmente aceitavel
- definicao minima sobre segredos, logging, backup e falhas externas
- revisao final de coerencia da milestone `M1`

Riscos da janela:

- definir operacao com base insuficiente
- ampliar escopo operacional acima do necessario para a fundacao
- deixar ambigua a diferenca entre MVP funcional e MVP operacional

Sinais de replanejamento:

- necessidade de retorno forte a arquitetura ou politicas
- indefinicao persistente sobre CLI, Web minima ou ambientes
- falta de base para consolidar um MVP operacional aceitavel

## 4. Regras de uso do cronograma

- o cronograma orienta foco dominante, nao exclusividade absoluta de fase
- revisitas a modelagem, arquitetura, requisitos ou politicas sao aceitaveis
  quando houver descoberta legitima
- mudancas relevantes de foco devem ser registradas no backlog e nos documentos
  impactados
- se uma janela nao fechar completamente, o replanejamento deve preservar a
  logica de prioridades, nao apenas empurrar datas
- a redistribuicao de tempo entre janelas e parte esperada da governanca do
  processo, e nao sinal automatico de falha
