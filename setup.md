---
layout: page
title: Setup
root: .
---

You need to download some files to follow this lesson:

1. Download [shell-novice-data.zip]({{ page.root }}/data/shell-novice-data.zip) and move the file to your Desktop.
2. Unzip/extract the file (ask your instructor if you need help with this step). You should end up with a new folder called data-shell on your Desktop.
3. Open a terminal and type:

~~~
$ cd
~~~
{: .bash}

That last step will make sure you start with your home folder as your working directory.

> ## Where to type commands: How to open a new shell
> The `shell` is a program that enables us to send commands to the computer and recive output. It is also referred to as the `terminal` or `command line`.
>
> Some computers include a default Unix Shell program. 
> The steps below describe some methods for identifying and opening a Unix Shell program if you already have one installed. 
> There are also options for identifying and downloading a Unix Shell program, a Linux/UNIX emulator, or a program to access a UNIX server. 
>
> If none of the options below address your circumstances, try an online search for: UNIX shell [your computer model] [your operating system].
>
> ### Linux
> The default shell for Linux operating systems is usually Bash.
> On most versions of Linux, it is accessible by running the Terminal program,
>  which can be found via the applications menu or the search bar.  
> If your machine is set up to use something other than bash, you can run it by opening a terminal and typing `bash`.
>
> ### MacOS
> For a Mac computer, the default Unix Shell is Bash,
> and it is available via the `Terminal` application.
>
> To open Terminal, try one or both of the following:
> * Go to your ‘Applications’ folder. Within ‘Applications’, open the ‘Utilities’ folder. Locate `Terminal` in that folder and open it.
> * Use the Mac ‘Spotlight’ computer search function. Search for: Terminal and press [Enter] - this will open Terminal.
>
> ### Windows
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
{: .callout}
