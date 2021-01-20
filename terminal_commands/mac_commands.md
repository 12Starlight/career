# **Mac Commands**

<kbd>cd [directory_name]</kbd> ~ Directory change

<kbd>ls</kbd> ~ Check the list inside directory

<kbd>pwd</kbd> ~ Present working directory

<kbd>mkdir</kbd> ~ Make directory

<kbd>touch</kbd> ~ Make file

<kbd>open</kbd> ~ Open file

<kbd>ls -la</kbd> ~ Shows all files open including `.` files

<kbd>ls -lah</kbd> ~ Shows all files open including `.` files and memory allocated

<kbd>mv</kbd> ~ Move a file or change file name

<kbd>cd ..</kbd> ~ Go up a directory

<kbd>cd</kbd> ~ Go to home directory

<kbd>cmd + spacebar</kbd> ~ Opens finder (inside finder `/` takes you to root directory)

<kbd>cp</kbd> ~ Copy a file

<kbd>rm [file_name]</kbd> ~ Delete a file, to confirm <kbd>rm -l</kbd>

<kdb>rm -R [directory_name]</kdb> ~ Deletes all files and subfolders, to confirm <kbd>rm -iR</kbd>

<kbd>rm -rf [directory_name]</kbd> ~ Deletes a directory

<kbd>rm -rf</kbd> ~ Deletes entire computer (**DO NOT DO**)

<kbd>cat</kbd> ~ Prints contents of a file in terminal

<kbd>ditto [new][old]</kbd> ~ Copies new directory, moves to old directory

<kbd>curl -O [URL]</kbd> ~ Download a URL to a directory

<kbd>;</kbd> ~ Allows you to type multiple commands on a line

<kbd>ctr + c</kbd> ~ Interupt a command that is already running

<kbd>cmd + shift + g</kbd> ~ Access root directory (/)

&nbsp;

### **Changing default for screenshots directory and file type**

<kbd>defaults write com.apple.screencapture location [directory_path]</kbd>, then
hit return, then <kbd>killall SystemUIServer</kbd> ~ Changes location of screenshots

<kbd>defaults write com.apple.screencapture type JPG</kbd>, then hit return, then
<kbd>killall SystemUIServer</kbd> ~ Changes default type (PNG) for screenshots

