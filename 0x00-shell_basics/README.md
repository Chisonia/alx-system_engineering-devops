#!/bin/bash

pwd = prints the absolute path name of the current working directory

ls = displays content list of current working directory

cd~ = changes the working directory to the user’s home directory

ls -l= Display current directory contents in a long format

ls -la = Display current directory contents, including hidden files (starting with .). Use the long format

ls -lan = Long format- with user and group IDs displayed numerically
And hidden files (starting with .)

mkdir /tmp/my_first_directory = Create a script that creates a directory named my first directory in the /tmp/ directory

mv /tmp/betty /tmp/my_first_directory = Move the file betty from /tmp/ to /tmp/my first directory

rm /tmp/my_first_directory = Delete the file betty

rm -r = Delete the directory my_first_directory that is in the /tmp directory

cd - = changes the working directory to the previous one

ls -la . .. /boot = lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format

file /tmp/iamafile = prints the type of the file named iamafile in /temp directory

ln -s /bin/ls _ls_ = Creates a symbolic link to /bin/ls, named __ls__

cp -un *.html ../ = Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

mv [[:upper:]]* /tmp/u =  moves all files beginning with an uppercase letter to the directory /tmp/u

rm *~ = deletes all files in the current working directory that end with the character ~

mkdir -p welcome/to/school = creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory

ls -lamvp = command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line

0 string SCHOOL school data  !:mime School = Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0
