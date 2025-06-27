# BrowserStack Testathon

Welcome to the **BrowserStack Testathon** repository!  
This project demonstrates end-to-end automated testing using Java, Selenium WebDriver, Cucumber, and TestNG, fully integrated with BrowserStack’s suite for cross-browser automation, test management, and observability.

---

## Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [BrowserStack Integrations](#browserstack-integrations)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [How to Run Tests](#how-to-run-tests)
- [Test Reporting](#test-reporting)
- [Test Plan](#test-plan)
- [Contributing](#contributing)
- [Resources](#resources)
- [License](#license)

---

## Overview

This repository is prepared for the BrowserStack Testathon, focusing on scalable and maintainable UI test automation. The framework leverages Cucumber for BDD, TestNG for test orchestration, and integrates BrowserStack Automate, Test Management, and Test Observability for a robust cloud-based testing workflow.

---

## Tech Stack

- **Java**  
- **Selenium WebDriver**
- **Cucumber** (Behavior-Driven Development)
- **TestNG** (Test orchestration and reporting)

---

## BrowserStack Integrations

- [BrowserStack Automate](https://www.browserstack.com/docs/automate/): Cloud-based Selenium grid for cross-browser testing.
- [BrowserStack Test Management](https://www.browserstack.com/docs/test-management): Centralized test case and result management.
- [BrowserStack Test Observability](https://www.browserstack.com/docs/test-observability): Real-time analytics and debugging for automated tests.

---

## Getting Started

### Prerequisites

- Java JDK 8 or above installed.
- Maven or Gradle for build automation.
- [BrowserStack Account](https://www.browserstack.com/users/sign_up).
- Access credentials for BrowserStack Automate and API keys.

### Setup

1. **Clone the repository**
    ```sh
    git clone https://github.com/Sumitbhattacharjee252/Browserstack_Testathon.git
    cd Browserstack_Testathon
    ```

2. **Configure BrowserStack Credentials**  
   Set your BrowserStack username and access key in your environment variables or in a config file.

3. **Install dependencies**
    ```sh
    mvn clean install
    ```
    or
    ```sh
    gradle build
    ```

---

## Project Structure

```
src/
 └── test/
     ├── java/
     │    ├── stepdefinitions/
     │    ├── runners/
     │    └── ...
     └── resources/
          ├── features/
          └── testng.xml
```

- **stepdefinitions/**: Cucumber step definitions
- **runners/**: TestNG/Cucumber runners
- **features/**: Gherkin feature files

---

## How to Run Tests

### Using Maven

```sh
mvn test
```

### Using Gradle

```sh
gradle test
```

Tests will run on BrowserStack Automate by default as per configuration.

---

## Test Reporting

- **TestNG Reports**: After execution, reports are generated under `/target/surefire-reports/`.
- **Cucumber Reports**: HTML/JSON reports in `/target/cucumber-reports/`.
- **BrowserStack Test Observability**: Access detailed test analytics and logs in your BrowserStack dashboard.

---

## Test Plan

You can access the latest public test plan here:  
**[Test Plan & Results - [PLACEHOLDER]](PUBLIC_TEST_PLAN_URL_HERE)**  
_Replace the above link with your actual public test plan URL._

---

## Contributing

1. Fork the repository.
2. Create your branch (`git checkout -b feature/my-feature`).
3. Commit your changes.
4. Push to the branch (`git push origin feature/my-feature`).
5. Open a pull request.

---

## Resources

- [BrowserStack Automate Documentation](https://www.browserstack.com/docs/automate/)
- [BrowserStack Test Management Overview](https://www.browserstack.com/docs/test-management)
- [BrowserStack Test Observability](https://www.browserstack.com/docs/test-observability)
- [Cucumber JVM Docs](https://cucumber.io/docs/guides/10-minute-tutorial-java/)
- [TestNG Docs](https://testng.org/doc/)
- [Selenium Docs](https://www.selenium.dev/documentation/)

---

## License

This project is licensed under the MIT License.
