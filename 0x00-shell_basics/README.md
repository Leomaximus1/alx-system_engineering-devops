#SCRIPT LOG 
#Script 1 - To print the absolute path name of the current working directory 

	#!/bin/bash 
	pwd

#Script 2 - To display the content list of current directory 
	ls

#Script 3 - To change the working directory to the user's home directory
	cd ~
 
#Script 4 - To display current directory in a long format 
	ls -l
 
#Script 5 - To display current directory contents, including hidden filed (starting with .). Use the long format
	la -al
 
#Script 6 - To display current directory contents, long format, with user group IDs and hidden files 
	ls -lna
 
#Script 7 - To create a directory names "my first directory in /tmp/ directory 
	mkdir /tmp/my_first_directory/
 
#Script 8 - To move the file betty from /tmp/ to /tmp/my first directory
	mv /tmp/betty /tmp/my_first_directory/betty

#Script 9 - To delete the file betty
	rm/tmp/my_first_directory/betty 
#Script 10 - To delete the directory my first directory that is in /tmp directory
	rm -r /tmp/my_first_directory 
#Script 11 - To change the working directory to the previous one 
	cd -
#Script 12 - To list all files inclduing hidden in boot directory in long format 
	ls -al . ../boot
#Script 13 - To print the type of the file named iamafile. that will be in the /tmp directory 
	file /tmp/iamafile
#Scrpt 14 - To create a symbolic link to /bin/ls named -ls-
	lin -s /bin/ls _ls_
#Script 15 - To copy all HTML files from current working 

	
