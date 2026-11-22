## Tabela de contribuição

| Data       | Contribuição                                                                                                  | Autor(es)     | Revisor(es) |
| ---------- | ------------------------------------------------------------------------------------------------------------- | ------------- | ----------- |
| 15/11/2026 | Criação da página separada por estudante                                                                                           | Evellyn Rocha   | João Paulo            |

# Árvores de Tarefas Concorrentes (CTT – ConcurTaskTrees)

## 1. Introdução e Fundamentação Teórica

A modelagem em CTT apoia a engenharia de Interação Humano-Computador (IHC) ao articular explicitamente o diálogo entre o usuário e o sistema, categorizando quem executa cada ação e como as tarefas se relacionam no tempo. Na avaliação do Microsoft Teams, a árvore CTT permite identificar pontos de escolha alternativa, tarefas que exigem troca simultânea de dados e momentos de processamento em segundo plano.

## 2. Metodologia e Elementos do CTT

A metodologia utilizada nesta análise foi fundamentada no livro *Interação Humano-Computador*, de Barbosa e Silva (2010), e nos trabalhos de Fabio Paternò sobre modelagem de tarefas.

### 2.1. Categorias de Tarefas

No CTT, cada nó da árvore é classificado graficamente em uma das quatro categorias funcionais:

| Categoria | Descrição |
|---|---|
| **Tarefa Abstrata (Abstract Task)** | Representa um objetivo de alto nível ou um agrupamento hierárquico que engloba uma combinação de subtarefas de diferentes categorias. |
| **Tarefa do Usuário (User Task)** | Atividade cognitiva ou física realizada exclusivamente pela pessoa, sem interação direta com o sistema computacional. |
| **Tarefa Interativa (Interactive Task)** | Ação em que ocorre o diálogo direto e a troca de informações entre a pessoa e a interface do sistema. |
| **Tarefa do Sistema (System Task)** | Processamento ou ação executada automaticamente pelo próprio sistema, sem intervenção humana direta. |

### 2.2. Operadores Temporais (Notação de Paternò)

A relação temporal entre tarefas irmãs situadas no mesmo nível de decomposição é definida por operadores formais:

| Operador | Nome | Descrição | Exemplo |
|---|---|---|---|
| `>>` | Ativação Sequencial (Enabling) | A tarefa da direita só pode ser iniciada após a conclusão da tarefa da esquerda. | `T1 >> T2` |
| `[]>>` | Ativação com Passagem de Informação (Enabling with Information Passing) | A tarefa T2 inicia após o término de T1, recebendo as informações produzidas por T1. | `T1 []>> T2` |
| `[]` | Escolha Alternativa (Choice) | O usuário deve escolher entre T1 ou T2. O início da execução de uma desabilita imediatamente a outra. | `T1 [] T2` |
| `\|= \|` | Independência de Ordem (Order Independence) | Ambas as tarefas devem ser realizadas, mas podem ser executadas em qualquer sequência, sem interrupção mútua. | `T1 \|= \| T2` |
| `|||` | Tarefas Concorrentes (Interleaving) | As tarefas podem ser realizadas em paralelo ou com ações intercaladas, sem ordem fixa. | `T1 \|\|\| T2` |
| `\|[]\|` | Tarefas Concorrentes Comunicantes (Synchronization) | As tarefas ocorrem concorrentemente e trocam informações em tempo real durante a execução. | `T1 \|[]\| T2` |
| `[>` | Desativação / Interrupção (Disabling) | A tarefa T1 é interrompida ou cancelada pela ativação da tarefa T2. | `T1 [> T2` |
| `\|>` | Suspensão e Retomada (Suspend / Resume) | A tarefa T1 é pausada por T2 e, ao término de T2, é retomada exatamente do ponto onde parou. | `T1 \|> T2` |

![Referência teórica sobre CTT](../../../../assets/ctt_ref_eve.png)

**Figura 1 – Referência teórica sobre Árvores de Tarefas Concorrentes (CTT).**

*Fonte: Barbosa e Silva (2010).*


## 3. Análise de Tarefas por Perfil de Usuário

### 3.1. Perfil: Estudante

**Responsável pelo perfil:** Evellyn de Sousa Rocha

**Tarefa analisada:** Realizar e entregar uma atividade de uma disciplina pelo Microsoft Teams.

#### 3.1.1. Texto Explicativo e Contextualização

A tarefa analisada consiste em permitir que o estudante localize, realize e entregue uma atividade disponibilizada pelo professor no canal de uma disciplina no Microsoft Teams.

Na abordagem CTT (ConcurTaskTrees), a atividade é representada por meio de tarefas abstratas, tarefas do usuário, tarefas do sistema e tarefas interativas. Inicialmente, o estudante acessa o Microsoft Teams e entra no canal da disciplina desejada. Em seguida, visualiza as publicações disponíveis e identifica a atividade que precisa realizar.

Após localizar a atividade, o estudante acessa suas instruções, elabora a resposta ou anexa o arquivo solicitado e revisa o conteúdo antes de realizar a entrega. Durante esse processo, o sistema apresenta as informações da atividade, disponibiliza os recursos necessários para o envio e registra a confirmação da entrega.

