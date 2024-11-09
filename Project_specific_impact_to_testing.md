### Project Specific Impact to Testing

This section outlines the key factors specific to the project that may influence the testing process, both positively and negatively. It serves as a reusable reminder to address potential risks and limitations effectively.

#### Project Phase
**Minimum Viable Product (MVP)**

The project is currently in the MVP phase, which means the focus is on delivering a product with the minimum set of features necessary to satisfy early adopters and gather feedback for future development.

#### Technology Stack
* **Frontend**: Angular
* **Backend**: Spring Boot (Java)
* **Database**: MySQL
* **APIs**: RESTful APIs
* **DevOps Tools**: Jenkins, Docker, Kubernetes
* **Testing Tools**: Selenium, JUnit, Postman, JMeter

#### Constraints & Assumptions
**Constraints**:
* Limited budget for additional testing tools and resources.
* Test environments are shared with other projects, leading to potential availability issues.
* Regulatory compliance requirements must be met, adding additional testing overhead.

**Assumptions**:
* Requirements will remain stable throughout the testing phase.
* Test data will be provided by the development team and will be sufficient for all test cases.
* Test environments will be configured and ready before the start of the testing phase.

#### Critical Success Factors
* High-quality deliverables with no critical defects.
* Completion of all testing activities within the scheduled timeline.
* Positive feedback from early adopters during User Acceptance Testing (UAT).
* Meeting performance benchmarks, including response time under load and system stability.
* Ensuring compliance with all relevant regulatory requirements.

#### Time Zones
**Team Locations**:
* Developers in the United States (Eastern Time Zone, ET)
* Testers in India (Indian Standard Time, IST)
* Stakeholders in the United Kingdom (Greenwich Mean Time, GMT)

**Overlap Hours**:
* 9 AM - 12 PM ET / 6:30 PM - 9:30 PM IST / 2 PM - 5 PM GMT

**Meeting Schedules**:
* Weekly status meetings scheduled at 10 AM ET / 7:30 PM IST / 3 PM GMT

**Continuous Integration**:
* Builds are triggered at 8 AM ET to ensure availability for both US and UK teams, with automated tests running overnight to accommodate IST team review in the morning.