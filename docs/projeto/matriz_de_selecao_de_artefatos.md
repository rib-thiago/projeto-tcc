# Matriz de Selecao de Artefatos

## 1. Objetivo

Este documento classifica os principais artefatos possiveis em quatro grupos:

- `obrigatorio`
- `recomendado`
- `opcional`
- `adiar`

Seu papel e ajudar a decidir, com criterio, quais artefatos devem existir no
projeto e quais podem ficar para fases posteriores.

## 2. Artefatos obrigatorios

### 2.1 Enquadramento e produto

- termo de abertura do projeto
- visao do produto
- declaracao de problema
- objetivos estrategicos
- criterios de sucesso
- escopo e fora de escopo
- mapa de stakeholders

### 2.2 Diagnostico

- inventario do sistema atual
- analise arquitetural `as-is`
- avaliacao da stack
- avaliacao de dependencias
- catalogo de funcionalidades existentes
- mapa de divida tecnica
- matriz `manter / adaptar / substituir / descartar`
- parecer tecnico do legado
- mapa de riscos herdados

### 2.3 Requisitos e negocio

- documento de requisitos
- regras de negocio
- requisitos nao funcionais
- casos de uso
- matriz de rastreabilidade
- criterios de aceite

### 2.4 Modelagem e arquitetura

- modelo de dominio
- modelagem `as-is`
- modelagem `to-be`
- diagrama de casos de uso
- diagrama de classes
- diagrama de sequencia
- diagrama de atividades
- C4 contexto
- C4 containers
- drivers arquiteturais
- visao arquitetural
- ADRs
- plano de evolucao arquitetural
- estrategia de integracoes externas
- matriz de alternativas

### 2.5 Governanca e execucao

- processo de software
- modelo de governanca
- politica de governanca
- plano de iteracoes
- gestao de riscos
- backlog estruturado
- definicao de pronto

### 2.6 Qualidade, seguranca e operacao

- politica de qualidade
- estrategia de testes
- matriz de verificacao
- checklist de revisao tecnica
- politica de seguranca e segredos
- modelo de ameacas
- requisitos de seguranca
- politica de dependencias e terceiros
- estrategia de configuracao por ambiente
- estrategia de ambientes
- estrategia de deploy
- estrategia de distribuicao
- observabilidade
- plano de backup e restauracao
- politica de dados, privacidade e conformidade

### 2.7 Registros e fechamento

- registro de iteracao
- conferencia de aderencia

## 3. Artefatos recomendados

- proposta de valor
- personas ou perfis operacionais
- jornadas de usuario
- mapa de capacidades
- especificacoes textuais de casos de uso
- glossario do dominio
- diagrama de estados
- diagrama de componentes
- C4 components
- 4+1
- relatorio de trade-offs
- roadmap
- plano de teste
- relatorio de testes em marcos importantes
- catalogo de evidencias
- politica de versionamento
- changelog
- avaliacao LGPD e uso de dados
- inventario de dados
- parecer de tecnologia
- relatorio de validacao do incremento
- pacote de demonstracao
- sintese executiva

## 4. Artefatos opcionais

- diagrama de pacotes
- catalogo de ADRs
- registro de decisoes nao arquiteturais
- atas de revisao ou decisao
- manual operacional
- runbook de incidentes
- politica de retencao e descarte
- catalogo de dependencias criticas
- mapa do corpo documental

## 5. Artefatos para adiar

Os artefatos abaixo podem ser adiados ate que o projeto mostre necessidade real
ou maior maturidade operacional:

- runbooks extensos sem ambiente remoto relevante
- documentacao operacional muito detalhada antes da primeira versao
  demonstravel
- formalizacoes redundantes cujo papel ja esteja adequadamente coberto por
  outros artefatos

## 6. Criterio de uso

A classificacao acima nao significa rigidez absoluta. Ela serve como ponto de
partida. A relevancia de cada artefato deve ser revisada a partir de:

- risco da decisao
- impacto arquitetural
- utilidade para defesa do TCC
- necessidade operacional
- custo de manutencao do proprio artefato
