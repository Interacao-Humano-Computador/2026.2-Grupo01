# **ANÁLISE DE TAREFAS EM IHC: MICROSOFT TEAMS**

**Análise Hierárquica de Tarefas (HTA) e ConcurTaskTrees (CTT)**  
*Fundamentado em Simone Barbosa & Bruno Silva (2010), Capítulo 8 (Seção 8.4, p. 163-176)*

# **1\. INTRODUÇÃO E CENÁRIO DE USO**

Com base nos dados coletados na entrevista com a participante **Leidiane Santos (Perfil Estudante, 48 anos, nível básico de informática)**, identificou-se que a sua tarefa central na plataforma Microsoft Teams é o **Acesso e Visualização de Aulas Síncronas (Ao Vivo e Gravadas)**.

# **2\. ANÁLISE HIERÁRQUICA DE TAREFAS (HTA \- HIERARCHICAL TASK ANALYSIS)**

A HTA (Análise Hierárquica de Tarefas) desdobra os objetivos do usuário em subobjetivos, ações e operações, identificando o plano de execução e possíveis gargalos de usabilidade (Barbosa & Silva, 2010, p. 164).

## **Tabela HTA: Tarefa 0 \- Assistir à Aula Gravada de uma Disciplina**

| Objetivo / Subobjetivo | Operações / Ações | Plano e Condições |
| :---- | :---- | :---- |
| **0\. Assistir à aula gravada de uma disciplina** | Tarefa principal da estudante no Microsoft Teams. | **Plano 0:** Fazer 1, depois 2, depois 3\. Se o link estiver expirado, fazer 3.1a. |
| **1\. Acessar o ambiente do curso** | 1.1 Iniciar o aplicativo Microsoft Teams.1.2 Autenticar com e-mail institucional/login. | **Plano 1:** Executar 1.1 e 1.2 sequencialmente ao ligar o computador. |
| **2\. Localizar o canal da disciplina** | 2.1 Clicar no ícone 'Equipes' na barra lateral.2.2 Selecionar a equipe da disciplina correspondente.2.3 Selecionar o canal 'Geral'. | **Plano 2:** Fazer 2.1; escolher a equipe em 2.2 e abrir o canal em 2.3. |
| **3\. Encontrar e reproduzir o vídeo da aula** | 3.1 Rolar o feed do chat procurando a mensagem da reunião encerrada.3.2 Clicar no cartão de mídia/link do vídeo.3.3 Aguardar o carregamento no player Stream/OneDrive.3.4 Dar play no vídeo. | **Plano 3:** Fazer 3.1 até achar o card; em seguida 3.2 e 3.3. Se 3.2 falhar por erro de permissão/expiração, acionar a **Solução de Contorno 3.1a** (solicitar link ao professor via mensagem externa). |

## **Representação Textual / Diagrama Hierárquico HTA**

0\. Assistir à aula gravada no Teams

 ![][image1]  
*Imagem gerada por IA.*

# **3\. ÁRVORE DE TAREFAS CONCORRENTES (CTT \- CONCURTASKTREES)**

A CTT (Paternò, 1999; Barbosa & Silva, 2010, p. 173\) categoriza os tipos de tarefas com base nos atores que as realizam e define as relações de precedência, concorrência e desativação entre os nós.

## **Legenda dos Tipos de Tarefas em CTT:**

* **Tarefa do Usuário (User Task):** Atividade cognitiva/processo mental interno do usuário.  
* **Tarefa do Sistema (System Task):** Processamento automático executado pelo sistema.  
* **Tarefa de Interação (Interactive Task):** Ação direta do usuário sobre a interface com resposta do sistema.  
* **Tarefa Abstrata (Abstract Task):** Tarefa complexa desdobrada em subtarefas.

## **Operadores de Relação Temporal em CTT:**

* `>>` **Sequência:** A tarefa da esquerda deve ser concluída antes da tarefa da direita iniciar.  
* `[]>` **Desativação (Disabling):** A tarefa da esquerda é interrompida assim que a da direita é iniciada.  
* `|||` **Concorrência:** As tarefas podem ser executadas simultaneamente.

## **Estrutura e Modelagem CTT da Tarefa:**

