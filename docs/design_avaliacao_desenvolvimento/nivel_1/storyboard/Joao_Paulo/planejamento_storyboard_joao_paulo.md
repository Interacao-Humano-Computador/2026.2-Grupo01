## Tabela de contribuição

| Data       | Contribuição | Autor(es) | Revisor(es) |
| ---------- | ------------ | --------- | ----------- |
| 05/11/2026 | Separação do conteúdo de João Paulo em página própria | João Paulo da Silva Pereira | A definir   |

# João Paulo - Planejamento da avaliação do storyboard

Objetivos, melhorias propostas, perguntas, método e roteiro do agendamento de reunião com o coordenador do curso (Nível 1).

> Esta página reúne, em um só lugar, a parte de João Paulo da Silva Pereira no projeto. O conteúdo foi separado de: [planejamento_avaliacao_storyboard.md](../../../../planejamento/storyboard/planejamento_avaliacao_storyboard.md), seções 3.2, 3.3, 4.2, 5.2 e 7.2.

---

### 3.2 Objetivos da avaliação do storyboard - Agendamento de reunião com o coordenador do curso

Esta subseção trata do storyboard da tarefa de **agendar uma reunião com o coordenador do curso**, sob a ótica do Perfil 1 (Estudante). Como a persona oficial do Estudante ainda não está preenchida na wiki, o storyboard usa uma persona provisória e fictícia, **Rafaela Duarte**, 21 anos, estudante de graduação, que precisa tirar uma dúvida com o coordenador sobre aproveitamento de disciplinas antes da matrícula. Esse nome deve ser trocado pelo da persona oficial quando o grupo a definir. Aqui não há canal da turma: a reunião é entre duas pessoas, e o desafio é encontrar o coordenador, achar um horário livre para os dois e deixar claro o assunto.

O storyboard avaliado (SB-A) tem sete quadros, apresentados na Tabela 1-A.

| Quadro | Cena                                                                     | Resposta do sistema                                         |
| ------ | ------------------------------------------------------------------------ | ----------------------------------------------------------- |
| 1      | Rafaela precisa tirar uma dúvida com o coordenador antes da matrícula.       | -                                                           |
| 2      | Abre o Calendário e aciona "Nova reunião".                               | Formulário enxuto aberto.                                   |
| 3      | Busca o coordenador pelo nome e o adiciona como participante.            | Sugestão do coordenador exibida ao digitar.                 |
| 4      | Consulta a disponibilidade do coordenador e escolhe um horário livre.    | Horários livres dos dois destacados; conflitos sinalizados. |
| 5      | Informa o assunto e a duração da reunião.                                | Campo de assunto com orientação do que escrever.            |
| 6      | Envia o convite.                                                         | Confirmação de envio; lembrete padrão discreto.             |
| 7      | O coordenador responde e Rafaela confere o status no calendário.          | Status do convite (aceito, pendente ou recusado) visível.   |

<p align="center">Tabela 1-A - Quadros do storyboard de agendamento de reunião com o coordenador (SB-A).</p>

