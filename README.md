# Minio S3 Server Playbook

This playbook will set up and configure a Minio S3 Server and the Client on target nodes.

It is suggested to have a second volume as your Minio Volume.  If on AWS, attach another EBS volume, and use the following procedures to mount the volume to your data directory: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-using-volumes.html
