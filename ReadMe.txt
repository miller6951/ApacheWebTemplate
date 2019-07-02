ReadMe 

Date: 7/1/2019

Apache CloudFormation Template

Scope: CloudFormation Template to create one Ec2 instance in default vpc / subnet that allows traffic both over 22 and 80.
       Apply the latest updates then install apache along with the creation of a index.html that prints hello world.
       Provide output of public DNS and public IP address back to the user executing the script.

Prerequisites:
       * Please run the template in the North Virginia region
       * Please create a keypair before running the template to ssh into the server

Runtime Instructions:
        * Navigate to CloudFormation
        * Choose Create Stack
        * Choose "Upload a template file" and select the file template to Upload
        * Enter a name for the Stack and choose your KeyName which would be the keypair created prior to Runtime
        * Click Next then Create Stack
        * After the EC2 and services are provisioned the Public IP and DNS will be shown in the outputs section

