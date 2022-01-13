# Installing VScode

* You first want to head over to --> [vscode website](https://code.visualstudio.com) to download vscode

![](https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/vsdownloadcircle.jpg)

* You then want to open up visual studio code which looks like when opened:

![](https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/vscodeactual.png)

* Create a folder on your desktop named **CSE15L**
* Then open that folder in vscode (under `open file...`)
* Once you have that folder opened, head over to your **explorer** on the left and hover over CSE15L and click the new file button

<img src="https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/newfile.jpg" width="155" height="115">

* Name the file *"connecting.java"*.
* Inside the class copy this piece of code:

```
public static void main(String[] args) {
        System.out.println("Hello Celestial Body!");
    }
```

* At the top of vscode, click **Terminal** and then **New Terminal**. This is where we will be inputting our commands to connect to the server.
* Your vscode should look something like:

![](https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/codeplusterminal.png)

# Remotely Connecting

* Windows: Install OpenSSH which allows you to connect to other servers --> [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)

* Lookup your CSE15L account name --> [UCSD account lookup](https://sdacs.ucsd.edu/~icc/index.php)

* In your vscode terminal enter this command, but replace AAA with your account specific letters:

`ssh cs15lwi22AAA@ieng6.ucsd.edu`

* A block of text should show up, just type *yes* into the terminal and then enter the password
* After sucessfully entering your password, your terminal should look like this:

<img src="https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/connected.png" width="425" height="190">

* You have now connected to the basement computers at UCSD

# Trying Some Commands

* Create a new terminal. You now have one terminal connected to the server *ssh* and another that is running on your computer *powershell*

![](https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/diffterms.png)

* Try these commands on both the server and client terminals
* `cd ~`
* `cd`
* `ls -lat`
* `ls -a`
* `pwd`

* If you ever want to leave the server just run `exit`

![](https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/lslatexamp.png)\
example of ls -lat command in server

![](https://github.com/HyperBlitzer/cse15l-lab-reports/blob/main/pwdexamp.png)\
example of pwd command in client

# Moving Files with scp





# Setting an SSH Key




# Optimizing Remote Running



