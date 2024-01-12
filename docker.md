# docker

## Check all images
sudo docker images

## Check all running containers
sudo docker container ls

## Check running and exited containers
sudo docker container ls -a

## Remove all images and containers not running
sudo docker system prune

## Build, tag and push
sudo docker build .
sudo docker tag IMAGE_NAME chuysb/IMAGE_NAME:latest
sudo docker image push chuysb/IMAGE_NAME:latest

## Docker Compose Run
sudo docker compose up -d 
