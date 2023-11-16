# OPENCART PROJECT
### TEST PLAN

    1. Introduction
        1.1 Project objective
        1.2 Functionalities in scope
        1.3 Functionalities and tests out of scope
    2. Test process
        2.1 Test planning
        2.2 Test analysis
        2.3 Test design
        2.4 Test implementation
        2.5 Test execution
        2.6 Test closure
        2.7 Test monitoring and control
     3. Test deliverables
        3.1 Test plan
        3.2 Test conditions
        3.3 Test cases
        3.4 Daily test summary reports
        3.5 Traceability matrix
        3.6 Test case results
        3.7 Bugs report
        3.8 Test completion report

#### 1. INTRODUCTION
This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage the testing process for Opencart.
##### 1.1 Project Objective
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using a live application.

Application under test: https://demo.opencart.com/  the focus will be only on Uploads menu

Application documentation: http://docs.opencart.com/en-gb/tools/uploads/

Tools: Jira, Zephyr Squad 
##### 1.2 Functionalities in scope
- All the features of Uploads menu which were defined in business requirements need to be tested: functional testing, GUI testing.  
- The below user story was created in Jira and describes functional specifications of the Upload menu.
![user story](https://github.com/farkas1david/Final-project-OC/assets/132594193/4fcc7458-6d1b-4330-bae9-02958943077d)


##### 1.3Functionalities and tests out of scope
- Non-functional testing like stress, performance is beyond scope of this project 
- No QA support for mobile application developed. Only web application will be tested. 
- Automation testing is beyond scope

#### 2. TEST PROCESS
##### 2.1 Test planning
##### Roles and responsibilities
| John Doe | Product Owner |
|---|---|
| Aaron Korsh | Software Developer |
| Farkas David | Tester |

##### Entry criteria:
- Business specifications are defined 
- Roles needed for the project are allocated 
- Initial project risks were detected and mitigated 
- Smoke test passed

##### Exit criteria:
- All test cases have been executed 
- The unresolved bugs/defects have low priority 
- No detected major risks remained un-mitigated 
- All resolved bugs have been retested and approved by the testers
- Regression testing have been ran and no major bugs detected  
- All business requirements have been covered by test cases 
- All business requirements have been met 

##### Risks:
- Project risks: lack of experience of QA team, lack of tools, short deadline for Jira and Zephyr Squad
- Product risks: critical bugs, content errors

##### 2.2 Test analysis 
- Analyze the business requirements to make sure that we have all the details to create the test conditions 
- Write test conditions that will be tested in out test process 

##### 2.3 Test design
- Functional test cases will be created in Jira 
- GUI test cases will be created in Jira 

##### 2.4 Test implementation
- Verify if the following elements are ready before test execution:
- Test environment is up and running: https://demo.opencart.com/admin/
- Access to test environment is given: 
    - Username: demo
    - Password: demo
- Cycle summary was created 
- Test cases were added to the cycle summary 
- Authorization token was created accessing the API and it is valid 

##### 2.5 Test execution
- Test cases are executed on the created cycle summary 
- Bugs have been created based on the failed test cases. The complete bug reports can be found here: https://github.com/farkas1david/Final-project-OC/blob/e0770d9b8d9e26247ac11c6ba1222ea480b35474/bug-reports.md
- Full regression pack is executed after changes made to the application

##### 2.6 Test closure
- All exit criteria were met as mentioned in the Test Planning section (2.1)
- The traceability matrix was generated to demonstrate the business requirements coverage
- Test execution chart was generated, the final report shows a number of 3 failed test cases of a total 30
- There are still 3 opened defects but they have low priority

##### 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.

#### 3. TEST DELIVERABLES

##### 3.1 Test plan
The plan identifies the items to be tested, the features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan.

##### 3.2 Test conditions
![test_conditions](https://github.com/farkas1david/Final-project-OC/assets/132594193/3561417e-05b9-4f3f-8a80-13c0a6933949)


##### 3.3 Test cases
Here you can find the [test cases](https://github.com/farkas1david/Final-project-OC/files/13253212/ZFJ-issue-export-11-03-2023-272134bffffcccf-0001.xlsx)


##### 3.4 Daily test status report
![Daily test execution](https://github.com/farkas1david/Final-project-OC/assets/132594193/488bdb3d-c0a7-4475-b782-a5cb2d40fe12)
![daily test execution 2](https://github.com/farkas1david/Final-project-OC/assets/132594193/770a9f51-77a1-446a-a54b-cb506be0aabb)

##### 3.5 Traceability matrix
![traceability matrix](https://github.com/farkas1david/Final-project-OC/assets/132594193/2c59a1bb-13f0-44e5-9bf6-5eb5b68444fb)

[Traceability Report from Jira](https://github.com/farkas1david/Final-project-OC/files/13120445/Traceability.Report.Recursive.Jira.pdf)

##### 3.6 Test case results
The results for the test cases can be found [here.](https://github.com/farkas1david/Final-project-OC/files/13120447/test.cases.and.results.pdf)

##### 3.7 Bugs report
During the project, we encountered two issues, which can be found [here.](https://github.com/farkas1david/Final-project-OC/files/13120463/bug.report.pdf)

##### 3.8 Test completion report
![test completion report](https://github.com/farkas1david/Final-project-OC/assets/132594193/815c9b79-564f-481d-aece-d20115a99de6)

