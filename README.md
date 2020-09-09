# BobsStoreSNL
Student Demo Project based on Adam Freeman's Book PRO ASP.NET Core 3 8th Edition

## Create Solution and Project

dotnet new globaljson --sdk-version 3.1.101 --output BobsStoreSln/OutdoorProducts
dotnet new web --no-https --output BobsStoreSln/OutdoorProducts --framework netcoreapp3.1
dotnet new sln -o BobsStoreSln
dotnet sln BobsStoreSln add BobsStoreSln/OutdoorProducts 
dotnet new xunit -o BobsStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1
dotnet sln BobsStoreSln add BobsStoreSln/OutdoorProducts.Tests 
dotnet add BobsStoreSln/OutdoorProducts.Tests reference BobsStoreSln/OutdoorProducts
