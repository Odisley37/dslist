# dslist

## Projeto Java API - Lista de Filmes

Este projeto é uma API RESTful básica para gerenciamento de uma lista de filmes, desenvolvida com Java e o framework Spring Boot. A aplicação tem como objetivo demonstrar a criação de uma API simples utilizando as melhores práticas de desenvolvimento com Spring.

## Descrição

O projeto é uma aplicação de cadastro e listagem de filmes, onde é possível realizar operações de criação, leitura, atualização e exclusão (CRUD) dos filmes. A arquitetura do projeto segue uma estrutura de camadas, facilitando a manutenção e escalabilidade.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação utilizada.
- **Spring Boot**: Framework principal para a construção da API.
- **Spring Data JPA**: Para acesso e manipulação dos dados no banco de dados.
- **H2 Database**: Banco de dados em memória para testes.
- **Maven**: Gerenciador de dependências e construção do projeto.

## Estrutura do Projeto

A arquitetura do projeto está dividida em diferentes camadas:

1. **Controller**: Camada responsável por expor os endpoints da API.
2. **Service**: Camada de serviço que contém a lógica de negócios.
3. **Repository**: Camada de acesso a dados, utilizando Spring Data JPA.
4. **Model**: Representação do objeto de filme e demais entidades.

## Funcionalidades

- **GET /movies**: Retorna a lista de todos os filmes cadastrados.
- **GET /movies/{id}**: Retorna um filme específico pelo ID.
- **POST /movies**: Cria um novo filme.
- **PUT /movies/{id}**: Atualiza as informações de um filme.
- **DELETE /movies/{id}**: Deleta um filme.

## Como Rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Odisley37/dslist.git
