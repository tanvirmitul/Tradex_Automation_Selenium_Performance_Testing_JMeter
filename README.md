# Tradex_Automation_Selenium_Performance_Testing_JMeter
### This is a complete project where an [Crypto-currency site](https://exchange-tradex.nftarttoken.xyz/) site is automated by writing test suites using selenium-webdriver and TestNg as testing framework and also perform performance testing (load testing & stress testing) by JMeter.
The following key modules/pages are automated:
- **SignUp** 
- **Login**
- **Logout**
- **Forgot password**
- **Reset password**
- **2FA Security Method Unavailable?**
- **Security Settings**


- **Checkout**</br>

Key test cases(total **75**) are written & automation performed (total **56**) for each module and test suites created including the positive and negative test cases.
For failed test cases it will take a screenshot aswell at the point of failure.
</br>The test runner codes can be extracted from this [link](https://github.com/tanvirmitul/Tradex_Automation_Selenium_Performance_Testing_JMeter/tree/main/src/test/java/testrunner).</br>
**The test cases are written following standard test case format in this excel file:**
[Test_cases.xlsx](https://docs.google.com/spreadsheets/d/1mXh8u5QwzKij1wrGjaf6hGOwgcsra5Zl6mkPvbuaRsY/edit?usp=sharing) </br>
**The checklist are written following standard format in this google docs file:**
[Checklist.docs](https://docs.google.com/document/d/1TMj1EE-dclCrhCLYSMyCZhTb9SRqPVjPjSLwvTk6qI0/edit?usp=sharing) </br>
**The documented test plan is written following standard format in this google docs file:**
[Checklist.docs](https://docs.google.com/document/d/1XqX2epgf_5FMyU5eQCP6ymqzeT9p2wglmVY-tbOoTJo/edit?usp=sharing) </br>

### Technology: </br>
- Tool: Selenium Webdriver
- IDE: Intellij IDEA
- Build tool: Gradle
- Language: Java
- Testing Framework : TestNG

### Prerequisite: </br>
- Need to install jdk 1.8, gradle and allure
- Configure Environment variable for jdk 1.8, gradle and allure
- Clone this project and unzip it
- Open the project folder
- Double click on "build.gradle" and open it through IntellIJ IDEA
- Let the project build successfully
- Click on "Terminal" and run the automation scripts

### Run the Automation Script by the following command:
 ```
 gradle clean test 
 ```
- Selenium will open the browser and start automating.
- After automation to view allure report , give the following commands:
 ```
allure generate allure-results --clean -o allure-report
allure serve allure-results
 ```

**Below is my allure overview report**:

[Test_report.docs](https://docs.google.com/document/d/1JS1a4TW5QBPYS2GTUR7Lymte0UVEOgfWRvSL-tgNyaY/edit?usp=sharing) </br>

**Here are the suites of this project**:

![suites](https://user-images.githubusercontent.com/55280106/185918539-c40ea3e9-dd3f-4e56-b223-adcf80fcbf25.png)

**Here is the overall walkthrough of the project:** [Video](https://drive.google.com/file/d/1fx4bMzsdBhugkUjqPKAI1z9UCwFo8W_-/view?usp=sharing)</br>
**You can watch the sanity testing of Checkout module from here:** [Video](https://drive.google.com/file/d/1nsk8-EKik-BnvjvH4mSwOwV7COD7dsas/view?usp=sharing)
