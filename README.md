# Magento Selenium TestNG POM

![Selenium](https://img.shields.io/badge/Selenium-Automation-green) ![TestNG](https://img.shields.io/badge/TestNG-Testing-blue) ![Maven](https://img.shields.io/badge/Maven-Build-orange)

Magento Selenium TestNG POM is a test automation framework for Magento applications using **Selenium WebDriver**, **TestNG**, and **Page Object Model (POM)**. This framework is designed for efficient UI testing with structured test cases and easy scalability.

---

## 🚀 Features
- 🔹 **Selenium WebDriver** for UI automation
- 🔹 **TestNG** for test execution and reporting
- 🔹 **Page Object Model (POM)** for maintainable test scripts
- 🔹 **Maven** for dependency management
- 🔹 **Assertions & Validations** for robust test verification
- 🔹 **Logging & Extent Reporting** for test insights

---

## 📂 Project Structure
![Project Structure](https://raw.githubusercontent.com/rahmannazneen/magent-selenium-testng-pom/main/images/project-structure.png)
```
magento-selenium-testng-pom/
├── src/
│   ├── main/java/pages/        # Page classes
│   ├── main/java/utils/        # Utility functions
│   ├── test/java/tests/        # Test cases
│   ├── test/java/base/         # Base test class
│   ├── resources/              # Configuration files
├── pom.xml                     # Maven dependencies
├── testng.xml                  # TestNG test suite configuration
```

---

## 🛠 Prerequisites
Ensure you have the following installed:
- **Java (JDK 8+)**
- **Maven**
- **Selenium WebDriver**
- **TestNG Plugin** (for IntelliJ/Eclipse)
- **Magento test environment**

---

## 🏗 Installation & Setup
### Clone the repository:
```sh
git clone https://github.com/rahmannazneen/magent-selenium-testng-pom.git
cd magent-selenium-testng-pom
```
### Install dependencies:
```sh
mvn clean install
```
### Configure Test Data:
- Update `config.properties` with Magento test credentials.

---

## 🏃 Running Tests
![Test Execution](https://raw.githubusercontent.com/rahmannazneen/magent-selenium-testng-pom/main/images/test-execution.png)
### Run all tests:
```sh
mvn test
```
### Run a specific test class:
```sh
mvn -Dtest=TestClassName test
```
### Run tests via TestNG XML:
```sh
mvn test -DsuiteXmlFile=testng.xml
```

---

## 📊 Test Reports
![Test Reports](https://raw.githubusercontent.com/rahmannazneen/magent-selenium-testng-pom/main/images/test-reports.png)
- **TestNG Report:** Available in `target/surefire-reports`
- **Extent Report:** Available in `target/extent-reports`

---

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit changes (`git commit -m "Your message"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 👩‍💻 Author
[rahmannazneen](https://github.com/rahmannazneen)

---

## 📸 Screenshots
### Sample Test Execution
![Test Execution Screenshot](https://raw.githubusercontent.com/rahmannazneen/magent-selenium-testng-pom/main/images/test-execution-screenshot.png)

### Extent Report Example
![Extent Report](https://raw.githubusercontent.com/rahmannazneen/magent-selenium-testng-pom/main/images/extent-report-example.png)
