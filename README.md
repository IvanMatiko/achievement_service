# Achievement Service

## Overview
Achievement Service is a backend application for managing user achievements within a system. It provides APIs for creating, assigning, and tracking achievements, enabling gamification and user engagement through reward systems.

## Features
- **Achievement Management:** Create, update, and delete achievements.
- **User Achievements:** Assign achievements to users and track their progress.
- **Progress Tracking:** Monitor and update user progress towards achievements.
- **Integration:** APIs designed for seamless integration with other services.
- **Swagger Documentation:** Built-in API documentation for easy development.

## Getting Started

### Prerequisites
- Java 11+
- Docker (optional for containerized deployment)
- Gradle

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/IvanMatiko/achievement_service.git
   cd achievement_service
2. Build the project:

   ./gradlew build

3. Run the application:

   ./gradlew bootRun

# API Endpoints

POST /achievements: Create a new achievement.

GET /achievements: Retrieve a list of achievements.

GET /achievements/{id}: Get details of a specific achievement.

PUT /achievements/{id}: Update an achievement.

DELETE /achievements/{id}: Delete an achievement.

POST /achievements/{id}/assign: Assign an achievement to a user.

# Technologies Used

Java: Core programming language.

Spring Boot: Framework for backend service development.

Redis : cache and broker message

Gradle: Build and dependency management tool.

Swagger: API documentation.

Docker: For containerized deployment

Testcontainers: for integration tests
