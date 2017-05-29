# dockertest
```sh
docker pull nginx:alpine
docker images
docker rmi 7e //remove image
docker run -d -p 8080:80 nginx:alpine
docker ps -a //show all runing container
docker stop c2 //stop
docker rm c2 //remove running image

docker run -d -p 8080:80 -v $(pwd):/usr/share/nginx/html nginx:alpine
```
