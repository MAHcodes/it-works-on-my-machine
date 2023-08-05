FROM mcr.microsoft.com/dotnet/sdk:6.0

WORKDIR /app

COPY . .

EXPOSE 5000

ENV ASPNETCORE_URLS=http://+:5000

CMD ["dotnet", "{AppName}.dll"]
