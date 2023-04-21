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
[Test_cases](https://docs.google.com/spreadsheets/d/1mXh8u5QwzKij1wrGjaf6hGOwgcsra5Zl6mkPvbuaRsY/edit?usp=sharing) </br>
**The checklist are written following standard format in this google docs file:**
[Checklist](https://drive.google.com/file/d/1EfPJvi9S8yPvjQOLY1LoOV2oVSeFKVEZ/view?usp=sharing) </br>
**The documented test plan is written following standard format in this google docs file:**
[Testplan](https://drive.google.com/file/d/15NUeBli3kFdyMXcrnEwzHOivbiq53Y2r/view?usp=sharing) </br>

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

**Here is my allure overview report**:[Test_report](https://drive.google.com/file/d/1OSDWwJMzDtZUMTebgL_trGctwWzHoy8h/view?usp=sharing) </br>

**Here is the overall walkthrough of the project:** [Video](https://drive.google.com/file/d/1l_4NF-x4bpDsFrXfGaIwO12qdkuEpN2S/view?usp=sharing)</br>

## Performance testing
## **Load testing**

- Find out the actual TPS for if 2000 user can give load within 1 hour **Expected load:** 2000 user, per hour.
- **Actual load:** what TPS? Breakdown the expected TPS in spread sheet and find out the actual TPS.
- For 600, 900s and 1200s load, add Jmeter UI screenshot
**The load testing strategy is written in standard form:**
[Load_Testing_Strategy](https://docs.google.com/spreadsheets/d/16JDx9z-FgROeiPNQ_qn99HGg8P8EmGqq4eknOJQk0Rw/edit?usp=share_link) </br>
**Here is load test report:** [Load_test_report](https://docs.google.com/document/d/15kMCTkWHIP83fkNdq_rv3Pj6ySvJ6LJzDnXEh7dprIc/edit?usp=sharing) </br>

## **Stress testing**

- Find out that maximum load server can handle.
- **Server capacity:** Constant the time in 600 secs and increases the user apply load untill the error has occured.
- For 600 secs, User: 333, 400, 500, 600
**The stress testing strategy is written in standard form:**
[Stress_Testing_Strategy](https://docs.google.com/spreadsheets/d/1Cixk2IkSrknw2MrhxBpv211NjK1r7uj9kGT8kx21XUs/edit?usp=sharing) </br>
**Here is stress testing report:** [Stress_testing_report](https://drive.google.com/file/d/11Qpm7Ont9FkwSn4iE4TmuZdK_ygOB5Y2/view?usp=sharing) </br>
