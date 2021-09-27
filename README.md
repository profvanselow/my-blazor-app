# Blazor Starter Application

This project started with a template containing an example [Blazor WebAssembly](https://docs.microsoft.com/aspnet/core/blazor/?view=aspnetcore-3.1#blazor-webassembly) client application, a C# [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview) and a C# class library with shared code.

## Getting Started

I created a repository from the [GitHub template](https://docs.github.com/en/enterprise/2.22/user/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) and cloned it locally to my machine.

Once I cloned the project, I opened the solution in [Visual Studio](https://visualstudio.microsoft.com/vs/preview/vs2022/) and followed these steps:

- In the **API** folder, copy `local.settings.example.json` to `local.settings.json`
- Press **F5** to launch both the client application and the Functions API app. In Visual Studio, you can right click the solution and select both API project and client project as startup projects. 

## Template Structure

- **Client**: The Blazor WebAssembly sample application
- **API**: A C# Azure Functions API, which the Blazor application will call
- **Shared**: A C# class library with a shared data model between the Blazor and Functions application

## Deploy to Azure Static Web Apps

This application was deployed to [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps) following a [quickstart guide](https://aka.ms/blazor-swa/quickstart).

The deployed URL is https://white-hill-0dd1a1310.azurestaticapps.net/

## Updates

To Do list added from tutorial at https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-a-blazor-app
