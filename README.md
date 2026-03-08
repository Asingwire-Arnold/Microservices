# Microservices
## Name
Asingwire Arnold
## Course
BSCS 2:2
## Registration Number
S24B23/013

## Introduction
Microservices architecture is a software design approach where an application is built as a collection of small, independent services. Each service performs a specific function and communicates with other services through APIs. This architecture helps large systems become more scalable, flexible, and easier to maintain.

### How Netflix Uses Microservices
### 1. User Account Management
Netflix uses a dedicated microservice to manage user accounts. This service handles user registration, login authentication, profile management, and subscription information.

### 2. Content Recommendation System
Netflix has a recommendation microservice that analyzes user viewing history, ratings, and preferences to suggest movies and TV shows.

### 3. Video Streaming and Content Delivery
Netflix uses microservices to manage video streaming and content delivery. These services handle tasks such as video encoding, buffering, and playback.

### 4. Search Functionality
Netflix also uses a search microservice that allows users to find movies, shows, and genres quickly. This service processes search queries and retrieves results from the content database.

## Companies That Reconsidered Microservices
### 1. Amazon (Some Internal Teams)

Although Amazon used microservices, some internal teams later realized that using too many small services created difficulties. These included complex system management, difficulty in debugging across multiple services, and high infrastructure costs. As a result, Amazon moved back to monoliths to simplify development.

### 2. Segment

Segment, a customer data platform, initially moved from a monolithic architecture to microservices but later reduced the number of services. The challenges they faced included large number of services becoming difficult to manage, and harder monitoring and troubleshooting. As a result, Segment combined several microservices into larger services, creating a **hybrid architecture**.
