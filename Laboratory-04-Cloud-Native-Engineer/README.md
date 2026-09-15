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
docker pull nginx                          # Download Nginx image from Docker Hub
```

### Container Deployment
```bash
docker run -d -p 8080:80 --name my-nginx nginx    # Run Nginx container
curl http://localhost:8080                        # Test the web server
```

### Container Lifecycle
```bash
docker ps                      # List running containers
docker ps -a                   # List all containers
docker stop my-nginx           # Stop the container
docker rm my-nginx             # Remove the container
```

## Skills Learned
✅ Understanding containerization vs. virtualization
✅ Using Docker CLI to manage images and containers
✅ Port mapping and networking in containers
✅ Container lifecycle management (create, run, stop, remove)
✅ Technical documentation with Markdown

## Challenges Encountered
- Initially unfamiliar with Docker syntax, but documentation and examples helped clarify
- Understanding port mapping took practice but is now clear

## Screenshots
- `docker-version.png` - Verification of Docker installation
- `nginx-running.png` - Successful curl output showing Nginx running
- `container-lifecycle.png` - Container management commands

---
**Completed:** [Today's Date]
