# Metas de Usabilidade

## Tabela de contribuição

| Data       | Contribuição                                                                                                                                  | Autor(es)   | Revisor(es) |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ----------- |
| 05/10/2026 | Criação da página.                                                                                                                            | Lucas Sales |             |
| 05/10/2026 | Adição das seções introdução e apropriação de tecnologia.                                                                                     | Lucas Sales |             |
| 06/10/2026 | Adição das metas de avaliação restantes e das metas de usabilidade selecionadas, com justificativa, indicadores e faixas de valores            | João Paulo  |             |

## 1. Introdução

O desenvolvimento de um sistema computacional não deve considerar apenas a implementação de suas funcionalidades, mas também a forma como essas funcionalidades são compreendidas e utilizadas pelos usuários. Um sistema pode oferecer diversos recursos e, ainda assim, apresentar dificuldades de uso caso sua interface não seja adequada às necessidades, conhecimentos e características de seu público. Por esse motivo, a avaliação da interação entre usuários e sistemas é uma etapa importante para identificar oportunidades de melhoria e compreender a qualidade da experiência proporcionada.

Nesse contexto, a avaliação de sistemas em Interação Humano-Computador pode possuir diferentes objetivos, dependendo do contexto e da finalidade da análise. De forma geral, as metas de uma avaliação podem estar relacionadas a quatro categorias principais (BARBOSA et al., 2021, Seção 11.2):

* **Apropriação de tecnologia pelos usuários**, incluindo o sistema computacional avaliado, mas não se limitando a ele;
* **Ideias e alternativas de design**, buscando identificar possibilidades para melhorar a interação e a interface;
* **Conformidade com um padrão**, verificando se o sistema atende a critérios, recomendações ou diretrizes estabelecidas;
* **Problemas na interação e na interface**, buscando identificar dificuldades enfrentadas pelos usuários durante a realização de suas atividades.

Essas diferentes metas permitem direcionar a avaliação de acordo com aquilo que se pretende compreender ou aprimorar no sistema. No caso do Microsoft Teams, a análise pode contribuir para compreender como os usuários interagem com seus diferentes recursos e identificar aspectos da interface que facilitam ou dificultam a realização das tarefas.

Esta página tem duas partes. A Seção 2 apresenta as quatro metas de avaliação aplicadas ao Teams. A Seção 3 define as **metas de usabilidade** do projeto de redesenho: os fatores de qualidade de uso que a equipe vai priorizar, a justificativa de cada escolha e a definição operacional de como cada meta será medida. Conforme a Engenharia de Usabilidade de Mayhew, adotada pelo grupo como processo de design, essas metas são definidas na fase de análise de requisitos, a partir do perfil dos usuários e da análise de tarefas, e são representadas no [Guia de Estilo](guia_estilo.md) para orientar a verificação nas demais atividades (BARBOSA et al., 2021, Seção 6.3.3).

## 2. Metas da avaliação aplicadas ao Microsoft Teams

### 2.1. Apropriação da tecnologia pelos usuários

No contexto do Microsoft Teams, a apropriação da tecnologia pode ser observada pela tentativa da plataforma de atender a diferentes necessidades de comunicação, colaboração e organização em um único ambiente. Em vez de limitar-se a uma única forma de interação, o sistema reúne recursos que podem ser utilizados de acordo com diferentes atividades e contextos de uso.

Um dos principais aspectos relacionados a essa apropriação é a disponibilidade multiplataforma. O Teams pode ser acessado por computadores, navegadores e dispositivos móveis, permitindo que o usuário mantenha suas atividades mesmo quando há uma mudança de dispositivo ou de contexto. Dessa forma, a utilização do sistema não fica restrita a um único ambiente físico ou equipamento.

Outro aspecto importante é a integração com o ecossistema Microsoft 365. Recursos como Word, Excel, PowerPoint, OneDrive e Outlook podem ser utilizados em conjunto com o Teams, permitindo que comunicação, armazenamento, edição de documentos e organização de compromissos estejam relacionados dentro de um mesmo ecossistema. Essa integração busca reduzir a necessidade de utilizar diferentes ferramentas de maneira isolada para realizar atividades que fazem parte de um mesmo fluxo de trabalho.

A plataforma também procura atender diferentes formas de comunicação e colaboração. O usuário pode utilizar mensagens individuais, conversas em grupo, canais, reuniões por vídeo, chamadas de áudio e compartilhamento de tela, escolhendo o recurso mais adequado de acordo com a atividade realizada. Em um contexto educacional, por exemplo, uma equipe pode utilizar canais para organizar uma disciplina, reuniões para aulas ou discussões e arquivos compartilhados para desenvolver trabalhos colaborativamente.

