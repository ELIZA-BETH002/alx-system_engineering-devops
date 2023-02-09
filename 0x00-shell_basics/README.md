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
