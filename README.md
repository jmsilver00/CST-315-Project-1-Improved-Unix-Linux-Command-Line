To compile and run code:
For command line: 
gcc newcommandline.c
./a.out
For batch
emacs (or other text editor) batch1.sh
enter any commands into the created sh file
back in the terminal: chmod +x batch1.sh
./batch1.sh
To exit commandline.c ctrl + c

First the command line is intilaized with createCML() and the user is prompted to input a command or enter a specific character “e” to exit, after a command is obtained it is broken into tokens separated by the delimetier space using the c function strtok(). Then each token is gone through to form a command argument. After this the command is run where a child is then made with the fork() command, in the terminal if a commands correct binary is found then the command will be executed, if not then the an error message will appear. 
