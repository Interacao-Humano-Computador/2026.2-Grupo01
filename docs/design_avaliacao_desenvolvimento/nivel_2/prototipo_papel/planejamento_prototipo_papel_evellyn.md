| Data       | Contribuição                                                                                                                        | Autor(es)                   | Revisor(es) |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------- | --------------------------- | ----------- |
| 20/10/2026 | Criação da página                                                                                                                   | evellyn rocha                  | A definir   |



# Planejamento da Avaliação do Protótipo de Papel

**Módulo de Aproveitamento de Estudos e Dispensa de Disciplinas no Microsoft Teams**



## 1. Introdução e Objetivos Gerais

Na área de Interação Humano-Computador (IHC), a prototipação de baixa e média fidelidade desempenha um papel fundamental na exploração de soluções de design e na avaliação formativa da experiência do usuário antes da escrita de código final (Barbosa e Silva, 2010, Cap. 4 e 10; Rogers et al., 2013, Cap. 8).

O método de prototipação em papel (Snyder, 2003) permite simular fluxos interativos de forma ágil, econômica e altamente participativa, revelando falhas no modelo mental, dificuldades na arquitetura de informação e ruídos na comunicabilidade da interface.

Este documento apresenta o planejamento rigoroso da avaliação de usabilidade do protótipo de papel criado para o módulo de Aproveitamento de Estudos e Dispensa de Componentes Curriculares integrado ao Microsoft Teams da UnB.

O planejamento está estruturado segundo o Framework DECIDE (Sharp, Rogers e Preece, 2007; Barbosa e Silva, 2010, Seção 9.8, p. 312-316).

**Rastreabilidade Metodológica:** O planejamento conecta as diretrizes teóricas de Simone Barbosa e Bruno Silva (2010) ao Manual de Peticionamento Eletrônico da SAA/UnB (v4.0), aos diagramas da Análise Hierárquica de Tarefas (HTA) e ao Storyboard versão 1.1 validados no projeto.

---

## 2. Contexto do Protótipo de Papel e Especificação da Tarefa

Atualmente, os discentes regulares da Universidade de Brasília realizam solicitações de aproveitamento e dispensa através do peticionamento eletrônico no SEI/UnB (Manual SAA v4.0).

A solução proposta integra este serviço diretamente ao ambiente do Microsoft Teams (Web e Desktop), reduzindo a burocracia e aproximando o serviço da rotina dos alunos.

### 2.1. Passo a Passo Esperado da Tarefa (Fluxo do Usuário)

- **Acesso à Guia:** Navegar no canal geral da turma no Teams e selecionar a guia superior "Serviços Acadêmicos".
- **Seleção do Serviço:** Clicar no card "Aproveitamento de Estudos e Dispensa" no painel principal.
- **Verificação Cadastral:** Conferir os dados cadastrais (Nome, Matrícula, Curso UnB) autopreenchidos via login autenticado.
- **Mapeamento de Equivalências:** Informar a instituição de origem e selecionar as disciplinas cursadas e equivalentes na UnB, identificando o tipo de crédito (Obrigatória, Optativa ou Módulo Livre).
- **Anexo de Documentos PDF:** Realizar o upload do Histórico Escolar Oficial e Ementas em PDF, respeitando o limite de até 10 MB e observando a confirmação visual verde [✓].
- **Revisão dos Dados:** Conferir a lista de matérias e arquivos anexados na tela de síntese antes da submissão final.
- **Submissão e Protocolo SEI:** Confirmar o envio, visualizar o número de protocolo oficial e receber o comprovante no e-mail institucional e no chat do Teams.
- **Acompanhamento do Status:** Consultar o painel de notificações estruturado em 3 fases (Solicitação Recebida, Em Análise pela Coordenação, Parecer Concluído).

### 2.2. Mapeamento das Telas e Peças Móveis do Protótipo em Papel

| Nº | Elemento no Protótipo | Tipo de Peça | Função Interativa na Simulação |
|---|---|---|---|
| 1 | Tela Inicial Canal Teams | Base A4 Estática | Exibe a aba 'Serviços Acadêmicos' na barra superior. |
| 2 | Menu de Serviços | Base A4 Estática | Apresenta o card 'Aproveitamento de Estudos e Dispensa'. |
| 3 | Formulário de Solicitação | Base A4 Estática | Campos cadastrais autopreenchidos e seleção de IES de origem. |
| 4 | Busca de Equivalências | Recorte Móvel Overlap | Drop-down de disciplinas com indicação de crédito (Obrigatória/Optativa/Livre). |
| 5 | Componente Upload PDF | Recorte Móvel Overlap | Exibe limite de 10 MB, extensão .pdf e marca verde de confirmação [✓]. |
| 6 | Modal Protocolo SEI | Recorte Pop-up | Mostra número de protocolo e aviso de envio para o e-mail institucional. |
| 7 | Painel de Acompanhamento | Base A4 Estática | Linha do tempo com 3 fases: Recebido, Em Análise e Concluído. |

