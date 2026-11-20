# Análise Hierárquica de Tarefas (HTA – Hierarchical Task Analysis)

## Tabela de Contribuição

| Data | Contribuição | Autor(es) | Revisor(es) |
|---|---|---|---|
|  | Inserção da tabela de contribuição e atualização do diagrama HTA da tarefa de comunicação entre usuários, exclusão de estrutura não utilizada. | Evellyn Rocha | João Paulo |

## 1. Introdução e Fundamentação Teórica

A aplicação da HTA na avaliação do Teams permite identificar gargalos na navegação, quebras de fluxo, redundâncias operacionais e pontos onde o sistema exige esforço cognitivo excessivo para a conclusão de tarefas do cotidiano universitário e administrativo.

## 2. Metodologia e Elementos da HTA

A modelagem HTA adota a seguinte estrutura:

- **Objetivo (Goal):** Um estado final de coisas que a pessoa deseja alcançar (ex.: estruturar uma nova equipe de projeto).
- **Subobjetivo (Subgoal):** Uma meta intermediária necessária para o atingimento de um objetivo superior.
- **Operação (Operation):** A unidade atômica da tarefa que não necessita de mais decomposição. Cada operação no nível folha é especificada pela tupla `<Input, Ação, Feedback>`:
  - **Input:** As condições de ativação ou informações necessárias para iniciar a operação.
  - **Ação:** O ato físico ou cognitivo executado pelo usuário ou sistema.
  - **Feedback:** A resposta visual ou auditiva fornecida pela interface indicando o resultado da ação.
- **Planos (Plans):** Regras formais que definem a sequência e as condições sob as quais os subobjetivos devem ser alcançados:
  - **Sequencial:** Execução em ordem fixa (ex.: `1 > 2`).
  - **Seleção / Decisão:** Escolha de um caminho entre alternativas mutuamente exclusivas (ex.: `2.1 / 2.2`).
  - **Paralelo / Concorrente:** Atividades realizadas ao mesmo tempo ou em qualquer ordem (ex.: `4.1 + 4.2`).

## 3. Análise de Tarefas

### 3.1. Aproveitamento de estudos e dispensa de disciplinas 

Nesta tarefa, o usuário precisa solicitar o aproveitamento de estudos e a dispensa de disciplinas, processo que atualmente é realizado por meio do Sistema Eletrônico de Informações (SEI) da universidade. Para executar essa atividade, o usuário precisa acessar o sistema e seguir os procedimentos necessários para preencher e encaminhar sua solicitação.

A principal mudança proposta nesta avaliação de IHC consiste na integração dessa funcionalidade ao Microsoft Teams, permitindo que o usuário realize a solicitação de aproveitamento de estudos e dispensa de disciplinas diretamente pela plataforma, sem precisar acessar separadamente o SEI.

Dessa forma, a proposta busca centralizar os serviços acadêmicos no Microsoft Teams, facilitando o acesso à funcionalidade, simplificando o fluxo de solicitação e proporcionando uma experiência mais integrada aos usuários.

**Figura 1 – HTA – Comunicação entre usuários**

![Diagrama HTA – Comunicação entre usuários](../../assets/hta_evellyn.png)

**Autor:** Evellyn Rocha

### 3.2. Objetivos, operações e planos

A estrutura da tarefa é apresentada conforme o modelo de tabela utilizado na análise HTA.

| Objetivos / Operações | Plano |
|---|---|
| **0. Solicitar aproveitamento de estudos e dispensa** | `1 > 2 > 3 > 4 > 5` |
| **1. Acessar o serviço** | `1.1 > 1.2 > 1.3` |
| 1.1. Acessar a plataforma institucional | — |
| 1.2. Localizar Serviços Acadêmicos | — |
| 1.3. Selecionar Aproveitamento de estudos e dispensas | — |
| **2. Preencher formulário** | `2.1 > 2.2 > 2.3 > 2.4 > 2.5 > 2.6` |
| 2.1. Informar dados pessoais e acadêmicos | — |
| 2.2. Informar instituição de origem | — |
| 2.3. Informar matéria solicitada | — |
| 2.4. Selecionar disciplina de equivalência | — |
| 2.5. Anexar documentos comprobatórios | — |
| 2.6. Prosseguir para revisão | — |
| **3. Revisar solicitação** | `3.1 + 3.2 + 3.3 > 3.4` |
| 3.1. Conferir dados preenchidos | — |
| 3.2. Conferir cálculo de equivalência | — |
| 3.3. Conferir documentos anexados | — |
| 3.4. Confirmar envio | — |
| **4. Receber comprovante** | `4.1 > 4.2 > 4.3` |
| 4.1. Visualizar número do pedido | — |
| 4.2. Receber confirmação pelo chat e e-mail | — |
| 4.3. Acessar acompanhamento e status | — |
| **5. Acompanhar solicitação** | `5.1 > 5.2 > 5.3 > 5.4` |
| 5.1. Consultar status enviado | — |
| 5.2. Consultar status recebido | — |
| 5.3. Consultar status em análise | — |
| 5.4. Consultar status concluído | — |

## 4. Referências Bibliográficas

BARBOSA, Simone Diniz Junqueiro; SILVA, Bruno Santana da. *Interação Humano-Computador*. Rio de Janeiro: Elsevier / Campus, 2010.

DIAPER, Dan. Hierarchical Task Analysis (HTA). In: DIAPER, Dan; STANTON, Neville (Eds.). *The Handbook of Task Analysis for Human-Computer Interaction*. Mahwah, NJ: Lawrence Erlbaum Associates, 2003. p. 67-142.

## 5. Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|---|---|---|---|---|
| 1.0 | 27/09/2026 | Criação da página. | Evellyn Rocha | Luccas Rodrigues |