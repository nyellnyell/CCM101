# Mission Reflection

1. **Boot Time and Setup:** Docker containers boot up within seconds because they run as isolated processes directly on the host operating system kernel. Virtual Machines require several minutes because they must initialize virtual hardware and load a complete guest operating system prior to running any application.

2. **Port Mapping (`-p 8080:80`):** Containers run inside isolated network namespaces detached from the host system. Port mapping routes incoming traffic from port 8080 on the host machine directly into port 80 inside the container where Nginx listens, enabling external access to the application.

3. **Data Impact of `docker rm`:** Deleting a container with `docker rm` permanently destroys its internal writable layer. Any data, files, or application logs created inside the container during execution will be permanently lost unless stored on external host mounts or volumes.

4. **DevOps & Containerization:** Containers bundle application code, dependencies, and configuration files into standard, immutable artifacts. This eliminates "works on my machine" issues, standardizing runtime behavior across local development and production systems while streamlining continuous integration and delivery (CI/CD) pipelines.

5. **GitHub Portfolio Evolution:** Adding container deployment and cloud-native practices demonstrates a transition from basic infrastructure setup to modern microservice delivery and application orchestration skills on my GitHub profile.
