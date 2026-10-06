## Tabela de contribuição

| Data       | Contribuição                                                                                                  | Autor(es)     | Revisor(es) |
| ---------- | ------------------------------------------------------------------------------------------------------------- | ------------- | ----------- |
| 05/10/2026 | Criação da página.                                                                                            | Lucas Sales   |             |
| 05/10/2026 | Adição das seções introdução, layout e organização espacial, tipografia, símbolos e ícones (estilo atual do Teams) | Lucas Sales   |             |
| 06/10/2026 | Elaboração do guia visual unificado para o redesenho: tipografia, janelas, cores, grids, layout e padrões     | João Paulo    |             |

## 1. Introdução

Guias de estilo são utilizados para registrar e organizar princípios, padrões e decisões de design que orientam a construção de uma interface. Em sistemas de grande escala, eles contribuem para manter a consistência entre diferentes telas e funcionalidades, facilitando tanto a compreensão da interface pelos usuários quanto o trabalho das equipes responsáveis pelo desenvolvimento e manutenção do sistema. Na Engenharia de Usabilidade de Mayhew (1999), adotada pelo grupo como processo de design, o guia de estilo é o artefato que transforma as decisões de projeto em regras verificáveis, de modo que todas as telas redesenhadas sigam o mesmo vocabulário visual e de interação.

Esta página tem duas partes. A Seção 2 registra os padrões observáveis na interface atual do Microsoft Teams, que servem de ponto de partida. A Seção 3 apresenta o **guia visual unificado do redesenho**, com as regras de tipografia, janelas, cores, grids, layout e padrões que serão aplicadas aos storyboards e protótipos da Etapa 4. As decisões da Seção 3 respondem aos requisitos e às frustrações levantados nas entrevistas, no grupo de foco, nas personas e nos cenários de uso do projeto; a Tabela 6 mostra essa rastreabilidade.

Todos os valores numéricos (tamanhos, espaçamentos, cores) são **propostas de projeto do grupo**, a serem validadas na avaliação formativa da Etapa 4. Eles não reproduzem as especificações oficiais da Microsoft.

## 2. Estilo atual observado no Microsoft Teams

No caso do Microsoft Teams, é possível observar a aplicação de diferentes padrões de design ao longo da plataforma. Esses padrões contribuem para manter uma identidade visual consistente e estabelecer formas semelhantes de interação entre funcionalidades distintas.

### 2.1. Layout e organização espacial

A interface do Teams utiliza uma organização espacial baseada na divisão das funcionalidades em áreas distintas. A navegação principal concentra o acesso a recursos como atividades, chat, equipes, calendário e chamadas, enquanto a área central é utilizada para apresentar o conteúdo selecionado.

Essa organização permite que o usuário mantenha uma referência espacial durante a navegação, identificando onde estão as principais categorias de funcionalidades. A utilização de estruturas semelhantes entre diferentes áreas também contribui para a consistência da interface.

### 2.2. Tipografia

A tipografia é utilizada para estabelecer uma hierarquia visual entre diferentes tipos de informação. Títulos, nomes de equipes e canais, mensagens, descrições e informações secundárias apresentam diferentes níveis de destaque, permitindo que o usuário identifique rapidamente a importância relativa de cada elemento.

A utilização consistente de tamanhos, pesos e estilos tipográficos também contribui para a organização das informações apresentadas nas telas.

### 2.3. Símbolos e ícones

O Teams utiliza ícones para representar diversas funcionalidades, como chat, calendário, chamadas, arquivos, configurações e outras ações. Esses elementos reduzem a necessidade de utilizar textos extensos para identificar determinadas funções e permitem que ações recorrentes sejam reconhecidas visualmente.

## 3. Guia visual unificado para o redesenho

### 3.1. Princípios que orientam o guia

Quatro diretrizes, derivadas das personas e dos cenários, orientam todas as decisões das seções seguintes:

1. **Ambiente limpo:** menos áreas e menos ferramentas visíveis ao mesmo tempo (Helena, a professora, pede "menos ferramentas e espaços na tela").
2. **Lugar certo para cada coisa:** o usuário deve saber, sem adivinhar, onde postar, conversar ou procurar (frustração central de Helena e de Roberto, o gestor).
3. **Atenção sob controle do usuário:** destaque visual é reservado ao que exige ação; notificações são graduadas e configuráveis (Helena e Roberto).
4. **Legível por todos:** o guia assume usuários com pouca familiaridade tecnológica e contextos variados de uso (notebook, tablet, celular), com contraste e alvos de toque generosos.

