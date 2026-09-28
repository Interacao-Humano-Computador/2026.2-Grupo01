# Cenários de Uso — Microsoft Teams

## 1. Introdução e Fundamentação Teórica

Ao focar nos objetivos dos atores, nas suas reflexões e na sequência de eventos (incluindo falhas e exceções do ambiente real), um **Cenário** é capaz de ajudar a identificar requisitos não funcionais, problemas de usabilidade, ruídos comunicativos e oportunidades de melhoria na plataforma **Teams**. Este documento traz os Cenários elaborados para este projeto.

---

## 2. Estrutura Padrão de um Cenário de Uso

Segundo a literatura-texto de IHC (Barbosa e Silva, 2010, p. 185), cada cenário construído no projeto deve mapear os seguintes elementos essenciais:

* **Identificador e Título:** Rótulo único e nome descritivo que resume a atividade retratada.
* **Ator / Persona Protagonista:** Persona principal e atores secundários envolvidos.
* **Objetivo do Ator:** A meta pessoal e prática que motiva a realização da atividade.
* **Contexto de Uso:** Descrição da situação física, social, organizacional e dos recursos tecnológicos disponíveis.
* **Precondições:** Estados iniciais necessários para que o cenário possa ocorrer no sistema.
* **Fluxo Principal (Passo a Passo):** A sequência cronológica de ações observáveis executadas pelo ator e as respectivas reações da interface do sistema.
* **Fluxos Alternativos / Exceções:** Os imprevistos, erros de interface, problemas de permissão ou falhas comunicativas que surgem no decorrer da tarefa e como são contornados.
* **Pós-condições (Resultado Final):** O estado final do ambiente e a interpretação do ator sobre o sucesso da atividade.
* **Perguntas / Avaliação de IHC Associada:** Questões analíticas sobre a qualidade de uso, acessibilidade e comunicabilidade reveladas pelo cenário.

---

## 3. Cenários de Uso por Perfil de Usuário

---

### 3.1. Perfil 1: Estudante

> **Responsável pelo Perfil:** *[Nome do Integrante do Grupo]*  
> **Título do Cenário:** Acceso ao Material de Aula e Submissão de Atividade Avaliativa com Prazo Estipulado

#### 1. Narrativa do Cenário

*[Espaço reservado para o integr
ante inserir o texto narrativo em formato de história da persona Estudante]*

#### 2. Mapeamento Estruturado

| Campo                               | Detalhes do Cenário de Uso                                                                                                                            |
| :---------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificador e Título:**         | **Cenário 01:** Submissão de Atividade Avaliativa pelo Estudante.                                                                                     |
| **Ator Protagonista:**              | *[Nome da Persona Estudante]* (Perfil 1: Estudante).                                                                                                  |
| **Objetivo do Ator:**               | Enviar o trabalho da disciplina dentro do prazo estipulado no Teams.                                                                                  |
| **Contexto de Uso:**                | *[Inserir ambiente, horário e dispositivos do estudante]*                                                                                             |
| **Precondições:**                   | *[Condições necessárias antes do início da tarefa]*                                                                                                   |
| **Fluxo Principal:**                | **1.** Acessar a equipe da disciplina.<br>**2.** Navegar até a aba *Tarefas (Assignments)*.<br>**3.** Anexar o arquivo PDF e clicar em *Entregar*.    |
| **Fluxos Alternativos / Exceções:** | **Exceção:** Falha no carregamento do anexo por instabilidade de rede.<br>**Solução:** Tentar novamente e confirmar o recebimento do feedback visual. |
| **Pós-condições:**                  | Atividade entregue com comprovante visual de submissão na tela.                                                                                       |
| **Avaliação de IHC:**               | Como a interface confirma ao estudante que a entrega foi concluída com sucesso?                                                                       |

---

### 3.2. Perfil 2: Professor

