# Scaffold - C# version

## Requirements
Install [SDK 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0).

## Run tests
Just run:

```bash
dotnet test
```

## Generation
This project was created with the following commands:

```bash
dotnet new sln --name Scaffold
mkdir src

cd src
dotnet new xunit --name Scaffold
cd ..
dotnet sln ./Scaffold.sln add ./src/Scaffold/Scaffold.csproj
```
