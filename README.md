# Running Azure Functions v4 (.NET 6) on Windows Docker Container

1. Run `dotnet publish . -o ./app` to publish the app
2. Run `docker build -t docker-dotnet6` to build the image
3. Run `docker run -p 80:80 docker-dotnet6` to run the function image on Port 80.