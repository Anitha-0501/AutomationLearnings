Web and API Automation with Selenium and Java
Overview
This repository contains a Maven-based Java project designed for web page and API automation. It utilizes Selenium for web automation and integrates with various API testing tools for comprehensive automation solutions.

Features
Web Page Automation: Automate interactions with web pages using Selenium WebDriver.
API Automation: Perform automated testing of APIs.
Maven Integration: Build and manage dependencies using Maven.
JUnit Integration: Utilize JUnit for test case management and reporting.
Getting Started
To get started with this project, follow the instructions below:

Prerequisites
Java JDK 8 or higher: Ensure that you have Java installed on your machine. You can download it from the Oracle website or use a package manager.
Maven: Apache Maven is required to manage project dependencies and build the project. Download Maven from the Apache Maven website and follow the installation instructions.
Selenium WebDriver: Ensure you have the necessary WebDriver binaries (e.g., ChromeDriver, GeckoDriver) that match your browser version.
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/Anitha-0501/AutomationLearnings.git
Navigate to the Project Directory

bash
Copy code
cd your-repository
Build the Project

Use Maven to compile and package the project:

bash
Copy code
mvn clean install
Configure WebDriver

Download the appropriate WebDriver for your browser and place it in a directory that is included in your system's PATH, or configure it within your test code.

Running Tests
To execute the tests, use the following Maven command:

bash
Copy code
mvn test
This will run all test cases defined in the src/test/java directory.

Project Structure
src/main/java: Contains the main source code for the project.
src/test/java: Contains the test cases and automation scripts.
pom.xml: Maven project configuration file, including dependencies and build settings.
Configuration
Selenium Configuration: Update the WebDriver path and browser configurations in the src/test/resources/config.properties file or within your test code as necessary.
API Endpoints: Configure API base URLs and endpoints in the src/test/resources/api-config.properties file.
Contributing
We welcome contributions to this project. If you would like to contribute, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push your changes to your forked repository.
Submit a pull request with a clear description of your changes.
License
This project is licensed under the MIT License.

Contact
For any questions or issues, please contact anitha.manian.qa@gmail.com.



