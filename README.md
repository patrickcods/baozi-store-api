# 🥟 Baozi Store - API REST

API REST desenvolvida para o gerenciamento básico de clientes, produtos e pedidos da **Baozi Store**, uma loja especializada em pães chineses artesanais. 

Projeto desenvolvido como Atividade Prática da disciplina de **Desenvolvimento Web Back-End**.

---

## 🚀 Tecnologias Utilizadas

- **Linguagem:** Java 17+
- **Framework:** Spring Boot 3.x
- **Persistência de Dados:** Spring Data JPA / Hibernate
- **Banco de Dados:** MySQL
- **Gerenciador de Dependências:** Apache Maven
- **Testes de API:** Postman

---

## 🏛️ Arquitetura do Projeto

O projeto foi construído seguindo o padrão arquitetural **MVC (Model-View-Controller)** e a divisão em pacotes exigida:

```text
src/main/java/com/example/demo/
├── controller/       # Camada de Controladores REST
├── model/            # Entidades JPA
└── repository/       # Interfaces Spring Data JPA
