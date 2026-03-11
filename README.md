# API REST em C# (.NET)

## Descrição

Este projeto foi desenvolvido com o objetivo de demonstrar o funcionamento da **arquitetura cliente-servidor** utilizando uma **API REST desenvolvida em C# com .NET**.  

A API disponibiliza dados fictícios de produtos através de **endpoints HTTP**, permitindo que aplicações clientes realizem requisições e recebam respostas em formato **JSON**.

Além da API, o projeto também pode incluir um **cliente em modo console** que consome os dados fornecidos pela API utilizando **HttpClient**, demonstrando na prática a comunicação entre cliente e servidor.

---

# Objetivo

O objetivo deste projeto é compreender e aplicar os seguintes conceitos:

- Arquitetura **Cliente-Servidor**
- Comunicação utilizando o **protocolo HTTP**
- Criação de **APIs REST**
- Consumo de endpoints por aplicações clientes
- Retorno de dados em formato **JSON**

---

# Tecnologias Utilizadas

As principais tecnologias utilizadas neste projeto foram:

- **C#**
- **.NET**
- **ASP.NET Core Web API**
- **Swagger / OpenAPI**
- **HTTP**
- **JSON**

---

# Estrutura do Projeto

### Descrição das Pastas

| Pasta / Arquivo | Descrição |
|---|---|
| Controllers | Contém os endpoints da API |
| Models | Define os modelos de dados utilizados |
| Program.cs | Arquivo principal responsável por iniciar a aplicação |
| ApiProdutos.csproj | Arquivo de configuração do projeto |
| launchSettings.json | Configuração de execução da API |

---

# Como Executar o Projeto

### 1️Clonar ou baixar o projeto


git clone <url-do-repositorio>


### Descrição das Pastas

| Pasta / Arquivo | Descrição |
|----------------|-----------|
| Controllers | Contém os endpoints da API |
| Models | Define os modelos de dados utilizados |
| Program.cs | Arquivo principal responsável por iniciar a aplicação |
| ApiProdutos.csproj | Arquivo de configuração do projeto |
| launchSettings.json | Configuração de execução da API |

---

# Como Executar o Projeto

### 1. Clonar ou baixar o projeto

git clone <url-do-repositorio>

cd ApiProdutos

dotnet run
Now listening on: http://localhost:5143

GET /api/produtos
sendo que ficara http://localhost:5143/api/produtos

| Etapa | Origem | Ação | Destino | Descrição |
|------|--------|------|--------|-----------|
| 1 | Cliente (Console / Aplicação) | Envia requisição HTTP (GET) | Servidor (API .NET) | O cliente solicita dados através de um endpoint da API |
| 2 | Servidor (API .NET) | Processa requisição | API | O servidor recebe a requisição e executa a lógica necessária |
| 3 | Servidor (API .NET) | Retorna resposta em JSON | Cliente | A API envia os dados solicitados no formato JSON |
| 4 | Cliente (Console / Aplicação) | Exibe os dados | Usuário | O cliente recebe os dados e apresenta no console |
Autor

Nome: Victor Santos Barcelos

Curso: Ciências da computação 

Disciplina: Desenvolvimento de sistemas 

Professor: Daniel Linhares Lim Apo
