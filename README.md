<<<<<<< HEAD
## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


=======
# CI/CD Integration for Docker & Kubernetes via Jenkins


## Project Overview
This project demonstrates the implementation of a Continuous Integration and Continuous Delivery (CI/CD) pipeline using Jenkins, Docker, Kubernetes, and Helm. The pipeline is designed to automate the entire process of building, testing, and deploying applications in a Kubernetes environment, ensuring a streamlined and efficient workflow from code integration to production deployment.


### Key Technologies
Jenkins: Used to orchestrate the CI/CD pipeline, managing the various stages of code integration, testing, and deployment.
Docker: Employed to containerize the applications, ensuring consistency and reliability across different environments.
Kubernetes: Acts as the orchestration platform, managing the deployment, scaling, and operation of containerized applications.
Helm: Utilized to simplify the deployment and management of Kubernetes applications through templated configuration files.
>>>>>>> d6a45a927fac484e06cf54e8453bb23e5327f9f4
