***File: 0-current_working_directory***

This is a script that prints the absolute path name of the current working directory

***File: 1-listit***

This displays the contents list of your current directory

***File: 2-bring_me_home***

This script changes the working directory to the user's home directory

***File: 3-listfiles***

This Display current directory contents in a long format

***File: 4-listmorefiles***

This display current directory contents, including hidden files (starting with .)

***File: 5-listfilesdigitonly***
Displays current directory contents

^long format
^with user and group IDs displayed numerically
^And hidden files (starting with .)

***File: 6-firstdirectory***

Creates a script that creates a directory named 'my_first_directory' in the /tmp/ directory

***File: 7-movethatfile***

Moves the file 'betty' from /tmp/ to /tmp/my_first_directory

***File: 8-firstdelete***

Deletes the file 'betty'

^the file 'betty' is in /tmp/my_first_directory

***File: 9-firstdirdeletion***

Deletes the directory 'my_first_directory' that is in the /tmp directory

***File: 10-back***

Writes a script that changes the working directory to the previous one

***File: 11-lists***

Writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format

***File: 12-file_type***

Writes a script that prints the type of the file named 'iamafile'. The file 'iamafile' will be in the /tmp direcory when we will run your script

***File: 13-symbolic_link***

Creates a symbolic link to '/bin/ls', anmed _ls_. The symbolic link should be created in the current working directory

***File: 14-copy_html***

Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
You can consider that all HTML files have the extension '.html'

***File: 100-lets_move***

Creates a script that moves all the files beginning with an uppercase letter to the directory '/tmp/u'. You can assume that the directory '/tmp/u' will exist when we run your script

***File: 101-clean_emacs***

Creates a script that deletes all the files in the current working directory that end with the character '~'

***File: 102-tree***

Creates a script that creates the directories 'welcome/', 'welcome/to/' and 'welcome/to/school' in the current directory
You are only allowed to use the two spaces (and lines) in your script, not more

***File: 103-commas***

Writes a command that lists all the files and directories of the current directory, separated by commas (,)

^directory names should end with a slash (/)
^files and directories starting with a dot (.) should be listed
^the listing should be alpha ordered, except for the directories '.' and '..' which should be listed at the very beginning
^only digits and letters are used to sort; Digits should come first
^you can assume that all the files we will test with will have at least one letter or one digit
^the listing should end with a new line

***File: school.mgc***

Creates a magic file 'school.mgc' that can be used with the command 'file' to detect 'School' data files. 'School' data files always contain the string 'SCHOOL' at an offset 0.