Além disso, o Teams permite que diferentes serviços e ferramentas sejam incorporados ao ambiente por meio de suas integrações. Isso amplia as possibilidades de utilização da plataforma e permite que organizações adaptem o ambiente às suas necessidades específicas, em vez de depender exclusivamente das funcionalidades básicas de comunicação.

Assim, a apropriação da tecnologia no Teams está relacionada à tentativa de abranger diferentes necessidades do usuário dentro de um mesmo ambiente, oferecendo flexibilidade quanto ao dispositivo utilizado, à forma de comunicação e às ferramentas empregadas. A plataforma busca, dessa maneira, fazer com que o usuário possa incorporar o sistema às suas atividades cotidianas de trabalho ou estudo, utilizando diferentes recursos conforme suas necessidades e contexto de uso.

### 2.2. Ideias e alternativas de design

A avaliação de ideias e alternativas de design compara diferentes soluções segundo critérios relacionados ao uso, como a facilidade de aprendizado e o apoio à recuperação de erros, e à construção, como o custo e o tempo de desenvolvimento (BARBOSA et al., 2021, Seção 11.2). Os critérios de comparação devem partir da análise da situação atual: contexto de uso, objetivos, necessidades e preferências dos usuários.

No projeto, essa meta se aplica ao redesenho das telas do Teams. A partir dos storyboards da Etapa 4, a equipe poderá comparar alternativas para os pontos mais problemáticos levantados nas entrevistas e nas personas, como o local de publicação de atividades e a organização de notificações. Também podem ser comparadas soluções já existentes em outros sistemas de comunicação mencionados pelos entrevistados (Meet, Zoom e Skype), o que equivale à análise competitiva de Nielsen (BARBOSA et al., 2021, Seção 6.3.2). Perguntas que orientam essa meta no projeto:

* Qual das alternativas é a mais eficiente? Qual é a mais fácil de aprender?
* Qual alternativa os usuários preferem, e por quê?
* Qual delas deixa mais evidente o espaço correto para cada tipo de conteúdo?

### 2.3. Conformidade com um padrão

Avaliar a conformidade com um padrão é importante quando a solução precisa ter características definidas por normas, como os padrões de acessibilidade do W3C, os padrões do sistema operacional em que o sistema executa e as convenções do domínio de aplicação (BARBOSA et al., 2021, Seção 11.2). Seguir padrões reduz a dificuldade dos usuários que já estão familiarizados com eles e contribui para a consistência entre as telas.

Para o Teams, três referências de conformidade são relevantes: (1) as diretrizes de acessibilidade WCAG 2.2, já aplicadas ao [Guia de Estilo](guia_estilo.md) por meio dos contrastes mínimos e dos alvos de interação; (2) as convenções do ambiente Windows, sistema usado por todos os entrevistados, como o comportamento de janelas, de fechamento e de teclado; e (3) a terminologia em português já consolidada no domínio de comunicação e colaboração. Essa avaliação não exige a participação de usuários e pode ser feita pela própria equipe durante a verificação dos artefatos. Perguntas que orientam essa meta:

* A interface segue as diretrizes de acessibilidade da WCAG 2.2?
* O comportamento de janelas, menus e teclado segue o padrão do sistema operacional?
* Os termos usados nas telas seguem as convenções do domínio e são os mesmos em todo o sistema?

### 2.4. Problemas na interação e na interface

Problemas na interação e na interface são os aspectos mais avaliados na área de IHC. Eles são identificados a partir de dados de uso e classificados pela gravidade (grau de impacto nocivo), pela frequência com que tendem a ocorrer e pelos fatores de qualidade de uso que prejudicam: usabilidade, experiência do usuário, acessibilidade ou comunicabilidade (BARBOSA et al., 2021, Seção 11.2).

No projeto, os problemas já relatados pelos usuários serão o ponto de partida: para a professora, não saber em qual espaço postar cada conteúdo, a demora no envio de arquivos e as notificações excessivas; para o gestor, a poluição por conversas de canais irrelevantes e a dispersão de arquivos enviados no chat privado; para a estudante entrevistada, a necessidade de rolar o feed do chat para encontrar o vídeo da aula gravada. Na avaliação formativa da Etapa 4, cada problema encontrado será classificado por gravidade, frequência e fator de qualidade de uso prejudicado. Perguntas que orientam essa meta, para cada perfil de usuário:

