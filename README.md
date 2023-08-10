# TestAutomation1
Automated Test for login page
Test Cases for a Registration and Login Page
Assuming there are the following fields in the registration and login page:

Username.
Password.
First Name.
Last Name.
Email Address.
Phone Number.
1. Test Cases for Registration Page:
Features to be Tested	Test Cases
Email field	
Test that the email field is in the correct format
Test that the email address is in the correct format
 Enter an invalid email address in the email field.
Enter an email address with special characters in the email field.
Enter an email address with spaces in the email field.
Leave the email field blank.
Terms and conditions	
Test that the terms and conditions are accepted
The user should be able to read the terms and conditions before ticking the checkbox.
The user should be able to tick the checkbox only if they have read and agreed to the terms and conditions.
The user should be able to see a confirmation message after ticking the checkbox and submitting the form.
Verify that the terms and conditions are visible on the registration page.
Verify that the terms and conditions can be scrolled through.
Verify that the terms and conditions can be printed.
Verify that the terms and conditions can be downloaded as a PDF.
Verify that the terms and conditions can be emailed to a user.
Password	
Password should be a minimum of 8 characters long.
Password should have at least 1 uppercase letter.
Password should have at least 1 lowercase letter.
Password should have at least 1 number.
Password should have at least 1 special character.
Password should not be same as username.
Test the password and confirm password fields match.
Confirmation message 	Test that the user can see a confirmation message after a successful registration
 Registration form	
Enter all valid details in the registration form and check if the user is able to register successfully
Enter all invalid details in the registration form and check if the user is able to register successfully
Try to register with an already existing username and check if the user is able to register successfully
 Login page 	Test that the user is redirected to the login page after a successful registration
2. Test Cases for Login Page:
Features to be Tested	Test Cases
Email field	
Test that the email is present.
The email field should accept valid email addresses.
The email field should not accept invalid email addresses.
The email field should display an error message when an invalid email address is entered.
The email field should be case-insensitive.
Password	
Test that the password field  is present.
Test that the password field is masked.
Test that a username field may allow for alphanumeric characters.
Test that the password field may require only numbers or letters.
Make sure that the password field is present and that it is labeled correctly.
Test that the password field accepts input.
Ensure that the password field masks input so that it is not visible as plain text.
Confirm that the password field has the correct level of security by testing for minimum length and character type requirements.
Verify that the password field does not auto-fill when using a password manager.
Test that the password field correctly validates input when submitting the form.
Login Form	
Test that the user is able to login with the correct credentials.
Test that the email and password fields are mandatory.
Test that the user is redirected to the correct page after login.
Enter all invalid details in the login form and check if the user is able to log in successfully.
Test that the user can see a forgot password link on the login page.
Try to log in with an already existing username and check if the user is able to log in successfully.
Error message 	Test that the user receives an error message if the login details are incorrect.
Factors to consider when writing test cases for registration and login page:
What happens if a user tries to register with an already existing username?
What happens if a user leaves one or more fields blank?
Is there a minimum or maximum length for any of the fields?
Are there any special characters that are not allowed in any of the fields?
Tips for Writing Better Test Cases
Well-organized test cases: Make sure the test cases are well-organized and easy to understand.
Clear language: Use clear and concise language when writing test cases.
Include all details: Include all relevant information in your test cases, such as input data, expected results, and steps to reproduce the issue.
Be thorough in testing: Be thorough when testing various functionality on the registration and login page.
Use automated tools: Take advantage of automation tools to streamline the process of writing and running test cases.
