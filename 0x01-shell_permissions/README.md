su betty = switches the current user to the user betty

whoami OR id -un = prints the effective username of the current user

Id -nG OR groups = prints all the groups the current user is part of

sudo chown betty hello = changes the owner of the file hello to the user betty

chmod u+x  hello = adds execute permission to the owner of the file hello

touch hello OR echo -n > hello = creates an empty file called hello

chmod 754 hello = adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

chmod ugo+x hello =  adds execution permission to the owner, the group owner and the other users, to the file hello

chmod 753 hello =  sets the mode of the file hello to this:   -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

chmod --reference=olleh hello = sets the mode of the file hello the same as olleh’s mode

chmod -R +X */ = adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.

mkdir -m751 my_dir = creates a directory called my_dir with permissions 751 in the working directory.

sudo chgrp school hello = changes the group owner to school for the file hello

chown -hR vincent:staff = changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

chown -h vincent:staff _hello = changes the owner and the group owner of _hello to vincent and staff respectively.

chown --from=guillaume betty  hello = changes the owner of the file hello to betty only if it is owned by the user guillaume

telnet towel.blinkenlights.nl = play the StarWars IV episode in the terminal.
