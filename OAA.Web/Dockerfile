FROM microsoft/aspnetcore:2.0
WORKDIR /publish
COPY ${source:-/} .
EXPOSE 80
CMD ["dotnet", "OAA.Web.dll"]