# API RESTful com Java Spring Boot

Este projeto é uma **API RESTful** desenvolvida em **Java** utilizando o **Spring Boot**, com persistência de dados em **PostgreSQL** e testes realizados via **Postman**.

O projeto foi construído seguindo o tutorial do vídeo:  
🎥 [Criando uma API REST com Spring Boot - Michelli Brito](https://www.youtube.com/watch?v=wlYvA2b1BWI&t=2701s)

## 🔧 Tecnologias utilizadas

- Java 17+
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Postman
- Maven

## 📌 Funcionalidades implementadas

- [x] Cadastro de produtos (`POST /products`)
- [x] Listagem de todos os produtos (`GET /products`)
- [x] Busca de produto por ID (`GET /products/{id}`)
- [x] Atualização de produto (`PUT /products/{id}`)
- [x] Remoção de produto (`DELETE /products/{id}`)

## 💾 Banco de Dados

A API está conectada a um banco de dados **PostgreSQL**.  
As configurações de acesso estão no arquivo `application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/seu_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
