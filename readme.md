**deprecated: [now a built-in AWS feature](https://aws.amazon.com/blogs/aws/s3-lifecycle-management-update-support-for-multipart-uploads-and-delete-markers)**

s3mpu-cleanup
-------------
Cleanup stale multipart uploads from an S3 bucket.

    $ npm install -g s3mpu-cleanup
    $ s3mpu-cleanup s3://my-bucket

    aborted s3://my-bucket/thumbnails/preview.jpg@16FTtpvs.gJx...
    aborted s3://my-bucket/thumbnails/catgif.jpg@OerXqge5ncLs...
    aborted s3://my-bucket/thumbnails/logo.jpg@BRXewFOgz2Ah...

