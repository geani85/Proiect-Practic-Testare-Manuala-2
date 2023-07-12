# Proiect-Practic-Testare-Manuala
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and aplly them in practice, using a live application

Application under test:https://demo.opencart.com/

API Documentation: N/A.

**The final project will be split into 2 section: [Testing section]() and  [SQL section]()**

Tools used: Mozilla, Jira, Zephyr Squad

**Functional specifications**

____

**Testing section**

**1.1 Test Planning**

We want to test some funtionalities like, Register ,LogIn, Search Bar and Wish List of the  Open Cart app.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

**1.1.1 Roles assigned to the project and persons allocated**


     Alex will test: Register and LogIn
     Geani will test: Search Bar and Wish List
     
     
**1.1.2 Entry criteria defined**

     - smoke test passed
     - testing environment is up and running
     - initial project risks were detected and mitigated
     
**1.1.3 Exit criteria defined**

     - 90% of tests are passed
     - no Critical issues have Open status


**1.1.4 Test scope**
  -   Register
  -   Log in
  -   Search Bar
  -   Wish List 


 - **Tests not in scope:**
    - Non-functional testing like stress, performance, compatibility,etc.
    - Automation testing is beyond scope.

**1.1.5 Risks detected:**

 - Projects risks:
      - Risks related to the ability of the OpenCart app to handle increased user load, high traffic volumes.
      - The risk of not being able to meet project deadlines 
      - Risks associated with managing expectations and communication with stakeholders, including conflicts or  changing requirements.
      - The risk of low user adoption.
 - Product risks:
      - Risks related to the user interface and user experience of the OpenCart app, such as confusing navigation, poor layout or difficulty in completing tasks.
      - The risk of the OpenCart app experiencing slow response times, frequent crashes, or inefficient resource utilization, which can lead to a poor user experience and loss of customers.

**1.1.6 Evaluating entry criteria**
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.


**1.2 Test Monitoring and Control**

It will be done by generating periodic reports that reflect the current status of the test.

**1.3 Test Analysis**

The testing process will be executed based on the above requirements for the ***module under test name***. The following test conditions were found:

  - Verify that an user can create an account using mandatory fields.
  - Verify that an user can create an account using all fields.
  - Verify that if mandatory fields are empty an error message appear.
  - Verify that if ‘First Name’ and 'Last Name' input fields are completed with numbers an error message appears.
  - Verify that an user can find a product.
  - Verify that an user can add a product in wish list.
  - Verify that an user can delete a product from the wish list.
        

**1.4 Test Design**

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are: 


The test cases with steps can be viewed here: [test_cases.pdf]()

**1.5 Test Implementation**

The following elements are needed to be ready before the test execution phase begins:

 - the enviroment is ready
 - the requirements have been reviewed
 - 
**1.6 Test Execution**

 - Test cases are executed on the created test Cycle summary(or Test Run): [cycle_summary_execution.pdf]()
 - Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf]()
enter here bug titles

**1.7 Test Completion**
 - Exit criteria was evaluated and passed
 - The traceability matrix was generated and can be found here: [Traceability_matrix.csv]()
 - Test execution chart was generated, the final report shows.... -> describe the final report
 -> enter here test execution report/chart


**2 SQL section**



