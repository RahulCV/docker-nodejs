

# Node.js based on Ubuntu 18.04 (Bionic Beaver)
----
### Pull from Docker Hub
```
docker pull rahulcv/nodejs:latest
```

### Build from GitHub
```
docker build -t rahulcv/nodejs github.com/rahulcv/docker-nodejs
```

### Run image
```
docker run -it rahulcv/nodejs bash
```

### Use as base image
```Dockerfile
FROM rahulcv/nodejs:latest
```


