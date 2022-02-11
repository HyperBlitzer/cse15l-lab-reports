# Streamlining ssh configuration (Windows)

### [Creating the .ssh config file]

- We are going to learn how to easily ssh into the server without typing `cs15lwi22zzz@ieng6.ucsd.edu`

- First, press (windows key + e), this will open up file explorer

- On the left side of the window, click on **This PC --> Windows (C:) --> Users --> (your user name) --> .ssh**

- Right click on the **.ssh** folder to add a txt file (most likely with notepad) called config

- Open the .txt file and add:

  ```
  Host ieng6
    HostName ieng6.ucsd.edu
    User cs15lwi22zzz (use your username)
  ```
  ![image](https://user-images.githubusercontent.com/90485689/153548133-76b06e54-eccf-4503-a1ba-400fb5c87029.png)
  
- You can change *ieng6* to something else that makes sense

- Save and now change the name of the file from *config.txt* to just *config*

### [Ssh'ing with the new alias]

- Head over to vscode and make a new file called `testingconfig.java`

- Open up the terminal and ssh into the ieng6 server, but instead of typing `cs15lwi22zzz@ieng6.ucsd.edu` , type what you put as the host

![image](https://user-images.githubusercontent.com/90485689/153549687-7a5749f3-67e8-4716-a9ad-5e158cdcfeff.png)

### [Scp'ing with the new alias]

- exit out of the server and add this code to your `testingconfig.java` file:

  ```
  public class testingconfig {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
  }
  ```
  
- In the terminal run `scp testingconfig.java ieng6:~/` 
- `ssh` back into the server and run `ls` to make sure that the `testingconfig.java` file is located in your student directory

![image](https://user-images.githubusercontent.com/90485689/153550509-abb5770b-fe8e-42ad-9866-f134564e88a4.png)




