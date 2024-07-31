# Building the image form Docker file in the local repo
- docker build . -t node-app:latest

# Running the Container from created image and publishing the app to port 80
- docker run -p 8000:8000 node-app:latest

# Application Running on Port 8000

![alt text](https://github.com/omdusane/docker-node-cicd/blob/main/image.png?raw=true)
