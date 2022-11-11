# MinIO HA with Nginx Proxy setup using Docker Compose

In this setup 4 MinIO instances are running in a distributed mode. 
The Nginx proxy is used to load balance the requests between the MinIO instances.

The MinIO GUI is available at [http://localhost:9000](http://localhost:9000).

The default admin credentials are `minioadmin:minioadmin`. 
You can change them by configuring the environment variables `MINIO_ROOT_USER` and `MINIO_ROOT_PASSWORD` in the `.env` file.