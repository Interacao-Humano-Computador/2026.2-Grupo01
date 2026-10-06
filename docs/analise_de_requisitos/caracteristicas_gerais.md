# Características Gerais

## Tabela de contribuição

| Data       | Contribuição                                                                                                                       | Autor(es)   | Revisor(es) |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------- | ----------- | ----------- |
| 05/10/2026 | Criação da página.                                                                                                                 | Lucas Sales |             |
| 05/10/2026 | Adição de introdução, seção de características gerais, reunião e videoconferencia e chat e mensagens.                              | Lucas Sales |             |
| 06/10/2026 | Adição do contexto de uso, das características físicas e lógicas restantes e do quadro de implicações para o redesenho            | João Paulo  |             |

## 1. Introdução

Os sistemas computacionais são desenvolvidos para apoiar a realização de atividades e objetivos dos usuários, oferecendo recursos que permitem executar tarefas, acessar informações e interagir com diferentes funcionalidades. Para isso, esses sistemas envolvem não apenas aspectos técnicos, mas também elementos relacionados à forma como os usuários compreendem, utilizam e interagem com suas interfaces.

Nesse contexto, um sistema computacional pode ser analisado a partir de diferentes aspectos, como funcionalidades, usuários, tarefas, informações e mecanismos de interação. A maneira como esses elementos são organizados influencia diretamente a experiência do usuário e a facilidade com que as atividades podem ser realizadas.

O Microsoft Teams é uma plataforma de comunicação e colaboração voltada para ambientes de trabalho e educação. A ferramenta reúne, em um mesmo ambiente, recursos de comunicação síncrona e assíncrona, permitindo que os usuários realizem reuniões, troquem mensagens, compartilhem arquivos e organizem atividades em grupos. Dessa forma, o Teams apresenta diferentes possibilidades de interação que podem ser analisadas sob a perspectiva da Interação Humano-Computador.

Esta página faz o mapeamento das características gerais da plataforma em duas dimensões. As **características físicas** (Seção 3) descrevem o contexto de uso: os dispositivos, os ambientes e as condições em que o Teams é utilizado. As **características lógicas** (Seção 4) descrevem o que a plataforma oferece: suas funcionalidades, a organização da informação e as regras de acesso. A Seção 5 resume as implicações dessas características para o redesenho das telas.

## 2. Contexto de uso

A interação entre o usuário e o sistema acontece em um contexto de uso, que abrange o momento da utilização (quando) e o ambiente físico, social e cultural em que a interação ocorre (onde) (BARBOSA et al., 2021, Seção 3.1). Esse contexto afeta o uso do sistema: o usuário pode ser interrompido por uma conversa ou por um telefonema, pode estar sob pressão no trabalho ou pode ter a conexão com a Internet interrompida (BARBOSA et al., 2021, Seção 11.4). Por isso, conhecer o contexto é necessário para avaliar se o sistema é adequado ao ambiente real em que será utilizado.

O contexto do Teams neste projeto vem do perfil de usuários, das personas e das entrevistas:

* **Quem usa:** estudantes, professores, funcionários técnico-administrativos e gestores, em ambiente educacional e de trabalho, incluindo a Administração Pública. Os perfis têm níveis diferentes de familiaridade com tecnologia, de básico a domínio.
* **Dispositivos:** os usuários mapeados utilizam principalmente notebooks e computadores de mesa, com uso eventual de tablet e celular. Um deles trabalha com extensão de tela, e a persona da professora usa computador e tablet. Todos os usuários mapeados utilizam atualmente o sistema operacional Windows.
* **Momento e ritmo de uso:** há usuários que cumprem carga horária fixa, outros que trabalham após o expediente e outros sem carga horária fixa. A professora reserva horários próprios para consultar a plataforma, e há usuários em regime de trabalho remoto.
* **Contexto social:** o Teams é usado tanto para comunicação individual quanto para atividades em grupo, como aulas, reuniões de equipe e alinhamentos de projeto. O uso envolve outras pessoas em tempo real, e os usuários recorrem também a outros canais, como o WhatsApp e o e-mail, para parte da comunicação.

## 3. Características físicas

As características físicas reúnem as propriedades do ambiente e dos dispositivos que condicionam a interação com o Teams. A Tabela 1 as apresenta.

<p><strong>Tabela 1:</strong> Características físicas do uso do Microsoft Teams</p>

