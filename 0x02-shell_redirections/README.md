1. Write a script that prints “Hello, World”, followed by a new line to the standard output.
	#!/bin/bash
	echo "Hello,World"

2. Write a script that displays a confused smiley "(Ôo)'
	#!/bin/bash
	echo "\"(Ôo)'"

3. Display the content of the /etc/passwd file.
	#!/bin/bash
	cat /etc/passwd

4. Display the content of /etc/passwd and /etc/hosts
	#!/bin/bash
	cat /etc/passwd /etc/hosts

5. Display the last 10 lines of /etc/passwd
	#!/bin/bash
	tail -10 /etc/passwd 

6. Display the first 10 lines of /etc/passwd
	#!/bin/bash
	head -10 /etc/passwd

8. Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
	#!/bin/bash
	echo "Best School" > '\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)'

9. Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
	#!/bin/bash
	ls -la > ls_cwd_content

10. Write a script that duplicates the last line of the file iacta
	#!/bin/bash
	tail -1 iacta >> iacta

11. Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
	#!/bin/bash
	find -name "*.js" -type f -delete

12. Write a script that counts the number of directories and sub-directories in the current directory.The current and parent directories should not be taken into account. Hidden directories should be counted
	#!/bin/bash
	ls -t | head -10
13. Create a script that takes a list of words as input and prints only words that appear exactly once.
	#!/bin/bash
	sort | uniq -u 

