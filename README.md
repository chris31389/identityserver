# Introduction

## Getting Started

1. Install Visual Studio 2017 with .Net Framework 4.7 and ASP.net Core.
1. Make sure that you have LocalDb Installed (Comes as part of Visual Studio 2017 Enterprise)
1. Make sure that a LocalDb instance `IdentityServerDb` exists by running `SqlLocalDB.exe create IdentityServerDb` in command prompt.

### Database Updates

To generate a new migration using powershell, you can run the following commands replacing `$root` and `$migrationName` with ones applicable to you.

``` Powershell
$root = "D:\Draycir.Approvals" #This should be replaced to suit your setup
$migrationName = "MyMigration" #This should be replaced 
cd "$root\src\Draycir.Approvals.Persistence.EntityFramework"
dotnet ef migrations add $migrationName -s "..\Draycir.Approvals.Persistence.EntityFramework.ConsoleApp\"
```
