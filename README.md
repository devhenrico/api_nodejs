# 📦 API de Cadastro de Usuários

Esta é uma API REST feita com Node.js, Express, Prisma e MongoDB, com validações usando Zod. Ela permite o cadastro, listagem e exclusão de usuários, sendo conectada diretamente a um formulário no [Frontend](https://formuiux.vercel.app/). Sempre que o usuário preenche o formulário, os dados são enviados para a API e salvos automaticamente no banco de dados.

## 🚀 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Prisma](https://www.prisma.io/)
- [MongoDB](https://www.mongodb.com/)
- [Zod](https://zod.dev/) – para validação dos dados

## 🛡️ Validações
A API valida os dados usando o Zod:

firstName e lastName: mínimo 2 caracteres

email: formato válido

password: máximo de 6 caracteres

## 🧑‍💻 Autor
Henrico
