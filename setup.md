---
layout: page
title: Setup
root: .
---

You need to download some files to follow this lesson:

<<<<<<< HEAD
1. Download [shell-novice-data.zip]({{ page.root }}/data/shell-novice-data.zip) and move the file to your Desktop.
2. Unzip/extract the file (ask your instructor if you need help with this step). You should end up with a new folder called data-shell on your Desktop.
3. Open a terminal and type:
=======
1. Download [data-shell.zip]({{ page.root }}/data/data-shell.zip) and move the file to your Desktop.
2. Unzip/extract the file (ask your instructor if you need help with this step). You should end up with a new folder called **data-shell** on your Desktop.
3. Open a terminal and type `cd`, then press the Enter key. That last step will make sure you start with your home folder as your working directory.
>>>>>>> 1d5edf0e14ef1f442f564ef8d0a6d910476cbcbc

~~~
$ cd
~~~
{: .bash}

That last step will make sure you start with your home folder as your working directory.

> ## Where to type commands: How to open a new shell
> The shell is a program that enables us to send commands to the computer and receive output. It is also referred to as the terminal or command line.
>
> Some computers include a default Unix Shell program. 
> The steps below describe some methods for identifying and opening a Unix Shell program if you already have one installed. 
> There are also options for identifying and downloading a Unix Shell program, a Linux/UNIX emulator, or a program to access a Unix Shell on a server. 
>
> If none of the options below address your circumstances, try an online search for: Unix shell [your computer model] [your operating system].
>
> ### Linux
> The default Unix Shell for Linux operating systems is usually Bash.
> On most versions of Linux, it is accessible by running the [(Gnome) Terminal](https://help.gnome.org/users/gnome-terminal/stable/)
> or [(KDE) Konsole](https://konsole.kde.org/)
> or [xterm](https://en.wikipedia.org/wiki/Xterm),
> which can be found via the applications menu or the search bar.
> If your machine is set up to use something other than bash, you can run it by opening a terminal and typing `bash`.
>
> ### MacOS
> For a Mac computer, the default Unix Shell is Bash,
> and it is available via the `Terminal` application.
>
> To open Terminal, try one or both of the following:
<<<<<<< HEAD
> * Go to your ‘Applications’ folder. Within ‘Applications’, open the ‘Utilities’ folder. Locate `Terminal` in that folder and open it.
> * Use the Mac ‘Spotlight’ computer search function. Search for: Terminal and press [Enter] - this will open Terminal.
=======
> * Go to your Applications. Within Applications, open the Utilities folder. Locate Terminal in the Utilities folder and open it.
> * Use the Mac ‘Spotlight’ computer search function. Search for: `Terminal` and press <kbd>Return</kbd>.
>>>>>>> 1d5edf0e14ef1f442f564ef8d0a6d910476cbcbc
>
> ### Windows
<<<<<<< HEAD
> Windows machines do not automatically have a Unix Shell program installed.
>
> There are two options here:
> * Use ‘Windows Subsystem for Linux’, which installs the user-facing
>   parts of a Linux distribution, including a shell; or
> * Use a terminal program to connect to a remote Unix machine via ‘SSH’.
>
> _Windows Subsystem for Linux_: this installs a bash shell, and the
> other tools which you'd expect to find in a Linux distribution, but
> running natively on Windows.  To install this, see [Microsoft's
> guidance](https://docs.microsoft.com/en-gb/windows/wsl/about) (or a
> few other sources of advice:
> [1](https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10),
> [2](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/),
> [3](https://www.howtogeek.com/265900/everything-you-can-do-with-windows-10s-new-bash-shell/)).
>
> _Using a terminal program for SSH_: There are a couple of options
> here, but probably the most straightforward is to use
> [MobaXTerm](https://mobaxterm.mobatek.net).
> [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/) is a
> very well-known and stable alternative, though it has less
> functionality.  A third possibility is
> [Cygwin](http://www.cygwin.com): some people swear by Cygwin, but in
> our experience it can be a little unpredictable.
=======
> Computers with Windows operating systems do not automatically have a Unix Shell program installed.
> In this lesson, we encourage you to use an emulator included in Git for Windows, 
> which gives you access to both Bash shell commands and Git. 
> If you are attending a Software Carpentry workshop session, it is likely you have already received instructions on how to install Git for Windows.
>
> Once installed, you can open a terminal by running the program Git Bash from the Windows start menu.
>
> Other solutions are available for running Bash commands on Windows. 
> There is now a Bash shell command-line tool available for Windows 10. 
> Additionally, you can run Bash commands on a remote computer or server that already has a Unix Shell, from your Windows machine. 
> This can usually be done through a Secure Shell (SSH) client. 
> One such client available for free for Windows computers is PuTTY. 
> See the reference below for information on installing and using PuTTY, 
> using the Windows 10 command-line tool, or installing and using a Unix/Linux emulator.
>
> #### Reference
> * [Git for Windows](https://git-for-windows.github.io/)
> * [How to Install Bash shell command-line tool on Windows 10](https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10)
> * [Install and Use the Linux Bash Shell on Windows 10](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)
> * [Using the Windows 10 Bash Shell](https://www.howtogeek.com/265900/everything-you-can-do-with-windows-10s-new-bash-shell/)
> * [Using a Unix/Linux emulator (Cygwin) or Secure Shell (SSH) client (Putty)](http://faculty.smu.edu/reynolds/unixtut/windows.html)
>>>>>>> 1d5edf0e14ef1f442f564ef8d0a6d910476cbcbc
{: .callout}
