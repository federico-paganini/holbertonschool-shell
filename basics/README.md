Sripts functionalities.



0-current_working_directory > Prints the absolute path name of the current working directory.

1-listit > Display the contents list of your current directory.

2-bring_me_home > Changes the working directory to the user's home directory. (Use with the source command: $ source ./file-name).

3-listfiles > Display current directory contents in a long format.

4-listmorefiles > Display current directory contents (including hidden files) in long format.

5-listfilesdigitonly > Display current directory contents in: Long format, with users and groups IDs displayed numerically and
		       hidden files.

6-firstdirectory > Creates a directory named my_first_directory in the /tmp/ directory.

7-movethatfile > Move the file betty from /tmp/ to /tmp/my_first_directory.

8-firstdelete > Deletes the file betty from /tmp/my_first_directory directory.

9-firstdirdeletion > Delete the directory my_first_directory that is in the /tmp directory.

10-back > Changes the working directory to the previous one.

11-lists >  Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current
	    directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type > Prints the type of the file named iamafile located in /tmp directory.

13-symbolic_link > Creates a symbolic link to /bin/ls, named __ls__ in the current directory.

14-copy_html > Copies all the HTML files from the current working directory to the parent of the working directory, but only copy
	       files that did not exist in the parent of the working directory or were newer than the versions in the parent of
	       the working directory.

15-lets_move > Moves all files beginning with an uppercase letter to the directory /tmp/u .

16-clean_emacs > Delete all files in the current working directory that end with the character ~ .

17-tree > Creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.