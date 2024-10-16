# [Shell, permissions](https://intranet.hbtn.io/projects/2020)

## 0. My name is Betty

Create a script that switches the current user to the user `betty`.

> - You should use exactly 8 characters for your command (+1 character for the new line)
> - You can assume that the user `betty` will exist when we will run your script

[View Task](./0-iam_betty)

## 1. Who am I

Write a script that prints the effective username of the current user.

[View Task](./1-who_am_i)

## 2. Groups

Write a script that prints all the groups the current user is part of.

[View Task](./2-groups)

## 3. New owner

Write a script that changes the owner of the file `hello` to the user `betty`.

[View Task](./3-new_owner)

## 4. Empty!

Write a script that creates an empty file called `hello`.

[View Task](./4-empty)

## 5. Execute

Write a script that adds execute permission to the owner of the file `hello`.

> - The file `hello` will be in the working directory

[View Task](./5-execute)

## 6. Multiple permissions

Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

> - The file `hello` will be in the working directory

[View Task](./6-multiple_permissions)

## 7. Everybody!

Write a script that adds execution permission to the owner, the group owner and the other users, to the file `hello`

> - The file `hello` will be in the working directory
> - You are not allowed to use commas for this script

[View Task](./7-everybody)

## 8. James Bond

Write a script that sets the permission to the file `hello` as follows:

> - Owner: no permission at all
> - Group: no permission at all
> - Other users: all the permissions
The file `hello` will be in the working directory You are not allowed to use commas for this script

[View Task](./8-James_Bond)

## 9. John Doe

Write a script that sets the mode of the file `hello` to this:
```sh
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```
> - The file `hello` will be in the working directory
> - You are not allowed to use commas for this script

[View Task](./9-John_Doe)

## 10. Look in the mirror

Write a script that sets the mode of the file `hello` the same as `olleh`’s mode.

> - The file `hello` will be in the working directory
> - The file `olleh` will be in the working directory

[View Task](./10-mirror_permissions)

## 11. Directories

Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

[View Task](./11-directories_permissions)

## 12. More directories

Create a script that creates a directory called `my_dir` with permissions 751 in the working directory.

[View Task](./12-directory_permissions)

## 13. Change group

Write a script that changes the group owner to `school` for the file `hello`

> - The file `hello` will be in the working directory
> - **The script must be present on the github repository and on the sandbox on the folder /tmp**

[View Task](./13-change_group)

## 14. Owner and group

Write a script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

[View Task](./14-change_owner_and_group)

## 15. Symbolic links

Write a script that changes the owner and the group owner of `_hello_` to `vincent` and `staff` respectively.

> - The file `_hello_` is in the working directory
> - The file `_hello_` is a symbolic link

[View Task](./16-symbolic_link_permissions)

## 16. If only

Write a script that changes the owner of the file `hello` to `vincent` only if it is owned by the user `guillaume`.

> - The file `hello` will be in the working directory

[View Task](./16-if_only)
