# Restful blog application

## Introduction

This challengue is prepared to test your .NET and architecture skills, we mainly observe the following points:

- Analysis
- Coding best practices
  - OOP
  - Unit Test
  - Multi Layer Architecture
  - Dependency Inversion
  - REST
  - JSON API
- Programming language knowledge and experience.

## Functional Requeriments

- .NET Core
- REST API 
- Multi Layer
- Database
- Unit Test

## Recomendations

- During the test, plan your tasks carefully in order to optimize your time. We recommend completing as many requirements as you can and focus first on the main ones and work on the optional/bonus requirements once you are happy with the implementation you have.
- Make sure you have uploaded your code to github before the test ends.

## The Problem

RESTful Blog App is an application that uses .NET Core to allow its user to create, read, update, and delete (CRUD) various blog posts.

```
@startuml

user --> (Create a Blog)
user --> (Update a Blog)
user --> (Delete a Blog)
user --> (List their Blogs)
user --> (Get a Blog By Id)

@enduml
```


- The part related to the database is free to choose among:
  - In memory database
  - Relational database
  - No relational database
  - Files with text plain or JSON
  - Entity Framework, Dapper, etc.

### Repository

- Fork the project: https://github.com/gaguayo-jala/dotnet-basic-project
- Try to push your commits contanstly.

### How to run the project

```shell
dotnet build
dotnet run --project src\api\BasicProject.Api
```

Use an HTTP client like Postman to `GET` `http://localhost:3003/Health`
