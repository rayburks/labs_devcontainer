
# DevContainer with .net 8

# Use Aspire

## Install aspire

To work with .NET Aspire, you'll need the following installed locally:

- .NET 8.0
- .NET Aspire workload
- Docker Desktop
- Visual Studio Code

```dotnetcli
dotnet nuget list source
dotnet workload update
dotnet workload install aspire
dotnet workload list

```