* O usuário consegue operar o sistema e atingir seu objetivo? Com que eficiência, em quanto tempo e após cometer quantos erros?
* Que parte da interface o deixa insatisfeito ou o desmotiva a explorar novas funcionalidades?
* Ele entende o que significa e para que serve cada elemento da interface?

## 3. Metas de usabilidade do projeto de redesenho

Definir as metas de usabilidade significa escolher os fatores de qualidade de uso que serão priorizados, estabelecer como serão medidos ao longo do processo de design e fixar as faixas de valores inaceitáveis, aceitáveis e ideais para cada indicador (BARBOSA et al., 2021, Seção 6.3.2). Esta seção apresenta essa definição para o redesenho do Teams.

### 3.1. Fatores de usabilidade considerados

A norma ISO 9241-11 define usabilidade como o grau em que um produto é usado por usuários específicos para atingir objetivos específicos com eficácia, eficiência e satisfação em um contexto de uso específico. Nielsen (1994) detalha a usabilidade em cinco fatores, que o livro-base adota (BARBOSA et al., 2021, Seção 3.2.1) e que a Tabela 1 resume.

<p><strong>Tabela 1:</strong> Fatores de usabilidade considerados na seleção das metas</p>

| Fator | Definição segundo a bibliografia |
| :--- | :--- |
| **Facilidade de aprendizado** (*learnability*) | Tempo e esforço necessários para que o usuário aprenda a utilizar o sistema com determinado nível de competência e desempenho |
| **Facilidade de recordação** (*memorability*) | Esforço cognitivo necessário para lembrar como interagir com a interface, conforme aprendido anteriormente |
| **Eficiência** (*efficiency*) | Tempo necessário para concluir uma atividade com apoio computacional, o que determina a produtividade do usuário depois de aprender a usar o sistema |
| **Segurança no uso** (*safety*) | Grau de proteção do sistema contra condições desfavoráveis aos usuários, obtido evitando problemas e ajudando o usuário a se recuperar deles |
| **Satisfação do usuário** (*satisfaction*) | Avaliação subjetiva do efeito do uso do sistema sobre as emoções e os sentimentos do usuário |

<p><em>Fonte: adaptado de Barbosa et al. (2021, p. 35-37).</em></p>

Como a bibliografia alerta, dificilmente um único sistema será muito bom em todos os fatores, pois é difícil articulá-los sem perdas: atalhos de teclado aumentam a eficiência, mas são difíceis de lembrar para usuários ocasionais, e muitos tutoriais facilitam o aprendizado, mas podem desagradar o usuário experiente. Por isso é importante conhecer as necessidades dos usuários e priorizar os fatores (BARBOSA et al., 2021, p. 37). A seleção a seguir segue esse princípio.

### 3.2. Metas selecionadas e justificativa

A equipe selecionou os cinco fatores, com prioridades diferentes, com base nas personas, nas entrevistas e nos cenários de uso do projeto. A Tabela 2 apresenta as metas e a evidência que justifica cada uma.

<p><strong>Tabela 2:</strong> Metas de usabilidade selecionadas e justificativa</p>

| Meta | Prioridade | Justificativa com base nos dados do projeto |
| :--- | :---: | :--- |
| **M1. Facilidade de aprendizado** | Alta | A professora Helena (persona) quer ajudar alunos, inclusive os mais velhos, a usar a plataforma sem dificuldade, e aponta o excesso de ferramentas como barreira para eles. A estudante entrevistada tem nível básico de informática. Segundo Helena, muitos alunos preferem o WhatsApp e o e-mail por considerá-los mais fáceis |
| **M2. Facilidade de recordação** | Média | Helena relata não saber em qual espaço colocar cada coisa. Roberto (gestor) relata dispersão de arquivos enviados no chat privado em vez da aba Arquivos e precisa localizar arquivos antigos e decisões já tomadas. Ambos os casos indicam que a organização do sistema é difícil de lembrar |
| **M3. Eficiência** | Alta | Helena cita a demora no envio de arquivos. No fluxo do estudante, a HTA mostra que o vídeo da aula é encontrado rolando o feed do chat. Marina (funcionária) tem como objetivo central encontrar as pessoas e as informações necessárias para concluir a tarefa. Roberto precisa de busca e rastreabilidade |
| **M4. Segurança no uso** | Média | A dúvida de Helena sobre onde postar cria risco de publicar no lugar errado, e Roberto precisa evitar a perda de avisos críticos. Há também risco de ações como excluir ou enviar a destinatário errado, que o sistema deve prevenir e permitir desfazer |
| **M5. Satisfação do usuário** | Alta | Helena relata ansiedade causada por notificações e pede ambiente limpo. Roberto relata poluição por conversas de canais irrelevantes. A estudante entrevistada afirmou que a poluição visual das equipes, com muitas mensagens, cansa ao longo do semestre |

