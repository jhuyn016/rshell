# rshell

#Introduction
This project creates a command shell in C++ called rshell that can print a command line($) and read in the commands on the line then 
execute them. This rshell allows users the ability to combine/chain commands with ; && || onto one line for execution. 

#Instructions
Compile the code by running the following command at the base of the rshell repository,
````
make
````
Run the code by calling the executable
````
bin/rshell
````

#Bugs
- One known bug is that if the user enters something random that is not a command such as, 'hello' and then tries to exit, exit has to
be called twice to successfully exit.
- Pertaining to the .sh test cases, there is an extra prompt line at the end of each test case run.
- There is currently undefined behavior with nested parenthesis.
- comments '#' are treated on a per command basis
