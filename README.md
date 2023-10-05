# Shell Commands 강의노트

### I/ORedirection:StandardOutput
- I/O redirection is a powerful concept in shell scripting and command-line usage. It allows you to control the flow of data between commands and files, making your interactions with the command line more flexible and efficient. In this lecture, we will focus on redirection of the standard output.
- **`>`** - Redirects stdout to a file and overwrites the file if it already exists.
  - Example: `ls > file.txt`


- **`>>`** - Redirects stdout to a file and appends to the file if it already exists.
  - Example: `echo "New content" >> file.txt`
   
    
### Backslash
- Backslah can be used to ignore line change incommand (“enter”),  to enter a long command in multiple lines

###### Example: `-rw-rw-r--`
- File Type: `-` (Regular File)
- Owner's Permissions: `rw-` (Read and Write)
- Group's Permissions: `rw-` (Read and Write)
- Others' Permissions: `r--` (Read)



### Text Editors

##### Vi
- **Description**: Vi is a classic Unix text editor known for its efficiency and availability on almost all Unix-like systems.

##### Vim
- **Description**: Vim (Vi IMproved) is an enhanced version of Vi, offering additional features and extensibility.

##### Emacs
- **Description**: Emacs is a highly customizable, extensible text editor with a powerful ecosystem of extensions.

##### Nano
- **Description**: Nano is a simple and beginner-friendly text editor with a straightforward interface.

##### Gedit
- **Description**: Gedit is the default text editor for the GNOME desktop environment on Linux.

##### KWrite
- **Description**: KWrite is the text editor for the KDE desktop environment, providing a simple and efficient editing experience.

## Shell Script

### ^G (Ctrl + G)
- **Function**: Ring the terminal bell.

### ^O (Ctrl + O)
- **Function**: Write out (save) the current file or script.


### ^W (Ctrl + W)
- **Function**: Delete the word before the cursor.

### ^K (Ctrl + K)
- **Function**: Delete text from the cursor position to the end of the line.

### ^J (Ctrl + J)
- **Function**: Enter or execute a command.
- 
### ^C (Ctrl + C)
- **Function**: Interrupt or stop the currently running command or script.

### ^X (Ctrl + X)
- **Function**: Cut or delete the selected text.
- 
### ^R (Ctrl + R)
- **Function**: Search for a previously used command.

### ^\ (Ctrl + \)
- **Function**: Send the quit signal.

### ^U (Ctrl + U)
- **Function**: Delete text from the cursor position to the 

### ^T (Ctrl + T)
- **Function**: Transpose (swap) characters.
