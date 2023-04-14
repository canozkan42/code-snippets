### `cat filename`

**cat** command is a shell command that is short for "concatenate". It is used to display the contents of one or more files on the terminal. You can also combine multiple files into a single file using "cat" and redirecting the output to a new file. For example, to combine the contents of two files into a new file named "combined.txt", you can run the following command:
```bash
cat file1.txt file2.txt > combined.txt
```

### `vim filename`

**vim** command is a shell command that allows you to open and edit a file using the Vim text editor. Here, "filename" is the name of the file that you want to edit. If the file does not exist, Vim will create it when you save your changes. If you do not specify a filename, Vim will start in "unnamed" mode, where you can create and edit a new file from scratch. Use "i" to enter insert mode to modify the text, and after modification ":x" command

### `la`

`la` is an alias for ls with the -la option, it will show all files and directories (including hidden) in a long listing format that includes additional information such as file size, permissions, and modification date.

## Search item in shell directory
```shell
ls | grep searched_item
```
The terminal command "ls | grep testkey" consists of two separate commands connected using the "pipe" operator "|".

The first command is "ls", which stands for "list directory contents". When this command is executed, it lists all the files and directories in the current working directory.

The second command is "grep", which stands for "global regular expression print". It searches for a specific pattern or regular expression in the input and prints out any lines that contain that pattern. In this case, the pattern it is searching for is "testkey".

When the two commands are connected with the pipe operator "|", it means that the output of the first command ("ls") is fed as input into the second command ("grep"). Therefore, the overall effect of the command "ls | grep testkey" is to list all the files and directories in the current working directory, and then search through that list for any entries that contain the string "searched_item". The resulting output will be a list of any files or directories that match that pattern.
