FROM mcr.microsoft.com/dotnet/aspnet:5.0
WORKDIR /app
COPY ./publish .
ENTRYPOINT ["dotnet", "Jitsukawa.EmailSender.Api.dll"]