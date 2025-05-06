# QA Technical Challenge – E2E Testing with Cypress, BDD & CI/CD

[< back to README](./README.md)

The Dynamox QA team invites you to complete the following QA-focused technical challenge, centered on implementing end-to-end tests using Cypress with a BDD (Behavior-Driven Development) approach. Additionally, you are required to integrate your tests with a CI/CD pipeline to ensure automated test execution on every push or pull request.

This challenge simulates a real testing environment and evaluates your ability to write meaningful, structured, and maintainable automated test scenarios for a React-based data visualization dashboard. The goal is to showcase your ability to ensure software quality through automated testing and to integrate the process with CI/CD pipelines for continuous validation.

You will run your tests against the following URL to validate the behavior of the application:

Web URL: https://dynamox-challenge-web-link.com

---

## Objective

Develop an automated testing suite that validates the main functional flows and interface behaviors of a sensor data dashboard application, according to the user stories and technical specifications provided below.

Your implementation should demonstrate:

* Strong understanding of QA processes in an Agile environment
* Proficiency with Cypress and BDD syntax (using tools like cypress-cucumber-preprocessor)
* Ability to structure tests based on business requirements and expected user behaviors
* CI/CD integration for automated test execution, ensuring tests are automatically run with each code change.

## Tools & Technologies
You must use the following tools for your implementation:

1. [ ] Cypress (for end-to-end testing)
1. [ ] Cypress + Cucumber (to write tests using BDD syntax – Gherkin)
1. [ ] CI/CD tool of your choice: GitHub Actions (preferred), GitLab CI, CircleCI, etc. for continuous integration and deployment
1. [ ] Git/GitHub for version control and submission

Bonus points if you also:

1. [ ] Add visual regression testing
1. [ ] Add advanced parallelization to your CI setup
1. [ ] Include test report generation (e.g., Allure, Mochawesome, Cypress Dashboard)

---

## User Stories (to test)
These user stories must be translated into test scenarios using the Given/When/Then format in .feature files.

Route Access & UI Load
1. [ ] As a user, I want to access the /data route and see a screen with a header and charts about machine data.
Chart Rendering
1. [ ] As a user, I want to see 3 time-series charts: acceleration, velocity, and temperature, each with correct axes.
Dynamic Data Fetch
1. [ ] As a user, I want data to be fetched every time I access /data, using the mock API.
Crosshair & Tooltip Sync
1. [ ] As a user, I want to hover over a chart point and see a synchronized vertical crosshair across all charts with tooltips.

## Test Plan & Deliverables
You should structure your QA solution with the following:

1. **Test Suite**:
  * cypress/ folder containing:
    * integration/ or e2e/ folder with .feature files and step definitions
    * Organized test cases reflecting the user stories
    * Clear naming conventions for specs

2. **CI/CD Integration**:

* Implement a CI/CD pipeline using your chosen tool (e.g., GitHub Actions) that:
    * Installs dependencies
    * Runs the Cypress test suite on every push to the repository or pull request
    * Optionally, generates test reports for easy feedback (e.g., Mochawesome or Allure reports)

3. **Documentation**:

* `README.md` should include:
  * Instructions for setting up and running the tests locally
  * Instructions for running the tests with CI/CD setup
  * Summary of test coverage and scenarios

## 🧑‍⚖️ Evaluation Criteria (continued)

Your submission will be evaluated based on the following additional criteria:

| Criterion                            | Expectation                                                       |
|--------------------------------------|-------------------------------------------------------------------|
| **Test Completeness**                | All user stories should be fully covered by automated tests       |
| **Test Accuracy**                    | Tests should accurately reflect the expected behavior of the application |
| **Test Performance**                 | Tests should be executed quickly and efficiently without unnecessary delays |
| **Flakiness**                        | Tests should not fail intermittently (no flaky tests)             |
| **CI/CD Pipeline Efficiency**       | The CI/CD pipeline should be well-configured to run tests on every code change, pull request, and deployment |
| **Error Handling**                  | Tests should account for possible error scenarios and edge cases in the application |
| **Test Data Management**            | Proper use of mock data and resetting state between test runs     |
| **Cross-Browser Testing**           | The application should be verified across common browsers (Chrome, Firefox, Safari, etc.) |
| **Mobile Compatibility Testing**    | Ensure mobile responsiveness and compatibility (if applicable)   |
| **Clear Test Reporting**            | Test results should be clearly reported with useful logs and actionable feedback |
| **Test Documentation**              | Tests should be clearly documented, making it easy for other QA engineers to extend and maintain them |
| **Code Organization & Modularity**  | Tests should be modular, reusable, and follow best practices for organization |

---

## Ready to Begin the Challenges?

* Fork this repository to your own Github account.
* Create a new branch using your first name and last name. For example: `caroline-oliveira`.
* After completing the challenge, create a pull request to this repository (https://github.com/dynamox-s-a/js-ts-full-stack-test) pointing to the main branch.
* We will receive a notification about your pull request, review your solution and get in touch with you.
<br>

**Good luck! We look forward to reviewing your submission.** 🚀

## Frequently Asked Questions

* Is it necessary to fork the original repo?
  **Yes, for us to track your changes and time spent.**

* Can I make assumptions if something isn't clear?
  **Yes, feel free to use your judgment. Just make sure to document any assumptions clearly.**

* Who do I contact if I have questions?
  **Email: giovanna.shinhe@dynamox.net (QA)**



