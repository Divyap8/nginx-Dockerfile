This repostiory contains Dockerfile to install and run nginx software as a container . 
To build Dockerfile :
  docker build -t nginximg .
To check whether image is created  using Dockerfile : 
  docker images 
To launch a container using image of this Dockerfile :
  docker run -d -p80:80 --name nginxcontainer nginximg 
To check whether container is created  using image : 
  docker ps 
