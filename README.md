# Class 16 Notes

Storage Cloud
- When I change the file
  - computer tells the server that there is a change
  - server knows this and downloads it

CDN - Content Delivery Network
- When a user wants to grab something, that data has to travel across to that user and carries a cost. 
- I want some file:
  - Has it changed? If not changed:
    - If I have the file near me:
      - you get the data quickly
      - not expensive and not alot on your computer
    - If not:
      - travels across wherever. 
  - Has changed:
    - give me the file and that local copy will be updated.
- can also be databases
- can also be servers. Have an express server and can be copied to servers in different parts of the world.
- Cloud **saves time and money**

- Eventual Consistency
  - 1000 copies of databases, everything can be the same eventually but not in real time. 
  

TimeStamp : 23:09

AWS Amplify - service that lets you deploy REACT apps.

API Gateway - make routes and name them

ie /cache route that is called GET
ie /content POST

Lambda - written code that runs getCodeChallenge

**THIS LAB**

Amazon EC2 - Amazon Elastic Compute Cloud
- instance of a linux server

Amazon Elastic Beanstalk - End-to-end web application management.
  - its an easy-to-use service for deploying and scaling web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby, Go, and Docker.
