\# Bandit — Levels 0 → 3



\## Bandit Level 0 → 1

\### Level Goal

The password for the next level is stored in a file called `readme` located in the home directory.



\### Steps Taken

\- Logged into Bandit0 using SSH  

\- Listed files in the home directory  

\- Read the `readme` file to retrieve the password  



\### Commands Used

ssh, ls, cat



\### Lessons Learned

\- Learned how to connect to a remote server via SSH  

\- Practiced reading basic files in Linux  



---



\## Bandit Level 1 → 2

\### Level Goal

Find the password is stored in a file called `-` located in the home directory.



\### Steps Taken

\- Listed files in the home directory (`ls`)  

\- Used `cat ./-` to safely read the file  



\### Commands Used

ls, cat



\### Lessons Learned

\- Filenames that start with special characters require careful handling  

\- Relative paths (`./`) allow safe access to tricky filenames  



---



\## Bandit Level 2 → 3

\### Level Goal

Find the password stored in a file called `--spaces in this filename--` located in the home directory.



\### Steps Taken

\- Listed files to find unusual filename  

\- Used quotes or escape characters to read file contents (`cat "--spaces in this filename--"`)  



\### Commands Used

ls, cat



\### Lessons Learned

\- Linux filenames can contain spaces and special characters  

\- Quoting or escaping filenames allows correct file access  



---



\## Bandit Level 3 → 4

\### Level Goal

Find the password stored in a hidden file in the `inhere` directory.



\### Steps Taken

\- Navigated into the `inhere` directory (`cd inhere`)  

\- Listed hidden files (`ls -a`)  

\- Read the hidden file  



\### Commands Used

cd, ls, cat



\### Lessons Learned

\- Hidden files start with a dot (`.`) in Linux  

\- Directory navigation and hidden file exploration are key fundamentals  


=======
\# Bandit Level 0 → 1



\## Goal

access the server and locate the password for the next level.



\## What I Did

\- connected to the server using SSH

\- logged in with the provided credentials

\- listed files in the home directory

\- read the contents of the README file



\## Commands Used

\- ssh

\- ls

\- cat



\## What I Learned

\- how to connect to a remote Linux server

\- basic file listing and file reading commands
>>>>>>> b746dd884ec8ae07596f66b0c6168a4cd4236a5d

