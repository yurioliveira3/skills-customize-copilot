# 📘 Tarefa: Construindo APIs REST com o framework FastAPI

## 🎯 Objetivo

Criar uma API REST simples usando o framework FastAPI em Python. Os alunos aprenderão a definir endpoints, lidar com requisições HTTP e implementar funcionalidades básicas de uma API.

## 📝 Tarefas

### 🛠️ Instalar FastAPI e criar um endpoint básico

#### Descrição
Instale o FastAPI e o Uvicorn, crie um servidor básico e defina um endpoint GET simples que retorna uma mensagem de boas-vindas.

#### Requisitos
O programa concluído deve:

- Ter o FastAPI instalado
- Definir um endpoint GET em "/"
- Retornar uma mensagem JSON como {"message": "Bem-vindo à API FastAPI!"}
- Ser executável com `uvicorn main:app --reload`

### 🛠️ Adicionar endpoints para operações CRUD

#### Descrição
Adicione endpoints para criar, ler, atualizar e deletar itens em uma lista simples (por exemplo, uma lista de tarefas).

#### Requisitos
O programa concluído deve:

- Ter um endpoint POST para criar um novo item
- Ter um endpoint GET para listar todos os itens
- Ter um endpoint PUT para atualizar um item existente
- Ter um endpoint DELETE para remover um item
- Usar uma estrutura de dados simples (lista ou dicionário) para armazenar os dados

### 🛠️ Implementar validação de dados

#### Descrição
Use os recursos de validação do Pydantic no FastAPI para validar os dados de entrada nos endpoints.

#### Requisitos
O programa concluído deve:

- Definir modelos Pydantic para os dados
- Validar automaticamente os dados de entrada
- Retornar erros apropriados para dados inválidos
- Incluir pelo menos um campo obrigatório e um opcional