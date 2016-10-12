# fileCopying
This program prompts the user for the filename of the file to copy from. The program verifies that a valid filename has been entered, otherwise it will keep prompting until a valid filename is entered. Currently, this source code / executable file and the file you want as the source file must be in the same folder/directory or the program will always tell you that the file could not be found. Next, the program asks for the filename of the destination file. If the file doesnt exist, it will be created and the data from the source file will be copied to the destination file. If the file exists, then the user has the option to write data to the end of the previous data in the file (append), overwrite the data in the file, or cancel the copy action and end the program. To demonstrate this code using an existing destination file, this source code / executable file and the destination file must be in the same folder/directory otherwise the program will proceed to create the file instead of recognizing an existing file.

How to compile:

Linux/UNIX & Mac OS X: Open terminal, cd to the directory where the source code file is stored. Run "gcc -o fileCopying fileCopying.c" (without quotes) on the terminal window. To run the program, simply do "./fileCopying" (without quotes).

Windows 7/8.1/10: Please use the IDE software "Code Blocks" to compile and run this program.
