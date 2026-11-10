## Tabela de contribuição

| Data       | Contribuição                                                                                        | Autor(es) | Revisor(es) |
| ---------- | --------------------------------------------------------------------------------------------------- | --------- | ----------- |
| 03/11/2026 | Adição do planejamento do teste de usabilidade do agendamento de reunião com o coordenador do curso | João Paulo da Silva Pereira | A definir   |
| 05/11/2026 | Reestruturação do planejamento no formato DECIDE, com perguntas, roteiro em blocos, tarefas e cronograma por sessão | João Paulo da Silva Pereira | A definir   |

# João Paulo - Planejamento da avaliação do protótipo de alta fidelidade (teste de usabilidade)

> **Funcionalidade:** agendamento de reunião com o coordenador do curso no Microsoft Teams (Perfil 1, Estudante).
> O planejamento geral do grupo está em [Planejamento do teste de usabilidade](../planejamento_teste_usabilidade.md). Esta página aplica o planejamento ao agendamento.

## 1. Introdução

O protótipo de alta fidelidade reproduz a aparência e a interação da tela final, em meio digital, e se diferencia do protótipo de papel, em que um avaliador simula o sistema. Para o agendamento, ele será construído no Figma e testado com estudantes antes da implementação, para medir eficácia, eficiência e satisfação ao marcar uma reunião com o coordenador.

O protótipo parte do storyboard, da HTA do Estudante e dos resultados do [protótipo de papel](../../nivel_2/prototipo_papel/Joao_Paulo/resultados_prototipo_papel_joao.md).

## 2. Metodologia: o framework DECIDE

A avaliação segue o DECIDE (Barbosa e Silva, 2021): (D) determinar os objetivos, (E) explorar as perguntas, (C) escolher os métodos, (I) identificar as questões práticas, (D) decidir como lidar com as questões éticas e (E) avaliar, interpretar e apresentar os dados.

## 3. D - Determinar os objetivos

A avaliação é formativa. Os objetivos são:

1. **Navegabilidade e fluxo digital:** verificar se o estudante percorre sozinho os passos 1 a 6 da HTA no protótipo digital;
2. **Entrada da tarefa:** verificar se a entrada pelo Calendário e pela conversa com o coordenador resolve o problema OPO-AG01 do protótipo de papel (o participante esperava iniciar por uma área de reuniões);
3. **Clareza dos elementos:** verificar se a lista de sugestões (nome e cargo), a disponibilidade dos dois, a orientação do assunto e o status do convite são entendidos;
4. **Problemas residuais de usabilidade:** identificar problemas que o papel não revelou;
5. **Satisfação subjetiva:** coletar a opinião do estudante e a comparação com o jeito que ele usa hoje.

## 4. E - Explorar perguntas

As perguntas foram adaptadas de Barbosa e Silva (2021) ao agendamento, e cada uma está ligada a uma meta de usabilidade.

**Tabela 1 - Perguntas de pesquisa**

| Nº  | Pergunta norteadora                                                                                   | Meta de usabilidade / critério            | Origem                           |
| --- | ----------------------------------------------------------------------------------------------------- | ----------------------------------------- | -------------------------------- |
| P01 | O estudante consegue iniciar a reunião sozinho, pelo Calendário ou pela conversa com o coordenador?   | Facilidade de aprendizado                 | OPO-AG01 (papel), T01            |
| P02 | Ele escolhe o coordenador, e não a secretaria, na lista de sugestões?                                 | Eficácia; reconhecimento em vez de memorização | VAL-AG01 (papel)            |
| P03 | Ele entende a disponibilidade dos dois e escolhe um horário livre para ambos?                         | Eficácia; visibilidade do estado do sistema | VAL-AG02 (papel), T01          |
| P04 | Em quanto tempo ele escreve o assunto, com a orientação do campo, e sem hesitar?                      | Eficiência                                | T02 (análise de tarefas)         |
| P05 | Ele entende a confirmação do envio e o status do convite (pendente, aceito ou recusado)?              | Visibilidade do estado do sistema         | VAL-AG03 (papel), T03            |
| P06 | Quanto tempo e quantos erros são necessários para concluir a tarefa?                                  | Eficiência; eficácia                      | Barbosa e Silva (2021)           |
| P07 | Como é a satisfação subjetiva, e como ele compara o protótipo com o e-mail ou outro meio que usa hoje? | Satisfação                                | T04 (análise de tarefas)         |

