# Challenge 1

You will create a complete infrastructure with a pipeline to build the application. When you write out the code
use Pulumi in either GO or Python. 

### Requirements
In this challenge you will need to do the following things:
- Create a AWS infrastructure that must contain the following
  - EKS + ALB's
  - ACM Certificates
  - ECR Repo
  - Route53 Zone and domain
- github action to build the application in the `app/` directory
  - must run in a container
  - must push to ECR
- Deployment to EKS via helm

### MUSTS
- Local configuration file
  - Need to be able to set AWS ACCOUNT ID
  - DNS name with SSL

This has the free rein on how you implement this. This is to see how you think, this will be the building blocks
for challenge 2.
