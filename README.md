# Manual testing OrangeHRM website using JIRA for the tests
In this repository I will be adding the test cases written in JIRA, for the dummy website OrangeHRM, in which I have manually tested the login page and the ADD + SEARCH + RESET functionalities from the Admin Module.

# Test Plan OrangeHRM

## Table of Content:

## 1. Introduction
## 1.1. Project objective
## 1.2. Functionalities in scope
## 1.3. Functionalities and tests out of scope
## 2. Test process
## 2.1. Test planning
## 2.2. Test analysis
## 2.3. Test design
## 2.4. Test implementation
## 2.5. Test execution
## 2.6. Test closure
## 2.7. Test monitoring and control
## 3. Test deliverables
## 3.1. Test plan
## 3.2. Test conditions
## 3.3. Test cases
## 3.4. Daily test summary reports
## 3.5. Traceability matrix
## 3.6. Test case results
## 3.7. Bugs report
## 3.8. Test completion report

## 1. Introduction

OrangeHRM provides a scalable HRM solution for small and midsize businesses, ensuring the entire employment lifecycle is covered, from onboarding to termination. Some of the functionalities are:

- employee information management
- employee leave management
- recruitment management
- employee performance management
- other managerial tools

## 1.1. Project objective

We need to raise the trust in the quality of the project as high as possible before releasing it to customers.
https://opensource-demo.orangehrmlive.com/

## 1.2. Functionalities in scope

a) Login functionality as an Admin

b) Admin Module – ADD, RESET, SEARCH functionalities

c) Application functionality from desktop perspective

## 1.3. Functionalities and tests out of scope

- No QA support for mobile applications developed. Only web+desktop applications will be tested
- Automation testing is beyond scope
- Non-functional testing like stress, performance is beyond scope of this project

## 2. Test process

## 2.1. Test Planning

Roles and responsibilities

I will test everything that is mentioned in "functionalities in scope".

Entry criteria:
- smoke test passed
- testing environment is up and running
- to have all browsers available for testing the cloud environment
- to have the supported environment for the desktop application

Exit criteria:
- no Critical issues have "Open Status"
- update tests have 100% passed
- 90% of tests have passed

Risks:
- stability risks (disconnects, crashes etc)
- some browsers might not be supported
- update tests might impact the user data
- stress conditions might impact the web applications

## 2.2. Test analysis
- we are planning on running a full regression test on the current version

## 2.3. Test design
- all test cases are written and reviewed

## 2.4 Test implementation
- this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority
  
## 2.5 Test execution
- the tests will be executed on the top used browser: Chrome. If time will be available we will extend tests on Mozilla Firefox and Microsoft Edge

## 2.6 Test closure
- at least 95% of tests are passed
- no Critical issues have Open status

## 2.7 Test monitoring and control

## 3. Test deliverables

## 3.1  Test plan 
- [Link to test plan](https://itfclasses.atlassian.net/browse/BRT-9?atlOrigin=eyJpIjoiYmUxNmMyNWZhZTMzNGRlYTk0OWJmNjNhODgzNDBiNDMiLCJwIjoiaiJ9)

## 3.2  Test conditions 
The test conditions will be created based on the business requirements validated in the test analysis phase and will represent the features to be tested and transformed into test cases.

## 3.3  Test cases
 - Links to the test cases
 - [Login Page OrangeHRM case scenarios and test cases](https://itfclasses.atlassian.net/browse/BRT-10?atlOrigin=eyJpIjoiMTE3MjUwNjU4NmYzNGU2NTgzYzMzZGI5ZGE1Mjg1MjAiLCJwIjoiaiJ9)
 - [Admin Module OrangeHRM - Search and Reset functionalities, case scenarios and test cases](https://itfclasses.atlassian.net/browse/BRT-25?atlOrigin=eyJpIjoiNTM4NjgyZmZiNGQxNDE2ZjhmMDA2Mzc3NGM2ODhhMmMiLCJwIjoiaiJ9)
 - [Admin Module OrangeHRM - Add functionality, case scenarios and test cases](https://itfclasses.atlassian.net/browse/BRT-54?atlOrigin=eyJpIjoiZjEwNGEzNDlmYzliNGZiM2FiYTFlNzJjNDUzYjI5Y2QiLCJwIjoiaiJ9)
   
## 3.4  Daily test summary report
 - [Link to test summary report](https://itfclasses.atlassian.net/projects/BRT?selectedItem=com.thed.zephyr.je__test-summary-project-level)

## 3.5  Traceability matrix
 - [Link to traceability matrix](https://itfclasses.atlassian.net/projects/BRT?selectedItem=com.thed.zephyr.je__traceability-project-level)

## 3.6  Test metrics
 - To be able to see the test metrics, you have to select the link below, select the version : "Test Plan OrangeHRM" and modify the time filter to Custom - 09/16/2023 to 11/07/2023
 - [Link to test metrics for OrangeHRM tests](https://itfclasses.atlassian.net/projects/BRT?selectedItem=com.thed.zephyr.je__test-metric-project-level)

## 3.7  Bugs report
 - [Login Page - "Forgot your password? button bug](https://itfclasses.atlassian.net/browse/BRT-14?atlOrigin=eyJpIjoiYTg4MWFjNWNkZmI0NDZkNjliNzUxNDBlODYzM2M4YTQiLCJwIjoiaiJ9)
