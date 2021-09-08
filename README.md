# aspdotnet-example
Sample web app based on ASP .NET

## Requirements

- Make sure you have [dotnet](https://dotnet.microsoft.com/download) configured/install on local/agent/destination machine 
## Run
1. Clone the repo
2. Goto repo folder -> `cd aspdotnet-example`
3. Start live web server -> `dotnet restore` ->  `dotnet watch run`
4. It should take you to [https://localhost:5000](https://localhost:5000)

## Build

- <b>Build application/Piublish</b>: `dotnet restore` -> `dotnet publish -c Release -o out`
- <b>Docker Image</b>: Use `Dockerfile` in the root folder -> `docker build -t <DOCKER_REPO/IMAGE_NAME:TAG> .`