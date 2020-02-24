# Shell

**Time at which I am logged in**

`who am i`

**Present working directory**

`pwd`

**Calendar**

`cal *m/mmm yyyy*`

**Date**

`date '+DATE:%m-%y%nTIME:%H:%M:%S'`

Output will be as follows :
```
DATE:02-20

TIME:10:56:55
```

**Touch**

Used to create empty files

`touch test1 test2 test3`

**mkdir**

Create a directory

`mkdir path\foldername`

~ : Is the location of the home directory

**cd**

Change the pwd folder

`cd path`

**cat**

Create a file and there needs to be a redirection operator. 

`cat > test`

Creates a text file with a prompt to type the contents. `Ctrl-D` to kill the get back to the terminal.

`cat < test`

Prints the content of the test file to std output.

`cat random test > sample`

Creates a merged file called sample with contents of random and test files. Sequence is same as specified in the shell.

**mv**

Rename 

Renames the file / folder to the file / folder specified.

`mv sample test`


**rm**

Removes a file / directory

`rm filename`

`rm -r foldername`

rmdir is a proxy for `rm -r`


**cp**

Copy files from one location to another

`cp ~/old ~/new`


**ln**
Creates a hard or soft link to file / folder.

`ln old new`

Changing old will make the same changes in old. Creates a copy of the file and old file can be deleted.

`ln -s old new_soft`

Creates a soft link that will be become redundant if old file is deleted. It creates a pointer to the old file.

**ls**

List directory structure along with the permissions

`ls -l`

List directory structure 

`ls -a`

**chmod**

Change permissions for file or folders

`chmod 777 test`

