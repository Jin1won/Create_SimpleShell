# Create_SimpleShell
Operating Systems Design Implementation Assignment #1<br>
17102067 Jinwon Jeong

## 1. Project Description
The objective of this project is that making simple shell by using Java. <br>
In the simple shell program, commands ‘pwd’, ‘ls’, ‘cat’, ‘ps’, ‘cd’, and ‘history’ should be executed successfully without any error or exception. <br>

## 2. Execution of SimpleShell.java file
The executing environment of the java file is Ubuntu which is installed in Oracle Virtual Box.<br>
After executing Ubuntu, you must open a terminal by using alt + ctrl + t. <br>
In terminal, you must make class file and after that, you can execute the java file by inputting below commands.<br>
### Compile SimpleShell.java file<br>
```
$ javac SimpleShell.java
```
After that, you can see new SimpleShell.class file in the same directory.<br>
### Run SimpleShell.class file
```
$ java SimpleShell
```
After that, the jsh> is printed on your terminal.

## 3. Commands description
### 1. cd
```cd```<br>
   The current directory is changed to /home/user/ directory<br>
   Absolute path is working
```cd /home```<br>
    The current directory change to /home directory
```cd user```
    The current directory change to sub directory folder named user
    Relative path is working
	cd <any existing directory> or cd ./<any existing directory>
    The current directory change to <any existing directory> directory which user input
	cd fakeDirectory
    Print error message “There is no such directory.”
2.	history
	‘history’
    Print all history of previous commands
	‘history <number>’
    Print most recent <number> commands 
	‘history !!’
    Run the previous command
	‘history !<number>’
    Run the command which matched with <number> index in the history
3.	Other Shell command
	‘ls’
	Print all directories and files in the current directory
	‘pwd’
Print the current directory
	‘cat <filename.filetype>’
Run the <filename.filetype> file and print the contents of the <filename.filetype> file