| Característica | Descrição | Evidência no projeto |
| :--- | :--- | :--- |
| **Acesso multiplataforma** | O Teams pode ser acessado por computadores, navegadores e dispositivos móveis, o que permite continuar uma atividade ao trocar de dispositivo | Usuários mapeados usam notebook, computador de mesa, tablet e celular |
| **Tamanho e resolução de tela** | A área disponível varia de telas de celular a monitores ampliados com tela adicional, o que exige uma interface que se adapte | Usuário com notebook e extensão de tela; persona com tablet |
| **Dispositivos de entrada** | Teclado e mouse nos computadores, toque em tablets e celulares, e microfone e câmera para reuniões e chamadas | Uso de reuniões e aulas síncronas relatado nas entrevistas e cenários |
| **Dispositivos de saída** | Tela e áudio (alto-falantes ou fones), usados para ver o conteúdo compartilhado e ouvir os participantes | Aulas gravadas e reuniões em tempo real nos cenários de uso |
| **Conexão com a Internet** | O funcionamento depende de conexão. A falha ou a lentidão afetam principalmente reuniões e o envio de arquivos | Demora no envio de arquivos relatada pela professora |
| **Ambiente físico** | Casa, local de trabalho ou sala de aula, com possíveis interrupções, ruídos e outras pessoas por perto | Usuários em regime remoto; trabalho após o expediente |
| **Sistema operacional** | Uso predominante em Windows, o que torna relevantes as convenções de janelas e de teclado desse ambiente | Todos os usuários mapeados usam Windows atualmente |

<p><em>Fonte: Autores (2026), a partir do perfil de usuários, das personas e das entrevistas.</em></p>

## 4. Características lógicas

As características lógicas descrevem as funcionalidades do Teams e a forma como a informação e o acesso são organizados. Segundo a documentação da Microsoft, ao criar uma equipe são criados também componentes do Microsoft 365 que sustentam suas funções, como o grupo da equipe, o site do SharePoint para os arquivos, a caixa de correio e o calendário compartilhados e o bloco de notas (MICROSOFT, s.d.). Essa integração explica por que o Teams reúne conversa, documentos e agenda em um único ambiente. As subseções a seguir descrevem as principais funcionalidades.

### 4.1. Videoconferências e reuniões

O Teams permite a realização de reuniões por videoconferência, possibilitando a comunicação entre diferentes participantes por meio de áudio e vídeo. Durante as reuniões, os usuários também podem utilizar recursos como compartilhamento de tela, apresentação de arquivos, chat e controle de microfone e câmera. Esses recursos permitem que diferentes formas de comunicação sejam utilizadas simultaneamente durante uma atividade.

### 4.2. Chat e mensagens

A plataforma disponibiliza comunicação por meio de conversas individuais ou em grupo. Os usuários podem enviar mensagens de texto, arquivos, imagens e outros conteúdos, além de responder e interagir com mensagens existentes. O recurso de chat permite tanto a comunicação direta entre usuários quanto a continuidade de conversas ao longo do tempo.

### 4.3. Equipes e canais

As equipes agrupam pessoas em torno de um objetivo, como uma disciplina, um projeto ou um setor, e são subdivididas em canais, que organizam as conversas e os arquivos por assunto. A estrutura de equipes e canais é a principal forma de organização da informação no Teams: é nela que o usuário decide em que espaço postar uma mensagem, uma atividade ou um arquivo. No projeto, a professora cria muitas turmas organizadas por setor e relata dúvida sobre onde colocar cada conteúdo, e o gestor cria equipes de projeto e define as regras de acesso a elas.

### 4.4. Arquivos e colaboração em documentos

Os arquivos compartilhados em uma equipe ficam armazenados em serviços do Microsoft 365, como o SharePoint, e podem ser editados em conjunto pelos participantes, com os aplicativos do Office (MICROSOFT, s.d.). O usuário também pode enviar arquivos pelo chat, o que cria dois caminhos para o mesmo tipo de conteúdo. Esse ponto aparece nos dados do projeto: o gestor relata arquivos dispersos por terem sido enviados no chat privado em vez de na aba de arquivos, e a professora relata demora no envio.

### 4.5. Calendário e agendamento

O calendário reúne reuniões e compromissos e é integrado ao agendamento de reuniões da plataforma e ao calendário do Microsoft 365 (MICROSOFT, s.d.). Permite marcar reuniões com os participantes e entrar nelas a partir do próprio calendário. É uma das funções centrais para os perfis de funcionário, professor e gestor, que precisam marcar e participar de reuniões.

### 4.6. Chamadas

Além das reuniões agendadas, o Teams permite chamadas de áudio e vídeo diretas entre usuários. Esse recurso ocupa um destino próprio de navegação na interface atual, ao lado de atividade, chat, equipes e calendário, conforme descrito no [Guia de Estilo](guia_estilo.md).

### 4.7. Atividade e notificações

