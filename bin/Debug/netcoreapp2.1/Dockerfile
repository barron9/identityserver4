FROM microsoft/aspnetcore
LABEL name="mking-website"
ENTRYPOINT ["dotnet", "authserver.dll"]
ARG source=.
WORKDIR /app
EXPOSE 80
COPY $source .
