# Selenium WebDriver Automation Framework

A reusable Selenium WebDriver automation framework built using Java and the Page Object Model (POM) design pattern.

## About This Project
This framework was built to automate functional and regression testing of web applications.
It separates test logic from UI interaction for better maintainability and scalability.

## What I Tested
- End-to-end flows including login, registration, product search, cart, and checkout
- Data-driven test scenarios using TestNG DataProvider across multiple input sets
- Cross-browser execution on Chrome and Firefox
- Alerts, frames, dropdowns, multiple windows, file uploads, and synchronization

## Test Reporting
- Integrated ExtentReports for detailed HTML reports with pass/fail status
- Screenshot capture on test failure for easy debugging
- Maven Surefire plugin configured for command-line test execution

## Tools & Technologies
- Java
- Selenium WebDriver
- TestNG
- Maven
- ExtentReports
- Page Object Model (POM)

## How to Run
1. Clone the repository
2. Open in IntelliJ IDEA
3. Run all tests via Maven:
```
mvn test
```

## Author
Sahil Avinash Phirke
