
Project Description:
-------------------
E613B. Testing - student_review_controller and student_task_controller
Class:
controller/student_review_controller.rb (71 lines)
controller/student_task_controller.rb (71 lines)
views/student_task/list.html.erb (126 lines)
What it does: The controllers and view manage student reviews and tasks in Expertiza
What needs to be done:
Write functional tests for the methods in the above mentioned controllers. Testing the ‘list’ functionality in the student_review_controller, and the ‘list’, ‘view’ and ‘others_work’ methods in the student_task_controller - 
check the redirtionect functionality, and 
include tests for inputs that might raise errors.



Link to project description:
----------------------------
-- Project VCL link
http://152.46.17.11:3000
-- github link
https://github.com/jinaymehta25/expertiza

Team members:
-------------

1. Jinay Mehta (unity id: jdmehta)
2. Mandar Chaudhary (unity id: mschaudh)
3. Pongobinath Sivashanmugam (unity id: psivash2)


Test Framework used:
--------------------
Test::Unit


Implementation details:
-----------------------
1. The functional tests have been generated for the list method of student_review_controller and list, view and other's work             method of student_task_controller respectively.
2. There are 9 functional tests of the list method in student_review_controller, 14 functional tests of list method in          student_task_controller

Instructions to run the tests:
------------------------------
1. Open the project
2. There are two test files "student_review_controller_test.rb" and "student_task_controller_test.rb" which contain the functional tests for list method of student_review_controller and list, view and other's work method of student_task_controller and the view for list, others and view  respectively.
3. Make sure that you run all the funtional tests so that the correct test data is populated in the test database.
4. Right click on the test file you would like to run.

Note:
We have tested the redirect functionality and funtion calls in the controller and in views rendering of views and redirections are checked.



Remote Computer: 152.46.17.11
User ID: mschaudh