<p><em>Fonte: Autores (2026), a partir das personas, dos cenários de uso e das entrevistas do projeto.</em></p>

Duas metas complementares da bibliografia de IHC também orientam o redesenho, sem indicadores próprios nesta tabela, porque são tratadas como verificação:

* **Acessibilidade:** remover barreiras que impedem mais pessoas de acessar e usar a interface (BARBOSA et al., 2021, Seção 3.2.3). É verificada pela meta de conformidade com a WCAG 2.2 (Seção 2.3) e pelos requisitos de contraste, tamanho e teclado do Guia de Estilo.
* **Comunicabilidade:** comunicar ao usuário a lógica do design e para que serve cada parte da interface (BARBOSA et al., 2021, Seção 3.2.4). Responde ao pedido da professora por "explicações embutidas" e é verificada pelo indicador I10 da Tabela 4.

### 3.3. Tarefas de referência

Os indicadores são medidos sobre as tarefas já modeladas na análise de tarefas (HTA) do projeto, uma por perfil, para que as metas sejam avaliadas em situações reais de uso.

<p><strong>Tabela 3:</strong> Tarefas de referência para a medição das metas</p>

| Código | Perfil | Tarefa de referência |
| :---: | :--- | :--- |
| **T1** | Estudante | Acessar e assistir à aula gravada de uma disciplina |
| **T2** | Professor | Publicar uma atividade para a turma |
| **T3** | Funcionário | Esclarecer uma dúvida com um colega de outro setor |
| **T4** | Gestor | Estruturar uma equipe de projeto e realizar o alinhamento síncrono |

<p><em>Fonte: Autores (2026), a partir da análise hierárquica de tarefas.</em></p>

### 3.4. Definição operacional: indicadores e faixas de valores

Cada meta é traduzida em indicadores mensuráveis, no formato proposto por Barbosa et al. (2021, Seção 6.3.2): para cada indicador define-se uma faixa **inaceitável**, uma **aceitável** e uma **ideal**. As medições serão feitas por teste de usabilidade, no qual participantes representativos de cada perfil realizam as tarefas de referência e são registrados o sucesso, o número de erros, o tempo e a opinião (BARBOSA et al., 2021, Seção 12.2.1), complementado por questionário pós-teste e entrevista.

<p><strong>Tabela 4:</strong> Indicadores, método de medição e faixas de valores por meta</p>

| ID (meta) | Indicador | Como medir | Inaceitável | Aceitável | Ideal |
| :---: | :--- | :--- | :---: | :---: | :---: |
| **I1** (M1) | Taxa de conclusão da tarefa na primeira tentativa, sem ajuda | Proporção de participantes que concluem T1 a T4 sem intervenção do avaliador | < 60% | 60% a 85% | > 85% |
| **I2** (M1) | Erros por tarefa na primeira sessão de uso | Contagem de erros observados por tarefa e por participante | 3 ou mais | 1 a 2 | 0 |
| **I3** (M1) | Consultas à ajuda ou pedidos de orientação por tarefa | Registro do avaliador e das gravações | 2 ou mais | 1 | 0 |
| **I4** (M2) | Taxa de conclusão ao repetir a tarefa após intervalo, sem ajuda | Participantes repetem a tarefa em nova sessão ou após outras tarefas do roteiro | < 70% | 70% a 90% | > 90% |
| **I5** (M2) | Redução do tempo na segunda execução em relação à primeira | (tempo 1 − tempo 2) ÷ tempo 1, média dos participantes | < 15% | 15% a 30% | > 30% |
| **I6** (M3) | Tempo para concluir a tarefa | Cronometragem por tarefa, comparada com o tempo medido no Teams atual (valor de referência) | Sem redução | Redução de 20% a 40% | Redução > 40% |
| **I7** (M3) | Passos observados em relação ao caminho previsto na HTA | Razão entre passos executados e passos do caminho ideal | > 1,5 | 1,2 a 1,5 | ≤ 1,2 |
| **I8** (M4) | Erros de destino por tarefa (postar, enviar ou excluir no lugar errado) | Contagem em T2 e T4, principalmente | 1 ou mais não recuperado | 1 recuperado | 0 |
| **I9** (M4) | Erros dos quais o participante se recupera sozinho | Proporção de erros corrigidos sem ajuda | < 70% | 70% a 90% | > 90% |
| **I10** (M5 e comunicabilidade) | Participantes que explicam corretamente a função de cada área da tela | Pergunta aberta no pós-teste sobre áreas indicadas pelo avaliador | < 60% | 60% a 85% | > 85% |
| **I11** (M5) | Satisfação geral com o uso | Questionário pós-teste (escala SUS, de 0 a 100) | < 68 | 68 a 80 | > 80 |
| **I12** (M5) | Sensação de controle sobre notificações e de ambiente limpo | Itens do questionário em escala de 5 pontos; média | < 3 | 3 a 4 | > 4 |

