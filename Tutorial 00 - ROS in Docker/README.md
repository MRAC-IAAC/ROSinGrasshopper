# ROS and Docker
- Clone this repository and open this folder in VSCode
- Build the docker image using the `Dockerfile`
    - in VSCode press `ctrl+shift+p` then type `Docker images: Build image`
    - enter a name for the image *("image_name":"tag")*: `roboticmosaic:latest`  
- Run multiple containers from the built image using the `docker-compose.yml` file from the VSCode terminal
    - docker-compose up -d


## Additional References
 
 [Docker compose | ROS](`http://wiki.ros.org/docker/Tutorials/Compose`)
 