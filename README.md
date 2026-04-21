Task Management API

API REST desenvolvida com Spring Boot para gerenciamento de tarefas.
Este projeto permite criar, listar, atualizar e deletar tarefas de forma simples e eficiente.

📚 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de:

Praticar Spring Boot
Criar APIs REST
Aplicar arquitetura em camadas
Praticar boas práticas de backend

🚀 Tecnologias Utilizadas
Java 17+
Spring Boot
Spring Data JPA
Hibernate
H2 Database
Maven
REST API

⚙️ Funcionalidades

✅ Criar tarefa
✅ Listar tarefas
✅ Buscar tarefa por ID
✅ Atualizar tarefa
✅ Deletar tarefa

📌 Endpoints da API
Criar tarefa
POST /tasks

Exemplo Body:

{
  "title": "Estudar Spring Boot",
  "description": "Criar API REST",
  "status": "PENDING"
}
Listar todas as tarefas
GET /tasks
Buscar tarefa por ID
GET /tasks/{id}
Atualizar tarefa
PUT /tasks/{id}
Deletar tarefa
DELETE /tasks/{id}
🗄️ Banco de Dados

Este projeto utiliza H2 Database em memória.

Acesse o console H2:

http://localhost:8080/h2-console

Configurações padrão:

JDBC URL: jdbc:h2:mem:testdb
User: sa
Password: (vazio)
