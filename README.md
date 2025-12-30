---

# Modelo de Domínio e ORM

Projeto **Spring Boot** para gestão de eventos acadêmicos, com foco em **modelagem de domínio**, **JPA/Hibernate** e **seeding de banco de dados**.

---

## 🛠 Tecnologias

* Java 21
* Spring Boot 4.0.1
* Spring Data JPA / Hibernate
* H2 Database

---

## 📊 Modelo de Domínio

O sistema gerencia **atividades**, **categorias**, **blocos de horários** e **participantes**.

### Relacionamentos

* Categoria ↔ Atividade: Many-to-One
* Atividade ↔ Bloco: One-to-Many
* Atividade ↔ Participante: Many-to-Many

---

## 🚀 Como Executar

1. Execute a aplicação.
2. Acesse o H2 Console:

   ```
   http://localhost:8080/h2-console
   ```
3. Os dados iniciais são carregados automaticamente via `import.sql`.

---
