FROM microsoft/dotnet:1.0.0-preview2-sdk
 
# Set environment variables
ENV ASPNETCORE_URLS="http://*:5000"
ENV ASPNETCORE_ENVIRONMENT="Development"
 
# Copy files to app directory
COPY . /app
 
# Set working directory
WORKDIR /app
 
# Restore NuGet packages
RUN ["dotnet", "restore"]
 
# Open up port
EXPOSE 5000
 
# Run the app
ENTRYPOINT ["dotnet", "run"]