As tarefas do usuário envolvem ações como acessar o canal, localizar a atividade, interpretar as instruções, elaborar a resposta e solicitar a entrega. As tarefas do sistema correspondem à exibição das publicações, disponibilização das instruções e registro da submissão. Já as tarefas interativas envolvem os momentos de interação entre estudante e plataforma, como selecionar a atividade, acessar seus detalhes, inserir respostas, anexar arquivos e confirmar a entrega.

#### 3.1.2. Relações Temporais e Categorização

**Nó raiz:** Realizar e entregar uma atividade de uma disciplina pelo Microsoft Teams.

**Operadores utilizados:**

- `>>` (Ativação): indica que uma tarefa somente pode começar após a conclusão da tarefa anterior. É utilizado para representar a sequência de acesso ao canal, localização da atividade, realização e entrega.
- `|||` (Concorrência): representa tarefas que podem ocorrer em qualquer ordem ou simultaneamente, quando não existe dependência entre elas. Pode ser aplicado às ações de elaborar uma resposta e anexar arquivos, conforme o formato da atividade.
- `[]>>` (Ativação com passagem de informação): representa a passagem de informações produzidas em uma tarefa para a seguinte, como as instruções da atividade utilizadas pelo estudante para elaborar sua resposta.

**Principais tarefas do sistema:**

- Exibir os canais e as publicações da disciplina.
- Apresentar as atividades disponibilizadas pelo professor.
- Exibir as instruções e os requisitos da atividade.
- Disponibilizar o campo de resposta ou a opção de anexar arquivos.
- Registrar a entrega da atividade.
- Exibir a confirmação de envio ao estudante.

#### 3.1.3. Estrutura de Decomposição e Operadores Temporais

A tarefa principal foi decomposta em quatro etapas: acessar o canal da disciplina, localizar a atividade, realizar a atividade e efetuar sua entrega.

**0. Realizar e Entregar uma Atividade no Microsoft Teams** — Tarefa Abstrata

- **1. Acessar o Canal da Disciplina** — Tarefa Abstrata
  - 1.1. Abrir o Microsoft Teams — Tarefa do Usuário
  - 1.2. Selecionar a equipe e o canal da disciplina — Tarefa Interativa
  - 1.3. Exibir as publicações disponíveis no canal — Tarefa do Sistema

- **2. Localizar a Atividade** — Tarefa Abstrata
  - 2.1. Visualizar as publicações e atividades disponíveis — Tarefa do Sistema
  - 2.2. Identificar a atividade desejada — Tarefa do Usuário
  - 2.3. Selecionar e acessar os detalhes da atividade — Tarefa Interativa

- **3. Realizar a Atividade** — Tarefa Abstrata
  - 3.1. Consultar as instruções e os requisitos da atividade — Tarefa Interativa
  - 3.2. Elaborar a resposta da atividade — Tarefa do Usuário
  - 3.3. Anexar o arquivo com a atividade realizada — Tarefa Interativa
  - 3.4. Revisar a resposta ou o arquivo anexado — Tarefa do Usuário

- **4. Entregar a Atividade** — Tarefa Abstrata
  - 4.1. Solicitar a entrega da atividade — Tarefa Interativa
  - 4.2. Registrar o envio da atividade — Tarefa do Sistema
  - 4.3. Exibir a confirmação de entrega — Tarefa do Sistema

#### 3.1.4. Diagrama Gráfico CTT

O diagrama gráfico representa a decomposição hierárquica da tarefa principal e as relações temporais entre suas subtarefas, considerando as categorias de tarefas descritas anteriormente.

**Figura 1 – Árvore de Tarefas Concorrentes (CTT) do perfil estudante.**

![Árvore CTT da funcionalidade analisada](../../../../assets/ctt_eve.png)

**Figura 2 – Árvore de Tarefas Concorrentes (CTT) da funcionalidade analisada por Evellyn.**

*Fonte: Elaborado pela autora.*


## 4. Referências Bibliográficas

BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação Humano-Computador*. Rio de Janeiro: Elsevier / Campus, 2010.

PATERNÒ, Fabio. *Model-Based Design and Evaluation of Interactive Applications*. London: Springer-Verlag, 1999.

PATERNÒ, Fabio. ConcurTaskTrees: An Engineered Notation for Task Models. In: DIAPER, Dan; STANTON, Neville (Eds.). *The Handbook of Task Analysis for Human-Computer Interaction*. Mahwah, NJ: Lawrence Erlbaum Associates, 2003. p. 483–503.

## 5. Agradecimentos à Inteligência Artificial

Agradecemos ao ChatGPT pelo apoio na organização e formatação deste documento em Markdown, na estruturação das tabelas. A ferramenta também auxiliou na revisão textual e na adequação do conteúdo para publicação no GitHub Pages. A análise, as decisões de modelagem e a validação do conteúdo permanecem sob responsabilidade dos autores.

# Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|---|---|---|---|---|
| 1.0 | 15/11 /2026 | Criação da página separada por estudante  | evellyn rocha | Lucas Sales |
| 1.1 | 20/11/2026 | Adição de informações que já estavam no git pages, poré m em outras paginas  não separadas por estudantes  | Evellyn Rocha | João Paulo |
