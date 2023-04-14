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

## Creating Variables in Linux

Variable=Value - creates a simple variable named Variable that stores Value

export Variable=Value - creates an environment variable

Both variables will be deleted after instance is restarted

printenv or env - prints all the environment variables

printenv Variable - prints the value of the specific environment variable

echo $Variable - prints the value of the regular variable
If you want to store the variables next time when you open the environment you have to add them to the .bashrc script:

#### Open the script with nano using command 

`nano .bashrc`

As this is a systme script it is important you do no change any of the existed code. To be safe, scroll to the bottom of the script and add your new code there

Type `export Variable=Value`` 
to create an environment variable that will be added with this scipt when environment loads

We can use `printenv Variable` to see if it's there, however currently its not being added. We need to restart the environment or restart the script for it to be added

We can use `source .bashrc` to reuse the scirpt and after that our variable will be added
