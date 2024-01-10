# Selenium_Testing_Automation_OrangeHrm
I have created a selenium automation testing project for OrangeHRM website.
I have also asserted the expected message after successfull activities.

## Project Summary
- Login as a admin to https://opensource-demo.orangehrmlive.com/
- Go to menu and create a new employee. Save the employee firstname, lastname, employeeid, username and password. Generate random password.
- Go to the dashboard again and search by the employee id if found
- Go to the Directory menu and search by employee name if found
- Logout the session.
- Now login with the newly created employee creds
- Assert your full name 
- Go to my info
- Scroll down and select Gender and Blood Type as O+ and save it. Then logout the user.
- Create a smoke suite configuration which will run only following features:
    - Login to admin
    - search by the employee id if found
    - logout admin and login to the employee id you created last
    - Update the blood Group as AB-
    - Logout the user
 
## How to run this project
- clone this project
- To run regression testing hit this command ```gradle clean test -PsuiteFile="MasterSuite.xml"```
- To run smoke testing hit this command ```gradle clean test -PsuiteFile="SmokeMasterSuite.xml"```
- To generate allure report hit these command  
  ```allure generate allure-results --clean -output```  
  ```allure serve allure-results```

## Project Test Cases
[https://docs.google.com/spreadsheets/d/1Fx1iinGV8W9k7XcMf4buPH9NmLR50T4GVCwwjjAB72I/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1w1K_C7pnQJ4c54mKnZrX-Gp-UZzUzNXmWD0MVm-Ybgw/edit?usp=sharing)

## Project Tools & Framework
- Intellij
- Jdk-11
- Selenium
- Allure
- TestNG
  
## Project Video Recording
https://drive.google.com/file/d/1ckvTyVljz4aPsFrj45dhS0fAmEjVV7qp/view?usp=sharing

## Allure Report Image: 
![1](https://github.com/bakhtiaralamshahrukh/Selenium_Testing_Automation_OrangeHrm/assets/69646920/c29cc137-b90d-4edc-967b-5388a784a19f)

![2](https://github.com/bakhtiaralamshahrukh/Selenium_Testing_Automation_OrangeHrm/assets/69646920/77bb5665-2459-4670-9f65-f07f168d67b6)

## Project Report Summary: 
![3](https://github.com/bakhtiaralamshahrukh/Selenium_Testing_Automation_OrangeHrm/assets/69646920/c058d529-7bb1-4462-8eab-a6f2b9ba6efe)


