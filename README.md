# Demonstração de NoSQL Injection com Node.js e MongoDB

Este repositório demonstra como falhas na validação de entradas podem tornar uma API vulnerável a ataques de **NoSQL Injection**. Utilizando Node.js e MongoDB, o projeto simula cenários onde entradas maliciosas podem comprometer a segurança da aplicação.

---

## Objetivo

- Ilustrar como entradas não sanitizadas podem ser exploradas para manipular consultas em bancos NoSQL.
- Educar desenvolvedores sobre práticas inseguras que levam a vulnerabilidades de injeção.
- Demonstrar a importância da validação e sanitização de dados em aplicações que utilizam MongoDB.

---

## O que é NoSQL Injection?

**NoSQL Injection** é uma vulnerabilidade onde um atacante pode interferir nas consultas que uma aplicação faz a um banco de dados NoSQL. Isso pode permitir:

- Bypass de autenticação.
- Acesso ou modificação de dados não autorizados.
- Execução de código malicioso no servidor.
- Causar negação de serviço (DoS).
- [Imperva: What Is NoSQL Injection?](https://www.imperva.com/learn/application-security/nosql-injection/)
- [PortSwigger: NoSQL Injection](https://portswigger.net/web-security/nosql-injection)

---

## Funcionalidades

- **API Simples**: Implementação de uma API com endpoints que interagem com o MongoDB.
- **Cenários Vulneráveis**: Exemplos de rotas onde entradas maliciosas podem ser injetadas.
- **Demonstração de Exploração**: Utilização de ferramentas como `api.http` para simular ataques.
- **Código Comentado**: Explicações no código sobre onde e como as vulnerabilidades ocorrem.

