## Course: User Management System
_

6. Commment your code where necessary. Good comments add context to code without explaining obvious things. A good rule of thumb is to explain ***WHY*** you do something and not **what** you are doing.


### Task: Implement a User Managment System for the Command Line
______

**ATTENTION:** Please **do not** use any of your actual passwords for this excercise, as they can be seen in plain text and may be saved in plain text on the computer.

Think of new, unique passwords that you never used and never will use.
______



1. Create a new java project named `UserManagement` without build tools. Create a simple Command Line interface within this project. Implement the following functionalities:
2. At the first start of the 
     1. change password
     2. check password
     2. leave password manager
3. The following contraints apply:
     1. The default password is "123456".
     2. when setting a new password, it needs to contain at least:
          1. 8 characters in total
          2. *_OPTIONAL_*: One number
          3. *_OPTIONAL_*: One special character (* , - , /, ...)
          4. *_OPTIONAL_*: One uppercase character
     3. when changing the password, the new password must differ from the old one
     4. if the password change is permitted, the user must confirm the new password by entering it again.
     5. the password object (a string) must be properly encapsulated by the correct access modifiers and getter/setter functions.

    The full documentation for String Class can be found [here](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)

4. **OPTIONAL**: To improve password storage security, upgrade your program by using a hashcode for storing the password instead of plain text.     
    

