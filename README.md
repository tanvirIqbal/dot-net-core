# dot-net-core

My first .Net Core app.

## Basic Commands

### Check fot dot net

dotnet --version  
dotnet --info

### Create a console application

dotnet new console -o CsharpHelloWorld  
cd CsharpHelloWorld  
dotnet run  

dotnet add package Humanizer  

dotnet ef migrations add AddItems  
dotnet ef migrations list  
dotnet ef database update  

dotnet ef database update NameOfTheMigrationYouWantToRollBack  
dotnet ef database drop  

### Create an ASP.NET Core project

dotnet new mvc --auth Individual -o AspNetCoreTodo  
cd AspNetCoreTodo  
dotnet run  
Now listening on: <http://localhost:5000>  
Application started. Press Ctrl+C to shut down.  