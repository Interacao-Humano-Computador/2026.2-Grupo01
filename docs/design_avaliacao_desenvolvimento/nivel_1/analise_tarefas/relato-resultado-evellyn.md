
# Tabela de contribuição

| Data | Contribuição | Autor(es) | Revisor(es) |
|---|---|---|---|
| 24/10/2026 | Criação da página e adição de relatos de resultados HTA | Evellyn de Sousa Rocha | A definir |

#  Relato dos Resultados da Análise Hierárquica de Tarefas (HTA)

> **Funcionalidade avaliada:** Aproveitamento de Estudos e Dispensa de Componentes Curriculares no Microsoft Teams  
> **Base teórica:** Análise Hierárquica de Tarefas — HTA (Annett, 2003; Barbosa e Silva, 2010, cap. 6 e 9)

---

## 1. Objetivos e Escopo da Avaliação por HTA

A Análise Hierárquica de Tarefas (HTA – *Hierarchical Task Analysis*) foi desenvolvida para compreender as competências e habilidades necessárias para realizar tarefas complexas, auxiliando na identificação de gargalos e problemas de desempenho.

O objetivo deste relato é apresentar os resultados consolidados da análise do fluxo de **Aproveitamento de Estudos e Dispensa de Componentes Curriculares** no Microsoft Teams. A análise busca mapear o trabalho dos discentes em termos de objetivos, subobjetivos, planos e operações, permitindo entender como a interface possibilita ou impede os usuários de alcançarem suas metas acadêmicas de forma eficiente e sem erros.

---

## 2. Metodologia de Análise e Consolidação

A condução da HTA e a síntese de seus resultados seguiram os passos prescritos por Diaper (2003) e Barbosa e Silva (2010, pp. 192–196):

1. **Definição do Objetivo de Alto Nível (Nível 0):** Mapeamento do estado final desejado pelo estudante (obter a dispensa de disciplinas).
2. **Decomposição Hierárquica (Redescrição):** Subdivisão dos objetivos em subobjetivos mutuamente exclusivos e exaustivos [3, 8].
3. **Especificação dos Planos:** Definição das relações lógicas de execução entre os subobjetivos: sequência fixa (`>`), seleção/decisão (`/`) e paralelo/conjunto (`+`).
4. **Análise das Operações Atômicas:** Mapeamento do nível mais baixo da hierarquia por meio da tupla `<Input, Ação, Feedback>`, identificando os gatilhos, ações de interface (*widgets*) e condições de satisfação.
5. **Análise Intersujeito e Diagnóstico de Erros:** Consolidação dos dados para distinguir características representativas do grupo de usuários de idiossincrasias individuais [9], categorizando as falhas em relação ao desempenho baseado em habilidades, regras e conhecimento (Reason, 1990).

---

## 3. Representação do Diagrama HTA

Abaixo é apresentada a decomposição gráfica do objetivo `0. Aproveitar estudos e obter dispensa de componentes curriculares no MS Teams`, seguindo a notação formal em que as **operações atômicas** são identificadas por textos sublinhados.

**Figura 1 – Diagrama HTA do processo de aproveitamento de estudos e dispensa de componentes curriculares**

![Figura 1 – Diagrama HTA do processo de aproveitamento de estudos e dispensa de componentes curriculares](diagrama_hta.png)

*Fonte: Elaborado pela autora (2026).*

---

## 4. Tabela de Análise de Tarefas e Operações

Conforme a Tabela 6.3 de Barbosa e Silva (2010, p. 194), a tabela especifica as tuplas de operação `<Input, Ação, Feedback>`, articulando o comportamento do sistema com os problemas potenciais e as recomendações de IHC.

