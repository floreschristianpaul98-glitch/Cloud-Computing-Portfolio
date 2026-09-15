# Docker Deployment Documentation

## Commands Executed

### 1. Pull Nginx Image
```bash
docker pull nginx
```
Downloads the official Nginx image from Docker Hub.

### 2. Run Container
```bash
docker run -d -p 8080:80 --name my-nginx nginx
```
Creates and starts Nginx container in background, mapping port 8080 to port 80.

### 3. Test Web Server
```bash
curl http://localhost:8080
```
Sends HTTP request to verify Nginx is running.

### 4. List Running Containers
```bash
docker ps
```
Shows all currently running containers.

### 5. Stop Container
```bash
docker stop my-nginx
```
Gracefully stops the running container.

### 6. List All Containers
```bash
docker ps -a
```
Shows all containers including stopped ones.

### 7. Remove Container
```bash
docker rm my-nginx
```
Permanently deletes the stopped container.
