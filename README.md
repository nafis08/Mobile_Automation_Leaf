# Mobile_Automation_Leaf

This project contains automated test scripts for the LeafOrg mobile application using **Appium** and **TestNG**. The test suite is designed to validate key user workflows such as authentication, support requests, and app configuration updates.

## Features Tested

- Login and Logout
- Forgot Password
- Change Password
- Contact Support
- Update Batches and Configuration
- General Application Navigation

## Tech Stack

- **Language:** Java
- **Test Framework:** TestNG
- **Automation Tool:** Appium
- **Build Tool:** Maven
- **CI/CD:** GitHub Actions

## Project Structure
```
src/
└── test/
├── java/
│ ├── app_installer/ # Contains APK file for testing
│ ├── leaforg_automation/ # Main test scripts
│ └── TestUtils/ # Utility classes for test data and reporting
.github/
└── workflows/
└── main.yml # GitHub Actions CI pipeline
```

## ⚙️ Getting Started

### Prerequisites

- Java JDK 8 or higher
- Android Studio / Emulator / Physical Device
- Appium Server
- Maven
- Node.js (for Appium)
- Git

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nafis08/Mobile_Automation_Leaf.git
   cd Mobile_Automation_Leaf
   ```
## Install dependencies:
```
mvn clean install
```
## Configure Appium:
- Ensure Appium server is running on default 127.0.0.1:4723.
- Update device capabilities in ConfigurationAppium.java if necessary.

## Run tests:
```
mvn test
```
## Test Execution
TestNG is used for orchestrating and reporting test runs. The "testng.xml" file controls which test classes are executed and in what order.
