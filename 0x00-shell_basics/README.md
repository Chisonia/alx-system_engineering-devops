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

ln -s /bin/ls _ls_ = Creates symbolic link to /bin/ls, named __ls__
