# Cloud Storage Research

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
| :--- | :--- | :--- | :--- |
| **Block Storage** | Stores data in fixed-size blocks without metadata, managed like an raw hard drive by an OS. | High-performance OS booting, relational databases, transactional systems. | AWS EBS (Elastic Block Store) |
| **File Storage** | Stores data in a hierarchical file structure (folders/files) using network protocols like NFS/SMB. | Shared network file drives, legacy application migration, content management systems. | AWS EFS (Elastic File System) |
| **Object Storage** | Stores data as self-contained objects containing raw data, metadata, and a unique identifier in a flat namespace. | Unstructured data storage, backup images, video archives, web assets, and analytics datasets. | AWS S3 (Simple Storage Service) |

### Why Object Storage for User-Uploaded Images?

Object Storage is the ideal choice for storing millions of user-uploaded images because of its flat namespace and horizontal scalability, eliminating file system tree overhead. Unlike Block or File storage, Object Storage allows customized metadata tagging and direct access via standard HTTPS REST APIs without server-side filesystem limitations. This ensures cost-effective, high-availability storage that grows seamlessly alongside image volume.