> **Responsável pela Persona:** João Paulo  
> **Status:** Persona Primária (Perfil 2: Professor)

#### 👤 Ficha da Persona: Helena Ribeiro
| Campo                               | Detalhes da Persona |
| :---------------------------------- | :------------------ |
| **Nome e Sobrenome:**               | Helena Ribeiro (nome fictício; a participante da entrevista é mantida em anonimato) |
| **Foto / Representação:**           | Mulher de 47 anos, expressão atenta e acolhedora, em ambiente de trabalho com computador e tablet (imagem ilustrativa a definir). |
| **Idade e Demografia:**             | **Idade:** 47 anos.<br>**Formação:** Pedagoga (professora de formação).<br>**Departamento:** Área de capacitação de servidores públicos.<br>**Tempo no cargo:** 16 anos como Gestora em Políticas Públicas.<br>**Dispositivos:** Computador e tablet. |
| **Status da Persona:**              | **Persona Primária** (foco do design e da avaliação para funcionalidades de ensino e de organização de turmas). |
| **Frase de Efeito (Motto):**        | *"Eu teria um ambiente limpo, primeiro, sem muitas ferramentas."* |
| **Perfil Profissional / Ocupação:** | Professora e capacitadora de servidores públicos, com turmas organizadas por setores de trabalho. Atua no serviço público como Gestora em Políticas Públicas. |
| **Objetivos do Usuário:**           | **Objetivos Pessoais:**<br>• Ajudar os alunos, inclusive os mais velhos, a usar a plataforma sem dificuldade.<br>• Manter uma rotina de trabalho sem ansiedade, consultando a plataforma em horários próprios.<br><br>**Objetivos no Teams:**<br>• Criar turmas de capacitação (muitas) e organizá-las por setor.<br>• Marcar reuniões e postar arquivos e atividades no lugar certo.<br>• Corrigir trabalhos e interagir com a turma no chat. |
| **Habilidades e Competências:**     | **Alfabetismo Computacional:** Intermediário.<br>**Atitude:** Aprende as ferramentas mexendo e, atualmente, com ajuda de IA. Vê o Teams como importante desde a pandemia, mas acha que hoje existem ferramentas mais modernas. |
| **Tarefas Principais e Rotina:**    | **Mais demoradas:** Corrigir trabalhos e interagir com a turma.<br>**Recorrentes:** Postar arquivos e atividades; consultar a plataforma em horários que ela reserva, com as notificações desativadas.<br>**Por turma / eventuais:** Criar turmas (recebendo-as prontas ou criando do zero) e marcar reuniões.<br>*(A entrevista não detalhou a frequência exata.)* |
| **Relacionamentos:**                | **Com Alunos (servidores):** Muitos preferem WhatsApp e e-mail por acharem mais fácil; entre eles há alunos mais velhos, com mais dificuldade com tecnologia.<br>**Com quem organiza o curso:** Recorre a essa equipe como suporte quando tem dúvida sobre a plataforma. |
| **Requisitos e Necessidades:**      | **Ambiente limpo:** Menos ferramentas e espaços na tela.<br>**Clareza de postagem:** Deixar evidente onde e como postar atividades.<br>**Explicações embutidas:** Indicar para que serve cada espaço, com interações mais dinâmicas.<br>**Envio ágil:** Subida de arquivos mais rápida.<br>**Notificações:** Poder reduzi-las ou desativá-las. |
| **Frustrações e Gambiarras:**       | **Frustrações:** Não saber em qual espaço colocar cada coisa (tarefa, conversa com o aluno) por causa da quantidade de opções; demora no envio de arquivos; excesso de ferramentas que dificulta o uso pelos alunos; notificações que a deixam ansiosa; dificuldade inicial na pandemia para gravar aulas e colocar material na plataforma.<br>**Soluções de Contorno:** Alunos recorrem ao WhatsApp e ao e-mail porque não encontram as coisas na plataforma; ela conta com o suporte de quem organiza o curso. |

