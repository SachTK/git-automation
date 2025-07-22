# 🚚 GIT Automation-Fleet Management System - Automated Test Suite

This repository contains the automated test scripts for the **Fleet Management System**, built using the **JTS Automation Framework Template**. The suite automates end-to-end functional testing of core features such as vehicle tracking, driver management, route monitoring, and more.

---

## 🧰 Tech Stack

| Tool/Framework       | Description                                          |
|----------------------|------------------------------------------------------|
| Java                 | Core programming language                            |
| Selenium WebDriver   | Browser-based UI automation                          |
| TestNG               | Test orchestration and assertions                    |
| Maven                | Build automation and dependency management           |
| ExtentReports        | Advanced HTML test reporting with screenshots        |
| Apache POI           | Reading test data and XPaths from Excel              |
| Property File Reader | Centralized configuration and test data management   |
| Chrome/Firefox/Edge  | Cross-browser testing support                        |

---


---

## ✅ Key Features of the Automation Suite

- 🔁 **Reusable Web Steps** for scalable and consistent interactions
- 📊 **Excel-Driven XPath Management** for centralized object storage
- 🧪 **TestNG Suite Support** with grouping, parallel execution, and filtering
- 🌐 **Cross-Browser Compatibility** with support for Chrome, Firefox, and Edge
- 📄 **Interactive Reporting** via ExtentReports including screenshots
- 🔐 **Secure Config Management** using external property files
- 🧼 **OOP-based Page Objects** for maintainable code design

---

## 🧪 How to Run the Tests

### Prerequisites

- Java 11+
- Maven 3.6+
- Chrome / Firefox / Edge browser installed

### Execution Steps

```bash
# Clone the repository
git clone https://github.com/Sachintha-Samarathunga/GIT-Fleet-Management-New.git
cd fleet-automation

# Install dependencies
mvn clean install

# Run tests on default browser (set in config.properties)
mvn test

# Run tests on a specific browser
mvn test -Dbrowser=firefox
mvn test -Dbrowser=edge
```
