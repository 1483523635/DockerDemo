FROM microsoft/aspnetcore:latest
#ARG Docker-Simple
#WORKDIR /app
#EXPOSE 80
#COPY ${source:docker-simple}/publish .
ENTRYPOINT ["dotnet", "Docker-Simple.dll"]
RUN mkdir -p /usr/src/app/DockerTest 
COPY . /usr/src/app/DockerTest 
WORKDIR /usr/src/app/DockerTest 
EXPOSE 80
#CMD ["dotnet", "Docker-Simple.dll", "--urls", "http://*:80"]
ENTRYPOINT ["dotnet", "Docker-Simple.dll"]
