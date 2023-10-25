# TechOps EduLink Backend

Welcome to the backend directory of the TechOps EduLink project. This directory contains the microservices and configurations that power the backend of our online education platform optimized for low-bandwidth environments.

## Microservices

### User Authentication Microservice (Node.js/Express.js):
- Provides user registration, login, and authentication features.
- **Source Code:** `./backend/user-auth/src/`
- **Tests:** `./backend/user-auth/tests/`
- **Dockerfile:** `./backend/user-auth/Dockerfile`
- **[User Authentication README](./backend/user-auth/README.md)**

### Content Delivery Microservice (Nginx):
- Manages content delivery, caching, and content optimization using Nginx.
- **Configuration:** `./backend/content-delivery/nginx.conf`
- **Dockerfile:** `./backend/content-delivery/Dockerfile`
- **[Content Delivery README](./backend/content-delivery/README.md)**

### Real-Time Communication Microservice (Node.js/Express.js):
- Enables real-time chat and collaboration using WebSockets.
- **Source Code:** `./backend/real-time-comm/src/`
- **Tests:** `./backend/real-time-comm/tests/`
- **Dockerfile:** `./backend/real-time-comm/Dockerfile`
- **[Real-Time Communication README](./backend/real-time-comm/README.md)**

### Course Management Microservice (Django):
- Handles course creation and management for instructors.
- **Source Code:** `./backend/course-management/`
- **Dockerfile:** `./backend/course-management/Dockerfile`
- **[Course Management README](./backend/course-management/README.md)**

### Progress Tracking Microservice (Django):
- Tracks and analyzes individual and overall student progress.
- **Source Code:** `./backend/progress-tracking/`
- **Dockerfile:** `./backend/progress-tracking/Dockerfile`
- **[Progress Tracking README](./backend/progress-tracking/README.md)**

### API Gateway Configuration:
- Configures Nginx as the API Gateway for routing and load balancing.
- **Configuration:** `./backend/api-gateway/nginx.conf`
- **Dockerfile:** `./backend/api-gateway/Dockerfile`
- **[API Gateway README](./backend/api-gateway/README.md)**

### CDN Nginx Configuration:
- Sets up Nginx as the Content Delivery Network (CDN) for optimized content delivery.
- **Configuration:** `./backend/nginx-cdn/cdn.conf`
- **Dockerfile:** `./backend/nginx-cdn/Dockerfile`
- **[CDN Nginx README](./backend/nginx-cdn/README.md)**

## Getting Started

To get started with the backend microservices, follow these steps:

1. Clone this repository to your local development environment.

2. Navigate to the desired microservice directory using the terminal, e.g., `cd backend/user-auth`.

3. Review the microservice's README and documentation for specific setup and usage instructions.

4. Build and run the microservice using Docker or other appropriate tools.

5. Repeat the above steps for other microservices as needed.

## Contributing

We welcome contributions from the open-source community. If you'd like to contribute to this project, please follow our [Contributing Guidelines](../CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.
