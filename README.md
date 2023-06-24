# hello-kubernetes
Nginx test container based on UBI8

## How to build
```
docker build . -t hello-kubernetes:latest 
```

## How to use
```
$ docker run --rm --name hello-test -p 80:8080 -d hello-kubernetes:latest
$ curl http://localhost 
Hello Kubernetes!
$ docker stop hello-test

```

