# Magento Selenium TestNG POM

![Selenium](https://img.shields.io/badge/Selenium-Automation-green) ![TestNG](https://img.shields.io/badge/TestNG-Testing-blue) ![Maven](https://img.shields.io/badge/Maven-Build-orange)

This project is an automation framework for testing Magento applications using Selenium WebDriver, TestNG, and the Page Object Model (POM) design pattern. The framework ensures efficient and maintainable test automation for web applications.

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

- **TestNG Report:** Available in `target/surefire-reports`
- **Extent Report:** Available in `target/extent-reports`

---
## 🎯 Future Enhancements
Add Parallel Execution support
Integrate with CI/CD pipelines (Jenkins/GitHub Actions)
Implement Cross-browser testing

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
