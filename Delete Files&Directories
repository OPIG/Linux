In this tutorial we can check how to safely delete files and directories using Linux Command line

To remove a file or directory in Linux, we can use the rm command or unlink command. The rm command removes each specified file. By default, it does not remove directories. Also, it does not work on directories that contain files. The rm command (short for remove) is a Unix / Linux command which is used to delete files from a file system. Usually, on most filesystems, deleting a file requires write permission on the parent directory (and execute permission, in order to enter the directory in the first place). Also, be careful with the rm command because it does not ask you for confirmation when deleting files. Be sure you really want to delete your files before you use rm, because once the files are gone, they’re not coming back. The multi-user nature of Linux does not allow for file recovery as in DOS. As soon as you let go of the space occupied by a file, the operating system is likely to use it for something else. The syntax for deleting the specified files is given below.

$ rm {file-name}
$ rm [options] {file-name}
$ rm -f {file-name}

Where -f used to remove the file forcefully.

If you want to delete a file named as test and you have run the command $ rm test, then it will immediately delete the file named test in the current directory without prompting. If you want to be prompted before the deletion, use the ‘-I’ flag. The only one safety feature in rm is it won’t delete a directory unless you use the -r flag. The other rm flag -f, which translates roughly to “Don’t ask me any questions–just delete the files.” While rm normally asks for confirmation before deleting a write-protected file, the -f (force) flag overrides this prompt.

 

1) To remove a file named test.txt, use the following command.

$ rm test.txt

Here rm test would delete the file named “test” in the current directory. You could also specify a full path to the file: rm /path/to/test would delete the file at /path/to/test on your file system.

 

2) You can also use the rm command to delete multiple files at one time like the following command.

$ rm file1 file2 file3

If you want to be careful when deleting files, you can use the -i option with the rm command. The ‘-I’ stands for “inquire”, so when you use this option the rm command prompts you with a yes/no prompt before actually deleting your files. For example:

$ rm -i files file2 file3

 

3) To remove all files & subdirectories from a directory, use the below given command.

$ rm -rf directoryname

 

4) To delete all TXT files in the current directory, use the following command.

$ rm *.txt

 

5) To delete all files in the current directory that begin with the string “index”, you can use the command given below.

$ rm index*

 

This command deletes files named index.php, index.html and in general, any filename that begins with the character string “index”.

 

How To remove a full directory in Linux

If you create a directory named mydir some months ago, and now do not need it, the mkdir command may be able to help you.

 

1) To remove a directory named as mydir that contains other files or directories, use the following command.

$ rm -r mydir

You can replace “mydir” with the name of the directory you want to delete. The above command would also present a prompt for approval to delete each of the files. If you don’t want to receive a prompt for each file, use the following command instead.

$ rm -rf mydir

 

2) To remove empty directory use rmdir instead of rm command:

$ rmdir mydir
