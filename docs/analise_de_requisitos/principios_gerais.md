# Princípios Gerais de Projeto de IHC Aplicados ao Microsoft Teams

## Tabela de contribuição

| Data | Contribuição | Autor(es) | Revisor(es) |
| ---------- | ------------------ | ----------- | ----------- |
| 05/10/2026 | Criação da página. | Lucas Sales | |
| 06/10/2026 | Aplicação dos Princípios Gerais de Projeto de IHC ao Microsoft Teams, com base nos problemas identificados na entrevista com o estudante João. | Evellyn de Sousa Rocha | |

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---------- | ------------------ | ----------- | ----------- |
| `1.0` | 05/10/2026 | Criação da página. | Lucas Sales | |
| `1.1` | 06/10/2026 | Inclusão da aplicação dos Princípios Gerais de Projeto de IHC e das diretrizes de redesign. | Evellyn de Sousa Rocha | |

---

## 1. Introdução

Os **Princípios Gerais de Projeto de IHC**, apresentados por Barbosa e Silva, podem ser utilizados para orientar decisões de projeto de interfaces a partir das necessidades, dificuldades e expectativas dos usuários.

No contexto deste projeto, os princípios são aplicados ao **Microsoft Teams**, considerando principalmente os problemas identificados na entrevista com o estudante João, como **poluição visual, dificuldade para localizar arquivos e notificações invasivas**.

A aplicação dos princípios busca transformar os problemas identificados em **diretrizes concretas de interface**, contribuindo para uma experiência mais simples e adequada ao contexto acadêmico.

---

## 2. Princípios de Design Aplicados

### 2.1 Correspondência com as Expectativas e Mapeamento Natural

**Princípio:**

A interface deve seguir a linguagem, o vocabulário e o modelo mental do usuário, evitando organizar as informações apenas de acordo com a lógica interna do sistema.

**Aplicação no Microsoft Teams:**

- **Organização acadêmica:** estruturar os canais e abas das equipes utilizando nomenclaturas relacionadas ao contexto universitário, como *"Materiais Didáticos"*, *"Gravações de Aula"* e *"Entregas"*.
- **Redução de jargões:** evitar termos técnicos relacionados ao ecossistema Microsoft/SharePoint que possam dificultar tarefas como salvar e compartilhar arquivos.

---

### 2.2 Simplicidade nas Estruturas das Tarefas

**Princípio:**

A interface deve reduzir a quantidade de etapas necessárias para realizar uma tarefa, seguindo a ideia de que estruturas mais simples podem facilitar a interação.

**Aplicação no Microsoft Teams:**

- **Atalho direto para arquivos:** permitir que os materiais da disciplina sejam visualizados e baixados em no máximo **1 ou 2 cliques** a partir da tela da turma.
- **Ações visíveis:** disponibilizar o botão **"Baixar"** diretamente sobre o documento, evitando esconder a ação dentro de menus adicionais, como o menu de três pontos (`...`).

---

### 2.3 Visibilidade e Reconhecimento em vez de Memorização

**Princípio:**

O usuário não deve precisar memorizar em qual tela, canal ou pasta uma determinada informação está localizada. As opções e informações importantes devem estar visíveis no contexto da tarefa.

**Aplicação no Microsoft Teams:**

- **Painel de recentes da disciplina:** apresentar na página inicial do canal os últimos materiais publicados pelo professor e o link direto para a reunião síncrona atual.
- **Redução da necessidade de memorizar caminhos:** evitar que o estudante precise lembrar em qual canal ou pasta um determinado PDF foi disponibilizado.

---

### 2.4 Projeto Estético e Minimalista

**Princípio:**

A interface deve evitar informações irrelevantes ou pouco utilizadas, pois elementos desnecessários podem competir pela atenção do usuário.

**Aplicação no Microsoft Teams:**

- **Modo Estudo/Foco:** permitir ocultar guias e funcionalidades secundárias, mantendo o foco nas atividades acadêmicas.
- **Menu lateral simplificado:** priorizar módulos utilizados na rotina acadêmica, como **Equipes, Arquivos, Chat e Reuniões**.
- **Redução da poluição visual:** diminuir a quantidade de funcionalidades apresentadas simultaneamente ao estudante.

---

### 2.5 Equilíbrio entre Controle e Liberdade do Usuário

