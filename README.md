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

 
![422266080-12eca13e-6c55-43c7-9306-32f30db1cf9b](https://github.com/user-attachments/assets/0c2ffce6-15cb-42b6-ac38-a0b59f7e08b5)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


![422266303-601ccc62-5eac-4325-b2e6-ef5e2f40629e](https://github.com/user-attachments/assets/e95ef8da-d21d-4d33-8cce-83a2ab9015d0)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir


![422266435-6320b9f5-ecbf-407e-8c33-6932b5adbc7b](https://github.com/user-attachments/assets/96f485da-f1c9-4a70-bba6-2fc2c29218c3)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir 


![422267227-1bfb8331-ef69-4083-b036-f616947ccce0](https://github.com/user-attachments/assets/97b07dc5-0afe-406b-8bfa-905066493996)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd 


![422267360-17ed06a3-83df-4215-a570-6aa9da63751d](https://github.com/user-attachments/assets/454e9302-1482-470c-980c-10821295aaea)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![422267539-9085a4e5-41a0-4b89-ab3a-9f9156a86ccf](https://github.com/user-attachments/assets/4cb6dd6d-3574-4a5a-b9c5-509e0528111d)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp 


![422267715-38500428-4534-4247-b56d-0b23b73c8ed6](https://github.com/user-attachments/assets/141b710e-b61f-4885-b6b8-3df660954dad)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


![422267874-3ac04521-5d53-4af3-8bc1-a56172ed06e5](https://github.com/user-attachments/assets/15212d10-aaf4-4825-a891-a5cbd8c37e91)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su 


![422268007-18855a0c-19f6-4fd0-9d46-7105abfe1467](https://github.com/user-attachments/assets/e7fa5777-34b4-44df-a165-240614aad20d)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv 


![422268164-0c048afe-1300-4af6-9b8e-d971eb883b62](https://github.com/user-attachments/assets/9deaa267-cb8b-4a38-9a43-1e53caca6410)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


![422268300-93d662a5-2617-42b1-ad27-5589c696f5b1](https://github.com/user-attachments/assets/9ad524f5-b696-476c-8af4-e1b60c6787b9)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head


![422268436-13950d64-e4bc-4d89-823d-2f4eaef97ac2](https://github.com/user-attachments/assets/fd7ff4d0-eb12-4e57-a7f9-056891be2162)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail 


![422268561-0dbd73ce-00dc-4682-a2d5-9f4f64f7fd8b](https://github.com/user-attachments/assets/930d3b24-637e-492b-bfa7-3d3878582897)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


![422268909-271bd113-094c-45e3-8ab3-55710729849f](https://github.com/user-attachments/assets/3adee7cd-9c58-4c85-94e1-2eb9e3a16d90)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


![422268914-b1d70ae4-a9b3-43ab-ae4c-dc0bb765cc78](https://github.com/user-attachments/assets/3a1c7bde-79e6-4bd7-8720-cbcec925d51d)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


![422269119-56bccda7-1cb2-4057-8d08-02c4a9957a48](https://github.com/user-attachments/assets/3fc0f50a-cb67-47be-9130-cd046483eb49)

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


![422269348-83dd6667-4762-4122-a451-c4666a026956](https://github.com/user-attachments/assets/bf714dcc-4c92-43bc-90b9-aaf05cfd03d1)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


![422269495-661f6446-ac1c-4e8f-aabc-98dc357b1f30](https://github.com/user-attachments/assets/c8f33471-e813-4e15-859c-896f35c13522)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


![276812468-49eba749-432d-4781-b840-cef388ea1cca](https://github.com/user-attachments/assets/d518579e-0b50-4dea-8eb9-695aca3471b4)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


![276812563-3ed1a386-4acd-45e0-988e-5c8f91724e91](https://github.com/user-attachments/assets/7167812f-a122-44b0-a7f5-5068b93d3805)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


![276812592-702d984b-18ab-41be-99ce-8f12092d5164](https://github.com/user-attachments/assets/6e2d399c-58b2-46a0-baf6-fbb0fe343b15)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


![276812681-94201a8c-442d-4d50-a950-6150c6b7c806](https://github.com/user-attachments/assets/ac7758d1-4991-4c8f-98e8-2f5f54c4116d)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


![276812710-f70d268d-3053-4257-9d7d-87836bf9b435](https://github.com/user-attachments/assets/44dcf7c6-9111-4ac1-b686-24ee43a16c74)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


![276812743-db06dbad-b3de-40e2-b4a6-7bc6347c78f0](https://github.com/user-attachments/assets/4c1bc740-7859-4600-8e7e-df142efd5a8d)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


![276812778-63f3333e-bbff-4fb1-8e49-ec4bbf8f3888](https://github.com/user-attachments/assets/60a5c3a7-f700-4bba-96df-6a5fbbbc50df)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


![276812829-4df9a6ff-ec1e-4929-adfe-32c909a90e4a](https://github.com/user-attachments/assets/4e07b3ef-eae6-42ac-966d-477cffe2c80c)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
