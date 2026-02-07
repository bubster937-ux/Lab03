## Lab 03

- Name: Andre bond
- Email: bond.57@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab03/Instructions.html

## Part 1 - git Guide

| git command         | Description |
| ---                 | ---         | 
| `git clone repo_URI`|clones your repository username and puts it in the list of files and directories|
| `git status`        |displays the state of the working directory|
| `git add filename`  |adds changes from the working directory to the index|
| `git commit`        |records changes|
| `git push`          |uploads local repository changes to a remote repository|
| `git pull`          |pulls from a remote repository|

## Part 2 - clone

1. Command to generate an SSH key with ed25519: ssh-keygen -t ed25519 -C "bond.57@wright.edu"
2. Command(s) to read & copy text of the *public* key: ~/.ssh$ cat id_ed25519.pub
3. Summary of steps to place *public* key in user profile: go into github, settings, ssh and gpg keys, new ssh key, paste cintents of id_ed25519.pub, save the key
4. Command to *clone* your `ceg2350s25-YOURGITHUBUSERNAME` with SSH for authentication: git clone git@github.com:WSU-kduncan/ceg2350-s26-bubster937-ux.git

## Part 3 - IO Redirection

1. `printenv HOME > thishouse`
   - Explanation: It Writes the value of the HOME environment variable into a file called thishouse, overwriting the file if it already exists.
2. `cat doesnotexist 2>> hush.txt`
   - Explanation: It Attempts to read a file that doesn’t exist; the error message (stderr) is appended to hush.txt
3. `cat nums.txt | sort -n >> all_nums.txt`
   - Explanation: It Sends the contents of nums.txt through a numeric sort and appends the sorted numbers to all_nums.txt.
4. `cat << "DONE" > here.txt`
   - Explanation: It Starts a here-document that writes user input into here.txt until the word DONE is entered. Quoting prevents variable expansion.
5. `ls -lt ~ | head`
   - Explanation: It Lists files in the home directory sorted by modification time (newest first) and displays only the first 10 entries.
6. `history | grep ".md"`
   - Explanation: It Filters the command history to show only commands that reference .md files.

## Part 4 - Rolling the Dice

Verify that `roll` made it to your GitHub repository for this course and is in your `Lab03` folder.  No answers will be written here unless you would like to leave a note to the TAs

## Part 5 - Retrospective Answers

1. Where and when did it go wrong while working on your script tasks? 
> Your reflection here: around step 4 or 5 stuff just wasnt working how i wanted 
2. Was anything familiar working with a new language compared to one you are used to?
> Your reflection here: if statements
3. Did you write good `commit` messages that refer to what tasks were completed at each commit?  What would you improve?
> Your reflection here: yes i woudlnt improve anything

## Part 6 - Citations / Resources

w3schools for part 1 and geeks for geeks for part 4

## Extra Credit

1. Note here *what* you did to the script for the extra credit.
