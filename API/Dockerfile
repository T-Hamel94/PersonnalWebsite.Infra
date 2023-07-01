# Dockerfile
# Use Microsoft's official .NET Core runtime base image
FROM mcr.microsoft.com/dotnet/aspnet:6.0

# Set the working directory
WORKDIR /app

# Copy the publish directory from your development environment
COPY ./app .

# Start the .NET Core app
ENTRYPOINT ["dotnet", "./PersonnalWebsite.RESTAPI.dll"]