<p><em>Fonte: Autores (2026), com formato de faixas de valores baseado em Barbosa et al. (2021, p. 103) e escala SUS de Brooke (1996).</em></p>

**Como ler os valores.** As faixas da Tabela 4 são **hipóteses de trabalho do grupo**, e não valores definidos pela bibliografia. Como o livro-base indica, a priorização costuma partir dos indicadores atuais de desempenho dos usuários. Por isso:

* A equipe medirá o valor **atual** de cada indicador no Teams durante o Teste Piloto da Etapa 4, e as faixas poderão ser recalibradas a partir dele, principalmente I6, definido como redução relativa ao valor atual.
* O valor de 68 pontos na escala SUS é a referência de uso corrente para um sistema de usabilidade média; a faixa ideal acima de 80 é uma meta de projeto.
* Com poucos participantes por perfil, os resultados serão interpretados como tendência e usados para decidir o que corrigir, e não como estatística conclusiva.

### 3.5. Prioridades e possíveis conflitos entre metas

As metas de prioridade alta (M1, M3 e M5) concentram as decisões de projeto, e as de prioridade média (M2 e M4) são verificadas em todas as telas, mas cedem em caso de conflito. Os principais conflitos previstos e a decisão adotada são:

* **Eficiência × aprendizado:** atalhos e recursos avançados não podem aparecer no caminho principal do usuário novato; ficam como aceleradores opcionais.
* **Ambiente limpo × recordação:** reduzir o número de itens na tela pode esconder funções; por isso a navegação mantém rótulos de texto, como definido no Guia de Estilo.
* **Segurança × eficiência:** confirmações constantes retardam o uso; a regra do projeto é preferir **desfazer** a pedir confirmação, reservando o diálogo para ações irreversíveis.

### 3.6. Como as metas serão usadas nas próximas etapas

* O [Guia de Estilo](guia_estilo.md) traduz as metas em regras de interface (por exemplo, base de 16 px e rótulos nos ícones para M1 e M2, desfazer em vez de confirmação para M4, três níveis de notificação para M5).
* Na Etapa 4, o planejamento da avaliação com o framework DECIDE usará os indicadores I1 a I12 para definir as perguntas, as tarefas T1 a T4 e os dados a coletar nos storyboards e no Teste Piloto.
* Os resultados serão comparados com as faixas da Tabela 4 para decidir se o redesenho atinge as metas ou se precisa de nova iteração.


## 4. Referências Bibliográficas

1. BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. **Interação Humano-Computador e Experiência do Usuário**. 1. ed. Rio de Janeiro: Autopublicação, 2021. Seções 3.2, 6.3, 11.2 e 12.2.1.
2. NIELSEN, J. **Usability Engineering**. San Francisco: Morgan Kaufmann, 1994.
3. MAYHEW, D. J. **The Usability Engineering Lifecycle: A Practitioner's Handbook for User Interface Design**. San Francisco: Morgan Kaufmann, 1999.
4. ISO. **ISO 9241-11:2019. Ergonomics of human-system interaction: usability: definitions and concepts**. Genebra, 2019.
5. BROOKE, J. SUS: a "quick and dirty" usability scale. In: JORDAN, P. W. et al. (ed.). **Usability Evaluation in Industry**. London: Taylor & Francis, 1996. p. 189-194.
6. W3C. **Web Content Accessibility Guidelines (WCAG) 2.2**. W3C Recommendation, 2023. Disponível em: <https://www.w3.org/TR/WCAG22/>. Acesso em: 6 out. 2026.

## 5. Histórico de versão

| Versão | Data       | Descrição                                                                                       | Autor(es)   | Revisor(es) |
| ------ | ---------- | ----------------------------------------------------------------------------------------------- | ----------- | ----------- |
| `1.0`  | 05/10/2026 | Criação da página, introdução e apropriação de tecnologia.                                      | Lucas Sales |             |
| `2.0`  | 06/10/2026 | Metas de avaliação restantes; metas de usabilidade selecionadas, indicadores e faixas de valores. | João Paulo  |             |
