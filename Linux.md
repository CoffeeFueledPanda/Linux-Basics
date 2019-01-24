[TOC]



## Distros:

### Ubuntu

Good old Ubuntu, clear and probably the most stable.

### CentOS

Is the same as Redhat, but free, without license exchanging only some icons and logos for different ones.





## Tools:

### PuTTY

• Is used mostly as a Windows kinda thing.

• Port is usually ‘22’ unless given otherwise from the network admin.

• Uses either the IP adress or server name to connect.

• To exit from terminal simply type ‘exit’.

• To connect through a command prompt use the following command “ssh servername”

• If your login ‘name’ is different from your ‘login name’ then type the following “ssh adminuser@servername”





## Common Directories:

**/ :** “Root” top of the system hierarchy.

**/bin** : Binaries and other executable programs.

**/etc** : System configuration files.

**/home** : Home directories, for each user account.

**/opt** : Optional or third party software.

**/tmp** : Temporary space, typically cleared on reboot.

**/usr** : User related programs.

**/var** : Variable data, most notably log files.





## Comprehensive Directory Listing:

**/boot** : Files needed to boot the operating system.

**/cdrom** : Mount point for CD-ROMs.

**/cgroup** : Controls Groups hierarchy.

**/dev** : Device files, typically controlled by the operating system and the system administrators.



## Basic Linux Commands:

**ls** - List directory contents.

**cd** - Changes the current directory.

**pwd** - Displays the present working directory.

**cat** - Concatenates and displays files.

**echo** - Display arguments to the screen.

**man** - Displays the online manual.

**exit** - Exits the shell or your current session.

**clear** - Clears the screen.



## Navigating Man Pages:

**Enter** - Move down one line.

**Space** - Move down one page.

**g** - Move to the top of the page.

**G** - Move to the bottom of the page.

**q** - Quit.

**man -k search_term** - Allows you to search the man pages.



## Directory Shortcuts:

**.**  : This directory.

**..**  : The parent directory.

**cd** - : Change to the previous directory.

To execute a command/file or script in your current directory use “ **cd ./name**"



## Creating and Removing Directories:

**mkdir [-p] directory** - Create a directory

**rmdir [-p] directory** - Remove a directory.

**rm -rf directory** - Recursively removes directory.

• [**-p]** is not needed, but it’s the parent directory command.

**rmdir** only removes empty directories, to remove a full directory and it’s contents use “**rm -rf**”.

**!!!**  *Note: After removing something using the above commands, you'll no longer be able to retrieve them, use this at your own risk*.  **!!!**



## Decoding ls -l Output:

**$ ls -l**

​	**-rw-rw-r-- 1 rick users 10400 Sep 27 09:30 funnydata.data**

Permission: **-rw-rw-r--**

Number of links: **1**

Owner name: **rick**

Group name: **users**

Number of bytes in the file: **10400**

Last modification time: **Sep 27 09:30**

File name: **funnydata.data**





