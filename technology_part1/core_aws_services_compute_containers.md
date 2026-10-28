# Container with ECS and EKS

## What are containers
- a tool that allows you to package an application and all necessary files, libraries, and dependencies the application needs to run
- small lightweight versions of vertual machines

## Challenges
- need deploy across multiple hosts to make it resilient
- need to move container when host goes down
- containers need to scale up or down when traffic changes

## Orchestrators
- deploys across all servers
- load-balancing requests to containers

## ECS (Elastic Container Service)
- just the brains and managed by AWS
- containers run on EC2 instances or Fargate
- only available on AWS

## Kubernetes
- open-source container orchestrator
- has two types of nodes
- control-plane nodes manage the cluster
- worker nodes responsible for actually running the containerized workloads

## EKS (Elastic Kubernetes Service)
- Users are responsible for managing both the control-plane and worker nodes
- managing control-plane/master nodes is diffcult
- manages the control place for you, but worker nodes are still the users responsibility
- unless they decide to use fargate

# ECS vs EKS
- ECS is unique to AWS
- EKS is open source
- ECS has a simpler architecture
- Kubernetes is very complex and has a steep learning curve
- ECS is cheaper