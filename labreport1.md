 # Lab Report 1

### Installing VSCode
Go to the Visual Studio Code website [Website](https://code.visualstudio.com/), and follow the instructions to download and install it on your computer. 

Once installed, open the application and it should look something like this:
![Image](https://ucsd-cse15l-s23.github.io/images/vscode.png)
### Remotely Connecting
In this step we will use VScode/terminal to connect to a remote computer over the Internet to do work there.

If you are using Windows you must install:

 [Git for Windows](https://gitforwindows.org/)

Once installed, use the steps in this post to set your default terminal to use the newly-installed `git bash` in Visual Studio Code:

 [Using Bash on Windoes in VScode](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)
 
 To find your CSE15L Account
Look up your course-specific account for CSE15L here:

[CSE15L Account](https://sdacs.ucsd.edu/~icc/index.php)

For help in resseting your password, here is a tutorial [Tutorial: How to Reset your CSE15L password](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view?usp=share_link)
Steps:
-Click on link, should be something like this:


<img width="855" alt="Screen Shot 2023-04-21 at 8 02 19 PM" src="https://user-images.githubusercontent.com/130090548/233758547-ba81170c-34fa-4e39-bd24-c8da02a5b885.png">




 Then, to use `ssh`, open a terminal in VScode. (Ctrl or Command + , or use the Terminal → New Terminal menu option). Your command will look like this, but with the `zz` replaced by the letters in your course-specific account. 
 
 `$ ssh cs15lsp23zz@ieng6.ucsd.edu`
 
 Don't copy the `$`, it's just a convention for how to write commands

As its the first time you've connected to the server, you should get a message like this:

`⤇ ssh cs15lsp23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])?`

Type `yes` and press enter, then give your password; the whole interaction should look something like this

<img width="870" alt="Screen Shot 2023-04-06 at 10 50 16 AM" src="https://user-images.githubusercontent.com/130090548/230487148-766ac2ef-a042-47a2-b0ff-e82cb8253679.png">


### Trying Some Commands
Try running commands `cd`, `ls`, `pwd`, `mkdir`, and `cp` and display what happens:
Here are some specific commans to try:



`ls`


<img width="407" alt="Screen Shot 2023-04-21 at 8 11 03 PM" src="https://user-images.githubusercontent.com/130090548/233758919-b23cb28e-989d-4ac7-9911-27c7b013c12c.png">


It is pretty much a command that list the files in the current directory

`ls -lat`
<img width="479" alt="Screen Shot 2023-04-21 at 8 17 11 PM" src="https://user-images.githubusercontent.com/130090548/233759099-c28fbdae-c15d-4c48-8658-561482b05bc3.png">


Displays all files and directories in the current directory, sorted by modification time in reverse order.




<img width="627" alt="Screen Shot 2023-04-06 at 1 21 29 PM" src="https://user-images.githubusercontent.com/130090548/230486181-8ca49c6c-89e4-4f93-b5e6-20bd7b536bec.png">
