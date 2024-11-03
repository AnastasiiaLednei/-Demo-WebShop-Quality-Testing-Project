
 
[DWQTP-14] No error message displayed for invalid "Card Holder Name" input, and payment is processed successfully despite invalid data. Created: 18/Sep/24  Updated: 23/Sep/24 
Status:	To Do
Project:	Demo WebShop Quality Testing Project

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	High 
Reporter: 	Anstasiia Lednei 
Assignee: 	Unassigned 
Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 Payment is proceed successfully.png      Payment is sucessful with invalid CardHolderName.png      no error message for invalid input.png     
Issue links: 	Blocks
blocks 	DWQTP-12 
Test Case 9: Place an Order 	To Do 


 Description  	 
Steps to Reproduce:
1.	Go to the checkout page.
2.	In the "Card Holder Name" field, enter invalid data: 
o	Enter numbers (e.g., "12345").
o	Enter a random string of characters (e.g., "gjggffghfgjhvjfhfjfj").
3.	Attempt to submit the order.
Expected Result:
•	An error message should appear indicating that the entered "Card Holder Name" is invalid.
•	The field should be highlighted in red for both numbers and random characters.
•	Payment should not be processed if the "Card Holder Name" is invalid.
Actual Result:
•	The field is highlighted in red only when entering numbers; no error message is displayed for random characters.
•	The payment is processed successfully despite the invalid "Card Holder Name".
________________________________________

 
[DWQTP-13] System allows proceeding to the payment method step with an invalid billing address and no error is displayed. Created: 18/Sep/24  Updated: 23/Sep/24 

Status:	To Do
Project:	Demo WebShop Quality Testing Project

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	High 
Reporter: 	Anstasiia Lednei 
Assignee: 	Unassigned 
Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 Incorect address.png      Proceed to payment.png     
Issue links: 	Blocks
blocks 	DWQTP-12 
Test Case 9: Place an Order 	To Do 


 Description  	 
Steps to Reproduce:
1.	Go to the cart page.
2.	Click on the "Proceed to Checkout" button.
3.	Enter an invalid billing address (e.g., incomplete address or incorrect postal code).
4.	Click to proceed to the payment method selection.
Expected Result:
•	The field with the invalid billing address should be highlighted in red.
•	An error message should appear indicating that the entered address is invalid.
•	Proceeding to the next step (payment method selection) should be blocked until the error is corrected.
Actual Result:
•	The system does not display an error message and does not highlight the field with the invalid billing address.
•	The user is able to proceed to the payment method selection despite entering an invalid address.

________________________________________

 
[DWQTP-1] Registration form does not show error messages for invalid data Created: 17/Sep/24  Updated: 23/Sep/24  Due: 23/Sep/24 
Status:	To Do
Project:	Demo WebShop Quality Testing Project

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	High 
Reporter: 	Anstasiia Lednei 
Assignee: 	Unassigned 
Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 Screenshot_5.png     
Issue links: 	Blocks
blocks 	DWQTP-4 
Test Case 1: Register a New User 	To Do 
Relates
relates to 	DWQTP-3 
Test Plan for Demo Web Store 	To Do 


 Description  	 
Steps to Reproduce:
1.	Go to the registration page.
2.	Enter incorrect data into one or more fields. For example, enter "11111" in a field where a different format is expected.
3.	Click the "Register" button.
Expected Behavior:
•	The field with incorrect data should be highlighted in red or display another visual error indicator.
•	An error message should appear explaining that the data is incorrect and how to fix it.
Actual Behavior:
•	The field with incorrect data is not highlighted in red.
•	No error message is displayed.
Notes:
•	Check if client-side and server-side validation is working.
•	Ensure that all required fields have appropriate validations and error messages.

________________________________________

[DWQTP-2] "Set New Password" button does not trigger any action or display a message Created: 17/Sep/24  Updated: 23/Sep/24 

Status:	To Do
Project:	Demo WebShop Quality Testing Project

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	Highest 
Reporter: 	Anstasiia Lednei 
Assignee: 	Unassigned 
Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 
Environment: 	•	Browser: Google Chrome 128.0.6613.138
•	Operating System (Операционная система): Windows 10 , version 22H2
•	Device : Desktop PC
•	Screen Resolution: 1920x1080
•	Application Version: v5.0
•	Network Conditions (Сетевые условия): Wi-Fi, 50 Mbps

Attachments: 	 Screenshot_7.png     
Issue links: 	Blocks
blocks 	DWQTP-6 
Test Case 3: Password Recovery 	To Do 
Relates
relates to 	DWQTP-3 
Test Plan for Demo Web Store 	To Do 


 Description  	 
Steps to Reproduce:
1.	Navigate to the password reset page.
2.	Enter a new password into the provided field.
3.	Click the "Set New Password" button.
Expected Behavior:
•	The button should trФigger the password reset action.
•	A confirmation message or a notification should appear indicating that the password has been successfully set, or that there was an issue.
Actual Behavior:
•	Clicking the "Set New Password" button does not trigger any action.
•	No confirmation message or notification is displayed.
•	The button appears to be non-responsive.
Notes:
•	Verify if the button's click event is properly bound and functioning.
•	Check for any JavaScript errors or issues in the browser console.
•	Ensure that the password reset process is correctly implemented on both client and server sides.

________________________________________

 

Generated at Sun Nov 03 15:05:15 GMT 2024 by Anstasiia Lednei using Jira 1001.0.0-SNAPSHOT#100272-rev:32ba8f90a7d1afb98edd0d36582aadeb545e0940. 
