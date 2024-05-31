---
languages:
- csharp
- aspx-csharp
page_type: sample
description: "A sample application you can use to follow along with Tutorial: Deploy an ASP.NET Core and Azure SQL Database app to Azure App Service."
products:
- azure
- aspnet-core
- azure-app-service
---

# .NET Core MVC sample for Azure App Service

This is a sample application that you can use to follow along with the tutorial at 
[Tutorial: Deploy an ASP.NET Core and Azure SQL Database app to Azure App Service](https://learn.microsoft.com/azure/app-service/tutorial-dotnetcore-sqldb-app). 

## Getting started

### Run from Visual Studio

1. git clone https://github.com/gathogojr/msdocs-dotnetcore-sqldb.git
2. cd msdocs-dotnetcore-sqldb
3. Open *DotNetCoreSqlDb.sln* in Visual Studio.
4. Start debugging.

### Run from command line

Run the following commands in a terminal:

```
git clone https://github.com/gathogojr/msdocs-dotnetcore-sqldb.git
cd msdocs-dotnetcore-sqldb
dotnet ef database update
dotnet run
```