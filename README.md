# S3-upload-file
Minimum working example showing how to upload file to S3 bucket.

## Usage
Run the following command:

```bash
docker-compose up
```
A web server and a standalone [Minio](https://min.io) instance are started. MinIO offers high-performance, S3 compatible object storage, which is perfect for our local demonstration.

Visit `http://localhost:8088`, select a file from your device, and press the upload button. If the file is uploaded to S3 successfully, the server will return the new file name that is used as an identifier in the bucket.

Visit `http://localhost:9000` and you can view all uploaded files from MinIO GUI.
