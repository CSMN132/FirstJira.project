#  Project
### Revision History

| Date | Description   | Author   | Comments |
| :-----: | :---: | :---: | :---: |
| 05.09.2023 | Test Plan for version 1.0  | Gogu Cosmin | draft test plan |
| 10.09.2023 | v1.0 | Andreea Popescu | Added more details for Test Process |

## Table of Content:
1. Introduction
   1. Project objective
   2. Functionalities in scope
   3. Functionalities and tests out of scope
2. Test process
   1. Test planning
   2. Test analysis
   3. Test design
   4. Test implementation
   5. Test execution
   6. Test closure
   7. Test monitoring and control
3. Test deliverables
   1. Test conditions
   2. Test cases
   3. Daily test summary reports
   4. Traceability matrix
   5. Test case results
   6. Bugs report
   7. Test completion report
   8. Schedule

## Introduction:

 - The Guru99 Bank project aims to provide net banking facility to its customers.
 - This release will have limited features. Over a period of time , new and new functionalities will be added to the site.
    
 ### 1.1 Project Objective
 
  - We need to raise the trust in the quality of the project as high as possible before releasing it to customers.
  - Application under test: https://demo.opencart.com/
  - Documentation: http://docs.opencart.com/en-gb/introduction/

 ### 1.2 Functionalities in scope

  - To ensure that new customers can successfully register and access the OpenCart services.
  - Functional testing & external interfaces are in scope and need to be tested.
  - The shoping site will be only compatible with Chrome version 27 and above and with opera.
  - Here we should write all the functionalities that are included in the release.
  - Testing the functionalities related to account management, including account creation, updating, and deletion.
   
 ### 1.3 Functionalities and tests out of scope

  - Non-functional testing like stress, performance is beyond scope of this project.
  - Automation testing is beyond scope.
  - No QA support for mobile applications developed. Only web applications will be tested.

## 2.Test process:

 ### 2.1 Test planning
  
   Roles and responsibilities:

| Ramona - Tester  | will test: Edit customer,Security testing,Performance testing. |    
| :-----: | :---: | 
| Andreea - Senior Tester | will test: Create new customer,System testing,Delete customer. |   

   Entry criteria:
   
  - smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing). 
  - testing environment is up and running.
  - Valid test data for creating a new customer is available, including name, address, phone number, and email.
  - roles needed for the project are allocated.
  - functional specifications are defined.
  - The necessary equipment and software are installed for testing.
  - Test scenarios and test cases for the 'New Customer,' 'Edit Customer,' and 'Delete Customer' functionalities are defined and documented.

   Exit criteria:
   
  - 90% of tests are passed
  - To generate a unique account number and authentication data for the new customer.
  - To provide a confirmation message of successful registration.
  - To correctly validate the user-entered data and provide error messages in case of errors.
  - To provide a detailed record of the test and the obtained results.
  - exploratory testing was performed on New customer module.
  - The customer deletion operation allows the successful removal of customers from the system.
  - After deletion, there are no unwanted references or leftover data in the system.
  - The system provides a confirmation or success message after a customer is successfully deleted.
  - In the case of a failed deletion, the system provides appropriate and detailed error messages.
  - All test recording data and their results are adequately documented.
  - Exploratory testing was conducted for the "Delete Customer" functionality to identify unexpected or unaddressed issues in the planned test cases.
  - The customer modification operation allows the successful modification of customer data in the system.
  - After modification, customer data is updated correctly and consistently throughout the entire system.
  - The system provides a confirmation or success message after the customer's data is successfully modified.
  - In the case of a failed modification, the system provides appropriate and detailed error messages.
  - All test recording data and their results are adequately documented.
  - Exploratory testing was conducted for the "Edit Customer" functionality to identify unexpected or unaddressed issues in the planned test cases.
      
   Risks:

  - stability risks (crashes, disconnects, etc)
  - IE browser might have performance issues
  - the web page pagination could be impacted when opened on mobile devices
  - stress conditions might impact the web application
  - new browser might not be supported
  - human error 
  - Data validation errors

 ### 2.2 Test analysis

  - Analyze the business requirements to make sure that we have all the details for creating the test conditions.
  - We plan on running a full regression test on the current version.
  - Write test conditions(What?).
  - Analyze the boundary conditions and limits for each functionality. For example, what happens when a customer record is at its data limit?.
  - Identify the functional requirements for each functionality, including what data can be modified, what data can be deleted, and what new customer data can be added.
    
 ### 2.3 Test design

  - defining the testing process.
  - all the test cases are written and then examined. 
  - Jira will be used as test management tool.
  - Zephyr squad will be used as a plugin for jira.

### 2.4 Test implementation

  - The following elements are needed to be ready before the test execution phase begins: https://demo.guru99.com/V4/index.php.
  - Testing environment is up and running:
  - Access to the testing environment is given: UserID:(mngr532768,password:Bugati1@).
  - Cycle summary was created.
  - Test cases were added to the cycle summary.
  - all the test data is available and reviewed (test data=registration was successfully,password example,manager user).
  - this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority.
  - Test suites are created (Cycle Summary was created).

### 2.5 Test execution

  - the tests will be executed on the following browsers: Chrome, Mozilla, IE if time will be available we will extend tests on Opera and Brave browsers.
  - Bugs will be created based on the failed test cases. 
  - The full regression testing will be done after new application changes.
  - Retesting will be done after a bug is fixed.
  - If the site will shut down, we will execute full retesting.
  - The regression test will be executed when a problem is solved.

### 2.6 Test closure

  - 100% tests were executed and 90% of them are passed. 
  - no Critical issues have Open status.

### 2.7 Test monitoring and control

  - Various periodic reports will be generated to reflect the current status of testing process, in case of major problems control measures could be taken. 
  - Offering feedback to the QA team and other stakeholders regarding the progress.
  - Conveying test results achieved so far to all relevant parties.
  - Identifying and tracking relevant test metrics.
  - All test cases are written and reviewd.
  - Planning and Estimation to determine the future course of action based on the metrics being tracked.
  - Prioritize testing efforts in a different way.
  - Reorganize test schedules and deadlines.
  - Restructure the test environment.
  - Reprioritize the test case and conditions.

## 3.	Test deliverables

 ### 3.1 Test condition
