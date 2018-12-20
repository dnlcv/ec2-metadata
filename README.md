# ec2-metadata
Ansible role to install EC2 Instance Metadata Query Tool

## EC2 Instance Metadata Query Tool
A simple bash script that uses curl to query the EC2 instance Metadata from within a running EC2 instance.

[https://aws.amazon.com/code/ec2-instance-metadata-query-tool/](https://aws.amazon.com/code/ec2-instance-metadata-query-tool/)

## Configuration
A local copy of the script is located under the files folder to allow ansible to quickly provision the script. However you can choose to download it from the official website or a custom website.
```
ec2_metadata_download: false
ec2_metadata_url: "http://s3.amazonaws.com/ec2metadata/ec2-metadata"
```
