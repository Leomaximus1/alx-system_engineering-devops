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
