# ByteCubed Configuration Management Challenge

Infrastructure Provisioning & Deployment
==========================

# Overview
At ByteCubed, we all share a passion for finding elegant solutions for complex problems.  To demonstrate your capabilities, we have provided a listing of sample problems meant to serve as a conversation point and help with the interview process.  These challenges are meant to be simple and should only require 2-3 hours to complete.

# Goal

Create a simple web server and provide a set of tools to serve as a health check.

# Prerequisites

You will need an [AWS account](http://aws.amazon.com). Create one if you don't own one already. You can use free-tier resources for this test.

# The Task

You are required to set up a new server in AWS. It must:

* Be publicly accessible.
* Run NGINX or Apache - To serve content.
* Deploy the following content.

```
ByteCubed Challenge ${HOSTNAME}
```

_Note_: ${HOSTNAME} is expected to be dynamically loaded as part of deployment, meaning that this will be different on each __new server__ deployment.  

# How to Submit
* Simply respond to your recruiter/team with a link to a Github repository. That contains the following items
  - Scripts (Shell Scripts, Ansible, Chef, Terraform, etc)
  - Deployment Instructions
  - Templates (if necessary)

# Extra Credit

This section is not necessary so not doing this will not have any bearing on how you are evaluated.  If you would like to demonstrate more of your capabilities, you can include the configuration for the following components.

* Leverage a scripting tool of your choice such as Terraform (our internal automation tool of choice).
* Leverage Docker as a way to containerize your application to assist in deployments.
* Run two of your web servers in High Availability Mode with a load balancer of your choice (NGINX, HAProxy, ELB).
