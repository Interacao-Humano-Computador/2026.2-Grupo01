# Planejamento da Avaliação Formativa: Análise de Tarefas e Storyboards (Framework DECIDE)

## Tabela de contribuição

| Data       | Contribuição                                                                                              | Autor(es)  | Revisor(es) |
| ---------- | --------------------------------------------------------------------------------------------------------- | ---------- | ----------- |
| 13/10/2026 | Criação da página com o planejamento completo da avaliação formativa, organizado pelas letras do DECIDE.  | João Paulo | A definir   |

## 1. Introdução

Este documento planeja a **avaliação formativa** do redesenho do Microsoft Teams, com foco em dois artefatos: a **análise de tarefas** (HTA e CTT) e os **storyboards** elaborados na Etapa 4. Na Engenharia de Usabilidade de Mayhew, processo adotado pelo grupo ([Processo de Design](processo_de_design.md)), a avaliação é feita durante a elaboração da solução, quando os custos de correção ainda são baixos (BARBOSA et al., 2021, Seção 11.3, p. 251).

O planejamento segue o framework **DECIDE** (PREECE et al., 2002, apud BARBOSA et al., 2021, Seção 11.8, p. 264), que orienta o planejamento, a execução e a análise de uma avaliação de IHC em seis atividades interligadas e iterativas:

<p><strong>Tabela 1:</strong> Atividades do framework DECIDE e onde cada uma é tratada neste documento</p>

| Letra | Atividade (BARBOSA et al., 2021, p. 264) | Seção |
| :---: | :--- | :---: |
| **D** | **D**eterminar os objetivos da avaliação | 3 |
| **E** | **E**xplorar as perguntas a serem respondidas | 4 |
| **C** | Escolher (***C**hoose*) os métodos de avaliação | 5 |
| **I** | **I**dentificar e administrar as questões práticas | 6 |
| **D** | **D**ecidir como lidar com as questões éticas | 7 |
| **E** | Avaliar (***E**valuate*), interpretar e apresentar os dados | 8 |

<p><em>Fonte: adaptado de Barbosa et al. (2021, p. 264).</em></p>

Como o livro-base ressalta, as atividades se influenciam: se uma decisão prática mudar (por exemplo, a falta de participantes de algum perfil), os objetivos e os métodos precisam ser revistos. Por isso a Seção 9 registra os riscos e as decisões de contingência.

### 1.1. O que significa "avaliar a análise de tarefas"

A análise de tarefas descreve o trabalho dos usuários em termos de objetivos, subobjetivos, planos e operações (BARBOSA et al., 2021, Seção 8.4, p. 163-167). Ela é avaliada em duas frentes complementares:

1. **Validade do modelo:** verificar com as partes interessadas se a decomposição de cada tarefa representa o que os usuários realmente fazem. É o passo 5 da HTA, "verificar a validade da decomposição junto às partes interessadas" (DIAPER, 2003, apud BARBOSA et al., 2021, p. 167).
2. **Uso do modelo como referência de avaliação:** comparar o caminho previsto na HTA/CTT com o caminho que os participantes seguem nos storyboards. O livro descreve essa forma de avaliação baseada em modelos de tarefas e registros de interação (BARBOSA et al., 2021, Seção 11.7.4, p. 262).

## 2. Escopo da avaliação

Raramente se avalia o sistema inteiro: é preciso delimitar partes da interface, tarefas e perfis (BARBOSA et al., 2021, Seção 11.7.2, p. 258). O escopo deste planejamento usa as **tarefas de referência T1 a T4** já definidas nas [Metas de Usabilidade](../analise_de_requisitos/metas_usabilidade.md), uma por perfil de usuário.

<p><strong>Tabela 2:</strong> Escopo: tarefas, artefatos de análise de tarefas e artefato avaliado</p>

| Código | Perfil | Tarefa de referência | Modelos de tarefa avaliados | Artefato de interface avaliado |
| :---: | :--- | :--- | :--- | :--- |
| **T1** | Estudante | Acessar e assistir à aula gravada de uma disciplina | HTA e CTT do Estudante | Storyboard(s) de T1 |
| **T2** | Professor | Publicar uma atividade para a turma | HTA e CTT do Professor | Storyboard(s) de T2 |
| **T3** | Funcionário | Esclarecer uma dúvida com um colega de outro setor | HTA (Comunicação entre usuários) e CTT do Funcionário | Storyboard(s) de T3 |
| **T4** | Gestor | Estruturar uma equipe de projeto e realizar o alinhamento síncrono | HTA e CTT do Gestor (nós 0 a 4.2) | Storyboard(s) de T4 |

<p><em>Fonte: João Paulo (2026), a partir das Metas de Usabilidade e da análise de tarefas do projeto.</em></p>

**Momento no processo:** avaliação **formativa**, sobre artefatos de baixa fidelidade (storyboards) e sobre modelos de tarefa, antes de existir uma solução executável. Esse é um uso previsto pelo livro-base: esboços de tela, storyboards e modelagem da interação servem de insumo para a avaliação formativa (BARBOSA et al., 2021, p. 251).

**Fora do escopo:** avaliação somativa, versão implementada do redesenho e as demais funcionalidades do Teams não cobertas por T1 a T4.

