# 📦 API de Cadastro de Usuários

API REST desenvolvida com **Node.js e Express** para gerenciamento de usuários, com persistência de dados utilizando **MongoDB** e **Prisma ORM**.

O projeto permite cadastrar, consultar, atualizar e remover usuários através de operações CRUD, colocando em prática conceitos fundamentais de desenvolvimento Back-End e integração com banco de dados.

---

## 📸 Preview

![Cadastro de Usuários](https://github.com/msm1996/cadastro-usuarios/raw/main/src/assets/Captura%20de%20tela%202025-10-02%20202622.png?raw=true)

---

## 🚀 Sobre o projeto

A **API de Cadastro de Usuários** foi desenvolvida para praticar a criação de um Back-End utilizando Node.js, Express e banco de dados.

A aplicação disponibiliza endpoints responsáveis pelas operações de cadastro, consulta, atualização e exclusão de usuários.

Os dados são persistidos no **MongoDB**, utilizando o **Prisma ORM** para comunicação com o banco de dados.

Este projeto também contribuiu para minha compreensão de como uma aplicação Front-End se comunica com uma API REST e como os dados são processados e armazenados no Back-End.

---

## ✨ Funcionalidades

- 👤 Cadastro de usuários
- 📋 Listagem de usuários
- ✏️ Atualização de usuários
- 🗑️ Exclusão de usuários
- 💾 Persistência de dados
- 🔄 Operações CRUD
- 🌐 Comunicação através de API REST

---

## 🔗 Endpoints da API

| Método | Rota | Função |
|---|---|---|
| `GET` | `/users` | Lista os usuários |
| `POST` | `/users` | Cadastra um novo usuário |
| `PUT` | `/users/:id` | Atualiza um usuário existente |
| `DELETE` | `/users/:id` | Remove um usuário |

---

## 🛠 Tecnologias utilizadas

- **Node.js** — ambiente de execução JavaScript no Back-End
- **Express.js** — criação da API e gerenciamento das rotas
- **MongoDB** — banco de dados utilizado para persistência
- **Prisma ORM** — comunicação entre a aplicação e o banco de dados
- **CORS** — configuração de acesso à API
- **Body Parser** — processamento dos dados enviados nas requisições

---

## 🧠 O que pratiquei neste projeto

Durante o desenvolvimento deste projeto, pratiquei conceitos importantes de Back-End, como:

- Criação de API REST
- Criação e organização de rotas com Express
- Operações CRUD
- Requisições HTTP
- Integração com banco de dados
- Persistência de dados com MongoDB
- Utilização do Prisma ORM
- Estruturação de uma aplicação Node.js
- Comunicação entre Front-End e Back-End

---

## 💻 Como executar o projeto

Clone o repositório:

```bash
git clone https://github.com/msm1996/cadastro-usuarios.git
```

Entre na pasta:

```bash
cd cadastro-usuarios
```

Instale as dependências:

```bash
npm install
```

Configure a conexão com o banco de dados no arquivo `.env`.

Depois execute:

```bash
npm run dev
```

---

## 👨‍💻 Autor

**Myke Santana Martins**

Desenvolvedor Front-End em formação, com conhecimentos de Back-End para integração de aplicações através de APIs REST.

- GitHub: https://github.com/MykeMartins96
- LinkedIn: https://www.linkedin.com/in/myke-santana-martins


