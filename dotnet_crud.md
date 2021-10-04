# Restful blog application

RESTful Blog App is an application that uses .NET Core to allow its user to create, read, update, and delete (CRUD) various blog posts.


### Requeriments

- Implement the CRUD for blogs
  - GET blogs
  - POST blog
  - PUT blog
  - DELETE blog
- For data layer consider implement:
  - Entity Framework Core in-memory or
  - Files encoded (Plain text, JSON, XML, etc).

![Clean Architecture](https://paulovich.net/img/CleanArchitecture-Uncle-Bob.jpg)

Download the project from:

https://github.com/gaguayo-jala/dotnet-basic-project


### How to run the project

```shell
dotnet build
dotnet run --project src\api\BasicProject.Api
```

Use an HTTP client like Postman to `GET` `http://localhost:3003/Health`
