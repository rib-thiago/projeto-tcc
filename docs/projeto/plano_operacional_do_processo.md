# Plano Operacional do Processo

## 1. Objetivo

Este documento funciona como guia operacional de consulta rapida para a
execucao do processo de software do projeto.

Seu papel nao e substituir os documentos estruturais do processo, mas apoiar a
atuacao cotidiana dentro das fases, iteracoes e ciclos de trabalho.

Este plano deve ajudar a responder, de forma pratica:

- em que fase estamos
- qual e o foco dominante da iteracao atual
- como se comportar em cada fase
- o que precisa ser produzido, revisto ou atualizado
- o que precisa ser verificado antes de avancar
- quais gates merecem atencao antes de mudar de bloco de trabalho

## 2. Relacao com os demais documentos

Este documento deve ser lido em conjunto com:

- `docs/projeto/processo_de_software.md`: define a decisao metodologica central
  e o nucleo normativo esperado do projeto
- `docs/projeto/fases_do_processo.md`: detalha as macrofases, seus limites,
  seus outputs, seus gates e a dinamica operacional do processo
- `docs/projeto/sequencia_de_producao_por_fase.md`: organiza a ordem logica de
  producao dos artefatos por fase e indica os artefatos tipicamente mobilizados
  em cada momento do processo
- `docs/projeto/cronograma_macro_da_fundacao.md`: organiza a distribuicao
  temporal da milestone atual em janelas de foco dominante
- `docs/projeto/modelo_plano_de_iteracao.md`: oferece a estrutura reutilizavel
  para planejamento tatico de cada iteracao
- `docs/projeto/criterios_de_pronto.md`: consolida criterios de pronto para
  documentos, iteracoes e issues estruturais
- `docs/projeto/modelo_de_governanca_operacional_do_backlog.md`: explicita como
  backlog, milestone, board, iteracoes e documentos se relacionam

Este plano e, portanto, um artefato de consulta operacional. Ele traduz a
estrutura metodologica em orientacoes praticas de uso cotidiano, sem substituir
nem duplicar o papel estrutural, temporal ou de governanca dos demais artefatos.

## 3. Regras operacionais gerais

### 3.1 Regra de foco dominante

Toda iteracao deve declarar explicitamente:

- fase principal
- objetivo principal
- issue principal
- artefato principal esperado

Mesmo quando tocar fases adjacentes, a iteracao deve manter um foco dominante
claro.

### 3.2 Regra de rastreabilidade minima

Todo trabalho relevante deve deixar rastro em pelo menos parte do sistema de
trabalho do projeto, conforme o caso:

- issue
- branch
- pull request
- documento atualizado
- registro de iteracao
- artefato de modelagem ou decisao

### 3.3 Regra de coerencia documental

Sempre que uma decisao alterar entendimento de processo, fase, artefato,
requisito, arquitetura ou operacao, os documentos impactados devem ser
revisitados.

### 3.4 Regra de progressao responsavel

Nao se deve avancar para blocos mais executivos do trabalho apenas porque ha
vontade de implementar. A passagem entre blocos deve respeitar entendimento
minimo, decisao suficiente e rastreabilidade adequada.

## 4. Como operar em cada fase

### 4.1 Enquadramento e Mandato

Foco da fase:

- definir problema, objetivos, stakeholders, restricoes e criterios de sucesso

Postura recomendada:

- evitar detalhamento tecnico precoce
- formular bem o problema antes de falar de solucao
- distinguir visao, escopo e premissas

Perguntas praticas:

- que problema estamos realmente tentando resolver
- para quem o projeto existe
- o que entra e o que fica fora
- como saberemos que esta rodada ou o projeto foram bem-sucedidos

Sinais de boa conducao:

- objetivo do projeto compreensivel
- escopo inicial delimitado
- stakeholders conhecidos
- sucesso definido de modo observavel

### 4.2 Governanca Minima de Fundacao

Foco da fase:

- criar condicoes minimas para o projeto ser conduzido com ordem e
  rastreabilidade

Postura recomendada:

- preferir controle suficiente a sofisticacao prematura
- estruturar o minimo que evite caos futuro

Perguntas praticas:

- onde o trabalho sera registrado
- como o fluxo de trabalho minimo sera controlado
- como garantir rastreabilidade entre backlog, decisao e documento

Sinais de boa conducao:

- backlog inicial existente
- milestone inicial definida
- project board inicial utilizavel
- estrutura documental minima criada
- definicao provisoria de pronto existente