### 3.3. Perfil 3: Funcionário

## Esclarecimento de uma dúvida com colegas de trabalho

Ator: Marina Alves, profissional da área de comunicação, com experiência no uso de computadores e de ferramentas de comunicação e colaboração.

Marina está realizando uma atividade de trabalho quando encontra uma dúvida que não consegue solucionar sozinha. Como precisa esclarecer a questão para dar continuidade à sua atividade, seu objetivo é encontrar um colega que possa fornecer a informação necessária.

Inicialmente, Marina conversa presencialmente com alguns colegas para identificar quem possui conhecimento sobre o assunto. Ao descobrir quem pode ajudá-la, ela procura essa pessoa no Microsoft Teams e inicia o contato. Marina apresenta sua dúvida e aguarda as informações necessárias para decidir como prosseguir com a atividade.

Caso o colega consiga esclarecer a questão, Marina encerra o contato e retorna à atividade que estava realizando, considerando que seu objetivo foi alcançado. Caso o colega não saiba responder à dúvida, ele indica outra pessoa que possivelmente possui o conhecimento necessário. Marina então procura essa nova pessoa no Teams e repete o processo de contato e esclarecimento.

Esse processo pode se repetir até que Marina encontre alguém capaz de esclarecer a dúvida. Ao obter a informação necessária, ela avalia que a dúvida foi resolvida e pode continuar sua atividade de trabalho.

---

### 3.4. Perfil 4: Chefe/Gestor

> **Responsável pelo Perfil:** Luccas Rodrigues  
> **Título do Cenário:** Estruturação de Nova Equipe de Projeto e Condução de Reunião Síncrona de Alinhamento pelo Gestor

#### 1. Narrativa do Cenário

Em uma manhã de segunda-feira, Roberto encontra-se em seu escritório em modo *home office* (jornada híbrida). Ele utiliza seu notebook corporativo com monitor secundário conectado e headset. O setor administrativo precisa iniciar um novo projeto estratégico de reestruturação de processos com prazo apertado imposto pela diretoria. Roberto precisa mobilizar sua equipe rapidamente, definir permissões de governança, publicar comunicados formais sem ruídos e conduzir uma reunião síncrona objetiva, garantindo que o registro dos encaminhamentos fique acessível a todos.

#### 2. Mapeamento Estruturado

