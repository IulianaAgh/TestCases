# TestCases

**Description**
Ensure the application blocks login attempts with invalid username or password.

**Steps to reproduce:**
1. Open website.com/login
2. Add invalid user, correct password
3. Click 'Login' button
4. Repeat step 2 with next combinations:
   -invalid user, invalid password
   -correct user, invalid password
   -invalid user, invalid password

**Test Data**

User: invaliduser
Pass: validpassword

-------------------------------------------------

**Description**
The test checks that authentication is not allowed when username and password fields are left blank. The application
must display an appropiate error message and prevent access to the account.

**Steps to reproduce:**
1. Open website.com/login
2. Leave user and password fields blank
3. Click 'Login' button
4. Observe the behavior of the application and any error message displayed.

**Test Data**

User:   
Pass:   

-------------------------------------

**Description**
When the user enters a non-existent word, the system should display the message 'No result for this word' instead
of generating an error.

**Steps to reproduce:**
1. Open emag.ro
2. Access the search bar.
3. Enter a word not related to the products on the site.
4. Press Enter on the search button.

**Test Data**

abcde
