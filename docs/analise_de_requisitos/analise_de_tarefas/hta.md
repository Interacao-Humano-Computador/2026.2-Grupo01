# Análise Hierárquica de Tarefas (HTA – Hierarchical Task Analysis)

| Data       | Contribuição                                                                                                                                  | Autor(es)   | Revisor(es) |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ----------- |
| 06/10/2026 | Inserção da tabela de contribuição e atualização de diagrama HTA da tarefa de comunicação entre usuários, exclusão de estrutura não utilizada | Lucas Sales |             |

## 1. Introdução e Fundamentação Teórica

A aplicação da HTA na avaliação do **Teams** permite identificar gargalos na navegação, quebras de fluxo, redundâncias operacionais e pontos onde o sistema exige esforço cognitivo excessivo para a conclusão de tarefas do cotidiano universitário e administrativo.

---

## 2. Metodologia e Elementos da HTA

A modelagem HTA adota a seguinte estrutura:

* **Objetivo (Goal):** Um estado final de coisas que a pessoa deseja alcançar (ex: *Estruturar uma nova equipe de projeto*).
* **Subobjetivo (Subgoal):** Uma meta intermediária necessária para o atingimento de um objetivo superior.
* **Operação (Operation):** A unidade atômica da tarefa que não necessita de mais decomposição. Cada operação no nível folha é especificada pela tupla `<Input, Ação, Feedback>`:
  * **Input:** As condições de ativação ou informações necessárias para iniciar a operação.
  * **Ação:** O ato físico ou cognitivo executado pelo usuário ou sistema.
  * **Feedback:** A resposta visual ou auditiva fornecida pela interface indicando o resultado da ação.
* **Planos (Plans):** Regras formais que definem a sequência e as condições sob as quais os subobjetivos devem ser alcançados:
  * `>` **Sequencial:** Execução em ordem fixa (ex: `1 > 2`).
  * `/` **Seleção / Decisão:** Escolha de um caminho entre alternativas mutuamente exclusivas (ex: `2.1 / 2.2`).
  * `+` **Paralelo / Concorrente:** Atividades realizadas ao mesmo tempo ou em qualquer ordem (ex: `4.1 + 4.2`).

---

## 3. Análise de Tarefas

## 3.1 Comunicação entre usuários:

Nesta tarefa o usuário precisa se comunicar com outros usuários, para alinhamentos, esclarecimentos de dúvidas, e outras tarefas que possam apoiar o trabalho individual de cada um, os mesmos utilizam a plataforma teams, com a funcionalidade de chat como meio de realização desta tarefa.


