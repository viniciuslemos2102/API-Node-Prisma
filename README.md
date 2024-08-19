# Projeto Node.js - Gerenciamento de Tarefas

Este projeto é uma API simples de gerenciamento de tarefas desenvolvida em Node.js. Ele explora conceitos fundamentais de desenvolvimento backend, como route params, query params, integração com o Prisma e persistência de dados utilizando MongoDB.

## Sumário

- [Instalação](#instalação)
- [Configuração](#configuração)
- [Uso](#uso)
  - [Rota de Criação de Tarefa](#rota-de-criação-de-tarefa)
  - [Rota de Listagem de Tarefas](#rota-de-listagem-de-tarefas)
  - [Rota de Atualização de Tarefa](#rota-de-atualização-de-tarefa)
  - [Rota de Exclusão de Tarefa](#rota-de-exclusão-de-tarefa)
- [Conceitos Utilizados](#conceitos-utilizados)
  - [Route Params](#route-params)
  - [Query Params](#query-params)
  - [Prisma](#prisma)
  - [MongoDB](#mongodb)
- [Licença](#licença)

## Instalação

Para executar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:

   ```bash
   git clone https://github.com/viniciuslemos2102/API-Node-Prisma.git
    
2. Navegue até o diretório do projeto:

   ```bash
   cd API-Node-Prisma
   
3.Instale as dependências:
   ```bash
   npm install
    
```bash
4. Configure as variáveis de ambiente no arquivo .env (veja a seção Configuração para mais detalhes).

Configuração
Este projeto utiliza variáveis de ambiente para configurar a conexão com o banco de dados MongoDB e o Prisma.

Crie um arquivo .env na raiz do projeto e adicione as seguintes variáveis:

Configuração
Este projeto utiliza variáveis de ambiente para configurar a conexão com o banco de dados MongoDB e o Prisma.

Crie um arquivo .env na raiz do projeto e adicione as seguintes variáveis:

env
Copiar código
DATABASE_URL="mongodb+srv://<usuario>:<senha>@cluster0.mongodb.net/myFirstDatabase?retryWrites=true&w=majority"
PORT=3000
Substitua <usuario> e <senha> pelas suas credenciais do MongoDB.
PORT
