# Terraform Basics

### How to install terraform ?

```````
    $ sudo yum install -y yum-utils
    $ sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
    $ sudo yum -y install terraform

```````

### Current verison of terraform is v1.9.5

`````````
   $ terraform -v 

`````````
### Provider vs Terraform version.

Terraform version : This is the tool version Provider version : This is the software version of the cloud provider and based on the selected provider version we might see different options. We typically go with latest. 

### When you make a place, you can see these symbols and here are the  meanings of it:

````
    +   : creates resource 
    -   : deletes resource
    -/+ : delete and recreate the resources
    ~   : something is changing in the existing resources 
    
``````
