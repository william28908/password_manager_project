# Password Generator & Manager Project
  Welcome to my first Python project! This is a simple Python script that allows users to not only create and store their passwords, but also update, delete, and view the current records that are in a SQL database. In addition, users can do those same actions to any username or website name they also inputted. 
  
  The way the script works is by creating a key (using the cryptography library) and then storing it to your local computer. Then, the passwords that are inputted are encrypted using that same key. If a new password is created, it will be encyrpted and if a non-encrypted password is inputted, it is turned into an encrypted one. These encrypted passwords are then stored in the SQL database and, depending on the user choice, a person can add, delete, update, or view the current records. The only way to view the passwords in an unencrypted manner is to choose the "(v)iew" option that the user can choose during the prompts as this option is what decrypts the passwords. To see an example of the code running, download the notebook and open it with VSCode as Github does not show the user prompts properly.
  
  In the future, I plan on turning this script into a full app.
