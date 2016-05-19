# Elasticsearch, Logstash, Kibana (ELK) Docker image for IBM Bluemix Development and Deployment


This Docker image is a complete log management stack that is intended to be deployed on IBM Bluemix containers, managing 
the logs of Bluemix applications, specifically during development.  It provides a quick easy way to manage and monitor 
Bluemix applications, providing debugging information useful in tracking down intermittent and long running issues.

This image is not intended to be used in production loads, where it might make more sense to manage separate containers for each component.

This image uses  Elasticsearch, Logstash, and Kibana, collectively known as ELK.

### Documentation

See the [ELK Docker image documentation web page](http://elk-docker.readthedocs.io/) for complete instructions on how to use this image.

### Docker Hub

This image is hosted on Docker Hub at 

### About

This image was modified by Jim Conallen from the original image written by [Sébastien Pujadas's](https://pujadas.net). 
It has been modified to be used to work with IBM Bluemix applications and be hosted in IBM Bluemix Docker Containers.  
It remains released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).

