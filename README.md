# faraby-eshop
this project is build on .net core app with react as frontend

# Features
1. Product Listing
2. User Accounts
3. Shopping Carts
4. Order Processing
5. Payment Integration

# Technology Stack
1. API: ASP.NET Core 8
2. Frontend: React
3. ORMs: Dapper & EF Core
4. CI/CD: Azure DevOps
5. Server: Windows Server with IIS

# Technology Stack
## React
- UI: react components
- State management: Redux
- Client-side routing: React Router
- HTTP Request: Axios

# Backend Architecture
- DB
    - SQL Server
    - Models
    - Migrations
- Pattern: CQRS with MediatR
    - Command: Dapper
        - insert, update, delete
        - business logic
        - transaction management
    - Query: EF Core
        - read-only query
        - return DTOs
- Service Layer
    - Abstraction layer between controller and Command/Query handler
- Testing
    - Unit test for command/query handler


