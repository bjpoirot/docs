[home](../ReadMe.md)


# Entity Framework Core #

<https://docs.microsoft.com/en-us/ef/core/index>


## Entity Framework Core - Migrations ##

Gebruik de command line tool om Migrations in EF Core te regelen

<https://docs.microsoft.com/en-us/ef/core/miscellaneous/cli/dotnet>

Let op! omdat context in apart class lib zit moet je de optie -s gebruiken!

dotnet ef migrations add InitialMigration -s ../Poirot.LIMS.WebApi/ -c LIMSContext
dotnet ef database update -s ../Poirot.LIMS.WebApi/ -c LIMSContext

## Entity Framework Core - Scaffolding existing DB ##

Gebruik de command line tool om Scaffolding in EF Core te regelen

<https://docs.microsoft.com/en-us/ef/core/cli/dotnet#dotnet-ef-dbcontext-scaffold>