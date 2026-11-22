## Tabela de contribuição

| Data       | Contribuição                                                                                                  | Autor(es)     | Revisor(es) |
| ---------- | ------------------------------------------------------------------------------------------------------------- | ------------- | ----------- |
| 05/10/2026 | Criação da página separada por estudante                                                                                           | Evellyn Rocha   | João Paulo            |

# Análise Hierárquica de Tarefas (HTA – Hierarchical Task Analysis)

## 1. Introdução e Fundamentação Teórica

A aplicação da Análise Hierárquica de Tarefas (HTA) na avaliação do Microsoft Teams permite identificar gargalos na navegação, quebras de fluxo, redundâncias operacionais e pontos nos quais o sistema exige esforço cognitivo excessivo para a conclusão de tarefas do cotidiano universitário e administrativo.

A HTA permite decompor uma tarefa principal em objetivos, subobjetivos e operações, organizando as etapas necessárias para que o usuário alcance o resultado desejado. Essa representação facilita a compreensão da sequência de ações e a identificação de possíveis problemas de interação.

## 2. Metodologia e Elementos da HTA

A modelagem HTA adota a seguinte estrutura:

| Elemento | Descrição |
|---|---|
| **Objetivo (Goal)** | Estado final que a pessoa deseja alcançar. Exemplo: estruturar uma nova equipe de projeto. |
| **Subobjetivo (Subgoal)** | Meta intermediária necessária para o atingimento de um objetivo superior. |
| **Operação (Operation)** | Unidade atômica da tarefa que não necessita de mais decomposição. Cada operação no nível folha é especificada pela tupla Input, Ação e Feedback. |
| **Plano (Plan)** | Regra que define a sequência e as condições sob as quais os subobjetivos devem ser alcançados. |

### 2.1. Estrutura das operações

Cada operação no nível folha é descrita por três elementos:

- **Input:** condições de ativação ou informações necessárias para iniciar a operação.
- **Ação:** ato físico ou cognitivo executado pelo usuário ou pelo sistema.
- **Feedback:** resposta visual ou auditiva fornecida pela interface, indicando o resultado da ação.

### 2.2. Planos e relações entre tarefas

Os planos definem a sequência e as condições para a realização das tarefas. Na representação utilizada nesta análise, são considerados os seguintes símbolos:

| Símbolo | Relação | Descrição | Exemplo |
|---|---|---|---|
| `>` | Sequencial | Execução das tarefas em ordem definida. | `1 > 2` |
| `/` | Seleção / Decisão | Escolha de um caminho entre alternativas. | `2.1 / 2.2` |
| `+` | Paralelo / Concorrente | Atividades realizadas simultaneamente ou sem dependência de ordem. | `4.1 + 4.2` |

**Referência teórica:** metodologia fundamentada no livro *Interação Humano-Computador*, de Barbosa e Silva.

**Figura 1 – Referência teórica sobre Análise Hierárquica de Tarefas (HTA).**

<!-- INSERIR AQUI A FOTOGRAFIA DA PÁGINA DO LIVRO DE BARBOSA E SILVA -->

*Fonte: Barbosa e Silva (2010).*

## 3. Análise de Tarefas

### 3.1. Perfil: Estudante

**Responsável pelo perfil:** Evelyn Rocha

**Tarefa analisada:** Realizar e entregar uma atividade no Microsoft Teams.

#### 3.1.1. Texto explicativo e contextualização

Nesta tarefa, o estudante precisa acessar o canal de uma disciplina no Microsoft Teams, localizar uma atividade disponibilizada pelo professor, realizar o que foi solicitado e efetuar sua entrega pela plataforma.

Inicialmente, o estudante acessa o Microsoft Teams e entra no canal da matéria desejada. Em seguida, visualiza as publicações disponíveis, identifica a atividade que precisa realizar e acessa suas instruções. Após compreender o que foi solicitado, o estudante elabora sua resposta ou anexa o arquivo correspondente, revisa o conteúdo e realiza a entrega por meio da opção disponibilizada pelo sistema.

