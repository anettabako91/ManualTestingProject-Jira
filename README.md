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
###### Roles and responsibilities

| Name | Role |
| :-----: | :---: |
| Ramona - Tester  | will test: Viewing order details,Searching for an order |
|George - Tester  | will test: Manually adding/modifying an order,Customer details,Payment details,Shipping details |
|Dana - Senior tester | will test: Products,Vouchers,Printing invoices |

###### Entry criteria:
- smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)
- testing environment is up and running
- roles needed for the project are allocated
- functional specifications are defined
- Test Data is prepared
- The necessary equipment and software are installed for testing

###### Exit criteria:
- 100% tests were executed and 95% are passed
- No Critical issues have Open status (All remaining defects/bugs have low severity)
- update tests are 100% passed (update tests will not generate other new issues that impact the application)
- Exploratory testing was performed on Orders module -> subsection Add new order

###### Risks:
- stability risks (crashes, disconnects, etc)
- IE browser might have performance issues
- the web page pagination could be impacted when opened on mobile devices
- stress conditions might impact the web application
- new browser might not be supported

  

### 3.4 Daily test summary report
Raportul generat in data x arata rularea a 10 test caseuri dintre care 9 passed si 1 failed.

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20report%20adding%20a%20new%20order%20manually.png)

![Daily report](https://github.com/anettabako91/ProiectTestareManuala/blob/main/daily%20report%20adding%20a%20new%20order%20manually2.png)

### 3.6 Test case results
[tesx sau test case results](https://github.com/anettabako91/ProiectTestareManuala/blob/main/TES-46.pdf)

la 3.3 zephyr test steps la export pdf - trebuie toate testele exportate pe urma se face "merge" si se incarca un singur fisier

3.6 execution si result la export pdf - trebuie toate testele exportate pe urma se face "merge" si se incarca un singur fisier

3.7 la fel - trebuie toate testele exportate pe urma se face "merge" si se incarca un singur fisier

3.8 schreenshot din dashboard