### 3.2. Tipografia

**Família.** Texto de interface em *Segoe UI Variable*, com alternativas na ordem da pilha abaixo, para que a aparência seja consistente em Windows (sistema usado por todos os entrevistados), macOS, Android e navegadores. Trechos de código ou identificadores usam *Consolas*.

```css
font-family: "Segoe UI Variable", "Segoe UI", system-ui, -apple-system,
             Roboto, "Helvetica Neue", Arial, sans-serif;
```

**Escala.** Base de **16 px** (e não 14 px), por causa de usuários com menos familiaridade com tecnologia e de leitura prolongada em mensagens. Os tamanhos são definidos em `rem`, para que o usuário possa ampliar o texto em até 200% sem perda de conteúdo ou de função.

<p><strong>Tabela 1:</strong> Escala tipográfica do redesenho</p>

| Estilo | Tamanho / entrelinha | Peso | Uso |
| :--- | :---: | :---: | :--- |
| Título de tela | 24 / 32 px | 600 | Nome da tela ou da equipe aberta (um por tela) |
| Título de seção | 18 / 24 px | 600 | Cabeçalhos de painéis, diálogos e grupos de lista |
| Corpo | 16 / 24 px | 400 | Mensagens, descrições, campos de formulário |
| Corpo em destaque | 16 / 24 px | 600 | Nome de remetente, item não lido, rótulos de campo |
| Secundário | 14 / 20 px | 400 | Pré-visualização de mensagem, texto de ajuda, horários |
| Legenda | 12 / 16 px | 400 | Metadados curtos (hora de envio, contadores). Nunca para informação essencial |
| Botão | 16 / 24 px | 600 | Rótulo de botões e abas |

<p><em>Fonte: Autores (2026).</em></p>

**Regras de uso**

- Apenas dois pesos (400 e 600); a hierarquia vem de tamanho e peso, não de variações de cor.
- Capitalização de frase (*Criar equipe*), sem texto todo em maiúsculas, que prejudica a leitura.
- Alinhamento à esquerda; sem texto justificado.
- Largura de linha de texto corrido entre 60 e 80 caracteres.
- Texto truncado com reticências deve ter o conteúdo completo disponível por foco ou toque (ex.: nome longo de canal).
- Links e ações de texto são sublinhados ou acompanhados de ícone, nunca diferenciados só pela cor.

### 3.3. Cores

**Paleta.** Uma cor de marca (índigo) usada com parcimônia, neutros levemente frios para as superfícies e quatro cores semânticas. A cor de marca aparece apenas na ação principal da tela, no item selecionado e no foco; isso mantém o ambiente limpo e faz o botão principal se destacar.

<p><strong>Tabela 2:</strong> Cores do tema claro e razão de contraste (WCAG 2.2)</p>

| Papel | Cor | Hex | Contraste | Uso |
| :--- | :---: | :---: | :---: | :--- |
| Marca / ação primária | <span style="display:inline-block;width:2.2em;height:1.2em;background:#4B4EA8;border:1px solid #767690;vertical-align:middle"></span> | `#4B4EA8` | 7,11:1 com branco | Botão primário, item selecionado, links, anel de foco |
| Fundo da aplicação | <span style="display:inline-block;width:2.2em;height:1.2em;background:#F5F5FA;border:1px solid #767690;vertical-align:middle"></span> | `#F5F5FA` | — | Fundo geral e painéis laterais |
| Superfície | <span style="display:inline-block;width:2.2em;height:1.2em;background:#FFFFFF;border:1px solid #767690;vertical-align:middle"></span> | `#FFFFFF` | — | Área de conteúdo, cartões, diálogos |
| Texto principal | <span style="display:inline-block;width:2.2em;height:1.2em;background:#1F1F2E;border:1px solid #767690;vertical-align:middle"></span> | `#1F1F2E` | 16,23:1 sobre branco | Corpo e títulos |
| Texto secundário | <span style="display:inline-block;width:2.2em;height:1.2em;background:#5C5C70;border:1px solid #767690;vertical-align:middle"></span> | `#5C5C70` | 6,52:1 sobre branco; 6,00:1 sobre o fundo | Pré-visualizações, horários, textos de ajuda |
| Fundo de seleção | <span style="display:inline-block;width:2.2em;height:1.2em;background:#EEEEF9;border:1px solid #767690;vertical-align:middle"></span> | `#EEEEF9` | 6,17:1 com a cor de marca | Item selecionado em listas e na navegação |
| Borda de controles | <span style="display:inline-block;width:2.2em;height:1.2em;background:#767690;border:1px solid #767690;vertical-align:middle"></span> | `#767690` | 4,41:1 sobre branco | Contorno de campos e botões secundários |
| Divisor decorativo | <span style="display:inline-block;width:2.2em;height:1.2em;background:#D0D0DE;border:1px solid #767690;vertical-align:middle"></span> | `#D0D0DE` | decorativo | Linhas entre seções, sem função informativa |
| Sucesso | <span style="display:inline-block;width:2.2em;height:1.2em;background:#2E7D32;border:1px solid #767690;vertical-align:middle"></span> | `#2E7D32` | 5,13:1 com branco | Envio concluído, presença disponível |
| Erro / destrutivo | <span style="display:inline-block;width:2.2em;height:1.2em;background:#B3261E;border:1px solid #767690;vertical-align:middle"></span> | `#B3261E` | 6,54:1 com branco | Mensagens de erro, ações irreversíveis |
| Alerta | <span style="display:inline-block;width:2.2em;height:1.2em;background:#8A5A00;border:1px solid #767690;vertical-align:middle"></span> | `#8A5A00` | 5,93:1 com branco | Avisos que pedem atenção |
| Informação | <span style="display:inline-block;width:2.2em;height:1.2em;background:#0B63B5;border:1px solid #767690;vertical-align:middle"></span> | `#0B63B5` | 6,06:1 com branco | Dicas e explicações embutidas |

