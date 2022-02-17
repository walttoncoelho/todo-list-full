# todo-list-full
## Projeto para consolidação de conhecimento

## Começando com vite

Este projeto foi inicializado com $ npm create vite@latest my-vue-app -- --template react

## Scripts Disponíveis

# Pasta Back-end
- Esta é uma aplçicação de fornece uma API que possibilita ler, atualizar, gravar e deletar
### Para esta aplicação foi utilizada o mongoose com node-restfull
Retorna um modelo Mongoose, para que se possa interagir de maneira mais simples e rápida.

## A API registra as seguintes rotas:
* GET /toddos
* GET /todos/:id
* POST /todos
* PUT /todos/:id
* DELETE /todos/:id

### 1- Instalando dependências.
*  Dentro da pasta do projeto exercute.
~~~javascript
npm i
~~~

### 2- Colocando em produção.
~~~javascript
npm run production
~~~


# Pasta Front-end

- Esta é uma aplicação que possibilita o usuário adicionar as suas tarefas, verificar o status, marcar como concluido e deletar as tarefas concluidas

### 1- Instalando dependências.
*  Dentro da pasta do projeto exercute.
~~~javascript
npm i
~~~

### 2- Para startar a aplicação use.
~~~javascript
npm run dev
~~~