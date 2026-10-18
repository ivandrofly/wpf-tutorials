# WPF Tutorials
Tutorial source code for WPF concepts.

All projects target **.NET 10** (`net10.0-windows`) and use the SDK-style project format.

## Requirements

- Windows
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)

`global.json` pins the 10.0 SDK band, so a newer major SDK installed side by side will not be picked up.

## Build and run

```powershell
dotnet build "WPF Tutorials.sln"
dotnet run --project NavigationMVVM
dotnet test ClassCommands.Tests
```

Each folder in the repository is a standalone demo and can be run with `dotnet run --project <Folder>`.
