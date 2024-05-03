# Demo-Netbanking-Project --> Automated Web Testing with Selenium, Java, and TestNG
**Overview**
This repository contains a comprehensive automated testing framework for a demo netbanking website. The project aims to validate critical functionalities such as user login, customer addition, customer details editing, and customer deletion. By leveraging Selenium WebDriver, Java, and TestNG, we’ve created a robust and maintainable test suite that ensures the reliability of the netbanking application.

**Key Features**
**Page Object Model (POM):** We’ve structured our test automation framework using the POM design pattern. Each web page is represented as a separate class, encapsulating its elements and interactions. This approach enhances code readability, reusability, and maintainability.
**Data-Driven Testing:** Our framework supports data-driven testing by integrating Excel sheets. You can easily parameterize test data (such as usernames, passwords, and customer details) and execute test cases with different input values.
**TestNG Annotations:** We’ve utilized TestNG annotations (such as @BeforeMethod, @Test, and @DataProvider) to manage test execution flow, setup, and teardown. This ensures efficient test orchestration and reporting.
**Custom Utilities:** We’ve created utility classes to handle common tasks, such as reading data from Excel files, logging test results, and capturing screenshots upon test failure.
**Getting Started
Prerequisites:**
Install Java Development Kit (JDK)
Set up your preferred Integrated Development Environment (IDE) with Maven support (e.g., IntelliJ IDEA, Eclipse)
Download the latest Selenium WebDriver JAR files
Create an Excel sheet with test data (e.g., usernames, passwords, customer details)

**Configure Test Data:**
Update the Excel sheet (TestData.xlsx) with relevant data.
Modify the config.properties file to specify the browser, URL, and other configuration settings.
**Run Test Suites:**
Execute test classes under the src/test/java directory.
Use TestNG XML files to group and execute specific test suites.
**Reporting and Logs**
Our framework generates detailed HTML reports (using Extent Reports) that provide insights into test execution status, including passed, failed, and skipped tests. Additionally, logs are available for debugging purposes.

**Contributions**
Feel free to contribute to this project by submitting pull requests or reporting issues. Let’s collaborate and enhance the quality of automated testing!

Happy testing! 🚀