<p><em>Fonte: Autores (2026). Contrastes calculados pela fórmula de luminância relativa da WCAG 2.2.</em></p>

**Tema escuro.** O redesenho prevê tema escuro, acompanhando a preferência do sistema operacional, com o fundo `#1B1B26`, a superfície `#262633`, o texto principal `#E6E6F5` (13,81:1), o texto secundário `#B4B4C8` (8,37:1) e a marca `#A9ACF5` (8,05:1 sobre o fundo). As cores semânticas ficam mais claras para manter o contraste: sucesso `#7BD88F` (9,79:1), erro `#FF8A80` (7,47:1) e alerta `#FFC857` (11,09:1).

**Regras de uso**

- Contraste mínimo de 4,5:1 para texto e de 3:1 para ícones e bordas de controles (WCAG 2.2, critérios 1.4.3 e 1.4.11).
- **A cor nunca é o único canal de informação:** erro, sucesso e alerta sempre combinam cor, ícone e texto; item não lido combina peso 600 e indicador, não só cor.
- Um único botão com preenchimento da cor de marca por tela ou diálogo.
- O vermelho é exclusivo de erro e de ações destrutivas, para manter seu significado.
- O anel de foco por teclado tem 2 px na cor de marca, com 2 px de afastamento, e é sempre visível.

### 3.4. Janelas

Chamamos de janelas as áreas sobrepostas ou destacadas do conteúdo principal. Cada tipo tem uma função única, para que o usuário saiba o que esperar ao abri-la.

<p><strong>Tabela 3:</strong> Tipos de janela do redesenho</p>

| Tipo | Dimensão proposta | Quando usar | Comportamento |
| :--- | :--- | :--- | :--- |
| Janela principal | Tela inteira | Estrutura da aplicação (Seção 3.6) | Única e sempre presente |
| Painel lateral | 360 px, à direita | Detalhes sem perder o contexto: informações da equipe, arquivos de uma conversa, participantes de uma reunião | Não bloqueia a tela; fecha com botão ou `Esc`; recolhido por padrão em telas médias |
| Diálogo modal | 480 px de largura máxima | Decisão que exige resposta antes de continuar: criar equipe, confirmar exclusão | Bloqueia o fundo; `Esc` cancela; foco preso dentro do diálogo e devolvido ao elemento de origem ao fechar |
| Menu e popover | Conforme o conteúdo | Ações secundárias de um item, seletores, ajuda contextual | Fecha ao clicar fora ou com `Esc`; nunca contém formulário longo |
| Aviso temporário (toast) | Inferior esquerdo, 360 px | Confirmação de ação concluída ("Arquivo enviado") | Some após 6 s, com opção de **Desfazer**; erros não somem sozinhos |
| Janela de reunião | Tela inteira ou flutuante | Chamadas e videoconferências | Controles de microfone, câmera e saída sempre visíveis, com rótulo de texto |