| Campo                                       | Detalhes do Cenário de Uso                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| :------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificador e Título:**                 | **Cenário 05:** Estruturação de Nova Equipe de Projeto e Condução de Reunião Síncrona de Alinhamento pelo Gestor no Microsoft Teams.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Ator / Persona Protagonista:**            | **Roberto Mendes** (Persona Primária: 44 anos, Coordenador de Projetos e Gestor de Setor Administrativo — Perfil 4: Chefe / Gestor).<br>*Atores secundários:* Camila (Analista Técnica e Colaboradora) e demais membros do setor administrativo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Objetivo do Ator:**                       | **Objetivo Pessoal:** Manter a equipe alinhada e produtiva sem sobrecarregá-la com reuniões extensas ou mensagens dispersas fora do expediente.<br>**Objetivos Práticos no Teams:**<br>1. Criar uma equipe e canal estruturados para o novo projeto.<br>2. Configurar permissões de governança e proteção de arquivos.<br>3. Publicar comunicado formal em destaque no *Canal Geral*.<br>4. Agendar e conduzir reunião síncrona com gravação e pauta centralizada.                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Contexto de Uso:**                        | Manhã de segunda-feira, escritório em *home office* (jornada híbrida), utilizando notebook corporativo com monitor secundário e headset. O setor precisa iniciar um projeto estratégico de reestruturação com prazo apertado imposto pela diretoria.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Precondições:**                           | • Roberto possui conta com privilégios de gestor/criador no Microsoft Teams.<br>• Os 8 colaboradores do setor estão previamente cadastrados na plataforma.<br>• Aplicação do Teams ativa e conectada à internet.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Fluxo Principal (Passo a Passo):**        | **1. Criação do Espaço de Trabalho:** Roberto abre o Teams, navega até *Equipes*, cria a equipe *"Projeto Reestruturação 2026"* e adiciona os 8 colaboradores.<br>**2. Configuração de Governança:** Acessa as *Configurações da Equipe* e desmarca a permissão para que membros excluam arquivos compartilhados ou criem canais privados.<br>**3. Publicação do Anúncio:** No *Canal Geral*, cria uma postagem do tipo *Anúncio (Announcement)* em destaque vermelho (*"Atenção: Início do Projeto Reestruturação 2026"*), insere as metas da semana e marca como *"Importante"*.<br>**4. Agendamento:** Acessa o *Calendário*, agenda a reunião de alinhamento para às 14h00 e vincula o convite ao canal da equipe.<br>**5. Condução da Reunião:** Às 14h00, inicia a videoconferência, ativa *Gravação e Transcrição*, compartilha a tela com a pauta e define responsabilidades em 45 minutos. |
| **Fluxos Alternativos / Exceções:**         | **Ruptura de Permissão (Falha de Acesso):** Durante a chamada, a colaboradora Camila tenta anexar um relatório no canal e relata no chat que não possui permissão de escrita na pasta do SharePoint vinculado.<br>**Tratamento / Resolução:** Roberto acessa o *Gerenciamento do Canal*, altera a permissão da pasta de *"Apenas Leitura"* para *"Membro / Edição"*. Camila tenta novamente e consegue anexar o arquivo com sucesso.                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Pós-condições (Resultado Final):**        | • A gravação da reunião fica disponível automaticamente no chat do canal.<br>• Todos os membros reagem com *"OK"* ao anúncio fixado.<br>• Os arquivos da equipe ficam organizados e protegidos na pasta correta.<br>• O alinhamento é concluído sem atrasos, retrabalho ou envio de e-mails/mensagens fora do horário comercial.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Perguntas / Avaliação de IHC Associada:** | • *Como o sistema apoia a visibilidade e priorização de avisos críticos?* (Através do recurso de Anúncio e etiqueta de Importante).<br>• *Qual foi a barreira de usabilidade/governança identificada?* (Configuração padrão de permissão de pastas herdada do SharePoint que bloqueou a edição de membros até a intervenção manual do gestor).<br>• *Como a plataforma apoia o trabalho assíncrono?* (Disponibilização automática da gravação e transcrição no canal para membros ausentes).                                                                                                                                                                                                                                                                                                                                                                                                        |

---

## 4. Referências Bibliográficas

* BARBOSA, Simone Diniz Junqueiro; SILVA, Bruno Santana da. **Interação Humano-Computador**. Rio de Janeiro: Elsevier / Campus, 2010.
* CARROLL, John M. **Making Use: Scenario-Based Design of Human-Computer Interactions**. Cambridge, MA: MIT Press, 2000.
* ROSSON, Mary Beth; CARROLL, John M. **Usability Engineering: Scenario-Based Development of Human-Computer Interactions**. San Francisco, CA: Morgan Kaufmann, 2002.

## 5. Histórico de Versão

| Versão | Data       | Descrição                                                               | Autor(es)        | Revisor(es)      |
| ------ | ---------- | ----------------------------------------------------------------------- | ---------------- | ---------------- |
| `1.0`  | 27/09/2026 | Criação da página.                                                      | Lucas Sales      | Luccas Rodrigues |
| `1.1`  | 27/09/2026 | Adição do cenário Esclarecimento de uma dúvida com colegas de trabalho. | Lucas Sales      | Luccas Rodrigues |
| `1.2`  | 27/09/2026 | Atualização de estrutura da página                                      | Luccas Rodrigues | Lucas Sales      |

