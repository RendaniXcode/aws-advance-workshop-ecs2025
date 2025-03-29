# AWS Advanced Workshop: ECS 2025

## Overview

Welcome to the AWS Advanced Workshop for Amazon Elastic Container Service (ECS) 2025! This workshop is designed to take you from beginner to expert in containerization and orchestration using Amazon ECS. You'll learn how to deploy, manage, scale, and optimize containerized applications using AWS's fully managed container orchestration service.

## Prerequisites

- An AWS account
- Basic knowledge of AWS services
- Familiarity with command-line interfaces
- Basic understanding of containerization concepts (helpful but not required)

## Workshop Environment

This workshop utilizes a pre-configured environment with VS Code Server for development. The environment includes:

- Amazon VPC with public and private subnets
- VS Code Server accessible via web browser
- Docker, Git, Node.js, and kubectl pre-installed
- Sample application code (/home/ec2-user/ecs-cats-dogs)
- IAM roles with necessary permissions

## Workshop Modules

### Module 1: Getting Started with Containers and ECS
- Introduction to containerization and Docker
- Understanding Amazon ECS concepts
- Building and running your first container locally
- Pushing containers to Amazon ECR

### Module 2: ECS Fundamentals
- Creating your first ECS cluster
- Understanding task definitions and container configurations
- Launching tasks and services
- Basic service configuration and management

### Module 3: Networking and Load Balancing
- ECS networking models (bridge, host, awsvpc)
- Service discovery options
- Application Load Balancer integration
- Exposing services to the internet

### Module 4: CI/CD for Container Deployments
- Setting up container image pipelines
- Implementing automated deployments to ECS
- Blue/green deployment strategies
- ECS integration with AWS CodePipeline and CodeBuild

### Module 5: Advanced ECS Operations
- Scaling strategies and capacity providers
- Spot instance integration
- Task placement strategies
- Service auto scaling

### Module 6: Monitoring, Logging, and Troubleshooting
- CloudWatch Container Insights
- Centralized logging architecture
- Troubleshooting common ECS issues
- Performance optimization

### Module 7: Security Best Practices
- Task IAM roles and execution roles
- Secrets management
- Network security and VPC endpoints
- Image vulnerability scanning

### Module 8: Advanced Architectures (Expert Level)
- Multi-region deployments
- ECS Anywhere for hybrid workloads
- Event-driven container architectures
- Microservices patterns with ECS

## Getting Started

1. Log in to your AWS account and launch the CloudFormation stack
2. Once the stack is created, locate the VS Code Server URL in the CloudFormation outputs
3. Use the provided password to access the VS Code Server
4. Open a terminal in VS Code and verify that Docker is running with `docker ps`
5. Navigate to the sample application directory: `cd /home/ec2-user/ecs-cats-dogs`

## Sample Applications

This workshop includes a sample "Cats and Dogs" application that demonstrates a multi-container architecture suitable for ECS deployment. The application consists of:

- Frontend web UI
- Backend microservices
- Database tier

## Additional Resources

- [Amazon ECS Documentation](https://docs.aws.amazon.com/ecs/)
- [Docker Documentation](https://docs.docker.com/)
- [AWS CLI Command Reference for ECS](https://docs.aws.amazon.com/cli/latest/reference/ecs/index.html)
- [ECS Workshop GitHub Repository](https://github.com/solminkim/ecs-cats-dogs)

## Support

If you have any questions or issues during the workshop, please contact the workshop facilitator or open an issue in the workshop GitHub repository.

---

&copy; 2025 AWS Advanced Workshop: ECS