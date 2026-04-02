# Processo de Software

## 1. Objetivo

Este documento define o processo de software proposto para o projeto.

O objetivo nao e apenas organizar implementacao de codigo. O objetivo e fundar
uma iniciativa de produto de software com padrao profissional, apta a gerar um
entregavel tecnicamente defensavel, operacionalmente coerente e academicamente
rastreavel.

Este documento tem natureza **executivo-normativa**. Seu papel e consolidar a
decisao metodologica central do projeto, seus principios, sua estrutura macro e
seu nucleo normativo esperado. O detalhamento operacional das fases, dos gates,
da dinamica cotidiana do trabalho e da orientacao pratica de execucao e
complementado por:

- `docs/projeto/fases_do_processo.md`
- `docs/projeto/plano_operacional_do_processo.md`

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
2. governanca minima de fundacao
3. diagnostico do estado atual
4. descoberta de produto e contexto operacional
5. engenharia de requisitos e regras de negocio
6. modelagem e avaliacao de alternativas
7. arquitetura, tecnologia e decisao
8. politicas fundacionais e governanca evoluida
9. construcao, validacao e integracao
10. transicao, operacao inicial e evolucao

## 6. Gates do processo

O processo adota gates minimos entre blocos decisorios relevantes. Eles existem
para impedir avancos prematuros e preservar coerencia entre entendimento,
decisao e execucao.

De forma sintetica, os gates principais sao:

- diagnostico para descoberta e requisitos: evita construir sobre leitura
  superficial do legado
- requisitos e modelagem para arquitetura e decisao: evita decidir a solucao sem
  base minimamente formalizada
- arquitetura e decisao para construcao: evita iniciar implementacao sem
  fundacao tecnica suficiente
- construcao para aceitacao operacional do MVP: evita chamar de MVP algo que
  apenas executa localmente sem minimo operacional

O detalhamento desses gates e mantido em
`docs/projeto/fases_do_processo.md`.

## 7. Unidade operacional do processo

A unidade operacional do processo sera a **iteracao curta orientada a objetivo**.

Cada iteracao deve:

- perseguir um objetivo claro
- ter escopo pequeno o suficiente para fechamento real
- gerar incremento verificavel
- deixar rastro em issue, branch, PR e documentacao de iteracao
- explicitar impactos em arquitetura, qualidade, seguranca e operacao quando
  aplicavel
- declarar fase principal, objetivo principal, issue principal e artefato
  principal esperado

Uma iteracao pode tocar fases adjacentes, mas deve manter foco dominante
explicito para evitar dispersao e perda de rastreabilidade.

Duracao sugerida:

- entre 3 e 10 dias corridos, conforme a complexidade do objetivo

## 8. Dinamica operacional

O funcionamento cotidiano do processo e detalhado em:

- `docs/projeto/fases_do_processo.md`
- `docs/projeto/plano_operacional_do_processo.md`
- `docs/projeto/modelo_plano_de_iteracao.md`

Em sintese:

- fase define o foco dominante
- iteracao define o objetivo tatico
- o dia define o trabalho concreto
- uma iteracao pode tocar fases adjacentes, desde que isso reduza risco ou
  destrave decisao

## 9. Nucleo normativo esperado

Este processo pressupoe a consolidacao progressiva de um nucleo normativo do
projeto. Sem detalhar o conteudo de cada politica, espera-se a existencia de
artefatos normativos ao menos para os seguintes temas:

- governanca do projeto
- Git, branches, commits e pull requests
- qualidade
- testes
- documentacao e modelagem
- decisoes arquiteturais
- seguranca e segredos
- dependencias e servicos terceiros
- configuracao por ambiente
- deploy, distribuicao e operacao
- dados, privacidade e conformidade
- backup e restauracao

## 10. Dimensoes obrigatorias

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
