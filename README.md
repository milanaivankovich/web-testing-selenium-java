# Student Management System – Selenium Automation

This repository contains a comprehensive suite of automated end-to-end tests for a Student Management Web Application. The project demonstrates the implementation of a functional testing framework using **Java**, **Selenium WebDriver**, and **JUnit** to ensure the reliability of critical user workflows.

## 🚀 Project Overview

The primary goal of this project is to automate the validation of CRUD (Create, Read, Update, Delete) operations and edge-case handling within a dynamic web environment.

### **Automated Workflows:**

* **Student Registration**: Validating the full process of adding new records to the database.
* **Data Integrity Updates**: Testing the modification of existing student records and ensuring changes persist across the UI.
* **Record Deletion**: Verifying that the application correctly removes data and updates the UI row count dynamically.
* **Validation & Error Handling**:
* **Negative Testing**: Ensuring the system correctly identifies and rejects invalid data formats.
* **Empty States**: Verifying application behavior when no data is present in tables.



## 🛠 Tech Stack

* **Automation Tool**: Selenium WebDriver (Chrome/Firefox)
* **Language**: Java
* **Test Framework**: JUnit 4
* **Build Tool**: Maven (`pom.xml`)
* **Scripting**: JavaScript Execution for dynamic DOM verification (e.g., row counting)

## 🧪 Advanced Automation Techniques

* **Dynamic Synchronization**: Implementation of `WebDriverWait` and `ExpectedConditions` to handle asynchronous web elements and ensure test stability.
* **DOM Interaction**: Using `JavascriptExecutor` to perform advanced validations that standard Selenium commands cannot, such as verifying table lengths directly from the document.
* **User Action Simulation**: Utilizing the `Actions` class to simulate mouse movements and complex user interactions.

## 🏁 Getting Started

1. **Clone the repository**:
```bash
git clone https://github.com/milanaivankovich/web-testing-selenium-java.git

```


2. **Environment Setup**:
* Ensure Java JDK 11+ is installed.
* Install Chrome/Firefox and the respective WebDrivers.
* The tests are configured to run against a local instance (default: `http://localhost:4200`).


3. **Run Tests**:
```bash
mvn test

```
