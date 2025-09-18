# Sql-Interface-2000

Interface gráfica académica, desenvolvida em C#, que permite interagir com uma base de dados relacional. Este projeto foi criado para fins de aprendizagem no âmbito de desenvolvimento de aplicações que realizem operações sobre bases de dados, com interface de utilizador e funcionalidades básicas de gestão.

---

## 🚀 Funcionalidades

- Login / autenticação (formulário de acesso)  
- Menus de navegação para diferentes operações: inserção, consulta, atualização e eliminação de dados (CRUD)  
- Execução de queries SQL a partir da interface gráfica  
- Demonstração de ligação entre aplicação desktop e base de dados (via ADO.NET / SqlClient)  
- Gestão de resultados de query numa interface visual (ex: grid/table ou equivalente)

---

## 🛠️ Tecnologias utilizadas

- Linguagem: **C#**  
- Plataforma: .NET (Desktop Application)  
- Acesso a dados: *Microsoft.Data.SqlClient*  
- Logging / registo de erros: *Microsoft.Extensions.Logging*  
- Ambiente gráfico: Windows Forms (ou equivalente)  
- SQL para scripts de base de dados

---

## 📋 Como usar / Instalar

1. Cria duas bases de dados com os nomes:  
   - `JJJ_International`  
   - `JJJ_International_Workers`

2. Instala os pacotes necessários com o dotnet CLI:

   ```bash
   dotnet add package Microsoft.Extensions.Logging
   dotnet add package Microsoft.Data.SqlClient
