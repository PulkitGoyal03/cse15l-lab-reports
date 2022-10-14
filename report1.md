# Lab Report 1 
Hello future students, welcome to CSE 15L. Below is a tutorial on how to get your environment set up and how to connect to the server.

**Installing VScode:**
Navigate to https://code.visualstudio.com/ and download the program. This will allow you to write code as well as give you access to a terminal in which you can connect to the server.

![Screenshot](https://user-images.githubusercontent.com/98442414/195953939-23fac949-ca6c-4118-a356-d9115784225c.png)

**Remotely Connecting:**
You then want to open up your terminal on either VScode or on your personal computer. I personally use my mac terminal which will look a little different than you may be doing but the entire idea is the same. You will first need to set a password to your CSE15L account which will look something like cs15lfa22XX@ieng6.ucsd.edu. You then need to type in your terminal “ssh *insert username here* and password in order to connect. It will then look something like this

![Screenshot (1)](https://user-images.githubusercontent.com/98442414/195954232-aec44372-f1c0-4537-b136-6c30af3980ed.png)

**Running Commands:**
If you made it this far, Congrats! You successfully connected to the server. You then can try some commands such as ls and cd which shows what files are in the system as well as allow you to change directories. 

![Screenshot (2)](https://user-images.githubusercontent.com/98442414/195954275-e5879537-63ac-4cb3-ba14-28a4c4686729.png)
![Screenshot (3)](https://user-images.githubusercontent.com/98442414/195954303-1f513be4-c65c-4a1b-9792-13d1253b85e2.png)

**Moving Files with scp:**
You can then try moving files around between systems using scp. In this example, I moved over a file that talks about what type of system it is running on. Notice how when it is run on the server, it uses linux rather than a mac or windows operating system. 

![Screenshot (4)](https://user-images.githubusercontent.com/98442414/195954375-def4a34f-9a86-4e26-ad79-cae51ae02e10.png)

**Setting an SSH Key:**
There is a program called ssh-keygen that creates files with both a public and private key that can be copied to a location on the server and a public key that can be copied to the client. In order to set it up, you wll need these lines of code.

![Screenshot (5)](https://user-images.githubusercontent.com/98442414/195954429-1410b578-1cb5-47d7-bb26-6ec989a9d465.png)

You then need to copy the public key to the ssh directory of a server and you can then use the server without needed to enter a password

**Optimization:**
After creating an ssh key, you can then run code directly without needing to login therefore increasing optimization. In order to do so, just type the command in quotations at the end of an ssh command and it will continue to run the command on the server without having to re-login
