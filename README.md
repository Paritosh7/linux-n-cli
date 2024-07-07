- Linux is a distribution that is based on UNIX philosophy. (same as macOS) Further, Ubuntu is a distribution (also known as distros) derived from Debian. Remember that there can be multiple distros and each distro has its know capability and Ubuntu is one of them.

- Kernel is the core part of any distribution and any new distro is made on top of the old distribution kernel with further capabilities that it want to concentrate on.

- Bash is a tool i.e. an interactive shell which lets you interact with the OS's kernel.

- pwd (present working directory)
- pwd --help (--help will tell what a particular will do)
- cd / (/ is the root directory and here you are changing the directory to the root directory)
- cd ../.. (this will go one directory up and then another directory, used in relative paths)
- Using just . means "this" directory, so cd . means change directory to this directory, also an example of relative path.

## Arguments / Parameters

- cd .. (The .. here can be considered an argument/parameter. This is the data we are passing the program cd to execute). For example if you write the command echo hi, (hi as argument) then you are passing echo, a program "hi" as an argument for it to run,.

## Flags

- ls -l -a (This will list all items in the pwd including hidden files, providing file information as well). -l and -a are both flags.

- There are long forms of these flags too which starts --

## Common tricks and tips

- ctrl + r (This is reverse lookup command where you can search for a command you used previously by typing any part of the command you remember)

- tail ~/.bash_history will provide the last few entries in the bash_history file. So, if someone gets hold of you computer, they will be able to access the .bash_history file and can access the passwords. However, you can edit the bash_history

- Remember to not copy and paste commands directly from the website if you don't understand them. Sometimes attackers highlight commands that they want, however, behind the scenes the command is different and it also have a return character which will execute your command.
