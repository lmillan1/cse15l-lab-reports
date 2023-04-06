 # Lab Report 1

### Installing VSCode
Go to the Visual Studio Code website [Website](https://code.visualstudio.com/), and follow the instructions to download and install it on your computer. 

Once installed, open the application and it should look something like this:
![Image](https://ucsd-cse15l-s23.github.io/images/vscode.png)
### Remotely Connecting
In this step we will use VScode/terminal to connect to a remote computer over the Internet to do work there.
**If you are using Windows you must install:

 [Git for Windows](https://gitforwindows.org/)

Once installed, use the steps in this post to set your default terminal to use the newly-installed `git bash` in Visual Studio Code:

 [Using Bash on Windoes in VScode](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)
 
 Then, to use `ssh`, open a terminal in VScode. (Ctrl or Command + , or use the Terminal → New Terminal menu option). Your command will look like this, but with the `zz` replaced by the letters in your course-specific account. 
 
 `$ ssh cs15lsp23zz@ieng6.ucsd.edu`
 
 Don't copy the `$`, it's just a convention for how to write commands

As its the first time you've connected to the server, you should get a message like this:

`⤇ ssh cs15lsp23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])?`

Type `yes` and press enter, then give your password; the whole interaction should look something like this

![Image](file:///Users/luismillan/Desktop/Screen%20Shot%202023-04-06%20at%2012.54.58%20PM.pdf)
### Trying Some Commands
