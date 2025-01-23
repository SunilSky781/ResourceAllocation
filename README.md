Resource Allocation Project

Overview This Spring Boot application manages resource allocation based on project skillset requirements.

Prerequisites: Java 17+ PostgreSQL database Maven/Gradle

Setup: Create PostgreSQL database named resourceallocation Update application.properties with your database credentials Run SQL script to populate initial data

Features: Find resources for microservice project Find resources for cloud-based project Flexible skill and experience-based filtering

Endpoints: /api/resources/microservice-project: Returns resources for microservice project /api/resources/cloud-project: Returns resources for cloud project.
