### docker init ASP.NET sample

This demonstrates the current result of `docker init` for a sample ASP.NET project (https://github.com/dotnet/dotnet-docker/tree/main/samples/aspnetapp).
This repo is unlikely to be updated long-term.

The output of running `docker init` in this repo looked like this (but with some colors):

```
$ docker init

Welcome to the Docker Init CLI!

This utility will walk you through creating the following files with sensible defaults for your project:
  - .dockerignore
  - Dockerfile
  - compose.yaml

Let's get started!

? What application platform does your project use? ASP.NET
default: "aspnetapp"
? What's the name of your solution's main project? aspnetapp
? What version of .NET do you want to use? 7.0
? What local port do you want to use to access your server? 8080

CREATED: .dockerignore
CREATED: Dockerfile
CREATED: compose.yaml
CREATED: README.Docker.md

✔ Your Docker files are ready!

Take a moment to review them and tailor them to your application.

When you're ready, start your application by running: docker compose up --build

Your application will be available at http://localhost:8080

Consult README.Docker.md for more information about using the generated files.
```