| Objetivos / operações                         | Problemas e recomendações                                                                                                                                                                                                                                                                                                                                             |
| --------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **0. Se comunicar com um usuário** `1>2`      | **input:** necessidade de informar algo ou obter algo de um usuário<br>**feedback:** usuário recebeu a mensagem e retornou ou agiu conforme o esperado<br>**plano:** 1>2<br>**recomendação:** avaliar se o chat do Teams é o canal adequado ao assunto e à urgência                                                                                                   |
| **1. Definir conteúdo e destinatários** `1+2` | **plano:** 1+2, definir os dois ao mesmo tempo ou em qualquer ordem                                                                                                                                                                                                                                                                                                   |
| 1.1 Definir o assunto ou pedido               | **input:** demanda ou dúvida a resolver<br>**ação:** decidir o conteúdo essencial e a ação esperada do usuário<br>**feedback:** assunto e pedido formulados com clareza<br>**problema:** mensagem vaga, sem a ação esperada explícita<br>**recomendação:** deixar claro o que se espera e o prazo                                                                     |
| 1.2 Definir o assunto ou pedido               | **input:** demanda ou dúvida a resolver<br>**ação:** decidir o conteúdo essencial e a ação esperada do usuário<br>**feedback:** assunto e pedido formulados com clareza<br>**problema:** mensagem vaga, sem a ação esperada explícita<br>**recomendação:** deixar claro o que se espera e o prazo                                                                     |
| **2. Transmitir a mensagem** `1>2`            | **plano:** 1>2<br>**problema:** o usuário pode não perceber ou não entender formatos menos comuns (Loop, ações de apps)<br>**recomendação:** priorizar texto quando o objetivo é ser compreendido rapidamente                                                                                                                                                         |
| 2.1 Enviar mensagem de texto                  | **input:** conteúdo e destinatário definidos<br>**ação:** escrever, revisar e enviar o texto<br>**feedback:** mensagem aparece como enviada na conversa<br>**problema:** enviar com erro ou para a conversa errada<br>**recomendação:** revisar antes de enviar                                                                                                       |
| 2.2 Enviar emoji, gif ou sticker              | **input:** necessidade de expressar tom ou reação<br>**ação:** escolher o item e enviar<br>**feedback:** item aparece na conversa<br>**problema:** o usuário interpretar o tom de forma diferente do pretendido<br>**recomendação:** usar como complemento ao texto, não como única mensagem                                                                          |
| 2.3 Adicionar componente do Loop              | **input:** conteúdo que precisa ser editado ou acompanhado em conjunto (lista, tabela, tarefas)<br>**ação:** inserir o componente na conversa e preencher<br>**feedback:** componente visível e editável pelos participantes<br>**problema:** usuário não saber que pode editar ou não ter acesso<br>**recomendação:** avisar na mensagem que o componente é editável |
| 2.4 Realizar ação vinculada à app Microsoft   | **input:** necessidade de integrar outra ferramenta (agendar reunião, compartilhar arquivo, etc.)<br>**ação:** acionar a app a partir do chat<br>**feedback:** ação concluída e refletida na conversa<br>**problema:** erro de permissão ou dificuldade de localizar a ação<br>**recomendação:** confirmar com o usuário que ele recebeu o que foi compartilhado      |
| **3. Obter retorno dos usuários** `1+2`       | **plano:** 1+2                                                                                                                                                                                                                                                                                                                                                        |
| 3.1 Acessar conversa com usuário              | **input:** mensagem enviada<br>**ação:** abrir a conversa e verificar a resposta<br>**feedback:** resposta identificada ou ausência de resposta constatada<br>**problema:** perder a resposta entre muitas notificações<br>**recomendação:** definir um prazo para checar o retorno                                                                                   |

Para melhor visualização da imagem, com possibilidade de ampliar, [clique aqui](../../assets/hta-entrevista-Lucas.png)

<p align="center">Figura 1 – HTA - Esclarecimento de dúvidas com colega de trabalho.</p>
![HTA](../../assets/hta-entrevista-Lucas.png)
<p align="center">Autor - Lucas Sales.</p>

## Histórico de versão

### 3.2. Perfil 4: Chefe/Gestor

> **Responsável pelo Perfil:** Luccas Rodrigues 
> **Tarefa Analisada:** Estruturar Equipe de Projeto e Realizar Alinhamento Síncrono no Microsoft Teams

#### 1. Texto Explicativo e Contextualização

A tarefa do gestor/chefe abrange as responsabilidades de liderança, criação de ambientes de trabalho para novos projetos, definição de diretrizes de governança e permissões de acesso a arquivos, bem como a condução de reuniões síncronas de alinhamento com a equipe. A análise busca mapear os pontos de atrito entre a gestão de pessoas/arquivos e as configurações oferecidas pela plataforma Teams.

#### 2. Tabela de Análise Hierárquica de Tarefas (Tabela HTA)

