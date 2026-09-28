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

| Campo | Detalhes do Cenário de Uso |
| :--- | :--- |
| **Identificador e Título:** | **Cenário 01:** Submissão de Atividade Avaliativa pelo Estudante. |
| **Ator Protagonista:** | *[Nome da Persona Estudante]* (Perfil 1: Estudante). |
| **Objetivo do Ator:** | Enviar o trabalho da disciplina dentro do prazo estipulado no Teams. |
| **Contexto de Uso:** | *[Inserir ambiente, horário e dispositivos do estudante]* |
| **Precondições:** | *[Condições necessárias antes do início da tarefa]* |
| **Fluxo Principal:** | **1.** Acessar a equipe da disciplina.<br>**2.** Navegar até a aba *Tarefas (Assignments)*.<br>**3.** Anexar o arquivo PDF e clicar em *Entregar*. |
| **Fluxos Alternativos / Exceções:** | **Exceção:** Falha no carregamento do anexo por instabilidade de rede.<br>**Solução:** Tentar novamente e confirmar o recebimento do feedback visual. |
| **Pós-condições:** | Atividade entregue com comprovante visual de submissão na tela. |
| **Avaliação de IHC:** | Como a interface confirma ao estudante que a entrega foi concluída com sucesso? |

---

### 3.2. Perfil 2: Professor

> **Responsável pelo Perfil:** *[Nome do Integrante do Grupo]*  
> **Título do Cenário:** Organização do Canal de Disciplina e Condução de Reunião Síncrona de Aula

#### 1. Narrativa do Cenário

*[Espaço reservado para o integrante inserir o texto narrativo em formato de história da persona Professor]*

#### 2. Mapeamento Estruturado

| Campo | Detalhes do Cenário de Uso |
| :--- | :--- |
| **Identificador e Título:** | **Cenário 01:** Condução de Aula Síncrona e Publicação de Materiais pelo Docente. |
| **Ator Protagonista:** | *[Nome da Persona Professor]* (Perfil 2: Professor). |
| **Objetivo do Ator:** | Ministrar aula online gravada e disponibilizar os slides para os alunos. |
| **Contexto de Uso:** | *[Inserir ambiente, horário e dispositivos do professor]* |
| **Precondições:** | *[Condições necessárias antes do início da aula]* |
| **Fluxo Principal:** | **1.** Iniciar reunião no canal da turma.<br>**2.** Ativar gravação e compartilhar apresentação de slides.<br>**3.** Encerrar a chamada e anexar o material na aba *Arquivos*. |
| **Fluxos Alternativos / Exceções:** | **Exceção:** Alunos relatam não visualizar o compartilhamento de tela.<br>**Solução:** Alternar o modo de apresentação no Teams para o modo Janela. |
| **Pós-condições:** | Aula ministrada, gravação disponível no chat e slides publicados. |
| **Avaliação de IHC:** | O sistema facilita o controle da sala e a gravação sem poluir a visão da apresentação? |

---

### 3.3. Perfil 3: Funcionário

> **Responsável pelo Perfil:** *[Nome do Integrante do Grupo]*  
> **Título do Cenário:** Atendimento de Solicitação Interna de Setor e Tramitação de Documentos

#### 1. Narrativa do Cenário

*[Espaço reservado para o integrante inserir o texto narrativo em formato de história da persona Funcionário]*

#### 2. Mapeamento Estruturado

| Campo | Detalhes do Cenário de Uso |
| :--- | :--- |
| **Identificador e Título:** | **Cenário 01:** Processamento de Solicitação e Envio de Documento Institucional. |
| **Ator Protagonista:** | *[Nome da Persona Funcionário]* (Perfil 3: Funcionário). |
| **Objetivo do Ator:** | Responder a demandas administrativas e compartilhar relatórios com outros setores. |
| **Contexto de Uso:** | *[Inserir ambiente, horário e dispositivos do funcionário]* |
| **Precondições:** | *[Condições necessárias antes do atendimento]* |
| **Fluxo Principal:** | **1.** Receber mensagem de solicitação no chat do setor.<br>**2.** Localizar o arquivo solicitado no repositório.<br>**3.** Compartilhar o link de acesso direto com o solicitante. |
| **Fluxos Alternativos / Exceções:** | **Exceção:** O solicitante não possui permissão de leitura no link enviado.<br>**Solução:** Ajustar as permissões de compartilhamento direto no Teams. |
| **Pós-condições:** | Documento entregue ao solicitante e registro de atendimento arquivado. |
| **Avaliação de IHC:** | Quão transparente é a gestão de permissões ao enviar links de arquivos pelo chat? |

---

### 3.4. Perfil 4: Chefe/Gestor
> **Responsável pelo Perfil:** Luccas Rodrigues  
> **Título do Cenário:** Estruturação de Nova Equipe de Projeto e Condução de Reunião Síncrona de Alinhamento pelo Gestor

#### 1. Narrativa do Cenário

Em uma manhã de segunda-feira, Roberto encontra-se em seu escritório em modo *home office* (jornada híbrida). Ele utiliza seu notebook corporativo com monitor secundário conectado e headset. O setor administrativo precisa iniciar um novo projeto estratégico de reestruturação de processos com prazo apertado imposto pela diretoria. Roberto precisa mobilizar sua equipe rapidamente, definir permissões de governança, publicar comunicados formais sem ruídos e conduzir uma reunião síncrona objetiva, garantindo que o registro dos encaminhamentos fique acessível a todos.

