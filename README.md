# hello-kubernetes
Nginx test container based on UBI8

## How to build
docker build . -t hello-kubernetes:latest 

## How to use
docker run -p 80:8080 -d hello-kubernetes  
curl http://localolhost 


