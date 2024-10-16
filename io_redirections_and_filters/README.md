# [Shell, I/O Redirections and filters](https://intranet.hbtn.io/projects/2021)

## 0. Hello World

Write a script that prints “Hello, World”, followed by a new line to the standard output.

[View Task](./0-hello_world)

## 1. Confused smiley

Write a script that displays a confused smiley `"(Ôo)'`.

[View Task](./1-confused_smiley)

## 2. Let's display a file

Display the content of the `/etc/passwd` file.

[View Task](./2-hellofile)

## 3. What about 2?

Display the content of `/etc/passwd` and `/etc/hosts`

[View Task](./3-twofiles)

## 4. Last lines of a file

Display the last 10 lines of `/etc/passwd`

[View Task](./4-lastlines)

## 5. I'd prefer the first ones actually

Display the first 10 lines of `/etc/passwd`

[View Task](./5-firstlines)

## 6. Line #2

Write a script that displays the third line of the file `iacta`.

The file `iacta` will be in the working directory

> - You’re not allowed to use `sed`


[View Task](./6-third_line)

## 7. It is a good file that cuts iron without making a noise

Write a shell script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.

[View Task](./7-file)

## 8. Save current state of directory

Write a script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.

[View Task](./8-cwd_state)

## 9. Duplicate last line

Write a script that duplicates the last line of the file `iacta`

> - The file `iacta` will be in the working directory

[View Task](./9-duplicate_last_lane)

## 10. No more javascript

Write a script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.

[View Task](./10-no_more_js)

## 11. Don't just count your directories, make your directories count

Write a script that counts the number of directories and sub-directories in the current directory.

> - The current and parent directories should not be taken into account
> - Hidden directories should be counted

[View Task](./11-directories)

## 12. What’s new

Create a script that displays the 10 newest files in the current directory.

Requirements:

> - One file per line
> - Sorted from the newest to the oldest

[View Task](./12-newest_files)

## 13. Being unique is better than being perfect

Create a script that takes a list of words as input and prints only words that appear exactly once.

> - Input format: One line, one word
> - Output format: One line, one word
> - Words should be sorted

[View Task](./13-unique)

## 14. It must be in that file

Display lines containing the pattern “root” from the file `/etc/passwd`

[View Task](./14-findthatword)

## 15. Count that word

Display the number of lines that contain the pattern “bin” in the file `/etc/passwd`

[View Task](./15-counthatword)

## 16. What's next?

Display lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`.

[View Task](./16-whatsnext)

## 17. I hate bins

Display all the lines in the file `/etc/passwd` that do not contain the pattern “bin”.

[View Task](./17-hidethisword)

## 18. Letters only please

Display all lines of the file `/etc/ssh/sshd_config` starting with a letter.

> - include capital letters as well

[View Task](./18-letteronly)

## 19. A to Z

Replace all characters `A` and `c` from input to `Z` and `e` respectively.

[View Task](./19-AZ)

## 20. Without C, you would live in hiago

Create a script that removes all letters `c` and `C` from input.

[View Task](./20-hiago)

## 21. esreveR

Write a script that reverse its input.

[View Task](./21-reverse)

## 22. DJ Cut Killer

Write a script that displays all users and their home directories, sorted by users.

> - Based on the the `/etc/passwd` file

[View Task](./22-users_and_homes)

## 23. Empty casks make the most noise

Write a command that finds all empty files and directories in the current directory and all sub-directories.

> - Only the names of the files and directories should be displayed (not the entire path)
> - Hidden files should be listed
> - One file name per line
> - The listing should end with a new line
> - You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`

[View Task](./23-empty_casks)

## 24. A gif is worth ten thousand words

Write a script that lists all the files with a `.gif` extension in the current directory and all its sub-directories.

> - Hidden files should be listed
> - Only regular files (not directories) should be listed
> - The names of the files should be displayed without their extensions
> - The files should be sorted by byte values, but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after file `jay`)
> - One file name per line
> - The listing should end with a new line
> - You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`

[View Task](./24-gifs)

## 25. Acrostic

An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. [Read more](https://en.wikipedia.org/wiki/Acrostic).

Create a script that decodes acrostics that use the first letter of each line.

> - The ‘decoded’ message has to end with a new line
> - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`

[View Task](./25-acrostic)

## 26. The biggest fan

Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

> - Order by number of requests, most active host or IP at the top
> - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`

[View Task](./26-the_biggest_fan)
