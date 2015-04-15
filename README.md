# Docker Python Flask Example Project

Install [boot2docker](http://boot2docker.io) - http://docs.docker.com/installation/mac/


```
docker build -t app .
docker run -d -p 8080:8080 app
```

## Test it out
```
curl `boot2docker ip`:8080
```
