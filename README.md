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

### Running a new docker instance OS
```
docker run -itd --name kali --network="host" kalilinux/kali-linux-docker
```
