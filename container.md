# CONTAINERS

## To Interactive Container from Images
  
    $ docker run -it <image_name>

## Giving a name to the Container while Creating 

     $ docker run --name <container_name> <image_name>

## Start Container which is Stopped

     $ docker start <container_id>

## To stop all the container

     $ sudo docker kill $(docker ps -a)

## To Connect Shell to Running Container

     $ docker container exec -it <container_id> bash

## To Delete Single Container

     $ docker rm <container_id/container_name>

## To Delete All Container

     $ docker rm $(docker ps -a -q)

## To list down the containers

     $ docker container ls

## To inspect or want the information on the container

     $ docker inspect <container_id>

## To run the container in the backgroud

     $ docker run -d <container_name>

## To check the log of the container

     $ docker logs <container_id>

## To check the log of the container for specific time interval

     $ docker logs --since 5s <container_id>

## To commit the changes in the container

      $ docker commit -m "added the changes in xyz.txt" <container_id> <custom_img_name>
