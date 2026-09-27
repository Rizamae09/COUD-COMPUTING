# Storage Types Research

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks and is commonly used like a hard drive. | Virtual machines and databases | AWS EBS |
| File Storage | Stores data in files and folders that can be shared across systems. | Shared files and applications | AWS EFS |
| Object Storage | Stores data as objects with metadata and unique identifiers. | Images, videos, backups, and other unstructured data | AWS S3 |

Object Storage is the best choice for the client's user-uploaded images because it is designed for large amounts of unstructured data. It can also scale as the number of photos increases.