**Pré-requisito de qualidade dos artefatos:** antes de qualquer sessão com participantes, os modelos T1 a T4 devem estar completos e consistentes entre si (ver Seção 5.1, método M1). Tarefas sem HTA ou CTT concluídos não podem entrar na rodada.

## 3. D — Determinar os objetivos da avaliação

O avaliador deve determinar os objetivos gerais, **por que** e **para quem** eles são importantes (BARBOSA et al., 2021, p. 264). Os objetivos abaixo são derivados das metas de avaliação do projeto (apropriação de tecnologia, alternativas de design, conformidade com padrão e problemas na interação; ver [Metas de Usabilidade](../analise_de_requisitos/metas_usabilidade.md), Seção 2).

<p><strong>Tabela 3:</strong> Objetivos da avaliação, interessados e justificativa</p>

| ID | Objetivo | Para quem é importante | Por que é importante |
| :---: | :--- | :--- | :--- |
| **O1** | Verificar se a **análise de tarefas** (HTA/CTT) representa corretamente o trabalho dos usuários de cada perfil | Equipe de design; usuários representados pelas personas | Os storyboards, as metas e o guia de estilo derivam desses modelos; um modelo incorreto propaga o erro para o redesenho |
| **O2** | Identificar **problemas na interação e na interface** dos storyboards ao executar T1 a T4 | Equipe de design; usuários dos quatro perfis | Corrigir cedo é mais barato; os problemas relatados nas entrevistas (onde postar, notificações em excesso, busca por arquivos e vídeos) são o ponto de partida |
| **O3** | **Comparar alternativas de design** de storyboard para as tarefas em que houver mais de uma proposta | Equipe de design | Permite escolher a solução mais eficiente, mais fácil de aprender e preferida pelos usuários |
| **O4** | Verificar se o redesenho caminha para as **metas de usabilidade** M1 a M5 (indicadores I1 a I12) | Equipe de design; professor da disciplina | Define se o redesenho precisa de nova iteração antes da próxima etapa |

<p><em>Fonte: João Paulo (2026), a partir de Barbosa et al. (2021, Seção 11.2) e das Metas de Usabilidade do projeto.</em></p>

A conformidade com padrão (WCAG 2.2, convenções do Windows e terminologia do domínio) é verificada pela própria equipe, sem participantes, durante a consolidação dos artefatos, conforme a Seção 2.3 das Metas de Usabilidade. Ela não é um objetivo desta rodada com usuários.

## 4. E — Explorar as perguntas a serem respondidas

Cada objetivo é desdobrado em perguntas específicas que operacionalizam a investigação, considerando o perfil dos usuários-alvo e suas atividades (BARBOSA et al., 2021, Seção 11.2, p. 249-251, Tabela 11.1). A coluna "Indicador" liga as perguntas às faixas de valores da Tabela 4 das Metas de Usabilidade.

<p><strong>Tabela 4:</strong> Perguntas da avaliação, por objetivo</p>

| ID | Obj. | Pergunta | Indicador |
| :---: | :---: | :--- | :---: |
| **Q1** | O1 | Cada subobjetivo e operação da HTA corresponde a algo que o usuário de fato faz? Há etapas faltando, sobrando ou na ordem errada? | — |
| **Q2** | O1 | Os planos (sequência, seleção, paralelo) refletem as circunstâncias reais, ou o usuário usa outro caminho? | — |
| **Q3** | O1 | Os problemas e as recomendações registrados na HTA (por exemplo, no critério p × c) são reconhecidos pelos usuários como relevantes? | — |
| **Q4** | O1 | O caminho seguido pelos participantes nos storyboards coincide com o caminho previsto na HTA e no CTT? Onde diverge e por quê? | I7 |
| **Q5** | O2 | O usuário consegue concluir a tarefa de referência? Com que frequência conclui sem ajuda? | I1 |
| **Q6** | O2 | Quantos e quais erros ocorrem, em que parte do storyboard e com que frequência? | I2, I8 |
| **Q7** | O2 | O usuário percebe que a ação correta está disponível, associa-a ao efeito desejado e percebe que está progredindo? | — |
| **Q8** | O2 | O usuário precisou de ajuda ou orientação? Em que momento e com qual dúvida? | I3 |
| **Q9** | O2 | O usuário se recupera sozinho dos erros? | I9 |
| **Q10** | O2 | O usuário entende o que significa e para que serve cada área da tela? | I10 |
| **Q11** | O3 | Qual alternativa é mais eficiente (menos passos, menos erros) e mais fácil de aprender? | I1, I2, I7 |
| **Q12** | O3 | Qual alternativa os usuários preferem, e por quê? | — |
| **Q13** | O4 | Qual é a satisfação geral com o redesenho? | I11 |
| **Q14** | O4 | O usuário tem sensação de controle sobre notificações e de ambiente limpo? | I12 |
| **Q15** | O4 | Quais indicadores ficam nas faixas inaceitável, aceitável e ideal? | I1 a I12 |

<p><em>Fonte: João Paulo (2026), com base nas perguntas-exemplo de Barbosa et al. (2021, Tabela 11.1) e nos passos da HTA (Diaper, 2003, apud Barbosa et al., 2021, p. 166-167).</em></p>

