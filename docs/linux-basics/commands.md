---
sidebar_label: Commands
sidebar_position: 1
slug: commands
---

# 34 Basic Linux Commands Every User Should Know

[VPS](https://www.hostinger.com/tutorials/vps)   May 12, 2022 Artūras B.   9 min Read

![34 Basic Linux Commands Every User Should Know](https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2019/05/linux-commands-1.webp)


[Download Complete Linux Commands Cheat Sheet](https://app.monstercampaigns.com/c/jg9u9k0by4lj9pvcjeso/)

When hearing about Linux, most people think of a complicated operating system that is only used by programmers. But it’s not as scary as it seems.

Linux is an entire family of open-source Unix operating systems, that are based on the Linux Kernel. This includes all of the most popular Linux based systems like Ubuntu, Fedora, Mint, Debian, and others. More accurately, they’re called distributions or distros.

Since Linux was first released in **1991**, it has continued to gain popularity due to its open-source nature. People can freely modify and redistribute it under their own name.

When operating a Linux OS, you need to use a shell — an interface that gives you access to the operating system’s services. Most Linux distributions use a graphic user interface (GUI) as their shell, mainly to provide ease of use for their users. It is common practice to use them when managing a [VPS](/docs/what-is-vps-hosting).

That being said, it’s recommended to use a command-line interface (CLI) because it’s more powerful and effective. Tasks that require a multi-step process through GUI can be done in a matter of seconds by typing commands into the CLI.

So if you’re considering using Linux, learning basic command lines will go a long way. In this article, you’ll learn **3**4 basic Linux commands that will undoubtedly help you navigate through Linux as a newbie.

Linux Basic Commands
--------------------

Before we go on to the list of commands, you need to open the command line first. If you are still unsure about the command-line interface, check out this [CLI tutorial](https://www.hostinger.com/tutorials/what-is-cli).

Although the steps may differ depending on the distribution that you’re using, you can usually find the command line in the **Utilities** section.

Here is a list of basic Linux commands:

### 1\. pwd command

Use the **pwd** command to find out the path of the current working directory (folder) you’re in. The command will return an absolute (full) path, which is basically a path of all the directories that starts with a forward slash **(/)**. An example of an absolute path is **/home/username**.

### 2\. cd command

To navigate through the Linux files and directories, use the **cd** command. It requires either the full path or the name of the directory, depending on the current working directory that you’re in.

Let’s say you’re in **/home/username/Documents** and you want to go to **Photos**, a subdirectory of **Documents**. To do so, simply type the following command: **cd** **Photos**.

Another scenario is if you want to switch to a completely new directory, for example,**/home/username/Movies**. In this case, you have to type **cd** followed by the directory’s absolute path: **cd /home/username/Movies**.

There are some shortcuts to help you navigate quickly:

*   **cd ..** (with two dots) to move one directory up
*   **cd** to go straight to the home folder
*   **cd-** (with a hyphen) to move to your previous directory

On a side note, Linux’s shell is case sensitive. So, you have to type the name’s directory exactly as it is.

### 3\. ls command

The **ls** command is used to view the contents of a directory. By default, this command will display the contents of your current working directory.

If you want to see the content of other directories, type **ls** and then the directory’s path. For example, enter **ls** **/home/username/Documents** to view the content of **Documents**.

There are variations you can use with the **ls** command:

*   **ls -R** will list all the files in the sub-directories as well
*   **ls -a** will show the hidden files
*   **ls -al** will list the files and directories with detailed information like the permissions, size, owner, etc.

### 4\. [cat command](/docs/linux-basics/cat-command/)

**cat** (short for concatenate) is one of the most frequently used commands in Linux. It is used to list the contents of a file on the standard output (sdout). To run this command, type **cat** followed by the file’s name and its extension. For instance: **cat file.txt**.

Here are other ways to use the **cat** command:

*   **cat > filename** creates a new file
*   **cat filename1 filename2>filename3** joins two files (1 and 2) and stores the output of them in a new file (3)
*   to convert a file to upper or lower case use, **cat filename | tr a-z A-Z >output.txt**

### 5\. cp command

Use the **cp** command to copy files from the current directory to a different directory. For instance, the command **cp scenery.jpg** **/home/username/Pictures** would create a copy of **scenery.jpg** (from your current directory) into the **Pictures** directory.

### 6\. [mv command](/docs/linux-basics/mv-command/)

The primary use of the **mv** command is to move files, although it can also be used to rename files.

The arguments in mv are similar to the cp command. You need to type **mv**, the file’s name, and the destination’s directory. For example: **mv file.txt /home/username/Documents**.

To rename files, the Linux command is **mv oldname.ext newname.ext**

### 7\. mkdir command

Use **mkdir** command to make a new directory — if you type **mkdir Music** it will create a directory called **Music**.

There are extra **mkdir** commands as well:

*   To generate a new directory inside another directory, use this Linux basic command **mkdir Music/Newfile**
*   use the **p** (parents) option to create a directory in between two existing directories. For example, **mkdir -p Music/2020/Newfile** will create the new “2020” file.

### 8\. [rmdir command](/docs/how-to-remove-files-and-folders-using-linux-command-line/)

If you need to delete a directory, use the **rmdir** command. However, rmdir only allows you to delete empty directories.

### 9\. rm command

The **rm** command is used to delete directories and the contents within them. If you only want to delete the directory — as an alternative to rmdir — use **rm -r**.

**Note**: Be very careful with this command and double-check which directory you are in. This will delete everything and there is no undo.

### 10\. [touch command](/docs/linux-touch-command-with-useful-examples/)

The **touch** command allows you to create a blank new file through the Linux command line. As an example, enter touch **/home/username/Documents/Web.html** to create an HTML file entitled **Web** under the **Documents** directory.

### 11\. locate command

You can use this command to **locate** a file, just like the search command in Windows. What’s more, using the **\-i** argument along with this command will make it case-insensitive, so you can search for a file even if you don’t remember its exact name.

To search for a file that contains two or more words, use an asterisk **(\*)**. For example, **locate -i school\*note** command will search for any file that contains the word “school” and “note”, whether it is uppercase or lowercase.

### 12\. [find command](/docs/how-to-use-find-and-locate-commands-in-linux/)

Similar to the **locate** command, using **find** also searches for files and directories. The difference is, you use the **find** command to locate files within a given directory.

As an example, find **/home/ -name notes.txt** command will search for a file called **notes.txt** within the home directory and its subdirectories.

Other variations when using the **find** are:

*   To find files in the current directory use, **find . -name notes.txt**
*   To look for directories use, **/ -type d -name notes. txt**

### 13\. [grep command](/docs/grep-command-in-linux-useful-examples/)

Another basic Linux command that is undoubtedly helpful for everyday use is **grep**. It lets you search through all the text in a given file.

To illustrate, **grep blue notepad.txt** will search for the word blue in the notepad file. Lines that contain the searched word will be displayed fully.

### 14\. [sudo command](/docs/sudo-and-the-sudoers-file/)

Short for “**SuperUser Do**”, this command enables you to perform tasks that require administrative or root permissions. However, it is not advisable to use this command for daily use because it might be easy for an error to occur if you did something wrong.

### 15\. df command

Use **df** command to get a report on the system’s disk space usage, shown in percentage and KBs. If you want to see the report in megabytes, type **df -m**.

### 16\. [du command](/docs/vps/how-to-check-and-manage-disk-space-via-terminal)

If you want to check how much space a file or a directory takes, the **du** (Disk Usage) command is the answer. However, the disk usage summary will show disk block numbers instead of the usual size format. If you want to see it in bytes, kilobytes, and megabytes, add the **\-h** argument to the command line.

### 17\. head command

The **head** command is used to view the first lines of any text file. By default, it will show the first ten lines, but you can change this number to your liking. For example, if you only want to show the first five lines, type **head -n 5 filename.ext**.

### 18\. [tail command](/docs/how-to-use-tail-command/)

This one has a similar function to the head command, but instead of showing the first lines, the **tail** command will display the last ten lines of a text file. For example, **tail -n filename.ext.**

### 19\. diff command

Short for difference, the **diff** command compares the contents of two files line by line. After analyzing the files, it will output the lines that do not match. Programmers often use this command when they need to make program alterations instead of rewriting the entire source code.

The simplest form of this command is **diff file1.ext file2.ext**

### 20\. [tar command](/docs/linux-tar-command-with-examples/)

The **tar** command is the most used command to archive multiple files into a **tarball** — a common Linux file format that is similar to zip format, with compression being optional.

This command is quite complex with a long list of functions such as adding new files into an existing archive, listing the content of an archive, extracting the content from an archive, and many more. Check out some [practical examples](https://www.linuxtechi.com/17-tar-command-examples-in-linux/) to know more about other functions.

### 21\. [chmod command](/docs/vps/change-linux-permissions-and-owners)

**chmod** is another Linux command, used to change the read, write, and execute permissions of files and directories. As this command is rather complicated, you can read [the full tutorial](https://www.computerhope.com/unix/uchmod.htm) in order to execute it properly.

### 22\. [chown command](/docs/linux-chown-command/)

In Linux, all files are owned by a specific user. The **chown** command enables you to change or transfer the ownership of a file to the specified username. For instance, **chown linuxuser2 file.ext** will make **linuxuser2** as the owner of the **file.ext**.

### 23\. jobs command

**jobs** command will display all current jobs along with their statuses. A job is basically a process that is started by the shell.

### 24\. [kill command](/docs/how-to-kill-a-process-in-linux/)

If you have an unresponsive program, you can terminate it manually by using the **kill** command. It will send a certain signal to the misbehaving app and instructs the app to terminate itself.

There is a total of [sixty-four signals](https://linoxide.com/linux-how-to/linux-signals-part-1/) that you can use, but people usually only use two signals:

*   **SIGTERM (15)** — requests a program to stop running and gives it some time to save all of its progress. If you don’t specify the signal when entering the kill command, this signal will be used.
*   **SIGKILL (9)** — forces programs to stop immediately. Unsaved progress will be lost.

Besides knowing the signals, you also need to know the process identification number (PID) of the program you want to **kill**. If you don’t know the PID, simply run the command **ps ux**.

After knowing what signal you want to use and the PID of the program, enter the following syntax:

**kill \[signal option\] PID**.

### 25\. [ping command](/docs/linux-ping-command-with-examples/)

Use the **ping** command to check your connectivity status to a server. For example, by simply entering **ping google.com**, the command will check whether you’re able to connect to Google and also measure the response time.

### 26\. wget command

The Linux command line is super useful — you can even download files from the internet with the help of the **wget** command. To do so, simply type **wget** followed by the download link.

### 27\. uname command

The **uname** command, short for Unix Name, will print detailed information about your Linux system like the machine name, operating system, kernel, and so on.

### 28\. [top command](/docs/vps/how-to-manage-processes-in-linux-using-command-line)

As a terminal equivalent to Task Manager in Windows, the **top** command will display a list of running processes and how much CPU each process uses. It’s very useful to monitor system resource usage, especially knowing which process needs to be terminated because it consumes too many resources.

### 29\. history command

When you’ve been using Linux for a certain period of time, you’ll quickly notice that you can run hundreds of commands every day. As such, running **history** command is particularly useful if you want to review the commands you’ve entered before.

### 30\. man command

Confused about the function of certain Linux commands? Don’t worry, you can easily learn how to use them right from Linux’s shell by using the **man** command. For instance, entering **man tail** will show the manual instruction of the tail command.

### 31\. echo command

This command is used to move some data into a file. For example, if you want to add the text, “Hello, my name is John” into a file called name.txt, you would type **echo Hello, my name is John** **\>> name.txt**

### 32\. zip, [unzip command](/docs/how-to-unzip-files-linux/)

Use the **zip** command to compress your files into a zip archive, and use the **unzip** command to extract the zipped files from a zip archive.

### 33\. hostname command

If you want to know the name of your host/network simply type **hostname**. Adding a **\-i** to the end will display the IP address of your network.

### 34\. useradd, userdel command

Since Linux is a multi-user system, this means more than one person can interact with the same system at the same time. **useradd** is used to create a new user, while **passwd** is adding a password to that user’s account. To add a new person named John type, **useradd John** and then to add his password type, **passwd 123456789.**

To remove a user is very similar to adding a new user. To delete the users account type, **userdel UserName**

### Bonus Tips and Tricks

Use the **clear** command to clean out the terminal if it is getting cluttered with too many past commands.

Try the **TAB** button to autofill what you are typing. For example, if you need to type Documents, begin to type a command (let’s go with **cd Docu,** then hit the TAB key) and the terminal will fill in the rest, showing you **cd Documents**.

**Ctrl+C** and **Ctrl+Z** are used to stop any command that is currently working. Ctrl+C will stop and terminate the command, while Ctrl+Z will simply pause the command.

If you accidental freeze your terminal by using **Ctrl+S**, simply undo this with the unfreeze **Ctrl+Q**.

**Ctrl+A** moves you to the beginning of the line while **Ctrl+E** moves you to the end.

You can run multiple commands in one single command by using the “**;**” to separate them. For example **Command1; Command2; Command3.** Or use **&&** if you only want the next command to run when the first one is successful.

#### Expert Tip

Did you know that you can edit text files with Linux commands using SSH? Instead of editing a file locally from your computer and later uploading it via FTP, you can edit the file instantly inside your account using either vim or nano commands.

Conclusion
----------

Basic Linux commands help users execute tasks easily and effectively. It might take a while to remember some of the basic commands, but nothing is impossible with lots of practice.

In the end, knowing and mastering these basic Linux commands will be undoubtedly beneficial for your management of your Linux desktop or [VPS solutions](/vps-hosting). Good luck!

#### Other Useful Linux Commands to Learn

[How to Use Sed Command to Read Files](/docs/how-to-use-linux-sed-command-examples/)  
[How to Use Curl Command for Data Transfer](/docs/curl-command-with-examples-linux/)  
[How to Perform DNS Lookup With Dig Command](/docs/how-to-use-the-dig-command-in-linux/)  
[How to Use Time Command in Linux](/docs/linux-time-command/)  
[How to Use Scp Command for File Transfer](/docs/using-scp-command-to-transfer-files/)  
[How to Use Linux Watch Command](/docs/linux-watch-command/)  
[How to Use Shutdown Command](/docs/linux-shutdown-command/)  
[How to Use Tee Command to Write and Display to a File](/docs/linux-tee-command-with-examples/)  
[How to Find File Type With File Command in Linux](/docs/linux-file-command/)  
[How to List Services in Linux](/docs/manage-and-list-services-in-linux/)  
[How to Use Rsync for File Transfer and Synchronization](/docs/how-to-use-rsync)  
[How to Change a User Password in Linux](/docs/how-to-change-password-in-linux/)  
[How to Create a Symbolic Link With ln Command](/docs/how-to-create-symbolic-links-in-linux/)
