# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 ![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/6ce32d60-eb17-475e-b8e3-f9304372f42e)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/5800f50a-fe2c-44f2-b67e-3611fcb70716)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/31e75265-967e-4263-9320-be341157b6a8)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/fb8e90e8-ba12-42a2-b169-afe506aed307)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/01a43b6c-667c-419c-8e59-34bb24eea270)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/5769484e-73b2-45d6-bbd9-c3bf7c610486)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/e30cc94c-5125-453b-b1f2-e152631c154f)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/517ab14c-bfcd-4911-bb66-83941a8aa090)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/859aff33-3736-4467-b5ed-f188f8a5a599)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/4e3776c5-3a20-40bc-977f-e3e10b9a69f8)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/4bec532a-144d-4159-b7a4-3c6f3e4f2000)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/d7248d0a-782e-440f-be60-96a9cb7e4da9)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/84807864-0502-419f-a940-4f8591f5fa3b)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/cfdbb0d3-7428-4f66-af5e-d3535a55720f)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/3cc22a0e-007a-4fdc-ab7a-49c87f90d150)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/005285e6-31f5-4721-8cea-efc4e9d83bbc)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/c7111f01-7880-4321-83e2-87177f1a1068)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/a2bd23c5-f880-4886-8b59-4af0990cccdd)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/6fe522e7-853c-4902-9baa-2b801b372dec)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/91639ce2-4875-4b42-9282-4e8ade557a69)



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/3ebe6222-0c37-4788-a503-864c71ee1b2a)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/5fa4615b-673c-4b55-96e3-6745ffae7a28)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/010e273a-c61e-43db-b38e-1e11700354ab)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/6c9e86f7-e4f0-447c-a8b9-14e4989f5152)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/e842d2cf-de32-4ae7-8015-29ed6647f9f1)


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/122033587/076ce406-da42-4ce0-bb9c-9b493228bfd4)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
