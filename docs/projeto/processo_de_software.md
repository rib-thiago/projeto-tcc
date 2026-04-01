# Processo de Software

## 1. Objetivo

Este documento define o processo de software proposto para o projeto.

O objetivo nao e apenas organizar implementacao de codigo. O objetivo e fundar
uma iniciativa de produto de software com padrao profissional, apta a gerar um
entregavel tecnicamente defensavel, operacionalmente coerente e academicamente
rastreavel.

O processo aqui proposto deve orientar:

- descoberta e delimitacao do problema
- diagnostico do estado atual do sistema existente
- modelagem e avaliacao critica de alternativas
- definicao de politicas e regras de trabalho
- implementacao incremental do produto
- preparacao para operacao, distribuicao e evolucao futura

## 2. Decisao de processo

O processo oficial recomendado para o repositorio e:

**processo iterativo e incremental, orientado a riscos, centrado em
arquitetura, diagnostico e governanca de produto, inspirado no Unified Process
e operacionalizado com Git e GitHub**.

Em termos praticos, isso significa:

- inspiracao metodologica em UP/RUP
- adaptacao ao contexto de projeto individual com ambicao profissional
- forte preocupacao com arquitetura, qualidade, seguranca e operacao
- documentacao rica quando aumenta poder de decisao, rastreabilidade ou defesa
  tecnica
- uso do repositorio como fonte oficial de verdade para artefatos normativos e
  tecnicos

## 3. Enquadramento do projeto

Este processo assume o seguinte enquadramento:

- o repositorio nao sera mera continuacao linear do projeto anterior
- o acervo existente sera tratado como insumo de descoberta, nao como verdade
  automaticamente aceita
- o trabalho deve simular a postura de uma empresa de software contratada para
  diagnosticar, decidir e entregar uma solucao adequada a um cliente de baixa
  maturidade
- o escopo inclui dimensoes de produto, engenharia, governanca, operacao,
  distribuicao, seguranca e conformidade

## 4. Principios do processo

### 4.1 Diagnostico antes de heranca

Decisoes, codigo, documentacao, bibliotecas e escolhas anteriores devem ser
avaliados antes de serem herdados como base normativa do novo projeto.

### 4.2 Arquitetura como ativo central

O projeto deve evoluir com arquitetura explicita, capaz de sustentar mudancas,
operacao, seguranca, testes e multiplas interfaces.

### 4.3 Risco antes de conveniencia

Itens com maior impacto arquitetural, tecnico, juridico, operacional,
financeiro ou de seguranca devem ser tratados antes de melhorias cosmeticas ou
expansoes de baixo valor.

### 4.4 Documentacao orientada a decisao

Diagramas, matrizes, pareceres, modelos UML, ADRs e relatorios devem ser
produzidos sempre que aumentarem entendimento, comparabilidade entre
alternativas, governanca ou capacidade de justificacao tecnica.

### 4.5 Incrementalidade real

Nenhuma fase deve pressupor reescrita total ou salto cego para implementacao. A
evolucao deve ocorrer por fatias pequenas, verificaveis e rastreaveis.

### 4.6 Qualidade como criterio de pronto

Teste, clareza estrutural, rastreabilidade, seguranca, observabilidade minima e
confiabilidade operacional nao sao acabamento tardio. Sao parte da definicao de
concluido.

### 4.7 Governanca proporcional ao risco

O projeto nao deve ser burocratico por reflexo, mas tambem nao deve ser enxuto
por dogma. O nivel de formalizacao deve acompanhar o impacto da decisao.

## 5. Macrofases

As macrofases completas do processo sao detalhadas em
`docs/projeto/fases_do_processo.md`.

De forma sintetica, o processo e organizado em:

1. enquadramento e mandato
2. diagnostico do estado atual
3. descoberta de produto e operacao
4. engenharia de requisitos e regras de negocio
5. modelagem e avaliacao de alternativas
6. arquitetura, tecnologia e decisao
7. governanca, politicas e forma de trabalho
8. construcao, validacao e integracao
9. transicao, operacao inicial e evolucao

## 6. Unidade operacional do processo

A unidade operacional do processo sera a **iteracao curta orientada a objetivo**.

Cada iteracao deve:

- perseguir um objetivo claro
- ter escopo pequeno o suficiente para fechamento real
- gerar incremento verificavel
- deixar rastro em issue, branch, PR e documentacao de iteracao
- explicitar impactos em arquitetura, qualidade, seguranca e operacao quando
  aplicavel

Duracao sugerida:

- entre 3 e 10 dias corridos, conforme a complexidade do objetivo

## 7. Fluxo de trabalho da iteracao

1. selecionar objetivo da iteracao
2. revisar riscos, dependencias e impacto arquitetural
3. definir necessidade de modelagem, comparacao de alternativas ou parecer
4. abrir ou refinar issues necessarias
5. escolher uma unica issue principal para execucao ativa
6. implementar ou documentar o trabalho em branch propria
7. validar com testes e checklists aplicaveis
8. abrir PR com rastreabilidade completa
9. registrar resultado, decisoes e aprendizados da iteracao

## 8. Dimensoes obrigatorias

O processo deve tratar, de forma integrada, as seguintes dimensoes:

- produto
- engenharia
- modelagem
- governanca
- operacao
- deploy e distribuicao
- seguranca
- conformidade
- qualidade
- documentacao