Durante esse processo, o estudante interage com diferentes recursos da plataforma, como canais, publicações, atividades, campos de resposta e anexos. O sistema, por sua vez, apresenta as informações da atividade, disponibiliza os mecanismos de envio e fornece a confirmação de que a entrega foi registrada.

#### 3.1.2. Diagrama HTA

**Figura 2 – Análise Hierárquica de Tarefas (HTA) da atividade de entrega pelo estudante no Microsoft Teams.**

<!-- INSERIR AQUI O DIAGRAMA HTA -->

*Fonte: Elaborado pelos autores.*

#### 3.1.3. Objetivos, operações, problemas e recomendações

A seguir, são apresentados o objetivo principal, seus subobjetivos e as operações necessárias para realizar e entregar uma atividade pelo Microsoft Teams. Para cada etapa, são identificados os possíveis problemas de interação e as respectivas recomendações.

### Objetivo 0 – Realizar e entregar uma atividade no Microsoft Teams

**Plano:** `1 > 2 > 3 > 4`

| Elemento | Descrição |
|---|---|
| **Input** | Necessidade de realizar uma atividade disponibilizada pelo professor. |
| **Ação** | Acessar o canal da disciplina, localizar a atividade, realizá-la e efetuar sua entrega. |
| **Feedback** | Atividade entregue e confirmação de envio apresentada pelo sistema. |
| **Problema identificado** | Dificuldade para localizar a atividade ou compreender as etapas necessárias para realizar e entregar a tarefa. |
| **Recomendação** | Organizar as etapas de acesso, localização, realização e entrega de maneira clara e intuitiva. |

### Objetivo 1 – Acessar o canal da disciplina

**Plano:** `1.1 > 1.2`

| Operação | Input | Ação | Feedback |
|---|---|---|---|
| **1.1. Abrir o Microsoft Teams** | Necessidade de acessar a plataforma. | Abrir o Microsoft Teams e realizar a autenticação, caso necessário. | Tela inicial da plataforma apresentada. |
| **1.2. Entrar no canal da matéria** | Identificação da disciplina que contém a atividade desejada. | Selecionar a equipe correspondente à disciplina e acessar seu canal. | Canal da disciplina aberto e conteúdo disponível para visualização. |

**Problemas e recomendações:**

| Problema identificado | Recomendação |
|---|---|
| Dificuldades de acesso, autenticação ou carregamento da plataforma. | Apresentar mensagens claras em situações de erro e facilitar o processo de autenticação. |
| Dificuldade para localizar a equipe ou o canal correspondente à disciplina desejada. | Apresentar as equipes e os canais de maneira organizada, facilitando sua identificação. |
| Confusão entre canais de diferentes disciplinas. | Utilizar nomes claros para as equipes e canais, facilitando sua identificação. |

### Objetivo 2 – Encontrar a atividade

**Plano:** `2.1 > 2.2`

| Operação | Input | Ação | Feedback |
|---|---|---|---|
| **2.1. Visualizar as publicações do canal** | Canal da disciplina acessado. | Consultar as publicações disponibilizadas pelo professor. | Publicações exibidas na tela, incluindo avisos e atividades. |
| **2.2. Selecionar a atividade desejada** | Publicações disponíveis no canal. | Identificar e selecionar a atividade que precisa ser realizada. | Atividade selecionada e seus detalhes disponibilizados. |

**Problemas e recomendações:**

| Problema identificado | Recomendação |
|---|---|
| Publicações em grande quantidade podem dificultar a localização de uma atividade específica. | Destacar as atividades e disponibilizar informações como título, prazo de entrega e descrição. |
| Dificuldade para diferenciar atividades de outras publicações do canal. | Utilizar identificação visual para destacar publicações relacionadas a atividades. |
| Atividades com títulos semelhantes ou informações insuficientes podem gerar confusão. | Apresentar títulos objetivos, descrição e prazo de entrega de cada atividade. |

