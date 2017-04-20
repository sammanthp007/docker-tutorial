## The slides:
https://docsend.com/view/swfzsus

## Docker tutorial course
https://training.docker.com/user/consume/course_pathway/824abc9f-c99a-3031-a28b-e289f2910991


## Commands:

### For seeing all the images that are loaded
```
docker ps 
```

### For seeing all the images
```
docker images
```

### For stopping running images
```
docker stop <id>
```

### For removing stopped images
```
docker rm <id>
```

### For removing the image from the computer itself
```
docker rmi <id>
```

### For building a image
```
docker build -t <userid>/<any name> .
```

### For running the built imge
```
docker run -p 8888:5000 sammanthp007/flask-example
```

### Running a new docker instance OS while using hosts ip as connection
```
docker run -itd --name kali --network="host" kalilinux/kali-linux-docker
```

### For executing the bash of OS
```
docker exec -it kali bash
```

### For creating a copy of a stopped container
```
docker commit kali kaliNew
```

### For running a new docker instance OS while using its own ports
```
docker run -p 666:80 -itd --name kaliNew kaliNew
```
