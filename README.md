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

## Shortcuts

- CTRL + A – takes you to the beginning of the line
- CTRL + E – takes you to the end of the line
- CTRL + K – "yank" everything after the cursor
- CTRL + U – "yank" everything before the cursor
- CTRL + Y - "paste" (paste in quotes because it doesn't actually go into your system clipboard) everything you yanked
- CTRL + L - clear the screen
- CTRL + R – reverse search through history

## Signals

- A signal is notification that is sent to program and it's the program's responsibility to stop or not.

- CTRL + C – SIGINT
- CTRL + D – SIGQUIT

## Editors

- nano, Straightforward
- vim, complicated and not really required.

## File interactions

- less, used to read a file and usually considered for long files.
- cat, similar to less, however, they are used for small files.
- head textfile.txt, read the first lines of a file and outputs it
- tail textfile.txt, reads the last lines of a file and outputs it
- rm new-file.txt, removes new-file.txt
- rm -r my-new-folder, removes my-new-folder and add -f to force everything through without confirmation (rm -r my-new-folder)

## cp

- cp source-file.txt destination-file.txt, copies source-file.txt into destination-file.txt
- cp source-file.txt my-new-folder/, copies source-files.txt to my-new-folder (trailing / isn't needed)
- cp -R source-directory destination-directory, copies everything from the source to the destination recurs

## mv

- mv file.txt new-name.txt, moving file.txt to new-name.txt which is in essence renaming the file.
- mv folder-name new-folder-name, moves 1 folder to another, unlike cp where you have to recursively copy a folder into another.
