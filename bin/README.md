# Workshop Spring Boot + JPA

Projeto desenvolvido durante o módulo de **Spring Boot, JPA e Hibernate** do curso de Java do professor **Nélio Alves**.

O objetivo deste projeto foi desenvolver uma **API REST** utilizando Spring Boot, aplicando conceitos de arquitetura em camadas, persistência de dados com **JPA/Hibernate** e tratamento de exceções.

## 🚀 Tecnologias utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- Banco de dados H2
- Postman

## 📌 Funcionalidades

- CRUD de usuários
- CRUD de produtos
- CRUD de categorias
- CRUD de pedidos
- Cadastro de pagamentos
- Associação entre pedidos e produtos
- Tratamento de exceções personalizadas
- API REST

## 🏗️ Modelo de domínio

O projeto é composto pelas seguintes entidades:

- User
- Order
- Product
- Category
- OrderItem
- Payment

Os relacionamentos entre as entidades foram implementados utilizando as anotações do JPA.

## 📁 Estrutura do projeto

```text
src
├── config
├── entities
│   ├── enums
│   └── pk
├── repositories
├── resources
├── services
│   └── exceptions
```

## 💾 Banco de dados

Durante o desenvolvimento foi utilizado o banco de dados em memória **H2**, permitindo testar a aplicação sem a necessidade de configurar um banco de dados externo.

O console do H2 pode ser acessado em:

```
http://localhost:8080/h2-console
```

## ▶️ Como executar

Clone o repositório:

```bash
git clone https://github.com/oMatheussd/workshop-springboot4-jpa.git
```

Entre na pasta do projeto:

```bash
cd workshop-springboot4-jpa
```

Execute a aplicação:

```bash
mvn spring-boot:run
```

A API estará disponível em:

```
http://localhost:8080
```

## 🧪 Testes da API

Os endpoints foram testados utilizando o **Postman**, realizando operações:

- GET
- POST
- PUT
- DELETE

## 📚 Conceitos praticados

- Spring Boot
- Injeção de Dependência
- Arquitetura em Camadas
- Spring Data JPA
- Hibernate
- Relacionamentos entre entidades
- CRUD
- API REST
- Tratamento de Exceções
- Banco de dados H2
- Serialização de objetos JSON

## 👨‍💻 Autor

Desenvolvido por **Matheus Duarte** durante os estudos de Java e Spring Boot.
