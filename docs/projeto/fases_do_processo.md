# Fases do Processo

## 1. Objetivo

Este documento detalha as macrofases do processo proposto, explicando:

- por que cada fase existe
- quais insumos costuma receber
- quais saídas pode gerar
- qual é o seu escopo exato
- como ela se conecta à dinâmica operacional do projeto

## 2. Observação Metodológica

As fases abaixo não formam uma cascata rígida. Elas são macroetapas de
responsabilidade.

Na prática:

- o trabalho diário acontece por iterações curtas
- cada iteração se ancora em uma ou mais fases
- uma fase define foco dominante, não exclusividade absoluta de trabalho

## 3. Fases

### 3.1 Enquadramento e Mandato

**Papel**

- definir o que é o projeto, por que ele existe, para quem ele existe, sob quais restrições e com que critérios de sucesso

**O que entra**

- motivação do TCC
- contexto geral do problema
- visão inicial do produto
- objetivos estratégicos
- critérios de sucesso
- stakeholders
- escopo e fora de escopo
- premissas e restrições
- riscos iniciais

**O que não entra**

- diagnóstico técnico detalhado do legado
- requisitos formais detalhados
- arquitetura-alvo detalhada
- políticas técnicas completas
- implementação da solução

**Possíveis saídas**

- termo de abertura do projeto
- visão do produto
- declaração de problema
- objetivos estratégicos
- critérios de sucesso
- mapa de stakeholders
- escopo e fora de escopo
- riscos iniciais

### 3.2 Governança Mínima de Fundação

**Papel**

- criar as regras mínimas para que o projeto possa ser conduzido com disciplina desde o início

**O que entra**

- estrutura mínima de backlog
- noção inicial de milestone
- noção inicial de iteração
- regra mínima de issue, branch e PR
- definição provisória de pronto
- organização mínima do repositório e dos documentos
- gestão inicial de riscos

**O que não entra**

- conjunto completo de políticas fundacionais
- política final de qualidade e segurança
- regras finais de operação e deploy
- taxonomia definitiva de labels e automações

**Possíveis saídas**

- backlog inicial
- quadro inicial de acompanhamento
- organização mínima de repositório
- marco inicial de governança do projeto

### 3.3 Diagnóstico do Estado Atual

**Papel**

- entender criticamente o sistema atual antes de herdar suas decisões

**O que entra**

- inventário do sistema atual
- análise arquitetural `as-is`
- avaliação da stack
- avaliação de dependências
- leitura crítica da documentação existente
- análise de aderência entre documentação e código
- mapeamento de funcionalidades existentes
- identificação de dívidas e riscos herdados
- modelagem reversa do que já existe
- matriz `manter / adaptar / substituir / descartar`

**O que não entra**

- decisão final da arquitetura futura
- redação final das políticas fundacionais
- implementação da nova solução
- formalização completa dos requisitos do sistema-alvo

**Possíveis saídas**

- inventário do sistema atual
- análise arquitetural `as-is`
- avaliação de stack
- avaliação de dependências
- catálogo de funcionalidades existentes
- mapa de dívida técnica
- matriz `manter / adaptar / substituir / descartar`
- parecer técnico do legado
- riscos herdados

### 3.4 Descoberta de Produto e Contexto Operacional

**Papel**

- explorar como o produto deve fazer sentido no uso real e no contexto operacional

**O que entra**

- proposta de valor
- perfis de uso
- jornadas
- mapa de capacidades
- contexto de uso
- hipóteses sobre CLI, Web, execução local e remota
- hipóteses de distribuição
- hipóteses de operação mínima

**O que não entra**

- especificação formal de requisitos
- regras de negócio detalhadas
- arquitetura detalhada
- decisões tecnológicas finais

**Possíveis saídas**

- proposta de valor
- perfis operacionais
- jornadas de uso
- mapa de capacidades
- hipóteses de operação
- direção inicial sobre CLI, Web, execução local e remota

### 3.5 Engenharia de Requisitos e Regras de Negócio

**Papel**

- converter visão, diagnóstico e descoberta em especificações rastreáveis

**O que entra**

- requisitos funcionais
- requisitos não funcionais
- regras de negócio
- atores
- casos de uso
- critérios de aceite
- glossário
- matriz de rastreabilidade

**O que não entra**

- decisão final de arquitetura
- diagramas puramente estruturais de software sem papel analítico
- decisões operacionais completas
- implementação

**Possíveis saídas**

- documento de requisitos
- regras de negócio
- requisitos não funcionais
- casos de uso
- especificações textuais
- matriz de rastreabilidade
- critérios de aceite
- glossário do domínio

### 3.6 Modelagem e Avaliação de Alternativas

**Papel**

- representar o problema e a solução possível, além de comparar alternativas relevantes

**O que entra**

- modelo de domínio
- UML
- C4
- `4+1`, se adotado
- fluxos `as-is` e `to-be`
- comparação entre alternativas de solução
- trade-offs preliminares

**O que não entra**

- decisão final ainda não deliberada
- implementação
- políticas organizacionais detalhadas

**Possíveis saídas**

- modelo de domínio
- UML de casos de uso, classes, sequência e atividades
- diagramas de estados e componentes, quando relevantes
- C4
- `4+1`
- modelagem `as-is` e `to-be`
- matrizes comparativas
- relatórios de trade-off

### 3.7 Arquitetura, Tecnologia e Decisão

**Papel**

- tomar as decisões principais sobre a solução

**O que entra**

- drivers arquiteturais
- visão arquitetural
- ADRs
- decisões de stack
- estratégia de módulos
- decisão sobre integrações externas
- decisão sobre interfaces principais
- definição do MVP técnico e operacional inicial

**O que não entra**

