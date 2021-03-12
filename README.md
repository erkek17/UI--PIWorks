Definition---> This is a user interface specification document for the user management screen for PI Works job application. The Screen has two purposes. First one is add new user data to database and second one is sorting and observing the user list from data base. 

# Screen Parts
1. Upper Bar
  
  1.1 New User Button 
   
  1.2 Disabled User Display Check Box 
   
  1.3 Save User Button 

2. User List
   
  2.1 ID Sorting Button
  
  2.2 User Name Sorting Button
  
  2.3 Email Sorting Button
  
  2.4 User Status Sorting Button
  
  2.5 Display User List

3. New User Information Screen

  3.1 Username Text Box

  3.2 Display Name Text Box
  
  3.3 Phone Text Box
  
  3.4 Email Text Box
  
  3.5 User Role Option Box
  
  3.6 User Status Check Box 

# Detailed Explanation
 
 1.Upper Bar-->This bar is on the top of the screen and have three actions. New User button and Disabled User Display Check Box are on the left side and Save User Button is on the right side.


  1.1--It is a button that clears the screen.
 
  1.2--This box works for controlling the list. If it is checked, Display screen is going to show only users that status is enabled.
 
  1.3-- This button is for saving the user information that written on the screen. It uploads the user data which filled on boxes to database.
  
  
 2.User List--> This list is on the left half of the screen. It is used for getting and viewing the list from database by wanted sorting options. That list includes in order of ID, User Name, Email and Status. Each list element have a sort button on the name of itself.
 
 
  2.1--That button sort the data list by ID. It has two options. On first click it will sort from smaller to bigger and on second click it will sort from bigger to smaller because of ID variable is integer.

  2.2--That button sorts data list by Emails. It has two options too. On first click it will sort from A to Z and on second click it will sort from Z to A because of Email variable is string.

  2.3--That button sorts data list by User Status. It has two options too. On first click it will sort from enabled to disabled and on second click it will sort from disabled to enabled because of User Status variable is boolean which is 1 for enabled and 0 for disabled.

  2.4--That part is below the sorting buttons. It gets data from database and shows by wanted sorting options.


  3.New User Information Screen--> This part is on the right side of the screen. It is used for inserting new user data. It includes the input parts for new user which username text box, display name text box, phone text box, mail text box user role option box and user status check box.

  3.1-- string input for username.
 
  3.2-- string input for display name.
 
  3.3-- string input for phone number.
 
  3.4-- string input for email.
 
  3.5-- input for user role. It has three options which are Guest, Admin, SuperAdmin. 
 
  3.6-- input for user status labeled 'Enabled'. If its checked, New user's status is going to be enabled.
 
// Screen Figure//
![User Management Screen](/pic1.png)
