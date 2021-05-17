# **Welcome to the Linux Shell edition of Dialy Blogs**

<img src="assets/shell.jpg" width=100% height=50%>

##### Photo by <a href="https://unsplash.com/@hellomm?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">xiaokang Zhang</a> on <a href="https://unsplash.com/s/photos/linux-shell?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

<br />

### *"She sells seashells by the seashore..."*

Ever heard of this tongue twister? Probably you would have. But don't worry, we are not going to learn about those kind of shells!

You may wonder, *in a world where everyone is using GUIs(acronym of Graphical User Interfaces), why on earth do we need to use a shell?* 

A valid question indeed! Believe me, the possibilities that you can uncover by using shells are vast. If you ask me, I would say that *the GUIs are just a tip of the iceberg.*

Now, I am assuming that you guys already know about Linux a little bit. If you don't have, no need to worry. Just go through this wonderfull article [What is Linux®?](https://www.explainthatstuff.com/linux.html) by [Chris Woodford](https://www.explainthatstuff.com/chris-woodford.html) and come back here.

### **So ready to dive into the world of Linux Shells now?**

*A Unix shell is a command-line interpreter or shell that provides a command line user interface for Unix-like operating systems. The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts.* (An excerpt from [https://en.wikipedia.org/wiki/Unix_shell](https://en.wikipedia.org/wiki/Unix_shell) page.)

To put in simpler terms, A shell is what sits between a Graphical User Interface (a.k.a. GUI) you are using and your computer hardware that does the stuff you want done.

By now, you may have understood that the most of the applications you are using is just *"front ends"* to these shells. So everything that can be done using an GUI can be also be done using shells. Now, I am pretty sure that you are getting more and more curious to learn more about shells!

Shell is what you can call a **Command Line Utility or a CLI**. It is actually a program that interprets commands, not an *operating system*. It is the way to interface with the operating system and run commands. Just as you guessed a **shell script** is an automated way of running these commands.

### **Bash**
Bash, or the Bourne-Again Shell, is the far most widely used and the default shell installed on most of the Linux distributions. Bash is an enhanced version of the original Unix shell program, **sh**, written by Steve Bourne. 

Other than Bash, there are other shells available also, these includes ksh, tcsh and zsh. If you are a beginner to Linux and Linux shell, I would recommend using **Bash** first and then learn other shells.

### **Now it's time to get our hands dirty!**

There is many options of enviroments to learn shell. If you don't have a linux system with you, you can try using online linux terminals like [copy.sh](https://copy.sh/v86/?) or [tutorial point terminal](https://www.tutorialspoint.com/unix_terminal_online.php). And there is always advance options like WSL2(Windows Subsystem for Linux) on your Windows systems.

If you are with a Linux system, you need to open the **Terminal**. Wondering what it is? It's a program called a *terminal emulator*. This is the program that opens a window and let's you interact with the shell. There is a bunch of different terminal emulator available including gnome-terminal, konsole, xterm, rxvt, kvt, nxterm, and eterm. 

If you are using one of the online emultors, the interface provided by them is equalent to the terminal.

Once you open the **terminal**, you will see something like this written on it with your username and system name.

```sh
john@mylinux:~$
```

The first part, "john", is just the user’s login name. "@mylinux" is the name of the computer the user is logged into. The "~" character tells us that user Joe is working from his home directory. The "$" character is the standard character denoting a non-root, regular user.

Now lets say, you want to list all the files in the home directory, all you have to type is

```sh
john@mylinux:~$ ls
```

The command *ls* is called a list command which returns list of the contents in a directory. Once you hit Enter key, the shell will respond with an output similar to this;

```sh
Desktop Documents Downloads Music 

Video Pictures 
```

This list may look a lot familiar, because these are the folder/files in your home directory.

Now, let's we have to create an empty file with the name *john.txt*. Ofcourse you are well familier with creating a file using File Browser, the GUI way. But this time lets try the CLI way.

All you have to do it use the command *touch* followed by the filename. Let's try

```sh
john@mylinux:~$ touch john.txt
```

This command will create the file in the current directory your shell is pointing that is the home directory. Now if you run the *ls* (list) command again, you would see the file name in the list.

As I mentioned earlier, the example here are just the tip of the iceberg. For more detailed commands try going through [linux-shell-commands notes](https://docs.cs.cf.ac.uk/notes/linux-shell-commands/) from CARDIF University.


### **References**
1. [https://www.linux.com/training-tutorials/introduction-linux-shell/](https://www.linux.com/training-tutorials/introduction-linux-shell/)
2. [https://linuxcommand.org/lc3_lts0010.php](https://linuxcommand.org/lc3_lts0010.php)