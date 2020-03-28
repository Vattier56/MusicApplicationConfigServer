# Music-Library Conifg Server Veloo
Spring Cloud Config provides configuration in a distributed system.

## Table of contents
* [General info](#general-info)
* [Requirements](#requirements)
* [Setup](#setup)

## General info
By default, the config server runs at ``` http://localhost:8888 ```

Configration can be found at ```http://localhost:<server port>/<application name>/<profile name>```



Default URL: ``` http://localhost:8888/config-service/default ```


## Requirements:
- Java version 1.8
- Apache Maven version 3.6.3
- Amazon account with S3 service
- Git repository with S3 configuration

Example configuration file  
```
$ access_id=AWSAccessKeyId
$ access_key=AWSSecretKey
$ bucket=bucketName
$ region=bucketRegionName
```
More information about S3 access keys

https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html

## Setup
To run this project, install it locally using maven:

```
$ mvn package
$ cd target
$ java -jar <projectName>
```

## Author
* Piotr Piasecki - [Vattier56](https://github.com/Vattier56)
