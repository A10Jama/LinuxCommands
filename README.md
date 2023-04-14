## Linux Commands

Below are some commonly used Linux commands:

### Navigation

cd [directory] : change the current directory to the specified directory.

pwd : print the current working directory.

ls  :   list the contents of the current directory.

ls [directory] : list the contents of the specified directory.

ls -l : list the contents of the current directory in long format.

### File Management

touch [filename]: create a new empty file with the specified name.

cp [source] [destination]: copy a file from the source path to the destination path.

mv [source] [destination]: move a file from the source path to the destination path.

rm [file]: remove the specified file.

mkdir [directory]: create a new directory with the specified name.

### Text Editing

nano [filename]   : open the specified file in the nano text editor for editing.

cat [filename]  : display the contents of the specified file in the terminal.

### System Information

whoami   : display the username of the current user.

top    : display information about the system's processes, including their resource usage.

history : display a list of the commands that have been executed in the current shell session.

### Permissions

chmod [permission] [file]  : change the permissions of the specified file to the specified permission value.

chmod [permission] [directory]/[file]  : change the permissions of the specified file within the specified directory to the specified permission value.

### Miscellaneous

exit  : exit or close the current shell or terminal session.

clear  :  clear the terminal screen.

## Make an environment

`printenv`: Prints all environment variables.
`env`: Displays all current environment variables and their values.
`printenv variable_name`: Prints the value of the specified environment variable.
`echo $"variable_name`: Prints the value of the specified environment variable.
`export LAST_NAME=Jama`: Creates a new environment variable called LAST_NAME with a value of Jama.
`ls -a`: Lists all files in the current directory, including hidden files.
`sudo nano .bashrc`: Opens the .bashrc file for editing with elevated privileges using the nano editor.
`source .bashrc`: refreshes the .bashrc file, which applies any changes made to it.
