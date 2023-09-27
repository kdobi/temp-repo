# Shell Commands 강의노트

### pwd
- shows the current path in a hierarchical directory

### cd (change directory)
- arguments: 
[directory name]  
/root  
.currentdirectory  
..upper-leveldirectory  
~home of currentuser 
 /[directoryname]:absolute path  
./[directoryname]:relative path  
../[directoryname]:relative path


### ls (list files and directories)

- l showdetailedinformation(longformat) 
- lh sameasabove,butsizeinunits

- ls = list the files in the working directory
- ls/bin = list the in the /bin directory (or any other directory we care to specify
- ls -l = list the files in the working directory in long format
- ls -l /etc /bin = list the files in the / bin directory and the /etc directory in long format
- ls -la .. = list all files (even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format

* *clear - erase all content

### cp(copy files and directories)

* cp file1 file2 = Copies the contents of file1 into file2. If file2 does not exist, it is created; otherwise, file2 is silently overwritten with the contents of file1.

* cp -i file1 file2 = Like above however, since the "-I' (interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.

* cp file1 dir1 = Copy the contents of file1 (into a file named file1) inside of directory dir1.

* cp -R dir1 dir2 1= Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory named dir1 within directory dir2


### mv(move files and directories or renamethem)

* mv file1 file2
If file2 does not exist, then file1 is renamed file2. If file2 exists, its contents are silently replaced with the contents of file1.

* my -1 file1 file2
Like above however, since the "-¡" (interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.

* mv file1 file2 dir1 
The files file1 and file2 are moved to directory dir1. If dir1 does not exist, aw will exit with an error.

* my dir1 dir2
If dir2 does not exist, then dir1 is renamed dir2. If dir2 exists, the directory dir1 is moved within directory dir2.

### rm(delete files and directories permantely and irreversevely!!!)

* rm filel file2
Delete file1 and file2.

* am -i file2 file2
 Like above however, since the "-i" (interactive) option is specified, the user is prompted before each file is deleted.
rm -r dir1 dir2
Directories dir1 and dir2 are deleted along with all of their contents.