As perguntas Q5 a Q10 seguem o objetivo "identificar problemas na interação e interface" da Tabela 11.1 do livro-base. A pergunta Q7 reúne as perguntas P1 a P4 do percurso cognitivo (BARBOSA et al., 2021, p. 273).

## 5. C — Escolher os métodos de avaliação

Os métodos devem responder às perguntas e atingir os objetivos, considerando prazo, orçamento, equipamentos e a experiência dos avaliadores (BARBOSA et al., 2021, p. 264). O grupo tem prazo curto, equipe de seis integrantes sem experiência prévia com os métodos, e acesso limitado a usuários dos quatro perfis. As Tabelas 12.10, 12.11 e 12.12 do livro-base orientam a escolha:

<p><strong>Tabela 5:</strong> Adequação dos métodos considerados ao objetivo desta avaliação</p>

| Método | Alternativas de design | Problemas de IHC | Uso formativo | Dados predominantes |
| :--- | :---: | :---: | :---: | :---: |
| Entrevistas | + | ++ | ++ | Qualitativos |
| Grupos de foco | +++ | +++ | ++ | Qualitativos |
| Percurso cognitivo | ++ | +++ | ++ | Qualitativos |
| Prototipação em papel | +++ | +++ | ++ | Qualitativos |
| Teste de usabilidade | ++ | +++ | + | Quantitativos |
| Avaliação de comunicabilidade | ++ | +++ | + | Qualitativos |

<p><em>Fonte: João Paulo (2026), reproduzindo a classificação das Tabelas 12.10, 12.11 e 12.12 de Barbosa et al. (2021, p. 307-308).</em></p>

### 5.1. Métodos escolhidos

O livro recomenda combinar métodos complementares e executar ao menos uma avaliação empírica, porque os usuários revelam o que os avaliadores não preveem (BARBOSA et al., 2021, p. 307-308). Por isso a avaliação combina uma inspeção rápida da equipe com uma observação com participantes:

<p><strong>Tabela 6:</strong> Métodos escolhidos, objetivo atendido e justificativa</p>

| ID | Método | Tipo | Objetivos | Justificativa |
| :---: | :--- | :--- | :---: | :--- |
| **M1** | **Validação da decomposição da HTA/CTT com os interessados** (entrevista curta usando o próprio diagrama) | Investigação | O1 | É o passo 5 da HTA. Entrevistas dão dados qualitativos sobre a representação do trabalho e podem usar o modelo como roteiro |
| **M2** | **Percurso cognitivo** sobre os storyboards, guiado pelas ações da HTA | Inspeção | O2, O3 | Rápido e sem usuários; avalia a facilidade de aprendizado, meta M1 de alta prioridade; usa o modelo de tarefas como lista de ações (BARBOSA et al., 2021, p. 272-274). Antecipa problemas antes das sessões com participantes |
| **M3** | **Prototipação em papel** com os storyboards e participantes dos quatro perfis | Observação | O2, O3, O4 | Indicada para avaliação formativa de soluções parciais e de baixa fidelidade e para comparar alternativas de design (BARBOSA et al., 2021, p. 303) |
| **M4** | **Comparação com o modelo de tarefas** (caminho observado × caminho da HTA/CTT) | Análise dos dados de M3 | O1 | Avalia o uso real contra o previsto pelo designer (BARBOSA et al., 2021, p. 262) |
| **M5** | **Questionário pós-teste (SUS) e entrevista pós-teste** | Investigação | O4 | Coleta satisfação (I11), controle sobre notificações (I12) e compreensão das áreas da tela (I10) |

<p><em>Fonte: João Paulo (2026).</em></p>

**Por que não o teste de usabilidade como método principal:** o livro o classifica como mais apropriado para avaliação somativa, sobre uma solução executável (BARBOSA et al., 2021, p. 308). Nesta rodada ele serve como inspiração para o que se mede (sucesso, erros, tempo, ajuda, opinião), mas as sessões usam protótipos em papel.

**Execução em duas camadas:**

- **Camada 1 (equipe, sem participantes):** M2 sobre todos os storyboards e M1 em paralelo ao recrutamento.
- **Camada 2 (com participantes):** M3, M4 e M5 na mesma sessão, com o roteiro do Apêndice A.

### 5.2. Quais indicadores podem ser medidos nesta rodada

As faixas de valores das Metas de Usabilidade foram definidas para um teste de usabilidade. Com storyboards em papel, nem todos os indicadores são válidos. A Tabela 7 registra a decisão, para não comparar valores que o método não produz de forma confiável.

<p><strong>Tabela 7:</strong> Mensurabilidade dos indicadores I1 a I12 com storyboards em papel</p>

