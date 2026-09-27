# Storage Types Research

## Comparison Table

| Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Splits data into fixed-size blocks, attached directly to a VM like a hard drive | Databases, OS boot volumes | AWS EBS |
| File Storage | Data organized in a hierarchical folder/file structure, accessed over a network | Shared file systems, home directories | AWS EFS |
| Object Storage | Stores data as objects with metadata, accessed via API/URL, highly scalable | Unstructured data such as images, videos, and backups | AWS S3 |

## Why Object Storage Suits the Client

Object Storage is suitable for the client because it can store large amounts of unstructured data such as images, videos, and backups. It is also highly scalable, so the storage can grow as the client's data increases without needing to manage physical storage directly.
