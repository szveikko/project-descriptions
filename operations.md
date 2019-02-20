# Operations

## Description

The Operations team is responsible for providing tools and infrastructure to all the other teams in the project phase, so they can have a standaridzed development environment. The project itself is not necessarily about building something new and unseen before, rather about learning how to use the tools that are in the repertoire of every DevOps engineer. While learning the usage of the tools, the apprentices also understand the concepts behind each technology. This is important because by understanding how and why are these technologies working in the way they are, the switch to a new technology can be almost effortless and really quick.

## Technologies

The project starts with a 0th week mini exercise in which the apprentices have to containerize a web application with database connected and deploy it manually to *AWS Elastic Beanstalk*. 
In the upcoming weeks, building on this basis they gradually start using *docker-compose* and *EC2* for deployment of the applications. From the third week onwards the infrastructure is no longer created manually, but with the help of *Terraform* for setting up the development/staging/production environments on *Elastic Cloud Computing*. Right after learning automated infrastructure creation the usage of CI servers is starting as well, the apprentices use Jenkins pipelines to build and test applications, block pull requests if necessary, send notifications to slack and deploy automatically to production.
In the end this toolkit gets extended with software that are capable of monitoring applications and servers, namely *Nagios* and the *ELK stack* which the apprentices first set up using *Terraform* and *Docker* and they start to monitor applications and the servers under these webapps.

The toolset that the apprentices use daily consists of:

- Amazon Web Services (AWS)
- Terraform
- CI servers (Jenkins/CircleCi)
- Linux Command Line 
- Docker
- ELK stack / Nagios