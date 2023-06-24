# hello-kubernetes
Nginx test container based on UBI8

## How to build
```
docker build . -t hello-aro:latest 
```

## How to use
```
$ docker run --rm --name hello-test -p 80:8080 -d hello-aro:latest
$ curl http://localhost 
Hello ARO!
ARO is an abbreviation for Azure Red Hat OpenShift. It's a managed OpenShift service on Azure.
$ docker stop hello-test

```