| Indicador | Medido nesta rodada? | Como / por quê |
| :---: | :---: | :--- |
| **I1** Conclusão na primeira tentativa, sem ajuda | Sim | Registro de sucesso por participante e tarefa |
| **I2** Erros por tarefa | Sim | Contagem no formulário de observação |
| **I3** Consultas de ajuda ou orientação | Sim | Registro do observador; no papel, toda dúvida do participante conta |
| **I4** Conclusão ao repetir a tarefa | Parcial | Só se a sessão tiver segunda execução (Apêndice A, opcional) |
| **I5** Redução do tempo na segunda execução | Não | O tempo da simulação em papel depende do avaliador que opera o protótipo |
| **I6** Tempo de conclusão vs. Teams atual | Somente a linha de base | Medir o tempo no Teams atual (valor de referência); a comparação fica para o protótipo executável |
| **I7** Passos observados vs. caminho da HTA | Sim | Razão entre passos executados e passos do caminho ideal (M4) |
| **I8** Erros de destino (postar, enviar, excluir no lugar errado) | Sim | Principalmente em T2 e T4 |
| **I9** Recuperação sozinho dos erros | Sim | Proporção de erros corrigidos sem ajuda |
| **I10** Explicação correta da função de cada área da tela | Sim | Pergunta aberta no pós-teste |
| **I11** SUS | Sim, com cautela | Aplicado, mas interpretado como indício, pois o participante avaliou um esboço |
| **I12** Controle sobre notificações e ambiente limpo | Sim | Itens de 5 pontos no pós-teste |

<p><em>Fonte: João Paulo (2026), a partir da Tabela 4 das Metas de Usabilidade.</em></p>

### 5.3. Rastreabilidade entre tarefas, modelos, storyboards e indicadores

A matriz abaixo garante que cada storyboard esteja associado às especificações de tarefa (atividade 4.2 do cronograma) e que cada nó relevante da HTA seja exercitado. Os nós de T4 vêm da HTA existente; os demais devem ser preenchidos pela equipe a partir dos diagramas de cada perfil.

<p><strong>Tabela 8:</strong> Matriz de rastreabilidade (a completar pela equipe)</p>

| Tarefa | Nós da HTA exercitados | Operadores do CTT relevantes | Storyboard | Indicadores |
| :---: | :--- | :--- | :---: | :--- |
| **T1** | A preencher (ex.: localizar e abrir a gravação da aula) | A preencher | SB-__ | I1, I2, I7 |
| **T2** | A preencher (ex.: escolher o espaço de publicação e publicar) | A preencher | SB-__ | I1, I2, I7, I8 |
| **T3** | 0 a 3 (definir conteúdo e destinatários, transmitir, obter retorno) | A preencher | SB-__ | I1, I2, I7 |
| **T4** | 0 a 4.2 (criar equipe, divulgar diretrizes, agendar e conduzir reunião, consolidar registros) | Nós 0 a 4.3 do CTT do gestor | SB-__ | I1, I2, I7, I8 |

<p><em>Fonte: João Paulo (2026).</em></p>

## 6. I — Identificar e administrar as questões práticas

### 6.1. Participantes

Os participantes devem representar o público-alvo, com características semelhantes às dos usuários típicos (BARBOSA et al., 2021, p. 258). Os perfis seguem a [seção de perfis](../analise_de_requisitos/perfil_usuarios.md) e os dados de U1 a U4 já levantados.

<p><strong>Tabela 9:</strong> Plano de recrutamento</p>

| Item | Decisão |
| :--- | :--- |
| Perfis | Estudante, Professor, Funcionário e Gestor (um por tarefa T1 a T4) |
| Meta | 2 participantes por perfil (8 no total) |
| Mínimo aceitável | 1 por perfil (4 no total); neste caso os resultados valem como indício por perfil |
| Referência de amostra | O livro cita de 5 a 12 usuários (Dumas e Redish, 1999) e 5 usuários para encontrar a maioria dos problemas (Nielsen, 2000); resultados com poucos participantes indicam tendências e servem ao reprojeto (BARBOSA et al., 2021, p. 258-259) |
| Quem evitar | Amigos, alunos, subordinados ou pessoas com relação próxima a algum avaliador, para não contaminar os dados (BARBOSA et al., 2021, p. 260) |
| Quem pode participar do teste piloto | Pessoa próxima ao grupo, que não tenha participado do planejamento; seus dados são descartados |
| Triagem | Questionário curto para conferir o perfil e a experiência com o Teams |
| Contato | Explicar objetivo, forma, local e duração; agendar data e horário; esclarecer dúvidas desde o primeiro contato |

<p><em>Fonte: João Paulo (2026), a partir de Barbosa et al. (2021, Seção 11.7.2).</em></p>

### 6.2. Papéis da equipe

A prototipação em papel exige pelo menos dois avaliadores por sessão: um que simula o comportamento do sistema e outro que observa (BARBOSA et al., 2021, p. 304-305).

<p><strong>Tabela 10:</strong> Papéis em cada sessão</p>

| Papel | Responsabilidade |
| :--- | :--- |
| **Facilitador / "computador"** | Apresenta o protótipo, entrega os cenários, troca as telas e os elementos conforme as ações do participante, sem dar explicações nem orientações. Tudo o que o participante precisar saber deve estar no storyboard |
| **Observador** | Preenche o formulário de observação (Apêndice D): sucesso, erros, ajuda, falas espontâneas, caminho percorrido |
| **Apoio / cronometrista** | Controla o tempo da sessão, a gravação autorizada e o material. Opcional se a equipe for pequena |

<p><em>Fonte: João Paulo (2026), a partir de Barbosa et al. (2021, p. 304-305).</em></p>

Os seis integrantes se revezam nos papéis. O integrante que elaborou determinado storyboard não deve ser o facilitador da sessão com esse storyboard, para reduzir a influência do autor sobre o participante.

