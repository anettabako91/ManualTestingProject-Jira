# OpenCart - Orders
### Revision History

| Date |Description  | Author  | Comments |
| :-----: | :---: | :---: | :---: |
| 08.09.2023 | Test Plan for version 1.0   | Anetta Bako  | draft test plan |
| 11.09.2023 | version 1.1 | Anetta Bako | Added more details for Test Process |
| 25.09.2023 | version 1.2 | Anetta Bako | Added more details for Test Deliverables |

### Table of content
1. Introduction
    1. Project obiective
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
    1. Test plan
    2. Test conditions
    3. Test cases
    4. Daily test summary reports
    5. Traceability matrix
    6. Test case results
    7. Bugs report
    8. Test completion report


### 1. Introduction
   - OpenCart is a free open source e-commerce platform for online merchants.
   - OpenCart provides a professional and reliable foundation from which to build a successful online store.
   - This foundation Appeals to a wide variety of users; ranging from seasoned web developers looking for a user-friendly interface to use, to shop owners just launching their business online for the first time.
   - OpenCart has an extensive amount of features that gives you a strong hold over the customization of your store.
   - With OpenCart's tools, you can help your online shop live up to its fullest potential.
   - When a customer goes through checkout, the information on their order is automatically transferred to the Orders section for you to keep track of it.
   - In the administration, you can view all of the orders made on their site, manually add orders, or edit the details of existing orders.

### 1.1 Project Objective 
We need to raise the trust in the quality of the project as high as possible before releasing it to customers.

Application under test:https://demo.opencart.com/admin/ 

- Username: demo
- Password: demo

### 1.2 Functionalities in scope
 - All the features of the “Orders” module in the menu defined in the business requirements for OpenCart Admin will be tested using the following type of testing:Functional testing,GUI testing,and API testing.

 - The Administration OpenCart will be tested on latest versions of Mozilla, Chrome, IE.

### 1.3 Functionalities and test out of scope
- All the features that are not under Orders module 
- Non-functional testing like stress, performance is beyond scope of this project
- Automation testing is beyond scope
- No QA support for mobile applications developed. Only web applications will be tested.

### 2. Test process
### 2.1 Test planning
##### Roles and responsabilities

| Name | Role |
| :-----: | :---: |
| Anetta Bako - Junior Tester  | will test: Viewing order details,Searching for an order |
| Anetta Bako - Junior Tester  | will test: Manually adding/modifying an order,Customer details,Payment details,Shipping details |
| Anetta Bako - Junior Tester | will test: Products,Vouchers,Printing invoices |

##### Entry criteria:

- roles needed for the project are allocated
- functional specifications are defined - business requirements are finalized

##### Exit criteria:
- 100% tests were executed 
- number of unresolved bugs is insignificant or they have low priority
- no critical issues have Open status 
- all resolved bugs have been re-tested and approved by the QA team
- update tests are 100% passed (update tests will not generate other new issues that impact the application)
- Exploratory testing was performed on Orders module -> subsection Add new order
- deadline was reached

##### Risks:
- stability risks (crashes, disconnects, etc)
- IE browser might have performance issues
- the web page pagination could be impacted when opened on mobile devices
- stress conditions might impact the web application
- new browser might not be supported

### 2.2 Test analysis 
- Analyze the business requirements to make sure that we have all the details for creating the test conditions
- Write the test conditions  
- Identify the functional requirements for each functionality, including what data can be modified, what data can be deleted, and what data about new order can be added

### 2.3 Test design
- defining the testing process
- all the test cases are written and then examined
- Jira will be used as test management tool
- Zephyr squad will be used as a plugin for Jira

### 2.4 Test implementation
- all the test data is available and reviewed (an account with Admin Role was created, username demo, password demo)
- testing environment is up and running
- test suites are created (Cycle Summary was created)

