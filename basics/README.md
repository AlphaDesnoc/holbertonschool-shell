# [Shell, basics](https://intranet.hbtn.io/projects/2019)

## 0. Where am I?

Write a script that prints the absolute path name of the current working directory.

[View Task](./0-current_working_directory)

## 1. What’s in there?

Display the contents list of your current directory.

[View Task](./1-listit)

## 2. There is no place like home

Write a script that changes the working directory to the user’s home directory.

> - You are not allowed to use any shell variables

[View Task](./2-bring_me_home)

## 3. The long format

Display current directory contents in a long format

[View Task](./3-listfiles)

## 4. Hidden files

Display current directory contents, including hidden files (starting with `.`). Use the long format.

[View Task](./4-listmorefiles)

## 5. I love numbers

Display current directory contents.

> - Long format
> - with user and group IDs displayed numerically
> - And hidden files (starting with .)

[View Task](./5-listfilesdigitonly)

## 6. Welcome

Create a script that creates a directory named `my_first_directory` in the `/tmp/` directory.

[View Task](./6-firstdirectory)

## 7. Betty in my first directory

Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

[View Task](./7-movethatfile)

## 8. Bye bye Betty

Delete the file `betty`.

The file `betty` is in `/tmp/my_first_directory`

[View Task](./8-firstdelete)

## 9. Bye bye My first directory

Delete the directory `my_first_directory` that is in the `/tmp` directory.

[View Task](./9-firstdirdeletion)

## 10. Back to the future

Write a script that changes the working directory to the previous one.

[View Task](./10-back)

## 11. Lists

Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

Be careful with the `/`

[View Task](./11-lists)

## 12. File type

Write a script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we will run your script.

[View Task](./12-file_type)

## 13. We are symbols, and inhabit symbols

Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.

[View Task](./13-symbolic_link)

## 14. Copy HTML files

Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

You can consider that all HTML files have the extension `.html`

[View Task](./14-copy_html)

## 15. Let’s move

Create a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.

You can assume that the directory `/tmp/u` will exist when we will run your script

[View Task](./15-lets_move)

## 16. Clean Emacs

Create a script that deletes all files in the current working directory that end with the character ~.

[View Task](./16-clean_emacs)

## 17. Tree

Create a script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory.

You are only allowed to use two spaces (and lines) in your script, not more.

[View Task](./17-tree)
