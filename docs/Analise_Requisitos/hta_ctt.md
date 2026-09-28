# HTA e CTT

## 1. Análise Hierárquica de Tarefas (HTA)

A HTA representa a decomposição da tarefa de obter um documento didático na aba de arquivos de uma equipe do Microsoft Teams.

### Objetivo principal

**0. Obter documento didático na aba de arquivos de uma equipe no MS Teams**

**Plano 0:** 1 → 2 → 3 → 4

### Decomposição da tarefa

#### 1. Localizar e selecionar a equipe da disciplina

**Plano 1:** 1.1 → 1.2

- **1.1** Clicar no módulo **Equipes** na barra lateral de navegação.
- **1.2** Identificar e clicar na equipe da disciplina desejada.

#### 2. Acessar o canal da turma

**Plano 2:** 2.1 / 2.2 (seleção)

- **2.1** Selecionar o canal padrão **Geral**.
- **2.2** Alternar para um subcanal específico da matéria, caso exista.

#### 3. Navegar até a aba Arquivos

**Plano 3:** 3.1 → 3.2

- **3.1** Clicar na guia **Arquivos** no cabeçalho superior do canal.
- **3.2** Aguardar o carregamento da lista de pastas pelo sistema.

#### 4. Localizar e fazer download do documento

**Plano 4:** 4.1 → 4.2 → 4.3

- **4.1** Navegar entre as pastas de materiais da disciplina.
- **4.2** Selecionar o arquivo de texto/PDF desejado.
- **4.3** Acionar o comando **Baixar** e verificar o salvamento local.

---

## 2. Problemas e recomendações identificados na HTA

| Etapa | Problema identificado | Recomendação |
|---|---|---|
| Obter documento | Poluição de abas dificulta a localização rápida | Criar atalho de **Arquivos Recentes** na tela inicial |
| Selecionar equipe | Muitas turmas sem ícones distintos | Padronizar códigos visuais por disciplina |
| Acessar canal | Incerteza sobre o canal onde o arquivo foi publicado | Disponibilizar link direto para a pasta de arquivos |
| Navegar em Arquivos | Lentidão do SharePoint integrado | Simplificar a lista e melhorar o carregamento |
| Baixar documento | Opção de download escondida no menu de ações | Disponibilizar botão direto de download |

---

# 3. ConcurTaskTrees (CTT)

O CTT representa as tarefas realizadas pelo usuário e pelo sistema, além das relações existentes entre essas tarefas.

## Tipos de tarefas

- **User Task:** atividade realizada exclusivamente pelo usuário.
- **System Task:** processamento realizado automaticamente pelo sistema.
- **Interactive Task:** interação direta entre usuário e interface.
- **Abstract Task:** composição de outras tarefas em direção a um objetivo.

## Árvore de tarefas

### Obter Documento Didático no MS Teams

**Tarefa abstrata**

1. **Decidir qual material baixar** — *User Task*
2. **Selecionar equipe da disciplina** — *Interactive Task*
3. **Acessar diretório de arquivos** — *Abstract Task*
   - Clicar na guia **Arquivos** — *Interactive Task*
   - Processar e renderizar lista de arquivos/pastas — *System Task*
4. **Efetuar download do arquivo** — *Abstract Task*
   - Navegar em pastas — *Interactive Task*
   - Filtrar pelo nome — *Interactive Task*
   - Clicar no comando **Baixar** — *Interactive Task*
   - Transferir arquivo para a pasta local e emitir aviso — *System Task*

## Relações entre tarefas

### Ativação

A seleção da equipe ativa a exibição do canal e permite o acesso à guia **Arquivos**.

### Passagem de informação

A seleção do arquivo fornece ao sistema as informações necessárias para executar o download.

### Independência

O usuário pode rolar a lista de arquivos ou utilizar a caixa de busca para localizar o documento.

### Escolha

O usuário pode escolher entre baixar diretamente o arquivo ou abrir uma pré-visualização no navegador.
## Diagrama CTT

![Diagrama CTT](diagramas/ctt.png)

## Diagrama HTA

![Diagrama HTA](diagramas/hta.png)