#### 2. Mapeamento Estruturado

| Campo | Detalhes do Cenário de Uso |
| :--- | :--- |
| **Identificador e Título:** | **Cenário 05:** Estruturação de Nova Equipe de Projeto e Condução de Reunião Síncrona de Alinhamento pelo Gestor no Microsoft Teams. |
| **Ator / Persona Protagonista:** | **Roberto Mendes** (Persona Primária: 44 anos, Coordenador de Projetos e Gestor de Setor Administrativo — Perfil 4: Chefe / Gestor).<br>*Atores secundários:* Camila (Analista Técnica e Colaboradora) e demais membros do setor administrativo. |
| **Objetivo do Ator:** | **Objetivo Pessoal:** Manter a equipe alinhada e produtiva sem sobrecarregá-la com reuniões extensas ou mensagens dispersas fora do expediente.<br>**Objetivos Práticos no Teams:**<br>1. Criar uma equipe e canal estruturados para o novo projeto.<br>2. Configurar permissões de governança e proteção de arquivos.<br>3. Publicar comunicado formal em destaque no *Canal Geral*.<br>4. Agendar e conduzir reunião síncrona com gravação e pauta centralizada. |
| **Contexto de Uso:** | Manhã de segunda-feira, escritório em *home office* (jornada híbrida), utilizando notebook corporativo com monitor secundário e headset. O setor precisa iniciar um projeto estratégico de reestruturação com prazo apertado imposto pela diretoria. |
| **Precondições:** | • Roberto possui conta com privilégios de gestor/criador no Microsoft Teams.<br>• Os 8 colaboradores do setor estão previamente cadastrados na plataforma.<br>• Aplicação do Teams ativa e conectada à internet. |
| **Fluxo Principal (Passo a Passo):** | **1. Criação do Espaço de Trabalho:** Roberto abre o Teams, navega até *Equipes*, cria a equipe *"Projeto Reestruturação 2026"* e adiciona os 8 colaboradores.<br>**2. Configuração de Governança:** Acessa as *Configurações da Equipe* e desmarca a permissão para que membros excluam arquivos compartilhados ou criem canais privados.<br>**3. Publicação do Anúncio:** No *Canal Geral*, cria uma postagem do tipo *Anúncio (Announcement)* em destaque vermelho (*"Atenção: Início do Projeto Reestruturação 2026"*), insere as metas da semana e marca como *"Importante"*.<br>**4. Agendamento:** Acessa o *Calendário*, agenda a reunião de alinhamento para às 14h00 e vincula o convite ao canal da equipe.<br>**5. Condução da Reunião:** Às 14h00, inicia a videoconferência, ativa *Gravação e Transcrição*, compartilha a tela com a pauta e define responsabilidades em 45 minutos. |
| **Fluxos Alternativos / Exceções:** | **Ruptura de Permissão (Falha de Acesso):** Durante a chamada, a colaboradora Camila tenta anexar um relatório no canal e relata no chat que não possui permissão de escrita na pasta do SharePoint vinculado.<br>**Tratamento / Resolução:** Roberto acessa o *Gerenciamento do Canal*, altera a permissão da pasta de *"Apenas Leitura"* para *"Membro / Edição"*. Camila tenta novamente e consegue anexar o arquivo com sucesso. |
| **Pós-condições (Resultado Final):** | • A gravação da reunião fica disponível automaticamente no chat do canal.<br>• Todos os membros reagem com *"OK"* ao anúncio fixado.<br>• Os arquivos da equipe ficam organizados e protegidos na pasta correta.<br>• O alinhamento é concluído sem atrasos, retrabalho ou envio de e-mails/mensagens fora do horário comercial. |
| **Perguntas / Avaliação de IHC Associada:** | • *Como o sistema apoia a visibilidade e priorização de avisos críticos?* (Através do recurso de Anúncio e etiqueta de Importante).<br>• *Qual foi a barreira de usabilidade/governança identificada?* (Configuração padrão de permissão de pastas herdada do SharePoint que bloqueou a edição de membros até a intervenção manual do gestor).<br>• *Como a plataforma apoia o trabalho assíncrono?* (Disponibilização automática da gravação e transcrição no canal para membros ausentes). |

---

## 4. Referências Bibliográficas

* BARBOSA, Simone Diniz Junqueiro; SILVA, Bruno Santana da. **Interação Humano-Computador**. Rio de Janeiro: Elsevier / Campus, 2010.
* CARROLL, John M. **Making Use: Scenario-Based Design of Human-Computer Interactions**. Cambridge, MA: MIT Press, 2000.
* ROSSON, Mary Beth; CARROLL, John M. **Usability Engineering: Scenario-Based Development of Human-Computer Interactions**. San Francisco, CA: Morgan Kaufmann, 2002.

## 5. Histórico de Versão

| Versão | Data       | Descrição          | Autor(es)        | Revisor(es)      |
| ------ | ---------- | ------------------ | ---------------- | ---------------- |
| `2.0`  | 27/09/2026 | Criação da página. | Luccas Rodrigues |                  |