---

## 3. Planejamento da Avaliação Segundo o Framework DECIDE

O Framework DECIDE (Sharp, Rogers e Preece, 2007; Barbosa e Silva, 2010, p. 312-316) guia o planejamento de avaliações de IHC através de seis etapas encadeadas e iterativas.

A seguir, detalha-se cada letra do framework aplicada ao protótipo de papel do módulo de aproveitamento de estudos.

### 3.1. D — Determinar os Objetivos da Avaliação de IHC

O objetivo central é realizar uma avaliação formativa de usabilidade e comunicabilidade do protótipo de papel, investigando se a solução proposta permite ao estudante solicitar dispensas disciplinares de forma clara, eficiente e sem erros de interpretação.

**Objetivos específicos:**

- Avaliar a clareza da navegação no Teams e a localização do aplicativo.
- Verificar se o estudante compreende a busca de equivalências e a classificação de créditos (Obrigatória/Optativa/Livre).
- Avaliar a sensação de segurança visual durante o upload de PDFs (limites de 10 MB e indicador verde [✓]).
- Checar a efetividade do feedback do protocolo SEI e o envio de comprovante por e-mail institucional.

### 3.2. E — Explorar Perguntas a Serem Respondidas

As perguntas de avaliação foram formuladas para orientar a observação durante a interação com o papel e estruturar a entrevista pós-teste, correlacionando-se com as metas de usabilidade (Barbosa e Silva, 2010, p. 313).

| ID | Pergunta de Avaliação | Meta de Usabilidade / Fator Relacionado |
|---|---|---|
| Q1 | O estudante localiza facilmente a aba 'Serviços Acadêmicos' no canal geral do Teams? | Facilidade de Aprendizado e Navegabilidade |
| Q2 | A busca de equivalências deixa claro o tipo de crédito (Obrigatória, Optativa ou Módulo Livre)? | Comunicabilidade e Clareza Conceitual |
| Q3 | O componente de upload transmite clareza sobre os arquivos  e confirmação [✓]? | Prevenção de Erros e Feedback Visual |
| Q4 | O recebimento do comprovante por e-mail institucional elimina o receio de perda do protocolo? | Segurança do Usuário e Fechamento de Operação |
| Q5 | A linha do tempo em 3 status (Recebido, Em Análise, Concluído) esclarece a atuação da coordenação? | Visibilidade do Estado do Sistema |

### 3.3. C — Escolher os Métodos de Avaliação de IHC

**Método Selecionado:** Prototipação em Papel (Snyder, 2003; Barbosa e Silva, 2010, Seção 10.2.3), combinada com o método de Teste de Usabilidade (*Usability Testing*) e protocolo de *Think Aloud* (Pensar em Voz Alta).

**Justificativa:** A simulação com papel é um método rápido, de baixo custo e altamente interativo. Permite testar a adequação do modelo mental do usuário e identificar gargalos na linguagem visual antes de qualquer desenvolvimento de código, possibilitando refinamentos imediatos no papel entre as sessões de teste.

### 3.4. I — Identificar e Lidar com as Questões Práticas e Logística

| Aspecto Prático | Definição Operacional e Recursos Alocados |
|---|---|
| Perfil dos Participantes | Estudantes de graduação regulares da FCTE/UnB que utilizam o MS Teams semanalmente em suas rotinas acadêmicas. |
| Recrutamento | Abordagem presencial no campus da UnB (FCTE/FGA), convidando voluntários para colaboração em pesquisa acadêmica. |
| Ambiente de Teste | Sala silenciosa e reservada na FCTE/UnB com mesa e cadeiras para o participante e os três membros da equipe. |
| Equipamentos | Telefone celular em tripé de apoio (visão superior com foco nas mãos/papel), canetas, post-its, tesoura e vias impressas do TCLE. |
| Papel: Moderador | Conduz a sessão, apresenta as instruções do cenário, estimula o think aloud e realiza a entrevista pós-teste. |
| Papel: Computador Humano | Simulador do Sistema: posiciona e troca as peças de papel em resposta neutra às ações do participante. |
| Papel: Observador / Escriba | Anota tempos de execução, caminhos percorridos, erros, dúvidas verbalizadas e pontos de hesitação. |
| Estudo-Piloto (Teste-Piloto) | Sessão prévia realizada em 22/10/2026 para testar o enquadramento da câmera, legibilidade dos papéis e tempo de execução. |

### 3.5. D — Decidir como Lidar com as Questões Éticas

