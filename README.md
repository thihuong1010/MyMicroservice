# MyMicroservice
Create a simple service that returns a list of values, then run the service in a Docker container

# Tech stacks
- .NET
- Microservice
- Docker

# Link tutorial
https://dotnet.microsoft.com/en-us/learn/aspnet/microservice-tutorial/intro

# How to run
- Create docker image: "docker build -t mymicroservice ."
- Run docker image: "docker run -it --rm -p 3000:80 --name mymicroservicecontainer mymicroservice"
- You can browse to the following URL to access your application running in a container: http://localhost:3000/WeatherForecast

- Optionally, you can view your container running in a separate terminal window using the following command: docker ps
