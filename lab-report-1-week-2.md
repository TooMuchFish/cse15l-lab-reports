# Name : Shaodong Shan
# Course: CSE 15L
Date: April 9, 2022

This is my first lab report, welcome.
![welcome](https://user-images.githubusercontent.com/103075501/162642398-9902f982-4aa5-4e33-816d-d0eba4ceace9.jpeg)

In this lab report, I'll indroduce the steps to complete how to complete the following steps.
* Installing VScode
* Remotely Connecting
* Trying Some Commands
* Moving Files with scp
* Setting an SSH Key
* Optimizing Remote Running


# 1. Installing the VScode

[VScode](https://code.visualstudio.com) is a website to download the free software, and the [follow the viedo](https://www.youtube.com/watch?v=MlIzFUI1QGA) to do the steps, you will be able to install your VScode easily
Notice your computer system and the VScode vision when you start this.
<img width="1193" alt="vscode1" src="https://user-images.githubusercontent.com/103075501/162642160-c92f1ee8-54fd-489a-814e-659a568dc126.png">

After you agree the agreement of vscode push to you, your vscode will ready to use, like the the image below.
<img width="1440" alt="vscode2" src="https://user-images.githubusercontent.com/103075501/162642179-6315fb5e-e112-42a6-af22-b330b221edf0.png">

welcome to the coding world!

# 2. Remotely Connecting
First thing is download the OpenSSH if you have not, [right here!](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
Then we need to finish the setting up which called my course speacial account before the class, [right here!](https://sdacs.ucsd.edu/~icc/index.php)
<img width="1128" alt="OPENSSH1" src="https://user-images.githubusercontent.com/103075501/162642195-f0854705-32aa-40d3-bde1-324aa8a55f7e.png">
when we need to login to the server remotely, we just use the command " ssh cs15lsp22aqr@ieng6.ucsd.edu " input to the terminal in your VScode.
then you will see the image below, it means you are remotely connecting to your class.
<img width="1088" alt="OpenSSH2" src="https://user-images.githubusercontent.com/103075501/162642221-ef3bef20-7284-413d-a0b7-88f5ad9e1194.png">

# 3. Trying Some Commands
there are a few commands we can use in terminal
* ls -lat
* ls -a
* cd
* cd ~
* pwd
* cp
* in <directory>
  <img width="1046" alt="somecommand" src="https://user-images.githubusercontent.com/103075501/162642236-17aeec9c-20bd-4ea1-b89d-8381bf5ad826.png">

# 4. Moving Files with scp
if we want to moving files with scp, now we saved a java file named WhereAmI.java, we can use the command "scp WhereAmI.java cs15lsp22apr@ieng6.ucsd.edu" to send it to remote server. like the image below.
![movingfilewithscp](https://user-images.githubusercontent.com/103075501/162642315-2f7ec480-0398-4b26-9fc0-afefa17b4448.png)

# 5. Setting an SSH Key
In this step, we are going to start the setting up of the SSH key, like the image below.
![settingkey](https://user-images.githubusercontent.com/103075501/162642330-8022ae39-7c9e-46bb-b5e4-7053e9a8774a.png)

# 6. Optimizing Remote Running
This step is calling the java file within the remote server, we can use some command keys:
* java
* javac filename.java
* etc..
![remoterunning](https://user-images.githubusercontent.com/103075501/162642349-34c97311-48cb-4c85-a17e-963c54c2a6db.png)
# Thank you
This is the end of my lab 1 report. Thank your watching.
  
![thank-you](https://user-images.githubusercontent.com/103075501/162642394-44533b1f-86e6-4dd4-ac23-0c8392cfdbbb.jpg)