A plataforma avisa o usuário sobre novidades, como menções, respostas e mensagens em equipes e conversas, por meio de uma área de atividade e de notificações. O usuário pode configurar quais avisos recebe. Esse é um dos pontos de maior atrito nos dados do projeto: a professora relata notificações que a deixam ansiosa e pede poder reduzi-las ou desativá-las, e o gestor relata poluição por conversas paralelas em canais irrelevantes.

### 4.8. Busca

O Teams oferece busca por mensagens, pessoas e arquivos. A busca sustenta a necessidade, relatada pelo gestor, de localizar arquivos antigos e decisões já tomadas, e a necessidade da funcionária de encontrar as pessoas e as informações para concluir suas tarefas.

### 4.9. Aplicativos e integrações

O Teams integra-se a aplicativos do Microsoft 365, como o Word, o Excel, o PowerPoint, o OneDrive e o Outlook, e permite incorporar outros serviços e aplicativos de terceiros, dependendo da gestão de aplicativos da organização (MICROSOFT, s.d.). Essa integração amplia as possibilidades do ambiente, mas aumenta o número de opções na tela, o que se relaciona ao pedido da professora por um ambiente com menos ferramentas.

### 4.10. Contas, funções e permissões

O acesso ao Teams é feito com uma conta institucional, gerenciada pelo serviço de identidade da Microsoft, e a plataforma permite adicionar pessoas externas à organização como convidadas. As equipes têm responsáveis e membros, e há funções de administrador para gerenciar o ambiente (MICROSOFT, s.d.). Essa estrutura de permissões é relevante para o gestor, que precisa configurar o acesso das equipes sem navegar por telas complexas.

## 5. Implicações para o redesenho

A Tabela 2 relaciona as características levantadas às decisões do redesenho, já registradas no [Guia de Estilo](guia_estilo.md) e nas [Metas de Usabilidade](metas_usabilidade.md).

<p><strong>Tabela 2:</strong> Características da plataforma e implicações para o redesenho</p>

| Característica | Implicação para o redesenho |
| :--- | :--- |
| Uso em computador, tablet e celular, com telas de tamanhos diferentes | Grade responsiva em três faixas, áreas que colapsam em ordem de prioridade e alvos de toque de 48 px (Guia de Estilo, Seções 3.5 e 3.6) |
| Usuários com pouca familiaridade tecnológica e uso no Windows | Base de texto de 16 px, rótulos de texto nos ícones de navegação e respeito às convenções de janela e teclado do sistema operacional (Guia de Estilo e Meta de conformidade) |
| Estrutura de equipes e canais como organização principal | Seletor "postar no canal ou conversar" com explicação, e estados vazios que explicam a função de cada espaço (Guia de Estilo, Seção 3.7) |
| Dois caminhos para arquivos (chat e aba de arquivos) | Seletor de destino com explicação (postar no canal ou conversar) e indicador de progresso com cancelamento no envio (Guia de Estilo, Seção 3.7; indicadores I6 a I9 das Metas de Usabilidade) |
| Notificações abundantes | Três níveis de notificação, contador numérico só para menções e acesso direto a "Não perturbe" (Guia de Estilo, Seção 3.7; indicador I12) |
| Busca e rastreabilidade de arquivos e decisões | Busca global em posição fixa na barra superior (Guia de Estilo, Seção 3.6) |
| Integração com muitos aplicativos | Cinco destinos de navegação, com os demais no menu "Mais", para manter o ambiente limpo (Guia de Estilo, Seção 3.6) |
| Contas, funções e permissões | Configurações da equipe em painel lateral e linguagem sem jargão técnico (Guia de Estilo, Seções 3.4 e 3.7) |

<p><em>Fonte: Autores (2026).</em></p>

## 6. Referências Bibliográficas

1. BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. **Interação Humano-Computador e Experiência do Usuário**. 1. ed. Rio de Janeiro: Autopublicação, 2021. Seções 3.1, 7.2 e 11.4.
2. MICROSOFT. **Visão geral do Microsoft Teams**. Microsoft Learn, [s.d.]. Disponível em: <https://learn.microsoft.com/pt-br/microsoftteams/teams-overview>. Acesso em: 6 out. 2026.

## 7. Histórico de versão

| Versão | Data       | Descrição                                                                                              | Autor(es)   | Revisor(es) |
| ------ | ---------- | ------------------------------------------------------------------------------------------------------ | ----------- | ----------- |
| `1.0`  | 05/10/2026 | Criação da página, introdução, videoconferências e chat.                                               | Lucas Sales |             |
| `2.0`  | 06/10/2026 | Contexto de uso, características físicas e lógicas restantes e implicações para o redesenho.           | João Paulo  |             |
