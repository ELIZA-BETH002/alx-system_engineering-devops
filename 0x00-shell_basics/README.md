0-current_working_directory: "pwd" - this command is used to show the current working directory 
1-listit: "ls" - This command is used to display the content list of the current working directory
2-bring_me_home: "cd" - This command changes the working directory to the user home directory
3-listfiles: "ls -l" - This command displays the current directory content in a long format
4-listmorefiles: "ls -la" - This script displays the current working directory contents including hidden files
5-listfilesdigitonly: "ls -la" - This script displays the current working directory contents in long format with user and group IDs displayed numerically
6-firstdirectory: "mkdir /tmp/my_first_directory" - This script creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile: "mv /tmp/betty /tmp/my_first_directory" - this script moves the file betty from /tmp/ to /tmp/my_first_directory.
8-firstdelete: "rm /tmp/my_first_directory/betty" - This script deletes the file betty.
9-firstdirdeletion: "rm -r /tmp/my_first_directory" - This script deletes the directory my_first_directory that is in the /tmp directory.
10-back: "cd -" - This script changes the working directory to the previous one.
11-lists: "ls -la . .. /boot" - This command writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type: "file /tmp/iamafile" - This writes a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we run the script.
13-symbolic_link: "ln -s /bin/ls __ls__" - This script is used to create a symbolic link to /bin/ls, named __ls__.
14-copy_html: "cp -u *.html" - This command is used to create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
100-lets_move: "mv [[:upper:]]* /tmp/u" - This creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs: "rm *~" - This command creates a script that deletes all files in the current working directory that end with the character ~.
102-tree: "mkdir -p welcome/to/school/my_first_directory" - This command creates a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
103-commas: "ls -xamp" - This command lists all the files and directories of the current directory, separated by commas (,).
