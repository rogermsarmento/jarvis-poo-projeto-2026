# 📔 Agenda de Contatos & Calculadora IMC

Este projeto é uma aplicação desktop desenvolvida em **Java** que combina o gerenciamento de uma agenda de contatos (CRUD) com uma ferramenta utilitária para cálculo de Índice de Massa Corporal (IMC). O software foi estruturado aplicando conceitos de Programação Orientada a Objetos (POO) e padrões de arquitetura para organização de código.

---

## 🚀 Funcionalidades

### Gestão de Contatos (CRUD)
* **Cadastrar:** Adição de novos contatos (nome, telefone, e-mail).
* **Listar:** Visualização completa de todos os registros.
* **Pesquisar:** Busca dinâmica por nome ou parte dele.
* **Atualizar:** Edição de dados de contatos existentes.
* **Excluir:** Remoção definitiva de registros.

### Calculadora de IMC
* Cálculo baseado no peso e altura informados.
* Classificação automática de acordo com a tabela da OMS (Abaixo do peso, Peso Ideal, Sobrepeso, etc.).
* Validação de campos para evitar entradas inválidas ou erros matemáticos.

---

## 🛠️ Tecnologias e Arquitetura

* **Linguagem:** Java
* **Interface:** Swing / JavaFX
* **Persistência de Dados:** JDBC (Java Database Connectivity)
* **Banco de Dados:** MySQL / PostgreSQL / SQLite
* **Padrão de Projeto:** DAO (Data Access Object) para isolar a lógica de acesso a dados.

---

## 📋 Documentação de Requisitos

### Requisitos Funcionais (RF)
1. **RF01:** O sistema deve permitir o cadastro, leitura, atualização e exclusão (CRUD) de contatos.
2. **RF02:** O sistema deve calcular o IMC utilizando a fórmula $peso / altura^2$.
3. **RF03:** O sistema deve retornar a classificação de saúde baseada no resultado do IMC.

### Requisitos Não Funcionais (RNF)
1. **RNF01:** A aplicação deve utilizar o padrão de arquitetura DAO.
2. **RNF02:** O sistema deve tratar exceções de entrada de dados (como letras em campos numéricos).
3. **RNF03:** A persistência deve ser feita em banco de dados relacional para garantir a durabilidade dos dados.

---

## 📁 Estrutura do Projeto

```text
src/
 ├── cf/        # Código fonte do projeto.
 ├── desing/    # Mockup e wireframe do projeto.
 ├── UML/       # Driagramas de caso de uso e de classe do projeto.
 └── MBD/       # Modelagem do banco de dados.
