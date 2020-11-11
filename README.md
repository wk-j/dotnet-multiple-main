## Main

```bash
dotnet build src/MyApp/MyApp.csproj /t:Rebuild /p:StartupObject=MyApp.Program
dotnet build src/MyApp/MyApp.csproj /t:Rebuild /p:StartupObject=MyApp.A
dotnet build src/MyApp/MyApp.csproj /t:Rebuild /p:StartupObject=MyApp.B

dotnet run --project src/MyApp
```