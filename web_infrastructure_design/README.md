# Web Infrastructure Design

## Overview
This project delves into the fundamentals of web infrastructure design, covering key concepts such as network basics, server roles, web servers, DNS, load balancing, and monitoring. Through this project, students are expected to design scalable and secure web infrastructures, understand the components involved, and explain their purposes and interactions.

### Concepts
For a comprehensive understanding, students should familiarize themselves with the following concepts:
- Network basics
- Server
- Web server
- DNS
- Load balancer
- Monitoring

## Learning Objectives
Upon completing this project, students should be able to:

- Draw and explain a basic web stack.
- Understand and explain the purpose of each component in a web infrastructure.
- Understand system redundancy and common acronyms like LAMP, SPOF, and QPS.
- Design secure, scalable web infrastructures that serve encrypted traffic and are monitored.

## Requirements
- A README.md file at the root of the project folder is mandatory.
- Diagrams should be included for each task. These can be drawn on a whiteboard, paper, or using software. Screenshots or photos of these diagrams must be included in the project.
- Each task must be whiteboarded without using notes or computer resources, in front of a peer, mentor, or staff member.
- Focus on addressing the specific requirements mentioned in each task. Avoid unnecessary details unless asked.

## Tasks

### 0. Simple Web Stack
Design a one-server web infrastructure that hosts a website accessible via `www.foobar.com`. Components include a server, web server (Nginx), application server, application files, database (MySQL), and a domain name configured to point to the server IP.

### 1. Distributed Web Infrastructure
Expand the simple web stack into a three-server infrastructure adding two more servers, a load balancer (HAproxy), and a set of application files. Explain the role of each new component and discuss the infrastructure's scalability and potential single points of failure (SPOFs).

### 2. Secured and Monitored Web Infrastructure
Enhance the three-server infrastructure to include security and monitoring. Add firewalls, an SSL certificate for HTTPS traffic, and monitoring clients. Discuss the addition of each component, its purpose, and the infrastructure's security and monitoring aspects.

### 3. Scale Up
Further scale the infrastructure by adding another server and configuring HAproxy as a cluster with the existing load balancer. Discuss the reasons for each additional component and the benefits they provide.

## Submission
- For each task, include the screenshot or photo of your diagram in the project folder.
- Write a detailed explanation for each task in the README.md, covering the requirements and your understanding of the infrastructure design.
- Prepare to explain your design and decisions during a whiteboarding session.

## Additional Resources
- [Network basics concept page](#)
- [Server concept page](#)
- [Web server concept page](#)
- [DNS concept page](#)
- [Load balancer concept page](#)
- [Monitoring concept page](#)
- [Application server vs web server](#)

*This project is part of the curriculum of [Holberton School](https://www.holbertonschool.com/). By [Sylvain Kalache](#).*
