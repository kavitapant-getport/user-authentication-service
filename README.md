# user-authentication-service
A microservice responsible for handling user authentication, authorization, and session management for Walmart's e-commerce platform.

## Features
- JWT token-based authentication
- Role-based access control (RBAC)
- OAuth integration with Google, Facebook, Apple
- Multi-factor authentication support
- Session management with Redis
- Rate limiting and brute force protection

## Tech Stack
- **Runtime**: Node.js 18+
- **Framework**: Express.js
- **Database**: MongoDB
- **Cache**: Redis
- **Authentication**: JWT + OAuth 2.0

## API Endpoints
- `POST /auth/login` - User login
- `POST /auth/register` - User registration  
- `GET /auth/profile` - Get user profile
- `POST /auth/logout` - User logout
- `POST /auth/refresh` - Refresh JWT token

## Environment Configuration
- **Development**: https://dev-auth.walmart.com
- **Staging**: https://staging-auth.walmart.com  
- **Production**: https://auth.walmart.com

## Monitoring & Health
- Health check endpoint: `GET /health`
- Metrics endpoint: `GET /metrics`
- Current uptime: 99.9%

## Team
- **Owner**: Platform Authentication Team
- **On-call**: DevOps Team Alpha
- **Slack**: #auth-service-support
