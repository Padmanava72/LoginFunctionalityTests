# LoginFunctionalityTests

## Overview
A repository contains Selenium TestNg scripts for testing the login functionality of a web aplication. The test suite include both successfull and unsuccessfull login scenerios.

## Test Execution Steps
- Java jdk (version 8 or higher).
- Selenium WebDriver(configured with the apprepriate browser driver, e,g.,ChromeDriver for Chrome).
- TestNG (to execute the test  scenerios).
- Browser Driver(e,g,chromeddriver for Chrome,edgeDriver for Edge).

## Assumptions 
- Valid Credintials: For the successful login test, it is aasumed that you have already the account with the valid credentials.
- Error Handling: The web application displays an error message when invalid credintials is user.

## Additional Information
- Browser_Specific: The current test are designed to work with Chrome using Chromedriver. to use another browser(e.g.,edge),update the Webdriver serupin the test script.
- Hardcoded Credintials: For demonstration purpose, the test credintials are hardcoded in the script .In a real_world scenerio, credintials should be stored securely(e.g., using configuration file like workbook for the data driven test)

## Challenges
- Element Synchronization : At time, elements may load slowly due ti netwirk or application performance issues. This was handled by using implicit waits in the scripts, but explicit waits could be introduced for more robust handling.
