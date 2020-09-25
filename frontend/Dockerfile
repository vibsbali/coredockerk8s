FROM mcr.microsoft.com/dotnet/core/sdk:3.1 AS base
RUN mkdir app
WORKDIR /app
COPY . /app
RUN dotnet restore
CMD ["dotnet","watch","run"]
