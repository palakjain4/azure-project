# azure-project

https://palakjain4.github.io/azure-project/ 

Industry: Lifestyle

Project Title: E-Commerce App

Problem Statement/Opportunity:
This is a project where I am going to deploy a website using azure services which can be used for e-commerce purpose over the internet.

Project Description:
This is a project where I am going to deploy a website using azure services which can be used for e-commerce purpose over the internet. 
Website Architecture: It is going to use two different servers for two different regions viz. US and India, accessed through a common domain. Then a load balancer, at the top of each server, is going to route the request to a specific regional server.

Primary Azure Technology: Virtual Machines, Traffic Manager, Application Gateway

Other Azure Technologies: DNS zones, Public IP Address, Resource groups.

Deployment steps: I firstly created 4 servers viz. 2 Indian servers and 2 US servers using virtual machines. Then deployed application gateways for Indian and US servers respectively. Then deployed a load balancer to distribute traffic among servers using traffic manager. DNS zone anlongwith some external help was used to deploy the final website.

Deployment URL: www.azure-project.tk
