# CEKAPURUM from doxxa11 (https://github.com/doxxa11)

## About

Ardio's project which requires containerization in the process of deploying this "CEKAPURUM" application.

## Before

Make sure on public>sensor.html line 19 to change to your IP.

## Requirements
 1. DOCKER

## Build an Image from Dockerfile:

 1. Clone this project
 2. Go to directory
 3. Type `docker build -t yourimagename .`
 
## Run image to Deploy on Docker:

  1. See and select your Docker image, type `docker images`
  2. Type `docker container run -d -p 80:80 yourimagename`
  3. Access on `localhost:80`
  
## if you are lazy to create an image:
  1. Type `docker pull gilangvperdana/cekapurum:3000`
  2. After the image is downloaded, run the images.

## This final site has been deployed on:
 `cekapurum.gbesar.com`