### 6.3. Material, ambiente e equipamentos

- **Material de apoio para cada sessão** (BARBOSA et al., 2021, p. 259): TCLE em duas vias; questionário pré-teste; cenários e instruções das tarefas; formulário de observação; roteiro de entrevista pós-teste e questionário SUS. Todos os participantes recebem o mesmo material e as mesmas orientações.
- **Protótipo:** telas dos storyboards impressas ou apresentadas em sequência, com os elementos que mudam durante a interação (menus, listas, diálogos, notificações) preparados em separado. O que não for previsto é desenhado na hora.
- **Ambiente:** sala silenciosa com mesa e cadeiras, para sessão presencial. Se for remota, o facilitador compartilha as telas e o participante indica suas ações por voz e cursor; essa mudança deve ser registrada no relato, pois altera a validade ecológica (Seção 8.4).
- **Registro:** gravador de áudio, e vídeo ou captura de tela somente se houver consentimento e se forem analisados. Registrar dados desnecessários torna a sessão artificial e constrangedora (BARBOSA et al., 2021, p. 260).
- **Duração:** cada tarefa deve ter, no máximo, 20 minutos e a sessão deve durar cerca de uma hora (BARBOSA et al., 2021, p. 259).

### 6.4. Teste piloto

O teste piloto avalia o próprio planejamento: se os materiais são claros, se o tempo é adequado e se os dados coletados permitem responder às perguntas Q1 a Q15 (BARBOSA et al., 2021, p. 260). Ele está previsto na atividade 4.4 do [cronograma](cronograma/cronograma_planejado.md).

- Conduzir como uma sessão real, com roteiro, material e gravação.
- Fazer uma análise breve dos dados para conferir se respondem às perguntas.
- Corrigir o planejamento e o material; repetir o piloto se as mudanças forem grandes.
- **Descartar os dados do piloto** das análises finais.
- Aproveitar o piloto para medir a **linha de base do I6** no Teams atual, se houver participante com o perfil.

### 6.5. Cronograma proposto

As datas abaixo são uma proposta e devem ser ajustadas ao calendário da disciplina e à disponibilidade dos participantes.

<p><strong>Tabela 11:</strong> Cronograma da avaliação</p>

| Atividade | Camada | Responsáveis | Data proposta |
| :--- | :---: | :--- | :---: |
| Completar a matriz de rastreabilidade (Tabela 8) | 1 | Grupo | A definir |
| M2: percurso cognitivo dos storyboards | 1 | Grupo, em duplas | A definir |
| M1: validação da decomposição com interessados | 1 | A definir | A definir |
| Teste piloto (cronograma 4.4) | 2 | Igor, Luccas e Rayca (conforme cronograma) | 12/10/2026 |
| Revisão do planejamento e do material após o piloto | 2 | Grupo | A definir |
| Sessões de prototipação em papel (M3, M4, M5) | 2 | Grupo, em duplas | A definir |
| Interpretação, consolidação e relato | 2 | Grupo | A definir |

<p><em>Fonte: João Paulo (2026).</em></p>

## 7. D — Decidir como lidar com as questões éticas

Os participantes devem ser respeitados e não podem ser prejudicados direta ou indiretamente, nem durante a avaliação nem após a divulgação dos resultados (BARBOSA et al., 2021, p. 264). A Resolução CNS nº 466/2012 não se aplica a avaliações com objetivos técnicos, mas seus princípios (autonomia, beneficência, não maleficência, justiça e equidade) orientam o cuidado ético, e a Resolução nº 510/2016 está mais próxima do trabalho em IHC (BARBOSA et al., 2021, Seção 7.4, p. 126-127). Em coerência com a atividade 2.2 do cronograma, o grupo adota esses princípios.

<p><strong>Tabela 12:</strong> Cuidados éticos e como serão aplicados</p>

| Cuidado (BARBOSA et al., 2021, p. 127-128) | Aplicação nesta avaliação |
| :--- | :--- |
| Explicar objetivos e forma da participação | Apresentação oral no recrutamento e novamente no início da sessão: objetivo, duração, dados coletados, uso dos dados e direitos |
| Consentimento livre e esclarecido | TCLE em duas vias, assinadas também pelo responsável do grupo, uma para o participante e outra para a equipe. Adaptar o termo de entrevista já existente ([Termo de Consentimento para Entrevista](../assets/TermoDeConsentimentoEntrevista.pdf)) para esta atividade: observação de uso de protótipos, gravação de áudio e eventual captura de tela |
| Permissão para gravar voz ou imagem | Informar o tipo de gravação já no recrutamento e obter autorização expressa antes de gravar; quem não autorizar participa sem gravação, com anotações do observador |
| Confidencialidade e privacidade dos dados brutos | Dados brutos compartilhados apenas entre os membros do grupo; armazenados em pasta de acesso restrito |
| Anonimato na divulgação | Usar códigos (P01, P02, ...) e substituir nomes citados pelos participantes por "[nome]". Cuidar para que idade, profissão ou sexo não identifiquem alguém que destoe do grupo |
| Críticas sem expor o indivíduo | Relatar o problema pelo grupo de participantes e pelo motivo, e não pelo desempenho de uma pessoa |
| Conforto e respeito | Oferecer pausas e água; deixar claro que **o protótipo é avaliado, e não o participante**; evitar o termo "cobaia" |
| Direito de recusar ou desistir | O participante pode parar a qualquer momento sem penalidade; o avaliador interrompe se perceber constrangimento |
| Grupos vulneráveis | Não recrutar menores de idade; evitar alunos e subordinados de integrantes do grupo, pelo princípio da autonomia |
| Acesso aos resultados | Oferecer aos participantes o resumo dos resultados antes da publicação na wiki |

