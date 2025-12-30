Bandit — Levels 4 → 7

# Bandit Level 4 → 5
## Level Goals 
Find the password stored in the only human-readable file inside the inhere directory.

## Steps Taken
* navigated into the inhere directory
* listed all files and used the file command to find the readable one

## Commands Used
* cd, ls, file, cat

## Lessons Learned
* the file command helps identify file types
* not all files with data are readable

# Bandit Level 5 → 6
## Level Goals 
Find the password in the file that is human-readable, exactly 1033 bytes, and not executable.
## Steps Taken
* seached within inhere using find with size and permission filters
* identify matching file
  
## Commands Used
* cd, find, cat
  
## Lessons Learned
* the find command can filter by size and permissions
* combining multiple conditions helps narrow down searches


# Bandit Level 6 → 7
## Level Goals
Find the password in the file that is owned by user bandit7, owned by group bandit6, and 33 bytes in size.
 
## Steps Taken
* Used find from root with ownership and size filters
* redirected permissions errors to avoid clutter
  
## Commands Used
* find, cat
  
## Lessons Learned
* files can exist anywhere
* redirected errors keeps output clean
