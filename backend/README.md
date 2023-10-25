# TechOps EduLink Backend

Welcome to the backend directory of the TechOps EduLink project. This directory contains the microservices and configurations that power the backend of our online education platform optimized for low-bandwidth environments.

## Microservices

1. **User Authentication Microservice** (Node.js/Express.js):
   - Provides user registration, login, and authentication features.
   - Source code: `./user-auth/src/`
   - Dockerfile: `./user-auth/Dockerfile`

2. **Content Delivery Microservice** (Nginx):
   - Manages content delivery, caching, and content optimization using Nginx.
   - Configuration file: `./content-delivery/nginx.conf`
   - Dockerfile: `./content-delivery/Dockerfile`

3. **Real-Time Communication Microservice** (Node.js/Express.js):
   - Enables real-time chat and collaboration using WebSockets.
   - Source code: `./real-time-comm/src/`
   - Dockerfile: `./real-time-comm/Dockerfile`

4. **Course Management Microservice** (Django):
   - Handles course creation and management for instructors.
   - Source code: `./course-management/`
   - Dockerfile: `./course-management/Dockerfile`

5. **Progress Tracking Microservice** (Django):
   - Tracks and analyzes individual and overall student progress.
   - Source code: `./progress-tracking/`
   - Dockerfile: `./progress-tracking/Dockerfile`

6. **API Gateway Configuration**:
   - Configures Nginx as the API Gateway for routing and load balancing.
   - Configuration file: `./api-gateway/nginx.conf`
   - Dockerfile: `./api-gateway/Dockerfile`

7. **CDN Nginx Configuration**:
   - Sets up Nginx as the Content Delivery Network (CDN) for optimized content delivery.
   - Configuration file: `./nginx-cdn/cdn.conf`
   - Dockerfile: `./nginx-cdn/Dockerfile`

## Getting Started

To get started with the backend microservices, follow these steps:

1. Clone this repository to your local development environment.

2. Navigate to the desired microservice directory using the terminal, e.g., `cd user-auth`.

3. Review the microservice's README and documentation for specific setup and usage instructions.

4. Build and run the microservice using Docker or other appropriate tools.

5. Repeat the above steps for other microservices as needed.

## Contributing

We welcome contributions from the open-source community. If you'd like to contribute to this project, please follow our [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.
