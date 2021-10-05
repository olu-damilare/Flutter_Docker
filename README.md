# flutter-web-dockerfile
A demo how to setup flutter web in docker container. The demo code is the default flutter app with a little modification in the title.

# Command
## Clone the repo
```
git clone https://github.com/olu-damilare/Flutter_Docker.git

```
## Switch directory
```
cd Flutter_Docker

```
## Build the docker image
```
docker build . -t flutter_docker .
```
## Run the container
```
docker run -i -p 8080:5000 -td flutter_docker

```

## View the application

localhost:8080



##   F l u t t e r _ D o c k e r  
 