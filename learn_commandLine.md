#Command line commands
  
Print Working Directory
   
>	pwd
   
Lists all files and directories in the working directory
   
>	ls
 

Change Directory

>	cd

Create new directory in working directory

>	mkdir 

Create a new file inside the working directory
>	touch 

<br/l>

List all contents of a directory, including hidden files and directories
>	ls -a

List all contents in long format
>	ls -l

Order files and directories by the time they were last modified
>	ls -t

Combine all three options
>	ls -alt

<br/l>

Copy files
>	cp

Move and rename files
>	mv 

Remove files
>	rm

Remove directories
>	rm -r 

Wildcard, use to select and group files by name
>	\*      

<br/l>

Redirect standard output of a command to a file, overwriting previous content
>	\>

Redirect standard output of a command to a file, append new content to old content
>	\>> 

Redirect standard input to a command
>	<

Redirect standard output of a command to another command
>	|

<br/l>

Sort lines of text alphabetically
>	sort

Filter duplicate, adjacent lines of text
>	uniq

Search for a text pattern and outputs it
>	grep

Search for a text pattern, modify it, and output it
>	sed

<br/l>

Command line text editor
>	nano

Environment settings location, can edit with nano
>	~/.bash_profile

Set and export an environment variable
>	export VARIABLE="Value"

Name of current user
>	USER

Command prompt
>	PS1

Home directory
>	HOME 

Return a colon separated list of file paths
>	PATH

Return a list of environment variables
>	env

<br/l>

Set custom commands and shortcuts to  regular commands
>	alias newCommand="command"