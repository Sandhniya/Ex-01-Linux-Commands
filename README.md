# Ex-01-Linux-Commands
SANDHIYA SREE B
212223220093

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

<img width="681" height="114" alt="image" src="https://github.com/user-attachments/assets/e7922e37-3e14-4d93-a45a-6903688d0b0e" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="427" height="100" alt="image" src="https://github.com/user-attachments/assets/6606d5b4-5612-4145-8cb6-5f07735bed34" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="369" height="78" alt="image" src="https://github.com/user-attachments/assets/4cabb08d-217f-4919-b6d0-8c9e49ef6e16" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
<img width="416" height="67" alt="image" src="https://github.com/user-attachments/assets/a9a8d4ba-519d-4a3d-ae1c-4aae507f7b1d" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
<img width="405" height="85" alt="image" src="https://github.com/user-attachments/assets/21eaed01-6725-4505-8657-3ba1363a8660" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="1189" height="945" alt="image" src="https://github.com/user-attachments/assets/81d1ac8a-3c93-4312-9c80-3ecaabe46560" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="517" height="60" alt="image" src="https://github.com/user-attachments/assets/ba845054-a86d-4092-be2a-638b4177a85a" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="535" height="550" alt="image" src="https://github.com/user-attachments/assets/a0b086ef-763c-4861-943d-0872c5f9562e" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="592" height="453" alt="image" src="https://github.com/user-attachments/assets/91dde2f1-b1fe-489e-8c69-ad9a82a2af38" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="547" height="430" alt="image" src="https://github.com/user-attachments/assets/99bac008-20f1-4af5-963d-ad400b8c1e58" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="591" height="496" alt="image" src="https://github.com/user-attachments/assets/46b30f1d-caf2-4d3a-9cd6-1e016471afa9" /> 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="754" height="84" alt="image" src="https://github.com/user-attachments/assets/f1e63682-d54f-474b-a322-707b90ed4492" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="415" height="150" alt="image" src="https://github.com/user-attachments/assets/8780a0e3-b52c-4b8d-95f4-7ec6a1e37889" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="402" height="119" alt="image" src="https://github.com/user-attachments/assets/97b763f5-19a1-4520-ba8a-1b64e22f980e" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="433" height="50" alt="image" src="https://github.com/user-attachments/assets/1265c3e7-7ec0-43c6-b566-cc0c52bb3058" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
<img width="618" height="165" alt="image" src="https://github.com/user-attachments/assets/0dbb03ef-e9e5-4294-9e61-9110e2029639" />
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="549" height="81" alt="image" src="https://github.com/user-attachments/assets/214f50a0-c033-4666-96fd-53d649bbd6cc" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="726" height="862" alt="image" src="https://github.com/user-attachments/assets/183490d2-a6cf-4e48-b525-2e0b11491a64" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="729" height="341" alt="image" src="https://github.com/user-attachments/assets/f8b11c0c-fab4-4003-99a0-861f7c583535" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 <img width="539" height="100" alt="image" src="https://github.com/user-attachments/assets/81ddcc0b-6b93-4ea1-9eb0-a6afe077aa67" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
<img width="539" height="74" alt="image" src="https://github.com/user-attachments/assets/f897fc8d-c5b5-4a8c-a898-bd3689a8c953" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="459" height="118" alt="image" src="https://github.com/user-attachments/assets/90f9c13f-2b03-4f8c-95aa-8cb91b4c2d05" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 <img width="374" height="284" alt="image" src="https://github.com/user-attachments/assets/d6c13979-8ea4-4d8d-a9ea-997d396c6091" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="452" height="178" alt="image" src="https://github.com/user-attachments/assets/d66e7911-35a9-480d-8168-a3dbf1c9064c" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="392" height="57" alt="image" src="https://github.com/user-attachments/assets/bc028dd0-ec7b-497c-b562-00690f2bcbeb" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="672" height="472" alt="image" src="https://github.com/user-attachments/assets/d35e2bc8-a677-49ce-9312-a4d1468b7393" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


<img width="356" height="91" alt="image" src="https://github.com/user-attachments/assets/29849e9b-f716-43ff-835b-b617399a3085" />



















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
