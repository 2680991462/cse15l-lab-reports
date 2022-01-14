# Lab report for week 1-2

## Installing VScode
* becasue I took CSE11 last quarter, VScode was installed in advance

![Image](1.PNG)


## Remotely Connecting

* I download and Installed OpenSSH
* Find my course-specific account for CSE15L
* I entered the command like this "ssh cs15lwi22apn@ieng6.ucsd.edu"
and successfully connected to the server!
![Image](2.PNG)

## Trying Some Commands

* The command pwd prints the current working directory.
* The command ls -i lists the index number of each file.
* The command ls -a prints out all files in the current directory.
* The command exit will let me logout of the server.

![Image](8.PNG)

![Image](9.PNG)

![Image](10.PNG)

![Image](11.PNG)

## Moving Files with scp

* Create a file called WhereAmI.java
* I run the command scp in the terminal and it said i file copied
* I run on the client, and it works

![Image](4.PNG)

![Image](5.PNG)

## Setting an SSH Key

* type the command "ssh-keygen" and follow the instructions.
* Windows computer should follow the extra ssh-add stpes
* Open the powershell and complete the extra steps
* after finished, I can copy without entering my password

![Image](6.PNG)

## Optimizing Remote Running

* This command will send a copy of the file to the server, logs into the server, execute the javac and java command in the same line. with saves a lot of work. 

![Image](7.PNG)

