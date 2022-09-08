## Shell, basics and script descriptions ##

An introductory crash course in the Shell on how to navigate directories using `cd`, `pwd`, `ls`, how to look around using `ls`, `less`, and `file`, and how to manipulate files with `cp`, `mv`, `rm`, and `mkdir`. Further practices includes working with the `type`, `which`, `help`, and `man` commands, implementing `wildcards`, reading `man` pages, creating links, and using keyboard shortcuts in Bash.

- [Current_working_directory](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/0-current_working_directory) :  prints the absolute path name of the current working directory
- [Listit](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/1-listit): Display the contents list of your current directory.
- [Bring_me_home](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/2-bring_me_home): changes the working directory to the user’s home directory
- [Listfiles](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/3-listfiles): Display current directory contents in a long format
- [Listmorefiles](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/4-listmorefiles): Display current directory contents, including hidden files (starting with .)
- [Listfilesdigitonly](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/5-listfilesdigitonly): Display current directory contents.
- [Firstdirectory](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/6-firstdirectory): creates a directory named my_first_directory in the /tmp/ directory.
- [Movethatfile](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/7-movethatfile): Move the file betty from /tmp/ to /tmp/my_first_directory
- [Firstdelete](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/8-firstdelete): Delete the file betty
- [Firstdirdeletion](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/9-firstdirdeletion): Delete the directory my_first_directory that is in the /tmp directory.
- [Back](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/10-back): changes the working directory to the previous one.
- [Lists](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/11-lists): lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
- [File_type](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/12-file_type): prints the type of the file named iamafile
- [Symbolic_link](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/13-symbolic_link): Create a symbolic link to /bin/ls, named __ls__.
- [Copy_html](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/14-copy_html): copies all the HTML files from the current working directory to the parent of the working directory.
- [100-lets_move](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/100-lets_move): script that moves all files beginning with an uppercase letter to the directory /tmp/u.
- [101-clean_emacs](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/101-clean_emacs): script that deletes all files in the current working directory that end with the character ~.
- [102-tree](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/102-tree): script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
- [103-commas](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/103-commas): command that lists all the files and directories of the current directory, separated by commas (,).
- [school.mgc](https://github.com/Callistus25/alx-system_engineering-devops/blob/main/0x00-shell_basics/school.mgc): magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0. for this task, create a shebang and add the command 
"0 string SCHOOL School data
!:mime School"

afterwards, run the command "file -C -m {filename}" i.e file -C -m school.mgc