## 5. C - Escolher os métodos

Será usado o **teste de usabilidade com protótipo de alta fidelidade**, em ambiente controlado, com três componentes: execução da tarefa no computador, técnica *think aloud* (verbalização durante o uso) e entrevista pós-teste (Rubin e Chisnell, 2008).

## 6. I - Identificar as questões práticas

### 6.1 Recrutamento

Participam estudantes de graduação da FCTE/UnB (Perfil 1), usuários do Microsoft Teams. Serão 3 participantes, seguindo Krug (2010) e Nielsen (1993), que indicam de 3 a 4 usuários para detectar a maioria dos problemas. A preferência é por quem ainda não viu o storyboard nem o protótipo de papel do agendamento. Os participantes serão identificados por letra.

### 6.2 Papéis da equipe

- **Moderador:** apresenta o termo de consentimento, lê os cenários e conduz a entrevista, sem explicar a interface durante a tarefa;
- **Observador:** registra tempos, erros, falas e pedidos de ajuda, e cuida da gravação.

Como o autor da funcionalidade conduz as sessões, o ideal é que o observador seja outro membro da equipe, para reduzir o viés.

### 6.3 Recursos

Protótipo interativo no Figma, notebook com mouse e teclado, celular com tripé para gravar a tela e o áudio (com autorização), termo de consentimento e ficha de observação. Local: sala vaga da FCTE/UnB. Não há custo adicional.

### 6.4 Protótipo

O protótipo digital terá as seguintes telas:

1. Calendário do Teams com o botão "+ Nova reunião";
2. Conversa com o coordenador, com a opção "Marcar reunião" (nó 1.2 da HTA);
3. Formulário de nova reunião com o campo Participante e a lista de sugestões (nome e cargo);
4. Disponibilidade dos dois, com horários livres e ocupados;
5. Assunto (com orientação do que escrever) e duração;
6. Resumo, botão "Enviar convite" e confirmação com lembrete;
7. Evento com o status do convite e o botão "Propor outro horário".

Os dados são fictícios (estudante Rafaela Duarte, coordenador Carlos Menezes, secretaria Carla Coordenadoria).

### 6.5 Tarefas e roteiro estruturado

**Bloco 1 - Abertura e protocolo ético (cerca de 2 min).** Apresentação, leitura do termo de consentimento e a frase: "estamos avaliando o sistema e não você". Pedido de *think aloud* e permissão para gravar.

**Bloco 2 - Entrevista pré-teste (cerca de 2 min).** Qual seu curso e semestre? Com que frequência usa o Teams? Já marcou reunião com professor ou coordenador, e por qual meio?

**Bloco 3 - Execução das tarefas (cerca de 8 a 10 min).**

**Tabela 2 - Tarefas, cenário e critério de êxito**

| Tarefa | Cenário lido pelo moderador                                                                                                                           | Ação esperada                                                                                                        | Critério de êxito                                                                               |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| 1      | Você é a Rafaela, estudante. A matrícula é daqui a 5 dias e você tem uma dúvida sobre aproveitamento de disciplinas. Marque uma reunião de 30 minutos com o coordenador, Carlos Menezes, na quinta-feira. | Iniciar a reunião (Calendário ou conversa), escolher o coordenador, escolher horário livre para ambos, informar o assunto e enviar (nós 1 a 5). | Convite enviado ao coordenador, em horário livre para os dois, com 30 minutos e assunto preenchido. |
| 2      | O coordenador respondeu que não pode no horário escolhido. Veja a resposta e proponha outro horário.                                                  | Consultar o status do convite e usar "Propor outro horário" (nós 6.1 e 6.2).                                         | Identifica o status recusado e envia uma nova proposta de horário.                              |

