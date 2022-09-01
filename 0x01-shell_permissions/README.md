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
#5 - adds execute permission to the owner of the file hello.
	#!/bin/bash
	chmod u+x hello 
