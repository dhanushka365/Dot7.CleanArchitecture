#Creating the Solution
- dotnet new sln -n Dot7.CleanArchitecture

#Creating the Domain Layer
- dotnet new classlib -o Dot7.CleanArchitecture.Domain

#Creating the Application Layer
- dotnet new classlib -o Dot7.CleanArchitecture.Application

#Creating the Infrastructure Layer
- dotnet new classlib -o Dot7.CleanArchitecture.Infrastructure

#Creating the API Layer
- dotnet new classlib -o Dot7.CleanArchitecture.Api

#Add all the projects into solution
- dotnet sln Dot7.CleanArchitecture.sln add(ls -r **/*.csproj)
