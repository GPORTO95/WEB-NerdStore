## Projeto E-Commerce - Nerd Store

Projeto Open-Source feito em .NET Core

Foi baseado em um e-commerce de vendas, inicialmente feito apenas para camisetas e canecas.

## Tecnologias implementadas:
- ASP.NET 3.1
- ASP.NET MVC Core
- ASP.NET Identity Core
- Entity Framework Core 3.1
- Fluent Api
- FluentValidator
- AutoMapper
- MediatR

## Arquitetura:
- Arquitetura completa com questões de separação de responsabilidades, SOLID e Clean Code
- Domain Driven Design (Camadas e padrão de modelo de domínio)
- Domain Events
- Domain Notification
- Domain Validations
- CQRS (Consistência Imediata)
- Event Sourcing
- Unit of Work
- Repository
- XUnit para cobertura de testes

## Start
- Ter instalado o [SDK .Net Core 3.1](https://dotnet.microsoft.com/download/dotnet/3.1)
- SSMS (SQL SERVER) - Rodar as migrations para cada contexto
- Instalar [Envent Store](https://developers.eventstore.com/)
- Habilitar o Event Store (Após executar o passo a passo de instalação conforme a documentação)

  1 - Após executar o passo a passo de instalação conforme a documentação
  
  2 - Posicionar o cmd na pasta instalada, provavelmente no seu C:\ESDB ou D:\ESDB(meu caso)
  
  3 - Executar comando EventStore.ClusterNode.exe --config D:\ESDB\eventstore.conf
