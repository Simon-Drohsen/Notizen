<h1>Command Line</h1>

<h2>A filesystem organizes a computer’s files and directories into a tree structure:</h2>

* The first directory in the filesystem is the root directory. It is the parent of all other directories and files in the filesystem.

* Each parent directory can contain more child directories and files. In the filesystem on the right, blog/ is the parent of 2014/, 2015/, and hardware.txt.

* Each directory can contain more files and child directories. The parent-child relationship continues as long as directories and files are nested.

* The command line is a text interface for the computer’s operating system. To access the command line, we use the terminal.

* A filesystem organizes a computer’s files and directories into a tree structure. It starts with the root directory. Each parent directory can contain more child directories and files.

<h2>From the command line, you can navigate through files and folders on your computer:</h2>

* pwd outputs the name of the current working directory.

* ls lists all files and directories in the working directory.

* cd switches you into the directory you specify.

* mkdir creates a new directory in the working directory.

* touch creates a new file inside the working directory.

<h2>You can use helper commands to make navigation easier:</h2>

* clear clears the terminal

* tab autocompletes the name of a file or directory

* ↑ and ↓ allow you to cycle through previous commands

<h2>Options modify the behavior of commands:</h2>

* ls -a lists all contents of a directory, including hidden files and directories

* ls -l lists all contents in long format

* ls -t orders files and directories by the time they were last modified

<h2>Multiple options can be used together, like ls -alt</h2>

* From the command line, you can also copy, move, and remove files and directories:

* cp copies files

* mv moves and renames files

* rm removes files

* rm -r removes directories

* Redirection reroutes standard input, standard output, and standard error.

<h2>The common redirection commands are:</h2>

* (Pfeil nach rechts) redirects standard output of a command to a file, overwriting previous content.

* (Pfeil nach rechts) redirects standard output of a command to a file, appending new content to old content.

* < redirects standard input to a command.

* | redirects standard output of a command to another command.

<h2>A number of other commands are powerful when combined with redirection commands:</h2>

* sort: sorts lines of text alphabetically.

* uniq: filters duplicate, adjacent lines of text.

* grep: searches for a text pattern and outputs it.

* sed : searches for a text pattern, modifies it, and outputs it.

* The environment refers to the preferences and settings of the current user.

* The nano editor is a command line text editor used to configure the environment.

* ~/.bash_profile is where environment settings are stored. You can edit this file with nano.

* Environment variables are variables that can be used across commands and programs and hold information about the environment.

* export VARIABLE="Value" sets and exports an environment variable.

* USER is the name of the current user.

* PS1 is the command prompt.

* HOME is the home directory. It is usually not customized.

* PATH returns a colon : separated list of file paths. It is customized in advanced cases.

* env returns a list of environment variables. You can redirect the output, using grep to select the variable you want to see.
