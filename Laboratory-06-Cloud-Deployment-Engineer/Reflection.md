# Mission Reflection

Writing a `docker-compose.yml` file significantly simplifies a cloud engineer's workload compared to executing individual `docker run` commands. Instead of manually configuring containers, networks, and environment variables every time, Compose allows us to define the entire application stack as Infrastructure as Code. This makes deployments reproducible, consistent, and easy to manage with a single command.

When working with YAML files, proper formatting is critical. An indentation error, such as using Tabs instead of Spaces or misaligning keys, will cause parsing failures and prevent the stack from deploying. YAML relies strictly on whitespace to denote structural hierarchy.

Environment variables like `MYSQL_PASSWORD` were used to securely configure application settings and establish database authentication parameters without hardcoding parameters directly inside container builds.

Deploying an enterprise-grade cloud system like Nextcloud in just a few minutes highlighted the power of modern containerization. Seeing the web interface connect seamlessly to the database stack demonstrated how quick enterprise infrastructure setup can be.

Since Mission 1, my understanding of Cloud Computing has evolved from viewing servers as standalone machines to orchestrating modular, scalable microservices using Infrastructure as Code.
