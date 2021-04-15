# CEKAPURUM

## About

Ardio project which requires containerization in the process of deploying this "CEKAPURUM" application.


## Build an Image from Dockerfile:

 1. Clone this project
 2. Go to directory
 3. Type `docker build -t yourimagename .`
 
## Run image on Docker:

  1. See and select your Docker image, type `docker images`
  2. Type `docker container run -d -p 80:80 yourimagename`
  3. Access on `localhost:80`
  
## if you are lazy to create an image:
  1. Type `docker pull gilangvperdana/cekapurum:3000`
  2. After the image is downloaded, run the images.

## Site can be accessed on :
 `cekapurum.gbesar.com`
