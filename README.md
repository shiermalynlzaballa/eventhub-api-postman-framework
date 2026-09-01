# EventHub API QA Automation Framework

API test automation framework built with **Postman, JavaScript, Postman CLI, Git, and GitHub Actions** for validating the EventHub REST API.
Swagger link: https://api.eventhub.rahulshettyacademy.com/api/docs/

## Portfolio

This repository demonstrates a complete API QA automation workflow from test design and scripting through CI/CD execution and reporting.


## Tech Stack

- **API Testing:** Postman
- **Automation:** JavaScript
- **CLI:** Postman CLI
- **CI/CD:** GitHub Actions
- **Version Control:** Git/GitHub
- **Reporting:** JUnit, JSON, HTML

## Key Skills Demonstrated

This project demonstrates practical experience in:

- REST API Testing
- API Test Automation
- Postman
- JavaScript
- Functional Testing
- CRUD Testing
- Authentication & Authorization
- Negative Testing
- Edge-Case Testing
- Data-Driven Testing
- Business Rule Validation
- Postman CLI
- Git
- GitHub
- GitHub Actions
- CI/CD
- Automated Reporting
- Regression Testing
- Defect Identification


## Test Coverage

The framework is based on the EventHub API and includes coverage across multiple API categories.
- Functional & CRUD testing
- Authentication & Authorization
- Negative & Edge Case testing
- Data-driven testing
- Business rule validation
- End-to-end API workflows

## Project Structure

```text
EventHubAPI_Postman_Framework/
├── .github/workflows/
├── postman/
│   ├── collections/
│   └── environments/
├── test-data/
├── reports/
├── .gitignore
├── package.json
└── README.md
```

## Functional Testing

Functional tests validate that API endpoints behave according to the expected business requirements.


## Data-Driven Testing

The framework supports data-driven execution using CSV test data.
Postman iteration variables can then be referenced inside requests and test scripts.

## Defect Management

A dedicated **Bug Reports** collection is included to reproduce, validate, and regression-test identified API defects.

- Defect reproduction and validation
- Expected vs. actual response verification
- Negative test scenarios for known defects
- Regression tests to ensure fixes do not introduce new issues
- Organized bug-specific test cases


## Postman CLI

The framework can be executed locally using Postman CLI.


## CI/CD

The framework is integrated with **GitHub Actions** to automatically execute API tests.

```text
Git Push → GitHub Actions → Postman CLI → API Tests → Reports
```

## Reports

Generated test reports include:

- JUnit
- JSON
- HTML

## Future Enhancements

Planned improvements include:

- Additional API test coverage
- Contract/schema validation
- Allure reporting
- Newman-based execution
- Performance testing with k6
- Dockerized test execution
- Enhanced CI/CD reporting
- Integration with additional test management tools

## Author

**Shiermalyn Zaballa** — Software QA Engineer
