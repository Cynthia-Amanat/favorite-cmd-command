# favorite-cmd-command

# ls

The ls (list) command is used to list directories or files. excluding any hidden files. Some of the most useful options are:

    ls -a: List all the files in the current directory including hidden files too
    ls -l: Long listing of all the files and their size in the current directory

# rm

rm (remove) command is used to delete files, directories or even symbolic links from your file system. Some of the most useful options are:

    rm -i: Remove all the files in the directory but let user confirm before deleting it
    rm -r: Remove non-empty directories including all the files within them
    rm -f: Remove files or directories without prompting even if they are write-protected — f stands for force.

# touch

The touch command allows you to create new empty files .

Some of the most useful options are:

    touch -c file1.txt: If file file1.txt already exists then this command will update the file’s timestamps otherwise it will do nothing.
    touch -a file1.txt: Update only the access timestamp of the file
    touch -m file1.txt: Update only the modify time of the file