Considerando os objetivos e as perguntas definidas por Barbosa e Silva (2021), declarados na [Tabela 1](#3-d-determinar-os-objetivos-da-avaliacao), o objetivo escolhido para esta tarefa foi **Identificar problemas na interação e interface**. A escolha se justifica porque o storyboard foi construído para evidenciar pontos de atrito já relatados: dificuldade de localizar a pessoa certa e a ação, conflito de horários percebido tarde, mensagens vagas sem a ação esperada e excesso de opções na tela.

Os objetivos específicos para esta tarefa incluem:

- Verificar se o participante compreende a sequência de ações necessária para marcar uma reunião com outra pessoa.
- Verificar se a busca pelo coordenador e a escolha de um horário livre para os dois são claras.
- Identificar elementos do formulário cuja função não fique clara.
- Verificar se o envio do convite e o status da resposta são percebidos nos quadros.
- Identificar oportunidades de melhoria para o reprojeto do fluxo de agendamento.

**Fundamentação bibliográfica:** Barbosa e Silva (2021), Capítulo 11, páginas 250 e 251 (objetivos e perguntas de IHC), conforme [Figura 1](#figura-1) e [Figura 2](#figura-2).

### 3.3 Melhorias propostas para o agendamento de reunião com o coordenador

O storyboard SB-A representa o reprojeto conceitual do agendamento. A Tabela 1-B relaciona cada problema já identificado na análise de tarefas (HTA de Comunicação entre usuários e HTA do Gestor, nó 3.1) e nas necessidades do perfil Estudante à melhoria proposta e ao quadro em que ela aparece. As melhorias são hipóteses de design: a avaliação com participantes verificará se elas funcionam, sem presumir que serão mantidas.

**Tabela 1-B – Problemas, melhorias propostas e quadros do SB-A**

| ID  | Problema identificado                                                              | Melhoria proposta                                                                                              | Quadro | Origem                                       |
| --- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------ | -------------------------------------------- |
| M01 | Dificuldade de localizar a pessoa certa e a ação de agendar.                       | Sugerir o coordenador ao digitar o nome e oferecer atalho "Marcar reunião" a partir da conversa com ele.       | 3      | HTA 2.4 (Comunicação entre usuários)         |
| M02 | Choque de horários, percebido só depois de enviar o convite.                       | Exibir a disponibilidade do coordenador durante o agendamento e sinalizar conflitos antes do envio.            | 4      | HTA 3.1 (Gestor)                             |
| M03 | Formulário com muitas opções e termos sem explicação.                              | Mostrar só os campos essenciais (participante, horário, assunto) e explicações curtas embutidas.               | 2      | Perfil Estudante (a confirmar na persona) |
| M04 | Mensagem vaga, sem a ação esperada explícita.                                      | Pedir um assunto e orientar o que escrever (motivo e o que se espera do coordenador).                          | 5      | HTA 1.1 (Comunicação entre usuários)         |
| M05 | Notificações em excesso, que geram ansiedade.                                      | Lembrete padrão discreto, com opção de escolher se e quando ele é enviado.                                     | 6      | Perfil Estudante (a confirmar na persona) |
| M06 | Incerteza sobre o envio do convite.                                                | Confirmar o envio com mensagem clara e mostrar onde a reunião ficou no calendário.                             | 6      | Fluxo do SB-A                                |
| M07 | Falta de retorno sobre a resposta do convidado.                                    | Mostrar o status do convite (aceito, pendente, recusado) e permitir propor outro horário.                      | 7      | HTA 3.1 (Comunicação entre usuários)         |

*Fonte: Elaborado pela equipe, a partir das HTA e do perfil Estudante; origens marcadas "a confirmar" dependem da persona oficial.*

Cada melhoria deve ficar visível no desenho do quadro indicado, e não apenas na legenda. A Tabela 3-A (seção 7.2) verifica M01 a M04 e M06 nas perguntas 3, 4 e 5. M05 e M07 ainda não têm pergunta própria e podem ser acrescentadas ao roteiro se a equipe decidir mantê-las.

### 4.2 Perguntas da avaliação do storyboard - Agendamento de reunião com o coordenador

As perguntas segundo Barbosa e Silva (2021), declaradas na [Figura 1](#figura-1) e na [Figura 2](#figura-2), que se destacam para esta avaliação, dentro do objetivo **Identificar problemas na interação e interface**, são:

**O usuário consegue operar o sistema?**: Verifica se, a partir dos quadros, o participante entende como iniciar a reunião, encontrar o coordenador e enviar o convite.

**Ele atinge seu objetivo? Com quanta eficiência? Após cometer quantos erros?**: Verifica se o fluxo leva a um horário livre para os dois sem tentativas repetidas.

**Ele entende o que significa e para que serve cada elemento de interface?**: Explora campos como participante, indicador de disponibilidade e assunto, relacionados à necessidade de explicações embutidas.

**Ele vai entender o que deve fazer em seguida?**: Avalia as transições entre os quadros, principalmente entre a escolha do horário e o envio do convite.

**Que problemas de IHC dificultam ou impedem o usuário de alcançar seus objetivos? Onde esses problemas se manifestam?**: Registra o quadro em que cada dificuldade aparece, para alimentar a tabela de problemas do relato dos resultados.

**Ele tem acesso a todas as informações oferecidas pelo sistema?**: Verifica se a disponibilidade do coordenador, a confirmação de envio e o status da resposta são visíveis ao usuário.

### 5.2 - Método de avaliação escolhido para avaliação do storyboard - Agendamento de reunião

Para o agendamento de reunião, o método escolhido é o mesmo descrito na seção 5: **investigação por entrevista semiestruturada**, guiada pela apresentação do storyboard SB-A. O objetivo "Identificar problemas na interação e interface" pede que o participante explique o que entende de cada quadro, o que a entrevista permite, sem exigir uma interface em código.

Como o facilitador não explica nem orienta durante a sessão, tudo o que o participante precisa saber deve estar nos quadros. O autor do storyboard não conduz a sessão de avaliação desse storyboard.

### 7.2. Roteiro de perguntas - Agendamento de reunião com o coordenador

Para o storyboard SB-A, o entrevistador utilizará as perguntas da Tabela 3-A, no mesmo formato da Tabela 3.

**Tabela 3-A – Roteiro de Perguntas para Validação do Storyboard de Agendamento de Reunião com o Coordenador**

| ID    | Pergunta / Enunciado                                                                                                            | Opções de Resposta       | Espaço para Observações e Justificativas                           |
| ----- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ------------------------------------------------------------------ |
| **1** | A narrativa visual é coerente com o objetivo de marcar uma reunião com o coordenador do curso?                                  | Sim / Não / Parcialmente | Registrar se o participante compreendeu o fluxo inicial.           |
| **2** | A situação retratada é compatível com sua experiência ao marcar reuniões com outras pessoas no Microsoft Teams?                 | Sim / Não / Parcialmente | Registrar comentários sobre experiências semelhantes.              |
| **3** | O storyboard apresenta os passos necessários para marcar a reunião, da abertura do formulário ao status da resposta?            | Sim / Não / Parcialmente | Identificar possíveis etapas ausentes.                             |
| **4** | Fica claro como encontrar o coordenador e o que cada campo do formulário significa?                                             | Sim / Não / Parcialmente | Registrar campos ou ícones que gerem dúvida.                       |
| **5** | A disponibilidade do coordenador e a confirmação de envio do convite são fáceis de perceber?                                    | Sim / Não / Parcialmente | Registrar o quadro em que a informação passou despercebida.        |
| **6** | A proposta de interação apresentada nos quadros parece facilitar o agendamento em relação ao que você conhece do Teams?         | Sim / Não / Parcialmente | Registrar a percepção geral do participante e suas justificativas. |

*Fonte: Elaborado pela equipe, no formato da Tabela 3.*

---

## Histórico de versão

| Versão | Data       | Descrição | Autor(es) | Revisor(es) |
| ------ | ---------- | --------- | --------- | ----------- |
| `1.0` | 05/11/2026 | Separação da parte de João Paulo em uma pasta própria | João Paulo da Silva Pereira | |
