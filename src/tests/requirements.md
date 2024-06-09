Enterprise Test Automation Framework for AUT (Salesforce)

1. Overview
The enterprise test automation framework is designed to provide a robust, scalable and feature rich solution for automated testing of the Salesforce application (AUT). The Framework encompasses various feature, including data-driven tesing, logging, retry mechanism, self-healing, cross browser testing, multiple environments, password encryption, code quality, CI/CD integration, reusable utilities, data generation, parallel testing, and API mocking/ testing

2. Features
2.1 Page Object Model (POM) Implementation
 
 - Objective: Apply POM principle to structure the code and make resuable & maintainable code.

2.2 Data-Driven Testing
- Objective: Enchance test coverage by parameterizing tests with external data.

2. Logging
- Objective :Provide comprehensive logs for detailed test execution analysis.

2.4 Retry Mechanism
- Objective: Handle intermittent failures gracefully with automatic retries.

2.5 Self Healing
- Objective: Adapt to dynamic changes in the Salesforce application to minimize maintainance efforts

2.6 Multiple Environments
- Objective: Support testing in various environment (Ex: sandbox, developer edition, production).

2.7 Cross-Browser Testing
- Objective: Validate application functionality across different browsers

2.8 Password Encryption
- Objective: Securely manage and use passwords in test scenarios.

2.9 Code Quality
- Objective: Enforce coding standards and maintain high quality code

2.10 CI/CD Integration
- Objective: Seamlessly integrate the framework with CI/CD pipelines

2.11 Re-usable Utilities
- Objective: Develop modular and reusable utilities to optimize code maintenance

2.12 Data Generation
- Objective: Generate test data dynamically to ensure diverse test Scenario

2.1 Parallel Testing
- Objective : Execute tests concurrently for faster feedback and optimized test suite execution

2.14 API Mocking/ Testing
- Objective : Mock and test Salesforce APIs to validate backend functionality.

3. Test Scenarios (Sample)

3.1 Page Object Model Class and basic Test

Scanario: Verify creation of page class for login page and create basic test.

Steps: 
1. Create POM Class for login page.
2. Create Tests using Page class and its methods to login.
  - Log in to Salesforce
  - Verify the success of Login

3.2 Data Driven Testing

Scenario: Verify creation of Salesforce records using different sets of data.

Steps: 
1. Retrive test data from an external source.
2. For each set of data: 
 
