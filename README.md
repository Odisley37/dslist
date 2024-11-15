# dslist ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white) ![Spring](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring&logoColor=white)

## Projeto Java API - Lista de Filmes 🎬

Este projeto é uma API RESTful simples para gerenciar uma lista de filmes, utilizando **Java** e o framework **Spring Boot**. O objetivo é demonstrar a criação de uma API básica que realiza operações CRUD em uma lista de filmes.

---

## 📋 Descrição

A aplicação permite cadastrar, listar, atualizar e deletar filmes. A estrutura do projeto é baseada em uma arquitetura de camadas, com camadas distintas para serviços, controladores e repositórios.

### 🔧 Tecnologias Utilizadas

- **Java**: Linguagem de programação.
- **Spring Boot**: Framework para construção da API.
- **Spring Data JPA**: Para manipulação do banco de dados.
- **H2 Database**: Banco de dados em memória para testes rápidos.
- **Maven**: Gerenciador de dependências.

### 🛠 Estrutura do Projeto

O projeto é dividido nas seguintes camadas:

- **Controller**: Responsável por expor os endpoints da API.
- **Service**: Contém a lógica de negócios.
- **Repository**: Acesso aos dados com Spring Data JPA.
- **Model**: Representação dos objetos e entidades.

---

## ⚙️ Funcionalidades

- **GET /movies**: Retorna todos os filmes cadastrados.
- **GET /movies/{id}**: Retorna um filme específico pelo ID.
- **POST /movies**: Cria um novo filme.
- **PUT /movies/{id}**: Atualiza um filme existente.
- **DELETE /movies/{id}**: Deleta um filme.

---

## 🚀 Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/Odisley37/dslist.git
   ```
----

## 🤝 Contribuição

Contribuições são bem-vindas! Se você encontrou algum bug ou tem sugestões de melhorias, sinta-se à vontade para abrir uma issue ou submeter um pull request.

##📄 Licença

Este projeto está licenciado sob a MIT License.


## 🤩 Agradecimentos

Obrigado por conferir este projeto! 🚀
   

