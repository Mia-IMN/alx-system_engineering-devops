*File: 0-1am_betty*

This script switches the current user to the user betty

*File: 1-who_am_i*

This script prints the effective username of the current user

*File: 2-groups*

This script prints all the groups the current user is a part of

*File: 3-new_owner*

This script changes the owner of file 'hello' to the user 'betty'

*File: 4-empty*

This script creates an empty file called hello

*File: 5-execute*

This script adds execute permission to the owner of the file hello

*File: 6-multiple_permissions*

This script adds execute permission to the owner and the group owner, and read permission to other users to the file 'hello'

*File: 7-everybody*

This script adds execution permission to the owner, the group owner and the other users, to the file hello

*File: 8-James_Bond*

This script sets the permission to the file hello as follows:
    **Owner:** no permission at all
    **Group:** no permission at all
    **Other users:** all the permissions

*File: 9-John_Doe*

This script sets the mode of the file hello to this: 
**-rwxr-x-wx 1 user user ...**

*File: 10-mirror_permissions*

This script sets the mode of the file 'hello' the same as "olleh's" mode

*File: 11-directories_permissions*

This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files are not changed.

*File: 12-directory_permissions*

This script creates a directory called my_dir with permissions 751 in the working directory

*File: 13-change_group*

This script changes the group owner to school for the file hello

*File: 100-change_owner_and_group*

This script changes the owner to vincent and the group owner to staff for the files and directories in the working directory

*File: 101-symbolic_link_permissions*

This script changes the owner and group owner of _hello to vincent and staff respectively

*File: 102-if_only*

This script changes the owner of the file hello to betty only if it is owned by the user guillaume

*File: 103-Star_Wars*

This script will play the StarWars IV episode in the terminal
