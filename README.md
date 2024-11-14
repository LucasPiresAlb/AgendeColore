# AgendeColore

> Foi desenvolvido também o **backend AgendeColore**. Se quiser olhar como ficou [clique aqui](#).

Este front end traz todas as principais funcionalidades de um sistema de agendamento de serviços de pintura, permitindo a interação com uma API REST para gerenciar os compromissos. Este sistema foi feito como trabalho final da disciplina de Desenvolvimento de Plataformas Web.

## ⚙️ Funcionalidades

- **Apresentação da aplicação (Landing Page)**
- **Criação de usuários** (`[POST] /register`)
- **Autenticação de usuários via JWT** (`[POST] /login`)
- **Tela de login** com redirecionamento automático para a dashboard após autenticação
- **Agendamento de serviços** com opções de escolha de datas e serviços
- **Gestão de agendamentos**: visualizar, modificar ou cancelar compromissos

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- **React** com Vite
- **React Router Dom**
- **Bootstrap**
- **Axios**
- **React Query**
- **Sonner** (para notificações toast)

## 🚀 Como executar o projeto

A aplicação consome uma API. Para o funcionamento correto, instale e configure a API primeiro. [Clique aqui para o passo a passo](#).

Clone o projeto e depois de baixado entre na raiz do projeto e execute:

```bash
npm install
Como falado anteriormente, você precisa rodar o backend feito para essa aplicação para o funcionamento correto. Defina um arquivo .env.local na raiz do projeto e copie todas as variáveis do .env.local.example.

makefile
Copiar código
VITE_API_URL="Defina a URL do backend local aqui"
Feito isso, execute o comando na raiz:

bash
Copiar código
npm run dev
Se tudo estiver certo, o front end irá iniciar 🚀.

