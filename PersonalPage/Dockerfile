FROM mcr.microsoft.com/dotnet/aspnet:6.0-alpine
COPY . /app
WORKDIR /app
RUN dotnet restore
RUN dotnet build
EXPOSE 80
ENTRYPOINT ["dotnet", "run"]
