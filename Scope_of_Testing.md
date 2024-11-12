### Scope of Testing

The scope of testing includes the following key points:

1. **In-Scope Systems/Components/Interfaces**:
   - Clearly define which systems, components, and interfaces are included in the scope of this document.

2. **Out-of-Scope Systems/Components/Interfaces**:
   - Clearly define what is not included in the scope of this document.

3. **Third-Party Systems**:
   - Define the third-party systems involved and specify who is responsible for their testing.

4. **External Testing Responsibilities**:
   - Define which parts of the system will be tested by other organizations and are therefore out of scope for this document.

For each component, the responsible side for execution and final result review will be defined in the table below:

| System/Component/Interface | Description | Responsible Side |
|----------------------------|-------------|------------------|
| Frontend Application       | Angular-based web application for user interaction. | Development Team |
| Backend API                | Spring Boot-based RESTful API for business logic and data processing. | Development Team |
| Database                   | MySQL database for storing application data. | Database Team |
| User Authentication        | OAuth2-based authentication system for user login and access control. | Security Team |
| Payment Gateway            | Integration with Stripe for processing payments. | Development Team |
| Notification Service       | Service for sending email and SMS notifications. | Development Team |
| CI/CD Pipeline             | Jenkins-based continuous integration and deployment pipeline. | DevOps Team |