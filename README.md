# MedVoll API

API REST desenvolvida com Java e Spring Boot para gerenciamento de médicos e pacientes da clínica MedVoll.

## Sobre o Projeto

O MedVoll é um sistema para gerenciamento de consultas médicas, permitindo o cadastro e gerenciamento de profissionais da saúde através de uma API REST.

Este projeto foi desenvolvido com foco em boas práticas de desenvolvimento backend utilizando Spring Boot, persistência de dados com JPA/Hibernate e controle de versões de banco de dados com Flyway.

## Tecnologias Utilizadas

* Java 17
* Spring Boot 3
* Spring Data JPA
* Hibernate
* Maven
* MySQL
* Flyway
* Lombok
* JUnit 5

## Arquitetura

O projeto segue uma arquitetura em camadas:

```text
Controller
   ↓
Service
   ↓
Repository
   ↓
Database
```

## Estrutura do Projeto

```text
src
├── main
│   ├── java
│   │   └── med.voll.api
│   │       ├── controller
│   │       ├── domain
│   │       ├── repository
│   │       └── service
│   └── resources
│       ├── application.properties
│       └── db/migration
└── test
```

## Pré-requisitos

Antes de executar o projeto, é necessário ter instalado:

* Java 17 ou superior
* Maven
* MySQL

## Como Executar o Projeto

Clone o repositório:

```bash
git clone https://github.com/AndreaNascimento11/MedVoll.git
```

Acesse a pasta do projeto:

```bash
cd MedVoll
```

Configure o banco de dados no arquivo:

```properties
src/main/resources/application.properties
```

Execute a aplicação:

```bash
mvn spring-boot:run
```

A aplicação será iniciada em:

```text
http://localhost:8080
```

## Banco de Dados

O projeto utiliza MySQL e Flyway para gerenciamento das migrations.

As migrations são executadas automaticamente durante a inicialização da aplicação.

## Testes

Para executar os testes:

```bash
mvn test
```

Para gerar o build da aplicação:

```bash
mvn clean install
```

## Conceitos Aplicados

* Desenvolvimento de APIs REST
* Programação Orientada a Objetos (POO)
* Persistência de dados com JPA/Hibernate
* Controle de versões do banco de dados com Flyway
* Validação de dados
* Injeção de Dependências
* Arquitetura em Camadas
* Testes automatizados

## Aprendizados

Durante o desenvolvimento deste projeto, aprofundei meus conhecimentos em:

* Construção de APIs REST com Spring Boot
* Mapeamento de entidades com JPA/Hibernate
* Gerenciamento de dependências com Maven
* Versionamento de banco de dados utilizando Flyway
* Integração com banco de dados MySQL
* Estruturação de aplicações utilizando arquitetura em camadas
* Escrita e execução de testes automatizados

## Melhorias Futuras

* Implementação de autenticação e autorização com JWT
* Documentação da API com Swagger/OpenAPI
* Dockerização da aplicação
* Implementação de paginação e filtros
* Integração contínua (CI/CD)

## Desenvolvido por

Andrea Nascimento

GitHub: https://github.com/AndreaNascimento11
