# BlazorApp
Experimenting with [Blazor WebAssembly RC](https://devblogs.microsoft.com/aspnet/blazor-webassembly-3-2-0-release-candidate-now-available/)

![.NET Core](https://github.com/laurentkempe/BlazorApp/workflows/.NET%20Core/badge.svg)

## Visual Studio Code

![Visual Studio Code Learn more](https://pbs.twimg.com/media/EW6rb6KXQAcZ1Qy?format=jpg&name=medium)


For sure you need the C# extension, but I guess you already have it, then you need [JavaScript Debugger (Nightly)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-debug-nightly) - [Learn more](https://docs.microsoft.com/en-us/aspnet/core/blazor/debug?tabs=visual-studio-code&view=aspnetcore-3.1#vscode
) and enable it in Visual Code settings of the extension:

![Enable JavaScript Debugger (Nightly)](https://pbs.twimg.com/media/EW6sUsrXsAAeTT9?format=jpg&name=large)

To hit a break point, you need to launch the app with the two launcher created " .NET Core Launch (Blazor Standalone)" then ".NET Core Debug Blazor Web Assembly in Chrome"

![breakpoint](https://pbs.twimg.com/media/EW6wkrsXQAAcow9?format=jpg&name=large)

## Build using Github Actions

See the configuration [build.yml](https://github.com/laurentkempe/BlazorApp/blob/master/.github/workflows/build.yml). It is the default configuration provided by Github, just modify the .NET Core Version to 3.1.201!

It works!

![Github Actions build](https://pbs.twimg.com/media/EW6z2RhXYAAgH84?format=jpg&name=large)