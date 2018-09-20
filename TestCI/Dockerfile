FROM microsoft/dotnet:2.1.1-aspnetcore-runtime
WORKDIR /app

COPY ./out .
EXPOSE 5001
ENTRYPOINT [ "dotnet","TestCI.dll" ]