<p><em>Fonte: João Paulo (2026), a partir de Barbosa et al. (2021, Seção 7.4).</em></p>

**Cuidado específico do Teams:** os storyboards e os cenários devem usar contas, nomes, equipes e mensagens fictícias. Nenhum participante deve exibir conversas, arquivos ou dados reais da sua organização durante a sessão.

## 8. E — Avaliar, interpretar e apresentar os dados

### 8.1. Dados coletados

<p><strong>Tabela 13:</strong> Dados coletados por método</p>

| Dado | Tipo | Método | Responde |
| :--- | :--- | :---: | :---: |
| Perfil e experiência prévia do participante | Nominal / ordinal | Pré-teste | Contexto das demais perguntas |
| Concordância ou correção apontada para cada nó da HTA | Qualitativo | M1 | Q1, Q2, Q3 |
| Resposta justificada às perguntas P1 a P4, por ação | Qualitativo | M2 | Q7 |
| Sucesso na tarefa (concluiu, concluiu com ajuda, não concluiu) | Ordinal | M3 | Q5 |
| Número e tipo de erros, local no storyboard | Razão / nominal | M3 | Q6, Q9 |
| Pedidos de ajuda e dúvidas | Razão / qualitativo | M3 | Q8 |
| Caminho percorrido (sequência de telas e ações) | Nominal | M3 e M4 | Q4, Q11 |
| Falas espontâneas e comentários | Qualitativo | M3 | Q7, Q10 |
| Explicação das áreas da tela | Qualitativo, classificado em correto ou incorreto | M5 | Q10 |
| Escala SUS (0 a 100) e itens de controle de notificações (1 a 5) | Intervalo | M5 | Q13, Q14 |
| Preferência entre alternativas e justificativa | Ordinal / qualitativo | M5 | Q12 |

<p><em>Fonte: João Paulo (2026), com a classificação de dados de Barbosa et al. (2021, Seção 11.5).</em></p>

Registra-se apenas o que contribui para as perguntas da Seção 4, para não tornar a sessão artificial (BARBOSA et al., 2021, p. 260).

### 8.2. Interpretação e consolidação

1. **Análise intraparticipante:** cada sessão é interpretada individualmente, buscando respostas às perguntas Q1 a Q15 (BARBOSA et al., 2021, p. 262).
2. **Análise interparticipante:** os resultados são consolidados para encontrar recorrências, que distinguem problemas do grupo de idiossincrasias individuais (BARBOSA et al., 2021, p. 263).
3. **Comparação com o modelo (M4):** para cada tarefa, comparar o caminho observado com o da HTA e do CTT. Divergências recorrentes indicam que o **modelo está incompleto ou incorreto** (O1) ou que o **storyboard conduz o usuário por outro caminho** (O2). A equipe decide caso a caso qual dos dois corrigir.
4. **Classificação dos problemas:** cada problema é descrito com local, fator de usabilidade prejudicado, gravidade e frequência (BARBOSA et al., 2021, p. 249 e 306). A gravidade usa uma escala proposta pelo grupo:

<p><strong>Tabela 14:</strong> Escala de gravidade dos problemas (proposta do grupo)</p>

| Nível | Descrição |
| :---: | :--- |
| **1. Cosmético** | O participante nota, mas não prejudica a tarefa |
| **2. Pequeno** | Causa hesitação ou pequeno atraso; o participante segue sozinho |
| **3. Grave** | Causa erro ou exige ajuda; o participante se recupera com dificuldade |
| **4. Crítico** | Impede a conclusão da tarefa ou causa erro irrecuperável (por exemplo, publicar no lugar errado sem como desfazer) |

<p><em>Fonte: João Paulo (2026).</em></p>

5. **Prioridade de correção:** definida pela combinação de gravidade e frequência, como na prototipação em papel (BARBOSA et al., 2021, p. 305).
6. **Critério de parada da decomposição:** ao encontrar a origem de um problema, a equipe usa o critério p × c da HTA (probabilidade de falha vezes custo da falha) para decidir se detalha mais a operação (BARBOSA et al., 2021, p. 166).

### 8.3. Critérios de decisão

Os valores medidos são comparados com as faixas inaceitável, aceitável e ideal da [Tabela 4 das Metas de Usabilidade](../analise_de_requisitos/metas_usabilidade.md).

- **Indicador inaceitável ou problema de gravidade 3 ou 4:** exige correção do storyboard (ou do modelo de tarefas) e nova iteração.
- **Indicador aceitável:** pode seguir, com os problemas de gravidade 1 e 2 registrados para o guia de estilo.
- **Indicador ideal:** mantido; registrado como ponto forte do redesenho.

