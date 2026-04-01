# Fases do Processo

## 1. Objetivo

Este documento detalha as macrofases do processo proposto, explicando porque
cada fase existe, quais insumos costuma receber, quais saidas pode gerar e como
ela se conecta ao trabalho iterativo do dia a dia.

## 2. Observacao metodologica

As fases abaixo nao formam um cascata rigida. Elas sao macroetapas de
responsabilidade. Na pratica, o trabalho diario acontece por iteracoes curtas,
mas cada iteracao se ancora em uma ou mais fases.

## 3. Fases

### 3.1 Enquadramento e mandato

Por que fazer:

- definir claramente o que esta sendo tratado como problema, produto e
  entregavel de TCC
- impedir que o projeto vire acumulacao informal de decisoes

Inputs tipicos:

- motivacao do TCC
- contexto do sistema atual
- restricoes de tempo, infraestrutura e escopo
- necessidades do cliente e do usuario

Possiveis outputs:

- termo de abertura do projeto
- visao do produto
- declaracao de problema
- objetivos estrategicos
- criterios de sucesso
- mapa de stakeholders
- escopo e fora de escopo
- riscos iniciais

### 3.2 Diagnostico do estado atual

Por que fazer:

- compreender o legado antes de herdar suas decisoes
- diferenciar o que existe, o que esta so documentado e o que deve ser revisto

Inputs tipicos:

- repositorio anterior
- documentacao existente
- historico Git
- backlog anterior
- stack atual

Possiveis outputs:

- inventario do sistema atual
- analise arquitetural `as-is`
- avaliacao de stack
- avaliacao de dependencias
- catalogo de funcionalidades existentes
- mapa de divida tecnica
- matriz `manter / adaptar / substituir / descartar`
- parecer tecnico do legado
- riscos herdados

### 3.3 Descoberta de produto, negocio e operacao

Por que fazer:

- pensar o sistema como produto e nao apenas como exercicio tecnico
- explicitar proposta de valor, formas de uso e viabilidade operacional

Inputs tipicos:

- outputs do enquadramento
- outputs do diagnostico
- visao futura do sistema
- perfis de usuario

Possiveis outputs:

- proposta de valor
- perfis operacionais
- jornadas de uso
- mapa de capacidades
- hipoteses de operacao
- direcao inicial sobre CLI, Web, execucao local e remota

### 3.4 Engenharia de requisitos e regras de negocio

Por que fazer:

- transformar visao e problema em necessidades rastreaveis
- dar base para arquitetura, backlog e testes

Inputs tipicos:

- visao do produto
- diagnostico
- jornadas e cenarios
- restricoes tecnicas e operacionais

Possiveis outputs:

- documento de requisitos
- regras de negocio
- requisitos nao funcionais
- casos de uso
- especificacoes textuais
- matriz de rastreabilidade
- criterios de aceite
- glossario do dominio

### 3.5 Modelagem e avaliacao de alternativas

Por que fazer:

- usar diagramas e artefatos como instrumentos de decisao
- reduzir ambiguidade e comparar alternativas de forma explicita

Inputs tipicos:

- requisitos
- regras de negocio
- diagnostico `as-is`
- questoes arquiteturais e operacionais abertas

Possiveis outputs:

- modelo de dominio
- UML de casos de uso, classes, sequencia e atividades
- diagramas de estados e componentes, quando relevantes
- C4
- 4+1
- modelagem `as-is` e `to-be`
- matrizes comparativas
- relatorios de trade-off

### 3.6 Arquitetura, tecnologia e decisao

Por que fazer:

- consolidar como a solucao sera montada e por que
- decidir stack, modulos, interfaces, operacao e evolucao

Inputs tipicos:

- requisitos
- modelos
- diagnostico do legado
- avaliacoes de tecnologia
- restricoes operacionais

Possiveis outputs:

- drivers arquiteturais
- visao arquitetural
- ADRs
- decisoes tecnologicas
- estrategia de integracoes externas
- plano de evolucao arquitetural
- definicao de MVP tecnico e operacional

### 3.7 Governanca, politicas e forma de trabalho

Por que fazer:

- dar ao projeto um sistema de gestao explicito
- transformar boas intencoes em regras e criterios verificaveis

Inputs tipicos:

- outputs das fases anteriores
- riscos identificados
- exigencias de qualidade, seguranca e rastreabilidade

Possiveis outputs:

- processo de software oficial
- modelo de governanca
- politicas fundacionais
- guidelines de execucao
- definicao de pronto
- plano de iteracoes
- backlog estruturado
- gestao de riscos

### 3.8 Construcao, validacao e integracao

Por que fazer:

- materializar as decisoes em software com disciplina e evidencia

Inputs tipicos:

- arquitetura consolidada
- politicas fundacionais
- backlog priorizado
- estrategia de testes

Possiveis outputs:

- codigo-fonte
- CLI funcional
- Web minima
- testes automatizados
- evidencias de execucao
- documentacao de iteracao
- correcoes e ajustes de arquitetura

### 3.9 Transicao, operacao inicial e evolucao

Por que fazer:

- tornar o sistema demonstravel, entregavel e minimamente sustentavel

Inputs tipicos:

- software executavel
- estrategia de deploy e distribuicao
- estrategia de observabilidade
- documentacao operacional

Possiveis outputs:

- versao demonstravel
- ambiente local reproduzivel
- ambiente remoto minimo, se adotado
- procedimento de deploy
- procedimento de backup e restauracao
- checklist operacional
- plano de evolucao futura
- material de defesa do TCC

## 4. Como o processo e tocado no dia a dia

### 4.1 Ciclo estrategico

Usado para revisar status do projeto, riscos, escopo e foco da proxima
iteracao.

### 4.2 Ciclo tatico de iteracao

1. escolher objetivo da iteracao
2. listar insumos necessarios
3. decidir quais artefatos precisam ser produzidos ou atualizados
4. abrir ou refinar issues
5. executar modelagem, analise ou implementacao
6. validar com checklist, teste e revisao
7. registrar outputs, decisoes e pendencias
8. planejar a proxima iteracao

### 4.3 Ciclo diario

No dia a dia, o trabalho pode se dividir em:

- leitura e diagnostico
- modelagem e decisao
- implementacao
- revisao e documentacao
- fechamento e rastreabilidade
