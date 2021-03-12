# Definition
This is a user interface specification document for the user management screen for PI Works job application. The Screen has two purposes. First one is add new user data to database and second one is sorting and observing the user list from data base. 

## Screen Parts
1. Upper Bar
   - New User Button
   - Disabled User Display Check Box
   - Save User Button
2. User List
   - ID Sorting Button
   - User Name Sorting Button
   - Email Sorting Button
   - User Status Sorting Button
   - Display User List
3. New User Information Screen
   - Username Text Box
   - Display Name Text Box
   - Phone Text Box
   - Email Text Box
   - User Role Option Box
   - User Status Check Box

## Detailed Explanation
  ### Upper Bar
  -------------
  This bar is on the top of the screen and have three actions. New User button and Disabled User Display Check Box are on the left side and Save User Button is on the right side.

  >#### New User Button
  >It is a button that clears the screen.

  >#### Disabled User Display Check Box
  >This box works for controlling the list. If it is checked, Display screen is going to show only users that status is enabled.

  >#### Save User Button
  >This button is for saving the user information that written on the screen. It uploads the user data which filled on boxes to database.


  ### User List
  -------------
  This list is on the left half of the screen. It is used for getting and viewing the list from database by wanted sorting options. That list includes in order of ID, User Name, Email and Status. Each list element have a sort button on the name of itself.

  >#### ID Sorting Button
  >That button sort the data list by ID. It has two options. On first click it will sort from smaller to bigger and on second click it will sort from bigger to smaller because of ID variable is integer.

  >#### Email Sorting Button
  >That button sorts data list by Emails. It has two options too. On first click it will sort from A to Z and on second click it will sort from Z to A because of Email variable is string.

  >#### User Status Sorting Button
  >That button sorts data list by User Status. It has two options too. On first click it will sort from enabled to disabled and on second click it will sort from disabled to enabled because of User Status variable is boolean which is 1 for enabled and 0 for disabled.

  >#### Display User List
  >That part is below the sorting buttons. It gets data from database and shows by wanted sorting options.


  ### New User Information Screen
  -------------------------------
  This part is on the right side of the screen. It is used for inserting new user data. It includes the input parts for new user which username text box, display name text box, phone text box, mail text box user role option box and user status check box.

  >#### Username Text Box
  >This box is a string input for username.
 
  >#### Display Name Text Box
  >This box is a string input for display name.
 
  >#### Phone Text Box
  >This box is a string input for phone number.
 
  >#### Email Text Box
  >This box is a string input for email.
 
  >#### User Role Option Box
  >This box is an input for user role. It has three options which are Guest, Admin, SuperAdmin. 
 
  >#### User Status Check Box
  >This check box is an input for user status labeled 'Enabled'. If its checked, New user's status is going to be enabled.
 

## Screen Figure
![User Management Screen](/pic1.png)
