## Test Case 2

From single feature branch(feature1) multiple MRs are raised with different lables.

1. From feature1, MR1 is raised, this MR contains 4 files:<br>
   a> AccountAutoNumberTriggerHandler.cls<br>
   b> AccountAutoNumberTriggerHandler.cls-meta.xml<br>
   c> AccountAutoNumberTriggerTest.xml<br>
   d> AccountAutoNumberTriggerTest.cls-meta.xml<br>

This MR is tagged with "release_a"

#### Raise MR from feature1 to DEV:<br>
![alt text](Screenshots/1.png) 

#### DEV Pipeline Success:(Automatically Triggered)
![alt text](Screenshots/2.png)


2. From feature1, MR2 is raised, this MR contains 4 files:<br>
   a> HelloWorld.cls<br>
   b> HelloWorldcls-meta.xml<br>
   c> HelloWorldTest.cls-meta.xml<br>
   d> HelloWorldTest.cls-meta.xml<br>

This MR is tagged with "release_b"

#### Raise MR from feature1 to DEV:<br>
![alt text](Screenshots/3.png) 

#### DEV Pipeline Success:(Automatically Triggered)
![alt text](Screenshots/4.png)


3. From feature1, MR3 is raised, this MR contains 4 files:<br>
   a> GreetingService.cls<br>
   b> GreetingService.cls-meta.xml<br>
   c> GreetingServiceTest.cls<br>
   d> GreetingServiceTest.cls-meta.xml<br>

This MR is tagged with "release_a"

#### Raise MR from feature1 to DEV:<br>
![alt text](Screenshots/5.png) 

#### DEV Pipeline Success:(Automatically Triggered)
![alt text](Screenshots/6.png)



#### QA Pipeline Success:(Manually Triggered after merging all MRs into DEV)
![alt text](Screenshots/7.png)