| Objetivos / Operações | Planos e Tuplas de Operação `<Input, Ação, Feedback>` | Problemas Identificados e Recomendações de IHC |
|---|---|---|
| **0. Aproveitar estudos e obter dispensa no MS Teams** | **Plano 0:** Executar 1, 2, 3 e 4 sequencialmente (1 > 2 > 3 > 4). Após confirmação, executar 5.<br><br>**Input:** Necessidade de dispensar disciplinas já cursadas.<br><br>**Feedback:** Processo deferido/indeferido e atualizado no histórico acadêmico. | **Problema:** Incerteza do aluno sobre quais disciplinas possuem equivalência.<br><br>**Recomendação:** Exibir uma lista de equivalências pré-aprovadas na interface inicial. |
| **1. Acessar módulo acadêmico no MS Teams** | **Plano 1:** Executar 1.1 e 1.2 sequencialmente (1.1 > 1.2). | — |
| **1.1 Localizar app "Serviços Acadêmicos" no canal** | **Input:** Barra de navegação e abas superiores do canal do Teams.<br><br>**Ação:** Clicar na guia "Serviços Acadêmicos".<br><br>**Feedback:** Abertura do painel de serviços. | **Problema:** Excesso de abas inativas no canal polui a visualização.<br><br>**Recomendação:** Fixar o atalho de solicitações na barra superior do canal geral. |
| **1.2 Selecionar "Aproveitamento de Estudos e Dispensa"** | **Input:** Menu de serviços disponíveis.<br><br>**Ação:** Clicar no card correspondente.<br><br>**Feedback:** Exibição da tela inicial do formulário com instruções. | **Problema:** Confusão conceitual entre dispensa interna e transferência.<br><br>**Recomendação:** Inserir texto explicativo diferenciando as modalidades. |
| **2. Preencher dados do formulário** | **Plano 2:** Executar 2.1 e 2.2 em conjunto/paralelo (2.1 + 2.2). | — |
| **2.1 Informar dados do aluno e da instituição de origem** | **Input:** Campos de formulário.<br><br>**Ação:** Digitar nome da instituição e curso de origem.<br><br>**Feedback:** Campos validados com destaque visual. | **Problema:** Preenchimento repetitivo de dados cadastrais.<br><br>**Recomendação:** Autopreencher matrícula, nome e curso a partir do login. |
| **2.2 Selecionar disciplina cursada e componente equivalente** | **Input:** Menu suspenso do currículo atual.<br><br>**Ação:** Selecionar a disciplina equivalente e informar a cursada.<br><br>**Feedback:** Par de disciplinas vinculado na solicitação. | **Problema:** Erro de digitação no código da disciplina.<br><br>**Recomendação:** Oferecer busca por código ou nome com autocompletar. |
| **3. Anexar documentação comprobatória exigida** | **Plano 3:** Executar 3.1 e 3.2 em conjunto/paralelo (3.1 + 3.2). | — |
| **3.1 Anexar Histórico Escolar Oficial autenticado (PDF)** | **Input:** Botão "Carregar Histórico Escolar".<br><br>**Ação:** Selecionar e carregar o arquivo PDF.<br><br>**Feedback:** Ícone do arquivo anexado e barra de upload em 100%. | **Problema:** Tentativa de envio de arquivos em formato não aceito.<br><br>**Recomendação:** Validar a extensão `.pdf` e indicar o tamanho máximo (10 MB). |
| **3.2 Anexar Ementa/Plano de Ensino detalhado (PDF)** | **Input:** Botão "Carregar Ementa/Plano de Ensino".<br><br>**Ação:** Fazer o upload das ementas correspondentes.<br><br>**Feedback:** Lista de ementas anexadas com botão de pré-visualização. | **Problema:** Esquecimento do anexo de ementa de alguma matéria.<br><br>**Recomendação:** Alerta visual de pendência documental para cada disciplina. |
| **4. Revisar e submeter a solicitação** | **Plano 4:** Executar 4.1 e, estando correto, executar 4.2 (4.1 > 4.2). | — |
| **4.1 Conferir dados preenchidos e lista de anexos** | **Input:** Tela de resumo dos dados e arquivos.<br><br>**Ação:** Revisar as informações inseridas.<br><br>**Feedback:** Destaque em verde para itens validados. | **Problema:** Necessidade de refazer todo o formulário para corrigir um erro.<br><br>**Recomendação:** Botão "Editar" ao lado de cada seção do resumo. |
| **4.2 Confirmar submissão e emitir protocolo** | **Input:** Botão "Submeter Solicitação".<br><br>**Ação:** Clicar no botão de envio final.<br><br>**Feedback:** Mensagem de sucesso e geração do protocolo na tela. | **Problema:** Dúvida se o pedido foi de fato recebido pela secretaria.<br><br>**Recomendação:** Enviar notificação automática no chat do Teams com protocolo. |
| **5. Acompanhar parecer e resultado final** | **Plano 5:** Executar 5.1 para consultar e 5.2 quando houver resultado (5.1 > 5.2). | — |
| **5.1 Consultar andamento da solicitação nas notificações** | **Input:** Central de notificações do Teams / aba de status.<br><br>**Ação:** Abrir o cartão da solicitação.<br><br>**Feedback:** Exibição da linha do tempo do processo. | **Problema:** Falta de visibilidade sobre o prazo de resposta.<br><br>**Recomendação:** Exibir a data estimada de conclusão do parecer. |
| **5.2 Visualizar parecer final e baixar comprovante** | **Input:** Notificação de conclusão do processo.<br><br>**Ação:** Acessar a notificação e fazer download do parecer.<br><br>**Feedback:** Download da declaração final de deferimento/indeferimento. | **Problema:** Indeferimento sem justificativa detalhada.<br><br>**Recomendação:** Apresentar parecer do relator com opção de recurso. |