### 4.3 Diagnostico do Estado Atual

Foco da fase:

- entender criticamente o sistema existente antes de herdar decisoes

Postura recomendada:

- desconfiar de supostos consensos nao verificados
- comparar documentacao, codigo e comportamento observado
- registrar valor, risco e limite do legado

Perguntas praticas:

- o que realmente existe hoje
- o que funciona, o que falta e o que esta mal compreendido
- quais escolhas anteriores merecem ser mantidas, adaptadas ou descartadas

Sinais de boa conducao:

- inventario do sistema elaborado
- arquitetura `as-is` minimamente compreendida
- stack e dependencias avaliadas
- riscos herdados identificados
- parecer tecnico do legado em construcao ou concluido

### 4.4 Descoberta de Produto e Contexto Operacional

Foco da fase:

- explorar valor, contexto de uso e hipoteses de operacao do produto

Postura recomendada:

- trabalhar com hipoteses explicitadas, nao com suposicoes invisiveis
- pensar uso, operacao e distribuicao desde cedo

Perguntas praticas:

- que valor concreto o produto entrega
- quem o utilizara e em que contexto
- qual o papel da CLI, da Web minima e do ambiente remoto

Sinais de boa conducao:

- proposta de valor explicitada
- jornadas e capacidades mapeadas
- hipoteses operacionais minimamente descritas

### 4.5 Engenharia de Requisitos e Regras de Negocio

Foco da fase:

- transformar descoberta e diagnostico em artefatos formais e rastreaveis

Postura recomendada:

- especificar com clareza sem congelar o aprendizado
- separar desejo, regra de negocio e requisito verificavel

Perguntas praticas:

- quais requisitos sao de fato obrigatorios
- quais regras de negocio governam o comportamento esperado
- que criterios de aceite tornam a entrega verificavel

Sinais de boa conducao:

- requisitos principais documentados
- regras de negocio explicitadas
- casos de uso principais conhecidos
- criterios de aceite definidos

### 4.6 Modelagem e Avaliacao de Alternativas

Foco da fase:

- representar o sistema atual e o sistema desejado, comparando alternativas

Postura recomendada:

- modelar para esclarecer e decidir, nao para ornamentar
- explicitar comparacoes quando houver trade-off real

Perguntas praticas:

- quais modelos ajudam a enxergar melhor o problema
- que alternativas existem e como elas se comparam
- o que a modelagem `as-is` e `to-be` esta revelando

Sinais de boa conducao:

- modelo de dominio consistente
- diagramas principais produzidos ou planejados com criterio
- alternativas relevantes comparadas com clareza

### 4.7 Arquitetura, Tecnologia e Decisao

Foco da fase:

- tomar decisoes estruturais sobre a solucao

Postura recomendada:

- registrar decisoes importantes
- comparar alternativas antes de fixar a direcao
- considerar impacto em operacao, seguranca, testes e evolucao

Perguntas praticas:

- que arquitetura melhor atende os drivers do projeto
- quais tecnologias sao adequadas ao problema real
- como a solucao sera modularizada, operada e evoluida

Sinais de boa conducao:

- visao arquitetural definida
- drivers arquiteturais claros
- ADRs relevantes produzidos
- estrategia de integracoes e evolucao descrita

### 4.8 Politicas Fundacionais e Governanca Evoluida

Foco da fase:

- consolidar o sistema normativo do projeto

Postura recomendada:

- transformar aprendizados e riscos em politica utilizavel
- evitar tanto o excesso abstrato quanto a falta de normatividade

Perguntas praticas:

- que politicas ja precisam nascer agora
- o que ainda depende de amadurecimento adicional
- como garantir coerencia entre politica, backlog e pratica

Sinais de boa conducao:

- processo de software amadurecido
- politica de governanca definida
- prioridades normativas claras
- backlog e iteracoes mais bem estruturados

### 4.9 Construcao, Validacao e Integracao

Foco da fase:

- transformar decisao em incremento executavel e validado

Postura recomendada:

- implementar por fatias pequenas
- manter documentacao, testes e evidencias em dia
- nao tratar revisao como etapa opcional

Perguntas praticas:

- qual e o incremento vertical desta iteracao
- que evidencias sustentam a validacao da entrega
- que impactos documentais ou arquiteturais precisam ser atualizados

Sinais de boa conducao:

- incremento implementado com rastreabilidade
- testes e evidencias disponiveis
- CLI e Web minima evoluindo com coerencia
- modelos e documentos atualizados quando necessario

