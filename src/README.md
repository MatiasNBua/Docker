# Docker

## Docker IMAGES:

- **docker images** -> for view all images that we have in our ordenator

- **docker pull node/node:16** -> (whit this form we can install images with differents versios or the latest version)

- **docker rm node/node:16** -> with this command u can delete the image of docker

## Docker Container:

- **docker create mongo** -> on this command u can create a docker container , and for last you can put the container name how referency

- **docker start [IDdocker]** -> here you up the docker container and u can take the dockerID in the last step when u create the docker

- **docker stop [IDdocker]** ->  Use this command serves for stop running the docker container

- **docker ps** -> Use this command u can see theses containers that running 
 
- **docker ps -a** -> Use this command u can the possibility of see all container is existing  

- **docker rm [docker-Name]** -> Use this command serves for eliminate a docker container

- **--name [docker-Name]** -> Use this command serves for change or assignes the dockers name

- **docker logs [doker-name]** ->  Use this comand the show you a logs of  your container online

- **--follow** -> Use this command u can see the container online, in case of any change, it will show it on the console.

- **docker run [image]** *[Is a simple command for apply all this seen above]* -> Use this command to find the image if you don't have it, download it. Create a new docker container and start this container.
 
- **-d** -> Use this command to initialize a docker container with a *dettached* mode, with this you can continue coding with the container running in the second location
 
- 


## Docker NETWORK:

- **-p[port of my ordenator]:[port on container of mapping with my computer]**

- **create docker -p[27017]:[27017] --name[name-docker] mongo**