| Objetivos / Operações                                               | Elementos da Operação (`<Input, Ação, Feedback>`) e Planos                                                                                                                                                                  | Problemas Identificados e Recomendações de IHC                                                                                                                                                                                |
| :------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **0. Estruturar equipe de projeto e realizar alinhamento síncrono** | **Plano:** Criar e configurar equipe (`1`), divulgar diretrizes (`2`), conduzir reunião (`3`) e consolidar registros (`4`). `Plano: 1 > 2 > 3 > 4`                                                                          | **Problema:** Excesso de etapas manuais espalhadas entre menus de configurações, calendário e chat.<br>**Recomendação:** Oferecer assistente de "Novo Projeto" que unifique a criação do grupo, permissões e reunião inicial. |
| **1. Criar e configurar espaço de trabalho da equipe**              | **Plano:** Criar a equipe com membros (`1.1`) e depois configurar as regras de permissão (`1.2`). `Plano: 1.1 > 1.2`                                                                                                        | **Problema:** Risco de membros ingressarem antes das permissões estarem ajustadas.<br>**Recomendação:** Permitir definir o perfil de permissões no próprio ato de criação da equipe.                                          |
| **1.1. Criar equipe no Teams e adicionar colaboradores**            | **Input:** Lista de e-mails/nomes dos colaboradores.<br>**Ação:** Acessar *Equipes > Criar Equipe*, digitar nome e incluir membros.<br>**Feedback:** Equipe visível na barra lateral e convites enviados.                   | **Problema:** Inclusão individual demorada para grupos grandes.<br>**Recomendação:** Permitir importação em lote via arquivo de lista ou grupo institucional pré-existente.                                                   |
| **1.2. Definir regras de governança e permissões**                  | **Input:** Painel de *Gerenciamento da Equipe*.<br>**Ação:** Desmarcar permissão de exclusão de arquivos e criação de canais privados.<br>**Feedback:** Caixas de seleção desmarcadas e regras ativas.                      | **Problema:** Opções de governança ocultas em submenus avançados.<br>**Recomendação:** Destacar atalhos de "Perfil de Segurança Padrão para Gestores" na tela principal.                                                      |
| **2. Divulgar diretrizes e pauta do projeto**                       | **Plano:** Publicar anúncio no Canal Geral (`2.1`) **OU** criar canal privado de gestão (`2.2`), conforme sensibilidade. `Plano: 2.1 / 2.2`                                                                                 | **Problema:** Avisos normais passam despercebidos no fluxo do chat.<br>**Recomendação:** Facilitar a alternância para o formato *Anúncio* com marcação de urgência.                                                           |
| **2.1. Publicar anúncio oficial no Canal Geral**                    | **Input:** Caixa de diálogo de nova conversa no canal.<br>**Ação:** Alterar tipo para *Anúncio*, digitar título e marcar como *Importante*.<br>**Feedback:** Postagem exibida com faixa vermelha e notificação disparada.   | **Problema:** Necessidade de lembrar de marcar manualmente como "Importante".<br>**Recomendação:** Sugerir automaticamente o rótulo de importância ao selecionar o modo Anúncio.                                              |
| **2.2. Criar canal privado para subgrupo de gestão**                | **Input:** Menu de opções da equipe.<br>**Ação:** Selecionar *Adicionar Canal*, marcar tipo *Privado* e escolher membros restritos.<br>**Feedback:** Novo canal criado com ícone de cadeado visível no menu.                | **Problema:** Dificuldade em migrar arquivos do canal geral para o canal privado criado posteriormente.<br>**Recomendação:** Fornecer opção direta de "Mover pasta para canal restrito".                                      |
| **3. Agendar e conduzir reunião síncrona**                          | **Plano:** Agendar evento no canal (`3.1`), iniciar chamada com gravação (`3.2`) e compartilhar pauta (`3.3`). `Plano: 3.1 > 3.2 > 3.3`                                                                                     | **Problema:** Reuniões agendadas fora do canal perdem o histórico de gravações e chat.<br>**Recomendação:** Definir o canal da equipe como destino padrão ao criar reuniões via Teams.                                        |
| **3.1. Agendar reunião vinculada ao canal**                         | **Input:** Formulário do *Calendário* no Teams.<br>**Ação:** Preencher título, horário, pauta e selecionar a equipe/canal.<br>**Feedback:** Evento confirmado no calendário e publicado no chat do canal.                   | **Problema:** Choque de horários com agendas externas (ex: Outlook).<br>**Recomendação:** Exibir indicador de disponibilidade dos membros em tempo real durante o agendamento.                                                |
| **3.2. Iniciar chamada com gravação e transcrição**                 | **Input:** Horário agendado atingido.<br>**Ação:** Clicar em *Ingressar*, abrir chamada e acionar *Iniciar Gravação e Transcrição*.<br>**Feedback:** Banner de notificação de gravação exibido para todos os participantes. | **Problema:** Esquecimento frequente em acionar a gravação no início da chamada.<br>**Recomendação:** Permitir configurar "Gravação Automática" na criação do convite.                                                        |
| **3.3. Compartilhar tela e coordenar pauta**                        | **Input:** Documento com a pauta aberto.<br>**Ação:** Clicar em *Compartilhar*, selecionar a janela e conduzir a discussão.<br>**Feedback:** Borda vermelha indicando tela compartilhada e visualização pelos membros.      | **Problema:** Dificuldade em visualizar chat/mão erguida enquanto compartilha tela inteira.<br>**Recomendação:** Aprimorar modo de apresentação com painel flutuante de participantes.                                        |
| **4. Consolidar registros e organizar entregáveis**                 | **Plano:** Disponibilizar gravação/ata (`4.1`) **EM PARALELO** à organização de pastas (`4.2`). `Plano: 4.1 + 4.2`                                                                                                          | **Problema:** Registros de reuniões ficam dispersos no feed de conversas.<br>**Recomendação:** Criar aba automática de "Recursos da Reunião" agrupando vídeo, transcrição e arquivos.                                         |
| **4.1. Disponibilizar gravação e ata no chat**                      | **Input:** Encerramento da videoconferência.<br>**Ação:** Verificar vídeo processado no chat e fixar mensagem com encaminhamentos.<br>**Feedback:** Mensagem fixada no topo do canal e vídeo acessível aos ausentes.        | **Problema:** Demora no processamento e disponibilização do link do vídeo gravado.<br>**Recomendação:** Notificar gestor no painel de atividades assim que o vídeo estiver pronto.                                            |
| **4.2. Organizar arquivos na aba de documentos**                    | **Input:** Arquivos recebidos durante a reunião.<br>**Ação:** Acessar a aba *Arquivos* do canal e mover documentos para pastas temáticas.<br>**Feedback:** Arquivos organizados em estrutura de diretórios e centralizados. | **Problema:** Arquivos do chat da chamada não vão automaticamente para a pasta do canal.<br>**Recomendação:** Unificar a pasta de anexos da reunião com o repositório principal do canal.                                     |

