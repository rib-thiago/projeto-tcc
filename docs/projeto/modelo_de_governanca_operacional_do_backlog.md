# Modelo de Governanca Operacional do Backlog

## 1. Objetivo

Este documento explicita como backlog, issues, milestone, project board,
iteracoes e documentos se relacionam na operacao cotidiana do projeto.

Seu papel e transformar a governanca minima em uma logica de trabalho mais
explicita e consultavel.

## 2. Unidade basica de trabalho

A unidade basica de trabalho do projeto e a issue orientada a objetivo.

Cada issue relevante deve, idealmente, explicitar:

- problema ou objetivo
- criterio de aceite
- fora de escopo
- milestone associada, quando fizer sentido
- artefatos possivelmente impactados

## 3. Relacao entre backlog e milestone

- o backlog representa o universo organizado do trabalho identificado
- a milestone agrupa o trabalho de um marco maior
- nem toda issue do backlog precisa estar imediatamente em execucao
- a milestone ativa deve refletir o foco dominante do momento do projeto

## 4. Relacao entre project board e iteracao

- o project board representa o estado visivel do trabalho
- a iteracao seleciona, dentro do backlog, o foco tatico dominante
- em regra, deve haver uma issue principal em `In Progress`
- outras issues podem existir na milestone sem competir pelo foco dominante da
  iteracao

## 5. Relacao entre issue e documentacao

Quando uma issue altera entendimento estrutural do projeto, espera-se:

- atualizacao dos documentos impactados
- registro de decisao, quando necessario
- revisao cruzada minima se houver efeito em mais de um documento central
- consulta a `docs/projeto/criterios_de_pronto.md` antes de declarar a issue
  estrutural como pronta

## 6. Quando replanejar o backlog

O backlog deve ser replanejado quando:

- surgir descoberta que mude a ordem de prioridades
- uma issue revelar dependencia forte nao prevista
- o cronograma macro perder aderencia com a densidade real das frentes
- documentos estruturais indicarem necessidade de nova frente de trabalho

## 7. Sinais de boa governanca operacional

- uma issue principal claramente dominante por iteracao
- backlog coerente com os documentos centrais
- milestone refletindo o foco real da rodada
- board utilizavel como espelho do estado do trabalho
- replanejamento registrado, nao apenas improvisado