<p><em>Fonte: Autores (2026).</em></p>

**Regras de uso**

- No máximo **um diálogo modal por vez**; diálogos não abrem outros diálogos.
- O título do diálogo é uma ação ou pergunta (*Criar equipe*, *Excluir o canal "Projeto"?*); o botão de confirmação repete o verbo (*Criar*, *Excluir*), nunca "OK" ou "Sim".
- Botões do diálogo alinhados à direita: o primário por último; o cancelamento sempre disponível.
- Ações destrutivas nomeiam o que será perdido e usam o botão vermelho; sempre que possível, oferecem **Desfazer** em vez de confirmação prévia, para não interromper o fluxo.
- Toda janela é operável por teclado e anunciada a leitores de tela (`role="dialog"`, `aria-modal`, `aria-live` nos avisos).
- Fundo atrás de um modal escurecido em 40%, com o conteúdo de trás inacessível.

### 3.5. Grids

**Espaçamento.** Todos os espaçamentos e dimensões usam múltiplos de **4 px**, com a escala 4 · 8 · 12 · 16 · 24 · 32 · 48 px. Elementos relacionados ficam mais próximos entre si do que de elementos não relacionados (proximidade).

**Grade de conteúdo.** Áreas de conteúdo (páginas de equipe, calendário, arquivos) seguem uma grade de colunas com margem e calha proporcionais à largura da tela.

<p><strong>Tabela 4:</strong> Grade e pontos de quebra</p>

| Faixa | Largura | Colunas | Margem | Calha | Navegação |
| :--- | :---: | :---: | :---: | :---: | :--- |
| Compacta (celular) | < 600 px | 4 | 16 px | 16 px | Barra inferior com rótulos |
| Média (tablet) | 600 a 1023 px | 8 | 24 px | 24 px | Barra lateral estreita; painel lateral sobrepõe o conteúdo |
| Expandida (computador) | ≥ 1024 px | 12 | 32 px | 24 px | Barra lateral; painel lateral ao lado do conteúdo |

<p><em>Fonte: Autores (2026).</em></p>

**Alvos de interação.** Altura de controles de 40 px no computador e de 48 px em telas de toque, com 8 px livres entre alvos adjacentes (acima do mínimo de 24 px do critério 2.5.8 da WCAG 2.2). A largura máxima do conteúdo é de 1440 px; acima disso, as margens crescem.

### 3.6. Layout

A estrutura geral reduz a navegação principal a cinco destinos, sempre com **ícone e rótulo de texto**, e mantém uma posição fixa para cada tipo de conteúdo. O destino *Chamadas* e os aplicativos adicionais ficam no menu **Mais**, o que reduz o número de opções permanentes na tela; essa escolha será conferida na avaliação da Etapa 4, já que chamadas são um recurso de uso frequente.

<p><strong>Figura 1:</strong> Esquema do layout padrão em tela expandida (≥ 1024 px)</p>

<div style="font-family:system-ui,sans-serif;font-size:0.8rem;max-width:760px;margin:0 auto;border:2px solid #767690;border-radius:6px;overflow:hidden">
  <div style="background:#4B4EA8;color:#fff;padding:0.5rem 0.8rem;display:flex;justify-content:space-between"><span><b>Barra superior</b> · 56 px</span><span>Busca global (largura máx. 640 px) · Perfil</span></div>
  <div style="display:flex;min-height:230px">
    <div style="width:20%;min-width:6.5rem;background:#EEEEF9;color:#1F1F2E;padding:0.5rem;border-right:1px solid #767690"><b>Navegação</b><br>72 px<br><br>Atividade<br>Conversas<br>Equipes<br>Calendário<br>Arquivos<br>Mais</div>
    <div style="width:22%;background:#F5F5FA;color:#1F1F2E;padding:0.5rem;border-right:1px solid #767690"><b>Lista</b><br>320 px<br><br>Conversas ou canais da seção escolhida</div>
    <div style="flex:1;background:#FFFFFF;color:#1F1F2E;padding:0.5rem;border-right:1px solid #767690"><b>Conteúdo</b><br>largura flexível<br><br>Mensagens, página da equipe, calendário<br><br><i>Campo de escrita fixo na base</i></div>
    <div style="width:20%;background:#F5F5FA;color:#1F1F2E;padding:0.5rem"><b>Painel lateral</b><br>360 px, opcional<br><br>Detalhes, arquivos, participantes</div>
  </div>
</div>