### 2.5 Test execution
- the tests will be executed on the following browsers: Chrome, Mozilla, IE if time will be available we will extend tests on Opera browsers
- Bugs will be created based on the failed test cases
- The full regression testing will be done after new application changes
- Retesting will be done after a bug is fixed
- The regression testing will be executed when a problem is solved
- If the site will shut down, we will execute full retesting - mai bine risc de produs - sanity testing mai bine aici

### 2.6 Test closure 
- all the 35 tests were executed, 26 of them, which means 74.29% , were passed
- no Critical issues have Open status

### 2.7 Test monitoring and control
- Various periodic reports will be generated to reflect the current status of testing process, in case of major problems control measures could be taken
- Offering feedback to the QA team and other stakeholders regarding the progress
- Identifying and tracking relevant test metrics
- Reorganize test schedules and deadlines
- Restructure the test environment
- Reprioritize the test case and conditions

### 3 Test deliverables

### 3.1 Test conditions 
 - there are a total number of 35 test conditions which shows us all the details about testing the OpenCart application - Orders section
 - you can find details about the project and test conditions on pages 1-4 in this [Jira project](https://github.com/anettabako91/ManualTestingProject-Jira/blob/main/Zephyr%20Test%20Steps%20%2B%20Executions%20%2B%20Results%20(Jira).pdf) or you can check all the test conditions [here](https://github.com/anettabako91/ManualTestingProject-Jira/blob/main/test_conditions_new.xlsx)

### 3.2 Test cases
- Test cases are designed to cover different scenarios and functionalities of the OpenCart web application.
- Each test case includes detailed steps, expected results, and preconditions.
- There are 35 test cases and the steps of them can be found here: [test cases](https://github.com/anettabako91/ManualTestingProject-Jira/blob/main/test_steps.pdf)


### 3.3 Daily test summary report
The daily report generated on 14 November 2023 shows the execution of 13 test cases of which 11 are passed , 1 failed, and 1 work in progress.

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-14%20111430.png)
![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-14%20111501.png)

On 17 November 2023 was executed a number of 12 test cases of which 7 are passed and 5 are failed.

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-17.png)
![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%202023-11-17%20143745.png)

The report generated on 21 November 2023 shows that the last 10 test cases were executed, 8 of them being passed and 2 failed.

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-21%20142059.png)
![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-21%20142158.png)

### 3.4 Traceability matrix
The traceability matrix was generated and can be found here: 
[TraceabilityMatrix](https://github.com/anettabako91/ManualTestingProject-Jira/blob/main/Traceability_new.xlsx)

- Regular updates to the Traceability matrix help maintain transparency and alignment between testing and project objectives throughout the test life cycle
- The matrix indicates the current status of each test case, helping to monitor the testing process and identify any gaps or missing coverage
- The matrix can be used for compliance purposes and to demonstrate that all requirements have been adequately tested and verified


### 3.5 Test case results
[Test case results](https://github.com/anettabako91/ManualTestingProject-Jira/blob/main/test_execution_and_results.pdf) - here is a list of all the test cases created, along with their results
- these test cases cover various aspects of the project and are used to assess its correctness and performance for the functionalities: "orders" , "adding manually a new order"


### 3.6 Bugs report
A total number of 4 bugs were found, of which 1 is related to 4 different test codition (ABT-49 - relates to ABT-24, ABT-28, ABT-5, ABT-19) and one of them relates to two test conditions (ABT-50 relates to ABT-25 and ABT-22) and both of them are related to mandatory fields - they are not marked with stars as it is shown in documentation, or they are not considered mandatory.\
All the bugs can be found in this [Bugs report](https://github.com/anettabako91/ManualTestingProject-Jira/blob/main/bugs_report.pdf)

### 3.8 Test execution report
Test execution chart was generated, the final report shows that a number of 8 tests out of 35 were failed, and one is work in progress.
A number of 35 test cases were planned for execution and all of them were executed.

![Test execution chart](https://github.com/anettabako91/ProiectTestareManuala/blob/main/dashboard.png)

### 3.9 Schedule
- we have 9 days of testing
- we have 35 test cases
- in order to finish the regression run we would need to run an ~ of 4 tests/day

