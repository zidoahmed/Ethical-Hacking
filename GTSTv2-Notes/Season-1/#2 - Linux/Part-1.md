# Intro to Linux
### What is Linux
- Linux is a kernel, not an operating system. (*without GNU, it is just a kernel but with the GNU in the front like GNU/Linux becomes an OS*)
- **Kernel** is a code/program that is used to meet your software and hardware and allocate some resources. (basically, it is used to connect the hardware and software found in our computer.)
- ![[Linux_kernel.jpg]]
- For an operating system to known as an OS, it needs a kernel in order to connect both the hardware and software of a computer. Linux is the kernel of the Linux OS. 
### History of Linux
- In **1969**, a team led by computer scientists **Ken Thompson and Denis Pitchie** created the first version of **UNIX on a PDP-7 minicomputer.**
- Which was chosen by mainly because of Thompson's familiarity with the system from his hobby work on it.
- ==BUT IT WASN'T CHEAP AND OPEN-SOURCE==
- Then person called "Linus Torvalds" created the Linux kernel and posted it online to make it open-source and it was developed in C programming language.
- By doing this, Linus Torvalds fixed **the two main issues** with unix systems which were:-
	1. **Not being cheap** = *he basically made it free.*
	2. **Not being open-source** = *he posted the source code online on his github.*
- After several years, **Richard Stallman** announced the GNU project in 1983 and co-founded the Free software foundation in **1983**.
- GNU is a free software replacement not full OS, but it was just software replacement not full OS. {Examples: Bash, tar, emacs, etc...}
- So **GNU (Software or software replacement)** + **Linus Kernel (Kernel)** will give the **GNU/LINUX OS.**
- The GNU Linux project was started to create a Unix-like operating system created with source code that could be copied, modified and redistributed. 
- For an OS to be called an OS, it needs two basic things:-
	1. A kernel, like the Linux kernel and
	2. software in that OS. (The software is essential for the kernel to function properly)
### What is shell
- *Users communicate with the kernel by the shell.
- The shell is a **command line interpreter (CLI)**. It translated commands entered by the user and converts them into a language that is understood by the kernel (*Translates from human language to binary code and then redoes the process whenever the user communicate with the kernel*)
- Shell is a common name in all Operating Systems whether it's Windows, GNU/Linux, Mac OS or any other OS. 
- But later on, Microsoft decided to name its shell to **Powershell (CMD)** and Linux became **Terminal** while Mac OS named theirs **Zsh** (Z shell) or **Terminal** like Linux.
### Types of shells
- Based on their features there are many shells.
	- SH
	- BASH
	- ZSH
	- FISH
- They differ in coloring, piping, command compilation and other kind of features.
- The commands you use on each shell are the same, the difference is mainly in coloring, piping and command compilation.
- To identify your shell, write this command:
```
> echo $SHELL
```
- Then, it will show you what kind of shell you're currently using.
- **SH Interface**:- No flashy coloring, just straight black and white. ![[shell_interface.jpg]]
- **BASH Interface**:- It's more colorful than SH. Have better piping then SH ![[bash_Interface.jpg]]
- **ZSH Interface**:- is my current shell in my laptop, so basically I don't photos of it.
- **FISH Interface**:- considered the most colorful shell type of all types. it is more recommended for women because it is mostly used by women hackers. ![[fish_Interface.jpg]]
### What is an OS - Operating System?
- OS is "Operating System", which means the main software part of computer that helps to work on.
- It is our computer's main software, without it our computers would be a blank screen. (Hardware without software can't exist and vice versa.)
- It contains:
	- **Kernel**:- Described above, a code that helps the hardware and software to communicate.
	- **Software**:- apps or other programs that can be installed on our computers
	- **Desktop environment**:- is a graphical interface that provide users with a visual way to interact with your OS. The different desktop environments are *mate, gnome, KDE plasma (similar with windows) and XFCE.*
		- To choose which desktop environment suits you, it depends on one thing; Speed:
			1. **If you have a slow PC**, XFCE and mate are good choices.
			2. **If you have a fast PC**, Gnome and KDE Plasma are better choices for customization and graphics. but you can stick with any desktop environment you want based on your goals.
	- **File extensions**
	- **Windows manager**
### Why Linux is used for hacking?
#### 1. Linux is fast
- No high spec computer/device needed.
- It works both for slow and fast PCs. But when it comes to windows, it becomes limited with a lot of criterias.
- Speed is essential in the field of cybersec to solve critical problems.
#### 2. Linux's usage in the industry
- **47% of professional developers use Linux-based operating systems**
- Linux powers **39.2%** of websites whose operating system is known.
- Linux powers **85%** of smartphones. (Hayden James)
- Linux, the third most popular desktop OS, has a market share of **2.09%.**
- The Linux market size world wide will reach **$15.64 billion** by 2022.
- The **world top 500 fastest supercomputers all run on Linux.**
- **96.3%** of the top one million web servers are running on Linux
- Today, there are over 600 active Linux distros
#### 3. Most Hacking tools are in Linux
- Almost all of the essential hacking tools are in Linux. Tools for hacking websites, apps, mobiles, servers, passwords and much more are found in Linux.
- The famous tool, **Burpsuite**, became available on windows very recently. but it is still more preferred on Linux. 
