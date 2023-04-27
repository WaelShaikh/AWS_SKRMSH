# SKRMSH: Multiplayer Web-Based Mobile Game

> **Abstract** : This project aims to develop a multiplayer web-based mobile game using AWS. The various services that will be used are EC2, S3 and RDS.

### Project Members
1. SHAIKH WAEL ATIQUE  [ Team Leader ] 
2. THATHERA SEJAL VILAS 
3. SHAIKH RUMSHA TANVEER 
4. SHAIKH MOHAMMAD TALHA MOHAMMAD SALIM 

### Project Guides
    No guides assigned.

### Deployment Steps
Please follow the below steps to run this project.
1. goto aws console.
2. now search for RDS.
3. click on create database.
4. select Standard create.
5. then click free tier.
6. set username and password.
7. click create database
8. database is created.
9. copy the endpoint and goto VPC security group.
10. goto inbound rules and edit the inbound rule.
11. Add two more rule and save it:
12. now goto ec2 instance.
13. select the instance and click on connect.
14. fire some query.
15. now go back to the S3 and make a bucket
16. now go to s3 to store snapshots of the project.
17. click on create bucket and name the bucket..
18. click on the create bucket.
19. unblock all public access and click on edit bucket policy.
20. click on the policy generator and copy arn.
21. select s3 bucket policy and in place of principle put * and action will be get object.and
paste arn address and click on add statement.
22. click on generate policy and copy policy.
23. click on save.
24. now go to objects and upload Images.
25. click on screenshot and click on object url
26. screenshot deploy in a s3 bucket
25. Integrate everything S3,RDS &amp; EC2 instances
26. final deployment of a project. snapshot.

### Subject Details
- Class : TE (COMP) Div A - 2022-2023
- Subject : Skill base Lab Course: Cloud Computing (SKL:CC)
- Project Type : Course Project

### Platform, Libraries and Frameworks used
1. [NodeJS](https://nodejs.org)
2. [PhaserJS](https://phaser.io/)
