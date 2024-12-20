## Course: User Management System
### Task: Implement a User Managment System for the Command Line
______

**ATTENTION:** Please **do not** use any of your actual passwords for this excercise, as they can be seen in plain text and may be saved in plain text on the computer.

Think of new, unique passwords that you never used and never will use.
______

For this group project, you may use either C# or Java in a IDE of your choice. An installation guide for Java and Visual Studio **Code** is available as Course 0: Setup.


1. Create a new project named `UserManagement`. Implement a simple Command Line interface within this project with the following functionalities:
2. At the first start of the program, print out the "admin" user name and add it to the account list. Ask the user to set a password for this admin account.
3. Implement the following functionalitites within the main menu:
     1. show all users
     2. change user
     2. add user
     3. remove user
     4. change current users password
     5. exit program
     6. As the last Menu Point, just print the current user.
4. To select a functionality, the user shall enter the number designating the submenu.
5. The following contraints apply:
     1. each user must enter a password upon account creation.
     2. to change user, the new users password needs to be confirmed.
     3. admin account can not be removed and only the admin account is allowed to delete users.
     4. if the password change is permitted, the user must confirm the new password by entering it again.
     5. the program shall loop and only terminate when exiting the program via menu option "exit".
     6. the password shall be stored only as a hash and not as plain text.
6. The program should be implemented in two steps:
   1. at first in a procedual manner (with static methods within one class)
   2. using an object-oriented approach

7. Upload both of your solutions two your assigned repository on github.
   
    The full documentation for String Class (in Java) can be found [here](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)

    