### 4.10 Transicao, Operacao Inicial e Evolucao

Foco da fase:

- tornar a entrega demonstravel, operavel e defensavel

Postura recomendada:

- validar a entrega em condicoes proximas do uso real
- verificar operacao minima, distribuicao e material de demonstracao

Perguntas praticas:

- o MVP esta operacionalmente aceitavel
- a entrega esta demonstravel e explicavel
- o que precisa ficar claro como limite e como proximo passo

Sinais de boa conducao:

- demonstracao preparada
- operacao minima documentada
- validacao do MVP operacional registrada
- evolucao futura minimamente planejada

## 5. Como conduzir uma iteracao

Roteiro recomendado:

1. identificar a fase principal da iteracao
2. definir o objetivo principal
3. selecionar ou refinar a issue principal
4. declarar o artefato principal esperado
5. listar artefatos secundarios possivelmente impactados
6. executar leitura, modelagem, decisao, escrita ou implementacao
7. revisar evidencias, coerencia e rastreabilidade
8. registrar o fechamento da iteracao e seus desdobramentos

Checklist de abertura da iteracao:

- qual e a fase principal
- qual problema esta sendo atacado
- qual issue representa esse trabalho
- qual artefato principal deve nascer ou amadurecer
- que criterios indicarao encerramento real

Checklist de fechamento da iteracao:

- o objetivo foi realmente atingido
- ha rastro suficiente do trabalho realizado
- os documentos impactados foram atualizados
- surgiram novas decisoes, riscos ou pendencias
- a proxima iteracao ficou mais clara

## 6. Como agir quando a iteracao muda de fase no meio do caminho

Mudancas de fase durante uma iteracao sao aceitaveis quando surgem descobertas,
restricoes ou riscos que mudam o foco do trabalho. O importante nao e evitar a
mudanca a qualquer custo, mas trata-la com consciencia e rastreabilidade.

Conduta recomendada:

- identificar se a mudanca e apenas apoio pontual a uma fase adjacente ou se o
  foco dominante realmente mudou
- se o foco dominante mudou, registrar isso na iteracao, na issue e nos
  documentos impactados quando necessario
- verificar se a mudanca reabre um gate anterior ou exige revisao de artefatos
  ja considerados suficientes
- evitar seguir implementando como se nada tivesse mudado

Sinais de mudanca legitima de fase:

- descoberta relevante que invalida uma premissa anterior
- lacuna de requisito, modelagem ou arquitetura que bloqueia a iteracao
- risco novo que exige retorno a uma fase de decisao ou governanca

## 7. Como operar no ciclo diario

Perguntas de orientacao diaria:

- em que fase esta o foco dominante do trabalho atual
- qual e o objetivo concreto da sessao de trabalho
- que artefato esta sendo amadurecido hoje
- o que precisa ser lido, escrito, decidido ou validado
- que rastro precisa ser deixado antes de encerrar a sessao

Boas praticas do ciclo diario:

- evitar alternancia excessiva entre frentes desconectadas
- registrar decisoes enquanto ainda estao frescas
- atualizar o minimo necessario para nao acumular divida documental
- encerrar a sessao deixando claro qual e o proximo passo

## 8. Gates a lembrar durante a execucao

Antes de mudar de bloco de trabalho, verificar se ha base minima para isso.

Lembretes operacionais:

- nao sair do diagnostico com leitura superficial do legado
- nao entrar em arquitetura sem requisitos e modelagem minimamente
  sustentadores
- nao iniciar construcao sem direcao arquitetural suficiente
- nao chamar de MVP algo que apenas roda localmente sem operacao minima

## 9. Sinais de desvio do processo

Alguns sinais merecem atencao imediata, porque indicam perda de coerencia entre
processo, backlog, documentos e execucao.

Sinais tipicos:

- implementacao avancando sem artefato de decisao ou requisito suficiente
- iteracao sem foco dominante claro
- backlog descolado dos documentos centrais do projeto
- documentos estruturais ficando sistematicamente desatualizados
- mudancas importantes ocorrendo sem rastro de decisao ou justificativa
- passagem de gate tratada apenas por ansiedade de avancar

## 10. Uso recomendado deste documento

Este plano deve ser consultado especialmente:

- no inicio de uma nova iteracao
- quando houver duvida sobre o foco dominante da fase atual
- quando o trabalho parecer disperso ou pouco rastreavel
- antes de mudar de bloco decisorio relevante
- durante revisoes de coerencia entre backlog, documentos e execucao
