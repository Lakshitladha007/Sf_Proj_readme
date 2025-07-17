## Test Case 1

This testcase focuses on commmon file shared between multiple MRs from a single feature branch.

1. From feature1, MR1 is raised and  this MR contains 2 files{**release_x**}: <br>  
   a> HelloWorld.cls<br>
   b> HelloWorldcls-meta.xml<br>
   c> HelloWorldTest.cls-meta.xml<br>
   d> HelloWorldTest.cls-meta.xml<br>

   a> GreetingService.cls<br>
   b> GreetingService.cls-meta.xml<br>
   c> GreetingServiceTest.cls<br>
   d> GreetingServiceTest.cls-meta.xml<br>

This MR is tagged with label "release_x"<br>

#### Raise MR from feature1 to DEV:<br>
![alt text](Screenshots/1.png) 

#### DEV Pipeline Success:(Automatically Triggered)
![alt text](Screenshots/2.png)

#### QA Pipeline Success:(Manually Triggered)
![alt text](Screenshots/3.png)

2. From feature1, MR2 is raised and this MR contains 1 new file1, deleted 1 files and updated 1 file{**release_y**}:<br>

   ADDED FILES:<br>
   a> AccountAutoNumberHandler.cls<br>
   b> AccountAutoNumberHandler.cls-meta.xml<br>
   c> AccountAutoNumberHandlerTest.cls<br>
   d> AccountAutoNumberHandlerTest.cls-meta.xml<br>

   UPDATED FILES:<br>
   a> HelloWorld.cls<br>
   b> HelloWorldcls-meta.xml<br>
   c> HelloWorldTest.cls-meta.xml<br>
   d> HelloWorldTest.cls-meta.xml<br>

   DELETED FILES:<br>
   a> GreetingService.cls<br>
   b> GreetingService.cls-meta.xml<br>
   c> GreetingServiceTest.cls<br>
   d> GreetingServiceTest.cls-meta.xml<br>

This MR is tagged with "release_y"

#### Raise MR from feature1 to DEV:
![alt text](Screenshots/4.png) 

#### DEV Pipeline Success:(Automatically Triggered)
![alt text](Screenshots/5.png)

#### QA Pipeline Success:(Manually Triggered)
![alt text](Screenshots/6.png)

3. From feature1, MR3 is raised, this MR contains 1 new file, 1 updated file{**release_x**}:<br>
   ADDED FILE:<br>
   a> ContactTriggerHandler.cls<br>
   b> ContactTriggerHandler.cls-meta.xml<br>
   c> ContactTriggerTest.<br>
   d> ContactTriggerTest.cls-meta.xml<br>

   UPDATED FILES:<br>
   a> HelloWorld.cls<br>
   b> HelloWorldcls-meta.xml<br>
   c> HelloWorldTest.cls-meta.xml<br>
   d> HelloWorldTest.cls-meta.xml<br>
 
This MR is tagged with "release_x"

#### Raise MR from feature1 to DEV:
![alt text](Screenshots/7.png) 

#### DEV Pipeline Success:(Automatically Triggered)
![alt text](Screenshots/8.png)

#### QA Pipeline Success:(Manually Triggered)
![alt text](Screenshots/9.png)