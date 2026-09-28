# Mission Reflection

### 1. Why object storage is better suited for millions of photos compared to traditional block storage:
Block storage requires managing a strict file system hierarchy and fixed drive capacity limits. As photo volume scales into millions, index lookup overhead slows down operations, and scaling storage requires re-partitioning or mounting additional drives. Object storage uses a flat namespace and custom metadata tags, allowing horizontal scaling across massive server clusters while retaining fast, direct access via web URIs without filesystem constraints.

### 2. How Docker simplified deploying MinIO:
Docker eliminated complex manual dependency installations, environment configuration, and service setups. By executing a single `docker run` command, the complete MinIO server stack was fetched, configured with custom credentials, mapped to specified system ports, and launched in an isolated environment within seconds.

### 3. What a "bucket" is in cloud storage:
In object storage, a bucket is a logical container used to organize and store objects (files and metadata). It functions similarly to a top-level root directory or drive, serving as the namespace, access control boundary, and administrative container for stored objects.

### 4. How enterprise companies prevent data loss during physical server crashes:
Enterprise cloud providers ensure durability through data replication across multiple availability zones and nodes, erasure coding (splitting data into chunks with parity for reconstruction), and automated cross-region asynchronous backups.

### 5. Linux command line confidence:
Navigating Linux CLI environments, running Docker daemons, mapping network ports, and executing terminal commands has become significantly clearer and more routine through hands-on cloud deployment exercises.
