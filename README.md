# DotNetCoreAndVueCli

This is meant to be a demo for using .NET Core 2.1 and Vue Cli in a SPA template provided from the project [here][project]. Fork this project to use as a good baseline for demo-ing a project using the "new stack", or for getting a headstart on a Vue/.NET Core project.

[project]: https://github.com/ow-en/ASPCoreVueCLITemplate

To build the project from soup to nuts (including installing the `dotnet` template that the project is based off of), view the project link above.

## To Build:

- Clone down the repo
- In the cloned directory, navigate to ~\DotNetCoreAndVueCli\VueCLICore\clientapp and run `npm install`.
- You can now run the project from either IIS in Visual Studio or with `npm run serve` in the same directory.

_These build instructions are subject to change as more dependencies are added or removed from the project._

**Important note regarding Hot Module Reloading in IIS: make sure to disable SSL in the `Properties` section of the root project in Visual Studio.**

Check the `npm package.json` in the `appclient` directory for all lumped in dependencies. Currently the `.nuget` is wide open, so there isn't anything special going on in the C# side except for Entity Framework Core.



