# Generate

```bash
dotnet restore
npm install -g generator-jhipster
npm install -g yo
npm install generator-jhipster@7.1.0
npm i -g generator-jhipster-dotnetcore
jhipster --blueprints dotnetcore
change <TargetFramework>net5.0 changes to <TargetFramework>net6.0

NOTE: Delete dotnetcore.csproj and Program.cs files after the generation
```

## Generate jdl:
```bash
jhipster import-jdl app.jdl
```
