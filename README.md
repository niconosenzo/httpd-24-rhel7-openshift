## Openshift3 template for apache httpd server

Based on rhscl/httpd-24-rhel7 docker image.

# Dockerfile 

Docker file example shows how to build and use image. 
To build image use

	docker build -t yourorg/imagename .

# Template

To use template load it into your openshift cluster:

	oc create -f application_template.yaml



