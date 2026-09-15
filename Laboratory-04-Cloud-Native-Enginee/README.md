# Mission Overview
This project explores cloud-native engineering fundamentals by comparing traditional virtual machine architectures against modern lightweight containers, deploying a containerized Nginx web server, and documenting container lifecycle management.

# Objectives
- Analyze key architectural differences between Hypervisor-based VMs and OS-level Containers.
- Initialize and inspect a Docker runtime environment on Linux.
- Deploy an Nginx web server container using detached execution and host-to-container port mapping.
- Execute lifecycle operations (listing, stopping, and removing containers).
- Maintain structured documentation and version control artifacts via GitHub.

# Docker Commands Executed
- `docker --version`
- `docker info`
- `docker pull nginx`
- `docker run -d -p 8080:80 --name my-nginx nginx`
- `curl http://localhost:8080`
- `docker ps`
- `docker stop my-nginx`
- `docker rm my-nginx`

# Skills Learned
- Managing Docker images and container lifecycle stages.
- Configuring container network exposure using host-to-container port forwarding.
- Utilizing Linux terminal commands for web application testing (`curl`).
- Authoring structured technical documentation using Markdown standards.

# Challenges Encountered
- Mapping container ports correctly (`-p 8080:80`) to ensure traffic from host network interfaces routes directly to the isolated container environment.
