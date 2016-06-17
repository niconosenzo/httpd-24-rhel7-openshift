## Openshift template for apache httpd server

Openshift template for httpd server. 
Based on rhscl/httpd-24-rhel7 docker image.

# Dockerfile 

Docker file example shows how to build and use image. 
To build image use

	docker build -t yourorg/imagename .

By default template using upstream image, so make sure you would update references
before adding it to openshift.

# Template

To use template load it into your openshift cluster:

	oc create -f application_template.yaml

 
