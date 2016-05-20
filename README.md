# Elasticsearch, Logstash, Kibana (ELK) Docker image for IBM Bluemix Development and Deployment


This Docker image is a complete log management stack that is intended to be deployed in IBM Bluemix containers, for the managing 
the IBM Bluemix application logs, specifically during development.  This image uses  Elasticsearch, Logstash, and Kibana, collectively known as ELK. It provides a quick easy way to manage and monitor apps, over a long period of time, providing debugging information useful in tracking down intermittent and long running issues.

This image is not intended to be used for production loads.  In those cases it might make more sense to manage separate containers and configure the stack with more security.


### Security

This image has no security features enabled, and is intended for development or local use only.  For information on securing this stack see the bog [Elastic Security: Deploying Logstash, ElasticSearch, Kibana "securely" on the Internet ](http://blog.eslimasec.com/2014/05/elastic-security-deploying-logstash.html).

### Docker Hub

This image is hosted on Docker Hub and can be pulled from [jconallen/elk-bluemix](https://hub.docker.com/r/jconallen/elk-bluemix/).

### About

This image was modified by Jim Conallen from the original image written by [Sébastien Pujadas](https://pujadas.net). 
It has been modified to be used to work with IBM Bluemix applications and be hosted in IBM Bluemix Docker Containers.  
It remains released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).

