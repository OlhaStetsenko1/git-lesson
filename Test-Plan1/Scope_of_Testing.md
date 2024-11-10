### Scope of Testing

This section defines the boundaries of testing activities for the e-commerce platform MVP.

#### In-Scope Items
The following systems, components, and interfaces will be tested:

| System/Component/Interface | Description | Responsible Side |
|----------------------------|-------------|------------------|
| Frontend Application       | Angular-based web application for user interaction. | Development Team |
| Backend API                | Spring Boot-based RESTful API for business logic and data processing. | Development Team |
| Database                   | MySQL database for storing application data. | Database Team |
| User Authentication        | OAuth2-based authentication system for user login and access control. | Security Team |
| Payment Gateway            | Integration with Stripe for processing payments. | Development Team |
| Notification Service       | Service for sending email and SMS notifications. | Development Team |
| CI/CD Pipeline             | Jenkins-based continuous integration and deployment pipeline. | DevOps Team |

#### Out-of-Scope Items
The following items will not be tested:

- Third-party services not directly integrated with the platform.
- Non-core functionalities that are planned for future releases.

#### Testing Levels
- Unit Testing: Testing individual components and functions.
- Integration Testing: Testing interactions between integrated components.
- System Testing: Testing the complete and integrated software system.
- Acceptance Testing: Testing the system against user requirements and business needs.

#### Testing Types
- Functional Testing: Ensuring the system performs its intended functions.
- Non-Functional Testing:
  - Performance Testing: Assessing the system's performance under various conditions.
  - Security Testing: Ensuring the system is secure from vulnerabilities.
  - Usability Testing: Evaluating the user experience and interface.