**Princípio:**

O sistema deve oferecer ao usuário controle sobre a interação e disponibilizar formas claras de interromper ou cancelar ações.

**Aplicação no Microsoft Teams:**

- **Gerenciamento de notificações:** disponibilizar uma opção de **"Não Perturbe" ou "Foco nos Estudos"** para silenciar notificações durante atividades acadêmicas.
- **Navegação segura:** disponibilizar opções claras de **"Voltar"** e **"Cancelar"** durante operações como carregamento ou download de arquivos.

---

### 2.6 Promoção da Eficiência do Usuário

**Princípio:**

A interface deve oferecer recursos que tornem mais rápidas as tarefas realizadas frequentemente pelos usuários, incluindo mecanismos de busca e atalhos.

**Aplicação no Microsoft Teams:**

- **Busca global aprimorada:** permitir filtros por informações como **nome do professor, mês/ano e tipo de arquivo**, facilitando a localização de conversas e materiais.
- **Atalhos de teclado:** disponibilizar e destacar atalhos para usuários que realizam tarefas frequentes, como `Ctrl+E` para acessar a busca.

---

### 2.7 Prevenção de Erros e Recuperação

**Princípio:**

O sistema deve procurar prevenir erros e, quando eles ocorrerem, apresentar mensagens claras e indicar ao usuário como solucionar o problema.

**Aplicação no Microsoft Teams:**

- **Prevenção de áudio aberto:** sinalizar de maneira clara quando o microfone estiver ativado ao entrar em uma reunião.
- **Tratamento de falhas de download:** caso ocorra uma interrupção durante o download de um arquivo, apresentar uma mensagem em linguagem simples e disponibilizar a opção **"Tentar novamente"**, evitando mensagens de erro pouco compreensíveis.

---

## 3. Relação entre Princípios, Problemas e Soluções

A tabela abaixo relaciona os princípios de projeto às dificuldades identificadas durante a entrevista com o estudante e às soluções de interface propostas.

| Princípio de Projeto | Problema identificado | Solução de interface proposta |
|---|---|---|
| Correspondência com as expectativas e mapeamento natural | Termos e organização pouco relacionados ao contexto acadêmico | Utilizar nomenclaturas como "Materiais Didáticos", "Gravações de Aula" e "Entregas" |
| Simplicidade nas estruturas das tarefas | Dificuldade para localizar e baixar arquivos | Disponibilizar acesso direto aos materiais em 1 ou 2 cliques |
| Visibilidade e reconhecimento | Necessidade de procurar em diferentes canais e pastas | Criar painel de materiais recentes e acesso direto às reuniões |
| Projeto estético e minimalista | Excesso de funcionalidades e poluição visual | Ocultar funcionalidades secundárias e simplificar o menu principal |
| Equilíbrio entre controle e liberdade | Notificações interrompem a realização das atividades | Disponibilizar modo "Não Perturbe" ou "Foco nos Estudos" |
| Promoção da eficiência do usuário | Busca por arquivos e conversas é demorada | Aprimorar a busca com filtros e atalhos |
| Prevenção de erros e recuperação | Microfone aberto e falhas durante downloads | Alertas claros e opção de "Tentar novamente" |

---

## 4. Diretrizes de Redesign

A partir da aplicação dos princípios, são propostas as seguintes diretrizes para o redesign da interface do Microsoft Teams no contexto acadêmico:

1. **Simplificar a interface**, reduzindo a quantidade de funcionalidades apresentadas simultaneamente.
2. **Facilitar o acesso aos materiais**, reduzindo a quantidade de etapas necessárias para localizar e baixar arquivos.
3. **Melhorar a organização das informações**, utilizando categorias e nomenclaturas relacionadas ao contexto acadêmico.
4. **Destacar informações recentes**, como materiais publicados e reuniões próximas.
5. **Aprimorar a busca**, permitindo localizar rapidamente arquivos e conversas.
6. **Oferecer maior controle sobre notificações**, especialmente durante atividades de estudo.
7. **Utilizar mensagens de erro claras**, acompanhadas de ações para recuperação.
8. **Destacar ações importantes**, evitando esconder funções frequentes em menus secundários.

---

## 5. Referência

BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação Humano-Computador*. Rio de Janeiro: Elsevier, 2010.