# Blazor Starter Application

This project started with a template containing an example [Blazor WebAssembly](https://docs.microsoft.com/aspnet/core/blazor/?view=aspnetcore-3.1#blazor-webassembly) client application, a C# [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview) and a C# class library with shared code.

## Getting Started

I created a repository from the [GitHub template](https://docs.github.com/en/enterprise/2.22/user/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) and cloned it locally to my machine.

I set up hosting on Azure following https://devblogs.microsoft.com/aspnet/azure-static-web-apps-with-blazor/

I opened the solution in [Visual Studio](https://visualstudio.microsoft.com/vs/preview/vs2022/) and followed these steps:

- right click Client in Solution Explorer and click Open in Terminal
- enter dotnet watch run 

This opened the app on my local machine so I could test modifications. 
When the modifications work I commit and push to GitHub which triggers the workflow. 

## Template Structure

- **Client**: The Blazor WebAssembly sample application
- **API**: A C# Azure Functions API, which the Blazor application will call
- **Shared**: A C# class library with a shared data model between the Blazor and Functions application

## Deploy to Azure Static Web Apps

This application was deployed to [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps) following a [quickstart guide](https://aka.ms/blazor-swa/quickstart).

The deployed URL is https://white-hill-0dd1a1310.azurestaticapps.net/

## Updates

IPO code from https://sites.google.com/site/profvanselow/programming/languages/c_1/blazor
To Do list added from tutorial at https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-a-blazor-app
