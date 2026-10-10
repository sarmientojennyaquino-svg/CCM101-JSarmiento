# Types of Cloud Storage

Cloud storage can be divided into three primary types: Block Storage, File Storage, and Object Storage. Each type is designed for different storage requirements and workloads.

| Storage Type       | Description                                                                                                                                                  | Primary Use Case                                                                                    | Cloud Provider Example              |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- | ----------------------------------- |
| **Block Storage**  | Stores data in fixed-size blocks that can be managed individually. It provides high-performance storage that can be attached to a virtual machine or server. | Best for operating systems, databases, and applications that require fast and consistent storage.   | **AWS EBS (Elastic Block Store)**   |
| **File Storage**   | Stores data as files organized in folders and directories. Multiple users or systems can access the same file system.                                        | Best for shared files, documents, and applications that need a common file system.                  | **AWS EFS (Elastic File System)**   |
| **Object Storage** | Stores data as objects along with metadata and a unique identifier. Objects can include images, videos, documents, and backups.                              | Best for large amounts of unstructured data such as photos, videos, backups, and other media files. | **AWS S3 (Simple Storage Service)** |

### Why Object Storage is Suitable for the Client

Object Storage is a suitable choice for the client's photo-sharing application because it is designed to store large amounts of unstructured data such as user-uploaded images. It allows the application to keep photos separately from the web server while providing scalable and accessible storage for potentially millions of images.