---

## 5. Consolidação dos Problemas de Usabilidade e Desempenho

A consolidação dos problemas identificados na análise HTA foi priorizada segundo o seu impacto no desempenho dos discentes e a escala de severidade de Nielsen (1994a).

- **Severidade 1 (Cosmético):** Não exige correção imediata, a menos que haja tempo no cronograma.
- **Severidade 2 (Pequeno):** Problema de baixa prioridade, mas que causa pequenos atrasos ou ruídos.
- **Severidade 3 (Grande):** Alta prioridade de correção; prejudica gravemente a eficiência e a prevenção de erros.

### Tabela de Problemas Não Corrigidos (para o Reprojeto)

| ID | Localização (Tela/Operação) | Fator de Usabilidade / Tipo de Erro | Descrição e Justificativa do Problema | Frequência e Impacto | Severidade (1 a 3) | Sugestão de Redesign / IHC |
|---|---|---|---|---|---|---|
| P-01 | Operação 1.1 / Aba Superior | Visibilidade da Interface / Erro de Regra | Dificuldade em localizar o atalho do aplicativo em meio a canais poluídos. | Alta frequência no grupo. | 3 (Grande) | Fixar um botão direto "Solicitações Acadêmicas" no topo do canal. |
| P-02 | Operação 2.1 / Formulário | Eficiência no Uso / Erro de Habilidade | Redundância no preenchimento manual de dados pessoais já existentes no sistema. | Todos os participantes. | 2 (Pequeno) | Autopreencher matrícula, nome e curso via perfil autenticado do Teams. |
| P-03 | Operação 3.1 e 3.2 / Upload PDF | Prevenção de Erros / Erro de Regra | Incerteza quanto aos formatos aceitos e limite de tamanho dos documentos PDF. | Média frequência. | 2 (Pequeno) | Exibir os limites de tamanho (10 MB) e formato (`.pdf`) antes da seleção de arquivo. |
| P-04 | Operação 4.2 / Confirmação | Feedback e Comunicabilidade / Erro de Conhecimento | Incerteza do estudante após a submissão, gerando dúvidas sobre o recebimento. | Alta frequência no grupo. | 3 (Grande) | Disparar notificação automática no chat do Teams com o número do protocolo. |

---

## 6. Planejamento do Reprojeto

Com base na priorização dos problemas mapeados na HTA, o cronograma de ajustes para o reprojeto do protótipo digital seguirá a ordem de severidade e impacto.

| ID da Correção | Ação de Redesign Priorizada | Integrante Responsável | Prazo Limite | Status |
|---|---|---|---|---|
| REP-01 | Implementar o envio de notificação com protocolo no chat do Teams (P-04). | Desenvolvedor / Designer | 27/10/2026 | Pendente |
| REP-02 | Redesenhar o cabeçalho do canal geral para destacar a guia de serviços (P-01). | Designer de Interface | 27/10/2026 | Pendente |
| REP-03 | Configurar o autopreenchimento dos dados do discente no formulário (P-02). | Desenvolvedor | DD/MM/2026 | Pendente |
| REP-04 | Adicionar mensagens de instrução prévia no componente de upload de PDF (P-03). | Designer de Interface | 27/10/2026 | Pendente |


##  Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :---: | :---: | :--- | :--- | :--- |
| `1.0` | 20/10/2026 | Criação da página e adição de relatos de resultados HTA | Evellyn Rocha |  |
|

##  Referências Bibliográficas

1. ANNETT, John. **Hierarchical Task Analysis**. In: DIAPER, Dan; STANTON, Neville (Eds.). *The Handbook of Task Analysis for Human-Computer Interaction*. Mahwah, NJ: Lawrence Erlbaum Associates, 2003. pp. 67–82.
2. BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. **Interação Humano-Computador**. Rio de Janeiro: Elsevier / Editora Campus, 2010. ISBN 978-85-352-3418-3.
3. UNIVERSIDADE DE BRASÍLIA (UnB). **Manual de Peticionamento Eletrônico: Aproveitamento de Estudos e Dispensa de Componentes Curriculares**. Versão 4.0. Brasília: Secretaria de Administração Acadêmica (SAA/UnB), 2023.