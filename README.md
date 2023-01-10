# Banking-App-With-TKinter-GUI
Banking App is a graphical users inface banking system app like any realistic banking app.  It allows users to register and create new accounts, as well as log in to existing accounts. When a user registers, the program prompts them to enter their name, age, gender, and password. It then checks if any of the fields are left empty or if the account already exists. If everything is valid, a new file with the user's name is created and the user's details are saved in the file. The login function checks if the entered name and password match any existing accounts and opens the account dashboard if they match.

The code uses the os library to list all the files in the directory the script is running in to check for existing accounts and to create new files for new accounts. It also uses the PIL library to handle images, which is not used in the given code snippet.

It's a good idea to use a more secure way of storing the password as this simple way of storing it in plaintext can be easily vulnerable to a number of attacks. Also, it is better to use some kind of data validation for the input fields like validating the age and gender to be integers, etc.

* It allows user to register an account
* Allows the user to make money deposits, also update new deposits 
* Allow user to withdraw money and update withdrawals 
* Allows user to view their account balance ans personal detatils
* Status messages
* It saves all information in a User file saved in same directory with the banking app file
It is created using python built-in library TKINTER
Requirements:
* pillow

You can clone this python project and run on a terminal

Python Version 3.11 
