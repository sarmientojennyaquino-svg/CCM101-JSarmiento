# MinIO Deployment

## Docker Command Used

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
local-minio:latest server /data --console-address ":9001"
```

## Web Console Port

The MinIO web console is accessed through port **9001**.

The MinIO server uses port **9000**, while the MinIO management console uses port **9001**.

## Bucket Created

The bucket created in the MinIO web console is:

`client-photos`

A test file was uploaded to the bucket to verify that object storage was working.

## Environment Variables

The `-e` flags are used to set environment variables inside the Docker container.

`MINIO_ROOT_USER=cloudadmin` sets the administrator username.

`MINIO_ROOT_PASSWORD=CloudNova2026!` sets the administrator password.

These variables allow the MinIO server to start with the specified administrator credentials.
