# BobbyStoreSNL
Student Demo Project based on Adam Freeman's Book PRO ASP.NET Core 3 8th Edition

## Create Solution and Project

dotnet new globaljson --sdk-version 3.1.101 --output BobsStoreSln/OutdoorProducts
dotnet new web --no-https --output BobsStoreSln/OutdoorProducts --framework netcoreapp3.1
dotnet new sln -o BobsStoreSln
dotnet sln BobsStoreSln add BobsStoreSln/OutdoorProducts 
dotnet new xunit -o BobsStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1
dotnet sln BobsStoreSln add BobsStoreSln/OutdoorProducts.Tests 
dotnet add BobsStoreSln/OutdoorProducts.Tests reference BobsStoreSln/OutdoorProducts

Link: https://www.apress.com/gp/book/9781484254394.


## Incorporating the cart feature
![Progress](Step2.PNG)
![Buttons](SportsStore_Navigation.PNG)
![CartPage](SportsStore_Navigation2.PNG)
![AddToCart](SportsStore_Navigation3.PNG)
![Tests](SportsStore_Navigation4.PNG)

## Completing Cart
![CompletingCart](SportsStore_CompletingtheCart.PNG)
![CompletingCart2](SportsStore_CompletingtheCart2.PNG)
![CompletingCart3](SportsStore_CompletingtheCart3.PNG)
![CartTest](SportsStore_CompletingtheCart4.PNG)
