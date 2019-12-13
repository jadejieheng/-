## (In Git Bash)
# Directories

The *`ls`* command lists all the files and folders in the current directory `(ot functional in cmd)`. A directory is another name for a folder (such as the Documents folder). Since you're in the home directory right now, you should see the contents of your home director

# Changing directories

To move into another directory, use the *`cd`* command. Let's try moving into your Desktop directory. First, make sure you're in your home directory (check for the ~ on your command line) and use ls to see if the Desktop directory is present. Try typing the following command into your terminal, which should move you into that directory:

There are a few ways to return to the home directory:

  - `cd .. (two dots).` The .. means "the parent directory". In this case, the parent directory of cs61a is your home directory, so you can use cd .. to go up one directory.
  
  - `cd ~ (the tilde).` Remember that ~ means home directory, so this command will always change to your home directory.
  
  - `cd (cd on its own).` Typing just cd is a shortcut for typing cd ~.

# Making new directories

The next command is called mkdir, which makes new directories. Let's make a directory called cs61a(folder) on your Desktop to store all of the assignments for this class:

    mkdir cs61a
    
# Extracting/Moving

    unzip lab00.zip
    mv ~/Downloads/lab00 ~/Desktop/cs61a/lab

The mv command will move the ~/Downloads/lab00 folder into the ~/Desktop/cs61a/lab folder.

# Summary

- `ls`: lists all files in the current directory

- `cd <path to directory>`: change into the specified directory

- `mkdir <directory name>`: make a new directory with the given name

- `mv <source path> <destination path>`: move the file at the given source to the given destination
