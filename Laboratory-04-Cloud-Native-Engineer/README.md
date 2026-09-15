# Laboratory 4: Cloud-Native Engineer

## Mission Overview
This laboratory introduces containerization and Docker, a fundamental shift from traditional virtual machines. As a Cloud-Native Engineer, I learned how to deploy, manage, and document containerized applications using Docker.

## Objectives
- Differentiate between Virtual Machines and Containers
- Access and verify Docker in a cloud environment
- Execute Docker CLI commands to manage containers
- Deploy and manage a containerized Nginx web server
- Create professional technical documentation

## Docker Commands Executed

### Image Management
```bash
docker pull nginx                          # Download Nginx image
```

### Container Deployment
```bash
docker run -d -p 8080:80 --name my-nginx nginx
curl http://localhost:8080                # Test web server
```

### Container Lifecycle
```bash
docker ps                      # List running containers
docker ps -a                   # List all containers
docker stop my-nginx           # Stop container
docker rm my-nginx             # Remove container
```

## Skills Learned
✅ Understanding containerization vs. virtualization
✅ Using Docker CLI
✅ Port mapping and networking
✅ Container lifecycle management
✅ Technical documentation

## Screenshots
- docker-version.png
- nginx-running.png
- container-lifecycle.png


<img width="1807" height="777" alt="image" src="https://github.com/user-attachments/assets/ee36a0a6-83bf-4870-93c0-96b2d6be2421" />
