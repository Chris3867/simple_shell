Simple shell  a UNIX command line interpreter.

It is designed to run in the Ubuntu 14.04 LTS linux environment and to be compiled using the GNU compiler collection v. gcc 4.8.4 with flags-Wall, -Werror, -Wextra, and -pedantic.

USAGE
The simple_shell is designed to execute commands in a similar manner to sh, however with more limited functionality. The development of this shell is ongoing. The below features will be checked as they become available (see man page for complete information on usage):

Features
 uses the PATH
 implements builtins
 handles command line arguments
 custom strtok function
 uses exit status
 shell continues upon Crtl+C (^C)
 handles comments (#)
 handles ;
 custom getline type function
 handles && and ||
 aliases
 variable replacement

Builtins
 exit
 env
 setenv
 unsetenv
 cd
 help
 history
