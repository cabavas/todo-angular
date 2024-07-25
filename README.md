# Team Todo App

![Logo](link-para-logo.png)

## Visão Geral

**Team Todo App** é uma aplicação simples desenvolvida em Angular que permite a gestão de tarefas de um time. Cada membro do time pode adicionar suas tarefas, marcá-las como completas e visualizar as tarefas de outros membros. As tarefas são salvas no `localStorage` do navegador, garantindo que não sejam perdidas ao recarregar a página.

## Funcionalidades

- Adicionar novas tarefas para qualquer membro do time.
- Marcar tarefas como concluídas.
- Visualizar todas as tarefas e suas respectivas atribuições.
- Salvar as tarefas no `localStorage` do navegador.

## Tecnologias Utilizadas

- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap (para estilização)

## Como Executar o Projeto

### Pré-requisitos

- Node.js (v14 ou superior)
- Angular CLI

### Passo a Passo
1. Clone o repositório:
```
   git clone https://github.com/seu-usuario/team-todo-app.git
   cd team-todo-app
```
2. Instale as dependências:
```
  npm install
```
3. Execute o servidor de desenvolvimento:
```
    ng serve
```
Abra o navegador e acesse http://localhost:4200.

Estrutura do Projeto
```
    src/app: Contém os componentes, serviços e modelos do Angular.

    src/assets: Arquivos estáticos como imagens e estilos globais.

    src/environments: Configurações de ambiente.
```
Prints da Aplicação
Página Inicial

Adicionando uma Nova Tarefa

Tarefas Concluídas

Contribuição

    - Faça um fork do projeto.
    - Crie uma nova branch para sua funcionalidade (git checkout -b feature/nova-funcionalidade).
    - Commit suas alterações (git commit -m 'Adiciona nova funcionalidade').
    - Faça um push para a branch (git push origin feature/nova-funcionalidade).
    - Abra um Pull Request.
