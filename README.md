# DockerWith.NETCore
Sample Core of ASP.NET Core Application to Create Docker Image in Linux CentOS.

Here are the steps for how to create your first Docker Image in CentOS Linux.

1) 	Install Docker for linux in CentOS.

2) Install dotnet from https://www.microsoft.com/net/core#centos.

3) Reach to the path where application is stored.

4) Use the command to build Image - docker build -t <ImageName>

5) Check the Image is created with the command - docker images. It will listdown all the images created in docker.

6) execute the coomand to run docker Image - docker run -t -p port:port <image name>. Here the port name would be the post that is mentioned in the docker file. here in this example I have mentioned to port name is 5000. The image would run in this case and browse the url in Linux with http://localhost:5000 or user the IP Address of the machine.