* **0\. Assistir Aula Gravada**  (Abstract Task)  
  * **1\. Autenticar no Sistema** (Abstract Task)  
    * 1.1 Abrir Teams  (Interactive Task) `>>`  
    * 1.2 Processar Login (System Task)  
  * `>>`  
  * **2\. Localizar Aula**  (Abstract Task)  
    * 2.1 Navegar até Canal  (Interactive Task) `>>`  
    * 2.2 Buscar Card de Gravação no Chat  (User Task \- Processo de busca visual) `>>`  
    * 2.3 Clicar no Link do Vídeo  (Interactive Task)  
  * `[]>` (Desativação da busca ao abrir o player)  
  * **3\. Assistir ao Vídeo**  (Abstract Task)  
    * 3.1 Carregar Player de Mídia (System Task) `>>`  
    * 3.2 Assistir ao Conteúdo  (User Task) `|||`  
    * 3.3 Controlar Reprodução (Pausar/Avançar)  (Interactive Task)

# **4\. ANÁLISE DE PROBLEMAS E RECOMENDAÇÕES DE IHC**

Com base nos modelos HTA e CTT aplicados ao perfil de Leidiane:

1. **Quebra no Fluxo no Passo 3.2 (HTA):** O link de gravação expira na nuvem, interrompendo o ciclo de ação da estudante (Golfo de Execução/Avaliação).  
   * **Recomendação:** Criar uma aba fixa de *"Repositório de Aulas"* no topo do canal com armazenamento permanente e indicador de validade visível.  
2. **Carga Cognitiva Elevada no Passo 2.2 (CTT):** A tarefa do usuário (*Buscar Card no Chat*) exige rolar manualmente conversas extensas.  
   * **Recomendação:** Implementar filtro rápido e botão de atalho *"Ver Gravações Anteriores"* na barra de ferramentas do canal.

**Referência Bibliográfica de Base:**  
BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação Humano-Computador*. Rio de Janeiro: Elsevier, 2010\. Capítulo 8 (Análise de Tarefas).

*Esse documento foi gerado com auxilio de IA*

# **Gabarito e Modelo de Artefatos em IHC**

# **Modelo de Persona e Caso de Uso**

**Fundamentado em Simone Barbosa & Bruno Silva (2010)**

# **1\. Artefato: Persona (Capítulo 6, Seção 6.2, p. 175-179)**

| Parâmetro | Detalhe |
| :---- | :---- |
| **Nome e Sobrenome:** | Leidiane Santos |
| **Foto / Representação:** | ![][image1] |
| **Idade e Demografia:** | 43 anos, residente em Brasília-DF, estudante do 1º semestre do curso de Administração da plataforma Kodie / Ensino Superior em andamento |
| **Status da Persona:** | \[X\] Primária (foco principal)  \[ \] Secundária  \[ \] Stakeholder  \[ \] Antipersona |
| **Frase de Efeito (Motto):** | *"Prefiro ferramentas simples e organizadas em um só lugar do que ter que mexer em vários sistemas confusos."* |
| **Perfil Profissional e Ocupação:** | Estudante universitária do 1º semestre no turno da noite; conciliando estudos com a rotina familiar e profissional. |
| **Objetivos do Usuário:** | 1\. Acessar as aulas síncronas ao vivo e localizar gravações passadas de forma direta no Microsoft Teams sem perder o link.2. Manter uma rotina de estudos simples e centralizada sem precisar alternar entre múltiplos aplicativos para entregar tarefas. |
| **Habilidades e Competências:** | Nível computacional básico; utiliza recursos essenciais de informática e smartphone no dia a dia; prefere aprender na prática sob orientação direta ou explicações passo a passo. |
| **Tarefas Principais e Rotina:** | Acessar o Teams nos horários de aula pelo notebook; clicar no link de reunião recebido; tentar rever aulas gravadas antes de avaliações; utilizar o WhatsApp para alinhamento rápido com colegas. |
| **Relacionamentos:** | Interage com colegas de turma por grupos de mensagem paralelos (WhatsApp) para tirar dúvidas e combinar atividades; depende da organização e criação das turmas por parte dos professores. |
| **Requisitos e Necessidades:** | Interface limpa e despoluída; aviso visual claro para links de reuniões ao vivo; aba centralizada de gravações e materiais que não expirem ou se percam no chat. |
| **Expectativas do Sistema:** | Espera que ao entrar na equipe da disciplina, a aula ao vivo ou a gravação da aula anterior esteja visível e acessível em um único clique. |

# **2\. Artefato: Caso de Uso / Cenário de Interação (Capítulo 7, Seção 7.2, p. 209-212)**

