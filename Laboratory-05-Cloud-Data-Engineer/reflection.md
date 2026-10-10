# Reflection

This laboratory helped me understand why object storage is useful when working with a large number of photos and other files. Object storage is suitable for millions of photos because the data can be stored as individual objects inside buckets. Unlike traditional block storage, object storage is designed for large amounts of unstructured data and provides a simple way to organize and access files.

Docker made the deployment of MinIO easier because I could run the storage service inside a container without manually installing and configuring every component on the Ubuntu system. The Docker command allowed me to configure the MinIO administrator username and password using environment variables. Port forwarding also allowed me to access the MinIO web console through my browser.

A bucket is a container used to organize and store objects in object storage. In this activity, I created a bucket named `client-photos` and uploaded a test file into it. The bucket provides a way to organize the uploaded data and manage the stored objects.

Enterprises can reduce the risk of data loss from physical server failures by using redundancy, backups, replication, and reliable storage systems. Instead of depending on only one physical server or disk, organizations can maintain copies of important data in other systems or locations. This helps protect data when hardware fails.

After completing this laboratory, I feel more confident using the Linux command line. I used commands such as `docker build`, `docker run`, `docker ps`, and other Linux commands to build and manage the MinIO environment. I also learned how Docker ports connect a containerized service to a web browser. Overall, the activity gave me practical experience with object storage, Docker, MinIO, and Linux.