Como as faixas são hipóteses de trabalho do grupo e a amostra é pequena, o resultado é lido como **tendência**, e não como estatística conclusiva (ver Metas de Usabilidade, Seção 3.4). A ausência de problemas não prova alta qualidade de uso; indica apenas que este estudo, neste escopo e com este planejamento, não os encontrou (BARBOSA et al., 2021, p. 263).

### 8.4. Validade do estudo

O livro pede atenção à confiabilidade dos dados e a três tipos de validade antes de concluir e divulgar resultados (BARBOSA et al., 2021, p. 264).

<p><strong>Tabela 15:</strong> Ameaças à validade e medidas de mitigação</p>

| Aspecto | Ameaça prevista | Mitigação |
| :--- | :--- | :--- |
| **Confiabilidade** (resultados semelhantes ao repetir o método) | Facilitadores diferentes conduzindo de modo diferente | Mesmo roteiro e mesmo material em todas as sessões; piloto para uniformizar a condução |
| **Validade interna** (mede o que deveria medir, com rigor) | Facilitador que dá dicas ao simular o sistema; autor do storyboard conduzindo a sessão; tempo dependente de quem opera o papel | Facilitador não explica nem orienta; autor não conduz a própria sessão; I5 e I6 não medidos com o papel (Tabela 7) |
| **Validade externa** (generalização) | Poucos participantes por perfil | Declarar o número e o perfil no relato; tratar como tendência |
| **Validade ecológica** (semelhança com a situação real) | Esboços em papel e tarefas simuladas, fora do ambiente real de trabalho ou estudo; eventual sessão remota | Cenários baseados nas tarefas reais das entrevistas; registrar o ambiente e as limitações no relato |

<p><em>Fonte: João Paulo (2026), a partir de Barbosa et al. (2021, p. 264).</em></p>

### 8.5. Relato dos resultados

O relato dos resultados será feito no modelo definido na atividade 4.3 do cronograma (Planejamento do Relato) e deve conter, no mínimo (BARBOSA et al., 2021, p. 263 e 305-306):

- objetivos e escopo da avaliação;
- método empregado e descrição resumida de cada um;
- número e perfil dos participantes e dos avaliadores (anonimizados);
- tarefas executadas;
- sumário dos dados, com tabelas e gráficos, e comparação com as faixas dos indicadores;
- interpretação dos dados e resposta a cada pergunta Q1 a Q15, ou justificativa de por que alguma não foi respondida;
- lista de problemas corrigidos durante os ciclos (local, fator prejudicado, descrição, correção, se voltou a ocorrer);
- lista de problemas não corrigidos (local, fator prejudicado, descrição, prioridade, sugestão de correção);
- alterações propostas nos modelos de tarefa (HTA/CTT), quando houver;
- plano de reprojeto.

## 9. Riscos e decisões de contingência

<p><strong>Tabela 16:</strong> Riscos e contingências</p>

| Risco | Efeito | Contingência |
| :--- | :--- | :--- |
| Falta de participante de algum perfil | Perfil sem evidência empírica | Manter apenas M1 e M2 para o perfil, registrar a lacuna e adiar o M3 daquela tarefa |
| Modelos de tarefa (HTA/CTT) incompletos para algum perfil | Matriz de rastreabilidade e M4 inviáveis | Concluir o modelo antes das sessões; a tarefa não entra na rodada sem ele |
| Participante sem autorização para gravar | Perda de dados | Anotações detalhadas do observador; sem pressão sobre o participante |
| Sessão ultrapassa 1 hora | Fadiga e dados distorcidos | Pausa rápida; reduzir a tarefa extra ou o questionário opcional |
| Piloto revela material confuso | Dados não confiáveis | Corrigir e repetir o piloto; descartar os dados |
| Sessão remota por falta de local | Menor validade ecológica | Registrar a mudança e a limitação no relato |

<p><em>Fonte: João Paulo (2026).</em></p>

## Apêndice A. Roteiro da sessão (cerca de 60 minutos)

<p><strong>Tabela 17:</strong> Roteiro da sessão de prototipação em papel</p>

| Min. | Etapa | Conteúdo |
| :---: | :--- | :--- |
| 0 a 5 | Acolhimento | Conversa de aquecimento; apresentar a sala e os papéis; oferecer água e pausa |
| 5 a 10 | Esclarecimento e TCLE | Explicar objetivo, procedimento, gravação e direitos; destacar que o protótipo é avaliado, e não a pessoa; entregar o TCLE em duas vias |
| 10 a 15 | Questionário pré-teste | Ler as perguntas e registrar as respostas (Apêndice B) |
| 15 a 20 | Apresentação do protótipo | Mostrar como os elementos estão representados no papel e como "clicar" neles |
| 20 a 40 | Tarefa(s) | Entregar o cenário (Apêndice C); o participante interage com o storyboard (até 20 min por tarefa); o facilitador não orienta; o observador preenche o formulário (Apêndice D) |
| 40 a 55 | Pós-teste | Entrevista e questionário SUS (Apêndice E); perguntar sobre a decomposição da tarefa (M1 complementar) |
| 55 a 60 | Encerramento | Agradecer; reiterar o anonimato; oferecer o resumo dos resultados |
| Opcional | Segunda execução | Repetir a tarefa após o intervalo ou outra tarefa, para medir I4, se o tempo permitir |

