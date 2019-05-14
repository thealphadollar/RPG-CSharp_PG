# Web-CSharp_ASP_PG
A Play-Ground for learning C# and ASP.NET core by building a simple webapp.

### Resource

The tutorial followed for this learning experience is available [here](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-2.2&tabs=visual-studio).

### How to build

I've used Visual Studio Code for the development purposes. To build and run the project, follow the below instructions.

##### Prerequisities

Any OS with the following dependencies installed is good for building the project.

- [.Net Core SDK 2.2](https://www.microsoft.com/net/download/all)
- [C# for Visual Studio](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)

##### Instructions

Use the following instructions in your terminal.

```bash
dotnet dev-certs https --trust
dotnet add package Microsoft.EntityFrameworkCore.SQLite
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
dotnet ef database update
```

After the above steps, open the MvcMovie folder in VS Code and press Ctrl + F5.

NOTE: Use the original tutorial to understand the working of each command or if you face any issue.
