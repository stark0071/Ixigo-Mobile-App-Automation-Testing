# Ixigo-Mobile-App-Automation-Testing
Automated UI and functional testing for the Ixigo mobile application using Appium and Java, focusing on validating flight search, booking flow, and filter functionalities.

🧪 Project Overview
This project demonstrates mobile automation testing for the Ixigo Android app, built using industry best practices and automation frameworks.

Key goals:
1.Validate flight search and filter logic
2.Automate booking flows with real-time data
3.Implement a maintainable and reusable test framework
4.Generate structured test reports and logs

| Tool                           | Purpose                            |
| ------------------------------ | ---------------------------------- |
| Java                           | Test logic and framework code      |
| Appium                         | Android app automation             |
| TestNG                         | Test execution and assertions      |
| Maven                          | Build management                   |
| Extent Reports                 | Reporting and test result analysis |
| Android Emulator / Real Device | Testing Environment                |


🧩 Features Automated
 1.Launch Ixigo App
 2.Search Flights with Date & City inputs
 3.Apply filters (non-stop, airline, etc.)
 4.Validate flight result consistency
 5.Booking screen navigation
 6.Error handling for invalid inputs
 7.Screenshot capture on test failure

 🏗️ Framework Design
1.Page Object Model (POM) for clean code organization
2.Data-Driven Testing using external test data
3.Modular helper utilities for reusable components
4.Supports parallel execution and device configuration

IxigoAppAutomation/
│
├── src/test/java/
│   ├── base/               # Driver setup and hooks
│   ├── pages/              # Page objects
│   ├── tests/              # Test classes
│   ├── utils/              # Helpers (waits, logs, etc.)
│
├── testng.xml              # Test suite definition
├── pom.xml                 # Maven configuration
├── screenshots/            # Failure screenshots
├── reports/                # Extent reports


🚀 How to Run
Clone the repository
Install dependencies via mvn clean install
Connect emulator or device
Run test suite using:

bash
mvn test
View reports in /reports/index.html

