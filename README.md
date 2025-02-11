<a href="https://www.buymeacoffee.com/hientech" target="_blank"><img src="https://img.shields.io/badge/-buy_me_a%C2%A0coffee-gray?logo=buy-me-a-coffee" alt="Buy Me A Coffee"></a>
  <br>
# jhipster-project-
JHipster project - Microservices architecture




### Monolithic web application 
+ MySQL - security aspects - run application test - 
+ i18n option 
+ testing option 
+ Modules 
+ File structure - server side source code 
+ Resource : config - i18n - mails - templates 
+ Admin module : User management, Metrics, Health, Config , Audit, Logs, API 
+ Run generated test- server side test - client side test 


### Entity modeling with Domain language 




### Deploy to production 
+ Docker 
    + Dockerfile 
+ Start production database with Docker 
+ Spring profiles 
+ Package app for local deployment
    + Building and deploying using Docker 
        + Use gradle task to build docker image
+ Heroku cloud 

### Microservice architecture 
+ Service registry 
+ Service discovery 
+ Health check 
+ Dynamic routing and resiliency 
+ Security 
+ Failover




### Deploy with Docker Compose
+ Docker Compose 
    + docker-compose file 
    + `docker-compose -f docker_file up `
    + `docker-compose -f docker_file down`
    + `docker ps`
    + `docker log container_id`
+ Kubernetes - orchestrate your deployment
    + Automatic deployment - scaling - managing containerized applications 
    + Automate it to scale it and out based on factors 
    + Spin up a new instance 
    + Zero downtime production - scale as require
    + Deployable component : pod - running process in container - deployment
    + Sample Kubernetes file - start a Nginx server 
    + kubectl CLI tool 
    + minikube - minified kubernetes - deploy and test 
+ OpenShift - provide cloud deployment
    + multi-cloud - open source container application platform - based on Kubernetes - deploy and manage applications - platform to build - deploy - manage applications 
    + self-service platform - provision - build - deploy applications and their components - automated workflow for converting your source to image - source to ready-to-run - dockerized images
    + Operation - provide a secure - enterprise-grade Kubernetes - cluster services - scheduling - orchestration with load balancing - auto-scaling capabilities 
+ Rancher - complete container management  
    + Rancher - container management platform - open source 

### JHipster best practices 
+ 



