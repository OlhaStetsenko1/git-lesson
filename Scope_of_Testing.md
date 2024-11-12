### Scope of Testing

This section defines the boundaries of the testing activities, clearly stating what will be tested and what will not be tested. This helps in setting the right expectations and ensures that all stakeholders are on the same page.

#### In-Scope:
- **Mobile Application**: 
  - Functional testing of all core features such as account management, transactions, and access to various banking services.
  - Compatibility testing on iOS and Android platforms to ensure the application works seamlessly across different devices and OS versions.
  - User interface (UI) and user experience (UX) testing to ensure a smooth and intuitive user experience.

- **Backend API**:
  - Testing of all API endpoints to ensure they function correctly and return the expected responses.
  - Security testing to ensure APIs are protected against common vulnerabilities such as SQL injection and cross-site scripting (XSS).

- **Database**:
  - Data integrity testing to ensure that data is correctly stored, retrieved, and updated.
  - Performance testing to ensure the database can handle the expected load and perform efficiently.

- **User Authentication**:
  - Testing of user registration, login, and logout functionalities.
  - Security testing to ensure that user authentication mechanisms are robust and secure.

- **Payment Gateway**:
  - Functional testing of payment processing, including successful and failed transactions.
  - Security testing to ensure that payment information is handled securely and in compliance with relevant regulations.

- **Notification Service**:
  - Testing of push notifications, email notifications, and SMS notifications to ensure they are sent and received correctly.
  - Performance testing to ensure notifications are delivered in a timely manner.

#### Out-of-Scope:
- **Non-Core Features**: 
  - Testing of features that are planned for future releases and are not part of the current MVP.
  
- **Compatibility Testing**:
  - Testing on platforms other than iOS and Android.

- **Extreme Load Performance Testing**:
  - Performance testing under extreme load conditions beyond the expected usage scenarios.