**Bloco 4 - Entrevista pós-teste (cerca de 3 min).**
1. Como foi fazer a tarefa? Houve algum momento de dúvida?
2. Como você escolheu por onde começar?
3. A lista de sugestões e os horários dos dois ficaram claros?
4. O campo de assunto ajudou? O que você escreveria?
5. Como você soube que o convite foi enviado e qual era a resposta?
6. Comparando com o que você faz hoje para marcar reunião, o que achou mais fácil e mais difícil?
7. O que você mudaria?

### 6.6 Cronograma

**Tabela 3 - Cronograma de construção e sessões (datas a confirmar)**

| Sessão / atividade              | Participante | Perfil   | Moderador  | Observador | Data prevista | Local / formato          |
| ------------------------------- | ------------ | -------- | ---------- | ---------- | ------------- | ------------------------ |
| Construção do protótipo no Figma | -            | -        | João Paulo | -          | 07 a 09/11    | Remoto                   |
| Piloto                          | Voluntário   | Estudante | João Paulo | A definir  | 10/11         | FCTE/UnB, presencial     |
| S01                             | Participante A | Estudante | João Paulo | A definir  | 10/11         | FCTE/UnB, presencial     |
| S02                             | Participante B | Estudante | João Paulo | A definir  | 11/11         | FCTE/UnB, presencial     |
| S03                             | Participante C | Estudante | João Paulo | A definir  | 12/11         | FCTE/UnB, presencial     |
| Interpretação dos dados         | -            | -        | João Paulo | -          | 13/11         | -                        |
| Relato dos resultados           | -            | -        | João Paulo | -          | 14 a 16/11    | -                        |

## 7. D - Decidir como lidar com as questões éticas

O termo de consentimento é lido e assinado antes da sessão. O foco é o sistema, e não o participante, que pode interromper a avaliação a qualquer momento. A gravação só ocorre com autorização, e o anonimato é preservado: o participante é identificado por letra e os nomes do protótipo são fictícios. Os vídeos serão publicados como não listados.

## 8. E - Avaliar, interpretar e apresentar os dados

- **Dados qualitativos:** anotações do *think aloud*, dúvidas, comentários da entrevista e problemas mapeados por tela, severidade (escala de Nielsen, de 0 a 4) e heurística violada;
- **Dados quantitativos:** taxa de conclusão por tarefa (sozinho, com ajuda ou não concluiu), número de erros e tempo por tarefa.

Os dados serão apresentados conforme o [planejamento do relato dos resultados](./planejamento_relato_resultados_teste_usabilidade_joao_paulo.md).

## 9. Teste piloto

O piloto é feito com um voluntário representativo, e os dados dele **não entram** nos resultados. Ele valida o protótipo, a clareza dos cenários, o tempo e a qualidade da gravação. As falhas serão corrigidas antes das sessões definitivas.

## 10. Referências bibliográficas

1. BARBOSA, Simone Diniz Junqueira et al. **Interação humano-computador e experiência do usuário.** Rio de Janeiro: Autopublicação, 2021.
2. KRUG, Steve. **Rocket Surgery Made Easy.** Berkeley: New Riders, 2010.
3. NIELSEN, Jakob. **Usability Engineering.** San Diego: Academic Press, 1993.
4. RUBIN, Jeffrey; CHISNELL, Dana. **Handbook of Usability Testing.** 2. ed. Indianapolis: Wiley, 2008.

## 11. Histórico de versão

| Versão | Data       | Descrição                                                                | Autor(es) | Revisor(es) |
| ------ | ---------- | ------------------------------------------------------------------------ | --------- | ----------- |
| `1.0`  | 03/11/2026 | Planejamento do teste de usabilidade do agendamento                      | João Paulo da Silva Pereira |             |
| `1.1`  | 05/11/2026 | Reestruturação no formato DECIDE, com perguntas, roteiro e cronograma    | João Paulo da Silva Pereira |             |
