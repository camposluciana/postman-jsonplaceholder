# Postman - JSONPlaceholder API

Coleção de testes de API REST utilizando o Postman, com requisições para a API pública [JSONPlaceholder](https://jsonplaceholder.typicode.com/).

## 🛠️ Tecnologias

- Postman
- JSONPlaceholder API

## 📁 Endpoints Testados

### Posts
- **GET** /posts — lista todos os posts
- **GET** /posts/{id} — busca post por ID
- **GET** /posts?userId={id} — filtra posts por usuário
- **POST** /posts — cria um novo post
- **PATCH** /posts/{id} — atualiza apenas o título
- **DELETE** /posts/{id} — remove um post

### Users
- **GET** /users — lista todos os usuários
- **POST** /users/{id} — busca usuário por ID
- **POST** /users — cria um novo usuário
- **PATCH** /users/{id} — atualiza nome do usuário
- **DELETE** /users/{id} — remove um usuário

## ▶️ Como usar

1. Instale o [Postman](https://www.postman.com/downloads/)
2. Importe o arquivo `JSONPlaceholder API.postman_collection.json`
3. Execute as requisições desejadas