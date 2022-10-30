
Test Scenario ID	Create account	Test Case ID	Create account 2
Test Case Description	Negative test case	Test Priority	High
Pre-Requisite	NA	Post-Requisite	A valid user account
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application	Schedula login page	Schedula login page		Pass	
2	Choose “Create an account” option	Create an account	Schedula create account page	Schedula create account page		Pass	
3	Enter Username, password and repeat password incorrectly	Username: username
Password:
***** 
Repeat password: *****(correct)	Create account failed	Create account failed		Failed	“Failed to create account: Passwords don’t match.”
Test Scenario ID	Login in an account	Test Case ID	Login 1
Test Case Description	Negative test case	Test Priority	High
Pre-Requisite	Have an account	Post-Requisite	Login to the account
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application	Schedula login page	Schedula login page		Pass	
2	Enter incorrect Username &  correct/ incorrect Password and hit login button	Username: uzername (incorrect)
Password:
***** 	Login failed – “Wrong username or password. Try again.”	Login failed – “Wrong username or password. Try again.”		Failed	

Test Scenario ID	Login in an account	Test Case ID	Login 2
Test Case Description	Negative test case	Test Priority	High
Pre-Requisite	Have an account	Post-Requisite	Login to the account
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application	Schedula login page	Schedula login page		Pass	
2	Enter correct Username &  incorrect Password and hit login button	Username: username (correct)
Password:
*** (incorrect) 	Login failed – “Wrong password. Try again.”	Login failed – “Wrong password. Try again.”		Failed	






Test Scenario ID	Login in an account	Test Case ID	Login 3
Test Case Description	Positive test case	Test Priority	High
Pre-Requisite	Have an account	Post-Requisite	Login to the account
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application	Schedula login page	Schedula login page		Pass	
2	Enter correct Username &  correct Password and hit login button	Username: username (correct)
Password:
***** (correct) 	Successful login – Schedula welcoming page	Successful login – Schedula welcoming page		Pass	


Test Scenario ID	Change password	Test Case ID	CP 1
Test Case Description	Positive test case	Test Priority	Medium
Pre-Requisite	Have an account	Post-Requisite	New password
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application	Schedula login page	Schedula login page		Pass	
2	Enter correct Username &  correct Password and hit login button	Username: username (correct)
Password:
***** (correct) 	Successful login – Schedula welcoming page	Successful login – Schedula welcoming page		Pass	




3	Click on the settings
	Settings	Settings page	Settings page		Pass	
4	Click on “Change my password”	Change my password	Change Password page	Change Password Page		Pass	
5	Enter correct Password	Old password: *****
New password: *****
Repeat new password: *****	“Password changed successfully”	“Password changed successfully”			New password must be repeated two times
Test Scenario ID	Change password	Test Case ID	CP 2
Test Case Description	Negative test case	Test Priority	Medium
Pre-Requisite	Have an account	Post-Requisite	New password
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application 	Schedula login page	Schedula login page		Pass	
2	Enter correct Username &  correct Password and hit login button	Username: username (correct)
Password:
***** (correct) 	Successful login – Schedula welcoming page	Successful login – Schedula welcoming page		Pass	




3	Click on the settings
	Settings	Settings page	Settings page		Pass	
4	Click on “Change my password”	Change my password	Change Password page	Change Password Page		Pass	
5	Enter incorrect new password	Old password: *****
New password: *****
Repeat new password: ********	“Passwords don’t match”	“Passwords don’t match”			New password must be repeated two times


Test Scenario ID	Delete account	Test Case ID	DA1
Test Case Description	Positive test case	Test Priority	Low
Pre-Requisite	An account that exists	Post-Requisite	Account deleted
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application	Schedula login page	Schedula login page		Pass	
2	Enter correct Username & correct Password and hit login button	Username: username (correct)
Password:
***** (correct) 	Successful login – Schedula welcoming page	Successful login – Schedula welcoming page		Pass	




3	Click on the settings
	Settings	Settings page	Settings page		Pass	
4	Click on “Delete Account”	Delete Account	Login Page	Login Page		Pass	“Account deleted successfully”


Test Scenario ID	Delete account	Test Case ID	DA2
Test Case Description	Negative test case	Test Priority	Low
Pre-Requisite	An account that exists	Post-Requisite	Account deleted
Test Execution Steps	
S.No	Action	Inputs	Expected Output	Actual Output	Test Browser	Test Result	Test Comments
1	Launch Application	Application	Schedula login page	Schedula login page		Pass	
2	Enter incorrect Username & correct Password and hit login button	Username: uzername (correct)
Password:
***** (correct) 	Successful login – Schedula welcoming page	Successful login – Schedula welcoming page		Pass	




3	Click on the settings
	Settings	Settings page	Settings page		Pass	
4	Click on “Delete Account”	Delete Account	Login Page	“Account does not exist”		Fail	

