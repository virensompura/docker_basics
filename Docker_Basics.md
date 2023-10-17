To install Docker

\$ sudo apt-get install docker.io

To Check the version of the Docker

\$ docker \--version \$ sudo docker version

To view all the active/inactive container

\$ docker ps -a \$ docker ps

To pull the container from the Docker hub

\$ sudo docker pull Ubuntu: 20.04 \$ sudo docker pulll
\<image_name\>:\<version\>

To run the container in interactive environment

\$ sudo docker run -it \--name \<image_name\> /bin/bash \$ docker
container exec -it \<container_id\> bash

To continue working in same container

\$ sudo docker start -a -i \<container_name\>

To list down the containers

\$ docker container ls

To stop the container

\$ docker stop \<container_id\>

To inspect or want the information on the container

\$ docker inspect \<container_id\>

To run the container in the backgroud

\$ docker run -d \<container_name\>

To remove the container

\$ docker rm \<container_name\>

To check the log of the container

\$ docker logs \<container_id\>

To check the log of the container for specific time interval

\$ docker logs \--since 5s \<container_id\>

To commit the changes in the container

\$ docker commit -m \"added the changes in xyz.txt\" \<container_id\>
\<custom_img_name\>

To view the images of Docker

\$ sudo docker images

To remove docker

\$ sudo apt-get remove docker docker-engine docker.io containerd runc