A avaliação será conduzida em conformidade estrita com a Resolução CNS nº 466/2012 e a Lei Geral de Proteção de Dados (LGPD). Os seguintes protocolos de salvaguarda ética serão aplicados (Barbosa e Silva, 2010, Cap. 9):

- **Assinatura do TCLE:** O participante assinará o Termo de Consentimento Livre e Esclarecido antes de qualquer atividade.
- **Esclarecimento de Foco:** O moderador reiterará que o teste avalia o protótipo e o sistema, e jamais a capacidade do aluno.
- **Privacidade e Imagem:** A gravação focará estritamente na mesa e na manipulação dos papéis, preservando a identidade visual.
- **Direito de Desistência:** É garantido ao participante o direito de interromper a sessão a qualquer momento sem qualquer penalidade.

### 3.6. E — Avaliar, Interpretar e Apresentar os Dados

Os dados qualitativos coletados (anotações do escriba, áudio do think aloud, gravação de vídeo e respostas pós-teste) serão interpretados em reunião de consolidação da equipe de IHC logo após as sessões.

**Classificação dos problemas de usabilidade:** Os problemas encontrados serão categorizados segundo a escala de severidade de Nielsen (1994):

- **Severidade 1 (Cosmético):** Ajuste superficial de layout que não impede a execução.
- **Severidade 2 (Pequeno):** Dúvida pontual ou pequeno atraso sem bloquear a tarefa.
- **Severidade 3 (Grande):** Falha grave na navegação ou feedback que exige redesign imediato.

**Apresentação dos Resultados:** Os resultados serão apresentados através de relatório sintético contendo tabelas de problemas e o planejamento do reprojeto (REP).

---

## 4. Tabela de Rastreabilidade Metodológica e Referências

| Etapa DECIDE | Mapeamento no Livro de Simone Barbosa | Artefatos e Fontes Conectadas no Projeto |
|---|---|---|
| D - Objetivos | Simone Barbosa & Bruno Silva (2010), Cap. 9, Seção 9.8, p. 312. | Análise de Tarefas (HTA) e Storyboard manual v1.1. |
| E - Perguntas | Simone Barbosa & Bruno Silva (2010), Cap. 9, Seção 9.8, p. 313. | Perguntas de usabilidade Q1–Q5 do roteiro de teste. |
| C - Métodos | Simone Barbosa & Bruno Silva (2010), Cap. 10, Seção 10.2.3, p. 358-362. | Método de Prototipação em Papel (Snyder, 2003). |
| I - Logística | Simone Barbosa & Bruno Silva (2010), Cap. 9, Seção 9.7.2, p. 308. | Papéis de equipe (Snyder, 2003) e Teste-Piloto de 22/10/2026. |
| D - Ética | Simone Barbosa & Bruno Silva (2010), Cap. 9, Seção 9.7.1, p. 303. | Resolução CNS 466/2012, LGPD e TCLE do projeto. |
| E - Resultados | Simone Barbosa & Bruno Silva (2010), Cap. 9, Seção 9.7.5, p. 311. | Classificação de Severidade de Nielsen (1994) e Plano REP. |

---

## 5. Referências Bibliográficas

- **BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da.** *Interação Humano-Computador*. Rio de Janeiro: Elsevier / Editora Campus, 2010. ISBN 978-85-352-3418-3.
- **BARBOSA, Simone Diniz Junqueira et al.** *Interação Humano-Computador e Experiência do Usuário*. Rio de Janeiro: Autopublicação, 2021. ISBN: 978-65-00-19677-1.
- **NIELSEN, Jakob.** *Usability Engineering*. San Francisco: Morgan Kaufmann, 1994.
- **ROGERS, Yvonne; SHARP, Helen; PREECE, Jenny.** *Design de Interação: além da interação homem-computador*. Porto Alegre: Bookman, 2013.
- **SHARP, Helen; ROGERS, Yvonne; PREECE, Jenny.** *Interaction Design: beyond human-computer interaction*. 2nd ed. Wiley, 2007.
- **SNYDER, Carolyn.** *Paper Prototyping: The Fast and Easy Way to Design and Refine User Interfaces*. San Diego: Morgan Kaufmann, 2003.
- **UNIVERSIDADE DE BRASÍLIA (UnB).** *Manual de Peticionamento Eletrônico: Aproveitamento de Estudos e Dispensa de Componentes Curriculares*. Versão 4.0. Brasília: SAA/UnB, 2023.


## Histórico de versão
| Versão | Data       | Descrição                                                                | Autor(es)     | Revisor(es) |
| ------ | ---------- | ------------------------------------------------------------------------ | ------------- | ----------- |
| `1.0`  | 30/10/2026 | Criação da página.                                                       | Evellyn Rocha  |             |