# OpenCart - Orders
### Revision History

| Date |Description  | Author  | Comments |
| :-----: | :---: | :---: | :---: |
| 08.09.2023 | Test Plan for version 1.0   | Dana Popescu  | draft test plan |
| 11.09.2023 | version 1.1 | George Marin | Added more details for Test Process |
| 25.09.2023 | version 1.2 | Ramona Chis | Added more details for Test Deliverables |

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
##### Roles and responsibilities

| Name | Role |
| :-----: | :---: |
| Ramona - Tester  | will test: Viewing order details,Searching for an order |
|George - Tester  | will test: Manually adding/modifying an order,Customer details,Payment details,Shipping details |
|Dana - Senior tester | will test: Products,Vouchers,Printing invoices |

##### Entry criteria:
- smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)
- testing environment is up and running
- roles needed for the project are allocated
- functional specifications are defined
- Test Data is prepared
- The necessary equipment and software are installed for testing

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

### 2.2 Test analysis - MEG MI IDE????
- Analyze the business requirements to make sure that we have all the details for creating the test conditions
- We plan on running a full regression test on the current version

### 2.3 Test design
- defining the testing process
- all the test cases are written and then examined
- Jira will be used as test management tool
- Zephyr squad will be used as a plugin for Jira

### 2.4 Test implementation
- all the test data is available and reviewed (an account with Admin Role was created, username demo, password demo)
- testing environment is up and running
- test suites are created (Cycle Summary was created)
- this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority

### 2.5 Test execution
- the tests will be executed on the following browsers: Chrome, Mozilla, IE if time will be available we will extend tests on Opera browsers
- Bugs will be created based on the failed test cases
- The full regression testing will be done after new application changes
- Retesting will be done after a bug is fixed
- The regression testing will be executed when a problem is solved
- If the site will shut down, we will execute full retesting

### 2.6 Test closure -- PONTOS SZAMOK!!!
- ....
- no Critical issues have Open status

### 2.7 Test monitoring and control -- MI KELL IDE???
- ...
- ...
- ...

### 3 Test deliverables
### 3.1 Test plan

### 3.2 Test conditions

### 3.3 Test cases
- Test cases are designed to cover various scenarios and functionalities of the Guru99 application.
- Each test case includes detailed steps, expected results, and preconditions.
- There are 35 test cases
la 3.3 zephyr test steps la export pdf - trebuie toate testele exportate pe urma se face "merge" si se incarca un singur fisier

### 3.4 Daily test summary report
The daily report generated on 14 November 2023 shows the execution of 13 test cases of which 11 are passed , 1 failed, and 1 work in progress.

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-14%20111430.png)
![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-14%20111501.png)

On 17 November 2023 was executed a number of 12 test cases of which 7 are passed and 5 are failed.

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-17.png)
![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%202023-11-17%20143745.png)

The report generated on 21 November 2023 shows that the last 10 test cases were executed, 8 of them being passed and 2 failed.

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-21%20142059.png)
![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20rep%20-%202023-11-21%20142158.png)

### 3.5 /traceability matrix

### 3.6 Test case results
[tesx sau test case results](https://github.com/anettabako91/ProiectTestareManuala/blob/main/TES-46.pdf)

3.6 execution si result la export pdf - trebuie toate testele exportate pe urma se face "merge" si se incarca un singur fisier

### 3.7 Bugs report

3.7 la fel - trebuie toate testele exportate pe urma se face "merge" si se incarca un singur fisier

### 3.8 Test completion report
3.8 schreenshot din dashboard

### 3.9 Schedule
- we have 9 days of testing
- we have 35 test cases
- in order to finish the regression run we would need to run an ~ of 4 tests/day

