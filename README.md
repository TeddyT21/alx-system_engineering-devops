
0.  Create a script that creates an alias. Name: ls  Value: rm *
		Answer :    alias ls = 'rm *'
1.	Create a script that prints hello user, where user is the current Linux user.
		Answer	:	echo "hello $USER"
2.	Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
		Answer	:  echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))
3.	Create a script that counts the number of directories in the PATH.
		Answer	:	printenv
4.	Create a script that lists environment variables.
		Answer	:	set
5.	Create a script that lists all local variables and environment variables, and functions.
		Create a script that creates a new local variable.
		Name: BETTY   Value: Holberton
			Answer	:	BEST="School"
