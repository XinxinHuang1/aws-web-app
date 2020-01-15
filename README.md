
## Project Description 
Spring Boot RESTful API Runs on AWS 

## Technology Stack
Linux environment
Shell Script
Spring Framework
Tomcat
REST
Java 
MySQL
JDBC
JSON
IntelliJ
Postman
Git
AWS(CloudFormation EC2 S3 Lambda ELB DynamoDB )
CircleCI

## Build Instructions
User class: user attributes
UserRepository class: get, select, update, delete users
UserService class: the main controller
BCrypt class: downloaded from "http://www.mindrot.org/projects/jBCrypt/", store password securely
Token creation: encoded from user's email and password

## Deploy Instructions
Deploy the application locally on Tomcat

Deploy on AWS 
"$bash csye6225-aws-cf-create-policy.sh"
"$bash csye6225-aws-cf-create-stack.sh"
"$bash csye6225-aws-cf-create-auto-scaling-application-stack.sh"

## Running Tests
Since we only developed the backend, we used Postman to test the functions.

## CI/CD



