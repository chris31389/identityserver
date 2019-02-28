# Introduction

## Getting Started

1. Install Visual Studio 2017 with .Net Framework 4.7 and ASP.net Core.
1. Make sure that you have LocalDb Installed (Comes as part of Visual Studio 2017 Enterprise)
1. Make sure that a LocalDb instance `IdentityServerDb` exists by running `SqlLocalDB.exe create IdentityServerDb` in command prompt.

### Database Updates

Run this to update the database to the current migration

`dotnet ef database update`

## Running the solution

Run using ISS Express in Visual Studio.

Navigate to: https://localhost:44333/Identity/Account/Login