| Parâmetro | Detalhe |
| :---- | :---- |
| **Identificador e Título:** | UC01 \- Acesso e Visualização de Aula Gravada no Microsoft Teams |
| **Ator / Persona Protagonista:** | Leidiane Santos (Persona Primária) |
| **Objetivo do Ator:** | Localizar e assistir a uma gravação de aula síncrona encerrada para revisar o conteúdo da disciplina. |
| **Contexto de Uso:** | Em casa, no período da tarde, utilizando um notebook pessoal conectado à internet residencial via Wi-Fi. |
| **Precondições:** | 1\. O Microsoft Teams deve estar instalado ou acessível via navegador operacional.2. O usuário deve estar autenticado em sua conta de estudante.3. A aula síncrona deve ter sido gravada e encerrada anteriormente pelo professor. |
| **Fluxo Principal (Passo a Passo):** | **1\. Ação do Usuário:** Leidiane abre o Microsoft Teams e navega até a guia 'Equipes'.**2\. Resposta do Sistema:** O sistema exibe a lista de equipes/disciplinas nas quais a aluna está matriculada.**3\. Ação do Usuário:** A aluna seleciona o canal Geral da disciplina desejada.**4\. Resposta do Sistema:** O sistema carrega o feed de postagens e o histórico do chat da reunião realizada.**5\. Ação do Usuário:** Leidiane rola o histórico do chat procurando o card do vídeo da aula gravada e clica no link do vídeo.**6\. Resposta do Sistema:** O sistema abre o player de mídia do Microsoft Stream/OneDrive e inicia a reprodução do vídeo da aula. |
| **Fluxos Alternativos / Exceções:** | **FA01 \- Link de Gravação Expirado ou Indisponível:** No passo 5, caso o link da gravação tenha expirado ou a permissão tenha caducado, o sistema exibe a mensagem *"Este vídeo expirou ou você não tem permissão para acessá-lo"*. O sistema apresenta um botão para 'Solicitar Acesso ao Proprietário/Professor'.**FA02 \- Dificuldade de Localização no Chat Poluído:** No passo 5, caso haja excesso de mensagens no chat, a aluna utiliza o campo de busca digitando *"Gravação"*, e o sistema filtra os cards de reuniões anteriores. |
| **Pós-condições (Resultado Final):** | A aluna assiste à gravação da aula, podendo pausar e retornar, concluindo sua revisão de conteúdo para a matéria. |
| **Perguntas / Avaliação de IHC Associada:** | O link da gravação está visível em menos de 3 cliques? A interface sinaliza de forma clara o tempo restante de validade da gravação antes de expirar? |

## **Referência Bibliográfica de Base**

BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. **Interação Humano-Computador**. Rio de Janeiro: Elsevier, 2010\. Capítulos 6 e 7\.

*Esse documento foi gerado com auxilio de IA*

# **Avaliação de Interação Humano-Computador**

# **Registro de Entrevista Simulada — Plataforma Microsoft Teams**

---

## **Ficha de Identificação da Sessão**

| Parâmetro | Detalhe |
| :---- | :---- |
| **Data e Horário** | 28/09/2026 das 14:00 às 14:35 |
| **Entrevistador(a)** | Rayca Yorrara |
| **Entrevistado(a)** | L.S. (Leidiane Santos) |
| **Perfil de Usuário** | **\[X\] Estudante**      \[ \] Professor      \[ \] Funcionário      \[ \] Gestor |
| **Autorizações** | **TCLE:** Aceito   |   **Gravação:** Autorizada (Áudio/Vídeo) |

---

# **Fase 1: Apresentação e Cuidados Éticos**

O protocolo de apresentação inicial foi devidamente conduzido. O script de abertura foi lido na íntegra, esclarecendo os objetivos da avaliação de IHC e garantindo a privacidade dos dados coletados.

* **Status da Etapa:** Termo de Consentimento Livre e Esclarecido (TCLE) aceito formalmente; gravação de áudio e vídeo iniciada.

---

# **Fase 2: Aquecimento (Perfil e Experiência Técnica)**

# **1\. Dados de Perfil Geral**

*  **Pergunta:** Qual a sua idade, área de atuação/curso e tempo de vínculo na instituição?  
* **Resposta:** *"Tenho 48 anos, faço um curso de  Administração da plataforma kodie e estou no 1° semestre."*

# **2\. Cargo e Função Exercida**

* **Pergunta:** Qual é exatamente a sua função principal hoje? Há quanto tempo exerce esse papel?  
* **Resposta:** *"Sou estudante."*

# **3\. Experiência Tecnológica e Computacional**

* **Pergunta:** Como você avalia o seu nível de familiaridade com computadores e ferramentas digitais? Prefere aprender novas ferramentas mexendo, lendo guias ou com explicações de terceiros?  
* **Resposta:** *"Considero meu nível básico. Consigo somente usar o básico para o dia a dia. Prefiro aprender com alguém me ensinando."*

