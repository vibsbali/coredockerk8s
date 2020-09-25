FROM mcr.microsoft.com/dotnet/core/sdk:3.1 AS base
RUN mkdir app
WORKDIR /app
COPY . /app
RUN dotnet restore
CMD ["dotnet","watch","run","--urls http://0.0.0.0:5000;https://0.0.0.0:5001"]
