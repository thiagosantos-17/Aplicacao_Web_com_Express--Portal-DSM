# Atividade: Aplicação Web com Express - Portal DSM

Este projeto é uma aplicação web multipágina desenvolvida como atividade prática para o curso de **Desenvolvimento de Software Multiplataforma (DSM)**. A aplicação utiliza **Node.js** com o framework **Express** para gerenciar rotas e servir arquivos estáticos.

## 🚀 Tecnologias Utilizadas

* **Backend:** Node.js.
* **Framework:** Express.
* **Variáveis de Ambiente:** Dotenv.
* **Frontend:** HTML5 e CSS3.
* **Fontes:** Roboto (Google Fonts).

## 📋 Funcionalidades e Rotas

O servidor Express (`server.js`) está configurado para responder às seguintes rotas:

* **Página Inicial (`/`):** Apresenta informações detalhadas sobre o curso de DSM, seus objetivos e grade curricular.
* **Login (`/login`):** Interface de autenticação para usuários cadastrados.
* **Cadastro (`/cadastro`):** Formulário para criação de novas contas.
* **Página de Erro (404):** Exibida automaticamente quando o usuário tenta acessar uma rota inexistente.

## 📂 Estrutura de Arquivos

Com base na implementação, o projeto organiza-se da seguinte forma:

* `server.js`: Configuração do servidor, middlewares de arquivos estáticos e definição de rotas.
* `public/assets/css/main.css`: Folha de estilo centralizada que utiliza Flexbox para o layout dos cards e botões.
* `public/pages/`: Contém os arquivos HTML (`index.html`, `login.html`, `cadastro.html`, `404.html`).

## 🛠️ Como Executar

1. Acesse em: `...`.

---
*Projeto desenvolvido para fins acadêmicos - Fatec / Centro Paula Souza.*
