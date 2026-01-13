# Python Microservices on AWS EKS

## Overview
This project demonstrates a production-style microservices architecture deployed on AWS EKS using Docker, Kubernetes, Helm, and RabbitMQ.

## Architecture
- AWS EKS (managed Kubernetes)
- Dockerized Python microservices
- MongoDB & PostgreSQL (via Helm)
- RabbitMQ for async processing
- JWT-based authentication

## Workflow
1. User authenticates and receives JWT
2. Authenticated user uploads a video
3. Video is queued via RabbitMQ
4. Converter service processes the video
5. Output stored and made available for download

## Key Learnings
- Kubernetes networking and service exposure
- IAM roles and AWS permissions
- Helm for managing stateful services
- Asynchronous microservice communication
- End-to-end testing using curl

## Status
Educational / learning project
