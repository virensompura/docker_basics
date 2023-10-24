# Docker Networking 

## List of all Docker Networks

  $ docker network ls

## To Assign Static IP to container 

  $ docker network create <network_name> --subnet=192.168.0.0/24

  $ docker run -d -network <network_name> --ip 192.168.0.109 <image_name>

## To connect the Docker container with custom network

  $ docker network connect <network_name> <container_id>

## To diconnect the Docker container with custom network

  $ docker network disconnect <network_name> <container_id>
