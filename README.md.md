# API Aluno Online - Avaliação de Backend

API RESTful desenvolvida como parte da avaliação de backend, com o objetivo de gerenciar os dados de alunos.

## 📜 Sobre o Projeto

O projeto consiste em uma API com três endpoints principais para operações de CRUD (Criar e Ler) de alunos. A aplicação foi construída utilizando Java com Spring Boot e se conecta a um banco de dados PostgreSQL provisionado na nuvem da AWS através do serviço RDS.

---

## 🚀 Tecnologias Utilizadas

* **Java 17**
* **Spring Boot 3**
* **Spring Data JPA / Hibernate**
* **Maven** para gerenciamento de dependências
* **PostgreSQL** como banco de dados
* **AWS RDS** para a hospedagem do banco de dados na nuvem
* **Insomnia** para testes e consumo da API
* **DBeaver** para administração do banco de dados

---

## Endpoints da API

A seguir estão os tipos de requisições que documentam o funcionamento dos endpoints e a persistência dos dados.

### 1. Criar Aluno (`POST /alunos`)

Endpoint responsável por receber os dados de um novo aluno em formato JSON e salvá-lo no banco de dados.

### 2. Buscar Todos os Alunos (`GET /alunos`)

Endpoint que retorna uma lista com todos os alunos cadastrados no banco de dados.

### 3. Buscar Aluno por ID (`GET /alunos/{id}`)

Endpoint que retorna os dados de um aluno específico a partir do seu ID.

### 4. Prova da Persistência no Banco de Dados (DBeaver)

Print do DBeaver mostrando os dados inseridos através da API, confirmando que foram salvos com sucesso no banco de dados PostgreSQL na AWS.
