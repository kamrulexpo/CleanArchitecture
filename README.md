# CleanArchitecture
ASP.NET Core Clean Architecture Project


### Add migrations
``` 
 dotnet ef migrations add "IniialCreate" -o "Data/Migrations" --project src/Infrastructure --startup-project src/web
 ```


### Update Database

```
 dotnet ef database update --project src/Infrastructure --startup-project src/web 
```
