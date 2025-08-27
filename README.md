# API-gateway
GoFiber-based API Gateway handling authentication and request routing for microservices
It provides authentication, request forwarding, and centralized entry point for microservice communication.

## Features
- JWT Authentication Middleware
- Request forwarding to microservices (User Service, Auth Service, Organization Service)
- Centralized route management
- Configurable service endpoints
- Lightweight and fast (built with GoFiber)

 ## Project Structure
├── config # Configuration (service endpoints, environment variables)
├── handler # Proxy logic for forwarding requests
├── middleware # Authentication middleware
├── routes # API Gateway routes
└── main.go # Entry point

---

## Getting Started

### Prerequisites
- [Go 1.22+](https://go.dev/dl/)
- [MongoDB](https://www.mongodb.com/) (if services require DB)
- Git

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/IT21215438/API-gateway.git
   cd api-gateway
2. Install dependencies
   go mod tidy
3. Run the gateway
   go run main.go