### Objetivo 3 – Realizar a atividade

**Plano:** `3.1 > 3.2 > 3.3`

| Operação | Input | Ação | Feedback |
|---|---|---|---|
| **3.1. Ler as instruções** | Atividade selecionada. | Acessar e ler a descrição, as orientações e os requisitos definidos pelo professor. | Informações da atividade apresentadas para consulta. |
| **3.2. Responder ou anexar o arquivo** | Instruções e requisitos da atividade compreendidos. | Elaborar a resposta no espaço disponibilizado ou selecionar e anexar o arquivo solicitado. | Resposta inserida ou arquivo anexado à atividade. |
| **3.3. Revisar a resposta** | Resposta elaborada ou arquivo anexado. | Conferir o conteúdo da resposta e verificar se o arquivo correto foi anexado antes da entrega. | Resposta revisada e pronta para submissão. |

**Problemas e recomendações:**

| Problema identificado | Recomendação |
|---|---|
| Instruções extensas ou pouco organizadas podem dificultar a compreensão do que deve ser realizado. | Apresentar as orientações de forma objetiva, destacando informações importantes, como critérios e prazo de entrega. |
| Dificuldades para preencher o campo de resposta, localizar arquivos ou identificar formatos aceitos pela plataforma. | Disponibilizar campos de resposta intuitivos, indicar os formatos de arquivos aceitos e apresentar orientações para anexação. |
| Ausência de conferência adequada pode levar ao envio de arquivos incorretos ou respostas incompletas. | Permitir a visualização da resposta e dos arquivos anexados antes da confirmação da entrega. |

### Objetivo 4 – Entregar a atividade

**Plano:** `4.1 > 4.2`

| Operação | Input | Ação | Feedback |
|---|---|---|---|
| **4.1. Clicar em "Entregar"** | Resposta revisada e pronta para submissão. | Selecionar a opção "Entregar" disponibilizada na atividade. | Solicitação de entrega processada pelo sistema ou apresentação de uma etapa de confirmação. |
| **4.2. Confirmar a entrega** | Solicitação de entrega realizada. | Confirmar a submissão, quando solicitado, e verificar o registro do envio. | Mensagem ou indicador de confirmação de que a atividade foi entregue. |

**Problemas e recomendações:**

| Problema identificado | Recomendação |
|---|---|
| O estudante pode acreditar que a atividade foi entregue apenas por ter preenchido a resposta ou anexado um arquivo. | Diferenciar claramente as etapas de preparação e entrega, apresentando uma confirmação após o registro do envio. |
| Dificuldade para localizar o botão de entrega ou confusão entre salvar e entregar a atividade. | Destacar a opção "Entregar" e diferenciá-la de outras ações, como salvar ou editar a resposta. |
| Ausência de retorno claro pode gerar dúvidas sobre a conclusão do envio. | Apresentar uma confirmação visível, informando que a atividade foi entregue com sucesso. |

## 4. Referências Bibliográficas

BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação Humano-Computador*. Rio de Janeiro: Elsevier / Campus, 2010.

DIAPER, Dan. Hierarchical Task Analysis (HTA). In: DIAPER, Dan; STANTON, Neville (Eds.). *The Handbook of Task Analysis for Human-Computer Interaction*. Mahwah, NJ: Lawrence Erlbaum Associates, 2003. p. 67–142.

## 5. Agradecimentos à Inteligência Artificial

Agradecemos ao ChatGPT pelo apoio na organização e formatação deste documento em Markdown, na estruturação das tabelas de objetivos, operações, problemas e recomendações, bem como na organização hierárquica dos elementos da Análise Hierárquica de Tarefas (HTA). A ferramenta também auxiliou na revisão textual e na adequação do conteúdo para publicação no GitHub Pages. A análise, as decisões de modelagem e a validação do conteúdo permanecem sob responsabilidade dos autores.