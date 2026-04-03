# Sequencia de Producao por Fase

## 1. Objetivo

Este documento organiza a ordem logica de producao dos artefatos do projeto,
indicando o que nasce primeiro, o que depende do que, o que pode ser produzido
em paralelo e o que faz mais sentido em fases posteriores.

## 2. Fase 1 - Enquadramento e mandato

Produzir primeiro:

- termo de abertura do projeto
- visao do produto
- declaracao de problema
- objetivos estrategicos
- criterios de sucesso
- escopo e fora de escopo
- mapa de stakeholders
- mapa inicial de riscos

Pode ser produzido em paralelo:

- proposta de valor
- personas
- jornadas
- mapa de capacidades

## 3. Fase 2 - Governanca minima de fundacao

Produzir primeiro:

- estrutura inicial de backlog
- milestone inicial
- project board inicial
- convencao minima de fluxo de trabalho
- rastreabilidade minima entre issue, branch e PR
- organizacao inicial do repositorio
- estrutura inicial documental
- definicao provisoria de pronto
- gestao inicial de riscos

## 4. Fase 3 - Diagnostico do estado atual

Produzir primeiro:

- inventario do sistema atual
- catalogo de funcionalidades existentes
- analise arquitetural `as-is`
- avaliacao da stack
- avaliacao de dependencias
- mapa de divida tecnica
- mapa de riscos herdados

Depois consolidar:

- matriz `manter / adaptar / substituir / descartar`
- parecer tecnico do legado
- modelagem `as-is`
- conferencia de aderencia

Pode ser produzido em paralelo:

- diagramas `as-is`
- inventario de dados
- avaliacao inicial de seguranca

## 5. Fase 4 - Descoberta de produto e contexto operacional

Nesta fase predominam artefatos exploratorios e de enquadramento operacional.

Produzir primeiro:

- proposta de valor
- perfis operacionais
- jornadas
- mapa de capacidades
- hipoteses sobre CLI, Web, execucao local e remota
- hipoteses sobre distribuicao e operacao minima

## 6. Fase 5 - Engenharia de requisitos e regras de negocio

Nesta fase predominam artefatos formais e rastreaveis.

Produzir primeiro:

- documento de requisitos
- regras de negocio
- requisitos nao funcionais
- criterios de aceite
- glossario do dominio

Depois:

- casos de uso
- especificacoes textuais dos casos prioritarios
- matriz de rastreabilidade

## 7. Fase 6 - Modelagem e avaliacao de alternativas

Produzir primeiro:

- modelo de dominio
- diagrama de casos de uso
- consolidacao e refinamento da modelagem `as-is`
- producao da modelagem `to-be`

Depois:

- diagrama de classes
- diagrama de sequencia
- diagrama de atividades
- C4 contexto
- C4 containers
- matrizes comparativas de alternativas

Mais tarde, se necessario:

- C4 components
- diagrama de componentes
- diagrama de estados
- diagrama de pacotes
- 4+1 consolidado

## 8. Fase 7 - Arquitetura e decisao

Produzir primeiro:

- drivers arquiteturais
- visao arquitetural
- matriz de alternativas
- estrategia de integracoes externas
- plano de evolucao arquitetural

Depois:

- ADRs
- relatorio de trade-offs
- mapa de modulos
- arquitetura `to-be` consolidada

## 9. Fase 8 - Politicas fundacionais e governanca evoluida

Produzir primeiro:

- revisao e consolidacao do processo de software
- modelo de governanca
- politica de governanca
- definicao de pronto amadurecida
- plano de iteracoes
- backlog estruturado
- gestao de riscos consolidada

Depois, em bloco normativo:

- politica de Git e PRs
- politica de qualidade
- politica de testes
- politica de documentacao e modelagem
- politica de decisoes arquiteturais
- politica de seguranca e segredos
- politica de dependencias e terceiros
- politica de configuracao por ambiente
- politica de deploy e distribuicao
- politica de dados e conformidade
- politica de backup e restauracao

## 10. Fase 9 - Construcao e validacao

Produzir continuamente:

- registros de iteracao
- checklists de revisao
- evidencias de teste
- atualizacao de modelos e documentos
- relatorios de validacao do incremento em marcos maiores

Entregas esperadas do primeiro incremento:

- implementacao do incremento vertical inicial
- CLI funcional
- Web minima funcional

## 11. Fase 10 - Transicao e defesa

Produzir primeiro:

- pacote de demonstracao
- sintese executiva das frentes
- conferencia final de aderencia
- validacao do MVP operacional
- entrega operacional minima documentada
- relatorio de trade-offs do projeto
- material de defesa

Depois:

- roadmap revisado
- plano de evolucao futura
- manual operacional refinado
- changelog consolidado

## 12. Ordem logica geral

Se sintetizada, a ordem logica geral fica assim:

1. enquadramento
2. governanca minima de fundacao
3. diagnostico
4. descoberta de produto e contexto operacional
5. requisitos e regras de negocio
6. modelagem e avaliacao de alternativas
7. arquitetura e decisao
8. politicas fundacionais e governanca evoluida
9. construcao e validacao
10. transicao e defesa