#### 3. Diagrama Gráfico HTA

![Diagrama HTA - Chefe/Gestor](../../assets/diagrama-hta-chefe.png)

---

## 4. Referências Bibliográficas

* BARBOSA, Simone Diniz Junqueiro; SILVA, Bruno Santana da. **Interação Humano-Computador**. Rio de Janeiro: Elsevier / Campus, 2010.
* DIAPER, Dan. **Hierarchical Task Analysis (HTA)**. In: DIAPER, Dan; STANTON, Neville (Eds.). *The Handbook of Task Analysis for Human-Computer Interaction*. Mahwah, NJ: Lawrence Erlbaum Associates, 2003. p. 67-142.

---

## 5. Histórico de Versão

| Versão | Data       | Descrição                                                                       | Autor(es)        | Revisor(es)      |
| ------ | ---------- | ------------------------------------------------------------------------------- | ---------------- | ---------------- |
| `1.0`  | 27/09/2026 | Criação da página.                                                              | Lucas Sales      | Luccas Rodrigues |
| `1.1`  | 27/09/2026 | Adição do diagrama hta de esclarecimento de uma dúvida com colegas de trabalho. | Lucas Sales      | Luccas Rodrigues |
| `1.2`  | 27/09/2026 | Atualização de estrutura da página                                              | Luccas Rodrigues | Lucas Sales      |
