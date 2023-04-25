# How to log into ieng6 account
Greetings,
Here is how to log into your ieng6 account to succesfully.
## Step 1: Download VS Code
Technically you can use a lot of things to ssh like a pro, but VS code makes life simpler here
You can download it [here](https://code.visualstudio.com/download)
![Image](/DownloadVSCode.png)
## Step 2: Set up your account
To do this, go to [this link](https://sdacs.ucsd.edu/~icc/index.php), and input your normal student information.
Click on your account (for CSE 15 students this quarter, this would begin with cs15lsp23)
Then, use the accompanying [global password reset](https://sdacs.ucsd.edu/~icc/password.php) tool to change your class account password (**NOT YOUR STUDENT ACCOUNT**)
![Image](/PasswordChange.png)
**NOTICE THAT THE ACCOUNT BEING USED HERE IS THE CSE 15L-SPECIFIC ID, NOT THE UCSD ACCOUNT**
You should get an email to your ucsd email to reset your password, and then you are good to go
## Step 3: SSH in VS Code
Open VS Code, and open a new terminal (As below)
![Image](/NewTerminal.png)
enter `ssh cs15lwi23zz@ieng6.ucsd.edu` (replace *zz* with your account name)
If you are asked about whether you want to connect, just say yes and move on (as you should with all things in life)
Then enter your password. You will not be able to see what you are entering, but it is being written, its just an old way of entering psswords.
If you think you accidentally wrote something you didn't mean to here, just spam backspace and try again.
If you see the following line, you are logged in:

![Image](/loginSuccess.jpg)

Otherwise, your password might me taking a while to reset, so wait and try again later
## Step 4: Have fun
Here is some example commands you can run:
* `cd ~`: go to home directory
* `ls`: Display subfolders of a directory
  * add `-l` to use long-listing
  * add `-a` to access all members of directory
  * add `-t` to sort by time
* combine (for instance, `-lat` displays the long-listed forms of all members of the directory sorted by time)
* `cat`: will display the text of the inputted file
* `logout`: log out of ieng6 account
![Image](/commands.jpg)
