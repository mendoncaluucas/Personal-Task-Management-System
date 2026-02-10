# Proposta de Projeto: Sistema de Gerenciamento de Tarefas Pessoais

## 1. Domínio do Problema (Escopo)
O projeto consiste no desenvolvimento de uma aplicação web simplificada para o **gerenciamento de tarefas pessoais**. O objetivo é permitir que um usuário organize seu dia a dia através de um sistema prático de listagem e controle de atividades.

### Funcionalidades Principais:
- **CRUD de Tarefas**: Cadastro, visualização, edição e exclusão de tarefas.
- **Controle de Status**: Funcionalidade para marcar tarefas como "Pendentes" ou "Concluídas".
- **Filtro Simples**: Visualização rápida de tarefas por status.

## 2. Tecnologias Utilizadas e Justificativas
Para garantir a viabilidade do desenvolvimento individual ao longo do semestre, foram escolhidas tecnologias que equilibram poder e simplicidade:

| Tecnologia | Função | Justificativa |
| :--- | :--- | :--- |
| **Java com Spring Boot** | Back-end | Framework robusto que facilita a implementação de **Injeção de Dependência (DI)** e **Inversão de Controle (IoC)**, requisitos centrais da disciplina. |
| **Thymeleaf** | Front-end | Motor de template que permite criar as telas (HTML) integradas ao Java, simplificando a arquitetura ao evitar a necessidade de um framework JavaScript externo. |
| **H2 Database** | Banco de Dados | Banco de dados relacional que roda em memória ou arquivo, ideal para desenvolvimento ágil sem necessidade de instalar servidores de banco de dados complexos. |
| **Maven** | Gestão | Gerenciador de dependências padrão para projetos Java, garantindo organização e facilidade na build. |

## 3. Arquitetura do Projeto
A aplicação seguirá o padrão **MVC (Model-View-Controller)** dentro de uma **Arquitetura Monolítica**. Esta escolha visa reduzir a complexidade de deploy e comunicação, permitindo focar na lógica de negócio e na aplicação dos padrões de projeto solicitados.

---
*Documento elaborado como proposta inicial para a disciplina de Programação WEB.*
