# API RESTful com Node.js, Express, MongoDB e Docker

Esta é uma API RESTful simples construída com Node.js, Express, e MongoDB, e containerizada usando Docker. A API permite a realização de operações CRUD (Criar, Ler, Atualizar, Deletar) para um recurso de usuário.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript.
- **Express**: Framework para Node.js que facilita a construção de APIs.
- **MongoDB**: Banco de dados NoSQL.
- **Mongoose**: Biblioteca para modelagem de dados MongoDB.
- **Docker**: Plataforma para criação e gerenciamento de contêineres.

## Configuração

### Pré-requisitos

- [Docker](https://www.docker.com/products/docker-desktop) e [Docker Compose](https://docs.docker.com/compose/install/) instalados.
- [Node.js](https://nodejs.org/) e [npm](https://www.npmjs.com/) instalados (opcional, apenas para desenvolvimento).

### Passos para Executar

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/usuario/nome-do-repositorio.git
   cd nome-do-repositorio


2. **Configuração do Ambiente**

    Crie um arquivo .env na raiz do projeto com os valores das variaveis de ambiente

3. **Construir e Executar os Contêineres**

    docker-compose up --build

