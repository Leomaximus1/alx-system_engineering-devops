#Scripts for Shell, permissions project 
#1 - Switches the current user to the user betty.
	#!/bin/bash
	su betty
#2 - prints the effective username of the current user.
	#!/bin/bash
	whoami
#3 - prints all the groups the current user is part of.
	#!/bin/bash
	groups
#4 - changes the owner of the file hello to the user betty.
	#!/bin/bash
	sudo chown betty hello
#4 - creates an empty file called hello.
	#!/bin/bash
	touch hello
#5 - adds execute permission to the owner of the file hello.
	#!/bin/bash
	chmod u+x hello
#6 - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
	#!/bin/bash
	chmod +114 hello
#7 - adds execution permission to the owner, the group owner and the other users, to the file hello 
	#!/bin/bash
	chmod +111 hello
#8 - sets the permission to the file hello as follows:Owner: no permission at all, Group: no permission at all, Other users: all the permissions
	#!/bin/bash
	chmod 007 hello
#9 - sets the mode of the file hello to this:-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
	#!/bin/bash
	chmod 753 hello
#10 - sets the mode of the file hello the same as olleh’s mode.
	#!/bin/bash
	chmod --reference olleh hello
#11 - Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
	#!/bin/bash
	chmod a+x */
#12 - Create a script that creates a directory called my_dir with permissions 751 in the working directory.
	#!/bin/bash
	mkdir -m 751 my_dir
#13 - Write a script that changes the group owner to school for the file hello
	#!/bin/bash
	chgrp school hello
#14 - Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
	#!/bin/bash
	chown vincent:staff *
#15 -Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.
	#!/bin/bash
	chown -h vincent:staff _hello
#16 - Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
	#!/bin/bash
	chown -from=guillaume betty hello  #error in this code solution 
#17 - Write a script that will play the StarWars IV episode in the terminal.
	#!/bin/bash
	telnet towel.blinkenlights.nl 