# **4\. Histórico com o Microsoft Teams**

* **Pergunta:** Há quanto tempo você utiliza o Microsoft Teams? Com que frequência acessa e em quais dispositivos?  
* **Resposta:** *"Comecei a usar no início do curso, desde o início das matérias online. Acesso durante as aulas , principalmente pelo notebook."*

---

# **Fase 3: Parte Principal (Mapeamento de Tarefas e Uso do Teams)**

# **Tópico 1: Função e Atividades Principais na Plataforma**

* **Pergunta:** Quais são as suas principais atividades no Teams durante o semestre? Quais realiza com mais frequência?  
* **Resposta:** *"Uso principalmente para assistir às aulas ao vivo."*  
* **Pergunta:** Quais tarefas você gosta mais e quais gosta menos de fazer? Por quê?  
* **Resposta:** *"Uso apenas para assistir às aulas, as demais demandas da faculdade são feitas em outro aplicativo."*

# **Tópico 2: Utilização dos Recursos do Teams e Preferências**

* **Pergunta:** Quais recursos do Teams você mais utiliza no seu dia a dia? O que acha da organização das informações dentro das equipes e canais?  
* **Resposta:** *"Uso apenas os links para entrar nas reuniões. Sobre a organização, acho um pouco confusa, não acho que eu saberia usar sozinha o app."*  
* **Pergunta:** Como é a experiência com a entrega de trabalhos e busca por gravações e materiais? O sistema de notificações ajuda ou atrapalha?  
* **Resposta:** *"A entrega de trabalhos (Tarefas) é feita em outro aplicativo, Mas achar gravações é chato porque o link expira ou fica perdido no chat da reunião."*

# **Tópico 3: Divisão de Responsabilidades e Autonomia**

* **Pergunta:** Você tem autonomia para criar suas próprias equipes de trabalho em grupo/canais de estudo ou depende da criação por parte de terceiros/professores? Como isso afeta o seu grupo?  
* **Resposta:** *"Nós, alunos, conseguimos criar chats em grupo ou até equipes simples entre nós, mas para a disciplina oficial dependemos 100% do professor criar a turma e nos adicionar. Para trabalhos de grupo, costumamos criar apenas um chat em grupo, pois criar uma equipe inteira no Teams dá muito trabalho."*

# **Tópico 4: Dificuldades, Problemas de Usabilidade e Soluções de Contorno**

* **Pergunta:** Já aconteceu de você tentar realizar uma tarefa no Teams e não conseguir ou se sentir confusa? O que aconteceu e como se resolveu?  
* **Resposta:** *"Sim\! Uma vez tentei abrir uma auula já encerrada e o link nao estava funcionando."*  
* **Pergunta:** Você utiliza outras ferramentas em paralelo com o Teams para realizar suas atividades? Por quê?  
* **Resposta:** *"Sim, uso a plataforma oferecida pelo meu curso"*

---

# **Fase 4: Desaquecimento e o "Sistema Ideal"**

# **1\. O Conceito do Sistema Ideal**

* **Pergunta:** Se você pudesse redesenhar o Microsoft Teams ou criar a plataforma ideal para a sua rotina de estudante, como ela seria?  
* **Resposta:** *"Seria uma plataforma bem mais leve e limpa, sem muitas funções ."*

# **2\. Mudanças e Melhorias Prioritárias**

* **Pergunta:** Se você pudesse mudar apenas 1 ou 2 coisas no Microsoft Teams hoje, o que mudaria?  
* **Resposta:** *"1. Melhoraria a busca interna, tornando mais fácil achar arquivos e gravações antigas."*

# **3\. Recomendações do Usuário**

* **Pergunta:** Que dica ou conselho você daria para os designers que projetam o Microsoft Teams?  
* **Resposta:** *"Pensar na simplicidade. Nem todo estudante é especialista em tecnologia. Deixar as coisas principais visíveis em um só clique facilita muito para quem estuda e trabalha ao mesmo tempo."*

---

# **Fase 5: Conclusão e Encerramento**

* **Comentários Espontâneos:** A participante ressaltou que, apesar de o Teams ser completo, a poluição visual das equipes com muitas mensagens acaba cansando ao longo do semestre.  
* **Status Final:** Entrevista finalizada com sucesso e gravação encerrada.

Link da gravação [Gravação da entrevista](https://youtu.be/9JlWqc2Z_J4?si=nRgSH6pHmylpWIJ8)  
*Esse documento foi gerado com auxilio de IA*

