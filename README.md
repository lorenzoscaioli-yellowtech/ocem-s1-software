# Runway Lighting Advisor

Piccola applicazione dimostrativa in C#/.NET: suggerisce il gradino di luminosità di ogni circuito
di una pista in base alla visibilità. Dominio e dati sono inventati.

## Struttura

```
RunwayLighting.sln
src/RunwayLighting.Core/    logica di dominio (regole in docs/requisiti.md)
src/RunwayLighting.Web/     interfaccia Blazor Server
tests/RunwayLighting.Tests/ test xUnit
docs/requisiti.md           requisiti funzionali
```

Accessibile in

```
http://localhost:5113
```

## Requisiti

.NET SDK 8 oppure 10: il progetto si compila per la versione installata (`Directory.Build.props`).
La solution si apre in Visual Studio 2022 (17.8+) o Visual Studio 2026, oppure in VS Code con
l'estensione C# Dev Kit. Per sapere quale SDK c'è: `dotnet --list-sdks`.

## Comandi

```bash
dotnet build
dotnet test
dotnet run --project src/RunwayLighting.Web
```
