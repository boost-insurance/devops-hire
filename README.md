# Boost Insurance DevOps Team TryOut!
Welcome to the try-outs to join the Boost Insurance's DevOps team. 

This try out is broken into to two challenges. Inside each of the challenges you will find
instructions on what needs to be done. 

You will fork this repo and make it private. Then add the following people as collaborators 
to it:
 - moos3
 - mark-boost
 
Once your completed the work. We will pull it down, run it and test it. Your code
needs to work and function. If we can't call a alb and get a random quote back then it 
doesn't work and should be served over https.

## Backstory on our Infrastructure
So our infrastructure is in AWS and GCP. We are 100% controlled by Pulumi. We do not apply any changes 
by hand in environments now except some database commands. Our stack looks like the following:
 - EKS
 - PostgresSQL
 - Python / Golang
 - Lambda
 - Cognito
 - S3

## Goals

The team goals in reviewing this exercise with you are as follows:

1. Evaluate your ability to understand and write basic application code (python/golang preferred)
1. Evaluate your ability to understand and help build a good developer experience
1. Show knowledge of both development and production concerns surrounding microservices and containerized applications
1. Show a basic understanding of Kubernetes resources and declarative infrastructure
1. Show knowledge of what questions and concerns to raise to a product development team or your own teammates in developing and releasing a service
1. See how you would work with us as a team in a normal task-based scenario.


## Deliverables

While all candidates have some different goals, we expect to see the following items completed before our interview:

1. A link to your forked repository that you'd like us to review
1. Documentation in the Git repository on how to run the application for local development
1. A production-ready Dockerfile we could build and deploy to a Kubernetes cluster using the helm chart provided

If you'd like to do so and have time, we'd love to see any of the following:

1. If you choose to need resources outside of Kubernetes, a snippet of pulumi code that describes the resource(s)
1. Create an endpoint in the app that does something of your choosing to demonstrate basic golang / python abilities and ability
   to quickly understand a small piece of a web framework. Perhaps it can show the current time, or something similar.

## What to Expect

While working on this challenge, you are welcome to email us for any clarification or requirement questions you have. Our recruiter
will let you know who to talk to during this process if you have any questions.

During the interview we will review your work, go through the PR as we would any code review, and discuss
the decisions you made and fixes you chose to implement, as well as any additional concerns you have. Be prepared to also discuss
CI/CD for the app, though we do not expect you to build anything for this.

*We only expect you to spend a few of hours on this.* You're welcome to do as much as you'd like to do,
but it's not our intention to take up days of your time. If there are things you don't have the time to fix,
please be prepared to talk us through them at the interview. We want you to showcase that you have the knowledge and skills
to help product development teams build, containerize, deploy, and release their apps in the cloud.