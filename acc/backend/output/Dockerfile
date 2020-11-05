FROM mcr.microsoft.com/dotnet/core/aspnet:3.0-alpine

WORKDIR /app

COPY /netcoreapp3.0 app/

ENTRYPOINT ["dotnet", "app/MyCity-Registries.dll"]
