# EC601-HW5-Unit Test
## Brief IntroductionUnit Test
This is EC601(Fall 2017) Homework 5 Unit Test by Jinguang Guo.

There are two tasks included:
The Task 1 is Task Cases;
The Task 2 is Automated Test.
 
## Task 1 - Test Cases
This task has two parts:
1. Generate your own test cases;
2. Run your own black box testing.
Check the test cases that I created and the results as:
unit test (HW5)/Test Case Sheet of Jinguang Guo's webapp.xlsx

## Task 2 - Automated Test
This task has two parts:
1. Run an automated test, e.g., AWS test farm and monkey test;
2. Interpret the results.
As the APP developed in HW2 is a WEB-App, CrossBrowserTesting and Monkey Test are used for the automated test.

### CrossBrowserTesting
First, a live test was done and passed(Which is not really an automated test):
The environment setting is: Mac iOS 10.12 and Safari 10
The recorded video can be found as:
unit test (HW5)/CrossBrowserTesting on Mac iOS 10.12 & Safari 10.mp4

Second, a series of screenshot tests(Which are automated tests) were finished in 10 different environment settings.
Most passed but some has some minor layout difference warnings, which is not critical problems. However, that can be fixed in the future.
The result can be found as:
/unit test (HW5)/screenshot test result.png
The automate testing scripts can be found as:
/unit test (HW5)/Autumate test code examples/

### The Monkey Test
The automated unit test also utilized the Monkey Test: http://monkeytest.it
The result can be found as:
/unit test (HW5)/Monkey test result.png
It passed with just 1 warning, which doesn't really hurt.

As the tests result shows, the HW2 project: Jinguang Guo's resume website is mostly a qualified WEB-App.