- política normativa completa do projeto
- execução plena da construção
- refinamentos tardios de operação

**Possíveis saídas**

- drivers arquiteturais
- visão arquitetural
- ADRs
- decisões tecnológicas
- estratégia de integrações externas
- plano de evolução arquitetural
- definição de MVP técnico e operacional

### 3.8 Políticas Fundacionais e Governança Evoluída

**Papel**

- consolidar a forma oficial de trabalhar após as principais decisões de solução terem sido tomadas

**O que entra**

- política de governança
- política de Git e PRs
- política de qualidade
- política de testes
- política de documentação e modelagem
- política de decisões arquiteturais
- política de segurança e segredos
- política de dependências e terceiros
- política de configuração por ambiente
- política de deploy e distribuição
- política de backup e restauração
- política de dados e conformidade
- guidelines complementares

**O que não entra**

- implementação em si
- revisão ampla de requisitos centrais já consolidados, salvo descoberta nova
- operação plena do produto final

**Possíveis saídas**

- processo de software oficial consolidado
- modelo de governança
- políticas fundacionais
- guidelines de execução
- definição de pronto
- plano de iterações
- backlog estruturado
- gestão de riscos amadurecida

### 3.9 Construção, Validação e Integração

**Papel**

- construir a solução com evidência e rastreabilidade

**O que entra**

- implementação
- testes
- validação
- CLI
- Web mínima
- ajustes incrementais de arquitetura
- documentação de iteração
- integração contínua mínima
- correção de problemas encontrados

**O que não entra**

- repensar do zero o enquadramento do projeto
- reabrir arquitetura sem motivação forte
- redesenhar políticas a cada microentrega

**Possíveis saídas**

- código-fonte
- CLI funcional
- Web mínima
- testes automatizados
- evidências de execução
- documentação de iteração
- correções e ajustes de arquitetura

### 3.10 Transição, Operação Inicial e Evolução

**Papel**

- tornar o sistema demonstrável, operável e pronto para apresentação e evolução

**O que entra**

- deploy
- distribuição
- ambiente local reproduzível
- ambiente remoto mínimo, se houver
- observabilidade mínima
- backup e restauração
- pacote de demonstração
- síntese executiva
- material de defesa
- plano de evolução futura

**O que não entra**

- grandes refundações metodológicas
- reabertura ampla do projeto sem necessidade real

**Possíveis saídas**

- versão demonstrável
- ambiente local reproduzível
- ambiente remoto mínimo, se adotado
- procedimento de deploy
- procedimento de backup e restauração
- checklist operacional
- plano de evolução futura
- material de defesa do TCC

## 4. Gates Principais Entre Fases

### 4.1 Gate A: do Diagnóstico para Descoberta/Requisitos

**Condições mínimas**

- inventário do sistema atual concluído
- análise arquitetural `as-is` inicial concluída
- avaliação inicial da stack concluída
- funcionalidades existentes minimamente mapeadas
- principais riscos herdados identificados
- legado analisado com profundidade suficiente para não depender de confiança cega

### 4.2 Gate B: de Requisitos/Modelagem para Arquitetura e Decisão

**Condições mínimas**

- visão do produto suficientemente estável
- regras de negócio iniciais definidas
- requisitos funcionais principais identificados
- requisitos não funcionais iniciais definidos
- casos de uso principais identificados
- modelo de domínio inicial produzido
- alternativas relevantes explicitadas quando houver trade-off real

### 4.3 Gate C: de Arquitetura e Decisão para Construção

**Condições mínimas**

- visão arquitetural inicial definida
- decisões arquiteturais centrais registradas
- estratégia inicial de interfaces definida
- estratégia de integrações externas definida
- estratégia mínima de operação definida
- backlog do primeiro incremento vertical definido
- critérios de aceite do primeiro incremento definidos

### 4.4 Gate D: para considerar o MVP operacionalmente aceitável

**Condições mínimas**

- fluxo principal executável
- CLI funcional
- Web mínima funcional
- configuração por ambiente mínima definida
- segredos fora do código
- logging mínimo presente
- estratégia de backup e restauração documentada
- falhas externas tratadas minimamente
- limites conhecidos do MVP explicitados

## 5. Dinâmica Operacional do Processo

### 5.1 Princípio Geral

- fase define o foco dominante
- iteração define o objetivo tático
- o dia define o trabalho concreto

### 5.2 Regra de Convivência entre Fases e Iterações

Uma iteração pode:

- estar ancorada em uma fase principal
- tocar artefatos de fases adjacentes
- desde que isso ajude a reduzir risco ou destravar decisão

Mesmo com sobreposição, cada iteração deve declarar:

- fase principal
- objetivo principal
- issue principal
- artefato principal esperado

### 5.3 Modelo Concreto de Ciclos

#### 5.3.1 Ciclo Estratégico

**Usado para**

- revisar status do projeto
- revisar riscos
- revisar escopo
- revisar a ordem das próximas decisões
- verificar se já há condição para passar de fase

**Saída esperada**

- decisão de foco das próximas iterações

#### 5.3.2 Ciclo Tático de Iteração

1. escolher objetivo da iteração
2. listar insumos necessários
3. decidir quais artefatos precisam ser produzidos ou atualizados
4. abrir ou refinar issues
5. executar modelagem, análise ou implementação
6. validar com checklist, teste e revisão
7. registrar outputs, decisões e pendências
8. planejar a próxima iteração

**Saída esperada**

- uma entrega, decisão ou artefato concreto

#### 5.3.3 Ciclo Diário

No dia a dia, o trabalho pode se dividir em:

- leitura e diagnóstico
- modelagem e decisão
- implementação
- revisão e documentação
- fechamento e rastreabilidade

**Saída esperada**

- progresso concreto no objetivo da iteração
