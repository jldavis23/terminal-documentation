**1. What is the terminal? Why is it an important tool for a web developer?**

The terminal is an interface that allows you to interact with programs on your computer. It is text-based, so you can control your computer by just using text. It is important for web developers because it allows you to use version control (git), install packages, create files and directories, and run commands that are useful when developing.

**2. For you, what are some important built-in commands to know. What do they do, and why are they important? (At least 5)**
- cd allows you to change directories. I often use this when I'm choosing a file to initialize as a git repo or if I want to see the directory's contents.
- ls lists all the files in the current directory. It is super useful to see what you have stored in a certain directory.
- man allows you to view the manual for a certain command. For example, I could run man ls and it will bring up the manual to explain what that command does and how to use it. It's helpful for when you don't remember exactly what a command does or what its arguments are.
- mkdir is a command to create a directory. Directories are important because they organize and house your various files.
- The touch command allows you to create a new file. This is a good one to know because files are the main thing you're working with in web development.

**3. What is the root?**

The root refers to the top-level directory on a computer. It is represented by a slash (/) symbol.

**4. What is the path?**

A path is sort of a map to where a certain file or directory is located. For example, the path /users/johnsmith/desktop/index.md shows that the index.md file is inside the desktop directory, which is inside the johnsmith directory, and so forth.

There is also an environment variable called $PATH. It is a list of directories that the terminal looks in to search for executable files when a command is run.

**5. What is the present working directory?**

The present working directory is the directory (or folder) that the user is currently in. You can find out what the current working directory is by running pwd in the terminal. 

**6. What is the bin? How does it work?**

bin stands for binary. The bin folder holds binary files that are necessary to run commands and programs. The bin folder is usually on the $PATH.


**7. Write about at least two new things you have personally learned about the command line.**

I learned that tilda (~) symbol represents your home directory. And the home directory on your computer isn't (usually) the root directory. The root directory is the top-level of your file system, while the home directory (which contains your personal files, etc) is a directory inside the root.

I also learned you can use the * symbol to modify multiple files at once. If you want to remove all javascript files in a directory, you can run rm * .js to remove them all at once.
