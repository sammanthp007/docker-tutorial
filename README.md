## The slides:
https://docsend.com/view/swfzsus


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
