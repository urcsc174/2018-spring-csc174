# In-class Exercise 11: Login System

*Due: today, in-class*

The purpose of this lab assignment is to practice building a PHP/MySQL login system for a website.

- Start your MAMP or WAMP server
- Create a database, database user/password, and assign privileges to the user.
  - In phpMyAdmin, remember you can do all three things all at once: 
    1. Create the user account
    2. Change the host name to "localhost"
    3. Click the checkbox, "Create database with same name and grant all privileges"

## Follow online instructions to build the demo

The goal here is to *not* blindly copy and paste the code from the tutorial, but actually read and understand how the pieces and parts work together.  You don't have to know exactly what each line of code does (most of it is error handling) but you do need to know what each snippet does from a high level.

- Go to: the [Tutorial Republic: PHP MySQL Login System tutorial](https://www.tutorialrepublic.com/php-tutorial/php-mysql-login-system.php) and follow the instructions
- Test your login system. 

## Add a new webpage to your demo

When your login system works as-is from the tutorial, make these changes:

- Create a new webpage in your login system website - add some content, any content, just so it looks different than the welcome.php page.
- Link the new webpage to the **welcome.php** page and vice versa so you can go back and forth between the two pages (in effect, a simple navigation menu)
- Make the new webpage inaccessible unless the user is logged-in
  - If the user goes to the new page directly (by URL) it should automatically re-route the user to the login page
- Add a button, "Sign Out of Your Account" to the the new webpage - same as the button on the welcome.php page

## Demonstrate Your Login System Website

- Show the TA or Professor your functioning login system for *participation* credit.