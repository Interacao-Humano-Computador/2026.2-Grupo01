# Persona e Caso de Uso

## 1. Persona

### João — Estudante Universitário

**Nome:** João  
**Idade:** 25 anos  
**Ocupação:** Estudante de Bacharelado e Licenciatura em Matemática na Universidade de Brasília (UnB).  
**Status:** Persona primária.

### Frase marcante

> "Procurar coisas específicas no Teams se torna complexo porque a plataforma é lotada de opções. Se eu pudesse, tiraria dois terços das funcionalidades para deixar apenas o essencial: canais, vídeo e chat."

### Objetivos

- Acessar materiais didáticos das disciplinas na aba **Arquivos**.
- Baixar artigos e textos disponibilizados pelos professores.
- Participar de reuniões síncronas por vídeo.

### Habilidades e conhecimento

- Ensino superior incompleto.
- Conhecimento tecnológico avançado.
- Experiência com programação, LaTeX e montagem/desmontagem de hardware.

### Tarefas e rotina

- Utiliza o Microsoft Teams semanalmente.
- Utiliza principalmente computador desktop/notebook.
- Também utiliza smartphone.
- Acessa equipes das disciplinas, arquivos e chamadas de vídeo.

### Principais dificuldades

- Interface considerada poluída pelo excesso de funcionalidades.
- Dificuldade para localizar arquivos e aulas gravadas.
- Notificações consideradas invasivas.
- Dificuldade para encontrar links de chamadas.
- Alguns professores também apresentam dificuldades técnicas com o Teams.

### Expectativas

O usuário espera uma plataforma mais direta e focada, com menos funcionalidades desnecessárias, facilidade para acessar materiais e maior clareza para participar de chamadas.

---

## 2. Caso de Uso

### UC01 — Acessar e Baixar Material Didático da Disciplina no MS Teams

**Ator:** João — Estudante Universitário.

**Objetivo:**  
Localizar e fazer o download de um artigo ou texto disponibilizado pelo professor para estudo.

**Contexto de uso:**  
Acesso semanal ao Microsoft Teams por computador ou notebook, em ambiente de estudo.

### Pré-condições

1. João deve estar autenticado com sua conta institucional da UnB no Microsoft Teams.
2. O professor deve ter criado a equipe da disciplina e adicionado o aluno.
3. O professor deve ter disponibilizado previamente o documento.

### Fluxo principal

1. João abre o Microsoft Teams e clica no ícone **Equipes** no menu lateral.
2. O sistema exibe o painel de equipes.
3. João seleciona a equipe da disciplina.
4. João acessa o canal **Geral** da disciplina.
5. O sistema exibe o conteúdo do canal e suas guias.
6. João clica na guia **Arquivos**.
7. O sistema carrega a lista de pastas e documentos compartilhados.
8. João localiza o arquivo desejado e clica em **Baixar**.
9. O sistema realiza o download e exibe uma confirmação.

### Fluxos alternativos e exceções

**Exceção 1 — Excesso de abas e complexidade:**  
Caso João não encontre o arquivo devido ao excesso de opções da interface, ele pode utilizar a busca interna ou navegar por outros canais.

**Exceção 2 — Dificuldade do professor:**  
Caso o professor tenha dificuldades para gerenciar os arquivos no Teams, João pode entrar em contato diretamente por e-mail institucional.

**Exceção 3 — Entrada em chamada:**  
Caso o link de uma reunião não esteja claro, João pode aguardar o início da chamada no feed do canal para utilizar a opção de ingresso.

### Pós-condição

O material didático é baixado e armazenado localmente no computador do estudante.