[DWQTP-3]  Test Plan for Demo Web Store Created: 17/Sep/24  Updated: 17/Sep/24 

Status:	To Do
Project:	Demo WebShop Quality Testing Project

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Epic 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Unassigned 
Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Issue links: 	Relates
relates to 	DWQTP-2 
"Set New Password" button does not tr... 	To Do 
relates to 	DWQTP-1 
Registration form does not show error... 	To Do 


 Description  	 
1.	Introduction
•	Purpose: Validate the functionality, usability, and performance of the demo web store available at https://practicesoftwaretesting.com/ .
•	Scope: This test plan will cover core functionalities provided by the demo web store, such as product browsing, shopping cart management, and checkout process.
1.	Test Objectives
•	Verify that the web store's core functionalities operate correctly.
•	Ensure the user interface is responsive and user-friendly.
•	Test the performance of the web store under typical usage scenarios.
1.	Test Items
•	User Registration and Login: Check if user registration, login, and password recovery processes work as expected.
•	Product Search and Filtering: Test the functionality of searching for products and applying filters.
•	Shopping Cart Management: Ensure users can add, update, and remove items from the cart.
•	Order Placement: Validate the process of placing an order and handling checkout.
•	User Interface Responsiveness: Check how the site responds on different devices and screen sizes.
•	Performance Testing: Measure page load times and responsiveness.
•	Basic Security Checks: Perform basic checks for data protection and secure authentication.
1.	Test Approach
•	Manual Testing: Conduct tests manually based on predefined test cases.
•	Tools: Jira.
1.	Test Schedule
•	Preparation: 17.09.24 - 30.09.24
•	Execution: 17.09.24 - 30.09.224
•	Reporting: 30.09.2024
1.	Resources
•	Testers: Anastasiia Lednei.
•	Test Environment: Use the demo version of the web store at https://practicesoftwaretesting.com/ .
1.	Test Cases
7.1 User Registration and Login
•	Test Case 1: Register a New User 
o	Steps: Navigate to the registration page, fill in details (e.g., name, email, password), and submit.
o	Expected Result: Successful registration with a confirmation message.
•	Test Case 2: Login with Valid Credentials 
o	Steps: Navigate to the login page, enter valid credentials, and submit.
o	Expected Result: Successful login with redirection to the home page.
•	Test Case 3: Password Recovery 
o	Steps: Navigate to the password recovery page, enter email, and follow recovery instructions.
o	Expected Result: Password reset email is received, and password is successfully reset.
7.2 Product Search and Filtering
•	Test Case 4: Search for a Product 
o	Steps: Enter a product name or keyword into the search bar and submit.
o	Expected Result: Relevant products are displayed based on the search query.
•	Test Case 5: Apply Filters 
o	Steps: Use filters like category, price range, and brand.
o	Expected Result: Products displayed match the selected filters.
7.3 Shopping Cart Management
•	Test Case 6: Add a Product to the Cart 
o	Steps: Select a product, specify the quantity, and click “Add to Cart.”
o	Expected Result: Product is added to the cart, and cart totals are updated.
•	Test Case 7: Update Product Quantity 
o	Steps: Navigate to the cart, change the quantity of an item, and update the cart.
o	Expected Result: Cart updates to reflect the new quantity and total cost.
•	Test Case 8: Remove a Product from the Cart 
o	Steps: Navigate to the cart, remove an item, and update the cart.
o	Expected Result: Product is removed, and the cart total is updated.
7.4 Order Placement
•	Test Case 9: Place an Order 
o	Steps: Proceed to checkout, enter shipping and payment details, and submit the order.
o	Expected Result: Order is placed successfully, and a confirmation message is displayed.
7.5 User Interface Responsiveness
•	Test Case 10: Test Responsiveness 
o	Steps: Open the site on various devices (desktop, tablet, mobile).
o	Expected Result: The site displays correctly and is functional on all devices.
7.6 Performance Testing
•	Test Case 11: Measure Page Load Times 
o	Steps: Use a tool to measure the load times of key pages (e.g., homepage, product pages).
o	Expected Result: Pages load within acceptable limits (e.g., under 3 seconds).
7.7 Basic Security Checks
•	Test Case 12: Verify Data Protection 
o	Steps: Check how personal data is handled and stored securely.
o	Expected Result: Data is protected and encrypted as necessary.
•	Test Case 13: Test Authentication Security 
o	Steps: Attempt login with invalid credentials.
o	Expected Result: Errors are displayed, and access is not granted.
1.	Reporting
8.1 Defect Reporting 
o	Defect Reporting Process: All discovered defects will be documented and tracked using the defect management system Jira. When creating a defect record, the following information should be included: 
	Defect title
	Detailed defect description
	Steps to reproduce
	Expected and actual results
	Screenshots or logs (if applicable)
	Priority and severity level
	Current defect status (open, in progress, closed)
2.	8.2 Test Results Reporting 
o	Test Results Format: Test results will be provided in reports within Jira. The reports will include: 
	Overview: A summary of the testing, including main objectives and coverage areas.
	Test Results: Statistics on executed tests, including the number of passed and failed tests.
	Discovered Defects: A list of all defects found during testing, with their current status.
	Recommendations: Recommendations for addressing discovered defects and improving product quality.
3.	8.3 Test Metrics 
o	Testing Metrics: The following metrics will be used to assess the testing process: 
	Number of tests executed
	Percentage of successful tests
	Number of defects found
	Time spent on testing
4.	8.4 Communication 
o	Communication Process: Updates on testing progress and results will be regularly provided to stakeholders via Jira. Major updates will be sent at the end of each testing phase or as critical defects are discovered.
o	Recipients: Test reports will be sent to project managers, developers, and other key stakeholders involved in the project.
5.	Approval
•	Prepared By: Anastasiia Lednei
•	Date: 17.09.2024
•	Approved By: Anastasiia Lednei
•	Date: 17.09.2024
________________________________________
