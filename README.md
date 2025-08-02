# Selenium-TestNG-POM

A testing repository using Selenium and TestNG to automate an e-commerce website<a href="https://envothemes.com/envo-ecommerce/"> Envo Ecommerce</a> and its suite of applications.


1. [Technology](#technology)
2. [Prerequisites](#prerequisites)
3. [How to run this project](#How-to-run-this-project)
4. [Reports View](#Reports-View)


### Technology:
- Tool: Selenium
- IDE: IntelIJ
- Build tool: Gradle
- Language: Java
- Framework: TestNG

### Prerequisites
* Install jdk 8 or any LTS version
* Configure **JAVA_HOME** and **GRADLE_HOME**
* Download Allure latest version and configure system environment path
* Stable internet connection

### How to run this project
* Clone the repo in your local directory
* Open terminal to the project folder
* Run command `gradle clean test` to build the project
```
gradle clean test
```
6. Run command `allure generate allure-results --clean -o allure-report` to generate allure report.
```
allure generate allure-results --clean -o allure-report
```
7. Run command `allure serve allure-results` to generate html report and automatically open it in a web browser.
```
allure serve allure-results
```

### Reports View
These are the screenshots of **Allure** reports:

![image]<img width="1913" height="1008" alt="Image" src="https://github.com/user-attachments/assets/c8447b89-0a6d-43d1-8f97-4d040e2f0c4e" />

![image]<img width="1918" height="1015" alt="Image" src="https://github.com/user-attachments/assets/ba121d7e-96f0-4997-ac72-5713e4e32f77" />

