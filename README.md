# config-management
A configuration management server is available in three steps.

## Description
Install Git, GitBucket, Jenkins and Artifactory on Vagrant.
So, you are released from construction of configuration management server.

## Usage
1. Download Vagrant and Virtual box
> https://www.vagrantup.com/

> http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html?ssSourceSiteId=otnjp

2. Adding Vagrant box
> $ vagrant box add centos7.2 https://github.com/CommanderK5/packer-centos-template/releases/download/0.7.2/vagrant-centos-7.2.box

3. provisioning
> $ vagrant up

## Pages
### GitBucket
> http://localhost:48081/gitbucket

### Artifactory
> http://localhost:48081/artifactory

### Jenkins
> http://localhost:48080

