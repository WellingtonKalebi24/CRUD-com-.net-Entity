comando iniciar o projeto:
### dotnet new webapi 
### dotnet new webapi --use-controllers -n NomeDoSeuProjeto

startar o projeto
### dotnet watch run

adicionar o swagger
### dotnet add package Swashbuckle.AspNetCore

adicionar OpenApi
### Install-Package Microsoft.AspNetCore.OpenApi


dar comando do ef, só precisa dar uma vez a cada computador
### dotnet tool install --global dotnet-ef


instalar o package para o projeto
### dotnet add package Microsoft.EntityFrameworkCore.Design
### dotnet add package Microsoft.EntityFrameworkCore.BancoDeDadosQueEstaTrabalhando


Entities: classe no programa e uma tabela no DB


Criar migrations
### dotnet-ef migrations add CriacaoTabelaContato

Executar migrations
### dotnet-ef database update


---> http://localhost:5232/swagger/index.html