<p><em>Fonte: Autores (2026).</em></p>

A Figura 1 resume o esquema; as regras de layout são:

- **Posições fixas:** navegação à esquerda, lista ao lado, conteúdo ao centro, detalhes à direita; nenhuma dessas áreas muda de lugar entre as seções, o que preserva a referência espacial já presente no Teams (Seção 2.1).
- **Barra superior com busca global em posição fixa**, para atender à necessidade de localizar arquivos antigos e decisões passadas (Roberto, o gestor).
- **Um objetivo por tela:** cada tela tem um título (Tabela 1) e uma única ação primária visível, na parte superior direita do conteúdo ou no campo de escrita.
- **Em telas médias e compactas**, as áreas colapsam em sequência (primeiro o painel lateral, depois a lista), nunca o conteúdo; o usuário volta pela seta de retorno no cabeçalho.
- **Densidade de informação:** o conteúdo principal ocupa a maior área; informações de apoio ficam no painel lateral, aberto sob demanda.
- **Estados vazios explicam o espaço:** uma lista vazia mostra uma frase sobre para que serve aquela área e a ação principal (ver Seção 3.7).

### 3.7. Padrões

Os padrões abaixo definem componentes e comportamentos recorrentes, para que a mesma tarefa seja sempre feita da mesma forma.

<p><strong>Tabela 5:</strong> Padrões de componentes</p>

| Padrão | Especificação |
| :--- | :--- |
| **Botões** | Quatro variações: *primário* (preenchido na cor de marca; um por tela), *secundário* (contorno `#767690`), *terciário* (apenas texto, para ações de baixa prioridade) e *destrutivo* (vermelho). Sempre com rótulo de verbo; botão só com ícone exige dica de texto e nome acessível |
| **Campos de formulário** | Rótulo sempre visível acima do campo (nunca só o texto de exemplo); texto de ajuda abaixo, em tamanho secundário; erro em linha com ícone, texto e cor vermelha, dizendo o que corrigir; campos obrigatórios identificados por texto ("obrigatório") |
| **Itens de lista (conversas e canais)** | Avatar ou ícone à esquerda, nome em peso 600 se houver item não lido, pré-visualização em texto secundário truncado em uma linha, horário à direita; selecionado com o fundo `#EEEEF9` e barra de 3 px na cor de marca |
| **Composição de mensagem** | Fixa na base do conteúdo, com área de texto que cresce até 6 linhas; anexar e enviar à direita, ambos com rótulo acessível; envio por `Enter`, nova linha por `Shift+Enter` |
| **Postar em canal vs. conversar** | Ao iniciar uma nova mensagem em uma equipe, o seletor mostra duas opções com uma frase de explicação cada ("Publicar no canal: todos da equipe veem" e "Conversar em particular: só as pessoas escolhidas veem"), evitando a dúvida de onde colocar cada coisa |
| **Comunicado importante** | Cartão com faixa lateral na cor de alerta, ícone, título e a marca "Importante", fixado no topo do canal até ser dispensado; é o único elemento permitido a competir com o conteúdo por atenção |
| **Notificações** | Três níveis configuráveis por equipe e canal: *Tudo*, *Só menções e respostas* (padrão) e *Silenciar*. Contador numérico apenas para menções e mensagens diretas; as demais atividades usam apenas o peso 600 no item, sem contador. Há acesso direto a "Não perturbe" e a horários de silêncio |
| **Ícones** | Estilo de contorno, 24 px (20 px dentro de botões compactos), traço de 1,5 px, um único conjunto em todo o sistema; na navegação, sempre com rótulo de texto; ícones isolados têm dica ao focar ou pairar e nome para leitor de tela |
| **Explicações embutidas** | Estados vazios e primeiros usos mostram uma frase sobre a função do espaço (ícone de informação na cor informativa); podem ser dispensados e reabertos pelo ícone de ajuda do cabeçalho |
| **Feedback de ações** | Toda ação mostra resposta em até 1 s: indicador de progresso para envios de arquivo (com porcentagem e opção de cancelar), toast de confirmação ao concluir, mensagem de erro com a causa e a próxima ação possível |
| **Linguagem** | Português do Brasil, verbos no infinitivo para ações, sem jargão técnico, siglas ou termos em inglês sem tradução ("Equipe", não "Team"; "Anúncio", não "Announcement"); o mesmo termo para o mesmo conceito em todas as telas |
| **Teclado e acessibilidade** | Todas as funções operáveis por teclado, com ordem de foco igual à ordem visual; atalhos documentados e nunca obrigatórios; descrições textuais e legendas para conteúdo de áudio e vídeo |

