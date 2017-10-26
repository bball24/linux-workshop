# linux-workshop

This introduction will be a brief intro on how to use Linux. Linux is an operating system that powers many devices that range from webservers to cell phones.

## File Structure
In Linux the file system is structred as shown

![Linux File System](https://github.com/ucrcyber/linux-workshop/blob/master/img/linux-filesystem.png)

```/```
That is the root of the file system

```/etc```
Contains system wide configurations

```/usr```
Contains system installed files such as programs like vim

```/var```
Contains variable data such as logs

```/home```
Contains user directories


## Navigating the file system
Knowing how to navigate around the Linux filesystem is a basic but critical skill.

The following are a couple of critical commands for navigating around.

* ``` ls ```
* ``` cd ```
* ``` pwd ```

### ls
This command will allow you to list all files and directories in your current working directory

### cd
This command will allow  you to change your directory

### pwd
This command will return what your current working directory is

## Processes
* ``` ps ```
* ``` top ```
* ```kill```

### ps
This will list processes that are running
Running ```ps -u $user``` will allow you to see what process belong to a certain user

### top
This will list the process tree for the entire OS

### kill
Does exactly as the name implies and kills a process

```kill $(pidof $process_name)```
Will kill all instances of 



## Getting system info
* ```ifconfig```
* ```lspci```
* ```lscpu```
* ```lsmod```
* ```uname -r```
* ``` w ```
* ``` cat /etc/*releases```
### ifconfig
Displays and allows control of network interfaces
### lspci
This will list pci devices
### lscpu
This will list cpu info
### lsmod             
This will list kernel modules
### uname
This will list a variety of system info ie kernel version
###  w                                                  
This will list who is logged in
###  cat /etc/*releases
Specific distribution will be displayed

## Viewing, creating, and editing files
* ```vim```
* ```less```
* ```cat```
* ```tail```
* ```rm```
* ```mkdir```
* ```touch```

## SSH
* ```ssh user@hostname ```

## Useful tools
* ```grep```
* ```tmux```
* ```awk```
* ```sed```
* ```ping```
* ```netstat```


## Man pages
If you don't know the arguments or how to use a command just read the man pages

Example
```man ls```
will display the arguments and some info on the ```ls``` command
