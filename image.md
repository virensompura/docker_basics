#IMAGES

## To pull the image
  
    $ docker pull <image_name>

## List all the images
    
    $ docker images -a

## Delete single image

    $ docker rmi <image_id>

## Delete all images

    $ docker rmi $(docker images -q)

## Building Image from DockerFile

    $ docker build -t <image_name>
