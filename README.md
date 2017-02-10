# Rclone Client

## Function
Installs and configures the [Rclone](http://rclone.org) client with an Amazon S3 destination.

## Vault
```
---
rclone_s3_remote_name: example
rclone_s3_access_key_id: xxxXXXxxxXXXxxxXXX
rclone_s3_secret_access_key: xxxXXXxxxXXXxxxXXX
rclone_s3_region: ca-central-1
rclone_s3_location_constraint: ca-central-1
```

## Variables
Amazon notes [regions and location constraints here](http://docs.aws.amazon.com/general/latest/gr/rande.html#s3_region).  Additional configuration variables may be modified within `rclone.conf.j2`.

## Tested Environment(s)
RHEL 7 & CentOS 7

## Changelog
**v1.01 (2017-02-10)**
* Modified to use Amazon S3 by default
* Added vault variables for name, region, and location constraint
* Modified tags for additional relevancy

**v1.0 (2016-03-28)**
* Original Release
