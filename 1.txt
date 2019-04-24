What is regression? What is retesting?

Regression testing - testing after there were made some changes, example : new features, bugs rezolved. 

Retesting or Confirmation testing - Testing after DevOps fixed a bug or a missing functionality. 

---

What is the relationship between the following: error, bug, defect, fault, failure.

All of the above features are meaning that a feature/ unit/ product doesn't work / doesn't meet the requirements of the product.

---

Name the difference between agile & v-model. (Please specify some roles and cycles for these)

V- Model - There is testing in paralel and can't come back at a point until it's the full cycle done.
Example - Design with integration testing; 
		System requirements with System testing;

Agile model - is testing in cycles of 2 to 4 weeks.
Analysis - DevOp - Test - Design - Feedback - 

----

Please state what is black box testing? How about white box testing? You can also give an example.

Black box testing - is testing based on the product requirements without having access to the code;

White box testing - is testing with access of the source code;

Example of black testing - Requirements sheet / file from the Project Manager.

Example of white testing - Testing of the requirements on the code itself; 



------------

In the images folder you have a login form. Create Test Cases for the given form.

Please state the testing types(functional, non-functional, black box, white box, design technique) for each TC created.

Test Cases -  Black Box (can easily be done by seeing the code / white box)  - 1 - testing the name box   - if contains only [a-zA-Z];
										- left it blank;
										- inserting numbers;
										- inserting special characters;
										- testing lenght;

									- 2 - testing the email : - blank;
									  - only name withouth @; 
									  - lenght;
									  - checking if the email is used already - registering 2 users with the same email; 
								
							- 3 - Password box - blank;
							   - checking the lenght / range - 1 character to maximum;

  Test Case - Black box  - Sing up button 	Functional		  - all other boxes are left blank; 
  											Functional		  - every boxe completed correctly; 
  											Non Functional		  - only name input and then click on signup;
  											Non Functional		  - only email input and then click on signup;
  											Non Functional		  - only password and then click on signup;
  											Non Functional		  - only name + email / name + password / password + email / 
  				White box - checking the logic on the above test with signup;									  
  			
  	Black box - Functional - Sign in - Clicking on should redirect us to the login interface/page.

  	Design - the screen moves;

  	Black Box - Functional testing - Clicking on any of the buttons for facebook / google + / linkin should redirect us to a new login interface/page;




-----

Consider that you have found a defect in the form for the previous exercise. Create a bug report for it.

Title - Cannot Sign up
Build - 
Severity - Critical; 
Priority - High.
Test steps - open login/signup page;
		- Inserted name : test1 
		- Inserted email : test1@emailtest.com
		- Inserted password : password1
Actual results - sign up button didn't redirect us to a new page / new interface;
Expected results - Sign up button should redirect for new page / new interface;
Logs - 
Screenshot - if the bug can't be reproduced or takes a longer explanation;