<p><em>Fonte: João Paulo (2026), a partir de Barbosa et al. (2021, Seções 11.7.2 e 11.7.3).</em></p>

## Apêndice B. Questionário pré-teste

Perguntas lidas ao participante, na forma de entrevista estruturada, com campos equivalentes aos usados na tabela de perfis do projeto:

1. Faixa de idade e formação.
2. Cargo ou ocupação; tempo na função.
3. Com que frequência usa o Microsoft Teams e há quanto tempo? Para qual finalidade?
4. Que outras ferramentas de comunicação ou colaboração costuma usar (por exemplo, Meet, Zoom, WhatsApp, e-mail)?
5. Como avalia a sua habilidade com computadores (básica, intermediária ou avançada)?
6. Costuma ler manual ou ajuda quando tem dificuldade?
7. Já realizou esta tarefa (T1 a T4) no Teams? Como costuma fazê-la?
8. Há alguma dificuldade que gostaria de relatar (visão, audição, motricidade) que influencie o uso de tela?

## Apêndice C. Cenários das tarefas

Os textos abaixo são modelos para a equipe ajustar, usando sempre nomes e dados fictícios.

- **T1 (Estudante):** "Você perdeu a aula de ontem da disciplina de Biologia Celular. O professor disse que a gravação ficaria disponível no Teams. Encontre a gravação e comece a assistir."
- **T2 (Professor):** "Você quer que sua turma de Química entregue um relatório até sexta-feira. Publique a atividade para a turma, no local que considerar adequado."
- **T3 (Funcionário):** "Você precisa saber com o setor de Compras se um pedido já foi aprovado. Envie a pergunta para o colega responsável e confirme que recebeu a resposta."
- **T4 (Gestor):** "Você vai iniciar um novo projeto com cinco pessoas. Crie o espaço da equipe, avise sobre a primeira reunião e deixe a gravação e a ata disponíveis para quem faltar."

## Apêndice D. Formulário de observação (por participante e tarefa)

| Campo | Registro |
| :--- | :--- |
| Participante / perfil / tarefa / alternativa de storyboard | P__ / __ / T__ / __ |
| Resultado | ( ) concluiu sem ajuda  ( ) concluiu com ajuda  ( ) não concluiu |
| Caminho percorrido (telas e ações em ordem) | |
| Nós da HTA seguidos / ignorados / acrescentados | |
| Erros (descrição, tela, recuperou sozinho? sim ou não) | |
| Erro de destino (publicou ou enviou no lugar errado)? | |
| Pedidos de ajuda e dúvidas | |
| Falas espontâneas relevantes | |
| Observações do avaliador | |

## Apêndice E. Pós-teste

**Entrevista (roteiro):**

1. Como foi realizar essa tarefa? O que foi mais fácil e o que foi mais difícil?
2. Em algum momento você não soube o que fazer em seguida? Em qual?
3. Vou apontar algumas áreas da tela. Para que serve cada uma? (I10)
4. O que você esperava encontrar e não encontrou?
5. Essa sequência de passos se parece com o que você faz no dia a dia? O que mudaria? (M1 complementar)
6. Se houver duas alternativas: qual preferiu e por quê? (Q12)

**Itens de controle de notificações (escala de 1 a 5, de "discordo totalmente" a "concordo totalmente") (I12):**

1. Senti que eu controlaria quais avisos receberia.
2. A tela me pareceu organizada e sem excesso de informação.

**Escala SUS:** aplicar as 10 afirmações da *System Usability Scale* (BROOKE, 1996), em português, com respostas de 1 a 5, e calcular a pontuação de 0 a 100 pelo método padrão da escala.

## 10. Referências Bibliográficas

1. BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. **Interação Humano-Computador e Experiência do Usuário**. 1. ed. Autopublicação, 2021. Seções 7.4, 8.4, 11.2, 11.3, 11.5, 11.7, 11.8, 12.1.2, 12.2.1, 12.2.3 e 12.2.4.
2. PREECE, J.; ROGERS, Y.; SHARP, H. **Interaction Design: Beyond Human-Computer Interaction**. New York: John Wiley & Sons, 2002. (framework DECIDE, citado por Barbosa et al., 2021, Seção 11.8).
3. DIAPER, D. Task analysis for human-computer interaction. *In*: DIAPER, D.; STANTON, N. (ed.). **The Handbook of Task Analysis for Human-Computer Interaction**. Mahwah: Lawrence Erlbaum, 2003. (citado por Barbosa et al., 2021, Seção 8.4).
4. BROOKE, J. SUS: a "quick and dirty" usability scale. *In*: JORDAN, P. W. et al. (ed.). **Usability Evaluation in Industry**. London: Taylor & Francis, 1996. p. 189-194.
5. BRASIL. Conselho Nacional de Saúde. **Resolução nº 466, de 12 de dezembro de 2012**; **Resolução nº 510, de 7 de abril de 2016**.

## 11. Histórico de versão

| Versão | Data       | Descrição                                           | Autor(es) | Revisor(es) |
| ------ | ---------- | --------------------------------------------------- | --------- | ----------- |
| `1.0`  | 13/10/2026 | Criação da página: planejamento DECIDE completo.    | João Paulo | A definir   |
