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

## 3. Fase 2 - Diagnostico do estado atual

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

## 4. Fase 3 - Descoberta de produto e requisitos

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

Pode ser produzido em paralelo:

- jornadas refinadas
- perfis operacionais refinados
- mapa de capacidades

## 5. Fase 4 - Modelagem

Produzir primeiro:

- modelo de dominio
- diagrama de casos de uso
- modelagem `as-is`
- modelagem `to-be`

Depois:

- diagrama de classes
- diagrama de sequencia
- diagrama de atividades
- C4 contexto
- C4 containers

Mais tarde, se necessario:

- C4 components
- diagrama de componentes
- diagrama de estados
- diagrama de pacotes
- 4+1 consolidado

## 6. Fase 5 - Arquitetura e decisao

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

## 7. Fase 6 - Governanca e politicas

Produzir primeiro:

- processo de software
- modelo de governanca
- politica de governanca
- definicao de pronto
- plano de iteracoes
- backlog estruturado
- gestao de riscos

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

## 8. Fase 7 - Qualidade, seguranca e operacao

Produzir primeiro:

- estrategia de testes
- matriz de verificacao
- politica de qualidade
- politica de seguranca e segredos
- modelo de ameacas
- requisitos de seguranca
- estrategia de ambientes
- estrategia de configuracao por ambiente
- estrategia de deploy
- estrategia de distribuicao
- observabilidade
- plano de backup e restauracao

Depois:

- manual operacional
- politica de retencao e descarte
- runbook de incidentes
- plano de release
- politica de versionamento
- changelog

## 9. Fase 8 - Construcao e validacao

Produzir continuamente:

- registros de iteracao
- checklists de revisao
- evidencias de teste
- atualizacao de modelos e documentos
- relatorios de validacao do incremento em marcos maiores

## 10. Fase 9 - Transicao e defesa

Produzir primeiro:

- pacote de demonstracao
- sintese executiva das frentes
- conferencia final de aderencia
- relatorio de trade-offs do projeto
- material de defesa

Depois:

- roadmap revisado
- plano de evolucao futura
- manual operacional refinado
- changelog consolidado

## 11. Ordem logica geral

Se sintetizada, a ordem logica geral fica assim:

1. enquadramento
2. diagnostico
3. requisitos
4. modelagem
5. arquitetura e decisao
6. governanca e politicas
7. qualidade, seguranca e operacao
8. construcao e validacao
9. transicao e defesa