<p><em>Fonte: Autores (2026).</em></p>

### 3.8. Rastreabilidade: do requisito à decisão do guia

A Tabela 6 liga os principais requisitos e frustrações levantados nas personas às decisões deste guia. Ela serve de roteiro para a avaliação formativa da Etapa 4: cada linha indica o que verificar com os usuários.

<p><strong>Tabela 6:</strong> Requisitos das personas e decisões do guia de estilo</p>

| Persona | Requisito ou frustração | Decisão do guia |
| :--- | :--- | :--- |
| Helena (professora) | "Ambiente limpo: menos ferramentas e espaços na tela" | Cinco destinos de navegação, cor de marca restrita à ação principal, painel lateral sob demanda (3.3 e 3.6) |
| Helena (professora) | Não saber em qual espaço colocar cada coisa | Seletor "Postar em canal vs. conversar" com explicação; título único por tela (3.6 e 3.7) |
| Helena (professora) | "Explicações embutidas: indicar para que serve cada espaço" | Estados vazios e ajuda contextual (3.6 e 3.7) |
| Helena (professora) | Notificações que causam ansiedade; poder reduzi-las | Três níveis de notificação, contador só para menções, "Não perturbe" (3.7) |
| Helena (professora) | Envio lento de arquivos | Indicador de progresso com porcentagem e cancelamento (3.7) |
| Roberto (gestor) | Poluição por notificações de canais irrelevantes | Padrão "Só menções e respostas", silenciar por canal (3.7) |
| Roberto (gestor) | Avisos críticos perdidos | Cartão de comunicado importante fixado no topo (3.7) |
| Roberto (gestor) | Busca e rastreabilidade de arquivos e decisões | Busca global em posição fixa na barra superior (3.6) |
| Roberto (gestor) | Menus claros para permissões, sem telas complexas | Painel lateral para configurações da equipe, linguagem sem jargão (3.4 e 3.7) |
| Marina (funcionária) | Encontrar rapidamente pessoas e informações para concluir tarefas | Busca global, posições fixas das áreas, itens de lista com identificação clara (3.6 e 3.7) |
| Todas | Uso em computador, tablet e celular; usuários com menos familiaridade | Grade responsiva, base de 16 px, alvos de toque de 48 px, contraste mínimo de 4,5:1 (3.2, 3.3 e 3.5) |

<p><em>Fonte: Autores (2026), a partir das personas do projeto.</em></p>

## 4. Declaração de uso de Inteligência Artificial Generativa

Em atenção às diretrizes da Sociedade Brasileira de Computação (SBC), informa-se que uma ferramenta de IA generativa foi utilizada como apoio na estruturação desta página, na redação das tabelas e no cálculo das razões de contraste. As decisões de projeto devem ser revisadas e validadas pelos integrantes do grupo, que mantêm a responsabilidade integral pelo conteúdo.

## 5. Referências Bibliográficas

1. MAYHEW, D. J. **The Usability Engineering Lifecycle: A Practitioner's Handbook for User Interface Design**. San Francisco: Morgan Kaufmann, 1999.
2. BARBOSA, S. D. J.; SILVA, B. S. da. **Interação Humano-Computador**. Rio de Janeiro: Elsevier / Campus, 2010.
3. BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. **Interação Humano-Computador e Experiência do Usuário**. 1. ed. Autopublicação, 2021.
4. W3C. **Web Content Accessibility Guidelines (WCAG) 2.2**. W3C Recommendation, 2023. Disponível em: <https://www.w3.org/TR/WCAG22/>. Acesso em: 6 out. 2026.
5. NIELSEN, J. **10 Usability Heuristics for User Interface Design**. Nielsen Norman Group, 1994. Disponível em: <https://www.nngroup.com/articles/ten-usability-heuristics/>. Acesso em: 6 out. 2026.

## 6. Histórico de versão

| Versão | Data       | Descrição                                                                                       | Autor(es)   | Revisor(es) |
| ------ | ---------- | ----------------------------------------------------------------------------------------------- | ----------- | ----------- |
| `1.0`  | 05/10/2026 | Criação da página.                                                                              | Lucas Sales |             |
| `2.0`  | 06/10/2026 | Guia visual unificado do redesenho: tipografia, janelas, cores, grids, layout e padrões.        | João Paulo  |             |
